---
TOCTitle: 'MS14-AUG'
Title: Resumo de boletins de segurança da Microsoft de agosto de 2014
ms:assetid: 'ms14-aug'
ms:contentKeyID: 62757414
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms14-aug(v=Security.10)'
---

 

Resumo de boletins de segurança da Microsoft de agosto de 2014
==============================================================

Publicado em: 12 de augusto de 2014 | Atualizado em: 19 de dezembro de 2014

**Versão:** 2.2

Este resumo de boletins lista os boletins de segurança lançados em agosto de 2014.

Com o lançamento dos boletins de segurança de agosto de 2014, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 7 de agosto de 2014. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins na quarta-feira, 13 de agosto de 2014, às 11:00 hrs - Horário do Pacífico (EUA e Canadá). Para exibir o webcast mensal e acessar os links de webcasts de boletins de segurança adicionais, consulte [Webcast do Boletim de segurança da Microsoft](http://technet.microsoft.com/security/dn756352).

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (2976627)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e vinte e cinco vulnerabilidades relatadas de forma privada no Internet Explorer. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário visualizar uma página da Web criada especialmente usando o Internet Explorer. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-043">MS14-043</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Windows Media Center pode permitir a execução remota de código (2978742)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada de forma privada no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário abrir um arquivo do Microsoft Office especialmente criado que invoque recursos do Windows Media Center. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-048">MS14-048</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no OneNote pode permitir a execução remota de código (2977201)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada de forma privada no Microsoft OneNote. A vulnerabilidade pode permitir a execução remota de código se um arquivo especialmente criado for aberto em uma versão afetada do Microsoft OneNote. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-044">MS14-044</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no SQL Server pode permitir a elevação de privilégio (2984340)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft SQL Server (uma no SQL Server Master Data Services e outro no RDBMS do SQL Server). A mais grave dessas vulnerabilidades afetando o SQL Server Master Data Services pode permitir a elevação de privilégio se um usuário visitar um site especialmente criado que injete um script do lado cliente na instância do usuário do Internet Explorer. Em todos os casos, o invasor não tem como forçar os usuários a exibir o conteúdo controlado pelo invasor. Em vez disso, o invasor precisa convencer os usuários a executar uma ação, normalmente clicando em um link em uma mensagem de email ou em uma mensagem do Instant Messenger que os leve ao site do invasor ou abrindo um anexo enviado por email.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-045">MS14-045</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades nos drivers de modo kernel podem permitir a elevação de privilégio (2984615)</strong><br />
<br />
Esta atualização de segurança elimina três vulnerabilidades no Microsoft Windows relatadas de forma privada. A mais severa destas vulnerabilidades poderá permitir a elevação de privilégio se um invasor se conectar a um sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essas vulnerabilidades.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10)">MS14-049</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no serviço Windows Installer pode permitir a elevação de privilégio (2962490)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade no Microsoft Windows relatada de forma privada. A vulnerabilidade pode permitir a elevação de privilégio se um invasor executar um aplicativo especialmente criado que tenta reparar um aplicativo previamente instalado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-050">MS14-050</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft SharePoint Server pode permitir a elevação de privilégio (2977202)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade no Microsoft SharePoint Server relatada de forma privada. Um invasor autenticado que explore essa vulnerabilidade com êxito pode usar um aplicativo especialmente criado para executar um JavaScript arbitrário no contexto do usuário no site atual do SharePoint.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-046">MS14-046</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no .NET Framework pode permitir o desvio de recurso de segurança (2984625)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada de forma privada no Microsoft .NET Framework. A vulnerabilidade pode permitir o desvio de recurso de segurança se um usuário visitar um site especialmente criado. Em um cenário de ataque de navegação na Web, um invasor que explore com êxito esta vulnerabilidade pode anular o recurso de segurança ASLR (Address Space Layout Randomization), que ajuda a proteger os usuários de uma classe ampla de vulnerabilidades. O desvio de recurso de segurança por si mesmo não permite a execução de códigos arbitrários. No entanto, um invasor pode usar esta vulnerabilidade de desvio de ASLR junto com outra vulnerabilidade, como uma vulnerabilidade de execução remota de código, que aproveita o desvio de ASLR para executar um código arbitrário.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Desvio de recurso de segurança</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-047">MS14-047</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no LRPC pode permitir o desvio de recurso de segurança (2978668)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada de forma privada no Microsoft Windows. A vulnerabilidade pode permitir o desvio de recurso de segurança se um invasor usá-la junto com outra vulnerabilidade, como a de execução remota de código, que tira proveito do desvio ASLR para executar um código arbitrário.</td>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-043">MS14-043</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do CSyncBasePlayer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4060">CVE-2014-4060</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-044">MS14-044</a></td>
<td style="border:1px solid black;">Vulnerabilidade de XSS no SQL Master Data Services</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1820">CVE-2014-1820</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-044">MS14-044</a></td>
<td style="border:1px solid black;">Vulnerabilidade de saturação de pilha no Microsoft SQL Server</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4061">CVE-2014-4061</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-045">MS14-045</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0318">CVE-2014-0318</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-045">MS14-045</a></td>
<td style="border:1px solid black;">Vulnerabilidade de double-fetch da fonte</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1819">CVE-2014-1819</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-045">MS14-045</a></td>
<td style="border:1px solid black;">Vulnerabilidade de alocação pool do kernel do Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4064">CVE-2014-4064</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação não autorizada de informações.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-046">MS14-046</a></td>
<td style="border:1px solid black;">Vulnerabilidade de ASLR no .NET</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4062">CVE-2014-4062</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de desvio de recurso de segurança.<br />
<br />
A Microsoft não recebeu nenhuma informação indicando que essa vulnerabilidade tinha sido usada publicamente para atacar clientes quando este boletim de segurança foi lançado pela primeira vez.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-047">MS14-047</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio ASLR do LRPC</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0316">CVE-2014-0316</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de desvio de recurso de segurança.<br />
<br />
A Microsoft não recebeu nenhuma informação indicando que essa vulnerabilidade tinha sido usada publicamente para atacar clientes quando este boletim de segurança foi lançado pela primeira vez.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-048">MS14-048</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código no OneNote</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2815">CVE-2014-2815</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10)">MS14-049</a></td>
<td style="border:1px solid black;">Vulnerabilidade de Reparo do Windows Installer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1814">CVE-2014-1814</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-050">MS14-050</a></td>
<td style="border:1px solid black;">Vulnerabilidade de conteúdo da página do SharePoint</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2816">CVE-2014-2816</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2774">CVE-2014-2774</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2784">CVE-2014-2784</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2796">CVE-2014-2796</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2808">CVE-2014-2808</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2810">CVE-2014-2810</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2811">CVE-2014-2811</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Elevação de Vulnerabilidade de Privilégio do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2817">CVE-2014-2817</a></td>
<td style="border:1px solid black;">0 - Exploração detectada</td>
<td style="border:1px solid black;">0 - Exploração detectada</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">A Microsoft está ciente dos ataques limitados que tentam explorar essa vulnerabilidade.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2818">CVE-2014-2818</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Elevação de Vulnerabilidade de Privilégio do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2819">CVE-2014-2819</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2820">CVE-2014-2820</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2821">CVE-2014-2821</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2822">CVE-2014-2822</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2823">CVE-2014-2823</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2824">CVE-2014-2824</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2825">CVE-2014-2825</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2826">CVE-2014-2826</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2827">CVE-2014-2827</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4050">CVE-2014-4050</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4051">CVE-2014-4051</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4052">CVE-2014-4052</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4055">CVE-2014-4055</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4056">CVE-2014-4056</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4057">CVE-2014-4057</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4058">CVE-2014-4058</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4063">CVE-2014-4063</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-051">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4067">CVE-2014-4067</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6354">CVE-2014-4145</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6354">CVE-2014-6354</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Nenhuma</td>
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
<th colspan="7">
Windows Server 2003
  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://technet.microsoft.com/pt-br/library/security/ms14-051)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://technet.microsoft.com/pt-br/library/security/ms14-045)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10))

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://technet.microsoft.com/pt-br/library/security/ms14-046)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://technet.microsoft.com/pt-br/library/security/ms14-047)

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
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

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
Internet Explorer 6  
(2976627)  
(Moderada)  
Internet Explorer 7  
(2976627)  
(Moderada)  
Internet Explorer 8  
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2993651)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2918614)  
(Importante)

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
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(Moderada)  
Internet Explorer 7  
(2976627)  
(Moderada)  
Internet Explorer 8  
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2993651)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2918614)  
(Importante)

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
Windows Server 2003 com SP2 para sistemas baseados no Itanium

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
(Moderada)  
Internet Explorer 7  
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2993651)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://technet.microsoft.com/pt-br/library/security/ms14-051)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://technet.microsoft.com/pt-br/library/security/ms14-045)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10))

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://technet.microsoft.com/pt-br/library/security/ms14-046)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://technet.microsoft.com/pt-br/library/security/ms14-047)

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
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(Crítica)  
Internet Explorer 8  
(2976627)  
(Crítica)  
Internet Explorer 9  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2993651)  
(Importante)  
Windows Vista Service Pack 2  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
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
Internet Explorer 7  
(2976627)  
(Crítica)  
Internet Explorer 8  
(2976627)  
(Crítica)  
Internet Explorer 9  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2993651)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://technet.microsoft.com/pt-br/library/security/ms14-051)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://technet.microsoft.com/pt-br/library/security/ms14-045)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10))

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://technet.microsoft.com/pt-br/library/security/ms14-046)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://technet.microsoft.com/pt-br/library/security/ms14-047)

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
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(Moderada)  
Internet Explorer 8  
(2976627)  
(Moderada)  
Internet Explorer 9  
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2993651)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
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
Internet Explorer 7  
(2976627)  
(Moderada)  
Internet Explorer 8  
(2976627)  
(Moderada)  
Internet Explorer 9  
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2993651)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2993651)  
(Importante)  
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://technet.microsoft.com/pt-br/library/security/ms14-051)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://technet.microsoft.com/pt-br/library/security/ms14-045)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10))

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://technet.microsoft.com/pt-br/library/security/ms14-046)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://technet.microsoft.com/pt-br/library/security/ms14-047)

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
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(Crítica)  
Internet Explorer 9  
(2976627)  
(Crítica)  
Internet Explorer 10  
(2976627)  
(Crítica)  
Internet Explorer 11  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(todas as edições exceto Starter e Home Basic)  
(2978742)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2993651)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(Crítica)  
Internet Explorer 9  
(2976627)  
(Crítica)  
Internet Explorer 10  
(2976627)  
(Crítica)  
Internet Explorer 11  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(todas as edições exceto Starter e Home Basic)  
(2978742)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2993651)  
(Importante)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://technet.microsoft.com/pt-br/library/security/ms14-051)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://technet.microsoft.com/pt-br/library/security/ms14-045)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10))

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://technet.microsoft.com/pt-br/library/security/ms14-046)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://technet.microsoft.com/pt-br/library/security/ms14-047)

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
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

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
(2976627)  
(Moderada)  
Internet Explorer 9  
(2976627)  
(Moderada)  
Internet Explorer 10  
(2976627)  
(Moderada)  
Internet Explorer 11  
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2993651)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(2993651)  
(Importante)  
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 e Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://technet.microsoft.com/pt-br/library/security/ms14-051)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://technet.microsoft.com/pt-br/library/security/ms14-045)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10))

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://technet.microsoft.com/pt-br/library/security/ms14-046)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://technet.microsoft.com/pt-br/library/security/ms14-047)

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
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Media Center quando instalado no Windows 8 para sistemas de 32 bits (apenas Professional edition)  
(2978742)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2993651)  
(Importante)  
Windows 8 para sistemas de 32 bits  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(Importante)  
Microsoft .NET Framework 3.5  
(2966827)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Media Center quando instalado no Windows 8 para sistemas baseados em 64 bits (apenas Professional edition)  
(2978742)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(2993651)  
(Importante)  
Windows 8 para sistemas baseados em x64  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(Importante)  
Microsoft .NET Framework 3.5  
(2966827)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Media Center quando instalado no Windows 8,1 para sistemas de 32 bits (apenas Professional edition)  
(2978742)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(2993651)  
(Importante)  
Windows 8.1 para sistemas de 32 bits  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(Importante)  
Microsoft .NET Framework 3.5  
(2966828)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Media Center quando instalado no Windows 8,1 para sistemas baseados em 64 bits (apenas Professional edition)  
(2978742)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(2993651)  
(Importante)  
Windows 8.1 para sistemas baseados em x64  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(Importante)  
Microsoft .NET Framework 3.5  
(2966828)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 e Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://technet.microsoft.com/pt-br/library/security/ms14-051)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://technet.microsoft.com/pt-br/library/security/ms14-045)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10))

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://technet.microsoft.com/pt-br/library/security/ms14-046)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://technet.microsoft.com/pt-br/library/security/ms14-047)

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
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

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
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2993651)  
(Importante)  
Windows Server 2012  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(Importante)  
Microsoft .NET Framework 3.5  
(2966827)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(Moderada)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2993651)  
(Importante)  
Windows Server 2012 R2  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(Importante)  
Microsoft .NET Framework 3.5  
(2966828)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT e Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://technet.microsoft.com/pt-br/library/security/ms14-051)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://technet.microsoft.com/pt-br/library/security/ms14-045)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10))

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://technet.microsoft.com/pt-br/library/security/ms14-046)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://technet.microsoft.com/pt-br/library/security/ms14-047)

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
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT  
(2993651)  
(Importante)  
Windows RT  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2993651)  
(Importante)  
Windows RT 8.1  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2978668)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Opção de instalação Server Core**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-051**](http://technet.microsoft.com/pt-br/library/security/ms14-051)

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

</td>
<td style="border:1px solid black;">
[**MS14-045**](http://technet.microsoft.com/pt-br/library/security/ms14-045)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://technet.microsoft.com/pt-BR/library///technet.microsoft.com/pt-br/library/security/ms14-049(v=Security.10))

</td>
<td style="border:1px solid black;">
[**MS14-046**](http://technet.microsoft.com/pt-br/library/security/ms14-046)

</td>
<td style="border:1px solid black;">
[**MS14-047**](http://technet.microsoft.com/pt-br/library/security/ms14-047)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)

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
(2993651)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação Server Core)  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação Server Core)  
(2918614)  
(Importante)

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
(2993651)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação Server Core)  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação Server Core)  
(2918614)  
(Importante)

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
(2993651)  
(Importante)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2943357)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(2978668)  
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
(2993651)  
(Importante)  
Windows Server 2012 (instalação Server Core)  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
(Importante)  
Microsoft .NET Framework 3.5  
(2966827)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2978668)  
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
(2993651)  
(Importante)  
Windows Server 2012 R2 (instalação Server Core)  
(2976897)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(2918614)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
(Importante)  
Microsoft .NET Framework 3.5  
(2966828)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(2978668)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS14-043**

