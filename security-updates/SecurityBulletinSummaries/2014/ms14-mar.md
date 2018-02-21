---
TOCTitle: 'MS14-MAR'
Title: Resumo dos boletins de segurança da Microsoft de março de 2014
ms:assetid: 'ms14-mar'
ms:contentKeyID: 61598063
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms14-mar(v=Security.10)'
---

 

Resumo dos boletins de segurança da Microsoft de março de 2014
==============================================================

Publicado em: 11 de março de 2014

**Versão:** 1.0

Este resumo de boletins lista os boletins publicados em março de 2014.

Com a publicação dos boletins de segurança de março de 2014, este resumo de boletins substitui a notificação antecipada de boletim emitida originalmente em 6 de março de 2014. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 12 de março de 2014, às 11:00 AM, Horário do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de março](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572977&culture=en-us).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

Sinopses
--------

 
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados**.

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet (2925418)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e dezessete vulnerabilidades relatadas de forma privada no Internet Explorer. Essas vulnerabilidades podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-013">MS14-013</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft DirectShow pode permitir a execução remota de código (2929961)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada de forma privada no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário abrir um arquivo de imagem especialmente criado. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-015">MS14-015</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no driver do modo do kernel do Windows podem permitir a elevação de privilégio (2930275)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e uma vulnerabilidade relatada de forma privada no Microsoft Windows. A mais rigorosa dessas vulnerabilidades pode permitir elevação de privilégio se um invasor fizer logon no sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essas vulnerabilidades.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-016">MS14-016</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no protocolo Remoto do Gerente de Conta de Segurança (SAMR) pode permitir o desvio do recurso de segurança (2934418)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir o desvio do recurso de segurança se um invasor fizer várias tentativas para coincidir senhas com um nome de usuário.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Desvio de recurso de segurança</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-014">MS14-014</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Silverlight pode permitir o desvio do recurso de segurança (2932677)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Silverlight. A vulnerabilidade poderá permitir desvio de recurso de segurança se o invasor hospedar um site que contenha o Silverlight especialmente criado para explorar esta vulnerabilidade e, então, convencer um usuário a exibir o site. Não há como o invasor forçar os usuários a visitarem o site mal intencionado. Em vez disso, um invasor tem que convencer os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um email ou por um pedido pelo Instant Messenger que leva os usuários ao site do invasor. Também é possível exibir conteúdo da Web próprio para a finalidade usando anúncios de banner ou outros métodos para implantar conteúdo da Web nos sistemas afetados.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Desvio de recurso de segurança</td>
<td style="border:1px solid black;">Não exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
</tbody>
</table>

<p></p>

  
 
  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas por ordem de ID do boletim e de ID da CVE. Só são incluídas as vulnerabilidades com uma classificação de gravidade Crítica ou Importante nos boletins.
  
