---
TOCTitle: Gerenciando certificados de licenciante para servidor
Title: Gerenciando certificados de licenciante para servidor
ms:assetid: '549979ad-13ee-4abc-8281-3e002a5a9561'
ms:contentKeyID: 18123592
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720272(v=WS.10)'
---

Gerenciando certificados de licenciante para servidor
=====================================================

Certificados de licenciante servidor expiram depois de um período de tempo especificado, normalmente depois de um ano. Para renovar um certificado de licenciante servidor, você deve estar conectado como um administrador local. Quando você renova o certificado de licenciante para servidor do cluster raiz de certificação, o RMS envia uma solicitação para renovar o certificado de licenciante para servidor ao Microsoft Enrollment Service. Quando você renova o certificado de um servidor de licenciamento, o RMS envia a solicitação de renovação ao servidor raiz de certificação que emitiu o certificado que está expirando.

Há três eventos que o RMS postará no Log de eventos do sistema que você deve monitorar. Esse eventos informam quando o certificado de licenciante servidor estiver se aproximando da data de renovação ou expirou. A tabela a seguir lista as identificações e os nomes dos eventos.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Identificação do evento</th>
<th style="border:1px solid black;" >Nome do evento</th>
<th style="border:1px solid black;" >Tipo do evento</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">16</td>
<td style="border:1px solid black;">LicensorCertExpiresInOneMonthEvent</td>
<td style="border:1px solid black;">Aviso. O serviço continua a funcionar normalmente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">17</td>
<td style="border:1px solid black;">LicensorCertExpiresInOneWeekEvent</td>
<td style="border:1px solid black;">Aviso. O serviço continua a funcionar normalmente.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">18</td>
<td style="border:1px solid black;">LicensorCertExpiredEvent</td>
<td style="border:1px solid black;">Erro. O serviço é desabilitado.</td>
</tr>
</tbody>
</table>
