---
TOCTitle: Notas de versão do Windows Rights Management Services com Service Pack 2
Title: Notas de versão do Windows Rights Management Services com Service Pack 2
ms:assetid: '78067886-681f-49a6-b43d-bfd08a369b69'
ms:contentKeyID: 18123730
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747637(v=WS.10)'
---

Notas de versão do Windows Rights Management Services com Service Pack 2
========================================================================

*Data de lançamento: dezembro de 2006*

Antes de iniciar
----------------

Leia as informações a seguir antes de instalar o Microsoft® Windows® Rights Management Services (RMS) com Service Pack 2 (SP2). As informações contidas nestas notas de versão aplicam-se ao servidor do RMS com SP2 e não ao cliente do RMS. Para obter informações sobre clientes do RMS, consulte a página sobre o RMS em [http://go.microsoft.com/fwlink/?LinkId=68637](http://go.microsoft.com/fwlink/?linkid=68637).

#### Requisitos do sistema

Os requisitos de hardware para executar o RMS com SP2 estão listados na tabela a seguir.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Requisito</th>
<th style="border:1px solid black;" >Recomendação</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Computador com um processador Pentium III (800 MHz ou superior)</td>
<td style="border:1px solid black;">Computador com dois processadores Pentium 4 (1500 MHz ou superior)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">256 MB de RAM</td>
<td style="border:1px solid black;">512 MB de RAM</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">20 GB de espaço livre no disco rígido</td>
<td style="border:1px solid black;">40 GB de espaço livre no disco rígido</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747637.note(WS.10).gif)Observação                                                                                |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| O servidor do RMS com SP2 foi desenvolvido para computadores de 32 bits. Se instalado em um computador de 64 bits, ele será executado no modo de emulação. |
  
Os requisitos de software para servidores que executam o RMS com SP2 estão listados na tabela a seguir.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Componente</th>
<th style="border:1px solid black;" >Requisito</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Sistema operacional</td>
<td style="border:1px solid black;">Microsoft Windows Server® 2003, exceto Web Edition, para o RMS com SP2.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Rights Management Services com SP2</td>
<td style="border:1px solid black;">O RMS com Service Pack 1 (SP1) deve estar instalado para que você possa atualizar para o RMS com SP2. O cliente do RMS com SP2 não tem esse requisito.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Sistema de arquivos</td>
<td style="border:1px solid black;">Recomenda-se o sistema de arquivos NTFS.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Pré-requisitos de componentes</td>
<td style="border:1px solid black;"><ul>
<li>Enfileiramento de Mensagens (também conhecido como MSMQ) com a integração ao serviço de diretório do Active Directory® habilitada.<br />
<br />
</li>
<li>IIS (Serviços de Informações da Internet) com ASP.NET habilitado.<br />
<br />
</li>
<li>Microsoft .NET Framework 1.1<br />
<br />
</li>
</ul></td>
</tr>
</tbody>
</table>
 

| ![](images/Cc747637.note(WS.10).gif)Observação                                                                                                                      |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Se você configurar o RMS com SP2 para permitir a administração remota, o computador que se conectar ao serviço de Administração do RMS com SP2 deverá usar o Internet Explorer 6.0 ou posterior. |

Os requisitos de infra-estrutura para servidores que executam o RMS com SP2 estão listados na tabela a seguir.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Componente</th>
<th style="border:1px solid black;" >Requisitos</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Serviços de diretório</td>
<td style="border:1px solid black;">O Active Directory em controladores de domínio que executam o Windows Server 2000 com Service Pack 3 (SP3) ou posterior, no mesmo domínio em que o RMS está instalado. Todos os usuários e grupos que usam o RMS para adquirir licenças e publicar conteúdo devem ter um endereço de email configurado no Active Directory.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Servidor de banco de dados</td>
<td style="border:1px solid black;">O RMS com SP2 exige um banco de dados e procedimentos armazenados para executar operações. Você pode usar o Microsoft SQL Server™ 2000 com SP3a ou posterior ou o Microsoft SQL Server 2005. Para testes ou outras implantações em um único computador, pode ser usado o Microsoft SQL Server Desktop Engine (MSDE 2000) Versão A ou o Microsoft SQL Server 2005 Express Edition.</td>
</tr>
</tbody>
</table>
  
