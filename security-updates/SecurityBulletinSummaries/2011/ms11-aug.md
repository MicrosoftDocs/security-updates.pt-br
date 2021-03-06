---
TOCTitle: 'MS11-AUG'
Title: Resumo do Boletim de Segurança da Microsoft de agosto 2011
ms:assetid: 'ms11-aug'
ms:contentKeyID: 61233671
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms11-aug(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de agosto 2011
==========================================================

Publicado: terça-feira, 9 de agosto de 2011 | Atualizado: quarta-feira, 26 de outubro de 2011

**Versão:** 1.2

Este resumo de boletins lista os boletins de segurança lançados em agosto de 2011.

Com o lançamento dos boletins de agosto de 2011, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 4 de agosto de 2011. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte Notificação antecipada dos boletins de segurança da Microsoft.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as Notificações de segurança técnica da Microsoft.

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 10 de agosto de 2011, às 11 horas - Hora do Pacífico (EUA e Canadá). Registre-se agora para participar do Webcast do boletim de segurança de agosto. Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte Webcasts e resumos dos boletins de segurança da Microsoft.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (2559049) </strong> <br />
<br />
Esta atualização de segurança crítica resolve cinco vulnerabilidades no Internet Explorer reportadas em particular e duas divulgadas publicamente. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que explorar com êxito qualquer uma destas vulnerabilidades poderá obter os mesmos direitos que o usuário local. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-058">MS11-058</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no servidor DNS podem permitir a execução remota de código (2562485) </strong> <br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no servidor Windows DNS. A mais severa destas vulnerabilidades pode permitir execução remota de código se um invasor registrar um domínio, criar um registro de recurso do DNS de NAPTR, e então enviar uma consulta de NAPTR especialmente criada para servidor de DNS de destino. Os servidores que não têm a função de DNS habilitada não estão em risco.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-059">MS11-059</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Data Access Components pode permitir a execução remota de código (2560656)</strong>  <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário abrir um arquivo legítimo do Excel (por ex: arquivo .xlsx) localizado no mesmo diretório de rede que um arquivo de biblioteca especialmente criado. O invasor que explorar com êxito a vulnerabilidade poderá obter os mesmos direitos que o usuário conectado. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-060">MS11-060</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Visio podem permitir a execução remota de código (2560978) </strong> <br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft Visio. As vulnerabilidades podem permitir a execução remota de código se o usuário abrir um arquivo do Visio especialmente criado. O invasor que explorar com êxito a vulnerabilidade poderá obter os mesmos direitos que o usuário conectado. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-061">MS11-061</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Acesso via Web da Área de Trabalho Remota pode permitir elevação de privilégio (2546250)</strong>  <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Acesso via Web da Área de Trabalho. A vulnerabilidade é um scripting entre sites (XSS) que pode permitir elevação de privilégio, possibilitando que um invasor executasse comandos arbitrários no site no contexto do usuário de destino. O Filtro de XSS no Internet Explorer 8 e no Internet Explorer 9 evita este ataque para seus usuários ao procurar por um servidor de Acesso via Web da Área de Trabalho na zona da Internet. O Filtro de XSS no Internet Explorer 8 e no Internet Explorer 9 não é habilitado por padrão na zona de Intranet.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-062">MS11-062</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no driver NDISTAPI de serviço de acesso remoto pode permitir elevação de privilégio (2566454)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em todas as edições com suporte do Windows XP e do Windows Server 2003. Esta atualização de segurança foi classificada como Importante para todas as edições com suporte do Windows XP e do Windows Server 2003. O Windows Vista, Windows Server 2008, Windows 7 e Windows Server 2008 R2 não foram afetados por esta vulnerabilidade.<br />
<br />
A vulnerabilidade pode permitir a elevação de privilégios se um invasor se conectar a um sistema afetado e executar um aplicativo especialmente criado para explorar a vulnerabilidade e assumir o controle total do sistema afetado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-063">MS11-063</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no CSRSS (Windows Client/Server Runtime Subsystem) pode permitir elevação de privilégio (2567680)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um invasor fizer logon em um sistema afetado e executar um aplicativo especialmente criado para enviar uma mensagem de evento do dispositivo para um processo de mais integridade. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-064">MS11-064</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades em Pilha de TCP/IP podem permitir negação de serviço(2563894)</strong> <br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft Windows. As vulnerabilidades podem permitir negação de serviço se um invasor enviar uma sequência de mensagens de Internet Control Message Protocol (ICMP) especialmente criada para um sistema de destino ou enviar uma solicitação de URL especialmente criada para um servidor que serve conteúdo de Web e tem o recurso Qualidade de serviço (QoS) com base em URL habilitado.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a><br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-065">MS11-065</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade em Protocolo de Área de Trabalho Remota pode permitir negação de serviço (2570222)</strong>  <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada particularmente no Protocolo de Área de Trabalho Remota. A vulnerabilidade pode permitir negação de serviço se um sistema afetado receber uma sequência de pacotes de RDP especialmente criados. A Microsoft também recebeu relatórios de ataques limitados e direcionados que tentam explorar a vulnerabilidade. Por padrão, o RDP (Remote Desktop Protocol, Protocolo de Área de Trabalho Remota) não é habilitado em nenhum sistema operacional do Windows.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a><br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-066">MS11-066</a></td>
<td style="border:1px solid black;"><strong>A vulnerabilidade no Controle de Gráfico da Microsoft pode permitir divulgação não autorizada de informações (2567943)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular nos Controles de Gráfico do ASP.NET. A vulnerabilidade pode permitir divulgação não autorizada de informações se um invasor enviar uma solicitação GET especialmente criada para um servidor afetado hospedando os Controles de Gráfico. Observe que essa vulnerabilidade não permite que um invasor execute códigos nem aumente seus direitos de usuário diretamente, mas ela pode ser usada para recuperar informações que podem ser usadas para tentar comprometer ainda mais o sistema afetado. Somente os aplicativos da Web usando o Microsoft Chart Control são afetados por este problema. As instalações padrão do .Net Framework não são afetadas.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a><br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft .NET Framework, <br />
Ferramentas para desenvolvedor da Microsoft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-067">MS11-067</a></td>
<td style="border:1px solid black;"><strong>A vulnerabilidade no Microsoft Report Viewer pode permitir divulgação não autorizada de informações (2578230)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Report Viewer. A vulnerabilidade pode permitir a divulgação não autorizada de informações se um usuário visualizar uma página da Web especialmente criada. Em todos os casos, no entanto, um invasor não teria nenhuma maneira de forçar um usuário a visitar tal site. Em vez disso, o invasor teria de convencer o usuário a visitar o site, tipicamente fazendo-o clicar em um link em uma mensagem de email ou em um programa de mensagens instantâneas que o conduziria ao site do invasor.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a><br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Ferramentas para desenvolvedor da Microsoft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-068">MS11-068</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Kernel do Windows pode permitir negação de serviço (2556532)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir negação de serviço se um usuário visitar um compartilhamento de rede (ou visitar um site que aponte para um compartilhamento de rede) contendo um arquivo especialmente criado. Em todos os casos, no entanto, o invasor não tem como forçar um usuário a visitar esses sites ou compartilhamentos de rede. Em vez disso, um invasor teria que convencer o usuário a visitar o site ou compartilhamento de rede, normalmente fazendo-o clicar em um link em uma mensagem de e-mail ou do Instant Messenger.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderada</a><br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-069">MS11-069</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no .Net Framework pode permitir a divulgação não autorizada de informações (2567951)</strong>  <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft .NET Framework. A vulnerabilidade pode permitir a divulgação não autorizada de informações se um usuário visualizar uma página da Web especialmente criada usando um navegador da Web que execute aplicativos de navegador XAML (XBAPs). No cenário de ataque na Web, o invasor terá que hospedar um site contendo uma página da Web usada para explorar essa vulnerabilidade. Além disso, sites comprometidos e sites que aceitem ou hospedem conteúdo fornecido pelo usuário ou anúncios pode conter conteúdo especialmente desenvolvido que pode explorar esta vulnerabilidade. Em todos os casos, entretanto, um invasor não teria como forçar os usuários a visitarem os sites. Em vez disso, o invasor teria que convencer os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um email ou mensagem do Instant Messenger que leva o usuário ao site do invasor. Esta vulnerabilidade também pode ser usada pelos aplicativos Windows .NET para anular as restrições do CAS (Code Access Security).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderada</a><br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft .NET Framework</td>
</tr>
</tbody>
</table>

<p></p>

  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas por ordem de ID do boletim e de ID da CVE. Só são incluídas as vulnerabilidades com uma classificação de gravidade Crítica ou Importante nos boletins.
  
**Como devo usar a tabela?**  
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o Índice de exploração da Microsoft.
  
Nas colunas a seguir, "Versão mais Recente de Software" se refere ao software, e "Versões mais Antigas de Software se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID do Boletim</th>
<th style="border:1px solid black;" >Título da vulnerabilidade</th>
<th style="border:1px solid black;" >ID do CVE</th>
<th style="border:1px solid black;" >Avaliação do risco de exploração para execução de códigos do última versão do software</th>
<th style="border:1px solid black;" >Avaliação do risco de exploração para execução de códigos das versões de software mais antigas</th>
<th style="border:1px solid black;" >Avaliação do risco de exploração para negação de serviço</th>
<th style="border:1px solid black;" >Principais observações</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição de abertura forçada de janela</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1257">CVE-2011-1257</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação não autorizada de manipuladores de eventos</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1960">CVE-2011-1960</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação de informações</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código do manipulador Telnet</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1961">CVE-2011-1961</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória de XSLT</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1963">CVE-2011-1963</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória de objeto de estilo</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1964">CVE-2011-1964</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-058">MS11-058</a></td>
<td style="border:1px solid black;">Vulnerabilidade de consulta de NAPTR de DNS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1966">CVE-2011-1966</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-058">MS11-058</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória não inicializada de DNS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1970">CVE-2011-1970</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de negação de serviço</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-059">MS11-059</a></td>
<td style="border:1px solid black;">Vulnerabilidade de carregamento não seguro de bibliotecas do Data Access Components</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1975">CVE-2011-1975</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-060">MS11-060</a></td>
<td style="border:1px solid black;">Vulnerabilidade pStream Release RCE</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1972">CVE-2011-1972</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-060">MS11-060</a></td>
<td style="border:1px solid black;">Vulnerabilidade Move Around the Block RCE</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1979">CVE-2011-1979</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-061">MS11-061</a></td>
<td style="border:1px solid black;">Vulnerabilidade de Acesso via Web da Área de Trabalho Remota</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1263">CVE-2011-1263</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-062">MS11-062</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do NDISTAPI</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1974">CVE-2011-1974</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-063">MS11-063</a></td>
<td style="border:1px solid black;">Vulnerabilidade de CSRSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1967">CVE-2011-1967</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração consistente</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-064">MS11-064</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço do ICMP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1871">CVE-2011-1871</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de negação de serviço</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-064">MS11-064</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço de QOS do TCP/IP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1965">CVE-2011-1965</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de negação de serviço</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-065">MS11-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade do Protocolo de área de trabalho remota</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1968">CVE-2011-1968</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Ataques limitados e direcionados estão sendo relatados para esta vulnerabilidade<br />
<br />
Esta é uma vulnerabilidade de negação de serviço</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-066">MS11-066</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação não autorizada de informações do Controle de Gráfico</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1977">CVE-2011-1977</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação de informações</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-067">MS11-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de XSS dos controles do Report Viewer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1976">CVE-2011-1976</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Código de exploração de funcionamento improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação de informações</td>
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
  
**Tabela 1**

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="7">
Windows XP (site em inglês)  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-063)
</td>
</tr>
<tr class="alternateRow">
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=90312c78-1fbd-4143-b2e6-ae5c48af6f57)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a771c93b-55a4-456f-a315-d0d1f2696960)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5feb8ed7-99d2-4dd6-986f-57a7fd0c6f19)  
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
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6bc1f0ac-223d-4b0b-86cd-2ba3863955c4)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0231c103-c0cb-4705-9d92-5356b8cbb265)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=23d77f3b-13f8-49f3-9c3c-27ad217cd59e)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=acb14d82-a801-4ec7-84cc-9f131009ebcb)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=272c813b-bd39-4e63-9fa7-c5b8ed0b08d7)  
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
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d5ee6787-408d-4870-af70-9338158b161b)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=09276f6e-e3f4-4b7e-996e-4ec376c103e1)  
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
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=26b5fb48-346a-49f1-840f-03f218a41c20)  
(Importante)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=042552ad-f46a-4bfc-9e5c-58f095eba1de)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=648596fc-fd97-438a-97be-d5d590f1c561)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4aa38-9241-465d-8d65-aba73e936d0f)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8de0f2db-aa09-48cd-a13b-e26a973e9cdc)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=870fdfdd-16bf-42a2-a23b-ed6045438d5e)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9c3d14d8-6716-4423-91a9-a05373227237)  
(Importante)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c9e283d8-d4a2-41e2-a73c-92fae957ba3d)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=470d56d1-5789-42cc-a088-a2c8ac934ab3)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2db4098a-f4f9-4211-b55d-5d0df1409c43)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8f208407-4bb3-41fe-b0d6-fc8a5e30e667)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=31af27b8-7b73-4090-94bd-2fb89d3970fc)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=64496a87-2225-402a-a94a-a8e92b17ac83)  
(Importante)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5aa3a493-4188-48a9-a549-cf9ba01ed32a)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1934acfa-5637-4ae9-9e9a-fc7e58930b7a)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ef140089-d022-4ee8-9cc4-7fb25295a39d)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=410c72d8-3b78-4c4a-ad61-acb7f854ffc2)  
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
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-063)
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
Nenhuma
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=66ddc7ce-5280-494d-bb3c-dab06e27fb5c)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a080f36e-c24f-40ac-bb40-b26cb31bcae3)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c82417ec-232f-4f84-ba2c-0ffad77e9bb5)  
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
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8f25ced5-ef86-4b9d-91fb-443c9a2c1458)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3f119902-8398-4814-8229-9eb9f0980e87)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=704c1c9c-d1c1-40cb-97a7-fbb1f195f9f8)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=a6ff7b27-bc21-4945-8b2e-757b6f83fa58)  
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
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d5b8ff09-237e-49f1-a566-e323ca11fbc3)  
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
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-063)
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
Nenhuma
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=da9c98d1-973c-44d9-aee5-f5c4a8e8c0e1)\*\*  
(Crítica)  
Internet Explorer 8\*\*  
(Crítica)  
Internet Explorer 9\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ac2d5122-6f9b-46f5-9840-77aa7ff84308)\*  
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
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1fbaabb9-8601-4760-813d-aeedfdcafb8b)\*  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9facff69-618f-4a64-8665-5dd6cde07de9)\*\*  
(Crítica)  
Internet Explorer 8\*\*  
(Crítica)  
Internet Explorer 9\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5f605f6f-3854-403d-878b-637626aef78f)\*  
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
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2e7253d8-fdc7-4563-9714-21ca3c77e4b1)\*  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=01885624-cfb1-4918-abef-ab0ea765cb04)  
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
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fe37eb6d-b1fa-496c-a0d3-19a6d35a6cb9)  
(Importante)
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-063)
</td>
</tr>
<tr class="alternateRow">
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
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7019de24-8c58-4565-ada1-ca8755115096)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=12292081-23f7-4968-8cd7-17aaef2aed6a)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6bc168d9-6664-41fb-914f-dbd7514a4b0e)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f4551b77-eb09-448a-9dc5-66de846035e7)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fcdb872f-2ee2-4f74-b7ae-1b82daf66761)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ef664114-6582-49d3-b332-078a7d075337)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64](http://www.microsoft.com/downloads/details.aspx?familyid=aafeff2d-db9a-4b3b-b620-be4ec5f5bdcc)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64](http://www.microsoft.com/downloads/details.aspx?familyid=0fc9a501-523d-4cbb-8d99-a773089afc4c)  
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
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-063)
</td>
</tr>
<tr class="alternateRow">
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=14fe68eb-2aa6-4a59-b9d8-deeae5236af2)\*\*  
(Crítica)  
Internet Explorer 9\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6a86e2cf-4e7d-4012-88c3-6957a3842dd3)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c29deec3-4672-4658-a550-dce244434cd4)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=777f3bbe-094c-411d-879d-34a5a20ae7f3)\*\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2f4043df-c07c-4611-b06a-7fcbb7416e7d)\*  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=82403fd3-ed75-4ea8-aa3f-ed9dda75612a)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1d6b8036-d38f-408a-a36c-027553faefc1)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b420cae3-de30-4c6c-8ed9-7431ad7ab4da)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observações para Windows Server 2008 e Windows Server 2008 R2**

