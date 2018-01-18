---
TOCTitle: Mantendo o banco de dados de log
Title: Mantendo o banco de dados de log
ms:assetid: 'de55058b-0d1a-4997-8a45-e14678ddd13f'
ms:contentKeyID: 18123790
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747691(v=WS.10)'
---

Mantendo o banco de dados de log
================================

As entradas de log também incluem cópias de licenças emitidas para diversas operações do RSM, como o registro de usuários e a atribuição de licenças de uso. No pior dos cenários — em que cada entrada de log é um registro bem-sucedido de usuário ou uma tentativa bem-sucedida de adquirir uma licença de uso — cada entrada de log adicionará cerca de 200 KB ao tamanho do banco de dados de log.

Por exemplo, suponha que um email protegido pelo RMS foi enviado a todos os 50.000 funcionários de uma empresa e que cada funcionário o abriu. Se cada um dos funcionários abrir esse email ao longo de um dia, o banco de dados de log crescerá cerca de 10 GB. É possível configurar o serviço ouvinte para não registrar os dados XrML atuais, o que reduziria a quantidade de informações registradas.

Considere a criação de scripts para arquivar as informações mais antigas do banco de dados de log em um banco de dados secundário. Exemplos de scripts de log encontram-se no RMS Toolkit, que está disponível para download grátis no [site da Microsoft](http://go.microsoft.com/fwlink/?linkid=26724) (http://go.microsoft.com/fwlink/?LinkId=26724).

Variáveis que afetam o crescimento do banco de dados de log
-----------------------------------------------------------

A previsão do tamanho de um banco de dados de log depende do ambiente. Numerosas entradas de "inicialização" no log podem ser previstas, entre as quais:

-   Registro de servidor RMS
-   Registro de usuário (uma solicitação exclusiva para cada computador usado por cada usuário)
-   Solicitações automatizadas de usuário para certificados de publicação offline

O volume de entradas no banco de dados de log após as primeiras entradas de inicialização relaciona-se com a emissão de licenças de uso para conteúdo protegido. Diversas condições afetam o crescimento desse banco de dados:

-   Requisito de uma nova licença de uso toda vez que um usuário acessar conteúdo protegido. Esse não é o método padrão para documentos protegidos, mas é uma configuração opcional. Se você optar por implementar esse requisito, os bancos de dados crescerão com maior rapidez.
-   Número esperado de emails protegidos enviados a cada pessoa todos os dias.
-   Número esperado de usuários exclusivos que lerão esses emails protegidos.
-   Número esperado de documentos do Microsoft Office 2003 (Word, PowerPoint e Excel) protegidos produzidos por cada pessoa todos os dias.
-   Destinatários esperados dos documentos protegidos.

O tamanho inicial do banco de dados de log será de cerca de 1,7 MB, incluindo a solicitação de um certificado pelo servidor RMS. Toda vez que um novo usuário se registra, ele obtém um certificado de conta de direitos (RAC) e um certificado de licenciante para cliente (CLC). Essas duas ações são registradas, e as duas juntas respondem pelo aumento de 0,06 MB do banco de dados. Toda vez que um usuário adquire com êxito uma licença para conteúdo protegido, o banco de dados cresce em 0,19 MB.

Para avaliar como essa estimativa funciona, considere uma organização com 5.000 usuários que implanta o RMS para uso geral. Cada usuário tem um computador, e a organização usa dois servidores RMS. Após a implantação, cada usuário, em média, cria um email protegido pelo RMS por dia, o qual é enviado para cinco outros usuários. Cada usuário também cria um documento protegido pelo RMS por dia, o qual é acessado por três outros usuários. A tabela a seguir estima o crescimento do banco de dados de log devido a essas atividades.

###  

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Ação</th>
<th style="border:1px solid black;" >Crescimento do log</th>
<th style="border:1px solid black;" >Tamanho cumulativo do log</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">O servidor RMS é configurado com êxito</td>
<td style="border:1px solid black;">1,7 MB</td>
<td style="border:1px solid black;">1,7 MB</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Registro de 5.000 funcionários (5.000*0,06)</td>
<td style="border:1px solid black;">300 MB</td>
<td style="border:1px solid black;">301,7 MB</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Emails protegidos acessados (25.000*0,19)</td>
<td style="border:1px solid black;">4.750 MB</td>
<td style="border:1px solid black;">5.051,7 MB</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Documentos protegidos acessados (15.000*0,19)</td>
<td style="border:1px solid black;">2.850 MB</td>
<td style="border:1px solid black;">7.901,7 MB</td>
</tr>
</tbody>
</table>
  
Portanto, após o registro o banco de dados de log tem um tamanho estático de cerca de 300 MB. Todavia, neste exemplo o crescimento diário é de 7,6 GB — perto do limite de 8 GB da instalação padrão do Enfileiramento de Mensagens. Se o banco de dados de log se tornasse indisponível por mais de um dia, as entradas de log começariam a se perder.
  
Controlando o tamanho do banco de dados de log  
----------------------------------------------
  
O plano de implantação precisa incluir um método de gerenciamento do banco de dados de log. A seguir são apresentadas as abordagens mais comuns.
  
-   **Remover e arquivar**  
    Este método envolve o uso de scripts SQL Server para arquivar informações selecionadas do banco de dados de log em um banco de dados secundário quando as entradas atingirem uma determinada idade. Também envolve a filtragem de informações irrelevantes do banco de dados, para não haver desperdício de espaço.  
-   **Limitar as informações registradas**  
    O banco de dados de log é composto de três tabelas principais. Uma delas é **DRMS\_Log\_Filter**, que identifica os campos da tabela mestre que devem ser registrados quando a filtragem de log está habilitada.  
    As entradas de tabela ativadas/desativadas indicam os campos da tabela mestre que estão atualmente registrados pelo serviço ouvinte de log do servidor RMS. Dois desses campos (relacionados ao XrML) já foram definidos como 0 para desabilitar o log, uma vez que eles respondem por cerca de 99% do tamanho de cada linha de solicitação de licença.  
    Outra tabela do banco de dados **DRMS\_Config\_ServerName\_Port**, chamada **DRMS\_ClusterPolicies**, contém um **PolicyName** de **LoggingFiltering**. **LoggingFiltering** está desabilitado por padrão. Se você alterasse o valor de **LoggingFiltering** para 1 e reinicializasse o Serviço ouvinte de log, o crescimento diário do banco de dados no exemplo fornecido antes cairia de 7,6 GB por dia para cerca de 160 MB por dia.  
-   **Mover o banco de dados de log**  
    Outra opção de gerenciamento do crescimento de um banco de dados de log é simplesmente movê-lo para um servidor com espaço de disco. O banco de dados de log pode existir em um servidor de banco de dados diferente do banco de dados de configuração. Para mover o banco de dados para um servidor diferente, siga estas etapas:  
    1.  Pare o serviço ouvinte de log em cada servidor RMS.  
    2.  Copie o banco de dados (ou crie um novo) em um servidor diferente.  
    3.  Edite o banco de dados **DRMS\_Config\_ServerName\_Port** do RMS selecionando a tabela **DRMS\_ClusterPolicies** e editando os valores de **LoggingDatabaseName** (nome do servidor de banco de dados) e **LoggingDatabaseServer** (nome do banco de dados).  
    4.  Reinicialize o IIS executando IISRESET.exe na linha de comando.