Como devo usar a tabela?
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Índice de exploração da Microsoft](http://technet.microsoft.com/security/cc998259).
  
Nas colunas a seguir, "Versão mais Recente de Software" se refere ao software, e "Versões mais Antigas de Software se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.
  
<p></p>

<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0297">CVE-2014-0297</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0298">CVE-2014-0298</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0299">CVE-2014-0299</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0302">CVE-2014-0302</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0303">CVE-2014-0303</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0304">CVE-2014-0304</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0305">CVE-2014-0305</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0306">CVE-2014-0306</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0307">CVE-2014-0307</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0308">CVE-2014-0308</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0309">CVE-2014-0309</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0311">CVE-2014-0311</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0312">CVE-2014-0312</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0313">CVE-2014-0313</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0314">CVE-2014-0314</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0321">CVE-2014-0321</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0322">CVE-2014-0322</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade foi divulgada publicamente.<br />
<br />
A Microsoft está ciente dos ataques limitados e direcionados que tentam explorar esta vulnerabilidade no Internet Explorer 10.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-012">MS14-012</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0324">CVE-2014-0324</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">A Microsoft está ciente dos ataques limitados e direcionados que tentam explorar esta vulnerabilidade no Internet Explorer 8.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-013">MS14-013</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do DirectShow</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0301">CVE-2014-0301</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-014">MS14-014</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio do Silverlight DEP/ASLR</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0319">CVE-2014-0319</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-015">MS14-015</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0300">CVE-2014-0300</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-015">MS14-015</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação não autorizada de informações do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0323">CVE-2014-0323</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta vulnerabilidade foi divulgada publicamente.<br />
<br />
Esta é uma vulnerabilidade de divulgação de informações em versões mais antigas de software.<br />
<br />
Esta é uma vulnerabilidade de negação de serviço na última versão do software.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-016">MS14-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio de recurso de segurança do SAMR</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0317">CVE-2014-0317</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
</tbody>
</table>

<p></p>

  
Softwares afetados  
------------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
**Como uso estas tabelas?**  
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
**Componentes e sistema operacional Windows**

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows XP (site em inglês)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(Crítica)  
Internet Explorer 7   
(2925418)  
(Crítica)  
Internet Explorer 8   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(Com o Active Directory Application Mode instalado)  
(2933528)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(Crítica)  
Internet Explorer 7   
(2925418)  
(Crítica)  
Internet Explorer 8   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(Com o Active Directory Application Mode instalado)  
(2933528)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(Moderada)  
Internet Explorer 7  
(2925418)  
(Moderada)  
Internet Explorer 8  
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(Com Active Directory instalado)  
(2923392)  
(Importante)  
Windows Server 2003 Service Pack 2  
(Com o Active Directory Application Mode instalado)  
(2933528)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(Moderada)  
Internet Explorer 7  
(2925418)  
(Moderada)  
Internet Explorer 8  
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(Com Active Directory instalado)  
(2923392)  
(Importante)  
Windows Server 2003 x64 Edition Service Pack 2  
(Com o Active Directory Application Mode instalado)  
(2933528)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(Moderada)  
Internet Explorer 7  
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(Com Active Directory instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(Crítica)  
Internet Explorer 8  
(2925418)  
(Crítica)  
Internet Explorer 9   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(Com Active Directory Lightweight Directory Service \[AD LDS\] instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(Crítica)  
Internet Explorer 8  
(2925418)  
(Crítica)  
Internet Explorer 9   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(Com Active Directory Lightweight Directory Service \[AD LDS\] instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(Moderada)  
Internet Explorer 8  
(2925418)  
(Moderada)  
Internet Explorer 9   
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(Com Active Directory ou Active Directory Lightweight Directory Service \[AD LDS\] instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(Moderada)  
Internet Explorer 8  
(2925418)  
(Moderada)  
Internet Explorer 9   
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(Com Active Directory ou Active Directory Lightweight Directory Service \[AD LDS\] instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
Nenhuma

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
(Crítica)  
Internet Explorer 9   
(2925418)  
(Crítica)  
Internet Explorer 10   
(2925418)  
(Crítica)  
Internet Explorer 11   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
(Crítica)  
Internet Explorer 9   
(2925418)  
(Crítica)  
Internet Explorer 10   
(2925418)  
(Crítica)  
Internet Explorer 11   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
(Moderada)  
Internet Explorer 9   
(2925418)  
(Moderada)  
Internet Explorer 10   
(2925418)  
(Moderada)  
Internet Explorer 11   
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(Com Active Directory ou Active Directory Lightweight Directory Service \[AD LDS\] instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8 e Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
Nenhuma

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 e Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Com Active Directory instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2925418)  
(Moderada)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2929961)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Com Active Directory instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT e Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
Nenhuma

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
Nenhuma

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2925418)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Opção de instalação Server Core**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://technet.microsoft.com/pt-br/library/security/ms14-012)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://technet.microsoft.com/pt-br/library/security/ms14-013)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://technet.microsoft.com/pt-br/library/security/ms14-015)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://technet.microsoft.com/pt-br/library/security/ms14-016)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
Nenhuma

</td>
<td style="border:1px solid black;">
Nenhuma

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação Server Core)  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação Server Core)  
(Com Active Directory ou Active Directory Lightweight Directory Service \[AD LDS\] instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação Server Core)  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação Server Core)  
(Com Active Directory ou Active Directory Lightweight Directory Service \[AD LDS\] instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(Com Active Directory ou Active Directory Lightweight Directory Service \[AD LDS\] instalado)  
(2923392)  
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
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(Com Active Directory instalado)  
(2923392)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(2930275)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(Com Active Directory instalado)  
(2923392)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
 

**Ferramentas e softwares para desenvolvedores Microsoft**

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-014**](http://technet.microsoft.com/pt-br/library/security/ms14-014)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 quando instalado no Mac  
(2932677)  
(Importante)  
Microsoft Silverlight 5 Developer Runtime quando instalado no Mac  
(2932677)  
(Importante)  
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de clientes Microsoft Windows  
(2932677)  
(Importante)  
Microsoft Silverlight 5 Developer Runtime quando instalado em todas as versões com suporte de clientes Microsoft Windows  
(2932677)  
(Importante)  
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de servidores Microsoft Windows  
(2932677)  
(Importante)  
Microsoft Silverlight 5 Developer Runtime quando instalado em todas as versões com suporte de servidores Microsoft Windows  
(2932677)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns.

O WSUS (Windows Server Update Services), SMS (Systems Management Server) e SCCM (System Center Configuration Manager) ajudam os administradores a distribuir as atualizações de segurança.

Os componentes do Avaliador de compatibilidade com atualizações, incluídos no Kit de ferramentas de compatibilidade de aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para informações sobre estas e outras ferramentas que estão disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/security/cc297183). 

Agradecimentos
--------------

 
A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) às pessoas mencionadas abaixo por trabalhar conosco para ajudar a proteger os clientes:

