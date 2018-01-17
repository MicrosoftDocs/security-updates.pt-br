---
TOCTitle: 'MS12-DEC'
Title: Resumo do Boletim de Segurança da Microsoft de dezembro 2012
ms:assetid: 'ms12-dec'
ms:contentKeyID: 61233685
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms12-dec(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de dezembro 2012
============================================================

Publicado: terça-feira, 11 de dezembro de 2012 | Atualizado: quinta-feira, 20 de dezembro de 2012

**Versão:** 2.0

Este resumo relaciona os boletins de segurança lançados em dezembro de 2012.

Com o lançamento dos boletins de segurança de dezembro de 2012, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 6 de dezembro de 2012. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 12 de dezembro de 2012, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de dezembro.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522564&culture=en-us) Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522564&culture=en-us).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

#### Sinopses

A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados e locais de download**.

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID do Boletim</th>
<th style="border:1px solid black;" >Título do boletim e Sinopse</th>
<th style="border:1px solid black;" >Classificação máxima de gravidade e impacto da vulnerabilidade</th>
<th style="border:1px solid black;" >Requisitos de reinicialização</th>
<th style="border:1px solid black;" >Softwares afetados</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-077">MS12-077</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (2761465)  <br />
<br />
</strong>Esta atualização de segurança resolve três vulnerabilidades relatadas em particular no Internet Explorer. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-078">MS12-078</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades em drivers do modo kernel do Windows podem permitir a execução remota de código<br />
(2783534)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e uma vulnerabilidade relatada em particular no Microsoft Windows. A mais rigorosa dessas vulnerabilidades pode permitir a execução remota do código se um usuário abrir um documento especialmente criado ou visitar uma página da Web mal-intencionada que incorpore arquivos de fonte TrueType ou OpenType. O invasor deve convencer os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um e-mail que os leve ao site do invasor.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-079">MS12-079</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Word pode permitir a execução remota de código (2780642)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office. A vulnerabilidade poderá permitir execução remota de código se um usuário abrir um arquivo RTF especialmente criado usando uma versão afetada de software do Microsoft Office, visualizar ou abrir uma mensagem de email RTF especialmente criada no Outlook ao usar o Microsoft Word como visualizador de emails. O invasor que explorar com êxito a vulnerabilidade poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-080">MS12-080</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Exchange Server podem permitir a execução remota de código (2784126)  <br />
<br />
</strong>Esta atualização de segurança elimina vulnerabilidades divulgadas publicamente e uma vulnerabilidade relatada em particular no Microsoft Exchange Server. As vulnerabilidades mais severas estão na Visualização de documentos do Microsoft Exchange Server WebReady e podem permitir a execução remota de código no contexto de segurança do serviço de transcodificação no Exchange Server se um usuário visualizar um arquivo especialmente criado usando o Outlook Web App (OWA). O serviço de transcodificação no Exchange usado para Visualização de documentos WebReady é executado na conta LocalService. A conta LocalService tem privilégios mínimos no computador local e apresenta credenciais anônimas na rede.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-081">MS12-081</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no componente de controle de arquivo do Windows pode permitir a execução remota de código (2758857)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário acessar uma pasta que contenha um arquivo ou subpasta com nome especialmente criado. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-082">MS12-082</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no DirectPlay pode permitir a execução remota de código (2770660)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se o invasor convencer o usuário a visualizar um arquivo do Office especialmente criado com conteúdo incorporado. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-083">MS12-083</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no IP-HTTPS pode permitir a passagem pelo recurso de segurança (2765809)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade poderá permitir uma passagem pelo recurso de segurança se um invasor apresentar um certificado revogado a um servidor IP-HTTPs comumente usado em implantações do Microsoft DirectAccess. Para explorar a vulnerabilidade, o invasor deve usar um certificado emitido pelo domínio para autenticação do servidor IP-HTTPs. Fazer logon em um sistema dentro da organização ainda pode exigir credenciais de domínio ou sistema.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Desvio de recurso de segurança</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas por ordem de ID do boletim e de ID da CVE. Só são incluídas as vulnerabilidades com uma classificação de gravidade Crítica ou Importante nos boletins.
  
