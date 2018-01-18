---
TOCTitle: Serviço Servidor do RMS
Title: Serviço Servidor do RMS
ms:assetid: '772d0a89-c9fb-4430-9434-38cd5add1e86'
ms:contentKeyID: 18123647
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747566(v=WS.10)'
---

Serviço Servidor do RMS
=======================

O serviço Servidor só é executado no cluster raiz do RMS. O serviço Servidor expõe uma solicitação feita por um cliente usando a publicação online para recuperar um certificado de licenciante para servidor.

O arquivo do aplicativo do serviço de servidor, Server.asmx, está localizado no diretório virtual de certificação que está no IIS.

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
