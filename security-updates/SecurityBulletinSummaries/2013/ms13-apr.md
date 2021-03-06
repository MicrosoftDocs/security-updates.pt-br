---
TOCTitle: 'MS13-APR'
Title: Resumo do Boletim de Segurança da Microsoft de abril 2013
ms:assetid: 'ms13-apr'
ms:contentKeyID: 61233695
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms13-apr(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de abril 2013
=========================================================

Publicado: terça-feira, 9 de abril de 2013 | Atualizado: terça-feira, 25 de junho de 2013

**Versão:** 4.0

Este resumo de boletins lista os boletins de segurança lançados em abril de 2013.

Com o lançamento dos boletins de segurança de abril de 2013, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 4 de abril de 2013. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 10 de abril de 2013, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de abril](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538640&culture=pt-br). Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538640&culture=pt-br).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (2817183)  <br />
<br />
</strong>Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Internet Explorer. Essas vulnerabilidades podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286679">MS13-029</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Remote Desktop Client pode permitir a execução remota de código (2828223)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no cliente de área de trabalho remota do Windows. A vulnerabilidade pode permitir a execução remota de código caso um usuário exiba uma página da Web especialmente criada. O invasor que explorar com êxito a vulnerabilidade poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286577">MS13-030</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no SharePoint pode permitir divulgação não autorizada de informações (2827663)  <br />
<br />
</strong>Esta atualização de segurança trata uma vulnerabilidade divulgada publicamente no Microsoft SharePoint Server. A vulnerabilidade pode permitir divulgação não autorizada de informação se o invasor conseguir determinar o endereço ou local de uma lista específica do SharePoint, obtendo acesso ao site do SharePoint onde a lista é mantida. O invasor precisaria atender aos requisitos de autenticação do site do SharePoint para explorar esta vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante </a><br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282388">MS13-031</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no kernel do Windows podem permitir a elevação de privilégio (2813170)  <br />
<br />
</strong>Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft Windows. As vulnerabilidades podem permitir elevação de privilégio se um invasor faz logon no sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essas vulnerabilidades.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante </a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280660">MS13-032</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Active Directory pode permitir a negação de serviço (2830914)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Active Directory. A vulnerabilidade pode permitir a negação de serviço se um invasor enviar uma consulta especialmente criada ao serviço Lightweight Directory Access Protocol (LDAP).</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante </a><br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286700">MS13-033</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Windows Client/Server Runtime Subsystem (CSRSS) pode permitir elevação de privilégio (2820917)  <br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada em todas as edições com suporte do Windows XP, Windows Vista, Windows Server 2003 e Windows Server 2008. A vulnerabilidade pode permitir elevação de privilégio se o invasor efetuar login no sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante </a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276805">MS13-034</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Cliente antimalware da Microsoft pode permitir a elevação de privilégio (2823482)  <br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade reportada em particular no Cliente antimalware da Microsoft. A vulnerabilidade pode permitir elevação de privilégio devido ao nome de caminho usado pelo Cliente antimalware da Microsoft. Um invasor que explore com êxito esta vulnerabilidade pode causar a execução de código arbitrário e assumir o controle total do sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. O invasor deve ter credenciais de logon válidas para explorar esta vulnerabilidade. Essa vulnerabilidade não pode ser explorada por usuários anônimos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante </a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Software de segurança da Microsoft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285672">MS13-035</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade de limpeza</strong> <strong>de HTML pode permitir a elevação de privilégios (2821818)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office. A vulnerabilidade pode permitir a elevação de privilégios se um invasor enviar conteúdo especialmente criado para um usuário.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante </a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=281927">MS13-036</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no driver do modo kernel podem permitir a elevação de privilégio (2829996)</strong> <br />
<br />
Esta atualização de segurança resolve três vulnerabilidades reportadas em particular e uma divulgada publicamente no Microsoft Windows. A mais severa destas vulnerabilidades poderá permitir a elevação de privilégio se um invasor se conectar a um sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar as vulnerabilidades mais severas.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante </a><br />
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1303">CVE-2013-1303</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1304">CVE-2013-1304</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1338">CVE-2013-1338</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286679">MS13-029</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução de código remoto do controle Active X no RDP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1296">CVE-2013-1296</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286577">MS13-030</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação não autorizada de informação de direitos de acesso incorretos</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1290">CVE-2013-1290</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação de informações.<br />
<br />
Essa vulnerabilidade foi divulgada publicamente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282388">MS13-031</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do kernel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1284">CVE-2013-1284</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282388">MS13-031</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do kernel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1294">CVE-2013-1294</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280660">MS13-032</a></td>
<td style="border:1px solid black;">Vulnerabilidade de consumo de memória</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1282">CVE-2013-1282</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286700">MS13-033</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do CSRSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1295">CVE-2013-1295</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">No Windows Server 2003 e Windows XP Professional x64 Edition, esta é uma vulnerabilidade de elevação de privilégio.<br />
<br />
No Windows XP, Windows Vista e Windows Server 2008, esta é uma uma vulnerabilidade de negação de serviço.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276805">MS13-034</a></td>
<td style="border:1px solid black;">Vulnerabilidade de nome de caminho impróprio de antimalware da Microsoft</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0078">CVE-2013-0078</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285672">MS13-035</a></td>
<td style="border:1px solid black;">Vulnerabilidade de limpeza de HTML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1289">CVE-2013-1289</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">A Microsoft está ciente dos ataques direcionados que tentam explorar a vulnerabilidade.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=281927">MS13-036</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1283">CVE-2013-1283</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=281927">MS13-036</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1292">CVE-2013-1292</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
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
<th colspan="7">
Windows XP (site em inglês)  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f7b699b1-7655-4c8f-bd1a-535ff210b338)   
(2817183)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e9f9848e-b926-4487-9dc2-b2a6b6f5f98e)   
(2817183)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4cf0de09-2e8d-4be0-bbbf-d040164f22e0)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=353812de-b1eb-4245-82e3-7829cb72bba3)  
(2813345)  
(Crítica)  
[Remote Desktop Connection 7.0 Client](http://www.microsoft.com/downloads/details.aspx?familyid=1754fdde-4744-4783-b6d3-e38eb2874b58)  
(2813347)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=69de7e3c-d99b-432a-b286-f45841edc4a7)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=8adb6ced-6065-454b-ba67-b0acd621df76)  
(2801109)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f47a73d3-05f6-4c7d-b063-c83dd0070c2d)  
(2820917)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=75914c2a-37bb-4541-81ed-a602acb27a14)  
(2808735)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=4496bce8-809e-458c-b199-49b32eef7b21)   
(2817183)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9d792ad9-c2d7-4972-9f27-4580af04571c)   
(2817183)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c3bdbbb8-57a2-4474-9b86-239f7a77e658)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=f413845a-84e0-48d9-b5bc-56a37109ab33)  
(2813345)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=74855fb1-cad1-463f-a02d-1c27a39667c9)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=9fb780b9-bbca-45ec-98db-da413f0ccddf)  
(2801109)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c143a028-2c38-469f-a563-be8030ec76e3)  
(2820917)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=20a1f311-5cdc-4675-a228-32993d8be3f9)  
(2808735)  
(Importante)
</td>
</tr>
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
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=8d834fd2-eaa0-4742-a8a2-93277ca41f91)   
(2817183)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b0cbbaaf-be40-4088-b3d3-ca85410807b7)  
(2817183)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cd2731b3-406e-4b73-bd70-4f2bb16dfb08)  
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=75b00750-80c3-4ffa-adbf-5f40a41309b9)  
(2813345)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2c242d48-8dbe-4474-ba39-f7e3ebe9a604)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=c27666a5-67ff-4e2d-b9d7-2cef19da1edd)  
(2772930)  
(Importante)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=13eb9459-0a39-4652-b577-6d8509801f62)  
(2801109)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=63ffbd1a-79a9-47c8-a904-b6e9a0fb626f)  
(2820917)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0722d681-eda8-48af-b079-36d45eb20f98)  
(2808735)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7149ecda-78d3-4289-81b2-5133cd9b4564)   
(2817183)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f22de9fa-96e0-4a09-8923-8731e0de38c9)  
(2817183)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=08c55acd-4c5e-4d5e-b524-19fd449e5c50)  
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=7efb8816-ca23-4a75-a0cc-53a663eac3a9)  
(2813345)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b7af0c30-0d09-434a-85d6-69e7e9ee9e29)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=1b009894-8503-42b6-85d1-1285ed14bef9)  
(2772930)  
(Importante)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=30c0c8d8-df70-4637-bea4-96e2e4d2cb28)  
(2801109)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bf96696e-13a4-4b01-a8d9-60654d7d1ac5)  
(2820917)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fc5f39a7-e89b-4ef0-887c-873ad546fb65)  
(2808735)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b10b94db-b281-46b6-b301-58f14de327d2)   
(2817183)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9d799925-5f8e-43c8-8674-19437a7a6c99)  
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=54e286a0-22f5-4b34-a246-c98c0647f093)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=0b65be9e-724d-469d-ba3b-93d8b174aecb)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=c56d776a-4293-4d3c-bcac-cd5f50eeb328)  
(2820917)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=dd159949-e0f0-4515-876d-837758a3fd51)  
(2808735)  
(Importante)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5591feef-5bc6-4e3e-9bbb-cd2205757340)  
(2817183)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e244c3f1-3c4e-4648-b1f9-e216b0009f1e)  
(2817183)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=190a78a5-e557-44f3-b214-7d3c904f7bd8)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=20500712-2c0f-41e2-95a8-db1a5dcf717a)  
(2813345)  
(Crítica)  
[Remote Desktop Connection 7.0 Client](http://www.microsoft.com/downloads/details.aspx?familyid=1bf2935a-2fa4-4a26-bccf-fe0b63a16b37)  
(2813347)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7f1aa4bd-a14e-4797-b542-4220e3d9d0d7)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=e1b1a3b4-7aae-4934-96cc-990cd1ce962d)  
(2772930)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=10664eeb-f759-4a0e-b1df-c463aae43902)  
(2820917)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3881a7f9-a5f1-4a28-b652-7b7f20c05259)  
(2808735)  
(Importante)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=55d753f3-b912-401c-bca6-61c212ffa0df)  
(2840149)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1bcd238f-2758-49f7-a347-7ec998637d5c)  
(2817183)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c35f53d6-eceb-4966-9487-2dfc2652c775)  
(2817183)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=6cfdb0d5-9c47-405f-bc60-0e4dd3eaff12)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=4c6f006c-fcb8-499f-bd91-9c8acb3ec3c3)  
(2813345)  
(Crítica)  
[Remote Desktop Connection 7.0 Client](http://www.microsoft.com/downloads/details.aspx?familyid=201eb194-e7c9-479c-bb03-646b22f2bbd1)  
(2813347)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d6b3ef0e-16e3-42cb-bffe-4b046f995771)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=ca2182ae-cd47-48d7-9bb0-4aeda4ee26cc)  
(2772930)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c12ce8b7-e8e2-47ac-bdaa-874dff5a6115)  
(2820917)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e5ba88a4-e0ec-45d7-8c0a-611521351890)  
(2808735)  
(Importante)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=89f1556f-442f-4888-b21a-ffbedaa8792e)  
(2840149)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=09bd431a-e94f-4fc5-bea9-569ebc17b0f3)  
(2817183)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=76f96697-0f07-49ad-9169-47cfe2f6a362)  
(2817183)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=2d8c4080-ff7a-42ef-95f4-36b642c0a089)   
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=92bd1819-46f9-4a9b-bf2b-ea6aaaee9890)  
(2813345)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=527ea8cd-88db-448a-b8e4-0fdf87fa369c)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=dd955bf1-e51f-4738-82bf-759e9dea0895)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=31561241-07c8-4396-ad80-9c62a2394658)  
(2820917)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e598863e-7ca1-42a6-9cb4-3f3a10f0ce71)  
(2808735)  
(Importante)  
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a4bdfe68-4de2-41fa-a593-2e07de105081)  
(2840149)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e46e002e-40b2-4bb3-89ad-63d320273ffa)  
(2817183)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b93153dc-f83a-4891-8230-765e3472614d)  
(2817183)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=08abb2ce-0a07-4f25-b9ad-5ec87c07f0bf)   
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=6518cdc6-10a6-46ed-a2f6-6f58216fe319)  
(2813345)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=604709f7-8712-4162-ab86-5988b19084f9)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=38d1cd8c-977b-47be-b703-a326a1b4f445)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=46ef3ace-30b2-4099-aa9d-142de82b0257)  
(2820917)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a9dd92b5-4137-47d1-85a3-506f1eaacee0)  
(2808735)  
(Importante)  
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1c36a50c-023d-420d-830a-d4cb2eda6ef2)  
(2840149)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b0d20b3f-f6cb-4cbc-9af1-1d33b4a6dfb2)  
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=4807c3fe-bc54-4db6-a9b0-ee21bdd9820f)  
(2813345)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6133c84a-b2ce-4a2e-8afc-7386caf80cc8)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=94971d7b-df42-4566-97eb-0a7572b0e2da)  
(2820917)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3e9ccb95-284a-478e-b521-f3a0acbae8da)  
(2808735)  
(Importante)  
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=738b2263-e1eb-4ada-a7f0-5165f42bc5c9)  
(2840149)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 7 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ec9c221a-065b-4f5c-95b6-9b650c24cffa)  
(2817183)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=041fd330-0998-44b5-bedd-d3e47965370d)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.0 Client](http://www.microsoft.com/downloads/details.aspx?familyid=d7623f17-783d-431a-8274-17d71df72202)  
(2813347)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=90d2c454-c31c-4ac4-ab94-b341d1244ee6)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=37b3e861-35fb-471b-b81a-a8b58bd26647)  
(2772930)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=1abeaf49-c458-4046-a001-8aee0ba35b3a)  
(2808735)  
(Importante)  
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=808ac8c6-394d-406b-b34e-07d03c760c27)  
(2840149)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ec9c221a-065b-4f5c-95b6-9b650c24cffa)  
(2817183)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=041fd330-0998-44b5-bedd-d3e47965370d)   
(2817183)  
(Crítica)  
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=cf49622e-8494-4082-a9aa-a6699711d827)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=d7623f17-783d-431a-8274-17d71df72202)  
(2813347)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=90d2c454-c31c-4ac4-ab94-b341d1244ee6)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=37b3e861-35fb-471b-b81a-a8b58bd26647)  
(2772930)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1abeaf49-c458-4046-a001-8aee0ba35b3a)  
(2808735)  
(Importante)  
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=808ac8c6-394d-406b-b34e-07d03c760c27)  
(2840149)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=01f4b588-38e3-43a7-ae5c-674b9c03fc42)  
(2817183)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ac93c656-2c9c-4378-9ae3-a60636b8ce6f)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.0 Client](http://www.microsoft.com/downloads/details.aspx?familyid=5595efaa-3d57-4c9a-8b53-7cfa06093f1e)  
(2813347)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=ebc1ea79-158f-4c81-ab49-3d3fca870363)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=94d19c2a-2457-4fa7-ade6-ad37d0e7f56a)  
(2772930)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=84275cfd-f5a3-4830-895d-beaf162cdc27)  
(2808735)  
(Importante)  
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=737a0cd0-eee6-4095-b9b1-2822024dd825)  
(2840149)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=01f4b588-38e3-43a7-ae5c-674b9c03fc42)  
(2817183)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ac93c656-2c9c-4378-9ae3-a60636b8ce6f)   
(2817183)  
(Crítica)  
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=775536fa-a8a2-4733-a0f0-08e742be1122)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=5595efaa-3d57-4c9a-8b53-7cfa06093f1e)  
(2813347)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=ebc1ea79-158f-4c81-ab49-3d3fca870363)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=94d19c2a-2457-4fa7-ade6-ad37d0e7f56a)  
(2772930)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=84275cfd-f5a3-4830-895d-beaf162cdc27)  
(2808735)  
(Importante)  
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=737a0cd0-eee6-4095-b9b1-2822024dd825)  
(2840149)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d8ffa592-6336-494d-bcd0-535ea2821525)  
(2817183)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7f68500e-6699-4341-b129-2dbd5bc508ac)   
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.0 Client](http://www.microsoft.com/downloads/details.aspx?familyid=79c870b9-b800-4f59-a5ea-19a5c890af52)  
(2813347)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d)  
(2808735)  
(Importante)  
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018)  
(2840149)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d8ffa592-6336-494d-bcd0-535ea2821525)  
(2817183)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7f68500e-6699-4341-b129-2dbd5bc508ac)   
(2817183)  
(Moderada)  
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=752ffe45-b251-4cdf-9848-4d15f75d4452)   
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=79c870b9-b800-4f59-a5ea-19a5c890af52)  
(2813347)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d)  
(2808735)  
(Importante)  
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018)  
(2840149)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2dec754b-4d51-4792-bee6-67e94a1a8157)  
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.0 Client](http://www.microsoft.com/downloads/details.aspx?familyid=c7047403-8c2a-42de-bea5-d7354847730a)  
(2813347)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5cfc2f18-4cde-4e21-8604-f694d69da535)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=6c577423-cd17-4317-98a3-5f6e767513c0)  
(2808735)  
(Importante)  
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=3f1abf13-14c3-4a92-b4c1-4caa40e29e7b)  
(2840149)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2dec754b-4d51-4792-bee6-67e94a1a8157)  
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.1 Client](http://www.microsoft.com/downloads/details.aspx?familyid=c7047403-8c2a-42de-bea5-d7354847730a)  
(2813347)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5cfc2f18-4cde-4e21-8604-f694d69da535)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=6c577423-cd17-4317-98a3-5f6e767513c0)  
(2808735)  
(Importante)  
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=3f1abf13-14c3-4a92-b4c1-4caa40e29e7b)  
(2840149)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="7">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 8 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=159c43ec-beaf-4ac3-8c3a-06a9716ac9ae)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=02d6d10e-3708-4424-8618-88414694c973)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=c7a7ba4d-1fe1-40ed-81f2-6fbb6dde2cf6)  
(2772930)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=882f2d67-b8e0-4859-871b-6a7cef27e3e5)  
(2808735)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=3309f621-4087-4688-b991-c2ef54532cb6)   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=18992e76-70f3-43a2-b47f-199c9728c7ca)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=bafaac33-2bef-4a5e-9451-23ca69c0a132)  
(2772930)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=852dac0f-75fe-443f-9b3d-1dbcac166b3d)  
(2808735)  
(Importante)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
**Nenhuma**
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
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=5015e763-6fb8-4737-9305-2e5850ef853d)   
(2817183)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=ef106525-c42b-4b25-83bf-e290e2bcad5a)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services](http://www.microsoft.com/downloads/details.aspx?familyid=209e3d5f-9333-469e-8b2c-212dc4ec764a)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=fbf53f06-1ee2-49c4-a5a8-3b1e9823b1b9)  
(2808735)  
(Importante)
</td>
</tr>
<tr>
<th colspan="7">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>   
(2817183)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(2808735)  
(Importante)
</td>
</tr>
<tr>
<th colspan="7">
Opção de instalação de núcleo de servidor
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=527ea8cd-88db-448a-b8e4-0fdf87fa369c) (instalação do núcleo do servidor)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=dd955bf1-e51f-4738-82bf-759e9dea0895)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=31561241-07c8-4396-ad80-9c62a2394658) (instalação do núcleo do servidor)  
(2820917)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e598863e-7ca1-42a6-9cb4-3f3a10f0ce71) (instalação do núcleo do servidor)  
(2808735)  
(Importante)  
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a4bdfe68-4de2-41fa-a593-2e07de105081) (instalação do núcleo do servidor)  
(2840149)  
(Moderada)
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
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=604709f7-8712-4162-ab86-5988b19084f9) (instalação do núcleo do servidor)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=38d1cd8c-977b-47be-b703-a326a1b4f445)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=46ef3ace-30b2-4099-aa9d-142de82b0257) (instalação do núcleo do servidor)  
(2820917)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a9dd92b5-4137-47d1-85a3-506f1eaacee0) (instalação do núcleo do servidor)  
(2808735)  
(Importante)  
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1c36a50c-023d-420d-830a-d4cb2eda6ef2) (instalação do núcleo do servidor)  
(2840149)  
(Moderada)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45) (instalação do núcleo do servidor)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d) (instalação do núcleo do servidor)  
(2808735)  
(Importante)  
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018) (instalação do núcleo do servidor)  
(2840149)  
(Moderada)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45) (instalação do núcleo do servidor)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d) (instalação do núcleo do servidor)  
(2808735)  
(Importante)  
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018) (instalação do núcleo do servidor)  
(2840149)  
(Moderada)
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
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=ef106525-c42b-4b25-83bf-e290e2bcad5a) (instalação Server Core)  
(2813170)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Services](http://www.microsoft.com/downloads/details.aspx?familyid=209e3d5f-9333-469e-8b2c-212dc4ec764a)  
(2772930)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=fbf53f06-1ee2-49c4-a5a8-3b1e9823b1b9) (instalação Server Core)  
(2808735)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS13-028, MS13-031 e MS13-036**