**Como devo usar a tabela?**  
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Índice de exploração da Microsoft](http://technet.microsoft.com/pt-br/security/cc998259.aspx).
  
Nas colunas a seguir, "Versão mais Recente de Software" se refere ao software, e "Versões mais Antigas de Software se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID do Boletim</th>
<th style="border:1px solid black;" >Título da vulnerabilidade</th>
<th style="border:1px solid black;" >ID do CVE</th>
<th style="border:1px solid black;" >Avaliação da capacidade de exploração da última versão de software</th>
<th style="border:1px solid black;" >Avaliação da capacidade de exploração de versão mais antiga de software</th>
<th style="border:1px solid black;" >Avaliação do risco de exploração para negação de serviço</th>
<th style="border:1px solid black;" >Principais observações</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-077">MS12-077</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do InjectHTMLStream</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4781">CVE-2012-4781</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-077">MS12-077</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do CMarkup</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4782">CVE-2012-4782</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-077">MS12-077</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação de contagem ref imprópria</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4787">CVE-2012-4787</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-078">MS12-078</a></td>
<td style="border:1px solid black;">Vulnerabilidade de análise de Fonte OpenType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2556">CVE-2012-2556</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-078">MS12-078</a></td>
<td style="border:1px solid black;">Vulnerabilidade de análise de fonte TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4786">CVE-2012-4786</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-079">MS12-079</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota do código &quot;listoverridecount&quot; em RTF do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2539">CVE-2012-2539</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-080">MS12-080</a></td>
<td style="border:1px solid black;">O Oracle Outside In contém várias vulnerabilidades que podem ser exploradas</td>
<td style="border:1px solid black;">Várias\*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">\*Várias vulnerabilidades, consulte o boletim MS12-080 para obter detalhes.<br />
<br />
Estas vulnerabilidades foram divulgadas publicamente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-080">MS12-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade RSS feed pode causar Exchange DoS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4791">CVE-2012-4791</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-081">MS12-081</a></td>
<td style="border:1px solid black;">Vulnerabilidade de análise de nome inteiro do Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4774">CVE-2012-4774</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-082">MS12-082</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de heap do DirectPlay</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1537">CVE-2012-1537</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-083">MS12-083</a></td>
<td style="border:1px solid black;">Vulnerabilidade de passagem pelo certificado revogado</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2549">CVE-2012-2549</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
</tbody>
</table>

<p></p>

  
Softwares afetados e locais de download  
---------------------------------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
**Como uso estas tabelas?**  
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, haverá também um hiperlink para a atualização de software disponível e a classificação de gravidade da atualização de software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
#### Componentes e sistema operacional Windows

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="6">
Windows XP (site em inglês)  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e39c8368-9cd3-4f29-8c9c-aa784122bef0)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d1881d12-2a40-4cb1-9428-31d6633746be)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8359ec5a-07f8-4b29-8576-7356a84daf82)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e4a2cd3b-598b-4cf4-8b42-2582d369bab5)  
(KB2753842)  
(Crítica)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7a7a68cf-42a2-49a4-bf0c-88dd582ddd0d)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f189ee1c-1457-4d50-87cd-5be268b04f16)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=98ceaf36-ef87-4ea3-8b73-bb0a1a624fe0)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=ed2d3c6e-b90a-49a7-867e-9549b14eb0bf)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=18e165e9-346b-4337-81d2-77f3bf5f5f3f)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5d0a76e1-80d3-4f81-be5e-8d235babaa61)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=27e6c4df-7988-4d03-b2f6-bc9ce37483f9)  
(KB2753842)  
(Crítica)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d2a59846-74fd-4166-9d65-1cc98cb7d934)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2bf25fc8-6458-4807-bb7d-1c07ec424638)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=421b0c02-e572-4362-b690-73ad63b028de)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=478f4789-0f5e-4bfb-9536-94314f84f12c)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ca71c15-0add-45cd-991f-e5810791c434)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0157c9ee-58c5-419f-ba97-6c4334318b75)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=efe4755b-3bc4-4a65-9826-7ecaa3856093)  
(KB2753842)  
(Crítica)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=74847cb5-a092-4818-bf7a-912ccaed7a12)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2242a927-cafb-41eb-8bf2-01302b5a5d94)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1b487137-8b5a-4f22-8395-f3fc4f25f00b)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=66b552b4-8b55-45de-ba0a-940dc24e6f56)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e9fb2cf9-3acb-48ac-80ac-f61f1a47a188)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=23c4962c-8526-4e18-9b8d-50f3c3a2bf6d)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=019d80e2-7622-4951-9437-5d613c5fb2fb)  
(KB2753842)  
(Crítica)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b0c9df15-857f-490a-96df-3883a11c3234)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4d97b0a5-1ba7-44f0-88b6-1e0a8039b9b1)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=39d79b5b-f11c-465a-8ddd-aecb571c711f)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=890d1149-7bb3-4d6e-a4ce-f9116c658eda)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d8025298-be72-4ef2-8914-7698494f4368)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=419b9fd2-dbe6-45b5-b025-9712bb9319d6)  
(KB2753842)  
(Crítica)  
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=323c122b-be77-45e9-805d-ab14f5cc76f9)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=e74713fd-e1bc-4a63-9a00-2f33000eac27)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=312975f6-2269-4c6f-996b-8fb04e8c08d6)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade** **agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3701a40d-e423-4204-9527-26e527f47fb0)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=394963e9-edd6-4b5d-b9d4-e6fb86d7eb54)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bd3a6f9b-7bfd-40e1-9393-a125030f2964)  
(KB2761465)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0cadef72-625f-4c91-8289-c10a96bb3423)  
(KB2753842)  
(Crítica)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f2854a4e-2597-49ab-8a85-715ea9194208)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ebd25f89-e6d9-4c48-a673-f665d189905c)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cd60c749-bb24-4147-9699-a1a75939a28f)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2856c7b8-d5c0-444d-8273-5bd116f8898b)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a0c6dbd-e537-43d7-97cc-0d3df354e46a)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=482fadb3-0974-40f3-af35-f29210913c81)  
(KB2761465)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dd5eb06a-c805-4518-a784-5e29d7636037)  
(KB2753842)  
(Crítica)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b6baf170-65b0-4068-b2a0-196c3e4b3aed)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e7629d85-5c18-4979-a8e2-054a6175cf21)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[](http://www.microsoft.com/downloads/details.aspx?familyid=?...?)[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d6f2c1d9-b775-48a0-b154-cf61b1e2674c)</a>
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a4824a10-4011-4ce5-9454-693d42acddf3)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e3d584f5-fc25-4e66-a911-4595018c51e3)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ffff647e-8d05-4c77-aea6-542ab8d76c57)  
(KB2761465)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a51b84d-2200-42c5-a6ab-4d570fa20609)  
(KB2753842)  
(Crítica)  
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdad28e8-987e-492e-a405-b3be552d2d7a)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ced1ffc6-7d30-480a-a3e0-8071981d1863)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=20ffdbfd-c786-41ca-9367-d7499108d711)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=750797e5-1da7-49a9-8c27-ff35fe7516a1)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ca4a5972-faec-412a-b51a-130253cebcab)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=8f22603d-3a0d-49da-9691-671c0c950867)  
(KB2761465)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9c60014b-133e-455e-b03f-d73f6e36d3de)  
(KB2753842)  
(Crítica)  
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6298d55c-2ed2-4a90-9dfe-43bae0932e27)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9a687e6-9ab7-4dae-9771-5f7bb3123e06)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cfeb7a06-5812-4a49-b69b-88be06d63d71)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4d49cd73-feea-44c7-86f2-048dd69233a4)   
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=68e6d5c4-cb20-4291-8864-4270db36ead0)  
(KB2753842)  
(Crítica)  
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2293a5fb-4a1c-41d9-ab67-b89e00078029)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=202b3919-0075-4c54-a189-123de852fc7b)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0345e31f-6d0d-4d46-8f02-8b2ffbf795f0)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5b461a22-6ca4-4ab9-8874-84d7928cc668)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=38b15264-1a1d-41a6-8803-2d3facdb2dc3)   
(KB2761465)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=d1894fc3-603a-4a94-9e27-e1c564688294)  
(KB2753842)  
(Crítica)  
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=48f7d41e-f1c4-428d-9889-543fcb1e272b)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=cdaae723-6287-4607-9dc2-c23e1fb31f80)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=27e57b08-8616-4eb3-9724-3647e6841296)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5b461a22-6ca4-4ab9-8874-84d7928cc668)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=38b15264-1a1d-41a6-8803-2d3facdb2dc3)   
(KB2761465)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d1894fc3-603a-4a94-9e27-e1c564688294)  
(KB2753842)  
(Crítica)  
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=48f7d41e-f1c4-428d-9889-543fcb1e272b)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=cdaae723-6287-4607-9dc2-c23e1fb31f80)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=27e57b08-8616-4eb3-9724-3647e6841296)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d19dfe38-77ef-4479-b3d9-8f6385ddee80)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7accb5a9-98a1-4358-90ba-534d197885c1)   
(KB2761465)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=d7b5c43d-b659-4843-8944-62bf52738bbc)  
(KB2753842)  
(Crítica)  
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=ae9f0c19-169b-4bcd-92f7-654b84bab01f)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=4a389411-bf52-4cb2-9051-ba7344b58474)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=5f7c21b9-7dd3-4b9f-84af-1450af6c7ee3)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d19dfe38-77ef-4479-b3d9-8f6385ddee80)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7accb5a9-98a1-4358-90ba-534d197885c1)   
(KB2761465)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=d7b5c43d-b659-4843-8944-62bf52738bbc)  
(KB2753842)  
(Crítica)  
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=ae9f0c19-169b-4bcd-92f7-654b84bab01f)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=4a389411-bf52-4cb2-9051-ba7344b58474)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=5f7c21b9-7dd3-4b9f-84af-1450af6c7ee3)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8968122d-d3b9-404e-ba23-846be9041e3f)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=14bd26c2-b006-4465-88cc-4ecdc5de540f)   
(KB2761465)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)  
(KB2753842)  
(Crítica)  
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=efe0d293-9cfb-46cb-b52e-0b90bde3f8e9)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)  
(KB2765809)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8968122d-d3b9-404e-ba23-846be9041e3f)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=14bd26c2-b006-4465-88cc-4ecdc5de540f)   
(KB2761465)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)  
(KB2753842)  
(Crítica)  
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=efe0d293-9cfb-46cb-b52e-0b90bde3f8e9)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)  
(KB2765809)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9191365d-5541-4277-9079-f4e72e98fd19)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=f26098f5-6b6c-48f9-8737-345ad4956cb0)  
(KB2753842)  
(Crítica)  
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=51b562f4-8b1a-416e-88dc-93b561ad850a)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2a0a6f92-c4bf-45a3-b103-b7937121b675)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=33096b07-bfa3-4879-b214-dfa81cd73cae)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=88a3452c-b416-41cf-867a-fdc64666c0a6)  
(KB2765809)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9191365d-5541-4277-9079-f4e72e98fd19)  
(KB2761465)  
(Nenhuma classificação de gravidade<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=f26098f5-6b6c-48f9-8737-345ad4956cb0)  
(KB2753842)  
(Crítica)  
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=51b562f4-8b1a-416e-88dc-93b561ad850a)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2a0a6f92-c4bf-45a3-b103-b7937121b675)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=33096b07-bfa3-4879-b214-dfa81cd73cae)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=88a3452c-b416-41cf-867a-fdc64666c0a6)  
(KB2765809)  
(Importante)
</td>
</tr>
<tr>
<th colspan="6">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=28fb32a1-12fd-420d-94ff-570742a02b8d)  
(KB2761465)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=385265c4-f920-4ac1-b474-a166b3d3ab42)  
(KB2753842)  
(Crítica)  
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=75969782-d3f8-40dd-8922-4408eefad6f3)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=15f86dbf-d8db-445c-8996-cc789c8a894d)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=ad0ee30f-b550-434b-9fe0-ff418e052d3f)  
(KB2761465)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=543af274-d6cf-4f85-a120-b7f3936d7fc2)  
(KB2753842)  
(Crítica)  
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=2332059d-30d3-4b44-b172-f054e26d8971)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=dfdda0c8-a440-49ab-832b-cdd343c57770)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=96fda694-876a-45e9-911a-b68b3bd03290)  
(KB2761465)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=15298129-8f1c-47d7-a7e9-efb40823d91a)  
(KB2753842)  
(Crítica)  
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f8e84ff9-a9c0-4363-b5a6-1b90254edd73)  
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=59be5ec7-df5a-4f01-8e27-ad76f1fe76bb)  
(KB2770660)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=d6654bf1-1ab9-4691-8729-793eb6d0e563)  
(KB2765809)  
(Importante)
</td>
</tr>
<tr>
<th colspan="6">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[2]</sup>
(KB2761465)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2753842)  
(Crítica)  
Windows RT<sup>[1]</sup>
(KB2779030)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Opção de instalação de núcleo de servidor
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a51b84d-2200-42c5-a6ab-4d570fa20609) (instalação do núcleo do servidor)  
(KB2753842)  
(Importante)  
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdad28e8-987e-492e-a405-b3be552d2d7a) (instalação do núcleo do servidor)  
(KB2779030)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ced1ffc6-7d30-480a-a3e0-8071981d1863) (instalação do núcleo do servidor)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9c60014b-133e-455e-b03f-d73f6e36d3de) (instalação do núcleo do servidor)  
(KB2753842)  
(Importante)  
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6298d55c-2ed2-4a90-9dfe-43bae0932e27) (instalação do núcleo do servidor)  
(KB2779030)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9a687e6-9ab7-4dae-9771-5f7bb3123e06) (instalação do núcleo do servidor)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas x64](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099) (instalação do núcleo do servidor)  
(KB2753842)  
(Importante)  
[Windows Server 2008 para sistemas x64](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c) (instalação do núcleo do servidor)  
(KB2779030)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817) (instalação do núcleo do servidor)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f) (instalação do núcleo do servidor)  
(KB2765809)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099) (instalação do núcleo do servidor)  
(KB2753842)  
(Importante)  
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c) (instalação do núcleo do servidor)  
(KB2779030)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817) (instalação do núcleo do servidor)  
(KB2758857)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f) (instalação do núcleo do servidor)  
(KB2765809)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=15298129-8f1c-47d7-a7e9-efb40823d91a) (instalação Server Core)  
(KB2753842)  
(Importante)  
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f8e84ff9-a9c0-4363-b5a6-1b90254edd73) (instalação Server Core)  
(KB2779030)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=d6654bf1-1ab9-4691-8729-793eb6d0e563) (instalação Server Core)  
(KB2765809)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observações para o MS12-077**

