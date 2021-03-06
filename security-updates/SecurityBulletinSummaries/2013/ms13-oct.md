---
TOCTitle: 'MS13-OCT'
Title: Resumo do Boletim de Segurança da Microsoft de outubro 2013
ms:assetid: 'ms13-oct'
ms:contentKeyID: 61233705
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms13-oct(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de outubro 2013
===========================================================

Publicado: terça-feira, 8 de outubro de 2013 | Atualizado: quarta-feira, 6 de novembro de 2013

**Versão:** 1.2

Este resumo de boletins lista os boletins de segurança lançados em outubro de 2013.

Com o lançamento dos boletins de segurança de setembro de 2013, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 3 de outubro de 2013. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 9 de outubro de 2013, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de outubro](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557381&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (2879017)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e oito vulnerabilidades relatadas em particular no Internet Explorer. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que conseguir explorar a mais severa das vulnerabilidades poderá obter os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades em drivers do modo do kernel do Windows podem permitir a execução remota de código (2870008)</strong><br />
<br />
Esta atualização de segurança resolve duas vulnerabilidades relatadas em particular no Microsoft Windows. A mais grave dessas vulnerabilidades podem permitir a execução remota de código se um usuário visualizar conteúdo compartilhado que incorpora arquivos de fonte OpenType ou de fonte TrueType. O invasor que explorar com êxito as vulnerabilidades poderá assumir o controle total de um sistema afetado.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-082">MS13-082</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no .NET Framework podem permitir a execução remota de código (2878890)</strong><br />
<br />
Essa atualização de segurança soluciona duas vulnerabilidades relatadas em particular e uma vulnerabilidade divulgada publicamente no Microsoft .NET Framework. A mais severa das vulnerabilidades pode permitir a execução remota de código se um usuário visitar um site que contém um arquivo OTF (OpenType Font, fonte do tipo aberto) especialmente criado usando um navegador capaz de instanciar aplicativos XBAP.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-083">MS13-083</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade na biblioteca de controle comum do Windows permite a execução remota de código (2864058)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um invasor enviar uma solicitação da Web especialmente criada a um aplicativo da Web ASP.NET em execução em um sistema afetado. Um invasor pode explorar essa vulnerabilidade sem autenticação para executar código arbitrário.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-084">MS13-084</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft SharePoint Server podem permitir a execução remota de código (2885089)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no software Microsoft Office Server. A vulnerabilidade mais severa pode permitir a execução remota de código se um usuário abrir um arquivo do Office especialmente criado em uma versão afetada do Microsoft SharePoint Server, do Microsoft Office Services ou do Web Apps.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-085">MS13-085</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Excel podem permitir a execução remota de código (2885080)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft Office. As vulnerabilidades mais severas podem permitir a execução remota de código se um usuário abrir um arquivo do Office especialmente criado com uma versão afetada do Microsoft Excel ou de outro software afetado do Microsoft Office. O invasor que explorar com êxito as vulnerabilidades poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-086">MS13-086</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Word podem permitir a execução remota de código (2885084)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft Office. As vulnerabilidades podem permitir a execução remota de código se um arquivo especialmente criado for aberto em uma versão afetada do software Microsoft Office. O invasor que explorar com êxito as vulnerabilidades poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-087">MS13-087</a></td>
<td style="border:1px solid black;"><strong>A vulnerabilidade no Silverlight pode permitir a divulgação não autorizada de informação (2890788)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Silverlight. A vulnerabilidade poderá permitir a divulgação de informações se o invasor hospedar um site que contenha um aplicativo do Silverlight especialmente criado que poderá explorar esta vulnerabilidade e, então, convencer um usuário a exibir o site. O invasor também pode tirar proveito dos sites comprometidos e de sites que aceitam ou hospedam o conteúdo fornecido pelo usuário ou anúncios. Esses sites podem ter conteúdo especialmente criado para explorar essa vulnerabilidade. Não há como o invasor forçar os usuários a visitarem o site mal intencionado. Em vez disso, um invasor tem que convencer os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um email ou por um pedido pelo Instant Messenger que leva os usuários ao site do invasor. Também é possível exibir conteúdo da Web próprio para a finalidade usando anúncios de banner ou outros métodos para implantar conteúdo da Web nos sistemas afetados.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Não exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3872">CVE-2013-3872</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3873">CVE-2013-3873</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3874">CVE-2013-3874</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3875">CVE-2013-3875</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3882">CVE-2013-3882</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3885">CVE-2013-3885</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3886">CVE-2013-3886</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3893">CVE-2013-3893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade foi divulgada publicamente.<br />
<br />
A Microsoft está ciente dos ataques direcionados que tentam explorar essa vulnerabilidade no Internet Explorer 8 e no Internet Explorer 9.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-080">MS13-080</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3897">CVE-2013-3897</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">A Microsoft está ciente dos ataques direcionados que tentam explorar essa vulnerabilidade no Internet Explorer 8.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Vulnerabilidade de análise de Fonte OpenType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-082">MS13-082</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Vulnerabilidade do Windows USB Descriptor</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3200">CVE-2013-3200</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3879">CVE-2013-3879</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do App Container</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3880">CVE-2013-3880</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">É uma vulnerabilidade de divulgação não autorizada de informações que pode levar a uma elevação de privilégio.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Vulnerabilidade de página NULA do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3881">CVE-2013-3881</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Vulnerabilidade de fetch duplo do subsistema kernel de gráficos do DirectX</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3888">CVE-2013-3888</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-081">MS13-081</a></td>
<td style="border:1px solid black;">Vulnerabilidade da tabela CMAP de fonte TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3894">CVE-2013-3894</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-082">MS13-082</a></td>
<td style="border:1px solid black;">Vulnerabilidade de análise de Fonte OpenType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-081">MS13-081</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-082">MS13-082</a></td>
<td style="border:1px solid black;">Vulnerabilidade de expansão de entidade</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3860">CVE-2013-3860</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-082">MS13-082</a></td>
<td style="border:1px solid black;">Vulnerabilidade de análise de JSON</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3861">CVE-2013-3861</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).<br />
<br />
Esta vulnerabilidade foi divulgada publicamente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-083">MS13-083</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de número inteiro no Comctl32</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3195">CVE-2013-3195</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-084">MS13-084</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-085">MS13-085</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-084">MS13-084</a></td>
<td style="border:1px solid black;">Vulnerabilidade de injeção de parâmetro</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3895">CVE-2013-3895</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-085">MS13-085</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade também afeta o boletim <a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-084">MS13-084</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-085">MS13-085</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3890">CVE-2013-3890</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-086">MS13-086</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3891">CVE-2013-3891</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-086">MS13-086</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3892">CVE-2013-3892</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-087">MS13-087</a></td>
<td style="border:1px solid black;">Vulnerabilidade do Silverlight</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3896">CVE-2013-3896</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de divulgação não autorizada de informações que pode levar a um desvio de recurso de segurança.</td>
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
<th colspan="5">
Windows XP (site em inglês)  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Internet Explorer 6   
(2879017)  
(Crítica)  
Internet Explorer 7   
(2879017)  
(Crítica)  
Internet Explorer 8   
(2879017)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2847311)  
(Crítica)  
Windows XP Service Pack 3  
(2862330)  
(Importante)  
Windows XP Service Pack 3  
(2862335)  
(Importante)  
Windows XP Service Pack 3  
(2868038)  
(Importante)  
Windows XP Service Pack 3  
(2883150)  
(Crítica)  
Windows XP Service Pack 3  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(Crítica)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4  
(2861188)  
(Crítica)
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
(2879017)  
(Crítica)  
Internet Explorer 7   
(2879017)  
(Crítica)  
Internet Explorer 8   
(2879017)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2847311)  
(Crítica)  
Windows XP Professional x64 Edition Service Pack 2  
(2862330)  
(Importante)  
Windows XP Professional x64 Edition Service Pack 2  
(2862335)  
(Importante)  
Windows XP Professional x64 Edition Service Pack 2  
(2868038)  
(Importante)  
Windows XP Professional x64 Edition Service Pack 2  
(2883150)  
(Crítica)  
Windows XP Professional x64 Edition Service Pack 2  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(Crítica)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4  
(2861188)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2864058)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(Moderada)  
Internet Explorer 7  
(2879017)  
(Moderada)  
Internet Explorer 8  
(2879017)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2847311)  
(Crítica)  
Windows Server 2003 Service Pack 2  
(2862330)  
(Importante)  
Windows Server 2003 Service Pack 2  
(2862335)  
(Importante)  
Windows Server 2003 Service Pack 2  
(2868038)  
(Importante)  
Windows Server 2003 Service Pack 2  
(2883150)  
(Crítica)  
Windows Server 2003 Service Pack 2  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(Crítica)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4  
(2861188)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2864058)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(Moderada)  
Internet Explorer 7  
(2879017)  
(Moderada)  
Internet Explorer 8  
(2879017)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2847311)  
(Crítica)  
Windows Server 2003 x64 Edition Service Pack 2  
(2862330)  
(Importante)  
Windows Server 2003 x64 Edition Service Pack 2  
(2862335)  
(Importante)  
Windows Server 2003 x64 Edition Service Pack 2  
(2868038)  
(Importante)  
Windows Server 2003 x64 Edition Service Pack 2  
(2883150)  
(Crítica)  
Windows Server 2003 x64 Edition Service Pack 2  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861189)  
(Crítica)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4  
(2861188)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2864058)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(Moderada)  
Internet Explorer 7  
(2879017)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2847311)  
(Crítica)  
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2862330)  
(Importante)  
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2862335)  
(Importante)  
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2868038)  
(Importante)  
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2883150)  
(Crítica)  
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863239)  
(Importante)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(2864058)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Internet Explorer 7  
(2879017)  
(Crítica)  
Internet Explorer 8  
(2879017)  
(Crítica)  
Internet Explorer 9   
(2879017)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2847311)  
(Crítica)  
Windows Vista Service Pack 2  
(2855844)  
(Crítica)  
Windows Vista Service Pack 2  
(2862330)  
(Importante)  
Windows Vista Service Pack 2  
(2862335)  
(Importante)  
Windows Vista Service Pack 2  
(2864202)  
(Importante)  
Windows Vista Service Pack 2  
(2868038)  
(Importante)  
Windows Vista Service Pack 2  
(2876284)  
(Importante)  
Windows Vista Service Pack 2  
(2883150)  
(Crítica)  
Windows Vista Service Pack 2  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(Crítica)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4  
(2861188)  
(Crítica)  
Microsoft .NET Framework 4.5  
(2861193)  
(Crítica)  
Microsoft .NET Framework 4.5  
(2861208)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2864058)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(Crítica)  
Internet Explorer 8  
(2879017)  
(Crítica)  
Internet Explorer 9   
(2879017)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2847311)  
(Crítica)  
Windows Vista x64 Edition Service Pack 2  
(2855844)  
(Crítica)  
Windows Vista x64 Edition Service Pack 2  
(2862330)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(2862335)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(2864202)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(2868038)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(2876284)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(2883150)  
(Crítica)  
Windows Vista x64 Edition Service Pack 2  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(Crítica)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4  
(2861188)  
(Crítica)  
Microsoft .NET Framework 4.5  
(2861193)  
(Crítica)  
Microsoft .NET Framework 4.5  
(2861208)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2864058)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(Moderada)  
Internet Explorer 8  
(2879017)  
(Moderada)  
Internet Explorer 9   
(2879017)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2847311)  
(Crítica)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2855844)  
(Crítica)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2862330)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2862335)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2864202)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2868038)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2876284)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2883150)  
(Crítica)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(Crítica)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4  
(2861188)  
(Crítica)  
Microsoft .NET Framework 4.5  
(2861193)  
(Crítica)  
Microsoft .NET Framework 4.5  
(2861208)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2864058)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(Moderada)  
Internet Explorer 8  
(2879017)  
(Moderada)  
Internet Explorer 9   
(2879017)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2847311)  
(Crítica)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2855844)  
(Crítica)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2862330)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2862335)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2864202)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2868038)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2876284)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2883150)  
(Crítica)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2861190)  
(Crítica)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4  
(2861188)  
(Crítica)  
Microsoft .NET Framework 4.5  
(2861193)  
(Crítica)  
Microsoft .NET Framework 4.5  
(2861208)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2864058)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2847311)  
(Crítica)  
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2862330)  
(Importante)  
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2862335)  
(Importante)  
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2864202)  
(Importante)  
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2868038)  
(Importante)  
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2876284)  
(Importante)  
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2883150)  
(Crítica)  
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2863253)  
(Importante)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2861697)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2864058)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(Crítica)  
Internet Explorer 9   
(2879017)  
(Crítica)  
Internet Explorer 10   
(2879017)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2847311)  
(Crítica)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2855844)  
(Crítica)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2862330)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2862335)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2864202)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2868038)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2876284)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2883150)  
(Crítica)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(Crítica)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4.5  
(2861208)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2864058)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(Crítica)  
Internet Explorer 9   
(2879017)  
(Crítica)  
Internet Explorer 10   
(2879017)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2847311)  
(Crítica)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2855844)  
(Crítica)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2862330)  
(Importante)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2862335)  
(Importante)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2864202)  
(Importante)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2868038)  
(Importante)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2876284)  
(Importante)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2883150)  
(Crítica)  
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(Crítica)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4.5  
(2861208)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2864058)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(Moderada)  
Internet Explorer 9   
(2879017)  
(Moderada)  
Internet Explorer 10   
(2879017)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2847311)  
(Crítica)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2855844)  
(Crítica)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2862330)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2862335)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2864202)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2868038)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2876284)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2883150)  
(Crítica)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(Crítica)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4.5  
(2861208)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2864058)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2847311)  
(Crítica)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2855844)  
(Crítica)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2862330)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2862335)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2864202)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2868038)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2876284)  
(Importante)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2883150)  
(Crítica)  
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2864058)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2847311)  
(Crítica)  
Windows 8 para sistemas de 32 bits  
(2862330)  
(Importante)  
Windows 8 para sistemas de 32 bits  
(2862335)  
(Importante)  
Windows 8 para sistemas de 32 bits  
(2863725)  
(Importante)  
Windows 8 para sistemas de 32 bits  
(2864202)  
(Importante)  
Windows 8 para sistemas de 32 bits  
(2868038)  
(Importante)  
Windows 8 para sistemas de 32 bits  
(2883150)  
(Crítica)  
Windows 8 para sistemas de 32 bits  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(Crítica)  
Microsoft .NET Framework 3.5  
(2861704)  
(Importante)  
Microsoft .NET Framework 3.5  
(2863243)  
(Importante)  
Microsoft .NET Framework 4.5  
(2861702)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2864058)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits  
(2847311)  
(Crítica)  
Windows 8 para sistemas de 64 bits  
(2862330)  
(Importante)  
Windows 8 para sistemas de 64 bits  
(2862335)  
(Importante)  
Windows 8 para sistemas de 64 bits  
(2863725)  
(Importante)  
Windows 8 para sistemas de 64 bits  
(2864202)  
(Importante)  
Windows 8 para sistemas de 64 bits  
(2868038)  
(Importante)  
Windows 8 para sistemas de 64 bits  
(2883150)  
(Crítica)  
Windows 8 para sistemas de 64 bits  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(Crítica)  
Microsoft .NET Framework 3.5  
(2861704)  
(Importante)  
Microsoft .NET Framework 3.5  
(2863243)  
(Importante)  
Microsoft .NET Framework 4.5  
(2861702)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits  
(2864058)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2847311)  
(Crítica)  
Windows Server 2012  
(2862330)  
(Importante)  
Windows Server 2012  
(2862335)  
(Importante)  
Windows Server 2012  
(2863725)  
(Importante)  
Windows Server 2012  
(2864202)  
(Importante)  
Windows Server 2012  
(2868038)  
(Importante)  
Windows Server 2012  
(2883150)  
(Crítica)  
Windows Server 2012  
(2884256)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(Crítica)  
Microsoft .NET Framework 3.5  
(2861704)  
(Importante)  
Microsoft .NET Framework 3.5  
(2863243)  
(Importante)  
Microsoft .NET Framework 4.5  
(2861702)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2864058)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="5">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
**Nenhuma**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows RT  
(2847311)  
(Crítica)  
Windows RT  
(2862330)  
(Importante)  
Windows RT  
(2862335)  
(Importante)  
Windows RT  
(2863725)  
(Importante)  
Windows RT  
(2864202)  
(Importante)  
Windows RT  
(2868038)  
(Importante)  
Windows RT  
(2883150)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2861702)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT  
(2864058)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
**Nenhuma**
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
Windows 8.1 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
<th colspan="5">
Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
(Moderada)
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
<th colspan="5">
Windows RT 8.1
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
<th colspan="5">
Opção de instalação do Server Core
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-080**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-080)
</td>
<td style="border:1px solid black;">
[**MS13-081**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-081)
</td>
<td style="border:1px solid black;">
[**MS13-082**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-082)
</td>
<td style="border:1px solid black;">
[**MS13-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-083)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do Server Core)  
(2847311)  
(Crítica)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do Server Core)  
(2862330)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do Server Core)  
(2862335)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do Server Core)  
(2864202)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do Server Core)  
(2876284)  
(Importante)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do Server Core)  
(2883150)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do Server Core)  
(2864058)  
(Nenhuma classificação de gravidade)
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
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do Server Core)  
(2847311)  
(Crítica)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do Server Core)  
(2862330)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do Server Core)  
(2862335)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do Server Core)  
(2864202)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do Server Core)  
(2876284)  
(Importante)  
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do Server Core)  
(2883150)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do Server Core)  
(2864058)  
(Crítica)
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
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)  
(2847311)  
(Crítica)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)  
(2862330)  
(Importante)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)  
(2862335)  
(Importante)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)  
(2864202)  
(Importante)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)  
(2876284)  
(Importante)  
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)  
(2883150)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(Importante)  
Microsoft .NET Framework 4  
(2858302)  
(Importante)  
Microsoft .NET Framework 4.5  
(2861208)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do Server Core)  
(2864058)  
(Crítica)
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
Windows Server 2012 (instalação Server Core)  
(2847311)  
(Crítica)  
Windows Server 2012 (instalação Server Core)  
(2862330)  
(Importante)  
Windows Server 2012 (instalação Server Core)  
(2862335)  
(Importante)  
Windows Server 2012 (instalação Server Core)  
(2863725)  
(Importante)  
Windows Server 2012 (instalação Server Core)  
(2864202)  
(Importante)  
Windows Server 2012 (instalação Server Core)  
(2883150)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(Crítica)  
Microsoft .NET Framework 3.5  
(2861704)  
(Importante)  
Microsoft .NET Framework 3.5  
(2863243)  
(Importante)  
Microsoft .NET Framework 4.5  
(2861702)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2864058)  
(Crítica)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**Observação sobre o MS13-080**

