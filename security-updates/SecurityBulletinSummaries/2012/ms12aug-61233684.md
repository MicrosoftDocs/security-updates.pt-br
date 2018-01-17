---
TOCTitle: 'MS12-AUG'
Title: Resumo do Boletim de Segurança da Microsoft de agosto 2012
ms:assetid: 'ms12-aug'
ms:contentKeyID: 61233684
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms12-aug(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de agosto 2012
==========================================================

Publicado: terça-feira, 14 de agosto de 2012 | Atualizado: terça-feira, 11 de dezembro de 2012

**Versão:** 3.0

Este resumo de boletins lista os boletins de segurança lançados em agosto de 2012.

Com o lançamento dos boletins de segurança de agosto de 2012, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 9 de agosto de 2012. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 15 de agosto de 2012, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de agosto](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522490&culture=en-us). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://go.microsoft.com/fwlink/?linkid=217214)

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-052">MS12-052</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para</strong> <strong>o Internet Explorer (2722913)</strong> <br />
<br />
Esta atualização de segurança resolve quatro vulnerabilidades relatadas em particular no Internet Explorer. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que explorar com êxito qualquer uma destas vulnerabilidades poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-053">MS12-053</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade na área de trabalho remota pode permitir a execução remota de código (2723135)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada particularmente no Protocolo de Área de Trabalho Remota. A vulnerabilidade pode permitir a execução remota de código se um invasor enviar uma sequência de pacotes RDP especialmente criados para um sistema afetado. Por padrão, o RDP (Remote Desktop Protocol, Protocolo de Área de Trabalho Remota) não é habilitado em nenhum sistema operacional do Windows. Os sistemas que não têm RDP habilitado não estão em risco.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-054">MS12-054</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades nos Componentesde conexão em rede do Windows podem permitir a execução remota de código (2733594)</strong> <br />
<br />
Esta atualização de segurança elimina quatro vulnerabilidades relatadas em particular no Microsoft Windows. A mais severa destas vulnerabilidades pode permitir a execução remota de código se um invasor enviar uma resposta especialmente criada a uma solicitação de spooler de impressão do Windows. As práticas recomendadas para firewall e as configurações de firewall padrão podem ajudar a proteger as redes contra ataques com origem externa ao perímetro da empresa. Essas práticas também recomendam que os sistemas conectados diretamente à Internet tenham um número mínimo de portas expostas.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-060">MS12-060</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade nos controles comuns do Windows pode permitir a execução remota de código (2720573)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular nos controles comuns do Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário visitar um site contendo conteúdo especialmente criado projetado para explorar a vulnerabilidade. No entanto, em todos os casos, um invasor não teria como forçar os usuários a visitarem tal site. Em vez disso, o invasor teria que convencer os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um e-mail ou mensagem do Instant Messenger que leva o usuário ao site do invasor. O arquivo mal-intencionado pode ser enviado também como um anexo de email, mas o invasor teria que convencer o usuário a abrir o anexo para explorar a vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft Server Software,<br />
Ferramentas para desenvolvedor da Microsoft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-058">MS12-058</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades na Exibição de Documento</strong> <strong>WebReady</strong> <strong>do Microsoft Exchange Server podem permitir execução remota de código (2740358)  <br />
</strong>Esta atualização de segurança elimina vulnerabilidades divulgadas publicamente na Exibição de Documento WebReady do Microsoft Exchange Server. As vulnerabilidades podem permitir a execução remota de código no contexto de segurança do serviço de transcodificação no Exchange Server se um usuário visualizar um arquivo especialmente criado usando o Outlook Web App (OWA). O serviço de transcodificação no Exchange usado para Visualização de documentos WebReady é executado na conta LocalService. A conta LocalService tem privilégios mínimos no computador local e apresenta credenciais anônimas na rede.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Não exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-055">MS12-055</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade nos drivers do modo</strong> <strong>kernel</strong> <strong>do Windows pode permitir a elevação de privilégio (2731847)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um invasor faz logon no sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-056">MS12- 056</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade nos mecanismos</strong> <strong>JScript</strong> <strong>e</strong> <strong>VBScript</strong> <strong>pode permitir a execução remota de código (2706045)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular nos mecanismos de scripts JScript e VBScript em versões de 64 bits do Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código caso um usuário tenha visitado um site especialmente criado. Não há como o invasor forçar os usuários a visitarem o site mal-intencionado. Em vez disso, o invasor teria que persuadir os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um e-mail ou mensagem do Instant Messenger que leva o usuário ao site do invasor.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-057">MS12- 057</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Office pode permitir a execução remota de código (2731879)  <br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office. A vulnerabilidade pode permitir a execução remota de código se um usuário abrir um arquivo especialmente criado ou incorporar um arquivo de gráficos CGM (Computer Graphics Metafile) especialmente criado em um arquivo do Office. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-059">MS12- 059</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Visio pode permitir a execução remota de código (2733918)  <br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office. A vulnerabilidade pode permitir a execução remota de código se o usuário abrir um arquivo do Visio especialmente criado. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-052">MS12-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória de layout</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1526">CVE-2012-1526</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-052">MS12-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código de Acesso de objeto NULL assíncrono</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2521">CVE-2012-2521</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-052">MS12-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código de corrompimento de tabela de função virtual</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2522">CVE-2012-2522</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-052">MS12-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código de estouro do número inteiro em JavaScript</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2523">CVE-2012-2523</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-056">MS12-056</a> também aborda essa vulnerabilidade.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-053">MS12-053</a></td>
<td style="border:1px solid black;">Vulnerabilidade do Protocolo de área de trabalho remota</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2526">CVE-2012-2526</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-054">MS12-054</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço do Protocolo de administração remota</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1850">CVE-2012-1850</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-054">MS12-054</a></td>
<td style="border:1px solid black;">Vulnerabilidade de sequência de caracteres de formato de serviço do spooler de impressão</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1851">CVE-2012-1851</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-054">MS12-054</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de heap do Protocolo de administração remota</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1852">CVE-2012-1852</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-054">MS12-054</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de pilha do Protocolo de administração remota</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1853">CVE-2012-1853</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-055">MS12-055</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2527">CVE-2012-2527</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-056">MS12- 056</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código de estouro do número inteiro em JavaScript</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2523">CVE-2012-2523</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-052">MS12-052</a> também aborda essa vulnerabilidade.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-057">MS12- 057</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória de formato de arquivo CGM</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2524">CVE-2012-2524</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-058">MS12-058</a></td>
<td style="border:1px solid black;">O Oracle Outside In contém várias vulnerabilidades que podem ser exploradas</td>
<td style="border:1px solid black;">Várias\*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">\*Várias vulnerabilidades, consulte o boletim <a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-058">MS12-058</a> para obter detalhes.<br />
<br />
Estas vulnerabilidades foram divulgadas publicamente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-059">MS12- 059</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro do buffer de formato de arquivo DXF do Visio</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1888">CVE-2012-1888</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-060">MS12-060</a></td>
<td style="border:1px solid black;">Vulnerabilidade de RCE MSCOMCTL.OCX</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1856">CVE-2012-1856</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">A Microsoft está ciente dos ataques direcionados que tentam explorar esta vulnerabilidade.</td>
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
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-052**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-052)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-053)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-054)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-055)
</td>
<td style="border:1px solid black;">
[**MS12- 056**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-056)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e1df425a-a67e-42f8-9eb5-a503f684c201)  
(KB2722913)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5afc85e3-a214-4774-93ab-17f9d199ebde)  
(KB2722913)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=213b3590-381e-437c-9391-ff6d7400f250)  
(KB2722913)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ccc3d8fb-2631-42d0-87ed-5d29d4b1f598)  
(KB2723135)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=5403c78c-6b87-4788-89c3-0140b887ec6f)  
(KB2705219)  
(Crítica)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c28e01d6-0030-417d-80dd-b34febd22ec1)  
(KB2712808)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=db21a230-0f6b-4d74-9f32-3718a59efd28)  
(KB2731847)  
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2fdbe657-1810-4c5d-9ba8-5da148272756)  
(KB2722913)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ce5e8621-5457-4a27-9816-9ce719fd6937)  
(KB2722913)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=01784bbc-20fc-4d0f-bfcd-a5a25dd603e8)  
(KB2722913)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a8eb0583-071d-4d8e-92fb-937035411b49)  
(KB2705219)  
(Crítica)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9e41497-5c49-45fc-8ad0-c853516609df)  
(KB2712808)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a036c343-5c6e-4484-b7f7-c7161c6880fd)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=e1b9a081-0329-4db6-b026-04a332cb0b4d)  
(KB2706045)  
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
[**MS12-052**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-052)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-053)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-054)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-055)
</td>
<td style="border:1px solid black;">
[**MS12- 056**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Baixa**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e5e3e9be-ba36-4fdf-93f6-a30fb087d273)  
(KB2722913)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0bced0f3-9778-4ee3-86fb-7f28b57adbce)  
(KB2722913)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=19393940-2519-4e97-89cd-de993ced31d5)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2847952f-0234-4cf6-820a-1f0a285b2fb7)  
(KB2705219)  
(Importante)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c20f475d-5211-4fdc-8a2f-4408f1baaece)  
(KB2712808)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=50090b08-3f82-4680-b871-2b18fc2386d0)  
(KB2731847)  
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=eb92185b-405a-4d96-b119-13f234a9c4ac)  
(KB2722913)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=26cda257-6607-4bd8-9152-cbcc2a753915)  
(KB2722913)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fe7a78fc-f882-4748-a9e3-04b85d136ca2)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3833d768-1dab-4a85-822f-87c7fa3db261)  
(KB2705219)  
(Importante)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad883d42-d8bb-482b-bf36-e2007cf73f84)  
(KB2712808)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7f72ba9a-80b2-459d-acad-da6a8b900d6f)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=81f5d8a5-12e5-4227-ae6f-5aea6ffff2a5)  
(KB2706045)  
(Baixa)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6c5edf14-ecb6-40af-a315-b049457415d6)  
(KB2722913)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c890335b-6ceb-427a-9cc7-95ef8c26d306)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2fba3a11-3621-464d-ab22-d902195205f4)  
(KB2705219) (Importante)  
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2857701f-3447-452c-a986-9f2fe42fe64d)(KB2712808)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9e647f22-2e80-4f4a-b648-615243741df2)  
(KB2731847)  
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
[**MS12-052**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-052)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-053)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-054)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-055)
</td>
<td style="border:1px solid black;">
[**MS12- 056**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-056)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=862bd543-2fc5-4c4c-8d18-4623ccc68166)  
(KB2722913)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=709a85b7-d192-4bba-990a-ea98fdf6e882)  
(KB2722913)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=430a43fa-78b8-4273-81e1-3081767ddcf9)  
(KB2722913)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cbae6606-3721-48b9-ba3e-9d85df7e08b9)  
(KB2705219)  
(Moderada)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b4b216dc-533e-4fb4-acc8-ce5eb231320e)  
(KB2712808)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=41362740-876e-4c9e-9729-67dea6830438)  
(KB2731847)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=da933584-40ba-42a0-82fc-b84b41c6c5a4)  
(KB2722913)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ec48d017-d9ed-4b0e-b51f-0f04996088b6)  
(KB2722913)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=5341a615-b737-4e48-8dfd-828725d9d513)  
(KB2722913)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e4b4e53b-69d6-4ab6-98bb-3f8871048abe)  
(KB2705219)  
(Moderada)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dc966826-83e6-4bdc-bc58-8b6eb8917934)  
(KB2712808)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=007b4d50-b770-4e8f-b8d0-060f7bb58ad5)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=294a7eb4-c47f-449f-8931-262bec7d6ecc)  
(KB2706045)  
(Importante)
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
[**MS12-052**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-052)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-053)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-054)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-055)
</td>
<td style="border:1px solid black;">
[**MS12- 056**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-056)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Baixa**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=91062e12-401e-472e-a6b6-0eb7216f5264)  
(KB2722913)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=77612ea1-13fb-4c53-bbd2-8796f0d5a9ed)  
(KB2722913)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=f016949d-b931-49f3-867b-f1c64839379e)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=354e502b-3016-4c5e-8611-bc1b35e1a7eb)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=35fb03b1-162a-4552-8bb9-6b564acbd57b)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ec759712-2f38-41a9-8b6d-c6908cc58479)  
(KB2731847)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a610d606-ca70-4dbd-9971-b6915dc4dc59)  
(KB2722913)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=defe6c53-66d7-4ea5-93b1-7487ccf19f24)  
(KB2722913)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=e5ab43bb-dbdb-4b2b-bbf2-260297ee5518)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2b8a730c-46ac-49b7-b9ae-73062d5a79f2)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e89024ca-a9e8-4ebf-91eb-cbf8e05398e7)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=caf68d77-3315-4383-a901-ba0385ffe561)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=47b2e47f-30f1-48e8-a857-70df319011ef)  
(KB2706045)  
(Baixa)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6564a6a1-c8ba-4275-81b5-6664c8e3d010)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cce9a924-a74c-49e0-869f-6b9c1cd12cba)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=57153478-4837-438a-8487-929a48fd758a)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dee601c7-4ab4-4556-8d83-90864b09d365)  
(KB2731847)  
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
[**MS12-052**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-052)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-053)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-054)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-055)
</td>
<td style="border:1px solid black;">
[**MS12- 056**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-056)
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
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Windows 7 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=625c45f5-5ad1-4ade-8883-33019587ab49)  
(KB2722913)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b2760784-6163-4a8d-86fb-72c88ed2b8ef)  
(KB2722913)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=f83f6d97-24f1-4ee0-971d-ab79071fede6)  
(KB2705219)  
(Moderada)  
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=2bcfb574-a7d0-4d7e-b557-41bdcddfde42)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=c709aabf-4b3f-4780-8b82-c6c33a211e31)  
(KB2731847)  
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=625c45f5-5ad1-4ade-8883-33019587ab49)  
(KB2722913)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b2760784-6163-4a8d-86fb-72c88ed2b8ef)  
(KB2722913)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f83f6d97-24f1-4ee0-971d-ab79071fede6)  
(KB2705219)  
(Moderada)  
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2bcfb574-a7d0-4d7e-b557-41bdcddfde42)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c709aabf-4b3f-4780-8b82-c6c33a211e31)  
(KB2731847)  
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f5bc6713-2540-4571-ae1f-04f427b33019)  
(KB2722913)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=cac3b463-fb9c-474e-9e3d-bb96f7b4c14f)  
(KB2722913)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=f49e3f9e-8a96-43e6-8b0a-5c9b78cd819d)  
(KB2705219)  
(Moderada)  
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=655182f9-110b-4b81-b140-0a5986d7343f)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=f62cf24a-8926-4dde-95ac-cc5f62e448be)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ece661be-4ddf-42cc-a62b-15ce53b9d74b)  
(KB2706045)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f5bc6713-2540-4571-ae1f-04f427b33019)  
(KB2722913)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=cac3b463-fb9c-474e-9e3d-bb96f7b4c14f)  
(KB2722913)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=f49e3f9e-8a96-43e6-8b0a-5c9b78cd819d)  
(KB2705219)  
(Moderada)  
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=655182f9-110b-4b81-b140-0a5986d7343f)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=f62cf24a-8926-4dde-95ac-cc5f62e448be)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ece661be-4ddf-42cc-a62b-15ce53b9d74b)  
(KB2706045)  
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
[**MS12-052**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-052)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-053)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-054)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-055)
</td>
<td style="border:1px solid black;">
[**MS12- 056**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Baixa**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f6ea664b-575c-4cf0-b479-d1a2653288ee)  
(KB2722913)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=30a43d95-f489-49c2-a48a-a262fa196bbf)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=bbb876e6-a6b9-4193-be5e-d84390d30f1e)  
(KB2706045)  
(Baixa)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f6ea664b-575c-4cf0-b479-d1a2653288ee)  
(KB2722913)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=30a43d95-f489-49c2-a48a-a262fa196bbf)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=bbb876e6-a6b9-4193-be5e-d84390d30f1e)  
(KB2706045)  
(Baixa)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=05a09f6e-b608-4430-b6d4-bb9d10d8347a)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=be89e6a5-34ef-4c23-8e16-722b9ae92073)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=27b52fb5-ff3c-4dca-9752-1517b873c9cb)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7f17c057-939e-415d-b56a-01082695ab77)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=97004a96-0c83-421d-91a9-d55be32610c9)  
(KB2706045)  
(Baixa)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=05a09f6e-b608-4430-b6d4-bb9d10d8347a)  
(KB2722913)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=be89e6a5-34ef-4c23-8e16-722b9ae92073)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=27b52fb5-ff3c-4dca-9752-1517b873c9cb)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7f17c057-939e-415d-b56a-01082695ab77)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
[JScript 5.8 e VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=97004a96-0c83-421d-91a9-d55be32610c9)  
(KB2706045)  
(Baixa)
</td>
</tr>
<tr>
<th colspan="6">
Opção de instalação de núcleo de servidor
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-052**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-052)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-053)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-054)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-055)
</td>
<td style="border:1px solid black;">
[**MS12- 056**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de** **gravidade agregada**
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=354e502b-3016-4c5e-8611-bc1b35e1a7eb)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=35fb03b1-162a-4552-8bb9-6b564acbd57b)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ec759712-2f38-41a9-8b6d-c6908cc58479)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2b8a730c-46ac-49b7-b9ae-73062d5a79f2)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e89024ca-a9e8-4ebf-91eb-cbf8e05398e7)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=caf68d77-3315-4383-a901-ba0385ffe561)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(Moderada)  
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft Office Suites e software
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-060)
</td>
<td style="border:1px solid black;">
[**MS12- 057**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-057)
</td>
<td style="border:1px solid black;">
[**MS12- 059**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-059)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)  
(Controles comuns do Windows)  
(KB2726929)  
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
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)  
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cc2a0eae-5b7e-465b-ab4c-a93ae7c7c458)  
(KB2596615)  
(Importante)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c2b0cb0f-db07-452f-a9a4-886124d3943e)  
(KB2596754)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)  
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cc2a0eae-5b7e-465b-ab4c-a93ae7c7c458)  
(KB2596615)  
(Importante)  
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c2b0cb0f-db07-452f-a9a4-886124d3943e)  
(KB2596754)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=4e08bab7-1408-444d-bad7-a4db76c7f6d3)  
(Controles comuns do Windows)  
(KB2597986)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=953b9b69-2f66-4f71-b342-467cc05030ba)  
(KB2687501)  
(Importante)  
[Microsoft Office 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=a55a33f9-1eb6-469a-967c-a483764772c3)  
(KB2687510)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=de95d8b9-51a5-43cd-8ba3-8cbb1320d099)  
(KB2687508)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=90b99372-4f13-4f3a-ae52-da6543745248)  
(KB2687501)  
(Importante)  
[Microsoft Office 2010 Service Pack 1 (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=da8a4d12-d4fc-4b6e-b65f-096dedddf529)  
(KB2687510)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1 (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=af690cd8-cb2c-4743-96f0-ffaec77adf10)  
(KB2687508)  
(Importante)
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office Web Components
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-060)
</td>
<td style="border:1px solid black;">
[**MS12- 057**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-057)
</td>
<td style="border:1px solid black;">
[**MS12- 059**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-059)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Web Components Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Web Components Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)  
(Controles comuns do Windows)  
(KB2726929)  
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
<th colspan="4">
Outros softwares do Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-060)
</td>
<td style="border:1px solid black;">
[**MS12- 057**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-057)
</td>
<td style="border:1px solid black;">
[**MS12- 059**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-059)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 Service Pack 1 (edição de 32 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 (edição de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=62e87f7b-f48e-43a7-86d7-cbb8f0603ea3)  
(KB2598287)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 Service Pack 1 (edição de 64 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 (edição de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=3889e1b3-69b2-4a8f-a0d9-de8c7dc6f5ec)  
(KB2598287)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS12-060**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-060)
</td>
<td style="border:1px solid black;">
[**MS12-058**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-058)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
Atualização de GDR:  
[Microsoft SQL Server 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=22be7d30-86f8-4a3b-ba46-b08624581c61)  
(KB983812)  
(Crítica)  
Atualização de QFE:  
[Microsoft SQL Server 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=09ebb11b-2b82-4891-8ae9-03481c0d7b29)  
(KB983811)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Analysis Services Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Analysis Services Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=3f5f7d2c-1fd1-437d-a74c-f316c2cd7818)  
(KB983813)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 para sistemas de 32 bits Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 para sistemas de 32 bits Service Pack](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)4<sup>[1]</sup>
(Controles comuns do Windows)  
(KB2726929)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 para sistemas baseados em x64 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 para sistemas baseados em x64 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Controles comuns do Windows)  
(KB2726929)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 para sistemas baseados em Itanium Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 para sistemas baseados em Itanium Service Pack](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)4<sup>[1]</sup>
(Controles comuns do Windows)  
(KB2726929)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 Express Edition com Advanced Services Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 Express Edition com Advanced Services Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Controles comuns do Windows)  
(KB2726929)(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Controles comuns do Windows)  
(KB2687441)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Commerce Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-060)
</td>
<td style="border:1px solid black;">
[**MS12-058**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-058)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2002 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2002 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=9ad19d40-16ed-47ad-b907-8a48bb64c6d3)  
(KB2716389)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d972437-f71a-4576-b5c1-a940c0824438)  
(KB2716390)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2009
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009](http://www.microsoft.com/downloads/details.aspx?familyid=3879fecd-8360-4c01-b88e-d56e8570cafb)  
(KB2716392)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2009 R2
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009 R2](http://www.microsoft.com/downloads/details.aspx?familyid=ce4f9470-e2b2-417e-9015-30355e837fbb)  
(KB2716393)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Host Integration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3dde4ef1-d41f-45b0-8660-a546cbe3fc81)  
(KB2711207)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-060)
</td>
<td style="border:1px solid black;">
[**MS12-058**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-058)
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
[Microsoft Exchange Server 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=21a26e23-9d83-41b6-95be-4b48f6e76023)  
(KB2756497)  
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
[Microsoft Exchange Server 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8646aaca-9829-4d3f-a77b-d24673818da7)  
(KB2756496)  
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
[Microsoft Exchange Server 2010 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b24182a-cee9-4ca0-9cc5-c4453475999d)  
(KB2756485)  
(Crítica)
</td>
</tr>
</table>

