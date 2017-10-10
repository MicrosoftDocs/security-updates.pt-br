---
TOCTitle: Resumo dos certificados e licenças do RMS
Title: Resumo dos certificados e licenças do RMS
ms:assetid: '637ccfca-318e-4346-85b5-0945b058fb9c'
ms:contentKeyID: 18123695
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747595(v=WS.10)'
---

Resumo dos certificados e licenças do RMS
=========================================

A tabela a seguir lista os certificados e as licenças usados pelo RMS. Eles serão discutidos detalhadamente nos demais tópicos desta seção.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Certificado ou licença</th>
<th style="border:1px solid black;" >Objetivo</th>
<th style="border:1px solid black;" >Conteúdo</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Certificados de licenciante para servidor</td>
<td style="border:1px solid black;">O certificado de licenciante para servidor que é emitido para servidores de licença concede os direitos de emitir:
<ul>
<li>Licenças de publicação<br />
<br />
</li>
<li>Licenças de uso<br />
<br />
</li>
<li>Certificados de licenciante para cliente<br />
<br />
</li>
<li>Modelos de diretiva de direitos<br />
<br />
</li>
</ul>
O certificado de licenciante para servidor que é emitido para o cluster raiz de certificação concede adicionalmente o direito para emitir:
<ul>
<li>Certificados de conta de direitos para clientes<br />
<br />
</li>
<li>Certificados de licenciante para servidor para servidores de licença<br />
<br />
</li>
</ul></td>
<td style="border:1px solid black;">O certificado de licenciante para servidor que é emitido para um servidor de licença contém a chave pública do servidor de licença.
O certificado de licenciante para servidor que é emitido para um servidor raiz de certificação contém a chave pública do servidor raiz de certificação.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Certificados de licenciante para cliente</td>
<td style="border:1px solid black;">Concedem ao usuário o direito de publicar conteúdo protegido pelo RMS sem estar conectado à rede corporativa.</td>
<td style="border:1px solid black;">Contém a chave pública do certificado e a chave particular do certificado criptografado pela chave pública do usuário que solicitou o certificado. Também contém a chave pública do servidor que emitiu o certificado.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Certificados de máquina do RMS</td>
<td style="border:1px solid black;">Identificam um computador ou dispositivo no qual o sistema RMS confia.</td>
<td style="border:1px solid black;">Contém a chave pública do computador ativado. A chave particular correspondente está no cofre desse computador.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Certificados de conta de direitos</td>
<td style="border:1px solid black;">Identificar um usuário no contexto de um computador ou dispositivo específico.</td>
<td style="border:1px solid black;">Contém a chave pública do usuário e a chave particular do usuário que está criptografada com a chave pública do computador ativado.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Licenças de publicação</td>
<td style="border:1px solid black;">Especificam os direitos que se aplicam ao conteúdo protegido pelo RMS.</td>
<td style="border:1px solid black;">Contêm a chave simétrica de conteúdo para descriptografar o conteúdo, o qual foi criptografado com a chave pública do servidor que emitiu a licença.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Licenças de uso</td>
<td style="border:1px solid black;">Especificam os direitos que se aplicam ao conteúdo protegido pelo RMS no contexto de um usuário autenticado específico.</td>
<td style="border:1px solid black;">Contém a chave simétrica do conteúdo para descriptografar o conteúdo, que é criptografado com a chave pública do usuário.</td>
</tr>
</tbody>
</table>
