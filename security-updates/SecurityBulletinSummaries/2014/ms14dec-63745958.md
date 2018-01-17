---
TOCTitle: 'MS14-DEC'
Title: Resumo de boletins de segurança da Microsoft de dezembro de 2014
ms:assetid: 'ms14-dec'
ms:contentKeyID: 63745958
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms14-dec(v=Security.10)'
---

 

Resumo de boletins de segurança da Microsoft de dezembro de 2014
================================================================

Publicado em: 09 de dezembro de 2014

**Version:** 1.0

Esse resumo de boletins lista os boletins de segurança lançados em dezembro de 2014.

Com o lançamento dos boletins de segurança de dezembro de 2014, este resumo de boletins substitui a notificação antecipada de boletim emitida originalmente em 04 de dezembro de 2014. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://technet.microsoft.com/pt-br/security/gg309152.aspx).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, visite [Notificações de Segurança Técnica da Microsoft](http://technet.microsoft.com/pt-br/security/dd252948.aspx).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

Resumo executivo
----------------

 
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados**.

 
<p></p>

<table style="border:1px solid black;">
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ID do boletim</strong></td>
<td style="border:1px solid black;"><strong>Título do boletim e Resumo executivo</strong></td>
<td style="border:1px solid black;"><strong>Classificação máxima de gravidade e impacto da vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>Requisitos de reinicialização</strong></td>
<td style="border:1px solid black;"><strong>Software afetado</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no servidor do Microsoft Exchange podem permitir a elevação de privilégio (3009712)<br />
<br />
</strong>Esta atualização de segurança resolve quatro vulnerabilidades relatada de forma privada no servidor do Microsoft Exchange. A mais grave de todas permite elevação de privilégio se o usuário clicar em uma URL especialmente criada para enviá-lo a um site do Outlook Web App atingido. Não há como um invasor forçar usuários a visitar o site especialmente criado. Em vez disso, o invasor teria de persuadir os usuários a visitar o site, geralmente fazendo-os clicar em um link em um email ou em uma mensagem do Instant Messenger que leve os usuários ao site do invasor, e então convencê-los a clicar em uma URL especialmente criada para isso.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (3008923)<br />
<br />
</strong>Esta atualização de segurança elimina quatorze vulnerabilidades relatadas em particular no Internet Explorer. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário visualizar uma página da Web criada especialmente usando o Internet Explorer. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a><br />
Execução de código remoto</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Word e Microsoft Office Web Apps podem permitir a execução de código remoto (3017301)<br />
<br />
</strong>Essa atualização de segurança resolve duas vulnerabilidades relatadas privadamente nos Microsoft Word e Microsoft Office Web Apps. As vulnerabilidades que podem permitir a execução de código remoto se um invasor convencer um usuário a abrir ou visualizar um arquivo do Microsoft Word especialmente criado em uma versão afetada do Microsoft Office. Um invasor que explorar com êxito as vulnerabilidades pode obter os mesmos direitos que o usuário atual. Se o usuário atual estiver conectado com direitos de administrador, um invasor poderá instalar programas, exibir, alterar ou excluir dados e criar novas contas com direitos totais do usuário. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a><br />
Execução de código remoto</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519135">MS14-082</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Office pode permitir a execução de código remoto (3017349)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office. A vulnerabilidade pode permitir a execução de código remoto se um arquivo especialmente criado for aberto em uma edição afetada do Microsoft Office. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Execução de código remoto</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Excel pode permitir a execução remota de código (3017347)<br />
<br />
</strong>Esta atualização de segurança elimina duas vulnerabilidades relatadas de forma privada no Microsoft Excel. As vulnerabilidades que podem permitir a execução de código remoto se um invasor convencer um usuário a abrir ou visualizar um arquivo do Microsoft Excel especialmente criado em uma versão afetada do Microsoft Office. Um invasor que explorar com êxito as vulnerabilidades pode obter os mesmos direitos que o usuário atual. Se o usuário atual estiver conectado com direitos de administrador, um invasor poderá instalar programas, exibir, alterar ou excluir dados e criar novas contas com direitos totais do usuário. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Execução de código remoto</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519131">MS14-084</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no mecanismo de script VBScript pode permitir execução remota de código (3016711)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no mecanismo de script VBScript no Microsoft Windows. A vulnerabilidade pode permitir a execução de código remoto caso um usuário visita um site especialmente criado. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Se um usuário atual tiver feito logon com direitos administrativos, o invasor que explorar com êxito essa vulnerabilidade poderá obter o controle total do sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a><br />
Execução de código remoto</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519129">MS14-085</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no componente do Microsoft Graphics pode permitir a divulgação de informações (3013126)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente no Microsoft Windows. A vulnerabilidade pode permitir a divulgação de informações se um usuário navega até um site que contenha conteúdo JPEG especialmente criado. Um invasor pode usar esta divulgação de informações para obter informações sobre o sistema que poderia então ser combinado com outros ataques para comprometer o sistema. A vulnerabilidade de divulgação de informações por si só não permite a execução arbitrária de código. No entanto, um invasor poderá usar essa vulnerabilidade de divulgação de informações em conjunto com outra vulnerabilidade para ignorar recursos de segurança, como o ASLR (Address Space Layout Randomization).</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
 
  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidade são listadas em ordem de ID do boletim, depois de ID do CVE. Só serão incluídas as vulnerabilidades que tiverem uma classificação de gravidade Crítico ou Importante nos boletins.
  