<sup>[1]</sup>Classificações de gravidade não se aplicam a esta atualização para o software especificado, porque os vetores de ataque conhecidos para a vulnerabilidade abordada neste boletim são bloqueados em uma configuração padrão. No entanto, como medida de defesa abrangente, a Microsoft recomenda que clientes deste software apliquem esta atualização de segurança.

<sup>[2]</sup>A atualização está disponível apenas no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

**Observação para o MS12-078**

<sup>[1]</sup>A atualização está disponível apenas no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office Suites e componentes
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6947d500-f197-4001-bb39-1c4221af1b36)  
(KB2760497)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=52aad8a5-14d9-4c02-828a-5c1164a01f27)<sup>[1]</sup>
(KB2760421)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=52aad8a5-14d9-4c02-828a-5c1164a01f27)<sup>[1]</sup>
(KB2760421)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=68c69b37-c544-4f24-8589-4212b868dd69)  
(KB2760410)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 Service Pack 1 (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=9d776c2b-1a9a-4ccb-9e76-dd2cb0f9a80d)  
(KB2760410)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Outros softwares do Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=4ccaabd9-5128-4505-ba2f-20bcf02b97ec)  
(KB2760498)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 2
</td>
<td style="border:1px solid black;">
[Pacote de compatibilidade do Microsoft Office Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c82de87d-3457-423e-9bfc-ec3f950049e7)  
(KB2760416)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3
</td>
<td style="border:1px solid black;">
[Pacote de compatibilidade do Microsoft Office Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c82de87d-3457-423e-9bfc-ec3f950049e7)  
(KB2760416)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observações para MS12-079**

