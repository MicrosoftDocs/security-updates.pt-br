---
TOCTitle: Tecnologias do cliente do RMS
Title: Tecnologias do cliente do RMS
ms:assetid: '6980468a-fc8c-489b-966f-2921ec268e74'
ms:contentKeyID: 18123622
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720288(v=WS.10)'
---

Tecnologias do cliente do RMS
=============================

Os computadores clientes que estão em uma implantação do RMS utilizam as tecnologias apresentadas a seguir, as quais permitem que os usuários criem, publiquem e consumam conteúdo protegido pelo RMS.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Tecnologia</th>
<th style="border:1px solid black;" >Descrição</th>
<th style="border:1px solid black;" >Emitido por</th>
<th style="border:1px solid black;" >Para obter mais informações</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Aplicativos habilitados para RMS</td>
<td style="border:1px solid black;">Necessários para criar e publicar conteúdo protegido pelo RMS. Os aplicativos podem ser desenvolvidos especificamente para o RMS, ou os aplicativos existentes podem ser redefinidos para funcionar com o RMS.</td>
<td style="border:1px solid black;">Desenvolvedores não-Microsoft.</td>
<td style="border:1px solid black;">Aplicativos habilitados para RMS</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Certificados de máquina do RMS</td>
<td style="border:1px solid black;">Identificam um computador específico como confiável para o RMS.</td>
<td style="border:1px solid black;">Serviço de Ativação para o RMS versão 1.0. Não é exigido nenhum serviço para obter um certificado de máquina com o RMS SP1.</td>
<td style="border:1px solid black;">Certificados de máquina do RMS</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Cofres</td>
<td style="border:1px solid black;">Contém a chave particular e um certificado correspondente do computador que contém a chave pública do computador.</td>
<td style="border:1px solid black;">Serviço de Ativação para o RMS versão 1.0. Não é exigido nenhum serviço para obter um cofre com o RMS SP1. O cofre contém a chave particular do computador; é a principal entidade de segurança para criptografia e descriptografia.</td>
<td style="border:1px solid black;">Cofres</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Certificados de conta de direitos</td>
<td style="border:1px solid black;">Identificam um usuário específico como confiável para o RMS.</td>
<td style="border:1px solid black;">Serviço de certificação de conta de direitos.</td>
<td style="border:1px solid black;">Certificados de conta de direitos</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Certificados de licenciante para cliente</td>
<td style="border:1px solid black;">Permitem que um usuário publique conteúdo protegido pelo RMS mesmo quando não estiver conectado à rede.
(Opcional)</td>
<td style="border:1px solid black;">Serviço de publicação do RMS.</td>
<td style="border:1px solid black;">Certificados de licenciante para cliente</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Licenças de publicação</td>
<td style="border:1px solid black;">Define direitos de uso de uma parte de conteúdo.</td>
<td style="border:1px solid black;">O serviço de publicação do RMS (ou, em caso de publicação offline, o certificado de licenciante para cliente) pode emitir essa licença.</td>
<td style="border:1px solid black;">Licenças de publicação</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Licenças de uso</td>
<td style="border:1px solid black;">Permitem que um usuário consuma o conteúdo protegido pelo RMS.</td>
<td style="border:1px solid black;">Serviço de licenciamento do RMS.</td>
<td style="border:1px solid black;">Licenças de uso</td>
</tr>
</tbody>
</table>