**\*Instalação do núcleo do servidor afetada.** Esta atualização se aplica, com a mesma classificação de gravidade, às edições com suporte do Windows Server 2008 e do Windows Server 2008 R2, conforme indicado, independentemente de terem sido instalados ou não com a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**\*\*Instalação de Núcleo de Servidor não afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**Tabela 2**

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="6">
Windows XP (site em inglês)
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c07e1630-43ba-491e-bd59-9eb53105986c)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=797a01dc-39fb-4511-832a-42d2975133f5)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
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
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=694ba1a6-7512-497d-a572-646a6e07b13b)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=308da543-d49d-4591-8bbc-d65c524bb0ad)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=3b459bf0-7844-4740-895c-d149d56e781f)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-069)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=114c2835-921a-4d3e-be91-dfd217fd26a9)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9713b7b8-f260-440d-a994-845f17683fe9)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0fcee476-8d7e-49a7-b6ea-89043304a653)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4d67ec00-e86a-49b6-a9a2-85b2520fa4bb)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-069)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c01d9132-af5f-4039-8195-95f6761f2d0e)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=da219735-b8b7-4f97-b8a8-7c253838de6b)\*\*\*  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=70797adb-d693-4102-9e7c-ba1ea8fb07d0)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e077af5-5823-4377-a997-44b022a694d8)\*\*\*  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9babf81a-8b21-42ae-a65c-f414793516ab)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=560efa6f-c956-47cb-a2f4-a1f45278b7cd)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(Moderada)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-069)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=814bbdfa-7cbc-40e5-8ca3-8fed9d13ff00)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6c8dd72b-abf8-4e1f-aafc-777c1a3ef3db)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits apenas:  
Microsoft .NET Framework 3.5.1  
(KB2539634)  
(Moderada)  
Windows 7 para sistemas de 32 bits apenas:  
Microsoft .NET Framework 4<sup>[1]</sup>
(KB2539636)  
(Moderada)  
Windows 7 para sistemas de 32 bits Service Pack 1 apenas;  
Microsoft .NET Framework 3.5.1  
(KB2539635)  
(Moderada)  
Windows 7 para sistemas de 32 bits Service Pack 1 apenas;  
Microsoft .NET Framework 4<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64](http://www.microsoft.com/downloads/details.aspx?familyid=085ee785-b6ad-4c68-835a-e17bc8f12a53)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64](http://www.microsoft.com/downloads/details.aspx?familyid=d90c07c1-3c07-4989-825c-fb8453541a0e)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 apenas:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(Moderada)  
Windows 7 para sistemas baseados em x64 apenas:  
Microsoft .NET Framework 4<sup>[1]</sup>
(KB2539636)  
(Moderada)  
Windows 7 para sistemas baseados em x64 Service Pack 1 apenas:  
Microsoft .NET Framework 3.5.1  
(KB2539635)  
(Moderada)  
Windows 7 para sistemas baseados em x64 Service Pack 1 apenas:  
Microsoft .NET Framework 4<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9fd2b4ba-d98e-4ad6-99f2-c471335042d3)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 apenas:  
Microsoft .NET Framework 4<sup>[1]</sup>
(KB2487367)  
(Importante)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 apenas:  
Microsoft .NET Framework 4\*<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=67cccd09-5b82-4546-884a-d2a9e2400820)\*\*\*  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 apenas:  
Microsoft .NET Framework 3.5.1\*  
(KB2539634)  
(Moderada)  
Windows Server 2008 R2 para sistemas baseados em x64 apenas:  
Microsoft .NET Framework 4<sup>[1]</sup>
(KB2539636)  
(Moderada)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 apenas:  
Microsoft .NET Framework 3.5.1\*  
(KB2539635)  
(Moderada)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 apenas:  
Microsoft .NET Framework 4\*<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=93752c8f-5461-4e6f-9cab-6401b985ef17)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=a1edf843-9a2a-4334-a95f-78e75a9b3ef1)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em Itanium apenas:  
Microsoft .NET Framework 3.5.1  
(KB2539634)  
(Moderada)  
Windows Server 2008 R2 para sistemas baseados em Itanium apenas:  
Microsoft .NET Framework 4<sup>[1]</sup>
(KB2539636)  
(Moderada)  
Windows Server 2008 R2 para sistemas baseados em Itanium Service Pack 1 apenas:  
Microsoft .NET Framework 3.5.1  
(KB2539635)  
(Moderada)  
Windows Server 2008 R2 para sistemas baseados em Itanium Service Pack 1 apenas:  
Microsoft .NET Framework 4<sup>[1]</sup>
(KB2539636)  
(Moderada)
</td>
</tr>
</table>

