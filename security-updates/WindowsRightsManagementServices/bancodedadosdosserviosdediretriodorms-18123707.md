---
TOCTitle: Banco de dados dos serviços de diretório do RMS
Title: Banco de dados dos serviços de diretório do RMS
ms:assetid: '6f6b8586-5d17-4a40-94a3-4dc738195301'
ms:contentKeyID: 18123707
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747617(v=WS.10)'
---

Banco de dados dos serviços de diretório do RMS
===============================================

O servidor de banco de dados hospeda o banco de dados dos serviços de diretório, que contém informações sobre usuários, identificadores (como endereços de email), SID (identificação de segurança), participação de grupo e identificadores alternativos. Essas informações são obtidas nas consultas LDAP feitas ao catálogo global do Active Directory pelo serviço de licenciamento do RMS. Para obter mais informações sobre esse processo e sua finalidade, consulte "[Cache do Active Directory do RMS](https://technet.microsoft.com/c721a2eb-2fe9-4346-b426-3cc169b97265)", mais adiante neste tema.

O grupo de serviço do RMS tem permissões de execução nos procedimentos armazenados que estão no banco de dados de serviços de diretório.

A tabela a seguir lista os atributos do Active Directory que são armazenados nas tabelas do banco de dados de serviços do diretório.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Tabela</th>
<th style="border:1px solid black;" >Atributo</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">GroupAliases</td>
<td style="border:1px solid black;"><ul>
<li>GroupName: o alias do grupo<br />
<br />
</li>
<li>GroupID: o identificador exclusivo deste grupo<br />
<br />
</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupIdentifiers</td>
<td style="border:1px solid black;"><ul>
<li>GroupDN: o nome distinto do Active Directory para este grupo<br />
<br />
</li>
<li>GroupID: o identificador exclusivo deste grupo<br />
<br />
</li>
<li>Vencimento: a data e a hora de vencimento das informações armazenadas para este grupo<br />
<br />
</li>
</ul></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupMembership</td>
<td style="border:1px solid black;"><ul>
<li>GroupID: o identificador exclusivo deste grupo<br />
<br />
</li>
<li>ParentID: o identificador exclusivo do grupo do qual este grupo é um membro<br />
<br />
</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PrincipalAliases</td>
<td style="border:1px solid black;"><ul>
<li>PrincipalName: um nome de alias para a entidade<br />
<br />
</li>
<li>PrincipalID: o identificador exclusivo desta entidade<br />
<br />
</li>
</ul></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PrincipalIdentifiers</td>
<td style="border:1px solid black;"><ul>
<li>PrincipalID: o identificador exclusivo desta entidade<br />
<br />
</li>
<li>Vencimento: a data e a hora de vencimento das informações armazenadas para esta entidade<br />
<br />
</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PrincipalMembership</td>
<td style="border:1px solid black;">Cada linha desta tabela inclui o identificador exclusivo de uma entidade e o identificador exclusivo do grupo que é um membro dela.
<ul>
<li>PrincipalID: o identificador exclusivo desta entidade<br />
<br />
</li>
<li>ParentID: o identificador exclusivo de um grupo do qual esta entidade é membro<br />
<br />
</li>
</ul></td>
</tr>
</tbody>
</table>