<p></p>

 
**Observações para o boletimMS12-060**

<sup>[1]</sup> Esta atualização é a mesma da atualização KB2726929 do Microsoft Office 2003

<sup>[2]</sup> Esta atualização é a mesma da atualização KB2687441 do Microsoft Office 2007

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Ferramentas e softwares para desenvolvedores Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual FoxPro
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-060)
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
Microsoft Visual FoxPro 8.0 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=0bef712a-b9e0-4ea9-98bf-68db366c8b8b)  
(KB2708940)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1ee09491-4871-41ca-a39c-8360d5a568d4)  
(KB2708941)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Visual Basic
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-060)
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
Visual Basic 6.0 Runtime
</td>
<td style="border:1px solid black;">
[Visual Basic 6.0 Runtime](http://www.microsoft.com/downloads/details.aspx?familyid=847ec64b-95be-463b-bdfb-969e91fe3207)  
(KB2708437)  
(Crítica)
</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS12-060**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://www.microsoft.com/brasil/security/), onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) e no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://www.microsoft.com/downloads/search.aspx?displaylang=pt-br). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Para os clientes do Microsoft Office for Mac, o Microsoft AutoUpdate for Mac pode ajudar a manter seu software Microsoft atualizado. Para obter mais informações sobre como usar o Microsoft AutoUpdate for Mac, consulte [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Frequentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

**Orientação de detecção e implantação:**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o [Artigo 961747 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Microsoft** **Baseline** **Security** **Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).

**SystemCenter** **Configuration** **Manager**

O gerenciamento de atualizações de software do System Center Configuration Manager simplifica a complexa tarefa de fornecer e gerenciar atualizações a sistemas de TI pela empresa. Com o System Center Configuration Manager, os administradores de TI podem fornecer atualizações de produtos da Microsoft a uma variedade de dispositivos, inclusive desktops, laptops, servidores e dispositivos móveis.

A avaliação automatizada de vulnerabilidade no System Center Configuration Manager detecta as necessidades de atualizações e relatórios com relação a ações recomendadas. O gerenciamento de atualizações de software no System Center Configuration Manager é integrado ao Microsoft Windows Software Update Services (WSUS), uma infraestrutura de atualização testada quanto à confiabilidade, que é familiar aos administradores de TI do mundo todo. Para obter mais informações sobre como os administradores podem usar o System Center Configuration Manager para implantar atualizações, consulte [Gerenciamento de atualizações de software](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Para obter mais informações sobre o System Center Configuration Manager, acesse: [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários.

**Observação** O System Management Server 2003 está fora de suporte principal desde 12 de janeiro de 2010. Para obter mais informações sobre ciclos de vida de produtos, acesse [Ciclo de Vida do Suporte Microsoft](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). A próxima versão do SMS, System Center Configuration Manager, já está disponível; consulte a seção anterior: **System Center** **Configuration** **Manager**.

Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, consulte [Cenários e procedimentos para o Microsoft Systems Management Server 2003: Distribuição de software e Gerenciamento de patches](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Para obter informações sobre o SMS, acesse: [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) para instalar essas atualizações.

**Avaliador de compatibilidade com atualizações e Kit de ferramentas de compatibilidade de aplicativos**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet.microsoft.com/library/cc749197) incluídos no [Kit de ferramentas de compatibilidade de aplicativos](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

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

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://go.microsoft.com/fwlink/?linkid=215201).

#### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://www.microsoft.com/downloads/search.aspx?displaylang=pt-br). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [Artigo 913086 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (em inglês).

#### Agradecimentos

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) às pessoas mencionadas abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   GWSlabs, que trabalha na [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar um problema descrito no boletim MS12-052
-   Derek Soeder, que trabalha com o [programa Beyond Security's SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html), por relatar um problema descrito no boletim MS12-052
-   Sung-ting Tsai e Ming-Chieh Pan, da [Trend Micro](http://www.trendmicro.com/) para relatar um problema descrito no MS12-052
-   Cris Neckar, da [Equipe de segurança do Google Chrome](http://chrome.google.com/), por relatar um problema descrito no boletim MS12-052
-   Edward Torkington, do NCC Group, por relatar um problema descrito no boletim MS12-053
-   Yamata Li, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar quatro problemas descritos no boletim MS12-054
-   [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   , da
-   [Google Inc](http://www.google.com/)
-   ., por relatar um problema descrito no boletim MS12-055
-   Cris Neckar, da [Equipe de segurança do Google Chrome](http://chrome.google.com/), por relatar um problema descrito no boletim MS12-056
-   [Andrei Costin](http://www.andreicostin.com)
-   por relatar um problema descrito no boletim MS12-057
-   Wil Dorman, da [CERT/CC](http://www.cert.org/), por trabalhar conosco em 13 problemas descritos no boletim MS12-058
-   Alexander Gavrun, que trabalha com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) da [TippingPoint](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS12-059

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617,aspx)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (14 de agosto de 2012): Resumo de boletins publicado.
-   V2.0 (9 de outubro de 2012): Resumo do boletim revisado para coincidir com o novo lançamento dos pacotes de atualização no MS12-053, no MS12-054, no MS12-055 e no MS12-058. Os clientes devem aplicar os pacotes de atualização relançados para evitar problemas nos certificados digitais descritos no Comunicado de segurança da Microsoft 2749655. Consulte os boletins para obter mais informações.
-   V3.0 (11 de dezembro de 2012): No MS12-057, atualizações KB2553260 e KB2589322 substituídas por KB2687501 e KB2687510, respectivamente, para todas as edições afetadas do Microsoft Office 2010. No MS12-059, atualização KB2597171 substituída por KB2687508 para todas as edições afetadas do Microsoft Visio 2010. No MS12-060, atualização KB2687323 substituída por KB2726929 nos controles comuns do Windows em todas as variantes afetadas do Microsoft Office 2003, Microsoft Office 2003 Web Components e Microsoft SQL Server 2005.

*Built at 2014-04-18T01:50:00Z-07:00*