**Como devo usar a tabela?**  
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Índice de Exploração da Microsoft](http://technet.microsoft.com/pt-br/security/cc998259).
  
Nas colunas a seguir, "Versão Mais Recente de Software" se refere ao software, e "Versões Mais Antigas de Software" se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.
  
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
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ID do boletim</strong></td>
<td style="border:1px solid black;"><strong>Título da vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>ID do CVE</strong></td>
<td style="border:1px solid black;"><strong>Avaliação da capacidade de exploração da última versão de software</strong></td>
<td style="border:1px solid black;"><strong>Avaliação da capacidade de exploração de versão mais antiga de software</strong></td>
<td style="border:1px solid black;"><strong>Avaliação do risco de exploração para negação de serviço</strong></td>
<td style="border:1px solid black;"><strong>Principais observações</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">Vulnerabilidade de falsificação do token do Outlook Web App</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6319">CVE-2014-6319</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação não autorizada de informações. Essa vulnerabilidade pode ser usada para falsificação em um ataque de engenharia social.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">Vulnerabilidade de XSS do OWA</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6325">CVE-2014-6325</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de elevação de privilégio.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">Vulnerabilidade de XSS do OWA</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6326">CVE-2014-6326</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de elevação de privilégio.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">Vulnerabilidade de redirecionamento de URL no Exchange</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6336">CVE-2014-6336</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação não autorizada de informações. Essa vulnerabilidade pode ser usada para falsificação em um ataque de engenharia social.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6327">CVE-2014-6327</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio de filtro XSS do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6328">CVE-2014-6328</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6329">CVE-2014-6329</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6330">CVE-2014-6330</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do VBScript</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio de filtro XSS do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6365">CVE-2014-6365</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6366">CVE-2014-6366</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio de ASLR no Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6368">CVE-2014-6368</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6369">CVE-2014-6369</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6373">CVE-2014-6373</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6374">CVE-2014-6374</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6375">CVE-2014-6375</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6376">CVE-2014-6376</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-8966">CVE-2014-8966</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução de código remoto de índice inválido</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6356">CVE-2014-6356</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></td>
<td style="border:1px solid black;">Use depois de se livrar da vulnerabilidade da execução de código remoto no Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6357">CVE-2014-6357</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519135">MS14-082</a></td>
<td style="border:1px solid black;">Use o Microsoft Office Component depois de se livrar da vulnerabilidade</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6364">CVE-2014-6364</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução de código remoto gratuito global no Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6360">CVE-2014-6360</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução de código remoto do ponteiro inválido do Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6361">CVE-2014-6361</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519131">MS14-084</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do VBScript</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de execução remota de código.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519129">MS14-085</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de informações dos componentes gráficos</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6355">CVE-2014-6355</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação não autorizada de informações.</td>
</tr>
</tbody>
</table>

<p></p>

  
 
  
Software afetado  
----------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
### Componentes e sistema operacional Windows

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(Moderado)  
Internet Explorer 7  
(3008923)  
(Moderado)  
Internet Explorer 8  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5,6  
(3012168)  
(Moderado)  
VBScript 5,7  
(3012172)  
(Moderado)  
VBScript 5.8   
(3012176)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(Moderado)  
Internet Explorer 7  
(3008923)  
(Moderado)  
Internet Explorer 8  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5,6  
(3012168)  
(Moderado)  
VBScript 5,7  
(3012172)  
(Moderado)  
VBScript 5.8   
(3012176)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(Moderado)  
Internet Explorer 7  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
(Moderado)  
VBScript 5.7   
(3012172)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(Crítico)  
Internet Explorer 8  
(3008923)  
(Crítico)  
Internet Explorer 9  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(Crítico)  
VBScript 5.8   
(Somente para os sistemas com o IE8)<sup>[1]</sup>
(3012176)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(Crítico)  
Internet Explorer 8  
(3008923)  
(Crítico)  
Internet Explorer 9  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(Crítico)  
VBScript 5.8   
(Somente para os sistemas com o IE8)<sup>[1]</sup>
(3012176)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(Moderado)  
Internet Explorer 8  
(3008923)  
(Moderado)  
Internet Explorer 9  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5,7   
(3012172)  
(Moderado)  
VBScript 5.8   
(Somente para os sistemas com o IE8)<sup>[1]</sup>
(3012176)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(Moderado)  
Internet Explorer 8  
(3008923)  
(Moderado)  
Internet Explorer 9  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(Moderado)  
VBScript 5.8   
(Somente para os sistemas com o IE8)<sup>[1]</sup>
(3012176)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(Crítico)  
Internet Explorer 9  
(3008923)  
(Crítico)  
Internet Explorer 10  
(3008923)  
(Crítico)  
Internet Explorer 11  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(Somente para os sistemas com o IE8)<sup>[1]</sup>
(3012176)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(Crítico)  
Internet Explorer 9  
(3008923)  
(Crítico)  
Internet Explorer 10  
(3008923)  
(Crítico)  
Internet Explorer 11  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(Somente para os sistemas com o IE8)<sup>[1]</sup>
(3012176)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(Moderado)  
Internet Explorer 9  
(3008923)  
(Moderado)  
Internet Explorer 10  
(3008923)  
(Moderado)  
Internet Explorer 11  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(Somente para os sistemas com o IE8)<sup>[1]</sup>
(3012176)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados no Itanium

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(Somente para os sistemas com o IE8)<sup>[1]</sup>
(3012176)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados no Itanium  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 e Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 e Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(Moderado)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT e Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Opção de instalação Server Core**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
VBScript 5,7   
(3012172)  
(Nenhuma classificação de gravidade)<sup>[2]</sup>
VBScript 5.8   
(3012176)  
(Nenhuma classificação de gravidade)<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
VBScript 5,7   
(3012172)  
(Nenhuma classificação de gravidade)<sup>[2]</sup>
VBScript 5.8   
(3012176)  
(Nenhuma classificação de gravidade)<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3013126)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(3012176)  
(Nenhuma classificação de gravidade)<sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3013126)  
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
(3013126)  
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
(3013126)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
**Observação para o MS14-080**