O RMS foi desenvolvido para e testado com servidores de banco de dados que executam o Microsoft SQL Server 2000 e o Microsoft SQL Server 2005. O RMS pode ser executado em outros servidores de banco de dados se eles atenderem aos seguintes critérios:
  
-   Oferecer suporte a interfaces ADO.NET fornecidas pelo Microsoft .NET Framework 1.1.  
-   Ser compatível com Transact-SQL, a linguagem SQL utilizada pelo Microsoft SQL Server, porque os scripts de inicialização e os procedimentos armazenados do RMS usam Transact-SQL.  
-   Oferecer suporte a todas as extensões específicas do Microsoft SQL Server.  
-   Responder às chamadas de método do namespace System.Data.SqlClient do .NET Framework.  
-   Fornecer a respectiva funcionalidade do namespace System.Data.SqlClient.  
-   Usar o Modo de Autenticação do Windows.
  
Para saber se o servidor de banco de dados atende aos critérios acima, entre em contato com o fornecedor do banco de dados pertinente.
  
A tabela a seguir lista os direitos e as permissões de usuário exigidos para realizar diferentes atividades com o RMS.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Atividade</th>
<th style="border:1px solid black;" >Requisitos de conta</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Instalar o RMS</td>
<td style="border:1px solid black;">Usuário do domínio com credenciais de administrador no computador local</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Provisionar um cluster raiz do RMS</td>
<td style="border:1px solid black;">Usuário do domínio com credenciais de administrador do computador local e permissão para consulta e gravação no Active Directory</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Provisionar um cluster somente de licenciamento do RMS</td>
<td style="border:1px solid black;">Usuário do domínio com credenciais de administrador do computador local e permissão para consulta no Active Directory</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Provisionar ao usar um novo banco de dados de configuração</td>
<td style="border:1px solid black;">Usuário do domínio com credenciais de administrador do computador local e permissão para leitura, gravação e criação no computador que executa o SQL Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Provisionar ao usar um banco de dados de configuração existente</td>
<td style="border:1px solid black;">Usuário do domínio com credenciais de administrador do computador local e permissão para leitura e gravação no computador que executa o servidor de banco de dados</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Administrar o RMS</td>
<td style="border:1px solid black;">Usuário do domínio com credenciais de administrador no computador local</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747637.note(WS.10).gif)Observação                                                                                                                                                                                                                     |  
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Para obter mais informações sobre a configuração do Windows Server, o Active Directory, o Enfileiramento de Mensagens, o IIS e sistemas de arquivos, consulte o Windows Server 2003 TechCenter em [http://go.microsoft.com/fwlink/?LinkId=78135](http://go.microsoft.com/fwlink/?linkid=78135). |
  
Se você estiver usando o RMS em uma implantação de cluster, deverá atender aos itens listados na tabela a seguir.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Condição</th>
<th style="border:1px solid black;" >Recomendação</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Muitos desktops que usarão o RMS</td>
<td style="border:1px solid black;">Use o SMS (Systems Management Server) ou a Diretiva de Grupo para instalar o cliente do RMS com SP2.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Grande número de solicitações do cliente</td>
<td style="border:1px solid black;">Use um servidor de balanceamento de carga, o serviço Balanceamento de Carga de Rede no sistema operacional Windows Server ou o balanceamento de carga de hardware para distribuir as solicitações no cluster.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Dois adaptadores de rede que utilizem endereçamento IP virtual para atender a solicitações da extranet e intranet</td>
<td style="border:1px solid black;">Verifique se algum registro do DNS (sistema de nome de domínio) que expõe o endereço IP virtual na extranet também expõe o endereço na intranet.</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747637.Important(WS.10).gif)Importante                                                                                                                                                                                                                                                                                                                                                                                                                                       |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Se o registro do DNS não for feito para a intranet, as solicitações de licença dos clientes internos não serão bem-sucedidas. Se você não conseguir modificar as configurações do DNS, a tabela de hosts de cada servidor do cluster poderá ser modificada para mapear a URL do cluster para o endereço IP virtual do cluster. O registro do DNS precisa ser feito antes do provisionamento do RMS. Se você já tiver provisionado o serviço, deverá remover o RMS do servidor e repetir o processo de provisionamento. |
  
