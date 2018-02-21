---
TOCTitle: Listas de revogação do RMS
Title: Listas de revogação do RMS
ms:assetid: '688d4dfa-c928-4b2f-8116-2f9e87d2b6f7'
ms:contentKeyID: 18123661
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720287(v=WS.10)'
---

Listas de revogação do RMS
==========================

Listas de revogação especificam o conteúdo, os aplicativos, os usuários ou outras entidades que foram revogadas. Uma organização deve incluir uma entidade que está em uma lista de revogação por um ou mais dos seguintes motivos:

-   Uma chave particular é desconhecida ou é suspeita de estar comprometida.
-   Um proprietário solicita revogação de uma que acredita estar comprometida.
-   Uma entidade não é mais válida (por exemplo, um funcionário foi demitido).
-   Existe uma falha na aplicação da segurança (por exemplo, um certificado emitido para um computador cliente foi comprometido).
-   Nova certificação é necessária devido a alterações de autorização.
-   As brechas de segurança existentes em um aplicativo habilitado para RMS tornam o seu uso inapropriado no consumo de conteúdo altamente confidencial ou de qualquer conteúdo protegido.
-   Uma parte do conteúdo que foi distribuída anteriormente agora está desatualizada ou não é mais apropriada para consumo.

A tabela a seguir descreve as entidades que você pode especificar em uma lista de revogação, juntamente com as informações que são usadas para identificar cada uma.

###  

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Entidade</th>
<th style="border:1px solid black;" >Identificador</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Um grupo de licenças ou de certificados</td>
<td style="border:1px solid black;">Identificação do emissor ou chave pública</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Um grupo de manifestos do aplicativo</td>
<td style="border:1px solid black;">Identificação do emissor ou chave pública</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Uma licença ou certificado específico</td>
<td style="border:1px solid black;">Identificação da licença ou hash</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Um manifesto específico do aplicativo</td>
<td style="border:1px solid black;">Identificação da licença ou hash</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Uma entidade específica</td>
<td style="border:1px solid black;">Identificação da entidade ou chave pública</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Uma parte específica do conteúdo</td>
<td style="border:1px solid black;">Identificação do conteúdo</td>
</tr>
</tbody>
</table>
  
> [!Note]  
> Para revogação ou exclusão, todos os hashes são SHA-1 \[NIS94c\], uma revisão do Algoritmo de Hash Seguro (SHA), o qual encontra-se especificado no padrão SHS (SHS, FIPS 180). SHA-1 é descrito no padrão ANSI X9.30 (parte 2). Para revogar por manifesto de aplicativo, é necessário extrair do manifesto do aplicativo um dos seguintes itens: a identificação do emissor, a chave pública do emissor, a identificação da licença ou o hash da licença. No entanto, os manifestos de aplicativo têm codificação base 64, de modo que as informações não fiquem disponíveis em exibições não criptografadas. Com o SDK cliente do RMS (Rights Management Services), é possível desenvolver um programa usando os métodos **DRMConstructCertificateChain**, **DRMDeconstructCertificateChain** e **DRMDecode** para decodificar o manifesto de aplicativo e obter as informações necessárias. Caso queira evitar que a capacidade de um determinado aplicativo consuma o conteúdo protegido pelo RMS, considere o uso da exclusão do aplicativo para proibir que o servidor RMS conceda licenças de uso a esses aplicativos. A limitação da exclusão é que ela não pode impedir que alguém com uma licença de uso válida descriptografe o conteúdo protegido pelo RMS. Para obter mais informações sobre exclusão de aplicativos, consulte "Excluindo aplicativos" em "Operando um servidor RMS", nesta coleção de documentos. 
  
As listas de revogação são arquivos XrML que especificam os seguintes parâmetros.
  
###  

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Parâmetro</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">ISSUEDTIME</td>
<td style="border:1px solid black;">A hora do sistema em que o arquivo XrML foi criado. É usado pela condição REFRESH que está em uma licença de uso para determinar há quanto tempo a lista de revogação existe.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ISSUER</td>
<td style="border:1px solid black;">O nome, a identificação e o endereço do emissor da lista de revogação.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PUBLICKEY</td>
<td style="border:1px solid black;">A chave pública do emissor da lista de revogação.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">REVOCATIONLIST</td>
<td style="border:1px solid black;">O nome, o tipo e a identificação de cada entidade revogada.</td>
</tr>
</tbody>
</table>
