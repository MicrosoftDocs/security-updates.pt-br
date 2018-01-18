---
TOCTitle: 'MS12-SEP'
Title: Resumo do Boletim de Segurança da Microsoft de setembro 2012
ms:assetid: 'ms12-sep'
ms:contentKeyID: 61233694
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms12-sep(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de setembro 2012
============================================================

Publicado: terça-feira, 11 de setembro de 2012 | Atualizado: sexta-feira, 21 de setembro de 2012

**Versão:** 2.0

Este resumo de boletins lista os boletins de segurança lançados em setembro de 2012.

Com o lançamento dos boletins de setembro de 2012, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 19 de setembro de 2012. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 12 de setembro de 2012, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de setembro](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522555&culture=en-us). Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522555&culture=en-us).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre o boletim desvinculado de segurança em 21 de setembro de 2012, às 12h00, Horário do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de setembro](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032529852&culture=en-us). Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032529852&culture=en-us).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras** **informações.**

### Informações do boletim

Sinopses
--------

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para</strong> <strong>o Internet Explorer (2744842)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e quatro vulnerabilidades relatadas em particular no Internet Explorer. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que explorar com êxito qualquer uma destas vulnerabilidades poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-061">MS12-061</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Visual Studio Team Foundation Server pode permitir a elevação de privilégio (2719584)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Visual Studio Team Foundation Server. A vulnerabilidade pode permitir elevação de privilégio se um usuário clicar em um link criado em uma mensagem de e-mail ou navegar em uma página usada para explorar a vulnerabilidade. Em todos os casos, entretanto, o invasor não tem como forçar os usuários a realizar essas ações. Em vez disso, o invasor teria que convencer os usuários a visitar um site, geralmente fazendo com que eles cliquem em um link em um e-mail ou mensagem do Instant Messenger que leva o usuário ao site do invasor.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Não é necessário reiniciar</td>
<td style="border:1px solid black;">Ferramentas para desenvolvedor da Microsoft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-062">MS12-062</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no System Center</strong> <strong>Operations</strong> <strong>Managerpode permitir a elevação de privilégio (2741528)</strong> <br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade em particular relatada no Microsoft System Center Configuration Manager. A vulnerabilidade pode permitir o aumento de privilégio se um usuário visitar um website afetado por meio de uma URL especialmente criada. Não há como o invasor forçar os usuários a visitarem o site mal-intencionado. Em vez disso, o invasor teria que persuadir os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um e-mail ou mensagem do Instant Messenger que leva o usuário ao site do invasor.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Não é necessário reiniciar</td>
<td style="border:1px solid black;">Microsoft Server Software</td>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-061">MS12-061</a></td>
<td style="border:1px solid black;">Vulnerabilidade do XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1892">CVE-2012-1892</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-062">MS12-062</a></td>
<td style="border:1px solid black;">Vulnerabilidade do XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2536">CVE-2012-2536</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do OnMove</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1529">CVE-2012-1529</a></td>
<td style="border:1px solid black;">Não afetado[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Event Listener</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2546">CVE-2012-2546</a></td>
<td style="border:1px solid black;">Não afetado[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do layout</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2548">CVE-2012-2548</a></td>
<td style="border:1px solid black;">Não afetado[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do cloneNode</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2557">CVE-2012-2557</a></td>
<td style="border:1px solid black;">Não afetado[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-063">MS12-063</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do execCommand</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4969">CVE-2012-4969</a></td>
<td style="border:1px solid black;">Não afetado[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente.<br />
<br />
A Microsoft está ciente dos ataques limitados que tentam explorar a vulnerabilidade.</td>
</tr>
</tbody>
</table>

<p></p>

 

<sup>[1]</sup>O Internet Explorer 10 não é afetado por esta vulnerabilidade.

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
<th colspan="2">
Windows XP (site em inglês)
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=967c9ef3-db48-4c2f-9a67-87851fd54962)  
(KB2744842)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6ba78d4c-3657-4963-b2da-7a3763c6b5c9)  
(KB2744842)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ac71ffe3-f077-4753-a238-47a2e9623363)  
(KB2744842)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=020b36c6-7050-4458-8762-bae35eb713cd)  
(KB2744842)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1e2e412a-be97-407e-9f02-fc074db3bb07)  
(KB2744842)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c727d956-be3e-4cd2-913c-f26cb6c33227)  
(KB2744842)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7aaaa15b-87d8-4afc-b183-8ce5becda026)  
(KB2744842)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=aef34ce4-a6ce-4f5e-9892-0a7fbd90c3b4)  
(KB2744842)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d63e25ad-ab8c-425f-89cd-29cd2b7b69d6)  
(KB2744842)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=366feacb-16ad-455c-b2ad-5038f998c432)  
(KB2744842)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=baa47c53-2724-43ef-8590-d3733b47e75b)  
(KB2744842)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=84144e56-f653-4c92-bf49-d44d9ba10489)  
(KB2744842)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=c28d6dc3-c2f0-4505-a545-85b7a0e3e2dc)  
(KB2744842)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=86c28695-86a5-4c17-82d6-7f98b3162aa6)  
(KB2744842)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="2">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-063)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=053546fc-ed41-43c2-b4f2-b76334314f5c)  
(KB2744842)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0a5a446d-0a48-4eec-b424-87339b34a3be)  
(KB2744842)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=daba1ef1-62db-43db-9d5b-495aa2d3550f)  
(KB2744842)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=cbe5681b-c28e-4a6a-9b97-0bfe44acf077)  
(KB2744842)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5642136e-68f6-42e8-b48e-1549733c6e7d)  
(KB2744842)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=aae496ef-fca2-4632-9a8f-2108722d2b28)  
(KB2744842)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-063)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=df861b42-bcf2-4f7a-9019-f49e6725f5dc)  
(KB2744842)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1d4f0f25-9539-4c38-babb-4af7f0f4c6cf)  
(KB2744842)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0b2965d7-e0b2-4035-a9e4-f6badb389098)  
(KB2744842)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fa9878c0-b7e5-43ac-b1eb-679e62cf62fc)  
(KB2744842)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=10bab7d4-0dd8-4fa7-b26c-715a68553707)  
(KB2744842)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=612a94ef-0950-41e8-9875-a8f0e71eba6f)  
(KB2744842)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ded887a4-a06d-4447-b19d-19d0f4928523)  
(KB2744842)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="2">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=93591461-39ff-4cbd-8df3-88cb80ed6255)  
(KB2744842)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3)  
(KB2744842)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=93591461-39ff-4cbd-8df3-88cb80ed6255)  
(KB2744842)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3)  
(KB2744842)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e2083388-19a9-4754-9449-1dad2a7f7543)  
(KB2744842)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=01045ee2-c7c4-4078-969f-905fd7e8774f)  
(KB2744842)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e2083388-19a9-4754-9449-1dad2a7f7543)  
(KB2744842)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=01045ee2-c7c4-4078-969f-905fd7e8774f)  
(KB2744842)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d46ec8ea-b8c8-42d9-a201-f36eb97b91b8)  
(KB2744842)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c44a0253-fefc-4ce6-9cfd-396fdea71f8d)  
(KB2744842)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d46ec8ea-b8c8-42d9-a201-f36eb97b91b8)  
(KB2744842)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c44a0253-fefc-4ce6-9cfd-396fdea71f8d)  
(KB2744842)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c132173b-f869-47ec-bb70-6307081473fe)  
(KB2744842)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c132173b-f869-47ec-bb70-6307081473fe)  
(KB2744842)  
(Moderada)
</td>
</tr>
</table>