#### Clientes com suporte nesta versão
  
O cliente do RMS sem service pack, o cliente do RMS com SP1 ou o cliente do RMS com SP2 pode ser instalado em qualquer computador que execute o Microsoft Windows 2000, Windows XP e Windows Server 2003. As versões anteriores de sistemas operacionais Windows não têm suporte nesta versão.
  
| ![](images/Cc747637.Caution(WS.10).gif)Cuidado                                                                        |  
|----------------------------------------------------------------------------------------------------------------------------------------------------|  
| Se você estiver usando o cliente do RMS sem service pack, o cliente não poderá usar a publicação online para um servidor RMS com SP1 ou posterior. |
  
Alterações na funcionalidade  
----------------------------
  
O RMS com SP2 tem vários novos recursos:
  
-   [Expansão de grupo avançada entre florestas](#bkmk_cif1)  
-   [Alterações de log de banco de dados](#bkmk_cif2)  
-   [Lotes de servidor maiores](#bkmk_cif3)  
-   [Compatibilidade com o Microsoft SQL Server 2005](#bkmk_cif4)
  
<span id="BKMK_CIF1"></span>
#### Expansão de grupo avançada entre florestas
  
#### O que esse recurso faz?
  
No RMS, a expansão de grupo entre florestas facilita a capacidade do RMS de expandir a associação de grupo Universal do Active Directory em outra floresta, na qual as associações de grupo não são replicadas entre duas florestas. Quando um usuário de uma floresta envia conteúdo protegido por direitos para um usuário de outra floresta, o RMS entra em um período de descoberta, quando verifica se o usuário tem acesso ao conteúdo. Esse processo de verificação é feito utilizando-se uma consulta LDAP de uma floresta para outra para localizar o ponto de conexão de serviço (SCP) do RMS da floresta. Quando o SCP da floresta remota é detectado, a conta de serviço do RMS envia uma solicitação ao pipeline de expansão de grupo. A solicitação pergunta à floresta remota se um usuário é membro de um grupo.
  
#### A quem esse recurso se aplica?
  
Esse novo recurso será de interesse para clientes do RMS que usam um ambiente Active Directory de várias florestas cujas associações de grupo Universal não são replicadas entre florestas.
  
#### Por que essa alteração é importante?
  
O novo protocolo de expansão de relação de confiança entre florestas vai melhorar a confiabilidade para os clientes que estão implantando um ambiente Active Directory de várias florestas.
  
#### O que funciona de maneira diferente?
  
Antes do RMS com SP2, a expansão de grupo entre florestas era feita através de chamadas remotas do .NET. Nesta versão, o protocolo de expansão de grupo entre florestas foi alterado para um serviço Web do ASP.NET que usa solicitações SOAP/HTTP para o pipeline de expansão de grupo de relação de confiança entre florestas.
  
| ![](images/Cc747637.note(WS.10).gif)Observação                                                                                                                                                                                                            |  
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Para fins de compatibilidade com versões anteriores, ainda há suporte para chamadas remotas do .NET no RMS com SP2. Entretanto, para tirar o máximo proveito do novo protocolo de expansão de grupo entre florestas, todos os clusters do RMS devem executar pelo menos o RMS com SP2. |
  
#### Que configurações foram adicionadas ou alteradas no RMS com SP2?
  
Por padrão, o novo pipeline de expansão de grupo do RMS tem as mais seguras configurações no RMS com SP2, ao qual somente os grupos Serviço e Administradores do RMS locais têm acesso. Para conceder acesso a uma conta, é preciso alterar a lista de controle de acesso no pipeline de expansão de grupo disponível em wwwroot\\\_wmcs\\GroupExpansion\\GroupExpansion.asmx.
  
| ![](images/Cc747637.Important(WS.10).gif)Importante                                                                                                                                                                                                                                                                                                                                              |  
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Verifique se a conta de serviço do RMS em cada floresta do Active Directory tem acesso ao pipeline de expansão de grupo em cada servidor do RMS do cluster. Se as contas não tiverem acesso, a expansão de grupo não será bem-sucedida. Se preferir, você pode criar a mesma conta em cada floresta e atribuir a mesma senha a cada conta. Nesse caso, você só teria de adicionar uma conta ao pipeline de expansão de grupo. |
  
Novos eventos foram adicionados ao RMS com SP2 para informá-lo sobre mensagens de problema que não chegam ao serviço de Enfileiramento de Mensagens. Esses novos logs de eventos incluem eventos que avisam quando uma mensagem não pode ser assinada digitalmente ou se não é possível validar a mensagem. Alguns exemplos de problemas de validação incluem mensagens incorretas, um hash ou uma assinatura faltando ou até mesmo um hash ou uma assinatura incorretos.
  
<span id="BKMK_CIF2"></span>
#### Alterações no log de banco de dados
  
#### O que esse recurso faz?
  
O RMS usa um serviço de ouvinte de log que envia toda a comunicação do RMS para o banco de dados de log utilizando o Enfileiramento de Mensagens. O cluster do RMS envia as mensagens para o serviço de Enfileiramento de Mensagens, e o serviço de ouvinte de log as recupera da fila do Enfileiramento de Mensagens e as grava no banco de dados de log.
  
#### A quem esse recurso se aplica?
  
Esse recurso se aplica aos usuários atuais do RMS que utilizam o serviço de ouvinte de log do RMS e aos novos usuários do RMS com SP2 que estão considerando a possibilidade de usar tal serviço do RMS.
  
#### Por que essa alteração é importante?
  
Em versões anteriores do RMS, a fila de registro em log do RMS era protegida pelo uso de listas de controle de acesso, mas a autenticação não estava habilitada. Sem a autenticação, um usuário mal-intencionado poderia gravar mensagens erradas na fila de registro em log do RMS.
  
#### O que funciona de maneira diferente?
  
No RMS com SP2, uma autenticação adicional é realizada nas mensagens transmitidas pelo cluster do RMS utilizando o Enfileiramento de Mensagens. Além das listas de controle de acesso que impedem o acesso não autorizado à fila de mensagens, a fila do Enfileiramento de Mensagens também é protegida por um mecanismo de verificação de autenticidade de mensagens. Quando uma mensagem é enviada ao serviço de Enfileiramento de Mensagens, os pipelines do RMS geram um hash dela e a assinam digitalmente usando a chave particular do cluster do RMS. O Serviço de Ouvinte de Log primeiro calcula seu próprio hash da mensagem e o compara ao hash incluído na mensagem. Se os hashes coincidirem, o Serviço de Ouvinte de Log verifica a assinatura usando a chave pública do cluster e o hash da mensagem. Se os hashes coincidirem e a assinatura for verificada, a mensagem é enviada para o banco de dados de log. Se as etapas de validação não forem bem-sucedidas, a mensagem é excluída permanentemente da fila do Enfileiramento de Mensagens e um aviso de evento é gravado no log Aplicativo de Visualizar Eventos.
  
#### Que configurações foram adicionadas ou alteradas no RMS com SP2?
  
Novos eventos foram adicionados ao RMS com SP2 para indicar quando mensagens de problema não chegaram à fila do Enfileiramento de Mensagens. Esses novos eventos são gravados no log Aplicativo e incluem mensagens que não podem ser assinadas digitalmente ou as assinaturas digitais das mensagens que não podem ser validadas. Alguns exemplos de problemas de validação incluem mensagens incorretas, um hash ou uma assinatura faltando ou até mesmo um hash ou uma assinatura incorretos.
  
<span id="BKMK_CIF3"></span>
#### Lotes de servidor maiores
  
#### O que esse recurso faz?
  
No RMS, os lotes aumentam o desempenho, pois permitem que várias solicitações de licença sejam enviadas ao cluster do RMS como uma única solicitação, em vez de criar uma solicitação para cada licença.
  
#### A quem esse recurso se aplica?
  
O suporte para lotes de servidor maiores será interessante para os aplicativos habilitados para RMS que precisam adquirir de uma só vez várias licenças de conteúdo protegido por direitos.
  
#### Por que essa alteração é importante?
  
Os lotes do RMS permitem que uma única solicitação seja emitida para o pipeline AcquireLicense do RMS a fim de obter licenças de Uso para diversos RACs (certificados de contas de direitos) em vez de uma ou mais Licenças de Publicação. Sem um tamanho de lote maior que 1, o aplicativo habilitado para RMS teria de solicitar individualmente uma licença de Uso para cada usuário.
  
#### O que funciona de maneira diferente?
  
Nas versões do RMS anteriores ao RMS com SP2, o cluster do RMS tinha suporte para um tamanho máximo de lote de 1. Se o tamanho máximo fosse definido como um número maior que 1, o cluster o ignorava. No RMS com SP2, esse tamanho máximo de lote pode ser de até 100.
  
| ![](images/Cc747637.note(WS.10).gif)Observação       |  
|-----------------------------------------------------------------------------------|  
| Apenas o pipeline AcquireLicense do RMS inclui suporte para solicitações em lote. |
  
Os relatórios de erros foram aprimorados no RMS com SP2 para incluir as solicitações em lote. Por exemplo, se você enviar um lote de dez solicitações e a segunda ou terceira solicitação não for bem-sucedida, será gravado no log de eventos um evento para cada falha.
  
<span id="BKMK_CIF4"></span>
#### Compatibilidade com Microsoft SQL Server 2005
  
#### O que esse recurso faz?
  
No RMS com SP2, é possível usar o Microsoft SQL Server 2005 como o servidor de banco de dados para dar suporte aos bancos de dados de configuração e de log do RMS sem a necessidade de fazer mais configurações.
  
#### A quem esse recurso se aplica?
  
O suporte para Microsoft SQL Server 2005 do RMS com SP2 será de interesse para os clientes do RMS que desejam usar o Microsoft SQL Server 2005 como banco de dados do RMS.
  
#### Por que essa alteração é importante?
  
Nas versões anteriores do RMS, os tipos de dados de alguns dos parâmetros utilizados na tabela sysmessages eram incompatíveis com a especificação de formato do Microsoft SQL Server 2005. Para obter mais informações, consulte o artigo 913372 da Base de Dados de Conhecimento Microsoft em [http://go.microsoft.com/fwlink/?LinkId=68638](http://go.microsoft.com/fwlink/?linkid=68638).
  
#### O que funciona de maneira diferente?
  
Nas versões do RMS anteriores ao RMS com SP2, as instruções SQL RAISERROR eram usadas para notificar o usuário do RMS de que havia ocorrido um erro. A instrução RAISERROR consulta a tabela sysmessages para recuperar as mensagens de erro do RMS armazenadas nela. O RMS com SP2 usa outra técnica para propagar erros de SQL para que não haja mais dependência da tabela sysmessages.
  
| ![](images/Cc747637.note(WS.10).gif)Observação                                                                                                                                                                                                                     |  
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Se você estiver atualizando do RMS com SP1 para o RMS com SP2, a tabela sysmessages não será mais consultada em busca de mensagens de erro, mas as mensagens propriamente ditas permanecerão na tabela. Uma instalação limpa do RMS com SP2 não adicionará novas entradas à tabela sysmessages. |
  
Problemas conhecidos  
--------------------
  
As próximas seções abordam problemas conhecidos desta versão do RMS.
  
#### O arquivo da Ajuda ainda faz referência ao RMS com Service Pack 1
  
O arquivo da Ajuda incluído na instalação do RMS com SP2 ainda faz referência ao RMS com SP1. Para obter informações sobre o RMS com SP2, consulte o tópico sobre o RMS em [http://go.microsoft.com/fwlink/?LinkId=68637](http://go.microsoft.com/fwlink/?linkid=68637).
  
#### O Windows Update não instala o cliente do RMS com SP2 em computadores baseados em x64 ou em Itanium
  
Se o cliente do RMS ou do RMS com SP1 estiver instalado em um computador baseado em x64 e você tentar atualizá-lo para o cliente do RMS com SP2 (x64) a partir do Windows Update, a instalação falhará. Embora os clientes do RMS anteriores, criados para sistemas de 32 bits, funcionassem em computadores baseados em x64, não é possível atualizá-los para o cliente do RMS com SP2 (x64). Primeiro, você deve desinstalar o cliente anterior para, então, iniciar a atualização novamente. O Windows Update detecta a versão do sistema operacional e oferece o cliente apropriado do RMS com SP2. O mesmo é válido para computadores baseados em Itanium.
  
#### O reprovisionamento sempre falha ao iniciar o serviço de ouvinte de log
  
Quando o provisionamento do cluster é removido, o serviço de ouvinte de log não deixa o serviço no estado Parado. Para parar o serviço completamente, você deve reiniciar o computador.
  
#### Não é possível remover domínios de publicação confiáveis não baseados em software
  
Depois de importar um domínio de publicação confiável com implementação de chave particular não baseada em software, não é possível excluí-lo. A importação de uma chave particular não baseada em software não deve ser feita usando o Console de Administração do Windows Rights Management Services. Entre em contato com o provedor de hardware apropriado para obter instruções sobre como exportar e importar a chave particular.
  
#### O Microsoft .NET Framework 2.0 altera as raízes virtuais do IIS quando instalado no servidor do RMS
  
O RMS com SP2 utiliza o mapeamento de script do ASP.NET incluído no .NET Framework versão 1.1. O mapeamento fornecido pelas versões posteriores não é compatível com o RMS com SP2. Entretanto, as duas versões podem coexistir sem interferência em outros aplicativos dependentes. Se o servidor tiver o .NET Framework 1.1 e o .NET Framework 2.0 ou posterior instalado, é possível que o cluster do RMS não funcione corretamente, mesmo que a instalação e o provisionamento do RMS com SP2 aparentemente tenham sido concluídos com êxito. O motivo é que as raízes virtuais do RMS precisam ser registradas no mapa de script do ASP.NET versão 1.1 e não na versão 2.0. Para registrar as raízes virtuais do RMS no mapa de script do ASP.NET versão 1.1, execute o seguinte comando no prompt de comando:
  
**%windir%\\Microsoft.NET\\Framework\\v1.1.4322&gt;aspnet\_regiis.exe -s W3SVC/1/ROOT/\_wmcs**
  
A execução desse comando registrará as raízes virtuais do RMS corretamente e permitirá que o RMS com SP2 seja executado no servidor.
  
#### Associações de grupo poderão estar faltando se for usado o nível funcional Nativo do Windows 2000 no Active Directory
  
Quando o RMS é implantando em um ambiente onde os níveis de infra-estrutura do Active Directory foram elevados para o nível funcional nativo do Windows 2000, o RMS pode não ser capaz de ler o atributo memberOf de objetos do Active Directory ao tentar expandir a associação de grupo das listas de distribuição ocultas. Para que o RMS possa ler o atributo memberOf, a conta de Serviço do RMS deve usar uma conta de domínio que seja membro do grupo Acesso Compatível com Versões Anteriores ao Windows 2000. Para obter mais informações, consulte o artigo 812841 da Base de Dados de Conhecimento Microsoft [http://go.microsoft.com/fwlink/?LinkId=78152](http://go.microsoft.com/fwlink/?linkid=78152).
  
#### O serviço de ouvinte de log envia mensagens do Enfileiramento de Mensagens para a Fila de Mensagens Mortas quando o banco de dados não pode ser acessado
  
Há situações (por exemplo, banco de dados inativo, problemas de conectividade de rede, etc.) em que o serviço de ouvinte de log não pode acessar o banco de dados. Nesse caso, as mensagens são enviadas para uma Fila de Mensagens Mortas. A única maneira de recuperar essas mensagens (ou seja, enviá-las para o banco de dados de log) é usar a ferramenta de Recuperação de Fila do RMS fornecida com o Kit de Ferramentas de Administração do RMS. Para baixar o Kit de Ferramentas de Administração do RMS, consulte [http://go.microsoft.com/fwlink/?LinkId=33841](http://go.microsoft.com/fwlink/?linkid=33841).
  
| ![](images/Cc747637.note(WS.10).gif)Observação                                                                                                                                                                                    |  
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Os parâmetros Recover e RecoverandPurge foram removidos de LogRecoveryCmd. Isso assegurará que todas as mensagens sejam encaminhadas de volta pelo serviço de Enfileiramento de Mensagens e autenticadas antes de serem enviadas para o banco de dados de log. |
  
#### É preciso atualizar para o RMS com SP2 antes de atualizar para o Microsoft SQL Server 2005
  
Ao atualizar para o RMS com SP2 e do Microsoft SQL Server 2000 para o Microsoft SQL Server 2005, atualize primeiro o RMS. Isso evitará quaisquer problemas de compatibilidade na atualização do Microsoft SQL Server.
  
#### Ocorre uma falha no provisionamento do RMS com SP2 em sites cujos nomes incluem um apóstrofo (')
  
Quando você tentar provisionar o RMS com SP2 em um site cujo nome inclui um apóstrofo ('), ocorrerá uma falha no processo de provisionamento e será exibida a mensagem de erro **Parâmetro inválido**. Para provisionar o RMS com SP2 no site, remova o apóstrofo do nome do site.
  
#### Habilitando o ASP.NET versão 1.1 em servidores que executam uma versão de 64 bits do Windows Server 2003
  
O tópico sobre requisitos do sistema da Ajuda do RMS explica como instalar o .NET Framework 1.1 e habilitar o ASP.NET 1.1 após a instalação do IIS (Serviços de Informações da Internet). Entretanto, se você instalar o .NET Framework 1.1 antes do IIS, o ASP.NET 1.1 não será listado nas extensões de serviços Web, e o procedimento documentado não será útil. Se o IIS tiver sido instalado após o .NET Framework 1.1, execute o seguinte comando no prompt de comando para habilitar o ASP.NET:
  
**%SystemRoot%\\Microsoft.NET\\Framework\\v1.1.4322\\aspnet\_regiis.exe -i –enable**
  
Ao usar uma versão do .NET Framework posterior à 1.1, substitua **-i** por **-ir** no comando para não ter de reconfigurar nenhum mapa de script existente do IIS.
  
#### A conta de serviço do RMS da floresta remota deve ser adicionada ao pipeline de expansão de grupo local
  
Foi corrigida uma questão de segurança que remove BUILTIN\\users da lista de controle de acesso no pipeline de expansão de grupo. Isso pode interromper a expansão de grupo entre cenários de florestas. Para resolver o problema, execute as seguintes etapas:
  
**Adicione a conta de serviço do RMS à floresta remota**  
1.  Em Floresta1, em que Floresta1 é o cluster raiz do RMS da primeira floresta, vá para inetpub\\wwwroot\\\_wmcs.
  
2.  Clique com o botão direito do mouse na pasta **GroupExpansion** e selecione **Propriedades**.
  
3.  Na janela **Propriedades de GroupExpansion**, clique na guia **Segurança**, adicione a entrada para *Floresta2\\RmsServiceAccount* (por exemplo, rmil31\\rmsvc), em que Floresta2 é o cluster raiz do RMS na segunda floresta.
  
4.  Clique em **OK**.
  
5.  Clique em **Executar**, digite **iisreset** e clique em**OK**.
  
#### A atualização do .NET Framework pode resultar em perda de dados
  
Se o .NET Framework (CLR) versão 1.1 for atualizado após a instalação e o provisionamento do RMS, as raízes virtuais serão definidas para usar o .NET Framework versão 2.0. Se isso acontecer, nenhuma informação será registrada no banco de dados de log. Isso resultará em perda de dados. Execute um dos seguintes procedimentos:
  
-   Atualize o .NET Framework antes de instalar e provisionar o RMS.  
-   Redefina as raízes virtuais para usar a versão 1.1 depois que o .NET Framework for atualizado.
  
Alterações na documentação desta versão  
---------------------------------------
  
Esta é a lista de tópicos que foram alterados nesta versão:
  
-   Confiar em certificados de conta de direitos baseados no Passport ([http://go.microsoft.com/fwlink/?LinkId=70369](http://go.microsoft.com/fwlink/?linkid=70369))  
-   Requisitos de software para o RMS ([http://go.microsoft.com/fwlink/?LinkId=70371](http://go.microsoft.com/fwlink/?linkid=70371))  
-   Como implantar o cliente do RMS ([http://go.microsoft.com/fwlink/?LinkId=70373](http://go.microsoft.com/fwlink/?linkid=70373))  
-   Instalação a partir do prompt de comando do RMS ([http://go.microsoft.com/fwlink/?LinkId=70374](http://go.microsoft.com/fwlink/?linkid=70374))  
-   Principais tabelas do banco de dados de configuração do RMS ([http://go.microsoft.com/fwlink/?LinkId=70375](http://go.microsoft.com/fwlink/?linkid=70375))  
-   Tabelas de certificação do banco de dados de configuração do RMS ([http://go.microsoft.com/fwlink/?LinkId=70376](http://go.microsoft.com/fwlink/?linkid=70376))  
-   Tabelas do banco de dados de log do RMS ([http://go.microsoft.com/fwlink/?LinkId=70377](http://go.microsoft.com/fwlink/?linkid=70377))  
-   Avaliando os requisitos de dimensionamento ([http://go.microsoft.com/fwlink/?LinkId=70378](http://go.microsoft.com/fwlink/?linkid=70378))  
-   Protegendo a implantação do RMS ([http://go.microsoft.com/fwlink/?LinkId=70379](http://go.microsoft.com/fwlink/?linkid=70379))  
-   Habilitando o serviço de descomissionamento ([http://go.microsoft.com/fwlink/?LinkId=70380](http://go.microsoft.com/fwlink/?linkid=70380))  
-   Planejando para usuários externos do RMS [http://go.microsoft.com/fwlink/?LinkId=70381](http://go.microsoft.com/fwlink/?linkid=70381))  
-   Habilitando o suporte do servidor do RMS para dispositivos móveis e serviços de servidor ([http://go.microsoft.com/fwlink/?LinkId=70382](http://go.microsoft.com/fwlink/?linkid=70382))
  
#### Direitos autorais
  
*As informações contidas neste documento representam a visão que a Microsoft Corporation tem atualmente sobre as questões discutidas até a data da publicação. Como a Microsoft deve responder a condições de mercado em constante mudança, essas informações não devem ser interpretadas como um compromisso da parte da Microsoft, nem a Microsoft pode garantir a exatidão de qualquer informação apresentada após a data da publicação.*
  
*Este documento se destina apenas a fins informativos. A MICROSOFT NÃO OFERECE NENHUMA GARANTIA EXPRESSA, IMPLÍCITA OU LEGAL REFERENTE ÀS INFORMAÇÕES DESTE DOCUMENTO.*
  
*O cumprimento de todas as leis de direitos autorais aplicáveis é de responsabilidade do usuário. Sem limitar os direitos protegidos pela lei de direitos autorais, nenhuma parte deste documento pode ser reproduzida, armazenada ou introduzida em sistemas de recuperação e nem transmitida de qualquer forma ou por qualquer meio (eletrônico, mecânico, por fotocópia, gravação ou de outra forma), nem para qualquer propósito, sem a permissão expressa, por escrito, da Microsoft Corporation.*
  
*A Microsoft pode ter patentes, solicitações de patentes, marcas comerciais, direitos autorais ou outros direitos de propriedade intelectual que tratam do assunto deste documento. Exceto quando expressamente declarado em um contrato de licença por escrito da Microsoft, o fornecimento deste documento não confere ao usuário nenhuma licença sobre essas patentes, marcas comerciais, direitos autorais ou outras propriedades intelectuais.*
  
*Salvo indicação em contrário, as empresas, organizações, produtos, nomes de domínio, endereços de email, logotipos, pessoas, locais e eventos de exemplo aqui citados são fictícios e nenhuma associação com nenhuma empresa, organização, produto, nome de domínio, endereço de email, logotipo, pessoa, local ou evento real foi pretendida ou deve ser inferida.*
  
*© 2006 Microsoft Corporation. Todos os direitos reservados.*
  
*Active Directory, Microsoft, MS-DOS, Visual Studio, Windows, Windows Server, SQL Server e Windows NT são marcas registradas ou marcas comerciais da Microsoft Corporation nos Estados Unidos e/ou em outros países.*
  
*Os nomes reais das empresas e dos produtos aqui mencionados podem ser marcas comerciais de seus respectivos proprietários.*