Este boletim abrange mais de uma categoria de software. Consulte as outras tabelas nesta seção para saber quais softwares foram afetados.

 

**Softwares do Microsoft Office**

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
**Softwares do Microsoft Office**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-048**](http://technet.microsoft.com/pt-br/library/security/ms14-048)

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
Service Pack 3 para Microsoft OneNote 2007

</td>
<td style="border:1px solid black;">
Service Pack 3 para Microsoft OneNote 2007  
(2596857)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
 

**Microsoft SQL Server**

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-044**](http://technet.microsoft.com/pt-br/library/security/ms14-044)

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
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3  
(GDR)  
(2977321)  
(Importante)  
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3  
(QFE)  
(2977322)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3  
(GDR)  
(2977321)  
(Importante)  
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3  
(QFE)  
(2977322)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3  
(GDR)  
(2977321)  
(Importante)  
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3  
(QFE)  
(2977322)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008 R2**

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
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 2  
(GDR)  
2977320)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 2  
(QFE)  
(2977319)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 2  
(GDR)  
(2977320)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 2  
(QFE)  
(2977319)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 2  
(GDR)  
(2977320)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 2  
(QFE)  
(2977319)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012**

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
Service Pack 1 para Microsoft SQL Server 2012 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Service Pack 1 para Microsoft SQL Server 2012 para sistemas de 32 bits  
(GDR)  
(2977326)  
(Importante)  
Service Pack 1 para Microsoft SQL Server 2012 para sistemas de 32 bits  
(QFE)  
(2977325)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Service Pack 1 para Microsoft SQL Server 2012 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Service Pack 1 para Microsoft SQL Server 2012 para sistemas baseados em x64  
(GDR)  
(2977326)  
(Importante)  
Service Pack 1 para Microsoft SQL Server 2012 para sistemas baseados em x64  
(QFE)  
(2977325)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014**

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
Microsoft SQL Server 2014 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 para sistemas baseados em x64  
(GDR)  
(2977315)  
(Importante)  
Microsoft SQL Server 2014 para sistemas baseados em x64  
(QFE)  
(2977316)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
 

