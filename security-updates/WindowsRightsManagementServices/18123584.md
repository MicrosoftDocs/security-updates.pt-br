---
TOCTitle: Serviço de publicação do RMS
Title: Serviço de publicação do RMS
ms:assetid: '4c0c8fe3-695c-4b2c-a2d3-cab9b52bbb25'
ms:contentKeyID: 18123584
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720267(v=WS.10)'
---

Serviço de publicação do RMS
============================

O serviço de publicação, que emite licenças de publicação, é executado no cluster raiz do RMS e em qualquer cluster somente de licenciamento. As licenças de publicação definem a diretiva pela qual licenças de uso podem ser entregues.

O arquivo do aplicativo do serviço de publicação, Publish.asmx, está localizado no diretório virtual de licenciamento que está no IIS.

A lista de controle de acesso padrão desse serviço é mostrada na seguinte tabela:

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Usuário ou grupo</th>
<th style="border:1px solid black;" >Permissão padrão</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Administradores</td>
<td style="border:1px solid black;">Controle Total</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Grupo de Serviço RMS</td>
<td style="border:1px solid black;">Ler e Executar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SYSTEM</td>
<td style="border:1px solid black;">Controle Total</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Usuários</td>
<td style="border:1px solid black;">Ler e Executar</td>
</tr>
</tbody>
</table>