<sup>[1]</sup>Para Internet Explorer 11, os clientes devem aplicar o conjunto de atualizações do Windows RT 8.1, do Windows 8.1 e do Windows Server 2012 R2: Outubro de 2013 (2883200). Observe que o conjunto de atualizações 2883200 contém alterações de segurança e não relativos à segurança. Para obter mais informações e links disponíveis para download, consulte o [Artigo 2883200 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/2883200).

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-086)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Microsoft Word 2003 Service Pack 3  
(2826020)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-086)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2827324)  
(Importante)  
Microsoft Office 2007 Service Pack 3  
(2760585)  
(Importante)  
Microsoft Office 2007 Service Pack 3  
(2760591)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2827330)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-086)
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
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (edições de 32 bits)  
(2826033)  
(Importante)  
Microsoft Office 2010 Service Pack 1 (edições de 32 bits)  
(2826023)  
(Importante)  
Microsoft Office 2010 Service Pack 1 (edições de 32 bits)  
(2826035)  
(Importante)
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
Microsoft Excel 2010 Service Pack 1 (edições de 64 bits)  
(2826033)  
(Importante)  
Microsoft Office 2010 Service Pack 1 (edições de 64 bits)  
(2826023)  
(Importante)  
Microsoft Office 2010 Service Pack 1 (edições de 64 bits)  
(2826035)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (edições de 32 bits)  
(2826033)  
(Importante)  
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(2826023)  
(Importante)  
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(2826035)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (edições de 64 bits)  
(2826033)  
(Importante)  
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(2826023)  
(Importante)  
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(2826035)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-086)
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
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (edições de 32 bits)  
(2827238)  
(Importante)  
Microsoft Office 2013 (edições de 32 bits)  
(2817623)  
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
Microsoft Excel 2013 (edições de 64 bits)  
(2827238)  
(Importante)  
Microsoft Office 2013 (edições de 64 bits)  
(2817623)  
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
Microsoft Excel 2013 RT  
(2827238)  
(Importante)  
Microsoft Office 2013 RT  
(2817623)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office para Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-086)
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
**Nenhuma**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2889496)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Outros softwares do Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-085)
</td>
<td style="border:1px solid black;">
[**MS13-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-086)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3
</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(2827326)  
(Importante)
</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(2827329)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2827328)  
(Importante)
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
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-084)
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
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc) (versões de 32 bits)  
(2596741)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (wssloc) (versões de 64 bits)  
(2596741)  
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
[**MS13-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-084)
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
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1 (wssloc)  
(2589365)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wssloc)  
(2589365)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-084)
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
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (pptserver)  
(2760561)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação sobre o MS13-084**

