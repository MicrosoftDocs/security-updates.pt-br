---
TOCTitle: Serviço de licenciamento do RMS
Title: Serviço de licenciamento do RMS
ms:assetid: '5cad1baf-0304-4e82-b62d-83a4aac2140b'
ms:contentKeyID: 18123604
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720278(v=WS.10)'
---

Serviço de licenciamento do RMS
===============================

O serviço de licenciamento, que emite licenças de uso, é executado no cluster raiz do RMS e em qualquer cluster somente de licenciamento. As licenças de uso permitem que os usuários consumam conteúdo protegido por direitos.

O arquivo do aplicativo do serviço de licenciamento, License.asmx, está localizado no diretório virtual de licenciamento que está no IIS.


> [!NOTE]  
> Você pode implantar um cluster somente de licenciamento à parte para descarregar as solicitações de licenciamento provenientes do cluster raiz. Também é possível implantar um servidor ou cluster de licença para um departamento, por exemplo, para permitir que o departamento a estabeleça suas próprias diretivas de direitos. Para obter mais informações sobre essas considerações, consulte "Identificando os principais componentes" em "RMS: planejamento e arquitetura " nesta coleção de documentos.

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