<p></p>

 
**Observações para Windows Server 2008 e Windows Server 2008 R2**

**\*Instalação do núcleo do servidor afetada.** Esta atualização se aplica, com a mesma classificação de gravidade, às edições com suporte do Windows Server 2008 e do Windows Server 2008 R2, conforme indicado, independentemente de terem sido instalados ou não com a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**\*\*Instalação de Núcleo de Servidor não afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**\*\*\*Instalação Núcleo do Servidor não afetada.** A vulnerabilidade abordada por esta atualização não afeta as edições com suporte do Windows Server 2008 ou Windows Server 2008 R2, conforme indicado, quando instalada usando a opção de instalação Núcleo do Servidor, mesmo que os arquivos afetados por esta vulnerabilidade possam estar presentes no sistema. No entanto, esta atualização ainda será oferecida aos usuários com arquivos afetados porque os arquivos de atualização são mais novos (com números de versão mais altos) que os arquivos que estão atualmente no seu sistema. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**Observações para MS11-066**

<sup>[1]</sup>**O .NET Framework 4 Client Profile não foi afetado.** Os pacotes redistribuíveis do .Net Framework versão 4 estão disponíveis em dois perfis: .NET Framework 4 e .NET Framework 4 Client Profile. O .Net Framework 4 Client Profile é um subconjunto do .Net Framework 4. A vulnerabilidade abordada nesta atualização afeta somente o .Net Framework 4 e não o .Net Framework 4 Client Profile. Para obter mais informações, consulte o artigo de MSDN, Instalando o .NET Framework.

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

