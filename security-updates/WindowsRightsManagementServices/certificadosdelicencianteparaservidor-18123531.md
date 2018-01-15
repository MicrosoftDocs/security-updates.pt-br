---
TOCTitle: Certificados de licenciante para servidor
Title: Certificados de licenciante para servidor
ms:assetid: '0b35fbcd-25a9-4587-898d-9a30fd1d3c5b'
ms:contentKeyID: 18123531
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720184(v=WS.10)'
---

Certificados de licenciante para servidor
=========================================

Um certificado de licenciante para servidor concede a um servidor RMS o direito de emitir certificados e licenças. Ao ser configurado, o primeiro servidor raiz de certificação da implantação do RMS recebe um certificado de licenciante para servidor do Microsoft Enrollment Service. Este processo é chamado de registro. Esse certificado contém a chave pública do servidor raiz de certificação e é assinado pela chave particular do serviço de registro. Outros servidores que são adicionados ao cluster raiz de certificação compartilham esse certificado.

Durante a configuração, o primeiro servidor de licenciamento que está em um cluster recebe um certificado de licenciante para servidor do servidor ou do cluster raiz de certificação do RMS em um processo chamado de sub-registro. Esse certificado contém a chave pública do servidor de licença e é assinado pela chave particular do servidor ou cluster raiz de certificação. Outros servidores que são adicionados ao cluster de licenciamento compartilham esse certificado.

A tabela a seguir lista os direitos que são concedidos a servidores pelos certificados de licenciante para servidor.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Concede direitos de emitir</th>
<th style="border:1px solid black;" >Certificado de licenciante para servidor que é emitido para um servidor raiz de certificação</th>
<th style="border:1px solid black;" >Certificado de licenciante para servidor que é emitido para um servidor de licença</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Certificados de conta de direitos</td>
<td style="border:1px solid black;">Sim</td>
<td style="border:1px solid black;">Não</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Licenças de publicação</td>
<td style="border:1px solid black;">Sim</td>
<td style="border:1px solid black;">Sim</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Licenças de uso</td>
<td style="border:1px solid black;">Sim</td>
<td style="border:1px solid black;">Sim</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Certificados de licenciante para servidor subordinado</td>
<td style="border:1px solid black;">Sim</td>
<td style="border:1px solid black;">Não</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Certificados de licenciante para cliente</td>
<td style="border:1px solid black;">Sim</td>
<td style="border:1px solid black;">Sim</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc720184.note(WS.10).gif)Observação                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |  
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| O RMS não requer servidores nem clusters de licenciamento separados, mas servidores ou clusters de licenciamento separados podem ser usados para descarregar as solicitações de licenciamento do cluster raiz de certificação. Os administradores também podem configurar servidores de licença para atender às necessidades de organizações internas que requerem controle direto sobre conteúdo de publicação protegido. Por exemplo, diretivas corporativas gerais que são implementadas nos modelos de diretiva de direitos do servidor ou cluster raiz de certificação podem não especificar alguns dos direitos que são necessários para um departamento específico. Nesse caso, o departamento pode implantar um servidor ou cluster de licença separado para armazenar modelos de diretiva de direitos e tratar suas solicitações de licença. |