<p></p>

 

#### Ferramentas e softwares para desenvolvedores Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual Studio Team Foundation Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-061**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-061)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio Team Foundation Server 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=721c4a38-b255-4792-83a5-7526a680a79a)<sup>[1]</sup>   
(KB2719584)   
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS12-061**

<sup>[1]</sup>Esta atualização é cumulativa e substitui atualizações cumulativas anteriores do software especificado.

#### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft System Center Configuration Manager
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-062**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Systems Management Server 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Systems Management Server 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f3a3d8e1-d551-43b4-9d54-9536f30c074d)<sup>[1]</sup>   
(KB2733631)   
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft System Center Configuration Manager 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft System Center Configuration Manager 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=89890c0e-118b-49ea-9fd1-6d23c674f9e8)<sup>[1]</sup>   
(KB2721642)   
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS12-062**

<sup>[1]</sup>Esta atualização está disponível somente no Centro de Download da Microsoft.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Microsoft Safety & Security Center](http://go.microsoft.com/fwlink/?linkid=85102), onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) e no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Para os clientes do Microsoft Office for Mac, o Microsoft AutoUpdate for Mac pode ajudar a manter seu software Microsoft atualizado. Para obter mais informações sobre como usar o Microsoft AutoUpdate for Mac, consulte [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS12-001"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Frequentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

**Orientação de detecção e implantação:**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o [Artigo 961747 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Microsoft** **Baseline** **Security** **Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, consulte [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://technet.microsoft.com/wsus/default).

**SystemCenter** **Configuration** **Manager**

O gerenciamento de atualizações de software do System Center Configuration Manager simplifica a complexa tarefa de fornecer e gerenciar atualizações a sistemas de TI pela empresa. Com o System Center Configuration Manager, os administradores de TI podem fornecer atualizações de produtos da Microsoft a uma variedade de dispositivos, inclusive desktops, laptops, servidores e dispositivos móveis.

A avaliação automatizada de vulnerabilidade no System Center Configuration Manager detecta as necessidades de atualizações e relatórios com relação a ações recomendadas. O gerenciamento de atualizações de software no System Center Configuration Manager é integrado ao Microsoft Windows Software Update Services (WSUS), uma infraestrutura de atualização testada quanto à confiabilidade, que é familiar aos administradores de TI do mundo todo. Para obter mais informações sobre o System Center Configuration Manager, consulte: [System Center Technical Resources](http://technet.microsoft.com/systemcenter/bb980621).

**Systems Management Server 2003**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários.

**Observação** O System Management Server 2003 está fora de suporte principal desde 12 de janeiro de 2010. Para obter mais informações sobre ciclos de vida de produtos, acesse [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742). A próxima versão do SMS, System Center Configuration Manager, já está disponível; consulte a seção anterior: **System Center** **Configuration** **Manager**.

Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, consulte [Cenários e procedimentos para o Microsoft Systems Management Server 2003: Distribuição de software e Gerenciamento de patches](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f). Para obter informações sobre o SMS, acesse: [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)) para instalar essas atualizações.

**Avaliador de compatibilidade com atualizações e Kit de** **ferramentas de compatibilidade de aplicativos**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet.microsoft.com/library/cc749197) incluídos no [Kit de ferramentas de compatibilidade de aplicativos](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

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

-   Sunil Yadav, da INR Labs ([Network Intelligence India](http://niiconsulting.com/)), por relatar o problema descrito no boletim MS12-061
-   Andy Yang, da [Stratsec](http://www.stratsec.net), por relatar um problema descrito no boletim MS12-062
-   Um pesquisador anônimo, que trabalha com a [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar um problema descrito no boletim MS12-063
-   [Rosario Valotta](https://sites.google.com/site/tentacoloviola)
-   , por relatar um problema descrito no boletim MS12-063
-   Stephen Fewer da [Harmony Security](http://www.harmonysecurity.com/), que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/)da[TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/), por relatar um problema descrito no boletim MS12-063.
-   Um pesquisador anônimo, que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) da [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/), por relatar um problema descrito no boletim MS12-063
-   Um pesquisador anônimo, que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) da [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/), por relatar um problema descrito no boletim MS12-063
-   [Mitre](http://www.mitre.org/)
-   , por trabalhar conosco em um problema descrito no boletim MS12-063

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617,aspx)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (11 de setembro de 2012): Resumo de boletins publicado.
-   V2.1 (2,0 de setembro de 2012): Foi adicionada uma atualização cumulativa para Internet Explorer ao Boletim de Segurança da Microsoft MS12-063 (2744842). Também foi adicionado o link ao webcast para este boletim de segurança desvinculado.

*Built at 2014-04-18T01:50:00Z-07:00*