**Observação para o MS11-069**

<sup>[1]</sup>**.NET Framework 4 e .NET Framework 4 Client Profile afetados.** Os pacotes redistribuíveis do .Net Framework versão 4 estão disponíveis em dois perfis: .NET Framework 4 e .NET Framework 4 Client Profile. O .NET Framework 4 Client Profile é um subconjunto do .NET Framework 4. A vulnerabilidade abordada nesta atualização afeta tanto o .NET Framework 4 quanto o .NET Framework 4 Client Profile. Para obter mais informações, consulte o artigo de MSDN, Instalando o .NET Framework.

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-060**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-060)
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
Microsoft Visio 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=866d64b3-7147-4b5f-80fe-4d3317f140df)  
(KB2553009)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0eeabde-5a92-45ae-aef6-81b7bdb4e0cd)  
(KB2553010)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2010 e Microsoft Visio 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 e Microsoft Visio 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=6da236c2-0ef5-4c13-8393-673b70298a77)  
(KB2553008)  
(Importante)  
Microsoft Visio 2010 e Microsoft Visio 2010 Service Pack 1 (edições de 64 bits)  
(KB2553008)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

#### Software e ferramentas para desenvolvedor da Microsoft

 
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
Chart Control
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[**MS11-067**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-067)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
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
Chart Control para Microsoft .NET Framework 3.5 Service Pack 1
</td>
<td style="border:1px solid black;">
[Chart Control para Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8a80cc03-0db9-4446-9ce6-159ad02cab52)  
(KB2500170)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Studio e Microsoft Report Viewer
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[**MS11-067**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-067)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=59231988-5413-4238-a3aa-32a127871430)  
(KB2548826)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=28bf2ae0-9e21-4201-b7f1-a207abc2866f)  
(KB2579115)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para o MS11-066**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o Centro de Gerenciamento de Atualização do Technet. O site TechNet Security Center fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar Segurança em Casa, onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no Microsoft Update e no Windows Update. As atualizações de segurança também estão disponíveis no Centro de Download da Microsoft. Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Para os clientes do Microsoft Office for Mac, o Microsoft AutoUpdate for Mac pode ajudar a manter seu software Microsoft atualizado. Para obter mais informações sobre como usar o Microsoft AutoUpdate for Mac, consulte Check for software updates automatically.