<sup>[1]</sup>As atualizações de segurança do Windows RT são fornecidas pelo [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Softwares do Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=63f6a338-a195-4923-908e-8c21713c7373)  
(2687422)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>
[Microsoft InfoPath 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=f1cd73d2-411b-4a58-b8c0-04fd58922dae)  
(2760406)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1 (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=ae2069d0-55b5-4dfe-9131-41888d6bbec3)  
(2687422)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>
[Microsoft InfoPath 2010 Service Pack 1 (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=f206071a-4502-432a-9e5b-50bb4e3f1757)  
(2760406)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>
</td>
</tr>
</table>

<p></p>

 
**Observações para MS13-035**

<sup>[1]</sup>As classificações de gravidade não se aplicam a esta atualização para o software especificado uma vez que os vetores de ataque conhecidos para essa vulnerabilidade estão bloqueados.

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-030**](http://go.microsoft.com/fwlink/?linkid=286577)
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1 (wosrv)](http://www.microsoft.com/downloads/details.aspx?familyid=6c7d007f-5c8d-464c-af04-4e7800a2e2a6)<sup>[1]</sup>
(2687421)  
(Importante)  
[Microsoft SharePoint Server 2010 Service Pack 1 (coreserver)](http://www.microsoft.com/downloads/details.aspx?familyid=c59c0d25-8d6c-4dda-a06b-e42891a9ddae)<sup>[1]</sup>
(2760408)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2013 (coreserverloc)](http://www.microsoft.com/downloads/details.aspx?familyid=2e5b1e49-0355-4111-a464-224bb2192029)<sup>[1]</sup>
(2737969)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-030**](http://go.microsoft.com/fwlink/?linkid=286577)
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d63ee461-b823-4eb1-9e6d-82f380627fb5)  
(2687424)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-030**](http://go.microsoft.com/fwlink/?linkid=286577)
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac805c46-8661-4e99-84da-c395dc05beb0)  
(2810059)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS13-030**