<sup>[1]</sup>Para o Microsoft Office Word 2007, além do pacote de atualização de segurança KB2760421, os clientes também precisam instalar a atualização de segurança para o Pacote de compatibilidade do Microsoft Office (KB2760416) para se protegerem da vulnerabilidade descrita neste boletim.

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=605fc9bc-a05c-4466-ace6-9c2af087d797)   
(KB2746157)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e43b1164-d768-4152-b9a3-d1491e2f3cba)   
(KB2787763)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2a49ed58-9dab-4d48-ae8a-c7139e3b34ba)   
(KB2785908)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Serviços de automação do Word](http://www.microsoft.com/downloads/details.aspx?familyid=62007dcd-80db-42e4-8478-9e81f89cab98)  
(KB2760405)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1 
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c98d8ef3-e9a8-4e7c-9e0a-02e192bab39c)   
(KB2687412)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**Observação para o MS12-079**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Microsoft Safety & Security Center](http://www.microsoft.com/brasil/security), onde essas informações também estão disponíveis, clicando em “Atualizações de segurança”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) e no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade executando uma pesquisa com a palavra-chave "atualização de segurança".

Para os clientes do Microsoft Office for Mac, o Microsoft AutoUpdate for Mac pode ajudar a manter seu software Microsoft atualizado. Para obter mais informações sobre como usar o Microsoft AutoUpdate for Mac, consulte [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS12-001"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Frequentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

**Orientação de detecção e implantação:**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o [Artigo 961747 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, consulte [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://technet.microsoft.com/wsus/default).

**System Center Configuration Manager**

O gerenciamento de atualizações de software do System Center Configuration Manager simplifica a complexa tarefa de fornecer e gerenciar atualizações a sistemas de TI pela empresa. Com o System Center Configuration Manager, os administradores de TI podem fornecer atualizações de produtos da Microsoft a uma variedade de dispositivos, inclusive desktops, laptops, servidores e dispositivos móveis.

A avaliação automatizada de vulnerabilidade no System Center Configuration Manager detecta as necessidades de atualizações e relatórios com relação a ações recomendadas. O gerenciamento de atualizações de software no System Center Configuration Manager é integrado ao Microsoft Windows Software Update Services (WSUS), uma infraestrutura de atualização testada quanto à confiabilidade, que é familiar aos administradores de TI do mundo todo. Para obter mais informações sobre o System Center Configuration Manager, consulte: [System Center Technical Resources](http://technet.microsoft.com/systemcenter/bb980621).

**Systems Management Server 2003**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários.

**Observação** O System Management Server 2003 está fora de suporte principal desde 12 de janeiro de 2010. Para obter mais informações sobre ciclos de vida de produtos, acesse [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742). A próxima versão do SMS, System Center Configuration Manager, já está disponível; consulte a seção anterior: **System Center Configuration Manager**.

Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, consulte [Cenários e procedimentos para o Microsoft Systems Management Server 2003: Distribuição de software e Gerenciamento de patches](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f). Para obter informações sobre o SMS, acesse: [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)) para instalar essas atualizações.

**Avaliador de compatibilidade com atualizações e Kit de ferramentas de compatibilidade de aplicativos**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet.microsoft.com/library/cc749197) incluídos no [Kit de ferramentas de compatibilidade de aplicativos](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199)
-   : Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965)
-   . Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://go.microsoft.com/fwlink/?linkid=215201).

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

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) às pessoas mencionadas abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   [Rosario Valotta](https://sites.google.com/site/tentacoloviola)
-   , por relatar dois problemas descritos no boletim MS12-077
-   Fermin J. Serna, da [Google Inc](http://www.google.com), por relatar um problema descrito no boletim MS12-077
-   Eetu Luodemaa e Joni Vähämäki, da [Documill](http://www.documill.com), que trabalham com o Chromium Security Rewards Program, por relatar um problema descrito no boletim MS12-078
-   Um colaborador anônimo, que trabalha com o programa [Beyond Security's SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html), por relatar um problema descrito no boletim MS12-079
-   Lucas Apa, da [IOActive](http://ioactive.co.uk/), por relatar um problema descrito no boletim MS12-081
-   [Aniway](mailto:aniway.anyway@gmail.com)
-   , que trabalha na
-   [VeriSign iDefense Labs](http://labs.idefense.com/)
-   , por relatar um problema descrito no boletim MS12-082

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617,aspx)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (11 de dezembro de 2012): Resumo de boletins publicado.
-   V1.1 (12 de dezembro de 2012): Corrigida entrada de requisitos de reinicialização do MS12-082. Esta é apenas uma alteração informativa. Não houve nenhuma alteração em arquivos de atualização de segurança.
-   V2.0 (20 de dezembro de 2012): Para o MS12-078, relançada atualização KB2753842 para resolver um problema com fontes OpenType não renderizadas adequadamente depois da instalação da atualização original. Os clientes que instalaram com êxito a atualização KB2753842 original precisam instalar a atualização relançada.

*Built at 2014-04-18T01:50:00Z-07:00*
