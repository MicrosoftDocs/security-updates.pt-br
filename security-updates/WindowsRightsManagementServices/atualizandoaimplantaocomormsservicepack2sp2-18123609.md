---
TOCTitle: 'Atualizando a implantação com o RMS Service Pack 2 (SP2)'
Title: 'Atualizando a implantação com o RMS Service Pack 2 (SP2)'
ms:assetid: '27ee06a1-f467-4a6c-b662-45ddb5f8c13e'
ms:contentKeyID: 18123609
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720225(v=WS.10)'
---

Atualizando a implantação com o RMS Service Pack 2 (SP2)
========================================================

Esta seção fornece informações para ajudá-lo a instalar o Microsoft® Windows® Rights Management Services (RMS) com Service Pack 2 (SP2) em uma organização com uma implantação do RMS existente. Somente organizações que já implantaram o RMS precisam atualizar a implantação com o RMS com SP2. As organizações que estão implantando o RMS pela primeira vez podem implantá-lo com SP2 seguindo as diretrizes do tópico sobre planejamento de uma implantação do RMS ([http://go.microsoft.com/fwlink/?LinkId=74999](http://go.microsoft.com/fwlink/?linkid=74999)) e o tópico sobre implantação de um sistema RMS ([http://go.microsoft.com/fwlink/?LinkID=75000](http://go.microsoft.com/fwlink/?linkid=75000)) nesta coleção de documentos.

Você pode instalar o RMS com SP2 sem remover a instalação existente do RMS com SP1. O programa de instalação para o RMS com SP2 detecta que o RMS com SP1 está instalado e inclui os recursos e configurações adicionais, conforme a necessidade.

| ![](images/Cc720225.note(WS.10).gif)Observação                                                                                                                                                                                                                                            |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Não há suporte para um caminho de atualização do servidor RMS sem service pack para o RMS com SP2. Se estiver usando o servidor RMS sem service pack, você deverá atualizar para o RMS com SP1 antes de atualizar para o RMS com SP2. O cliente do RMS pode ser atualizado de qualquer versão anterior do cliente RMS. |

**Neste tema**

-   [Preparando a atualização do RMS com SP2](#bkmk_preparingforsp2update)
-   [Executando a atualização do RMS com SP2](#bkmk_performingsp2update)
-   [Atualizando clusters](#bkmk_updateclusters)
-   [Atualizando clientes RMS](#bkmk_updateclients)
-   [Interoperabilidade com o RMS versão 1.0](#bkmk_interop)
-   [Removendo o RMS com SP2](#bkmk_removingrms)

<span id="bkmk_PreparingForSP2Update"></span>
Preparando a atualização do RMS com SP2
---------------------------------------

A atualização do RMS com SP2 foi projetada para permitir que você continue a executar o RMS sem interrupção. No entanto, antes de atualizar o cluster do RMS, é recomendável fazer o seguinte:

-   Fazer backup do banco de dados de configuração e da chave particular do RMS Para obter mais informações, consulte o tópico sobre backups do sistema para RMS ([http://go.microsoft.com/fwlink/?LinkId=75001](http://go.microsoft.com/fwlink/?linkid=75001)) nesta coleção de documentação.
-   Se estiver usando uma chave particular baseada em software, verifique se tem a senha da chave particular do RMS.
-   Faça backup do banco de dados de log se desejar manter estatísticas registradas em log anteriormente.
-   Verifique se tem as mais recentes atualizações críticas e de segurança para o sistema operacional instalado nos clientes e servidores. Para verificar se você tem todas as atualizações críticas e de segurança, clique em **Iniciar** e em **Windows Update** e siga as instruções na tela..

<span id="bkmk_PerformingSP2Update"></span>
Executando a atualização do RMS com SP2
---------------------------------------

Quando o Assistente para Instalação do Windows Rights Management Services com Service Pack 2 detecta sua instalação do RMS, verifica a instalação atual do RMS com SP1 e apenas adiciona novos arquivos ou substitui arquivos que precisem ser alterados para o RMS com SP2. Se você já está executando o RMS com êxito, não precisa reprovisionar ou executar configurações adicionais após instalar o RMS com SP2 para continuar a executar o RMS.

<span id="bkmk_UpdateClusters"></span>
Atualizando clusters
--------------------

Se tiver instalado o RMS em uma configuração de cluster, planeje a atualização dos clusters para minimizar o impacto sobre a atualização da instalação. Considere as seguintes recomendações ao determinar a melhor forma de aplicar o RMS com SP2 na organização:

-   Como prática recomendada, instale o RMS com SP2 em uma parte de um cluster de cada vez, para que a atualização do cluster possa ser mais previsível e haja menos possibilidade de degradação no serviço durante a atualização.
-   Se houver vários clusters RMS, atualize os clusters raiz de certificação primeiro e, depois, atualize os clusters de licenciamento com sub-registro.
-   Se estiver usando a expansão de grupo entre florestas, você poderá atualizar os clusters nas florestas de maneira independente, sem afetar a capacidade dos servidores RMS de expandir associações de grupo entre florestas.
-   O RMS com SP2, o RMS com SP1 e o servidor RMS versão 1.0 só poderão coexistir e interoperar se estiverem em florestas diferentes do Active Directory. Não é recomendável ter versões diferentes do servidor RMS no mesmo cluster.
-   O pacote de instalação do RMS com SP2 também pode ser usado para instalar uma nova implantação do RMS com SP2 em um servidor; ele não exige que o RMS com SP1 seja instalado.

<span id="bkmk_UpdateClients"></span>
Atualizando clientes RMS
------------------------

Um novo cliente do RMS com SP2 está disponível no Windows Update ou no Centro de Download da Microsoft. O pacote de instalação do cliente do RMS com SP2 também pode ser usado para instalar uma nova versão do cliente do RMS com SP2 em um computador; ele não exige que o cliente do RMS versão 1.0 seja instalado. O cliente do RMS com SP2 inclui um recurso de compatibilidade com versões anteriores para permitir seu uso com aplicativos habilitados para RMS que exigem o RMS versão 1.0.

Para obter mais informações sobre como atualizar e instalar o cliente do RMS, consulte o tópico sobre distribuição do Cliente do RMS ([http://go.microsoft.com/fwlink/?LinkId=75070](http://go.microsoft.com/fwlink/?linkid=75070)).

<span id="bkmk_InterOp"></span>
Interoperabilidade com o RMS versão 1.0
---------------------------------------

Como o RMS com SP2 fornece muitos aperfeiçoamentos e melhorias de desempenho, você deve instalá-lo durante o próximo ciclo de atualização. Embora servidores e clientes do RMS que executam o RMS com SP2 sejam totalmente interoperáveis com servidores e clientes que não executam o RMS com SP2, observe as seguintes diferenças na forma como eles funcionam em um ambiente misto:

-   Somente servidores que executam o RMS com SP1 e posterior são compatíveis com inscrição offline.
-   Apenas clientes que executam o RMS com SP1 e posterior são ativados automaticamente.
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
<th style="border:1px solid black;" >Versão do Servidor RMS</th>
<th style="border:1px solid black;" >Recursos com suporte em clientes da versão 1</th>
<th style="border:1px solid black;" >Recursos com suporte em clientes com SP2</th>
<th style="border:1px solid black;" >Recursos com suporte em ambientes de clientes mistos</th>
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
Os clientes com SP2 são ativados automaticamente.
Os clientes da versão 1 devem ser ativados pela Internet.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SP2</td>
<td style="border:1px solid black;">Todos os recursos anteriores.
Inscrição offline do servidor.
Sem clientes ativados automaticamente.</td>
<td style="border:1px solid black;">Todos os recursos do SP1.
Inscrição offline do servidor.
Clientes ativados automaticamente.
Cofre de servidor.
Suporte incluído para o Microsoft SQL Server™ 2005.</td>
<td style="border:1px solid black;">Todos os recursos anteriores e os recursos do SP2.
Inscrição offline do servidor.
Os clientes com SP2 são ativados automaticamente.
Os clientes da versão 1 devem ser ativados pela Internet.</td>
</tr>
</tbody>
</table>
 

<span id="bkmk_RemovingRMS"></span>
Removendo o RMS com SP2
-----------------------

Para retornar o servidor RMS à configuração anterior após instalar o RMS com SP2, use **Adicionar ou Remover Programas** no **Painel de Controle** para remover o RMS com SP2.
