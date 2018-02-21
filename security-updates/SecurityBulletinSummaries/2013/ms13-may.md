---
TOCTitle: 'MS13-MAY'
Title: Resumo do Boletim de Segurança da Microsoft de maio 2013
ms:assetid: 'ms13-may'
ms:contentKeyID: 61233703
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms13-may(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de maio 2013
========================================================

Publicado: terça-feira, 14 de maio de 2013 | Atualizado: quarta-feira, 22 de maio de 2013

**Versão:** 1.1

Este resumo de boletins lista os boletins de segurança lançados em maio de 2013.

Com o lançamento dos boletins de segurança de maio de 2013, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 9 de maio de 2013. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 15 de maio de 2013, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de maio](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538728&culture=en-us). Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538728&culture=en-us).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

#### Sinopses

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (2829530)  <br />
<br />
</strong>Esta atualização de segurança elimina onze vulnerabilidades relatadas em particular no Internet Explorer. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que conseguir explorar a mais severa das vulnerabilidades poderá obter os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-038">MS13-038</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança</strong> <strong>para o Internet Explorer (2847204)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente no Internet Explorer. A vulnerabilidade pode permitir a execução remota de código se um usuário visualizar uma página da Web especialmente criada no Internet Explorer. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-039">MS13-039</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no HTTP.sys pode permitir a negação de serviço (2829254)</strong> <strong><br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir negação de serviço se o invasor enviar um pacote HTTP especialmente criado para um servidor ou cliente afetado do Windows.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-040">MS13-040</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no .NET Framework podem permitir falsificação (2836440)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular e uma vulnerabilidadedivulgada publicamente no .NET Framework. A mais severa das vulnerabilidades pode permitir a falsificação caso um aplicativo do .NET receba um arquivo de XML especialmente criado. O invasor que conseguir explorar as vulnerabilidades poderá modificar o conteúdo de um arquivo de XML sem invalidar a assinatura do arquivo e acessar funções importantes como se fosse um usuário autenticado.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Falsificação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-041">MS13-041</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Lync pode permitir a execução remota de código (2834695)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Lync. A vulnerabilidade pode permitir execução remota de código se o invasor compartilhar conteúdo especialmente criado, como um arquivo ou programa, como uma apresentação no Lync ou Communicator, e então convencer o usuário a aceitar um convite para visualizar ou compartilhar o conteúdo apresentável. Em todos os casos, o invasor não tem como forçar os usuários a visualizar ou compartilhar o arquivo ou programa controlado pelo invasor. Em vez disso, o invasor precisa convencer os usuários a realizar uma ação, geralmente os fazendo aceitar um convite no Lync ou Communicator para visualizar ou compartilhar o conteúdo apresentável.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Publisher podem permitir a execução remota de código (2830397)  <br />
<br />
</strong>Esta atualização de segurança elimina 11 vulnerabilidades relatadas em particular no Microsoft Office. As vulnerabilidades podem permitir a execução remota de código se um usuário abrir um arquivo do Publisher especialmente criado com uma versão afetada do Microsoft Publisher. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-043">MS13-043</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no</strong> <strong>Microsoft Word pode permitir a execução remota de código (2830399)</strong> <strong><br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office. A vulnerabilidade poderá permitir a execução de código se o usuário abrir um arquivo especialmente criado ou visualizar uma mensagem de email com uma versão afetada do software do Microsoft Office. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-044">MS13-044</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Visio pode permitir a divulgação de informações (2834692)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office. A vulnerabilidade pode permitir a divulgação não autorizada de informações se um usuário abrir um arquivo especialmente criado do Visio. Observe que essa vulnerabilidade não permite que um invasor execute códigos nem aumente seus direitos de usuário diretamente, mas ela pode ser usada para gerar informações úteis que poderiam ser usadas para tentar comprometer ainda mais o sistema afetado.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-045">MS13-045</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Windows Essentials pode permitir a divulgação não autorizada de informações (2813707)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Windows Essentials. A vulnerabilidade pode permitir a divulgação não autorizada de informações se o usuário abrir o Windows Writer usando uma URL especialmente criada. O invasor que conseguir explorar a vulnerabilidade poderá anular configurações de proxy do Windows Writer e sobrescrever arquivos acessíveis ao usuário no sistema de destino. No cenário de ataque na Web, um site pode conter um link especialmente criado usado para explorar esta vulnerabilidade. O invasor precisa convencer os usuários a visitar o site e abrir o link especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows Essentials</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-046">MS13-046</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades nos drivers do modo kernel podem permitir a elevação de privilégio (2840221)</strong> <br />
<br />
Esta atualização de segurança elimina três vulnerabilidades relatadas em particular no Microsoft Windows. As vulnerabilidades podem permitir elevação de privilégio se um invasor faz logon no sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essas vulnerabilidades.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
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
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Índice de exploração da Microsoft](http://technet.microsoft.com/security/cc998259).
  
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0811">CVE-2013-0811</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de informações de array JSON</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1297">CVE-2013-1297</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação de informações.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1306">CVE-2013-1306</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1307">CVE-2013-1307</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1308">CVE-2013-1308</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1309">CVE-2013-1309</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1310">CVE-2013-1310</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1311">CVE-2013-1311</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1312">CVE-2013-1312</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-2551">CVE-2013-2551</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-037">MS13-037</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3140">CVE-2013-3140</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-038">MS13-038</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1347">CVE-2013-1347</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente.<br />
<br />
A Microsoft está ciente dos ataques que tentam explorar essa vulnerabilidade no Internet Explorer 8.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-039">MS13-039</a></td>
<td style="border:1px solid black;">Vulnerabilidade na negação de serviço em HTTP.sys</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1305">CVE-2013-1305</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-040">MS13-040</a></td>
<td style="border:1px solid black;">Vulnerabilidade de falsificação de assinatura digital XML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1336">CVE-2013-1336</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de falsificação.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-040">MS13-040</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio de autenticação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1337">CVE-2013-1337</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente.<br />
<br />
Esta é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-041">MS13-041</a></td>
<td style="border:1px solid black;">Vulnerabilidade de RCE no Lync</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1302">CVE-2013-1302</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de alocação de valor negativo no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1316">CVE-2013-1316</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de número inteiro no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1317">CVE-2013-1317</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de ponteiro de interface corrompido no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1318">CVE-2013-1318</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de controle de valor de retorno no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1319">CVE-2013-1319</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de buffer no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1320">CVE-2013-1320</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de validação de valor de retorno no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1321">CVE-2013-1321</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de verificação de intervalo inválido no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1322">CVE-2013-1322</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de controle de valor NULL incorreto no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1323">CVE-2013-1323</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de número inteiro assinado no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1327">CVE-2013-1327</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de controle de ponteiro no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1328">CVE-2013-1328</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-042">MS13-042</a></td>
<td style="border:1px solid black;">Vulnerabilidade de subfluxo de buffer no Publisher</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1329">CVE-2013-1329</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-043">MS13-043</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de forma do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1335">CVE-2013-1335</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-044">MS13-044</a></td>
<td style="border:1px solid black;">Vulnerabilidade de resolução de entidades externas de XML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1301">CVE-2013-1301</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação de informações.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-045">MS13-045</a></td>
<td style="border:1px solid black;">Vulnerabilidade de manipulação indevida de URL no Windows Essentials</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0096">CVE-2013-0096</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-046">MS13-046</a></td>
<td style="border:1px solid black;">Vulnerabilidade de fetch duplo do subsistema kernel de gráficos do DirectX</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1332">CVE-2013-1332</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MS13-046</td>
<td style="border:1px solid black;">Vulnerabilidade de estouro do buffer do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1333">CVE-2013-1333</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-046">MS13-046</a></td>
<td style="border:1px solid black;">Vulnerabilidade de controle de janelas no Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1334">CVE-2013-1334</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(Crítica)  
Internet Explorer 7   
(2829530)  
(Crítica)  
Internet Explorer 8   
(2829530)  
(Crítica)
</td>
<td style="border:1px solid black;">
Internet Explorer 8   
(2847204)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2829361)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(Crítica)  
Internet Explorer 7   
(2829530)  
(Crítica)  
Internet Explorer 8   
(2829530)  
(Crítica)
</td>
<td style="border:1px solid black;">
Internet Explorer 8   
(2847204)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2829361)  
(Importante)
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(Moderada)  
Internet Explorer 7  
(2829530)  
(Moderada)  
Internet Explorer 8  
(2829530)  
(Moderada)
</td>
<td style="border:1px solid black;">
Internet Explorer 8   
(2847204)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(Moderada)  
Internet Explorer 7  
(2829530)  
(Moderada)  
Internet Explorer 8  
(2829530)  
(Moderada)
</td>
<td style="border:1px solid black;">
Internet Explorer 8   
(2847204)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2829530)  
(Moderada)  
Internet Explorer 7  
(2829530)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2829361)  
(Nenhuma classificação de gravidade)
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(Crítica)  
Internet Explorer 8  
(2829530)  
(Crítica)  
Internet Explorer 9   
(2829530)  
(Crítica)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(Crítica)  
Internet Explorer 9   
(2847204)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804582)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2830290)  
(Importante)  
Windows Vista Service Pack 2  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(Crítica)  
Internet Explorer 8  
(2829530)  
(Crítica)  
Internet Explorer 9   
(2829530)  
(Crítica)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(Crítica)  
Internet Explorer 9   
(2847204)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804582)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2830290)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(2829361)  
(Nenhuma classificação de gravidade)
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(Moderada)  
Internet Explorer 8  
(2829530)  
(Moderada)  
Internet Explorer 9   
(2829530)  
(Moderada)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(Moderada)  
Internet Explorer 9   
(2847204)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804582)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2830290)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(Moderada)  
Internet Explorer 8  
(2829530)  
(Moderada)  
Internet Explorer 9   
(2829530)  
(Moderada)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(Moderada)  
Internet Explorer 9   
(2847204)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804582)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2830290)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2830290)  
(Importante)  
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2829361)  
(Nenhuma classificação de gravidade)
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(Crítica)  
Internet Explorer 9   
(2829530)  
(Crítica)  
Internet Explorer 10   
(2829530)  
(Crítica)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(Crítica)  
Internet Explorer 9   
(2847204)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804582)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2830290)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2829361)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(Crítica)  
Internet Explorer 9   
(2829530)  
(Crítica)  
Internet Explorer 10   
(2829530)  
(Crítica)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(Crítica)  
Internet Explorer 9   
(2847204)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804582)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2830290)  
(Importante)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2829361)  
(Importante)
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(Moderada)  
Internet Explorer 9   
(2829530)  
(Moderada)  
Internet Explorer 10   
(2829530)  
(Moderada)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(Moderada)  
Internet Explorer 9   
(2847204)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804582)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2830290)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(Moderada)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2830290)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2829361)  
(Nenhuma classificação de gravidade)
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
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
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2829530)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2829254)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804583)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2830290)  
(Importante)  
Windows 8 para sistemas de 32 bits  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2829530)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits  
(2829254)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804583)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits  
(2830290)  
(Importante)  
Windows 8 para sistemas de 64 bits  
(2829361)  
(Nenhuma classificação de gravidade)
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2829530)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2829254)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804583)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2830290)  
(Importante)  
Windows Server 2012  
(2829361)  
(Nenhuma classificação de gravidade)
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2829530)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows RT  
(2829254)  
(Moderada)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2804583)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT  
(2830290)  
(Importante)  
Windows RT  
(2829361)  
(Nenhuma classificação de gravidade)
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
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)  
(2830290)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)  
(2829361)  
(Nenhuma classificação de gravidade)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do núcleo do servidor)  
(2830290)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do núcleo do servidor)  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)
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
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(Importante)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804582)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)  
(2830290)  
(Importante)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr class="alternateRow">
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
(2829254)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(Importante)  
Microsoft .NET Framework 4.5  
(2804583)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2830290)  
(Importante)  
Windows Server 2012 (instalação Server Core)  
(2829361)  
(Nenhuma classificação de gravidade)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS13-040**

