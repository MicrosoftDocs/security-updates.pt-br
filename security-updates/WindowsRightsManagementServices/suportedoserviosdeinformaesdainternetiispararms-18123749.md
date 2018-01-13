---
TOCTitle: 'Suporte do Serviços de Informações da Internet (IIS) para RMS'
Title: 'Suporte do Serviços de Informações da Internet (IIS) para RMS'
ms:assetid: 'bd4dc69f-1e4e-4e95-9ae2-c925d8a14d4c'
ms:contentKeyID: 18123749
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747649(v=WS.10)'
---

Suporte do Serviços de Informações da Internet (IIS) para RMS
=============================================================

Os principais serviços do RMS são fornecidos por um conjunto de serviços ASP .NET na Web. Esses serviços da Web são executados no IIS (Serviços de Informações da Internet) da Microsoft®. Durante o processo de configuração do servidor, o RMS configura diretórios virtuais no IIS. Os arquivos do aplicativo dos serviços da Web são instalados nos diretórios virtuais.

Durante a configuração do servidor, é possível selecionar o site no qual você deseja configurar diretórios virtuais de uma lista de sites existentes no servidor. Antes de configurar um servidor, talvez você deseje criar um site especial para o RMS. Caso o faça, você poderá configurar restrições de autenticação e de acesso específicas para a sua implantação de RMS.

Por padrão, os arquivos dos serviços da Web e os diretórios virtuais são protegidos por listas de controle de acesso condicional para impedir acesso não autorizado a esses recursos. As entradas de controle de acesso desses itens são as seguintes:

-   O grupo de administradores tem controle total.
-   O sistema local tem controle total.
-   O grupo de serviço RMS tem permissões de leitura e de execução.
-   Convidados e usuários têm permissões para ler e executar, listar conteúdo da pasta e ler.
-   O acesso anônimo não é permitido.

A tabela a seguir lista os diretórios virtuais que são criados no IIS e os serviços que estão instalados nos diretórios virtuais.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Diretório virtual</th>
<th style="border:1px solid black;" >Serviço</th>
<th style="border:1px solid black;" >Arquivo de serviço na Web</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">_wmcs</td>
<td style="border:1px solid black;">Este é o diretório virtual de administração do cluster do RMS.</td>
<td style="border:1px solid black;">Não aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Certification</td>
<td style="border:1px solid black;">Este diretório virtual contém os serviços que suportam a certificação do RMS.</td>
<td style="border:1px solid black;">Não aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Proxy de ativação</td>
<td style="border:1px solid black;">Activation.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Certificação de conta</td>
<td style="border:1px solid black;">Certification.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Pré-certificação</td>
<td style="border:1px solid black;">Precertification.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Localizador de serviço</td>
<td style="border:1px solid black;">ServiceLocator.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Servidor</td>
<td style="border:1px solid black;">Server.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Certificação do servidor</td>
<td style="border:1px solid black;">ServerCertification.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Certificação do dispositivo móvel</td>
<td style="border:1px solid black;">MobileDeviceCertfication.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Registro</td>
<td style="border:1px solid black;">SubEnrollService.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Licenciamento.</td>
<td style="border:1px solid black;">Este diretório virtual contém os serviços que suportam o licenciamento do RMS.</td>
<td style="border:1px solid black;">Não aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Licenciamento.</td>
<td style="border:1px solid black;">License.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Publicação</td>
<td style="border:1px solid black;">Publish.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Servidor</td>
<td style="border:1px solid black;">Server.asmx</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Localizador de serviço</td>
<td style="border:1px solid black;">ServiceLocator.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Admin</td>
<td style="border:1px solid black;">Este diretório virtual contém os serviços que suportam a administração do RMS.</td>
<td style="border:1px solid black;">Não aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Administração</td>
<td style="border:1px solid black;">AdminSvc.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DrmRemote</td>
<td style="border:1px solid black;">Interface do .NET Remoting.</td>
<td style="border:1px solid black;">Não aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DirectoryServices</td>
<td style="border:1px solid black;">Este é um subdiretório de DrmRemote</td>
<td style="border:1px solid black;">Não aplicável</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747649.note(WS.10).gif)Observação                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| O serviço de administração tem restrições mais rígidas do que outros serviços da Web porque as interfaces fornecidas permitem configurar o RMS. Por isso, os membros do grupo de usuários não podem obter acesso ao serviço de administração. Além disso, a filtragem de IP é habilitada para conceder acesso somente ao computador local. O diretório virtual DirectoryServices não concede acesso a usuários convidados. O serviço localizador de serviço também concede controle total à conta de serviço de rede. A fim de configurar um servidor de licenciamento, você deve alterar as entradas de controle de acesso padrão para permitir o acesso do administrador do RMS. |
