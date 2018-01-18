---
TOCTitle: Serviço de administração do RMS
Title: Serviço de administração do RMS
ms:assetid: '4bd3e142-f0f6-40e9-a160-deab28ce5b88'
ms:contentKeyID: 18123663
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747560(v=WS.10)'
---

Serviço de administração do RMS
===============================

O serviço de administração é executado no cluster raiz do RMS e em clusters somente de licenciamento. O serviço de administração hospeda o site de Administração e permite que você gerencie o RMS.

O arquivo do aplicativo do serviço de administração (Default.aspx) está localizado no diretório virtual Admin (*site\_do\_RMS*\\\_wmcs\\Admin), onde *site\_do\_RMS* é substituído pelo nome do site no qual você configurou o RMS.

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
</tbody>
</table>