**MS14-012**

-   lokihardt@ASRT, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products) , por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0297)
-   Amol Naik, que trabalha com [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0297)
-   Edward Torkington, do [NCC Group](https://www.nccgroup.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0297)
-   lokihardt@ASRT, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products)  , por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0298)
-   Jose A. Vazquez da Yenteasy - Security Research, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products)  , por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0299)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0302)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0303)
-   Hui Gao, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0304)
-   Zhibin Hu, da [Qihoo](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0304)
-   Tianfang Guo da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0305)
-   Jason Kratzer, que trabalha na [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0306)
-   Jason Kratzer, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products)  , por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0307)
-   lokihardt@ASRT, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products)  , por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0308)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0308)
-   Jason Kratzer, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0308)
-   Amol Naik, que trabalha com [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0309)
-   Scott Bell, da [Security-Assessment.com](http://www.security-assessment.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0311)
-   Yujie Wen, da [Qihoo](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0311)
-   Simon Zuckerbraun, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products)  , por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0312)
-   [Omair](http://krash.in/), que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0313)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0314)
-   Zhibin Hu, da [Qihoo](http://www.360.cn/) por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0314)
-   Liu Long, da [Qihoo](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0314)
-   Anil Aphale, por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0314)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0321)
-   Yujie Wen, da [Qihoo](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0321)
-   Zhibin Hu, da [Qihoo](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0321)
-   Liu Long, da [Qihoo](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0321)
-   Abdul-Aziz Hariri, de [Zero Day Initiative](http://www.zerodayinitiative.com/)[da HP](http://www.hpenterprisesecurity.com/products)  , por relatar a Vulnerabilidade de Corrupção de Memória do Internet Explorer (CVE-2014-0321)
-   Yuki Chen, da [Trend Micro](http://www.trendmicro.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0321)
-   [FireEye, Inc.](http://www2.fireeye.com/) por trabalhar conosco na Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0322)
-   Liu Long, da [Qihoo](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-0322)

**MS14-013**

-   Um pesquisador anônimo, que trabalha na [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar a vulnerabilidade de corrupção de memória DirectShow (CVE-2014-0301)

**MS14-014**

-   [NSFOCUS Information Technology Co., Ltd.,](http://en.nsfocus.com/) por relatar a Vulnerabilidade de desvio DEP/ASLR do Silverlight (CVE-2014-0319)

**MS14-015**

-   Alexander Chizhov, por trabalhar conosco na Vulnerabilidade de divulgação de informações do Win32k (CVE-2014-0323)

**MS14-016**

-   Andrew Barltett da The Samba Team e Catalyst IT, por relatar a vulnerabilidade de desvio de recurso de segurança do SAMR (CVE-2014-0317)
-   [Muhammad Faisal Naqvi](http://ae.linkedin.com/in/mfaisalnaqvi), do Paquistão, por relatar a Vulnerabilidade de desvio de recurso de segurança do SAMR (CVE-2014-0317)

Outras informações
------------------

 
### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

Em relação ao lançamento de boletins que ocorre na segunda terça-feira do mês, a Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows no Windows Update, Microsoft Update, Windows Server Update Services e Centro de Download. Nenhuma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows está disponível para os lançamentos de boletins de segurança desvinculados.

### Atualizações não relacionadas à segurança no MU, WU e WSUS

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](https://support.microsoft.com/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://go.microsoft.com/fwlink/?linkid=215201).

### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [Artigo 913086 (em inglês) da Microsoft Knowledge Base](https://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (em inglês).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).

Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617)

Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (11 de março de 2014): Resumo de boletins publicado.

*Página gerada em 19-08-2014 15:55Z-07:00.*
