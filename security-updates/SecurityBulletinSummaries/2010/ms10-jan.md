---
TOCTitle: 'MS10-JAN'
Title: Resumo do Boletim de Segurança da Microsoft de janeiro 2010
ms:assetid: 'ms10-jan'
ms:contentKeyID: 61233662
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms10-jan(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de janeiro 2010
===========================================================

Publicado: terça-feira, 12 de janeiro de 2010 | Atualizado: quinta-feira, 21 de janeiro de 2010

**Versão:** 2.0

Este resumo de boletins lista os boletins de segurança lançados em janeiro de 2010.

Com o lançamento dos boletins de janeiro de 2010, este resumo substitui a notificação antecipada de boletim lançada originalmente em 20 de janeiro de 2010. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada do Boletim de Segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 13 de janeiro de 2010, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de janeiro.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427677&eventcategory=4&culture=en-us&countrycode=us) Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

Para o boletim de segurança desvinculado adicionado à Versão 2.0 deste resumo dos boletins, MS10-002, a Microsoft hospeda um webcast para solucionar as dúvidas dos clientes sobre esse boletim em 21 de janeiro de 2010 às 13h00, Horário do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast em 21 de janeiro, às 13h00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032440627&culture=en-us). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações de alta prioridade que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

Sinopses
--------

 
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Software afetado e locais de download**.

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID do Boletim</th>
<th style="border:1px solid black;" >Título do boletim e Sinopse</th>
<th style="border:1px solid black;" >Classificação máxima de gravidade e impacto da vulnerabilidade</th>
<th style="border:1px solid black;" >Necessidade de Reinicialização</th>
<th style="border:1px solid black;" >Softwares afetados</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-001">MS10-001</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Mecanismo de Fonte OpenType Incorporada pode permitir a execução remota de código (972270)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade poderá permitir a execução remota de código se um usuário exibir conteúdo renderizado em uma fonte OpenType Incorporada (EOT) especialmente criada em aplicativos cliente que podem renderizar fontes EOT, como Microsoft Internet Explorer, Microsoft Office PowerPoint ou Microsoft Office Word. O invasor que explorar com êxito essa vulnerabilidade poderá assumir o controle total de um sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-002">MS10-002</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para Internet Explorer (978207)</strong><br />
<br />
Esta atualização de segurança crítica resolve sete vulnerabilidades no Internet Explorer reportadas em particular e uma divulgada publicamente. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas em ordem de ID do boletim e de ID da CVE.
  
**Como devo usar a tabela?**  
  