Consulte também outras categorias de software nesta seção, **Softwares afetados**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

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
[**MS13-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-084)
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
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Excel Services  
(2827327)  
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
[**MS13-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-084)
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
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(Importante)  
Serviços de automação do Word  
(2826022)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(2826029)  
(Importante)  
Serviços de automação do Word  
(2826022)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-084)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade** **agregada**
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
Excel Services  
(2752002)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Serviços de automação do Word  
(2826036)  
(Importante)
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
[**MS13-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-084)
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
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 1  
(2826030)  
(Importante)  
Microsoft Excel Web App 2010 Service Pack 1  
(2826028)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2826030)  
(Importante)  
Microsoft Excel Web App 2010 Service Pack 2  
(2826028)  
(Importante)
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
[**MS13-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-084)
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
Microsoft Office Web Apps 2013
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2827222)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação sobre o MS13-084**

Consulte também outras categorias de software nesta seção, **Softwares afetados**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Ferramentas e softwares para desenvolvedores Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-087**](http://technet.microsoft.com/pt-br/security/bulletin/ms13-087)
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
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 quando instalado no Mac  
(2890788)  
(Importante)  
Microsoft Silverlight 5 Developer Runtime quando instalado no Mac  
(2890788)  
(Importante)  
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de clientes Microsoft Windows  
(2890788)  
(Importante)  
Microsoft Silverlight 5 Developer Runtime quando instalado em todas as versões com suporte de clientes Microsoft Windows  
(2890788)  
(Importante)  
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de servidores Microsoft Windows  
(2890788)  
(Importante)  
Microsoft Silverlight 5 Developer Runtime quando instalado em todas as versões com suporte de servidores Microsoft Windows  
(2890788)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

-   O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns.
-   O WSUS (Windows Server Update Services), SMS (Systems Management Server) e SCCM (System Center Configuration Manager) ajudam os administradores a distribuir as atualizações de segurança.
-   Os componentes do Avaliador de compatibilidade com atualizações, incluídos no Kit de ferramentas de compatibilidade de aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para informações sobre estas e outras ferramentas que estão disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/security/cc297183).

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

