---
TOCTitle: Planejando os requisitos de cluster para o RMS
Title: Planejando os requisitos de cluster para o RMS
ms:assetid: 'ec4023eb-4d39-4551-9789-c8a2d973a55b'
ms:contentKeyID: 18123875
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747792(v=WS.10)'
---

Planejando os requisitos de cluster para o RMS
==============================================

Se estiver usando o RMS em uma implantação em clusters, não deixe de considerar como lidar com as condições abaixo que podem existir em sua organização.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Condição</th>
<th style="border:1px solid black;" >Recomendação</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Grande número de desktops que usam o RMS.</td>
<td style="border:1px solid black;">Você pode usar o Windows Update, um script ou um método de distribuição de software, como o SMS (Systems Management Server) ou a Diretiva de Grupo para instalar e ativar o software Microsoft Windows Rights Management Services.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Grande quantidade de solicitações de cliente.</td>
<td style="border:1px solid black;">Use um servidor de balanceamento de carga, o serviço NLB (Balanceamento de carga de rede) ou o balanceamento de carga de hardware para distribuir as solicitações pelo cluster.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Dois adaptadores de rede que usem endereçamento IP virtual para atender a solicitações de extranet e intranet.</td>
<td style="border:1px solid black;">Certifique-se de que qualquer registro do DNS feito para expor o endereço IP virtual à extranet também seja feito para expô-lo à intranet.
Se o registro do DNS não for feito para a intranet, as solicitações de licença dos clientes internos falharão. Se não conseguir modificar os registros do recurso do DNS, você poderá modificar a tabela de hosts de cada servidor no cluster para mapear o URL do cluster para o endereço IP virtual do cluster. O registro do DNS precisa ser feito antes da configuração do RMS. Se já tiver configurado o RMS, você deverá desconfigurá-lo e repetir o processo de configuração.</td>
</tr>
</tbody>
</table>