As visualizações técnicas do Windows e do Windows são afetadas. Recomenda-se que os consumidores que estiverem executando esses sistemas operacionais apliquem a atualização, que está disponível no [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=pt-br). 

**Observações para o MS14-084**

Uma atualização do VBScript 5.8 está disponível para o Windows Technical Preview e Windows Server Technical Preview e é fornecida através da Atualização Cumulativa do Internet Explorer 3008923 ([MS14-080](http://go.microsoft.com/fwlink/?linkid=521659)). Recomenda-se que os consumidores que estiverem executando as edições Preview apliquem a atualização, que está disponível no [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=pt-br).

<sup>[1]</sup>Aplicável aos sistemas com o Internet Explorer 8 instalado. Clientes com sistemas executando o Internet Explorer 9 ou posterior devem aplicar a Atualização Cumulativa do Internet Explorer ([MS14-080](http://go.microsoft.com/fwlink/?linkid=521659)), que também aborda a vulnerabilidade discutida no MS14-084.

<sup>[2]</sup>As classificações de gravidade não são aplicadas para o software especificado porque os vetores de ataque conhecidos no Internet Explorer para a vulnerabilidade discutida no MS14-084 estão bloqueados. No entanto, como uma medida de defesa profunda, a Microsoft recomenda que os clientes desse software apliquem essa atualização de segurança para ajudar a proteger contra possíveis novos vetores de ataque identificados no futuro.

 

### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-075**](https://technet.microsoft.com/pt-br/library/security/ms14-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2996150)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-075**](https://technet.microsoft.com/pt-br/library/security/ms14-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2986475)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3011140)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
Atualização Cumulativa 6 do Microsoft Exchange Server 2013  
(3011140)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
 

### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2920793)  
(Crítico)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2596927)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2984942)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(2899518)  
(Crítico)  
Microsoft Word 2010 Service Pack 2 (edições de 32 bits)  
(2899519)  
(Crítico)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(2553154)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (edições de 32 bits)  
(2910902)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(2899518)  
(Crítico)  
Microsoft Word 2010 Service Pack 2 (edições de 64 bits)  
(2899519)  
(Crítico)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(2553154)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (edições de 64 bits)  
(2910902)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013 e Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (edições de 32 bits)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 (edições de 32 bits)  
(2910916)  
(Crítico)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (edições de 32 bits)  
(2726958)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (edições de 32 bits)  
(2910929)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (edições de 32 bits)  
(2910916)  
(Crítico)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)  
(2726958)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (edições de 32 bits)  
(2910929)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (edições de 64 bits)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 (edições de 64 bits)  
(2910916)  
(Crítico)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (edições de 64 bits)  
(2726958)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (edições de 64 bits)  
(2910929)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (edições de 64 bits)  
(2910916)  
(Crítico)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)  
(2726958)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (edições de 64 bits)  
(2910929)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT  
(2910916)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2726958)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2910929)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT Service Pack 1  
(2910916)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2726958)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(2910929)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office para Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
Microsoft Office para Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office para Mac 2011  
(3018888)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Outros softwares do Office**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2920729)  
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
Pacote de compatibilidade do Microsoft Office Service Pack 3

