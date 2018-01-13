---
TOCTitle: Substituindo a descoberta de serviços do Active Directory
Title: Substituindo a descoberta de serviços do Active Directory
ms:assetid: '9d97e7fb-5b05-4853-ad7b-6cc82b9729f0'
ms:contentKeyID: 18123718
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747614(v=WS.10)'
---

Substituindo a descoberta de serviços do Active Directory
=========================================================

Os serviços e clientes do RMS descobrem a localização de serviços procurando primeiro no Registro local. Se determinadas chaves do Registro não tiverem um valor, os serviços e clientes do RMS procurarão o ponto de conexão de serviço (SCP) no Active Directory. Isso significa que você poderá substituir a configuração de descoberta padrão do Active Directory se digitar determinadas chaves no Registro do servidor ou do cliente.

| ![](images/Cc747614.note(WS.10).gif)Observação                                                                                                                  |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Se o cluster raiz do RMS estiver configurado de modo que o SCP não seja publicado no Active Directory, você poderá usar essas chaves para indicar aos clientes do RMS a localização correta. |

Esta seção descreve as entradas do Registro e fornece detalhes sobre como você pode criá-las.

Substituindo a descoberta de serviço para o sub-registro de cluster somente de licenciamento
--------------------------------------------------------------------------------------------

Se você estiver provisionando um cluster somente de licenciamento e desejar que ele faça um sub-registro com um cluster raiz diferente do cluster raiz que implantou na floresta do Active Directory do cluster somente de licenciamento, substitua a descoberta dos serviços de sub-registro e de certificação de conta.

#### Descrições de entradas do Registro

As entradas do Registro a seguir são usadas para substituir os serviços de sub-registro e certificação de conta.

-   **SubEnrollmentURL**. Essa entrada especifica o caminho para o cluster raiz que o servidor de licenciamento usa ao solicitar seu certificado de licenciante para servidor.
-   **GicURL**. Essa entrada especifica o caminho para o serviço de certificação de conta para esse cluster somente de licenciamento.

#### Detalhes da entrada

Em computadores que executam a versão de 32 bits do Windows Server 2003, o caminho completo da subchave do Registro para as entradas de descoberta de serviços para o sub-registro do cluster somente de licenciamento é:

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0**

Em computadores que executam a versão de 64 bits do Windows Server 2003, o caminho completo da subchave do Registro para as entradas de descoberta de serviços para o sub-registro do cluster somente de licenciamento é:

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0**

A tabela a seguir lista as entradas que você pode adicionar para substituir a descoberta de serviços.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Nome</th>
<th style="border:1px solid black;" >Tipo</th>
<th style="border:1px solid black;" >Valor</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SubEnrollmentURL</td>
<td style="border:1px solid black;">Cadeia de caracteres</td>
<td style="border:1px solid black;">http(ou https)://<em>nome_do_servidor</em>/_wmcs/certification/subenrollservice.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GicURL</td>
<td style="border:1px solid black;">Cadeia de caracteres</td>
<td style="border:1px solid black;">http(ou https)://<em>nome_do_servidor</em>/_wmcs/certification/certification.asmx</td>
</tr>
</tbody>
</table>
  
Substituindo a descoberta de serviços do lado cliente para publicação  
---------------------------------------------------------------------
  
Se os usuários publicarem conteúdo de seus computadores, talvez você deseje substituir os locais dos servidores usados para publicação dependendo da topologia usada na empresa. Os locais dos servidores usados para publicação normalmente são descobertos pelo cliente por meio do Active Directory. Se você adicionar as chaves do Registro adequadas nos computadores cliente, os clientes ignorarão esses métodos e, em vez disso, usarão as URLs que especificar no valor da entrada do Registro.
  
| ![](images/Cc747614.note(WS.10).gif)Observação                                                                                                          |  
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| As substituições de cliente listadas nessas seções devem ser criadas como chaves, não como entradas individuais. O valor das chaves deve ser criado na entrada padrão de cada chave. |
  
