---
TOCTitle: 'Serviço de pré-certificação do RMS'
Title: 'Serviço de pré-certificação do RMS'
ms:assetid: '09957294-167f-4f98-88e9-ae90fbeb26c1'
ms:contentKeyID: 18123573
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720191(v=WS.10)'
---

Serviço de pré-certificação do RMS
==================================

O serviço de pré-certificação só é executado no cluster raiz do RMS. Este serviço habilita um servidor a solicitar um certificado de conta de direitos em nome de um usuário e pode ser usado para desenvolver aplicativos personalizados. O Microsoft Exchange Server 2007 e o Microsoft Office SharePoint Server 2007 são alguns dos que utilizam esse serviço.

O arquivo do aplicativo do serviço de pré-certificação, Precertification.asmx, está localizado no diretório virtual de certificação que está no IIS.

Para obter mais informações sobre como desenvolver aplicativos personalizados, consulte a documentação sobre a tecnologia Windows Rights Management Services na MSDN Library em [http://go.microsoft.com/fwlink/?LinkID=32972](http://go.microsoft.com/fwlink/?linkid=32972) (a página pode estar em inglês).

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
