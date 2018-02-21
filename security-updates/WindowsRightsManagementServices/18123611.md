---
TOCTitle: Revogação nos modelos de diretiva de direitos
Title: Revogação nos modelos de diretiva de direitos
ms:assetid: '287c5b92-fcb5-4295-9c2b-4e37e643beb2'
ms:contentKeyID: 18123611
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720226(v=WS.10)'
---

Revogação nos modelos de diretiva de direitos
=============================================

Condições de revogação são especificadas nos modelos de diretiva de direitos. Os valores da condição de revogação que você digita em um modelo de diretiva de direitos são capturados em uma marca XrML REFRESH na licença de publicação emitida em relação àquele modelo. A licença de uso resultante emitida pelo servidor também conterá a marca REFRESH.

A tabela a seguir lista os parâmetros que estão na marca REFRESH.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Parâmetro</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">ID</td>
<td style="border:1px solid black;">A identificação da lista de revogação.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ADDRESS</td>
<td style="border:1px solid black;">A URL ou caminho UNC onde a lista de revogação pode ser obtida.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PUBLICKEY</td>
<td style="border:1px solid black;">A chave pública do emissor da lista de revogação. Essa chave pública corresponde à chave particular que foi usada para assinar a lista de revogação.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">INTERVALTIME</td>
<td style="border:1px solid black;">O tempo máximo da lista de revogação, em dias. Se a lista de revogação armazenada em cache for mais antiga do que o permitido por INTERVALTIME, o cliente do RMS obterá a lista de revogação mais recente na URL listada em ADDRESS. Isso garante que uma lista de revogação atualizada seja usada.</td>
</tr>
</tbody>
</table>
  
Para obter mais informações sobre como criar modelos de diretiva de direitos, consulte "Criando e modificando modelos de diretiva de direitos" em "Operando um servidor RMS", nesta coleção de documentos.
