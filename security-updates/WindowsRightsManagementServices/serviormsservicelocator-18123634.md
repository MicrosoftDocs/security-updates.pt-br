---
TOCTitle: Serviço RMS Service Locator
Title: Serviço RMS Service Locator
ms:assetid: '6f410cc9-5d5b-4df3-bf4f-7b13811eb52f'
ms:contentKeyID: 18123634
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747548(v=WS.10)'
---

Serviço RMS Service Locator
===========================

O serviço Service Locator é executado nos clusters raiz e somente de licenciamento do RMS. Ele fornece a URL da conexão de serviço do cluster para o Active Directory, de modo que ela possa ser descoberta por clientes habilitados para RMS.

O arquivo do aplicativo do serviço localizador de serviço, ServiceLocator.asmx, está localizado nos diretórios virtuais Certification e Licensing que estão no IIS.

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
