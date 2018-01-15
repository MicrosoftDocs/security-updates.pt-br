---
TOCTitle: 'Serviço de sub-registro do RMS'
Title: 'Serviço de sub-registro do RMS'
ms:assetid: '6b05e71c-5e7d-467c-9e13-35ac14d3718a'
ms:contentKeyID: 18123627
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720289(v=WS.10)'
---

Serviço de sub-registro do RMS
==============================

O serviço de sub-registro só é executado no cluster raiz do RMS. Ele responde a solicitações enviadas durante a configuração por servidores de clusters somente de licenciamento para certificados de licenciante para servidor.

O arquivo do aplicativo do serviço de sub-registro, SubEnrollService.asmx, está localizado no diretório virtual de certificação *Site\_do\_RMS*\\\_wmcs\\Certification\\, onde *Site\_do\_RMS* é substituído pelo nome do site no qual você configurou o RMS.

Por padrão, o acesso a esse serviço é restrito à conta SYSTEM local. Para configurar e registrar um servidor subordinado em um cluster somente de licenciamento, a conta de usuário do administrador do servidor de licenciamento deve ser adicionada à DACL (lista de controle de acesso discricionário) do arquivo SubEnrollService.asmx com privilégios de controle total.

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
<td style="border:1px solid black;">SYSTEM</td>
<td style="border:1px solid black;">Controle Total</td>
</tr>
</tbody>
</table>