Por fim, as atualizações de segurança podem ser baixadas do Microsoft Update Catalog. O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as Perguntas Frequentes sobre Microsoft Update Catalog.

**Orientação para detecção e implantação**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o Artigo 961747 (em inglês) da Microsoft Knowledge Base.

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite Microsoft Baseline Security Analyzer.

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite Windows Server Update Services.

**System Center Configuration Manager 2007**

O gerenciamento de atualizações de software do Configuration Manager 2007 simplifica a complexa tarefa de fornecer e gerenciar atualizações a sistemas de TI pela empresa. Com o Configuration Manager 2007, os administradores de TI podem fornecer atualizações de produtos da Microsoft a uma variedade de dispositivos, inclusive desktops, laptops, servidores e dispositivos móveis.

A avaliação automatizada de vulnerabilidade no Configuration Manager 2007 detecta as necessidades de atualizações e relatórios com relação a ações recomendadas. O gerenciamento de atualizações de software no Configuration Manager 2007 é integrado ao Microsoft Windows Software Update Services (WSUS), uma infraestrutura de atualização testada quanto à confiabilidade, que é familiar aos administradores de TI do mundo todo. Para obter mais informações sobre como os administradores podem usar o Configuration Manager 2007 para implantar atualizações, consulte Gerenciamento de atualizações de software. Para obter mais informações sobre o Configuration Manager, acesse: System Center Configuration Manager.

