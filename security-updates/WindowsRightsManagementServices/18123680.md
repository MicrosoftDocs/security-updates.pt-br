---
TOCTitle: Alterando as configurações de cache do Active Directory
Title: Alterando as configurações de cache do Active Directory
ms:assetid: '8789a7a5-2065-4fae-9104-e0a70f1f2fb6'
ms:contentKeyID: 18123680
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747586(v=WS.10)'
---

Alterando as configurações de cache do Active Directory
=======================================================

As configurações no Registro especificam o número de entradas que serão armazenadas no cache do Active Directory. Para aumentar o tempo de resposta para as solicitações do cliente, é possível modificar essas configurações. Para obter mais informações, consulte "Otimizando o desempenho dos serviços de diretório", já mencionado neste tema. Você também pode especificar o período de validade para as informações que estão armazenadas em cache.

Em computadores que executam a versão de 32 bits do Windows Server 2003, a seguinte chave do Registro é o caminho completo da subchave para as entradas em cache:

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0\\DirectoryServices**

Em computadores que executam a versão de 64 bits do Windows Server 2003, a seguinte chave do Registro é o caminho completo da subchave para as entradas em cache:

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0\\DirectoryServices**

A tabela a seguir lista as entradas que controlam o comportamento do cache na memória.

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
<th style="border:1px solid black;" >Nome</th>
<th style="border:1px solid black;" >Tipo</th>
<th style="border:1px solid black;" >Valor padrão</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">PrincipalCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">Número máximo de entidades e seus endereços de email e SIDs que podem ser armazenados em cache.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PrincipalCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">Período de validade de informações de entidades em cache.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupIDCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">Número máximo de grupos e seus endereços de email e SIDs que podem ser armazenados em cache.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupIDCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">Período de validade de informações dos membros do grupo em cache.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupMembershipCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">Número máximo de contatos que são membros de um grupo que pode ser armazenado em cache.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupMembershipCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">Período de validade de informações em cache de contatos que são membros de um grupo.</td>
</tr>
</tbody>
</table>
  
> [!Caution]  
> Editar o Registro incorretamente pode causar sérios danos ao sistema. Antes de alterar o Registro, faça backup dos dados importantes que estão no computador. 
  
> [!Note]  
> As entradas do Registro **PrincipalCacheExpireMinutes**, **GroupIDCacheExpireMinutes**, **GroupMembershipCacheExpireMinutes** e **ContactMembersofGroupCacheExpireMinutes** também controlam o vencimento do cache no cache local do Active Directory, armazenado no banco de dados de serviços de diretório no servidor do seu banco de dados. 