<sup>[1]</sup>Esta atualização exige a instalação da atualização cumulativa do Project Server 2013 (2768001). Para obter mais informações sobre esta atualização, incluindo links para download, consulte o [Artigo da Microsoft Knowledge Base 2768001](http://support.microsoft.com/kb/2768001).

**Observações para MS13-035**

<sup>[1]</sup>Para edições com suporte do Microsoft SharePoint Server 2010, além dos pacote de atualização de segurança para o Microsoft SharePoint 2010 (2687421 e 2760408), os clientes também precisam instalar a atualização de segurança do Microsoft SharePoint Foundation 2010 (2810059) para ficarem protegidos contra as vulnerabilidades descritas neste boletim.

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Microsoft Office Web Apps

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Softwares do Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
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
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1d35b235-305a-45c8-a395-7658792d177e)  
(2760777)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS13-035**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Software de segurança da Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Software antimalware
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-034**](http://go.microsoft.com/fwlink/?linkid=276805)
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
Windows Defender para Windows 8 e Windows RT
</td>
<td style="border:1px solid black;">
Windows Defender para Windows 8 e Windows RT<sup>[1]</sup>   
(2781197)   
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS13-034**

<sup>[1]</sup>Esta atualização está disponível no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Microsoft Safety & Security Center](http://go.microsoft.com/fwlink/?linkid=85102), onde essas informações também estão disponíveis, clicando em “Atualizações de segurança”.

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

**MS13-028**

-   Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google](http://www.google.com/), por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1303)
-   Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google](http://www.google.com/), por reportar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1304)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de uso após liberação do Internet Explorer (CVE-2013-1338)
-   Um pesquisador anônimo, por trabalhar conosco em alterações de defesa abrangentes incluídas neste boletim

**MS13-029**

-   c1d2d9acc746ae45eeb477b97fa74688, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por reportar a Vulnerabilidade de execução de código remoto do controle Active X no RDP (CVE-2013-1296)

**MS13-031**

-   [Gynvael Coldwind](http://gynvael.coldwind.pl/)
-   e
-   [Mateusz “j00ru" Jurczyk,](http://j00ru.vexillium.org/)
-   da
-   [Google Inc,](http://www.google.com/)
-   por reportarem a Vulnerabilidade de condição forçada do kernel (CVE-2013-1284)
-   [Gynvael Coldwind](http://gynvael.coldwind.pl/)
-   e
-   [Mateusz “j00ru" Jurczyk,](http://j00ru.vexillium.org/)
-   da
-   [Google Inc,](http://www.google.com/)
-   por reportarem a Vulnerabilidade de condição forçada do kernel (CVE-2013-1294)

**MS13-033**

-   George Georgiev, por reportar a Vulnerabilidade de corrupção de memória do CSRSS (CVE-2013-1295)

**MS13-034**

-   Bruce Monroe, da [Intel](http://www.intel.com/), por reportar a Vulnerabilidade de nome de caminho impróprio de antimalware da Microsoft (CVE-2013-0078)
-   Shai Sarfaty, por reportar a Vulnerabilidade de nome de caminho impróprio de antimalware da Microsoft (CVE-2013-0078)
-   Tony Robotham, da Centrica, por reportar a Vulnerabilidade de nome de caminho impróprio de antimalware da Microsoft (CVE-2013-0078)

**MS13-035**

-   Drew Hintz, da [Equipe de segurança do Google](http://www.google.com/), por reportar a Vulnerabilidade de limpeza de HTML (CVE-2013-1289)

**MS13-036**

-   [Gynvael Coldwind](http://gynvael.coldwind.pl/)
-   e
-   [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   , da
-   [Google Inc](http://www.google.com/)
-   , por reportarem a Vulnerabilidade de condição forçada Win32k (CVE-2013-1283)
-   Wang Yu do [Qihoo 360 Security Center](http://www.360.cn/) por reportar a Vulnerabilidade de Análise de Fonte Win32k (CVE-2013-1291)
-   [Gynvael Coldwind](http://gynvael.coldwind.pl/)
-   e
-   [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   , da
-   [Google Inc](http://www.google.com/)
-   , por reportarem a Vulnerabilidade de condição forçada Win32k (CVE-2013-1292)
-   [Gynvael Coldwind](http://gynvael.coldwind.pl/)
-   e
-   [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   , da
-   [Google Inc](http://www.google.com/)
-   , por trabalharem conosco na Vulnerabilidade de desorientação do ponteiro NULL do NTFS (CVE-2013-1293)

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (9 de abril de 2013): Resumo de boletins publicado.
-   V1.1 (10 de abril de 2013): MS13-029 corrigiu o número de versão para Remote Desktop Connection Client no Windows 7 Service Pack 1 e no Windows Server 2008 R2 Service Pack 1 versões 7.0 e 7.1. Esta é somente uma alteração instrutiva. Não houve nenhuma alteração em arquivos de atualização de segurança.
-   V2.0 (11 de abril de 2013): No MS13-036, removidos os links para a atualização de segurança 2823324 devido a um problema conhecido de instalação. Consulte o boletim para obter detalhes.
-   V3.0 (23 de abril de 2013): No MS13-036, substituída a atualização 2823324 pela atualização 2840149 do NTFS.sys quando instalado em edições suportadas do Windows Vista, Windows Server 2008, Windows 7 e Windows Server 2008 R2. Consulte o boletim para obter os detalhes.
-   V3.1 (24 de abril de 2013): No MS13-028, adicionada uma avaliação do risco de exploração no **Índice de exploração** do CVE-2013-1338. Essa alteração é apenas informativa.
-   V4.0 (25 de junho de 2013): Para o MS13-029, revisado o boletim a fim de relançar a atualização 2813347 para o Remote Desktop Connection 7.0 Client no Windows XP Service Pack 3. Consulte o boletim para obter os detalhes.

*Built at 2014-04-18T01:50:00Z-07:00*
