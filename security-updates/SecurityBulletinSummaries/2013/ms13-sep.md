---
TOCTitle: 'MS13-SEP'
Title: Resumo de boletins de segurança da Microsoft de setembro de 2013
ms:assetid: 'ms13-sep'
ms:contentKeyID: 61233706
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms13-sep(v=Security.10)'
---

 

Resumo de boletins de segurança da Microsoft de setembro de 2013
================================================================

Publicado: terça-feira, 10 de setembro de 2013 | Atualizado: quarta-feira, 6 de novembro de 2013

**Versão:** 1.1

Este resumo de boletins lista os boletins de segurança lançados em setembro de 2013.

Com o lançamento dos boletins de segurança de setembro de 2013, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 5 de setembro de 2013. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 11 de setembro de 2013, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de setembro](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557378&culture=en-us). Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557378&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft SharePoint Server podem permitir a execução remota de código (2834052)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade divulgada publicamente e nove vulnerabilidades reportadas em particular no software do Microsoft Office Server. A vulnerabilidade mais severa pode permitir execução remota de código no contexto da conta de serviço W3WP se o invasor enviar conteúdo especialmente criado ao servidor afetado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=307055">MS13-068</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Outlook pode permitir a execução remota de código (2756473)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Outlook. A vulnerabilidade pode permitir a execução remota de código se o usuário abrir ou visualizar uma mensagem de email especialmente criada usando uma edição afetada do Microsoft Outlook. O invasor que explorar com êxito a vulnerabilidade poderá obter os mesmos direitos que o usuário local. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (2870699)</strong><br />
<br />
Esta atualização de segurança resolve dez vulnerabilidades relatadas em particular no Internet Explorer. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que conseguir explorar a mais severa das vulnerabilidades poderá obter os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320629">MS13-070</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no OLE pode permitir a execução remota de código (2876217)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário abrir um arquivo que contenha um objeto OLE especialmente criado. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314046">MS13-071</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no arquivo de tema do Windows pode permitir execução remota de código (2864063)<br />
</strong><br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário aplicar um tema especialmente criado para o Windows em seu sistema. Em todos os casos, um usuário não pode ser forçado a abrir o arquivo ou aplicar o tema; para um ataque ser bem-sucedido, um usuário deve ser convencido a fazê-lo.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Office podem permitir a execução remota de código (2845537)<br />
</strong><br />
Esta atualização de segurança aborda 13 vulnerabilidades relatadas em particular no<strong></strong>Microsoft Office. As vulnerabilidades mais severas podem permitir a execução remota de código se um arquivo especialmente criado for aberto em uma versão afetada do software Microsoft Office. Um invasor que conseguir explorar as vulnerabilidades mais severas poderá obter os mesmos direitos de usuário que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Excel podem permitir a execução remota de código (2858300)</strong><br />
<br />
Esta atualização de segurança resolve três vulnerabilidades relatadas em particular no Microsoft Office. As vulnerabilidades mais severas podem permitir a execução remota de código se um usuário abrir um arquivo do Office especialmente criado com uma versão afetada do Microsoft Excel ou outro software afetado do Microsoft Office. Um invasor que conseguir explorar as vulnerabilidades mais severas poderá obter os mesmos direitos de usuário que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308989">MS13-074</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Access podem permitir a execução remota de código (2848637)</strong><br />
<br />
Esta atualização de segurança resolve três vulnerabilidades relatadas em particular no Microsoft Office. As vulnerabilidades poderão permitir a execução remota de código se o usuário abrir um arquivo do Access especialmente criado com uma versão afetada do Microsoft Access. O invasor que explorar com êxito as vulnerabilidades poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318022">MS13-075</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Office IME (chinês) pode permitir a elevação de privilégio (2878687)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office Project IME (chinês). A vulnerabilidade pode permitir elevação de privilégio se um invasor conectado iniciar o Internet Explorer a partir da barra de ferramentas no Microsoft Pinyin IME para chinês simplificado. Um invasor que explorar com êxito essa vulnerabilidade poderá executar código arbitrário no modo do kernel. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de administração. Somente implementações do Microsoft Pinyin IME 2010 são afetadas por esta vulnerabilidade. Outras versões de IME do chinês simplificado e outras implementações de IME não são afetadas.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades nos drivers do</strong> <strong>modo kernel podem permitir a elevação de privilégio (2876315)</strong><br />
<br />
Esta atualização de segurança resolve duas vulnerabilidades relatadas em particular no Microsoft Windows. As vulnerabilidades podem permitir elevação de privilégio se um invasor faz logon no sistema e executa um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essas vulnerabilidades.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320630">MS13-077</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Gerenciador de Controle de Serviços do Windows pode permitir a elevação de privilégio (2872339)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a elevação de privilégio se o invasor convencer o usuário autenticado a executar um aplicativo especialmente criado. Para explorar esta vulnerabilidade, o invasor deve ter credenciais válidas de logon e poder fazer logon localmente, ou deve convencer um usuário a executar o aplicativo especialmente criado pelo invasor.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318021">MS13-078</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no FrontPage pode permitir divulgação não autorizada de informações (2825621)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft FrontPage. A vulnerabilidade pode permitir a divulgação não autorizada de informações se um usuário abrir um documento do FrontPage especialmente criado. A vulnerabilidade não pode ser explorada automaticamente. Para um ataque ser efetivo, um usuário deve ser convencido a abrir o documento especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320666">MS13-079</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Active Directory pode permitir a negação de serviço (2853587)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Active Directory. A vulnerabilidade pode permitir a negação de serviço se um invasor enviar uma consulta especialmente criada ao serviço Lightweight Directory Access Protocol (LDAP).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Negação de Serviço</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço do SharePoint</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0081">CVE-2013-0081</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1315">CVE-2013-1315</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desativação do MAC</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1330">CVE-2013-1330</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de XSS no SharePoint</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3179">CVE-2013-3179</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de XSS POST</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3180">CVE-2013-3180</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade foi divulgada publicamente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3847">CVE-2013-3847</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3848">CVE-2013-3848</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3849">CVE-2013-3849</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3857">CVE-2013-3857</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3858">CVE-2013-3858</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=307055">MS13-068</a></td>
<td style="border:1px solid black;">Vulnerabilidade de certificado de mensagem</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3870">CVE-2013-3870</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3201">CVE-2013-3201</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3202">CVE-2013-3202</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3203">CVE-2013-3203</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3204">CVE-2013-3204</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3205">CVE-2013-3205</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3206">CVE-2013-3206</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3207">CVE-2013-3207</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3208">CVE-2013-3208</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3209">CVE-2013-3209</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3845">CVE-2013-3845</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">O Internet Explorer 11 não é afetado.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320629">MS13-070</a></td>
<td style="border:1px solid black;">Vulnerabilidade de propriedade do OLE</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3863">CVE-2013-3863</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314046">MS13-071</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código em arquivo do Windows Theme</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0810">CVE-2013-0810</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de resolução de entidades externas de XML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3160">CVE-2013-3160</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação não autorizada de informações.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3847">CVE-2013-3847</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3848">CVE-2013-3848</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3849">CVE-2013-3849</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3850">CVE-2013-3850</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3851">CVE-2013-3851</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3852">CVE-2013-3852</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3853">CVE-2013-3853</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3854">CVE-2013-3854</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3855">CVE-2013-3855</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3856">CVE-2013-3856</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3857">CVE-2013-3857</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3858">CVE-2013-3858</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1315">CVE-2013-1315</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3158">CVE-2013-3158</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a></td>
<td style="border:1px solid black;">Vulnerabilidade de resolução de entidades externas de XML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3159">CVE-2013-3159</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação não autorizada de informações.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308989">MS13-074</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Access</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3155">CVE-2013-3155</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308989">MS13-074</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória de formato de arquivo do Access</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3156">CVE-2013-3156</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308989">MS13-074</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Access</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3157">CVE-2013-3157</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318022">MS13-075</a></td>
<td style="border:1px solid black;">Vulnerabilidade de IME chinês</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3859">CVE-2013-3859</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Vulnerabilidade de fetch múltiplo Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1341">CVE-2013-1341</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Vulnerabilidade de fetch múltiplo Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1342">CVE-2013-1342</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Vulnerabilidade de fetch múltiplo Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1343">CVE-2013-1343</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Vulnerabilidade de fetch múltiplo Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1344">CVE-2013-1344</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Vulnerabilidade de fetch múltiplo Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3864">CVE-2013-3864</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Vulnerabilidade de fetch múltiplo Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3865">CVE-2013-3865</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3866">CVE-2013-3866</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de negação de serviço no Windows 8 e Windows Server 2012.<br />
<br />
Windows 8.1 e Windows Server 2012 R2 não são afetados.<br />
<br />
Esta é uma vulnerabilidade de divulgação não autorizada de informações que pode levar a uma elevação de privilégio em outros softwares afetados.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320630">MS13-077</a></td>
<td style="border:1px solid black;">Vulnerabilidade de liberação dupla do Service Control Manager</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3862">CVE-2013-3862</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318021">MS13-078</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de XML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3137">CVE-2013-3137</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação não autorizada de informações.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320666">MS13-079</a></td>
<td style="border:1px solid black;">Vulnerabilidade DoS remoto anônimo</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3868">CVE-2013-3868</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).<br />
<br />
Windows 8.1 e Windows Server 2012 R2 não são afetados.</td>
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
<th colspan="7">
Windows XP (site em inglês)
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2870699)  
(Crítica)  
Internet Explorer 7  
(2870699)  
(Crítica)  
Internet Explorer 8  
(2870699)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2876217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2864063)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2876315)  
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
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2870699)  
(Crítica)  
Internet Explorer 7  
(2870699)  
(Crítica)  
Internet Explorer 8  
(2870699)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2876217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2864063)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2876315)  
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
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2870699)  
(Moderada)  
Internet Explorer 7  
(2870699)  
(Moderada)  
Internet Explorer 8  
(2870699)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2876217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2864063)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2876315)  
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
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2870699)  
(Moderada)  
Internet Explorer 7  
(2870699)  
(Moderada)  
Internet Explorer 8  
(2870699)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2876217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2864063)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2876315)  
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
(2870699)  
(Moderada)  
Internet Explorer 7  
(2870699)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2876217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2864063)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2876315)  
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
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
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
**Nenhuma**
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2870699)  
(Crítica)  
Internet Explorer 8  
(2870699)  
(Crítica)  
Internet Explorer 9  
(2870699)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2864063)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2870699)  
(Crítica)  
Internet Explorer 8  
(2870699)  
(Crítica)  
Internet Explorer 9  
(2870699)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2864063)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
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
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
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
**Nenhuma**
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2870699)  
(Moderada)  
Internet Explorer 8  
(2870699)  
(Moderada)  
Internet Explorer 9  
(2870699)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2864063)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Services  
(2853587)  
(Importante)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2870699)  
(Moderada)  
Internet Explorer 8  
(2870699)  
(Moderada)  
Internet Explorer 9  
(2870699)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2864063)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Services  
(2853587)  
(Importante)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2870699)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2864063)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2876315)  
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
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
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
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2870699)  
(Crítica)  
Internet Explorer 9  
(2870699)  
(Crítica)  
Internet Explorer 10  
(2870699)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2872339)  
(Importante)
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2870699)  
(Crítica)  
Internet Explorer 9  
(2870699)  
(Crítica)  
Internet Explorer 10  
(2870699)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2872339)  
(Importante)
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
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
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
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
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2870699)  
(Moderada)  
Internet Explorer 9  
(2870699)  
(Moderada)  
Internet Explorer 10  
(2870699)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2872339)  
(Importante)
</td>
<td style="border:1px solid black;">
Active Directory Services  
(2853587)  
(Importante)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2870699)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2872339)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
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
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
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
**Nenhuma**
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2870699)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2870699)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
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
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
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
**Nenhuma**
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2870699)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Services  
(2853587)  
(Importante)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
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
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
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
**Nenhuma**
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2870699)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows RT  
(2876315)  
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
<th colspan="7">
Opção de instalação do Server Core
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-069**](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[**MS13-070**](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[**MS13-071**](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[**MS13-076**](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[**MS13-077**](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[**MS13-079**](http://go.microsoft.com/fwlink/?linkid=320666)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade** **agregada**
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
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do Server Core)
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
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do Server Core)  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Services  
(2853587)  
(Importante)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do Server Core)
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
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do Server Core)  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Services  
(2853587)  
(Importante)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)
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
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)  
(2872339)
</td>
<td style="border:1px solid black;">
Active Directory Services  
(2853587)  
(Importante)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2876315)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Active Directory Services  
(2853587)  
(Importante)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="6">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-068**](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[**MS13-072**](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[**MS13-073**](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[**MS13-074**](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[**MS13-075**](http://go.microsoft.com/fwlink/?linkid=318022)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
(MSO)  
(2817474)  
(Importante)  
Microsoft Word 2003 Service Pack 3  
(2817682)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2003 Service Pack 3  
(2810048)  
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
<th colspan="6">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-068**](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[**MS13-072**](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[**MS13-073**](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[**MS13-074**](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[**MS13-075**](http://go.microsoft.com/fwlink/?linkid=318022)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2007 Service Pack 3  
(2825999)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(MSO)  
(2760411)  
(Importante)  
Microsoft Office 2007 Service Pack 3  
(MSPTLS)  
(2597973)  
(Importante)  
Microsoft Word 2007 Service Pack 3  
(2767773)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2760583)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Access 2007 Service Pack 3  
(2596825)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-068**](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[**MS13-072**](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[**MS13-073**](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[**MS13-074**](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[**MS13-075**](http://go.microsoft.com/fwlink/?linkid=318022)
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
Microsoft Office 2010 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 1 (edições de 32 bits)  
(2794707)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 1 (edições de 32 bits)  
(2760769)  
(Importante)  
Microsoft Word 2010 Service Pack 1 (edições de 32 bits)  
(2767913)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (edições de 32 bits)  
(2760597)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Access 2010 Service Pack 1 (edições de 32 bits)  
(2687423)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Pinyin IME 2010 (versão de 32 bits)  
(2687413)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 2 (edições de 32 bits)  
(2794707)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 2 (edições de 32 bits)  
(2760769)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 32 bits)  
(2767913)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (edições de 32 bits)  
(2760597)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Access 2010 Service Pack 2 (edições de 32 bits)  
(2687423)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 1 (edições de 64 bits)  
(2794707)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 1 (edições de 64 bits)  
(2760769)  
(Importante)  
Microsoft Word 2010 Service Pack 1 (edições de 64 bits)  
(2767913)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (edições de 64 bits)  
(2760597)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Access 2010 Service Pack 1 (edições de 64 bits)  
(2687423)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Pinyin IME 2010 (versão de 64 bits)  
(2687413)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 2 (edições de 64 bits)  
(2794707)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 2 (edições de 64 bits)  
(2760769)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 64 bits)  
(2767913)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (edições de 64 bits)  
(2760597)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Access 2010 Service Pack 2 (edições de 64 bits)  
(2687423)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-068**](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[**MS13-072**](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[**MS13-073**](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[**MS13-074**](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[**MS13-075**](http://go.microsoft.com/fwlink/?linkid=318022)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (edições de 32 bits)  
(2768017)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Access 2013 (edições de 32 bits)  
(2810009)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (edições de 64 bits)  
(2768017)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Access 2013 (edições de 64 bits)  
(2810009)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2768017)  
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
<th colspan="6">
Microsoft Office para Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-068**](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[**MS13-072**](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[**MS13-073**](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[**MS13-074**](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[**MS13-075**](http://go.microsoft.com/fwlink/?linkid=318022)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2877813)  
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
<th colspan="6">
Outros softwares do Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-068**](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[**MS13-072**](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[**MS13-073**](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[**MS13-074**](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[**MS13-075**](http://go.microsoft.com/fwlink/?linkid=318022)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Pacote de compatibilidade do Microsoft Office Service Pack 3
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(2760823)  
(Importante)
</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(2760588)  
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
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2817683)  
(Importante)
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
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2760590)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 

#### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Portal Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-067**](http://go.microsoft.com/fwlink/?linkid=293350)
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
Microsoft SharePoint Portal Server 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 2.0  
(2810061)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-067**](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (versões de 32 bits)  
(2760420)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (versões de 64 bits)  
(2760420)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-067**](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1 (wss)  
(2810067)  
(Crítica)  
Microsoft SharePoint Server 2010 Service Pack 1 (coreserver)  
(2817393)  
(Crítica)  
Microsoft SharePoint Server 2010 Service Pack 1 (wosrv)  
(2817372)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wss)  
(2810067)  
(Crítica)  
Microsoft SharePoint Server 2010 Service Pack 2 (coreserver)  
(2817393)  
(Crítica)  
Microsoft SharePoint Server 2010 Service Pack 2 (wosrv)  
(2817372)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-067**](http://go.microsoft.com/fwlink/?linkid=293350)
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
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013  
(2817315)  
(Importante)  
Microsoft SharePoint Server 2013 (coreserverloc)  
(2810083)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para o MS13-067**

Consulte também outras categorias de software nesta seção, **Softwares afetados**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software

#### Microsoft Office Services e Web Apps

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-067**](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Excel Services  
(2760589)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Excel Services  
(2760589)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-067**](http://go.microsoft.com/fwlink/?linkid=293350)
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
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Excel Services  
(2760595)  
(Crítica)  
Microsoft Business Productivity Servers  
(2553408)  
(Crítica)  
Serviços de automação do Word  
(2760755)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(2760595)  
(Crítica)  
Microsoft Business Productivity Servers  
(2553408)  
(Crítica)  
Serviços de automação do Word  
(2760755)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-067**](http://go.microsoft.com/fwlink/?linkid=293350)
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
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Excel Web App 2010 Service Pack 1  
(2760594)  
(Crítica)  
Microsoft Word Web App 2010 Service Pack 1  
(2817384)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Excel Web App 2010 Service Pack 2  
(2760594)  
(Crítica)  
Microsoft Word Web App 2010 Service Pack 2  
(2817384)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-067**](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2817305)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para o MS13-067**

Consulte também outras categorias de software nesta seção, **Softwares afetados**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software

#### Software de Produtividade

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft FrontPage 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-078**](http://go.microsoft.com/fwlink/?linkid=318021)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft FrontPage 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft FrontPage 2003 Service Pack 3  
(2825621)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

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

**SystemCenter Configuration Manager**

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

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

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

**MS13-067**

-   Will Dormann, do [CERT/CC,](http://www.cert.org/) por relatar a Vulnerabilidade de corrupção da memória do Microsoft Office (CVE-2013-1315)
-   Alexandre Herzog da [Compass Segurança AG](http://www.csnc.ch/) por relatar a Vulnerabilidade de desativação não autorizada de MAC (CVE-2013-1330)
-   Benjamin Kunz Mejri, do Vulnerability Research Laboratory, por reportar a Vulnerabilidade de XSS no SharePoint (CVE-2013-3179)
-   Mateusz Jurczyk, Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google](http://www.google.com/), por reportar as Vulnerabilidades diversas de corrupção de memória no Word (CVE-2013-3847, CVE-2013-3848, CVE-2013-3849, CVE-2013-3857, CVE-2013-3858)

**MS13-068**

-   Alexander Klink, da [n.runs AG](https://www.nruns.com/), por reportar a Vulnerabilidade de certificado de mensagem (CVE-2013-3870)

**MS13-069**

-   Jose Antonio Vazquez Gonzalez, trabalhando em conjunto com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3201)
-   Jose Antonio Vazquez Gonzalez, trabalhando em conjunto com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3202)
-   Arthur Gerkis, trabalhando em conjunto com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)[da HP](http://www.zerodayinitiative.com/), por reportar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3203)
-   Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google](http://www.google.com/), por reportarem a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3204)
-   Peter 'corelanc0d3r' Van Eeckhoutte da [Corelan](http://www.corelangcv.com/), trabalhando em conjunto com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3205)
-   Bo Qu da [Palo Alto Networks](http://www.paloaltonetworks.com/) por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3205)
-   Arthur Gerkis, trabalhando em conjunto com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)[da HP](http://www.zerodayinitiative.com/), por reportar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3206)
-   Arthur Gerkis, trabalhando em conjunto com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)[da HP](http://www.zerodayinitiative.com/), por reportar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3207)
-   Arthur Gerkis, trabalhando em conjunto com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)[da HP](http://www.zerodayinitiative.com/), por reportar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3208)
-   Um pesquisador anônimo, trabalhando em conjunto com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3209)
-   Jose Antonio Vazquez Gonzalez, trabalhando em conjunto com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3845)

**MS13-070**

-   G. Geshev, que trabalha na [Zero Day Initiative](http://www.hpenterprisesecurity.com/products) da [HP](http://www.zerodayinitiative.com/), por relatar a Vulnerabilidade da propriedade OLE (CVE-2013-3863)

**MS13-071**

-   Eduardo Prado que, trabalhando junto à [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar a Vulnerabilidade de execução remota de código do arquivo de tema do Windows (CVE-2013-0810)

**MS13-072**

-   Timur Yunusov, Alexey Osipov e Ilya Karpov, da [Positive Technologies](http://www.ptsecurity.com/), por reportarem a Vulnerabilidade de resolução de entidades externas de XML (CVE-2013-3160)
-   Mateusz Jurczyk, Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google](http://www.google.com/), por reportarem múltiplas Vulnerabilidades de corrupção de memória no Microsoft Word (CVE-2013-3847, CVE-2013-3848, CVE-2013-3849, CVE-2013-3850, CVE-2013-3851, CVE-2013-3852, CVE-2013-3853, CVE-2013-3854, CVE-2013-3855, CVE-2013-3856, CVE-2013-3857, CVE-2013-3858)

**MS13-073**

-   Will Dormann, do [CERT/CC,](http://www.cert.org/) por relatar a Vulnerabilidade de corrupção da memória do Microsoft Office (CVE-2013-1315)
-   Will Dormann, do [CERT/CC,](http://www.cert.org/) por relatar a Vulnerabilidade de corrupção da memória do Microsoft Office (CVE-2013-3158)
-   Timur Yunusov, Alexey Osipov e Ilya Karpov da [Positive Technologies,](http://www.ptsecurity.com/) por relatarem a Vulnerabilidade de resolução de entidades externas do XML (CVE-2013-3159)

**MS13-074**

-   Kaveh Ghaemmaghami, da [Secunia SVCRP](http://secunia.com/), por reportar a Vulnerabilidade de corrupção de memória do Access (CVE-2013-3155)
-   Kaveh Ghaemmaghami, da [Secunia SVCRP](http://secunia.com/), por reportar a Vulnerabilidade de corrupção de memória de formato de arquivo do Access (CVE-2013-3156)
-   Kaveh Ghaemmaghami, da [Secunia SVCRP](http://secunia.com/), por reportar a Vulnerabilidade de corrupção de memória do Access (CVE-2013-3157)

**MS13-075**

-   Wei Wang, da [VulnHunt](http://www.vulnhunt.com/), por reportar a Vulnerabilidade do IME em chinês (CVE-2013-3859)

**MS13-076**

-   [Gynvael Coldwind](http://gynvael.coldwind.pl/) e [Mateusz "j00ru" Jurczyk,](http://j00ru.vexillium.org/) da [Google Inc,](http://www.google.com/) por relatarem a Vulnerabilidade de fetch múltiplo do Win32k (CVE-2013-1341)
-   [Gynvael Coldwind](http://gynvael.coldwind.pl/) e [Mateusz "j00ru" Jurczyk,](http://j00ru.vexillium.org/) da [Google Inc,](http://www.google.com/) por relatarem a Vulnerabilidade de fetch múltiplo do Win32k (CVE-2013-1342)
-   [Gynvael Coldwind](http://gynvael.coldwind.pl/) e [Mateusz "j00ru" Jurczyk,](http://j00ru.vexillium.org/) da [Google Inc,](http://www.google.com/) por relatarem a Vulnerabilidade de fetch múltiplo do Win32k (CVE-2013-1343)
-   [Mateusz "j00ru" Jurczyk,](http://j00ru.vexillium.org/) da [Google Inc,](http://www.google.com/) por relatar a Vulnerabilidade de fetch múltiplo do Win32k (CVE-2013-1344)
-   [Gynvael Coldwind](http://gynvael.coldwind.pl/) e [Mateusz "j00ru" Jurczyk,](http://j00ru.vexillium.org/) da [Google Inc,](http://www.google.com/) por relatarem a Vulnerabilidade de fetch múltiplo do Win32k (CVE-2013-3864)
-   [Gynvael Coldwind](http://gynvael.coldwind.pl/) e [Mateusz "j00ru" Jurczyk,](http://j00ru.vexillium.org/) da [Google Inc,](http://www.google.com/) por relatarem a Vulnerabilidade de fetch múltiplo do Win32k (CVE-2013-3865)
-   Guo Pengfei da [Qihoo 360 Security Center](http://www.360.cn/) por relatar a Vulnerabilidade de elevação de privilégio do Win32k (CVE-2013-3866)

**MS13-078**

-   Timur Yunusov da [Positive Technologies](http://www.ptsecurity.com/) por relatar a Vulnerabilidade de divulgação não autorizada de XML (CVE-2013-3137)

#### Suporte

-   O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (10 de setembro de 2013): Resumo de boletins publicado.
-   V1.1 (6 de novembro de 2013): Para MS13-067, corrigimos o nome do produto para a atualização do Microsoft Office Web Apps Server 2013 (2817305).

*Built at 2014-04-18T01:50:00Z-07:00*
