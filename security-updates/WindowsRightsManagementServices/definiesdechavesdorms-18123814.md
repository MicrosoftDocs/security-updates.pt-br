---
TOCTitle: Definições de chaves do RMS
Title: Definições de chaves do RMS
ms:assetid: 'b052305c-1db7-434a-bad9-26d704156776'
ms:contentKeyID: 18123814
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747729(v=WS.10)'
---

Definições de chaves do RMS
===========================

A tabela a seguir lista as chaves usadas em um sistema RMS.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Chave</th>
<th style="border:1px solid black;" >Uso</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Chaves do servidor</td>
<td style="border:1px solid black;"><strong>Chave pública</strong>
Criptografa a chave de conteúdo que está em uma licença de publicação, de modo que apenas o servidor RMS possa recuperar a chave de conteúdo, e emite licenças de uso em relação a essa licença de publicação.
<strong>Chave particular</strong>
Assina todos os certificados e licenças que são emitidas pelo servidor.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Chaves da máquina</td>
<td style="border:1px solid black;"><strong>Chave pública</strong>
Criptografa uma chave particular de um certificado de conta de direitos.
<strong>Chave particular</strong>
Descriptografa um certificado de conta de direitos.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Chaves de licenciante para cliente</td>
<td style="border:1px solid black;"><strong>Chave pública</strong>
Criptografa a chave simétrica do conteúdo nas licenças de publicação que ele emite.
<strong>Chave particular</strong>
Assina licenças de publicação que são emitidas localmente enquanto o usuário não está conectado à rede.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Chaves do usuário</td>
<td style="border:1px solid black;"><strong>Chave pública</strong>
Criptografa a chave de conteúdo que está em uma licença de uso, de modo que apenas um determinado usuário possa consumir o conteúdo protegido pelo RMS usando essa licença.
<strong>Chave particular</strong>
Permite que um usuário consuma o conteúdo protegido pelo RMS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Chaves de conteúdo</td>
<td style="border:1px solid black;">Criptografa conteúdo protegido pelo RMS quando o autor o publica.</td>
</tr>
</tbody>
</table>