**Systems Management Server 2003**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários.

**Observação** O System Management Server 2003 está fora de suporte principal desde 12 de janeiro de 2010. Para obter mais informações sobre ciclos de vida de produtos, acesse Ciclo de Vida do Suporte Microsoft. A próxima versão do SMS, System Center Configuration Manager 2007, já está disponível; consulte também o **System Center Configuration Manager 2007**.

Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, consulte Cenários e procedimentos para o Microsoft Systems Management Server 2003: Distribuição de software e Gerenciamento de patches. Para obter informações sobre o SMS, acesse: Microsoft Systems Management Server TechCenter.

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte Implementando atualizações de software usando o Recurso Distribuição de Software do SMS. Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no SMS 2003 Administration Feature Pack) para instalar essas atualizações.

**Avaliador de Compatibilidade com Atualizações e Application Compatibility Toolkit**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do Avaliador de compatibilidade com atualizações incluídos no Kit de ferramentas de compatibilidade de aplicativos para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199)
-   : Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)
-   . Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em Parceiros do Microsoft Active Protections Program (MAPP).

#### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site Orientações de segurança para gerenciamento de atualizações oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no Centro de Download da Microsoft. Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no Microsoft Update.
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o Artigo 913086 (em inglês) da Microsoft Knowledge Base.

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site IT Pro Security Community (em inglês).