**MS13-080**

-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com)
-   , que trabalha com a
-   [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)
-   [da HP](http://www.zerodayinitiative.com/)
-   , por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3872)
-   Jose A. Vazquez, da Yenteasy Security Research, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3873)
-   Amol Naik, que trabalha com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)[da HP](http://www.zerodayinitiative.com/), por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3874)
-   Um pesquisador anônimo, trabalhando em conjunto com a [VeriSign iDefense Labs](http://labs.idefense.com), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3874)
-   Jose A. Vazquez, da Yenteasy Security Research, que trabalha com a [VeriSign iDefense Labs](http://labs.idefense.com), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3875)
-   Ivan Fratric, da [Equipe de segurança do Google](http://www.google.com/), por reportar a Vulnerabilidade de corrupção da memória do Internet Explorer (CVE-2013-3882)
-   Jose A. Vazquez, da Yenteasy - Security Research por reportar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3882)
-   Jose A. Vazquez, da Yenteasy - Security Research por reportar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3885)
-   Jose A. Vazquez, da Yenteasy Security Research, que trabalha com a [VeriSign iDefense Labs](http://labs.idefense.com), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3886)
-   Yoshihiro Ishikawa, da [LAC Co.,](http://www.lac.co.jp/) por trabalhar conosco na Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3893)
-   Hoodie22, trabalhando com o National Cyber Security Centre dos Países Baixos, por trabalhar conosco na Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3897)
-   Daniel Chechik da Equipe Trustwave SpiderLabs por trabalhar conosco na Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3897)
-   Renato Ettisberger da [IOprotect GmbH](http://ioprotect.ch/) por trabalhar conosco na Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3897)

**MS13-081**

-   Um pesquisador anônimo, que trabalha com [a](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative da HP](http://www.zerodayinitiative.com/), por relatar a vulnerabilidade de análise de fonte OpenType (CVE-2013-3128)
-   Andy Davis, do [NCC Group,](http://www.nccgroup.com/) por relatar a Vulnerabilidade do Windows USB Descriptor (CVE-2013-3200)
-   Lucas Bouillot da ANSSI, por relatar a Vulnerabilidade do Windows USB Descriptor (CVE-2013-3200)
-   Seth Gibson e Dan Zentner, da [Endgame](http://www.endgame.com/) por relatar a Vulnerabilidade de página NULA do Win32k (CVE-2013-3881)
-   ZombiE, que trabalha com [a](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative da HP](http://www.zerodayinitiative.com/), por relatar a Vulnerabilidade da tabela CMAP de fonte TrueType (CVE-2013-3895)

**MS13-082**

-   Um pesquisador anônimo, que trabalha com [a](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative da HP](http://www.zerodayinitiative.com/), por relatar a vulnerabilidade de análise de fonte OpenType (CVE-2013-3128)
-   James Forshaw, da [Context Information Security](http://www.contextis.com/), por reportar a Vulnerabilidade da expansão da entidade (CVE-2013-3860)

**MS13-083**

-   孙晓山 do TCA, Instituto de Software da Academia Chinesa de Ciências por relatar a vulnerabilidade de estouro de inteiro Comctl32 (CVE-2013-3195)

**MS13-084**

-   Mateusz Jurczyk, Ivan Fratric e Ben Hawkes da [Equipe de Segurança de Google,](http://www.google.com/) por relatarem a Vulnerabilidade de corrupção da memória do Microsoft Excel (CVE-2013-3889)
-   Nutan kumar panda por relatar a Vulnerabilidade de injeção de parâmetro (CVE-2013-3895)
-   Ari Elias-Bachrach e Angela Kelso do [National Institutes of Health](http://nih.gov/) por trabalhar conosco nas alterações de defesa abrangentes incluídas este boletim

**MS13-085**

-   Mateusz Jurczyk, Ivan Fratric e Ben Hawkes da [Equipe de Segurança de Google,](http://www.google.com/) por relatarem a Vulnerabilidade de corrupção da memória do Microsoft Excel (CVE-2013-3889)
-   Mateusz Jurczyk, Ivan Fratric e Ben Hawkes da [Equipe de Segurança de Google,](http://www.google.com/) por relatarem a Vulnerabilidade de Corrupção da memória do Microsoft Excel (CVE-2013-3890)

**MS13-086**

-   Yuhong Bao por relatar a Vulnerabilidade de corrupção de memória (CVE-2013-3891)
-   Mateusz Jurczyk, Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google,](http://www.google.com/) por relatarem a Vulnerabilidade de corrupção de memória (CVE-2013-3892)

**MS13-087**

-   Vitaliy Toropov por relatar a vulnerabilidade no Silverlight (CVE-2013-3896)

#### Suporte

-   O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (8 de outubro de 2013): Resumo de boletins publicado.
-   V1.1 (10 de outubro de 2013): Para o MS13-080, removemos a avaliação do risco de exploração no Índice de exploração para CVE-2013-3871. Incluindo este CVE no Índice de exploração original era um erro de documentação. O CVE-2013-3871 está programado para ser abordado em uma atualização de segurança futura. Esta é apenas uma alteração informativa. Para MS13-082, boletim revisado para indicar que as instalações do Server Core do Windows Server 2012 são afetadas pela vulnerabilidade abordada na atualização 2861194. Não houve alterações à lógica de detecção nem aos arquivos de atualização de segurança. Os clientes que já atualizaram seus sistemas com êxito não precisam fazer mais nada.
-   V1.2 (6 de novembro de 2013): Para MS13-084, corrigimos o nome do produto para a atualização do Microsoft Office Web Apps Server 2013 (2827222).

*Built at 2014-04-18T01:50:00Z-07:00*