#### Descrições de chaves do Registro
  
As chaves do registro a seguir podem ser usadas para substituir a descoberta automática do cluster do RMS.
  
-   **Activation**. Essa chave do Registro define a URL do serviço de ativação de computador. Se você estiver executando o cliente do RMS com Service Pack 1 ou posterior, essa entrada do Registro não é mais utilizada.  
-   **EnterprisePublishing**. Essa chave do Registro define a URL de uma instalação do RMS que você deseja que o cliente use para solicitações de licenciamento.  
-   **CloudPublishing**. Essa chave do Registro define a URL do serviço de licenciamento hospedado pela Microsoft que poderá ser usada se o cliente não tiver acesso a uma instalação do RMS, mas tiver acesso à Internet.
  
#### Detalhes da chave
  
O caminho completo da subchave do Registro para entradas de descoberta de serviços no lado cliente para publicação é:
  
**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\MSDRM\\ServiceLocation\\**
  
A tabela a seguir lista as chaves do Registro que você pode adicionar a um computador cliente do RMS para substituir a descoberta de serviços.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Nome</th>
<th style="border:1px solid black;" >Tipo</th>
<th style="border:1px solid black;" >Valor</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Activation</td>
<td style="border:1px solid black;">Cadeia de caracteres</td>
<td style="border:1px solid black;">http(ou https)://<em>nome_do_cluster_do RMS</em>/_wmcs/Certification, em que <em>nome_do_cluster_do_RMS</em> é o nome do cluster do RMS.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">EnterprisePublishing</td>
<td style="border:1px solid black;">Cadeia de caracteres</td>
<td style="border:1px solid black;">http(ou https)://<em>nome_do_cluster_do_RMS</em>/_wmcs/Licensing, em que <em>nome_do_cluster_do_RMS</em> é o nome do cluster do RMS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CloudPublishing</td>
<td style="border:1px solid black;">Cadeia de caracteres</td>
<td style="border:1px solid black;">http(ou https)://<em>nome_do_cluster_FQDN</em>/_wmcs/Licensing, em que <em>nome_do_cluster_FQDN</em> é o nome de domínio totalmente qualificado do cluster do RMS.</td>
</tr>
</tbody>
</table>
  
É recomendável aplicar essas chaves do Registro usando o SMS ou a Diretiva de Grupo para garantir que todos os clientes da empresa usem os servidores de publicação corretos.
  
| ![](images/Cc747614.Caution(WS.10).gif)Cuidado                                                                               |  
|-----------------------------------------------------------------------------------------------------------------------------------------------------------|  
| A edição incorreta do Registro pode causar danos graves ao sistema. Antes de alterar o Registro, faça backup de todos os dados importantes do computador. |
  
Um exemplo do arquivo do Registro (.reg) pode ser usado para importar as chaves do Registro corretas para cada servidor RMS no cluster.
  
**Para importar as chaves do Registro corretas para cada servidor do cluster do RMS**  
1.  Copie o exemplo a seguir de arquivo do Registro para o Bloco de Notas.
  
    `Windows Registry Editor Version 5.00`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation]`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\Activation]`
  
    `@="http://<RMS_cluster_name>/_wmcs/certification"`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\EnterprisePublishing]`
  
    `@="http://<RMS_cluster_name>/_wmcs/licensing"`
  
2.  Substitua &lt;nome\_do\_cluster\_do\_RMS&gt; pelo nome do cluster do RMS.
  
3.  Salve o arquivo com a extensão de nome de arquivo .reg.
  
4.  Clique duas vezes no nome do arquivo no Windows Explorer.
  
5.  Se a caixa de diálogo **Controle de Conta de Usuário** for exibida, confirme se a ação exibida é a desejada e clique em **Continuar**.. Quando for exibido um prompt para perguntar se você deseja adicionar as informações ao Registro, clique em **Sim**.