#### Agradecimentos

A Microsoft agradece às pessoas mencionadas abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   Yngve N. Pettersen, da Opera Software ASA, por relatar um problema descrito no boletim MS11-057
-   [Lostmon Lords](http://lostmon.blogspot.com)
-   por relatar um problema descrito no boletim MS11-057
-   Makoto Shiotsuki, da Security Professionals Network Inc., por relatar um problema descrito no boletim MS11-057
-   Um pesquisador anônimo, que trabalha na Zero Day Initiative da [TippingPoint](http://www.tippingpoint.com/), por relatar um problema descrito no boletim MS11-057.
-   Stephen Fewer da [Harmony Security](http://www.harmonysecurity.com/), que trabalha com na TippingPoint's [Zero Day Initiative](http://www.zerodayinitiative.com/) por relatar um problema descrito no boletim MS11-057.
-   Michal Zalewski do [Google Inc.](http://www.google.com/) para trabalhar conosco em alterações de defesa profunda incluídas no boletim ms11-057
-   Grischa Zengel (Zengel Medizintechnik GmbH) por relatar um problema descrito no boletim MS11-058
-   Linlin Zhao da Baidu Security Team, por relatar dois problemas descritos no boletim MS11-060
-   Sven Taute por relatar um problema descrito no boletim MS11-061
-   Lufeng Li da Neusoft Corporation, por relatar um problema descrito no boletim MS11-062
-   Alex Ionescu da Winsider Seminars & Solutions Inc. por relatar um problema descrito no boletim MS11-063
-   Nico Leidecker e James Forshaw, da Context Information Security, por relatarem um problema descrito no boletim MS11-066
-   ADAM Bixby da Gotham Digital Science por relatar um problema descrito no boletim MS11-067
-   Zheng Wenbin de [Qihoo 360 Security Center](http://www.360.cn/) por relatar um problema descrito no boletim MS11-068
-   Michael J. Liu por relatar um problema descrito no boletim MS11-069

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site Ciclo de Vida do Suporte Microsoft.
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do Suporte de Segurança ou pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas. Para obter mais informações sobre as opções de suporte disponíveis, consulte Ajuda e Suporte da Microsoft.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de Ajuda e Suporte Internacional.

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (9 de agosto de 2011): Resumo de boletins publicado.
-   V1.1 (10 de agosto de 2011): Para MS11-059, foram corrigidas informações sobre necessidade de reinicialização na seção **Sinopses**. Para MS11-065, foi corrigida a principal observação no **índice de exploração** para CVE-2011-1968. Para MS11-068, foi revisada a anotação sobre o núcleo de servidor para o Windows Server 2008 e o Windows Server 2008 R2.
-   V1.2 (26 de outubro de 2011): Para o MS11-066 e MS11-069, corrigida aplicação de instalação do Server Core no .NET Framework 4 no Windows Server 2008 R2 para sistemas baseados em x64.

*Built at 2014-04-18T01:50:00Z-07:00*