<sup>[1]</sup>**.NET Framework 4 e .NET Framework 4 Client Profile afetados.** Os pacotes redistribuíveis do .Net Framework versão 4 estão disponíveis em dois perfis: .NET Framework 4 e .NET Framework 4 Client Profile. O .NET Framework 4 Client Profile é um subconjunto do .NET Framework 4. A vulnerabilidade abordada nesta atualização afeta tanto o .NET Framework 4 quanto o .NET Framework 4 Client Profile. Para obter mais informações, consulte o artigo de MSDN, [Instalando o .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="4">
Softwares do Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-042**](http://go.microsoft.com/fwlink/?linkid=287106)
</td>
<td style="border:1px solid black;">
[**MS13-043**](http://go.microsoft.com/fwlink/?linkid=287107)
</td>
<td style="border:1px solid black;">
[**MS13-044**](http://go.microsoft.com/fwlink/?linkid=293446)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2003 Service Pack 3  
(2810047)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Word 2003 Service Pack 3  
(2810046)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2007 Service Pack 3  
(2597971)  
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
Microsoft Office 2010 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2010 Service Pack 1 (edições de 32 bits)  
(2553147)  
(Importante)
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
Microsoft Office 2010 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2010 Service Pack 1 (edições de 64 bits)  
(2553147)  
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
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2817361)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2003 Service Pack 3 
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Visio 2003 Service Pack 3   
(2810062)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 3 
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 3   
(2596595)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2010 Service Pack 1 (edições de 32 bits) 
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Visio 2010 Service Pack 1 (edições de 32 bits)   
(2810068)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2010 Service Pack 1 (edições de 64 bits) 
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Visio 2010 Service Pack 1 (edições de 64 bits)   
(2810068)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

#### Softwares e Plataformas de Comunicação da Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Lync
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-041**](http://go.microsoft.com/fwlink/?linkid=293445)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Communicator 2007 R2
</td>
<td style="border:1px solid black;">
Microsoft Communicator 2007 R2  
(2827753)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 bits)  
(2827750)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 bits)  
(2827750)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(instalação de nível administrativo)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(instalação de nível administrativo)  
(2827752)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(instalação de nível usuário)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(instalação de nível usuário)  
(2827751)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Web Components Server)
</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Web Components Server)  
(2827754)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