**Microsoft Server Software**

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-050**](http://technet.microsoft.com/pt-br/library/security/ms14-050)

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
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013  
(2880994)  
(Importante)  
Microsoft SharePoint Foundation 2013  
(2880994)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(2880994)  
(Importante)  
Microsoft SharePoint Foundation 2013 Service Pack 1  
(2880994)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
 

**Outros softwares**

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Media Center TV Pack para Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-043**](http://technet.microsoft.com/pt-br/library/security/ms14-043)

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
<tr>
<td style="border:1px solid black;">
Windows Media Center TV Pack para Windows Vista (edições de 32 bits)

</td>
<td style="border:1px solid black;">
Windows Media Center TV Pack para Windows Vista (edições de 32 bits)  
(2978742)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Center TV Pack para Windows Vista (edições de 64 bits)

</td>
<td style="border:1px solid black;">
Windows Media Center TV Pack para Windows Vista (edições de 64 bits)  
(2978742)  
(Crítica)

</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS14-043**

Este boletim abrange mais de uma categoria de software. Consulte as outras tabelas nesta seção para saber quais softwares foram afetados.

 

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

**MS14-043**

-   Alisa Esage (@alisaesage), que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de uso após liberação do CSyncBasePlayer (CVE-2014-4060)

**MS14-045**

-   Wang Yu, da [Qihoo 360](http://www.360.cn/), por relatar a Vulnerabilidade de double-fetch da fonte (CVE-2014-1819)
-   Ilja Van Sprundel, por relatar a Vulnerabilidade de alocação pool de kernel do Windows (CVE-2014-4064)

**MS14-047**

-   [Alex Ionescu](http://www.alex-ionescu.com/), por relatar a Vulnerabilidade de desvio ASLR do LRPC (CVE-2014-0316)

**MS14-048**

-   Eduardo Prado que, que trabalha com o programa [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) da Beyond Security, por relatar a Vulnerabilidade de execução remota de código no OneNote (CVE-2014-2815)

**MS14-049**

-   Denis Gundarev, do [Entisys](http://www.entisys.com/), por relatar a Vulnerabilidade de Reparo do Windows Installer (CVE-2012-4784)
-   [Stepfan Kanthak](http://home.arcor.de/skanthak/safer.html) por trabalhar conosco em alterações de defesa profunda incluídas neste boletim

**MS14-051**

-   AbdulAziz Hariri, da [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2774)
-   Yujie Wen, da [Qihoo 360](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2784)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2796)
-   [Chen Zhang (demi6od)](https://github.com/demi6od), da [Equipe de segurança NSFOCUS](http://www.nsfocus.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2808)
-   [Chen Zhang (demi6od)](https://github.com/demi6od), da [Equipe de segurança NSFOCUS](http://www.nsfocus.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2810)
-   IronRock, que trabalha com [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2811)
-   James Forshaw, da [Context Information Security](http://www.contextis.com/), por relatar a vulnerabilidade de elevação de privilégio do Internet Explorer (CVE-2014-2817)
-   AbdulAziz Hariri, da [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2818)
-   Zeguang Zhao da [Team509](http://team509.com/) e Liang Chen, da [KeenTeam](http://www.k33nteam.org/) ( @K33nTeam), que trabalham com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatarem Vulnerabilidade a de elevação de privilégio do Internet Explorer (CVE-2014-2819)
-   Arthur Gerkis, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2820)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2821)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2822)
-   [Chen Zhang (demi6od)](https://github.com/demi6od), da [Equipe de segurança NSFOCUS](http://www.nsfocus.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2823)
-   Yuki Chen, da [Qihoo 360](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2824)
-   [Chen Zhang (demi6od)](https://github.com/demi6od), da [Equipe de segurança NSFOCUS](http://www.nsfocus.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2825)
-   [Chen Zhang (demi6od)](https://github.com/demi6od), da [Equipe de segurança NSFOCUS](http://www.nsfocus.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2826)
-   Simon Zuckerbraun, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2827)
-   [Omair](http://krash.in/), que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4050)
-   Peter "corelanc0d3r" Van Eeckhoutte, da [Corelan](http://www.corelangcv.com/), que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4051)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4052)
-   Simon Zuckerbraun, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4055)
-   Peter "corelanc0d3r" Van Eeckhoutte, da [Corelan](http://www.corelangcv.com/), que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4056)
-   Yuki Chen, da [Trend Micro](http://www.trendmicro.com/), que rabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4057)
-   Sky, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4058)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4063)
-   Wei Wang, da [VulnHunt](http://www.vulnhunt.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4067)
-   [lokihardt@ASRT](https://technet.microsoft.com/pt-BR/mailto:lokihardt@asrt), que trabalha com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products) da [HP](http://www.zerodayinitiative.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4067)
-   Omair, que trabalha com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products) [da HP](http://www.zerodayinitiative.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4145)
-   Omair, que trabalha com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products) [da HP](http://www.zerodayinitiative.com/), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-6354)

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

-   V1.0 (12 de agosto de 2014): Resumo de boletins publicado.
-   V2.0 (15 de agosto de 2014): Boletim relançado para anunciar a substituição da atualização 2982791 pela atualização 2993651 para todas as versões com suporte do Microsoft Windows. Consulte o boletim para obter detalhes.
-   V2.2 (19 de dezembro de 2014): Foi adicionada uma Avaliação do risco de exploração ao Índice de Exploração para CVE-2014-6354, no MS14-051. Esta alteração é apenas informativa.

*gerados página 2014-09-18 12:09 de Z 07:00.*
