---
TOCTitle: Exibindo arquivos de log
Title: Exibindo arquivos de log
ms:assetid: '2dc9ed54-76d8-4721-ba93-194845de726a'
ms:contentKeyID: 18123542
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720228(v=WS.10)'
---

Exibindo arquivos de log
========================

Dependendo de como você implantou o RMS, os arquivos de log estão armazenados em um servidor de banco de dados como SQL Server ou Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Versão A. Você pode desenvolver filtros para reduzir as informações armazenadas nos arquivos de log. Para obter instruções, consulte a Ajuda do SQL Server Enterprise Manager.

Uma entrada típica de log tem cerca de 300 bytes. A tabela a seguir descreve os campos que são registrados.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Campo</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">HostMachineName</td>
<td style="border:1px solid black;">O computador que tratou a solicitação.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">HostMachineRequestId</td>
<td style="border:1px solid black;">Identifica esta solicitação neste computador de maneira exclusiva. A combinação de HostMachineName e HostMachineRequestId identifica a solicitação em todo o cluster de maneira exclusiva.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RequestTime</td>
<td style="border:1px solid black;">Hora, em Hora Universal Coordenada (Hora de Greenwich), em que a solicitação foi recebida.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RequestPath</td>
<td style="border:1px solid black;">URL relativa ao arquivo.asmx, por exemplo: /_wmcs/licensing/License.asmx.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RequestType</td>
<td style="border:1px solid black;">Nome do método da Web invocado, por exemplo: AcquireLicense.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RequestUserAddress</td>
<td style="border:1px solid black;">Endereço IP de origem do solicitante.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RequestUserAgent</td>
<td style="border:1px solid black;">Valor do Agente do Usuário do cabeçalho HTTP.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">AuthenticatedState</td>
<td style="border:1px solid black;">Se a conexão HTTP foi autenticada (True/False).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SecureConnectionState</td>
<td style="border:1px solid black;">Se esta é uma conexão SSL (True/False).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">AuthenticatedId</td>
<td style="border:1px solid black;">Nome de logon para solicitações autenticadas. Em branco se AuthenticatedState=False.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ReceivedXrMLDocument</td>
<td style="border:1px solid black;">O documento XrML recebido do solicitante.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ReceivedXrMLDocumentIssuerChain</td>
<td style="border:1px solid black;">A cadeia do emissor para o documento XrML recebido.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IssuedXrMLDocument</td>
<td style="border:1px solid black;">O documento XrML devolvido ao solicitante.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IssuedXrMLDocumentIssuerChain</td>
<td style="border:1px solid black;">A cadeia do emissor para o documento XrML emitido.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SuccessOrFailure</td>
<td style="border:1px solid black;">Se a solicitação obteve êxito ou falhou (Succeeded/Failed).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Metadados</td>
<td style="border:1px solid black;">Campo de metadados.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ErrorInformation</td>
<td style="border:1px solid black;">Mensagem de erro descritiva, se tiver ocorrido um erro.</td>
</tr>
</tbody>
</table>