#### Ferramentas e softwares para consumidores Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Windows Essentials
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-045**](http://go.microsoft.com/fwlink/?linkid=280675)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Essentials 2011
</td>
<td style="border:1px solid black;">
Windows Essentials 2011   
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Essentials 2012
</td>
<td style="border:1px solid black;">
Windows Essentials 2012   
(2813707)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Microsoft Safety & Security Center](http://www.microsoft.com/brasil/security), onde essas informações também estão disponíveis, clicando em “Atualizações de segurança”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) e no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade executando uma pesquisa com a palavra-chave "atualização de segurança".

Para os clientes do Microsoft Office for Mac, o Microsoft AutoUpdate for Mac pode ajudar a manter seu software Microsoft atualizado. Para obter mais informações sobre como usar o Microsoft AutoUpdate for Mac, consulte [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS13-001"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Frequentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

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

Em relação ao lançamento de boletins que ocorre na segunda terça-feira do mês, a Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows no Windows Update, Microsoft Update, Windows Server Update Services e Centro de Download. Nenhuma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows está disponível para os lançamentos de boletins de segurança desvinculados.

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

**MS13-037**

-   Jose Antonio Vazquez Gonzalez, que trabalha na [VeriSign iDefense Labs](http://labs.idefense.com), por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-0811)
-   Yosuke Hasegawa e Masahiro Yamada, por reportar a Vulnerabilidade de divulgação de informações de array JSON - (CVE-2013-1297)
-   SkyLined, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP,](http://www.hpenterprisesecurity.com/products) por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1306)
-   Scott Bell, da [Security-Assessment.com](http://www.security-assessment.com/), por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1306)
-   Ivan Fratric, da [Google Inc](http://www.google.com/), por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1307)
-   [Aniway.Aniway@gmail.com](mailto:aniway.anyway@gmail.com)
-   , que trabalha com a
-   [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   da
-   [HP](http://www.hpenterprisesecurity.com/products)
-   , por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1308)
-   SkyLined, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP,](http://www.hpenterprisesecurity.com/products) por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1309)
-   Yuhong Bao, por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1310)
-   Scott Bell, da [Security-Assessment.com](http://www.security-assessment.com/), por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1311)
-   Stephen Fewer, da [Harmony Security](http://www.harmonysecurity.com), que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1312)
-   [VUPEN Security](http://www.vupen.com)
-   (Pwn2Own 2013), que trabalha com a
-   [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   da
-   [HP](http://www.hpenterprisesecurity.com/products)
-   , por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-2551)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-3140)
-   Masato Kinugawa por trabalhar conosco em alterações de defesa abrangentes incluídas neste boletim
-   [VUPEN Security](http://www.vupen.com)
-   (Pwn2Own 2013), que trabalha com a
-   [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)
-   da
-   [HP](http://www.zerodayinitiative.com/)
-   , por trabalhar conosco em alterações de defesa abrangentes incluídas neste boletim

**MS13-038**

-   Daniel Caselden da [FireEye](http://www.fireeye.com/) por relatar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1347)
-   [A iSIGHT Partners](http://www.isightpartners.com/)
-   por trabalhar conosco na Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1347)

**MS13-039**

-   Marek Kroemeke, 22733db72ab3ed94b5f8a1ffcde850251fe6f466, AKAT-1, da [Zero Day Initiative](http://www.hpenterprisesecurity.com/products) da [HP](http://www.zerodayinitiative.com/), por reportar a Vulnerabilidade de negação de serviço em HTTP.sys (CVE-2013-1305)

**MS13-040**

-   James Forshaw, da [Context Information Security](http://www.contextis.com/), por reportar a Vulnerabilidade de falsificação de assinatura digital XML (CVE-2013-1336)

**MS13-042**

-   Will Dormann, do [CERT/CC](http://www.cert.org/), por trabalhar conosco em diversas Vulnerabilidades de execução remota de código no Microsoft Publisher (CVE-2013-1316, CVE-2013-1317, CVE-2013-1318, CVE-2013-1319, CVE-2013-1320, CVE-2013-1321, CVE-2013-1322, CVE-2013-1323, CVE-2013-1327, CVE-2013-1328 e CVE-2013-1329)

**MS13-043**

-   Will Dormann, do [CERT/CC](http://www.cert.org/), por reportar a Vulnerabilidade de corrupção de forma do Word (CVE-2013-1335)

**MS13-044**

-   Timur Yunusov, da [Positive Technologies](http://www.ptsecurity.com/), por reportar a Vulnerabilidade de resolução de entidades externas de XML (CVE-2013-1301)

**MS13-045**

-   Andrea Micalizzi, que trabalha com a equipe da [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) da Beyond Security, por reportar a Vulnerabilidade de manipulação indevida de URL no Windows Essentials (CVE-2013-0096)

**MS13-046**

-   [Gynvael Coldwind](http://gynvael.coldwind.pl/)
-   e
-   [Mateusz “j00ru" Jurczyk,](http://j00ru.vexillium.org/)
-   da
-   [Google Inc,](http://www.google.com/)
-   por reportarem a Vulnerabilidade de fetch duplo do subsistema kernel de gráficos do DirectX - (CVE-2013-1332)
-   [Qihoo 360 Security Center](http://www.360.cn/)
-   por reportar a Vulnerabilidade de estouro de buffer no Win32k - (CVE-2013-1333)
-   Um pesquisador anônimo, que trabalha na [iDefense VCP](http://labs.idefense.com/), por reportar a Vulnerabilidade de controle de janelas no Win32k - (CVE-2013-1334)

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (14 de maio de 2013): Resumo de boletins publicado.
-   V1.1 (22 de maio de 2013): Para o MS13-037, corrigido o número da Common Vulnerabilities and Exposures no CVE-2013-3140. Esta é apenas uma alteração informativa.

*Built at 2014-04-18T01:50:00Z-07:00*
