---
TOCTitle: 'Atualizando a implantação com o RMS Service Pack 1 (SP1)'
Title: 'Atualizando a implantação com o RMS Service Pack 1 (SP1)'
ms:assetid: 'a562c4b0-15df-46db-9d61-24db74871cfa'
ms:contentKeyID: 18123845
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747714(v=WS.10)'
---

Atualizando a implantação com o RMS Service Pack 1 (SP1)
========================================================

Esta seção fornece informações para ajudá-lo a instalar o Microsoft ® Windows® Rights Management Services (RMS) Service Pack 1 (SP1) em uma organização com uma implantação existente do RMS. Somente organizações que já implantaram o RMS precisam atualizar a implantação com o RMS SP1. As organizações que estão implantando o RMS pela primeira vez podem implantar o RMS com SP1, seguindo as diretrizes de Planejando uma Implantação do RMS e Implantando um sistema RMS nesta coleção de documentos.

Você pode instalar o RMS SP1 sem remover a instalação existente do RMS. O programa de instalação para o RMS SP1 detecta que o RMS está instalado e inclui os recursos e configurações adicionais, conforme a necessidade.

**Neste tema**

-   [Preparando a atualização do RMS SP1](#bkmk_1)
-   [Executando a atualização do RMS SP1](#bkmk_2)
-   [Atualizando clusters](#bkmk_3)
-   [Atualizando clientes RMS](#bkmk_4)
-   [Interoperabilidade com o RMS versão 1.0](#bkmk_5)
-   [Removendo o RMS com SP1](#bkmk_6)

<span id="BKMK_1"></span>
Preparando a atualização do RMS SP1
-----------------------------------

A atualização do RMS SP1 foi projetada para permitir que você continue a executar as operações do RMS sem interrupção. No entanto, antes de atualizar os servidores RMS, é recomendável fazer o seguinte:

-   Fazer backup do banco de dados de configuração e da chave particular do RMS. Para obter mais informações consulte "Backups do sistema para RMS" na seção "Planejando uma implantação do RMS" desta coleção de documentos.
-   Verifique se possui a senha da chave particular do RMS.
-   Faça backup do banco de dados de log se desejar manter estatísticas registradas em log anteriormente.
-   Verifique se tem as mais recentes atualizações críticas e de segurança para o sistema operacional instalado nos clientes e servidores. Para verificar se você tem todas as atualizações críticas e de segurança, clique em **Iniciar** e em **Windows Update** e siga as instruções na tela..

<span id="BKMK_2"></span>
Executando a atualização do RMS SP1
-----------------------------------

Quando o Assistente para Instalação do RMS SP1 detecta a instalação do RMS, apenas adiciona novos arquivos ou substitui arquivos que precisam ser alterados para o RMS SP1. Se você já está executando o RMS com êxito, não precisa reprovisionar ou executar configurações adicionais após instalar o RMS SP1 para continuar a executar o RMS.

<span id="BKMK_3"></span>
Atualizando clusters
--------------------

Se tiver instalado o RMS em uma configuração de cluster, planeje a atualização dos clusters para minimizar o impacto sobre a atualização da instalação. Considere as seguintes recomendações ao determinar a melhor forma de aplicar o RMS SP1 na organização:

-   Como prática recomendada, instale o RMS SP1 em uma parte de um cluster de cada vez, para que a atualização do cluster possa ser mais previsível e haja menos possibilidade de degradação no serviço durante a atualização.
-   Se houver vários clusters RMS, atualize os clusters raiz de certificação primeiro e, depois, atualize os clusters de licenciamento com sub-registro.
-   Se estiver usando a expansão de grupo entre florestas, você poderá atualizar os clusters nas florestas de maneira independente, sem afetar a capacidade dos servidores RMS de expandir associações de grupo entre florestas.
-   O RMS SP1 e o servidor RMS versão 1.0 podem coexistir e interoperar.
-   O pacote de instalação do RMS SP1 também pode ser usado para instalar uma nova versão do RMS SP1 em um servidor; ele não exige que o RMS versão 1.0 seja instalado.

<span id="BKMK_4"></span>
Atualizando clientes RMS
------------------------

Um novo cliente do RMS está incluído no RMS com SP1. O pacote de instalação do cliente do RMS SP1 também pode ser usado para instalar uma nova versão do cliente do RMS SP1 em um computador; ele não exige que o cliente do RMS versão 1.0 seja instalado. O cliente do RMS SP1 inclui um recurso de compatibilidade com versões anteriores para permitir seu uso com aplicativos habilitados para RMS que exigem o RMS versão 1.0.

Esse novo cliente do RMS fornece os seguintes recursos:

-   O cliente não precisa mais se conectar à Microsoft pela Internet e baixar um cofre.
-   Se você instalar o cliente do RMS usando uma diretiva de grupo ou SMS, não serão necessários privilégios de administrador para a instalação.
-   O cliente do RMS SP1 inclui um novo cofre de servidor (também conhecido como processador de segurança de servidor) que pode ser usado para habilitar no RMS serviços Web ou aplicativos de servidor, como Windows SharePoint® Services e Exchange Server 2003, para permitir que o serviço consuma e redistribua conteúdo protegido pelo RMS. Esse cofre foi projetado para oferecer elevado desempenho e escalabilidade quando usado em aplicativos de servidor confiáveis
-   O cliente do RMS utiliza algoritmos de criptografia certificados FIPS 140-2. Isso permite que o cliente seja implantado em uma organização compatível com FIPS.

<span id="BKMK_5"></span>
Interoperabilidade com o RMS versão 1.0
---------------------------------------

Como o RMS SP1 fornece muitos aperfeiçoamentos e melhorias de desempenho, você deve instalá-lo após concluir os testes. Embora servidores e clientes do RMS que executam o RMS SP1 sejam totalmente interoperáveis com servidores e clientes do RMS que não executam o RMS SP1, observe as seguintes diferenças na forma como eles funcionam em um ambiente misto:

-   Somente servidores que executam o RMS SP1 são compatíveis com inscrição offline.
-   Apenas clientes que executam o RMS SP1 e posterior são ativados automaticamente.
-   A tabela a seguir mostra a funcionalidade para a qual há suporte em ambientes mistos:

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Versão do Servidor do RMS</th>
<th style="border:1px solid black;" >Recursos com suporte em clientes com a v1</th>
<th style="border:1px solid black;" >Recursos com suporte em clientes com SP1</th>
<th style="border:1px solid black;" >Recursos com suporte em ambientes de clientes mistos (v1 e SP1)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">1.0</td>
<td style="border:1px solid black;">Todos os recursos anteriores.
Sem inscrição offline do servidor. O servidor deve se inscrever pela Internet.
Sem clientes ativados automaticamente.</td>
<td style="border:1px solid black;">Todos os recursos anteriores.
Sem inscrição offline do servidor.
Clientes ativados automaticamente.</td>
<td style="border:1px solid black;">Todos os recursos anteriores.
Os clientes com SP1 são ativados automaticamente.
Os clientes da v1 devem ser ativados pela Internet.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SP1</td>
<td style="border:1px solid black;">Todos os recursos anteriores.
Inscrição offline do servidor.
Sem clientes ativados automaticamente.</td>
<td style="border:1px solid black;">Todos os recursos do SP1.
Inscrição offline do servidor.
Clientes ativados automaticamente.
Cofre de servidor.</td>
<td style="border:1px solid black;">Todos os recursos anteriores e os recursos do SP1.
Inscrição offline do servidor.
Os clientes com SP1 são ativados automaticamente.
Os clientes da v1 devem ser ativados pela Internet.</td>
</tr>
</tbody>
</table>
 

<span id="BKMK_6"></span>
Removendo o RMS com SP1
-----------------------

Para retornar o servidor RMS à configuração anterior após instalar o RMS SP1, use **Adicionar ou Remover Programas** no **Painel de Controle** para remover o RMS SP1.

**Observação**   Se tiver feito backup do banco de dados de configuração antes de instalar o RMS SP1, você poderá restaurar o backup para erradicar completamente todas as alterações introduzidas pelo RMS SP1. Caso não tenha feito backup do banco de dados de configuração, talvez você possa usar o banco de dados de configuração da instalação do RMS SP1 com a instalação restaurada do RMS. A instalação restaurada do RMS ignorará os campos adicionais que a instalação do RMS SP1 adiciona ao banco de dados de configuração porque não os utiliza.
