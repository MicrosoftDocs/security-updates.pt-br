---
TOCTitle: Serviço de proxy de ativação do RMS
Title: Serviço de proxy de ativação do RMS
ms:assetid: '6b9d33ef-466b-405b-a768-54e5615d6770'
ms:contentKeyID: 18123700
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747608(v=WS.10)'
---

Serviço de proxy de ativação do RMS
===================================

Todas as solicitações de ativação de máquina do RMS versão 1.0 passam pelo serviço de proxy de ativação, que só é executado no cluster raiz do RMS. Você deve ativar um computador cliente para que ele possa ser usado com o RMS para publicar ou consumir conteúdo protegido por direitos. A partir do RMS com Service Pack 1, o cliente é "auto-ativado", não sendo necessário usar o servidor proxy de ativação nem o Serviço de Ativação da Microsoft para gerar um cofre e um certificado de máquina.

O serviço de proxy de ativação encaminha solicitações de ativação de máquina de clientes do RMS versão 1.0 para o Serviço de Ativação da Microsoft, o qual retorna um cofre personalizado e um certificado de máquina correspondente do RMS que são exclusivos para um determinado usuário e computador. O serviço de proxy de autenticação, em seguida, encaminha esses itens de volta para o cliente solicitante.

O arquivo do aplicativo do serviço de proxy de autenticação, Activation.asmx, está localizado no diretório virtual de certificação que está no IIS. A lista de controle de acesso padrão desse serviço é mostrada na seguinte tabela:

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
<td style="border:1px solid black;">Convidados</td>
<td style="border:1px solid black;">Ler e Executar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Grupo de Serviço RMS</td>
<td style="border:1px solid black;">Ler e Executar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SYSTEM</td>
<td style="border:1px solid black;">Controle Total</td>
</tr>
</tbody>
</table>