Use esta tabela para conhecer a probabilidade de o código de exploração em funcionamento ser lançado em 30 dias contados do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Você deve revisar cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade a sua implantação. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| ID do Boletim                                                       | Título da vulnerabilidade                                                                                   | ID do CVE                                                                        | Avaliação do índice de exploração                                                                                | Principais observações                                                                                                                                                                                                          |  
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-001](http://technet.microsoft.com/security/bulletin/ms10-001) | Falha no número inteiro de fontes compactadas Microtype Express na Vulnerabilidade do descompactador LZCOMP | [CVE-2010-0018](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0018) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente | Esta avaliação do índice de exploração se aplica a sistemas que executam o Microsoft Windows 2000. A exploração de sistemas que executam o Windows XP e sistemas operacionais posteriores é improvável.                         |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | Vulnerabilidade de manipulação de scripts de filtro XSS                                                     | [CVE-2009-4047](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-4047) | Nenhuma                                                                                                          | A execução de códigos não é possível com esta vulnerabilidade.                                                                                                                                                                  |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | Vulnerabilidade de validação de URL                                                                         | [CVE-2010-0027](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente   | (Nenhum)                                                                                                                                                                                                                        |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | Vulnerabilidade de corrupção de memória não inicializada                                                    | [CVE-2010-0244](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0244) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente   | (Nenhum)                                                                                                                                                                                                                        |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | Vulnerabilidade de corrupção de memória não inicializada                                                    | [CVE-2010-0245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0245) | Nenhuma                                                                                                          | Os clientes que aplicaram o boletim [MS09-072](http://technet.microsoft.com/security/bulletin/ms09-072) estão protegidos porque esta vulnerabilidade é bloqueada pelas alterações incluídas na atualização do boletim MS09-072. |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | Vulnerabilidade de corrupção de memória não inicializada                                                    | [CVE-2010-0246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0246) | Nenhuma                                                                                                          | Os clientes que aplicaram o boletim [MS09-072](http://technet.microsoft.com/security/bulletin/ms09-072) estão protegidos porque esta vulnerabilidade é bloqueada pelas alterações incluídas na atualização do boletim MS09-072. |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | Vulnerabilidade de corrupção de memória não inicializada                                                    | [CVE-2010-0247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0247) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente   | (Nenhum)                                                                                                                                                                                                                        |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | Vulnerabilidade de corrupção de memória não inicializada                                                    | [CVE-2010-0248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0248) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente | (Nenhum)                                                                                                                                                                                                                        |  
| [MS10-002](http://technet.microsoft.com/security/bulletin/ms10-002) | Vulnerabilidade de corrupção de memória não inicializada                                                    | [CVE-2010-0249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0249) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente   | **No momento, esta vulnerabilidade está sendo explorada no ecossistema da Internet.**                                                                                                                                           |
  
Softwares afetados e Locais de download  
---------------------------------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
**Como uso estas tabelas?**  
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, haverá também um hiperlink para a atualização de software disponível e a classificação de gravidade da atualização de software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
#### Componentes e sistema operacional Windows

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=47f85cbd-282e-4c92-9809-68bba49e0a12)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4 quando instalado no Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=51e99e4f-1670-4b12-a9fe-e0ccf50cdabc)  
(Crítica)  
[Internet Explorer 6 Service Pack 1 quando instalado no Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a38aa9d0-c3fe-4d41-8805-7d5370263c1b)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="3">
Windows XP (site em inglês)
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 e Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=793a6b3f-7660-40be-b7d5-7b0eec55e1cd)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6 para Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=207eecad-6e84-48e6-ae18-6794a3618ee0)  
(Crítica)  
[Internet Explorer 7 para Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3510c7d8-7e8f-479e-b6f9-5745a845664d)  
(Crítica)  
[Internet Explorer 8 para Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7c2948fb-f486-4801-bc21-bbf40d5a78c2)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=31609ce9-656a-4f7d-a501-709a31ca34c3)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6 para Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eb2d8055-4d50-4f83-82b8-055c7b8f5422)  
(Crítica)  
[Internet Explorer 7 para Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cc5aea0b-e553-4f7f-a2cc-cba41bb87ae7)  
(Crítica)  
[Internet Explorer 8 para Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=41b83fad-948b-4a9c-80ed-9c5a60bd35b4)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e1d6e338-dea9-458e-b35d-796e069d74d7)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6 para Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fea91227-44ad-4549-8732-497a8ceff870)  
(Moderada)  
[Internet Explorer 7 para Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=14726445-3ff4-463c-9fc1-c9b758079aca)  
(Crítica)  
[Internet Explorer 8 para Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d480c87-2ca9-4505-a59d-a6d73d001fa5)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ddbcf231-9fde-4dc2-ad04-a01b69d1a980)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6 para Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=633e63f4-605b-43c4-8a4b-2730312a1c72)  
(Moderada)  
[Internet Explorer 7 para Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c8742230-16d8-4b2f-bd3e-8834c759856b)  
(Crítica)  
[Internet Explorer 8 para Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3e2e740b-8417-4758-8468-15221249ec71)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=c71a13cf-7e2f-4b02-8684-1a4e4b46ddda)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6 para Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b9308d50-ca66-43ff-9dc5-d05c90baa764)  
(Moderada)  
[Internet Explorer 7 para Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5622f223-df9c-4a6a-bdf0-feebaf9920fd)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6387228c-eedc-4511-b3c6-8922606f4c84)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7 no Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=92495551-dedd-43d4-bb3a-51028bc5c6d6)  
(Crítica)  
[Internet Explorer 8 no Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5e2cbd7d-f64f-49e5-a159-1965ebfe2a92)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7b4f5089-13b1-421b-a00b-22632bba4229)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7 no Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3cb139b3-59f4-44ef-9911-4dd4e3b83e7d)  
(Crítica)  
[Internet Explorer 8 no Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b7a7e8e7-f4c5-459d-ab6c-05a192e1e3f9)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e175c436-37e0-497f-8b7f-6cacaa25ad7c)\*\*  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7 no Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8c4c91ec-1b2b-4176-bd77-45245b590329)\*\*  
(Crítica)  
[Internet Explorer 8 no Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f5ce8582-af63-4870-bee3-0abeeefa1458)\*\*  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x-64 e Windows Server 2008 para sistemas baseados em x-64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1b10a177-fd45-406f-8edc-b8d4b84881b7)\*\*  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7 no Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4f9975b8-3f91-4116-9200-ef55ece75854)\*\*  
(Crítica)  
[Internet Explorer 8 no Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=be11981c-d286-4e3c-94bf-d4e67a975d5a)\*\*  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e8bc9a24-a794-4827-a6bb-785c6b2189f4)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7 no Windows Server 2008 para sistemas baseados no Itanium e no Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9395547f-b620-4cbd-9ff5-11b76cd73859)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=75491ad0-40a6-4efb-9574-d82210f6d0da)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8 no Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=278443c1-15dc-436b-893b-ffea6d29d16d)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=8a53f0e9-0616-440e-90f2-a12524e1bee4)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8 no Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=a584cd0f-2e05-4e36-8858-0ffead637162)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-001**](http://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](http://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=308166e4-571b-4d6c-bd9f-3ed4afa4eafe)\*\*  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8 no Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=d3386793-a594-4bc5-8308-28b561d43087)\*\*  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1d0da42b-9755-4fd2-afd1-0d023d187133)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8 no Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9d137bab-8312-4240-af74-c65ba652fde0)  
(Crítica)
</td>
</tr>
</table>

<p></p>

 
**Observação para Windows Server 2008 e Windows Server 2008 R2**

**\*\*Instalação de Núcleo de Servidor não afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos de MSDN, [Núcleo do Servidor](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) e [Núcleo do Servidor para Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Observe que a opção de instalação do Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://go.microsoft.com/fwlink/?linkid=85102), no qual essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) e no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Frequentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

**Observação** A partir de 1º de agosto de 2009, a Microsoft descontinuará o suporte à Atualização do Office e à Ferramenta de Inventário da Atualização do Office. Para continuar obtendo as últimas atualizações para produtos Microsoft Office, use o [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Para obter mais informações, consulte [Sobre a Atualização do Microsoft Office: Perguntas frequentes](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Orientação para detecção e implantação**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o [Artigo 961747 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários. O próximo lançamento do SMS, System Center Configuration Manager 2007, já está disponível; consulte também [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Para obter mais informações sobre como os administradores podem usar o SMS 2003 para instalar atualizações de segurança, consulte [Gerenciamento de Patches de Segurança do SMS 2003.](http://go.microsoft.com/fwlink/?linkid=22939) Usuários do SMS 2.0 também podem usar o Security Update Inventory Tool (SUIT) para ajudar a implantar atualizações de segurança. Para obter informações sobre o SMS, visite [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) (sites em inglês) para instalar essas atualizações.

**Avaliador de Compatibilidade com Atualizações e Application Compatibility Toolkit**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) incluídos no [Kit de ferramentas de compatibilidade de aplicativos](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações de alta prioridade que não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do MAPP (Microsoft Active Protections Program)](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [Artigo 913086 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (em inglês).

#### Agradecimentos

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) à pessoa citada abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   Tavis Ormandy, da [Google Inc.](http://www.google.com/), por relatar um problema descrito no boletim MS10-001
-   [David Lindsay "thornmaker"](http://p42.us/) e [Eduardo A. Vela Nava "sirdarckcat"](http://www.sirdarckcat.net/) por relatarem um problema descrito no boletim MS10-002
-   Lostmon Lords por relatar um problema descrito no boletim MS10-002
-   Brett Moore, que trabalha com a [TippingPoint](http://www.tippingpoint.com/) e a [Zero Day Initiative](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS10-002
-   Wushi da [team509](http://www.team509.com/), que trabalha com a [TippingPoint](http://www.tippingpoint.com/) e a [Zero Day Initiative](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS10-002
-   Sam Thomas, da eshu.co.uk, que trabalha com a [TippingPoint](http://www.tippingpoint.com/) e a [Zero Day Initiative](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS10-002
-   Sam Thomas, da eshu.co.uk, que trabalha com a [TippingPoint](http://www.tippingpoint.com/) e a [Zero Day Initiative](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS10-002
-   Haifei Li, da [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) da Fortinet, por relatar um problema descrito no boletim MS10-002
-   Peter Vreugdenhil, da [Verisign iDefense Labs](http://labs.idefense.com/), que trabalha com a [TippingPoint](http://www.tippingpoint.com/) e a [Zero Day Initiative](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS10-002
-   Meron Sellem, da [BugSec](http://www.bugsec.com/), por relatar um problema descrito no boletim MS10-002

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) às seguintes empresas por trabalharem conosco e por fornecerem detalhes sobre um problema descrito no boletim MS10-002:

-   [Google Inc.](http://www.google.com/) e [MANDIANT](http://www.mandiant.com/)
-   [Adobe](http://www.adobe.com/)
-   [McAfee](http://www.mcafee.com/)

#### Suporte

-   O software afetado listado foi testado a fim de determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do [Suporte de Segurança](http://go.microsoft.com/fwlink/?linkid=21131) ou pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas. Para obter mais informações sobre as opções de suporte disponíveis, consulte [Ajuda e Suporte da Microsoft](http://support.microsoft.com/).
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (12 de janeiro de 2010): Resumo de boletins publicado.
-   V2.0 (21 de janeiro de 2010): Foi adicionada uma **atualização cumulativa para Internet Explorer ao Boletim de Segurança da Microsoft MS10-002 (978207)**. Também foi adicionado o link ao webcast para este boletim de segurança desvinculado.

*Built at 2014-04-18T01:50:00Z-07:00*