</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(2920792)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(2920790)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
**Observação para o MS14-081**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nessa seção para mais software afetados. 

 

### Microsoft Office Services e Web Apps

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Serviços de Automação do Word  
(2899581)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Serviços de Automação do Word  
(2883050)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Serviços de Automação do Word  
(2883050)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2910892)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2889851)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(2889851)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
**Observação para o MS14-081**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nessa seção para mais software afetados. 

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O Microsoft Baseline Security Analyzer (MBSA) permite aos administradores procurar em sistemas remotos e locais para as atualizações de segurança que ainda não foram instaladas e por erros comuns em configuração de segurança.

O Windows Server Update Services (WSUS), o Systems Management Server (SMS) e o System Center Configuration Manager ajudam os administradores a distribuir atualizações de segurança.

Os componentes do Avaliador de Compatibilidade de Atualizações, incluídos no Kit de Ferramentas de Compatibilidade de Aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para obter mais informações sobre essas e outras ferramentas disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/pt-br/security/cc297183). 

Agradecimentos
--------------

 
A Microsoft reconhece os esforços dos membros da comunidade de segurança que nos ajudam a proteger os consumidores graças à divulgação responsável de vulnerabilidades. Consulte [Agradecimentos](https://technet.microsoft.com/pt-br/library/security/dn820091.aspx) para obter mais informações.

Outras informações
------------------

 
### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

Em relação ao lançamento de boletins que ocorre na segunda terça-feira do mês, a Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows no Windows Update, Microsoft Update, Windows Server Update Services e Centro de Download. Nenhuma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows está disponível para os lançamentos de boletins de segurança desvinculados.

### Atualizações não relacionadas à segurança no MU, WU e WSUS

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 do Banco de Dados de Conhecimento da Microsoft](https://support.microsoft.com/kb/894199/pt-br): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/pt-br/windowsserver/bb332157.aspx). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://technet.microsoft.com/pt-br/security/dn467918).

### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://technet.microsoft.com/pt-br/library/bb466251.aspx) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://www.microsoft.com/downloads/results.aspx?displaylang=pt-br&freetext=security%20update). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=pt-br).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [artigo 913086 da Base de Dados de Conhecimento da Microsoft](https://support.microsoft.com/kb/913086/pt-br).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://technet.microsoft.com/pt-br/security/cc136632.aspx).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://support2.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle).

Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/pt-br/security/bb980617)

Ajude a proteger seu computador executando o Windows contra vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=pt-br)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx?ln=pt-br)

### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Dados de Conhecimento da Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (9 de dezembro de 2014): Resumo do boletim publicado.

*Página gerada em 04-12-2014 13:31Z-08:00.*
