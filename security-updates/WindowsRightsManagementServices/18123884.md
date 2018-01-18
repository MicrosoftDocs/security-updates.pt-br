---
TOCTitle: Serviço de certificação de conta do RMS
Title: Serviço de certificação de conta do RMS
ms:assetid: 'fb294969-850e-44b4-8f6a-ca5d5cec1bf1'
ms:contentKeyID: 18123884
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747802(v=WS.10)'
---

Serviço de certificação de conta do RMS
=======================================

O serviço de certificação de conta só é executado no cluster raiz. O serviço de certificação de conta cria certificados de conta de direitos, os quais associam contas de usuário a computadores específicos. Um certificado de conta de direitos permite que um usuário publique ou consuma conteúdo protegido por direitos enquanto utiliza um computador específico.

O arquivo do aplicativo do serviço de certificação de conta, Certification.asmx, está localizado no diretório virtual de certificação que está no IIS.

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
