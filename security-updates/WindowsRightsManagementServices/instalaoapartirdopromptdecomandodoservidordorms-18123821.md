---
TOCTitle: Instalação a partir do prompt de comando do servidor do RMS
Title: Instalação a partir do prompt de comando do servidor do RMS
ms:assetid: 'b55b1e2a-dd14-4168-a37f-9cdedbec660b'
ms:contentKeyID: 18123821
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747733(v=WS.10)'
---

Instalação a partir do prompt de comando do servidor do RMS
===========================================================

Você pode instalar o RMS com Service Pack 2 (SP2) via prompt de comando, o que permite automatizar a instalação. A automatização da instalação pode ser feita de uma destas duas formas: executando uma instalação autônoma usando o cliente EXE baixado ou usando os arquivos MSI extraídos do EXE baixado para instalar o cliente do RMS. Para instalar usando o arquivo EXE baixado, utilize esta sintaxe:

**WindowsRightsManagementServicesSP2-KB917275-Client-ENU.exe -override 1 /I MsDrmClient.msi REBOOT=ReallySuppress /q -override 2 /I RmClientBackCompat.msi REBOOT=ReallySuppress /q**

Para instalar usando os arquivos do Windows® Installer (.msi), primeiro você deve extrair os arquivos msi do arquivo executável do RMS com SP2. O seguinte comando pode ser executado em um prompt de comando para extrair os arquivos msdrmclient.msi e RmClientBackCompat.msi:

**WindowsRightsManagementServiceSP2-KB917275-Server-ENU.exe /X:C:\\***Install\_Location*

Depois de extrair os arquivos .msi, você poderá usar os seguintes comandos para instalar o RMS:

**msiexec.exe /I MSDrmClient.msi /qn ALLUSERS=2 /m MSIDHOG /lei logfile.log DISPLYPAGE="NO" TARGETDIR=c:\\***Install\_Location*

**msiexec.exe /I RMClientBackCompat.msi /qn ALLUSERS=2 /m MSIDHOG /lei logfile.log DISPLYPAGE="NO" TARGETDIR=c:\\***Install\_Location*

A tabela a seguir descreve a sintaxe de cada comando.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Parâmetro</th>
<th style="border:1px solid black;" >Definição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>/I MSDrmClient.msi</strong> ou <strong>/I RMClientBackCompat.msi</strong></td>
<td style="border:1px solid black;">Necessário. Especifica o produto a ser instalado.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/qn</strong></td>
<td style="border:1px solid black;">Opcional. Especifica uma instalação silenciosa, sem a interação do usuário.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/lei</strong> <em>logfile.log</em></td>
<td style="border:1px solid black;">Opcional. Especifica o arquivo ao qual serão vinculadas as mensagens de erro e de status.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>DISPLAYPAGE=&quot;NO&quot;</strong></td>
<td style="border:1px solid black;">Opcional. Especifica que a página <strong>Administração Global</strong> não será exibida após a instalação.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>TARGETDIR=c:\</strong><em>Install_Location</em></td>
<td style="border:1px solid black;">Opcional. Especifica o diretório em que o RMS com Service Pack 2 deve ser instalado. Se você não especificar um local, será usado o local de instalação padrão.</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747733.note(WS.10).gif)Observação                                                                                                                                                                                                         |  
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Qualquer que seja o método de instalação que você escolha implementar, é preciso certificar-se de que os dois arquivos .msi sejam instalados com sucesso. Se ocorrer um erro que impeça a instalação do MSDrmClient.msi, o arquivo RMClientBackCompat.msi não deverá ser instalado. |
