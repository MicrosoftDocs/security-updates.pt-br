---
TOCTitle: 'MS13-FEB'
Title: Resumo do Boletim de Segurança da Microsoft de fevereiro 2013
ms:assetid: 'ms13-feb'
ms:contentKeyID: 61233698
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms13-feb(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de fevereiro 2013
=============================================================

Publicado: terça-feira, 12 de fevereiro de 2013 | Atualizado: quarta-feira, 13 de fevereiro de 2013

**Versão:** 1.2

Este resumo de boletins lista os boletins de segurança lançados em fevereiro de 2013.

Com o lançamento dos boletins de fevereiro de 2013, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 7 de fevereiro de 2013. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 13 de fevereiro de 2013, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de fevereiro](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538626&culture=en-us). Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538626&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (2792100)  <br />
<br />
</strong>Esta atualização de segurança elimina 13 vulnerabilidades relatadas em particular no Internet Explorer. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275837">MS13-010</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Vector Markup Language pode permitir a execução remota de código (2797052)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade reportada em particular na implementação do VML (Vector Markup Language) no Windows. A vulnerabilidade pode permitir a execução remota de código caso um usuário tenha exibido uma página da Web especialmente criada usando o Internet Explorer. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271307">MS13-011</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade na descompactação de mídia pode permitir a execução remota de código (2780091)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente no Microsoft Windows. A vulnerabilidade pode permitir execução remota de código se um usuário abrir um arquivo de mídia especialmente criado (tal como um arquivo .mpg), abrir um documento do Microsoft Office (tal como um arquivo .ppt) que contenha um arquivo de mídia incorporado especialmente criado ou receber conteúdo de fluxo especialmente criado. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279801">MS13-012</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Exchange Server podem permitir a execução remota de</strong> <strong>código (2809279)  <br />
<br />
</strong>Esta atualização de segurança elimina vulnerabilidades divulgadas publicamente no Microsoft Exchange Server. A vulnerabilidade mais severa está na Visualização de documentos do Microsoft Exchange Server WebReady e podem permitir a execução remota de código no contexto de segurança do serviço de transcodificação no Exchange Server se um usuário visualizar um arquivo especialmente criado usando o Outlook Web App (OWA). O serviço de transcodificação no Exchange usado para Visualização de documentos WebReady é executado na conta LocalService. A conta LocalService tem privilégios mínimos no computador local e apresenta credenciais anônimas na rede.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279005">MS13-020</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade na automação OLE pode permitir a execução remota de código (2802968)  <br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade reportada em particular no Microsoft Windows Object Linking and Embedding (OLE) Automation. A vulnerabilidade pode permitir a execução remota de código se o usuário abrir um arquivo especialmente criado. O invasor que explorar com êxito a vulnerabilidade poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272434">MS13-013</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades na análise do FAST Search</strong> Server 2010 para SharePoint podem permitir execução <strong>remota de</strong> <strong>código (2784242)  <br />
<br />
</strong>Esta atualização de segurança resolve vulnerabilidades divulgadas publicamente no Microsoft FAST Search Server 2010 for SharePoint. As vulnerabilidades podem permitir execução remota de código no contexto de segurança da conta do usuário com um token restrito. O FAST Search Server for SharePoint somente será afetado pelo problema se o Advanced Filter Pack estiver habilitado. Por padrão, o Advanced Filter Pack está desabilitado.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office, <br />
Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276948">MS13-014</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no NFS Server pode permitir a negação de serviço (2790978)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a negação de serviço se um invasor tentar uma operação de arquivo em um compartilhamento somente leitura. O invasor que explorar com êxito esta vulnerabilidade pode fazer com que o sistema afetado pare de responder e reinicie. A vulnerabilidade somente afeta servidores Windows com a função NFS habilitada.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a>  <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275736">MS13-015</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no .NET Framework pode permitir a elevação de privilégio (2800277)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidaderelatada em particular no .NET Framework. A vulnerabilidade pode permitir elevação de privilégios se um usuário visualizar uma página da Web especialmente criada usando um navegador da Web que execute aplicativos de navegador XAML (XBAPs). A vulnerabilidade também pode ser usada pelos aplicativos Windows .NET para anular as restrições do CAS (Code Access Security). O invasor que explorar com êxito a vulnerabilidade poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no driver do modo do kernel do Windowspode permitir a elevação de privilégio (2778344)</strong> <br />
Esta atualização de segurança elimina 30 vulnerabilidades relatadas em particular no Microsoft Windows. As vulnerabilidades podem permitir elevação de privilégio se um invasor faz logon no sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essas vulnerabilidades.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a>  <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no kernel do Windows podem permitir a elevação de privilégio (2799494)</strong> <br />
Esta atualização de segurança resolve três vulnerabilidades relatadas em particular em todas as versões com suporte do Microsoft Windows. As vulnerabilidades podem permitir elevação de privilégio se um invasor faz logon no sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essas vulnerabilidades.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278912">MS13-018</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no TCP/IP pode permitir negação de serviço (2790655)  <br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a negação de serviço se um invasor não autenticado enviar um pacote de conclusão de conexão especialmente criado ao servidor.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a>  <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278896">MS13-019</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Windows Client/Server Runtime Subsystem (CSRSS) pode permitir elevação de privilégio (2790113)  <br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um invasor fizer logon em um sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a>  <br />
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de codificação de caracteres Shift JIS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0015">CVE-2013-0015</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação de informações.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de SetCapture do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0018">CVE-2013-0018</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de COmWindowProxy do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0019">CVE-2013-0019</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de CMarkup do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0020">CVE-2013-0020</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de vtable do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0021">CVE-2013-0021</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de LsGetTrailInfo do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0022">CVE-2013-0022</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de CDispNode do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0023">CVE-2013-0023</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de pasteHTML do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0024">CVE-2013-0024</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de SLayoutRun do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0025">CVE-2013-0025</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de InsertElement do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0026">CVE-2013-0026</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de CPasteCommand do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0027">CVE-2013-0027</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de CObjectElement do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0028">CVE-2013-0028</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso de CHTML do Internet Explorer depois da liberação</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0029">CVE-2013-0029</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275837">MS13-010</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória de VML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0030">CVE-2013-0030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">A Microsoft está ciente de que esta vulnerabilidade está sendo usada como uma vulnerabilidade de divulgação não autorizada de informações em ataques limitados e direcionados.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271307">MS13-011</a></td>
<td style="border:1px solid black;">Vulnerabilidade de descompactação de mídia</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0077">CVE-2013-0077</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279801">MS13-012</a></td>
<td style="border:1px solid black;">O Oracle Outside In contém várias vulnerabilidades que podem ser exploradas</td>
<td style="border:1px solid black;">Várias\*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">\*Várias vulnerabilidades, consulte o boletim MS13-012 para obter detalhes.<br />
<br />
Estas vulnerabilidades foram divulgadas publicamente.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272434">MS13-013</a></td>
<td style="border:1px solid black;">O Oracle Outside In contém várias vulnerabilidades que podem ser exploradas</td>
<td style="border:1px solid black;">Várias\*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">\*Várias vulnerabilidades, consulte o boletim MS13-013 para obter detalhes.<br />
<br />
Estas vulnerabilidades foram divulgadas publicamente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276948">MS13-014</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desreferência NULL</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1281">CVE-2013-1281</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275736">MS13-015</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de retorno de chamada do WinForms</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0073">CVE-2013-0073</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1248">CVE-2013-1248</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta é uma medida de proteção abrangente nos softwares mais recentes.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1249">CVE-2013-1249</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta é uma medida de proteção abrangente nos softwares mais recentes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1250">CVE-2013-1250</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1251">CVE-2013-1251</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1252">CVE-2013-1252</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1253">CVE-2013-1253</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1254">CVE-2013-1254</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1255">CVE-2013-1255</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1256">CVE-2013-1256</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1257">CVE-2013-1257</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1258">CVE-2013-1258</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1259">CVE-2013-1259</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1260">CVE-2013-1260</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1261">CVE-2013-1261</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1262">CVE-2013-1262</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1263">CVE-2013-1263</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1264">CVE-2013-1264</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1265">CVE-2013-1265</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1266">CVE-2013-1266</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1267">CVE-2013-1267</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1268">CVE-2013-1268</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1269">CVE-2013-1269</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1270">CVE-2013-1270</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1271">CVE-2013-1271</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1272">CVE-2013-1272</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1273">CVE-2013-1273</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1274">CVE-2013-1274</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1275">CVE-2013-1275</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1276">CVE-2013-1276</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1277">CVE-2013-1277</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do kernel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1278">CVE-2013-1278</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">Vulnerabilidade de condição forçada do kernel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1279">CVE-2013-1279</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">Vulnerabilidade de contagem de referência do kernel do Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1280">CVE-2013-1280</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278912">MS13-018</a></td>
<td style="border:1px solid black;">Vulnerabilidade de TCP FIN WAIT</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0075">CVE-2013-0075</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278896">MS13-019</a></td>
<td style="border:1px solid black;">Vulnerabilidade de contagem de referências</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0076">CVE-2013-0076</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279005">MS13-020</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código de automação de OLE</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1313">CVE-2013-1313</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
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
<th colspan="11">
Windows XP (site em inglês)  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
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
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9bf087e7-4487-48bf-84e9-04b816411a0f)   
(KB2792100)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4501ef62-7d06-49b7-af86-c84e399e6275)  
(KB2792100)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2ab64eac-8ecf-4178-9a01-5f10fc2f049e)  
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=daed0c2e-bd9a-4685-a5f9-1c01f7fdeccf)   
(KB2797052)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fd693211-bcc8-4267-9aa1-86bac45e25bf)  
(KB2797052)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e8924d23-f6e2-41bf-9542-f8991d084db9)  
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=95f5acea-32a0-42a5-a14d-837edf313984)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3a8ddbab-5999-48b7-9de8-423954f345b6)  
(KB2802968)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cdaa7282-c354-4d70-938a-a025631205a2)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9100bf70-8723-4635-9b78-f7c3048a950f)  
(KB2799494)    
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=c42347dd-5ec8-4760-a685-2cd7b6bb7bb2)   
(KB2792100)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6513176c-e9cb-4863-a228-5bc369135996)  
(KB2792100)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=25e15457-ffd2-4466-aff9-1d0830e967d7)  
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=dd9383b9-a6df-44a7-bea9-8f7d088bc488)   
(KB2797052)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b042e717-bf4e-44a1-a1ba-6359bf551e8e)  
(KB2797052)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c8618c96-25c0-415b-b147-5713ec5ab5b1)  
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=06ef35a1-f76f-4e99-a8b2-6b086c7e51be)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)   
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f72228df-8379-4bd9-b446-cb9505e9d228)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a945336-b037-4ee6-9ea2-dfb885747b97)  
(KB2799494)    
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
<th colspan="11">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
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
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=35b58c7a-aae3-4445-957a-42ee708d77a5)   
(KB2792100)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3ee73b80-b8f6-4843-afba-41c7b55faf17)  
(KB2792100)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d67754e2-7ebd-484d-a008-ed8719e0c72d)  
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9b96ebfc-93e9-41bb-81f9-35c433ca5479)   
(KB2797052)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b902617d-1f35-4b17-9a44-235c0d3c27d2)  
(KB2797052)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=47ca5d22-b957-4ac9-91e9-c440b0614728)  
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=e3b0b928-0f76-4b51-871a-aeda2ee3b7d5)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8daebdb5-eba2-4685-b781-ead5c2185548)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c005c0a0-4025-4a07-a76d-c57ed5afbd68)  
(KB2799494)    
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=075de724-b996-413f-8ff3-74f435d94b9b)   
(KB2792100)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a90d6861-7ff6-4501-9200-f72b5a9f1817)  
(KB2792100)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=319a7a93-c03e-4c0b-a5c4-6a4f379d781e)  
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b3ca28b1-9d3c-4df5-b8d7-f31d70f6e714)   
(KB2797052)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e13c9366-9cb6-4e62-bf6c-a09fe7842463)  
(KB2797052)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=80aab9c7-4511-4d44-b570-c77cdb50e542)  
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=493377a4-4ce2-4dd9-ba84-090466248669)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e7d03ef2-517b-4442-a968-5aaa300dd2ba)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dc004424-61f9-49ed-9cb3-b89ed9e98aef)  
(KB2799494)    
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=92ce1fa1-4b12-4fd5-9a02-21fc9b119fb9)   
(KB2792100)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5965ce09-c5d7-4072-bad3-df46f9b76478)  
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=63791740-00e2-4569-967e-36086efe6ca6)   
(KB2797052)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d1a9b2b2-191c-4ffe-9c8a-8ef641a45eb7)  
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=8e9a09fd-f360-4471-ac89-481dc2935cec)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2a3039a4-9b46-4db8-a539-07d52bbf1b92)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=3cad66f1-6651-4948-9579-9df050fdaa1b)  
(KB2799494)    
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
<th colspan="11">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
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
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=eea43429-2691-4a31-a640-d74035145d2d)  
(KB2792100)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5c195229-8e63-4fff-a304-13c13b2fa132)  
(KB2792100)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7f7ce868-28ce-497e-882f-3abfdd9b89e8)   
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4f946407-cd81-48b5-a279-1ab81388b70b)  
(KB2797052)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e0cfc24f-293c-4817-a69c-f9cfd514e1c1)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=4fab0417-5c9a-4e5d-864d-b1b3bee6fc89)   
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=d730eacf-e30a-45aa-89da-dfec5e87906a)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)   
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)   
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0ff0475c-cc1b-4886-971e-1a71e6b311c3)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4de1249f-012e-47cb-ad08-4fd5bddb0879)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=80b766e7-3b7f-4d04-9a80-71864a13df8c)  
(KB2790655)    
(Moderada)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=308d99ff-7575-4d70-958f-0d57fd6bffab)  
(KB2792100)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d9d4987e-95ad-4246-a52b-7ac859a40e67)  
(KB2792100)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=74b370c0-29f5-4acb-a3cd-bd2c2b708bb7)   
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6ffb3215-1c90-4eb2-9143-0866efc98374)  
(KB2797052)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=649dbf4e-654b-48a2-bd35-2df7f34fbb56)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=44fbe00c-eeb4-4a80-a934-7ce58c02d6ec)   
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=4cd6b10c-b310-4aee-bbca-f23049c14455)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)   
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)   
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e5043a08-a9e4-422b-8455-80a5091d38b9)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=448ac43a-0a6f-4049-be2b-c853b5dbfab3)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=92bad797-5b66-422c-a096-8070d02bb8b2)  
(KB2790655)    
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="11">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
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
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=71c805ed-a68b-4d3e-97ca-922557cfbf67)  
(KB2792100)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=775ea105-4a71-4b7b-9dc0-50f1eecab96d)  
(KB2792100)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ccdf8abc-9657-4aff-8d73-4824a558c168)   
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d432acb3-10a0-4f4c-a793-381aedd4bdd1)  
(KB2797052)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b91ce04a-a464-4388-9386-54dd2815b8dd)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=58f0810c-f253-4740-ac9f-75b8a4506b06)   
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=86cc3b51-818a-49a6-abab-488ac316e021)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)   
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)   
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=850e319f-dd6e-4480-86c3-a5129f084817)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d7a74c8-de4b-4bcb-8b3f-581858d0776b)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c24aa6f3-82a5-4b1f-adc8-4aece948161c)  
(KB2790655)    
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=de1b96b7-a5ac-4a39-9808-c00c6b1a4325)  
(KB2792100)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e5775802-e529-4894-b1cf-2839948706c2)  
(KB2792100)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=51df1e78-f014-4492-8a3d-83b3c821458b)   
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=152f90b3-efae-42e6-a845-59052383a8a0)  
(KB2797052)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=304ac41e-b4e5-4bf8-94d2-f2bd9a07bcff)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7b85336a-d3f7-4077-b6eb-55b3042f5335)   
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=fe239f9b-d986-4828-a01d-8abd494037ec)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)   
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)   
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8978769b-447b-4b01-848a-cbcdf692f17a)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c9fbb7cc-c33b-4af9-8416-9d16015e79c1)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2738fbe4-2163-4e77-82e6-208a7a08a70c)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=61c1964f-9307-4128-9470-bcb20e07856b)  
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1a2af9dc-e9a7-477e-9943-8132eb7fea81)  
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=4b3e48e3-0dbe-449b-9bca-0ba8bbdcbab0)   
(KB2780091)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)   
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f84e24c-43f4-4851-932c-8849171b2505)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f3e18038-b8a1-4eba-9542-8396903a3709)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c269c175-f47c-456a-9360-f38bbdfd7ed0)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="11">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
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
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4df9414b-02da-4254-ab29-5091151e2900)  
(KB2792100)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b21bd7b3-2eb8-433a-b6c2-8243c5128038)   
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d7d64177-deec-4fd3-9716-b7816fe3c623)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=04a101c6-d553-426f-b3cd-412eefeec580)   
(KB2797052)  
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
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)    
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=631adede-ba0f-461f-85e1-82b60a7efec1)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=912ac2e1-e737-43fb-acc8-a01a918a8475)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=cb4270c4-cec5-49e0-a56b-97539d6352a0)  
(KB2790655)    
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=d4d02ef9-b0a4-46a3-ad92-7508aa26ad3b)  
(KB2790113)    
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4df9414b-02da-4254-ab29-5091151e2900)  
(KB2792100)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b21bd7b3-2eb8-433a-b6c2-8243c5128038)   
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d7d64177-deec-4fd3-9716-b7816fe3c623)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=04a101c6-d553-426f-b3cd-412eefeec580)   
(KB2797052)  
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
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)    
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=631adede-ba0f-461f-85e1-82b60a7efec1)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=912ac2e1-e737-43fb-acc8-a01a918a8475)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=cb4270c4-cec5-49e0-a56b-97539d6352a0)  
(KB2790655)    
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d4d02ef9-b0a4-46a3-ad92-7508aa26ad3b)  
(KB2790113)    
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6ef9cbf9-d131-420d-b566-6b0f94f2e1c1)  
(KB2792100)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=4b2402ff-035a-47c4-b982-00d428eab379)   
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d503795a-b1a3-48dc-b1e6-27628aeb150a)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=36eb59be-6703-40c0-b01c-0fffb1456719)   
(KB2797052)  
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
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)    
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=8dab3aca-fde1-4bd9-b82a-e4805a2e8d39)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=0d1601cc-fb76-4276-bf0b-a46b7f8055ae)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=5d93cb19-7854-4b49-9743-8d6a11be2dd6)  
(KB2790655)    
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=77277398-c5b4-4ba4-8425-465710b0bef2)  
(KB2790113)    
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6ef9cbf9-d131-420d-b566-6b0f94f2e1c1)  
(KB2792100)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=4b2402ff-035a-47c4-b982-00d428eab379)   
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d503795a-b1a3-48dc-b1e6-27628aeb150a)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=36eb59be-6703-40c0-b01c-0fffb1456719)   
(KB2797052)  
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
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)    
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=8dab3aca-fde1-4bd9-b82a-e4805a2e8d39)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=0d1601cc-fb76-4276-bf0b-a46b7f8055ae)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=5d93cb19-7854-4b49-9743-8d6a11be2dd6)  
(KB2790655)    
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=77277398-c5b4-4ba4-8425-465710b0bef2)  
(KB2790113)    
(Importante)
</td>
</tr>
<tr>
<th colspan="11">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
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
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e7b455a3-6a44-430c-a7d1-30c03ef7f141)  
(KB2792100)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7e9d97f2-c006-4e5a-bc80-10450069b8c5)   
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a36109b-f1e2-4cde-9ede-9f7449c5412c)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=be2fd20a-4c37-47a6-a322-e16acd99db2c)   
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4)  
(KB2790978)   
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)    
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab)  
(KB2790113)    
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e7b455a3-6a44-430c-a7d1-30c03ef7f141)  
(KB2792100)  
(Moderada)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7e9d97f2-c006-4e5a-bc80-10450069b8c5)   
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a36109b-f1e2-4cde-9ede-9f7449c5412c)  
(KB2797052)  
(Crítica)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=be2fd20a-4c37-47a6-a322-e16acd99db2c)   
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4)  
(KB2790978)    
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)    
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)   
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab)  
(KB2790113)    
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c1eb941e-833d-46f0-bf65-d9701d67bc20)  
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c2e1c1b3-5b75-47cf-91d5-82d413b358e6)  
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=8e37196c-2f43-457d-8d87-336d8775c0bf)  
(KB2790978)    
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)    
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=99320f36-1481-446c-bc3e-d33fcfd1f2c1)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9f0b132a-8616-49cd-8927-393f35d0cf21)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=e1be5dea-dd13-42b5-a37f-4bcd828cc65f)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9fbc37dd-53ec-4de1-b1c1-9761a8f83ab8)  
(KB2790113)    
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c1eb941e-833d-46f0-bf65-d9701d67bc20)  
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c2e1c1b3-5b75-47cf-91d5-82d413b358e6)  
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=8e37196c-2f43-457d-8d87-336d8775c0bf)  
(KB2790978)    
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)    
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=99320f36-1481-446c-bc3e-d33fcfd1f2c1)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9f0b132a-8616-49cd-8927-393f35d0cf21)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=e1be5dea-dd13-42b5-a37f-4bcd828cc65f)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9fbc37dd-53ec-4de1-b1c1-9761a8f83ab8)  
(KB2790113)    
(Importante)
</td>
</tr>
<tr>
<th colspan="11">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=7966de38-c6a6-4137-8b7e-8ccd3306521a)   
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=0389b515-59bf-4733-aab4-ffb822efdbea)   
(KB2797052)  
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
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)  
(KB2789650)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)  
(KB2789649)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=d5395864-1822-4151-a10c-f6a036f8853f)  
(KB2778344)    
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=5b74e5b3-7b8d-4669-b403-c776e70bf072)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=e7739ba6-9c62-4180-a095-47fdb6c741e9)  
(KB2790655)    
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=d6720d21-269b-4605-b95e-573bc327afd9)   
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=c1859853-d43f-4497-b212-e6a4daa43485)   
(KB2797052)  
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
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)  
(KB2789650)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)  
(KB2789649)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=79aaaa3a-747a-4320-9fd2-5f4a6de3d13c)  
(KB2778344)    
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=a41a2b38-5e5c-48bc-8727-e19402519f12)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=dd2042b8-c784-4dfc-8fca-61905693cda5)  
(KB2790655)    
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="11">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=8e3fdcd0-ab75-4500-aac7-7ecb4f39fca7)   
(KB2792100)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=3b39813e-5ee2-412e-b1f1-a16617a70f43)   
(KB2797052)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=b284296a-1db5-47dc-af2c-bf55d0ad09e6)  
(KB2790978)   
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)  
(KB2789650)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)  
(KB2789649)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=aac38d33-fad6-4060-bad4-61cf7c059af9)  
(KB2778344)    
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=4e427f56-436e-43d0-b4f8-eee8427b3741)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f74a104d-4749-4dd5-b144-2e4ce9c284a2)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="11">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>   
(KB2792100)  
(Crítica)
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>   
(KB2797052)  
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
Windows RT<sup>[1]</sup>
(KB2778344)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2799494)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2790655)   
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="11">
Opção de instalação de núcleo de servidor
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=850e319f-dd6e-4480-86c3-a5129f084817) (instalação do núcleo do servidor)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d7a74c8-de4b-4bcb-8b3f-581858d0776b) (instalação do núcleo do servidor)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c24aa6f3-82a5-4b1f-adc8-4aece948161c) (instalação do núcleo do servidor)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8978769b-447b-4b01-848a-cbcdf692f17a) (instalação do núcleo do servidor)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c9fbb7cc-c33b-4af9-8416-9d16015e79c1) (instalação do núcleo do servidor)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2738fbe4-2163-4e77-82e6-208a7a08a70c) (instalação do núcleo do servidor)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4) (instalação do núcleo do servidor)  
(KB2790978)    
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9) (Instalação do núcleo de servidor)  
(KB2789644)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036) (instalação do núcleo do servidor)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb) (instalação do núcleo do servidor)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01) (instalação do núcleo do servidor)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab) (instalação do núcleo do servidor)  
(KB2790113)    
(Importante)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4) (instalação do núcleo do servidor)  
(KB2790978)    
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062) (Instalação do núcleo de servidor)  
(KB2789645)    
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(Instalação de núcleo de servidor) (KB2789642)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139) (Instalação de núcleo de servidor)  
(KB2789648)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036) (instalação do núcleo do servidor)  
(KB2778344)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb) (instalação do núcleo do servidor)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01) (instalação do núcleo do servidor)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab) (instalação do núcleo do servidor)  
(KB2790113)    
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=b284296a-1db5-47dc-af2c-bf55d0ad09e6) (instalação Server Core)  
(KB2790978)   
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014) (Instalação do núcleo de servidor)  
(KB2789650)    
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0) (Instalação de núcleo de servidor)  
(KB2789649)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=aac38d33-fad6-4060-bad4-61cf7c059af9) (instalação Server Core)  
(KB2778344)    
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=4e427f56-436e-43d0-b4f8-eee8427b3741) (instalação Server Core)  
(KB2799494)    
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f74a104d-4749-4dd5-b144-2e4ce9c284a2) (instalação Server Core)  
(KB2790655)    
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**Observações para MS13-009, MS13-010, MS13-017 e MS13-018**

<sup>[1]</sup>As atualizações de segurança do Windows RT são fornecidas pelo [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

**Observações para MS13-015**

<sup>[1]</sup>**.NET Framework 4 e .NET Framework 4 Client Profile afetados.** Os pacotes redistribuíveis do .Net Framework versão 4 estão disponíveis em dois perfis: .NET Framework 4 e .NET Framework 4 Client Profile. O .NET Framework 4 Client Profile é um subconjunto do .NET Framework 4. A vulnerabilidade abordada nesta atualização afeta tanto o .NET Framework 4 quanto o .NET Framework 4 Client Profile. Para obter mais informações, consulte o artigo de MSDN, [Instalando o .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

**Observações para MS13-016**

<sup>[1]</sup>As atualizações de segurança do Windows RT são fornecidas pelo [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

<sup>[2]</sup>As classificações de gravidade não se aplicam a esta atualização para o software especificado. No entanto, como medida de defesa abrangente, a Microsoft recomenda que clientes deste software apliquem esta atualização de segurança.

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
[**MS13-012**](http://go.microsoft.com/fwlink/?linkid=279801)
</td>
<td style="border:1px solid black;">
[**MS13-013**](http://go.microsoft.com/fwlink/?linkid=272434)
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
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=316a1aff-b72d-4d96-8ee5-bd86b0e29e6f)   
(KB2788321)   
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=498e7612-73b5-4e28-99a4-b3157ac69932)   
(KB2746164)   
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft FAST Search Server 2010 for SharePoint
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-012**](http://go.microsoft.com/fwlink/?linkid=279801)
</td>
<td style="border:1px solid black;">
[**MS13-013**](http://go.microsoft.com/fwlink/?linkid=272434)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft FAST Search Server 2010 for SharePoint Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Advanced Filter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=0ae86754-69a8-4c82-855c-2ee2b7887fa5)<sup>[1]</sup>   
(KB2553234)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS13-013**

<sup>[1]</sup>Esta atualização está disponível somente no Centro de Download da Microsoft.

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

-   Masato Kinugawa por relatar um problema descrito no boletim MS13-009
-   [Omair](http://krash.in/)
-   , que trabalha na
-   [Zero Day Initiative da](http://www.zerodayinitiative.com/)
-   [HP](http://www.hpenterprisesecurity.com/products)
-   , por relatar um problema descrito no boletim MS13-009
-   SkyLined, que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar um problema descrito no boletim MS13-009
-   Arthur Gerkis, que trabalha na Exodus Intelligence, por relatar um problema descrito no boletim MS13-009
-   Stephen Fewer da [Harmony Security](http://www.harmonysecurity.com), que trabalha com[Zero Day Initiative](http://www.hpenterprisesecurity.com/products) da [HP,](http://www.zerodayinitiative.com/) por relatar dois problemas descritos no boletim MS13-009.
-   [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com)
-   , que trabalha na
-   [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   da
-   [HP](http://www.hpenterprisesecurity.com/products)
-   , por relatar um problema descrito no boletim MS13-009
-   Tencent PC Manager por relatar um problema descrito no boletim MS13-009
-   Arthus Gerkis, que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar um problema descrito no boletim MS13-009
-   Um pesquisador anônimo, que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar um problema descrito no boletim MS13-009
-   Scott Bell, da [Security-Assessment.com](http://www.security-assessment.com), por relatar dois problemas descritos no boletim MS13-009
-   Jose A Vazquez, da Yenteasy Security Research, que trabalha com a Exodus Intelligence, por relatar um problema descrito no boletim MS13-009
-   Jose A Vazquez, da Yenteasy Security Research, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar um problema descrito no boletim MS13-009
-   Mark Yason, da IBM X-Force, por relatar um problema descrito no MS13-009
-   Ollie Whitehouse, do [NCC Group,](http://www.nccgroup.com/)por trabalhar conosco em alterações adicionais de proteção abrangente incluídas no boletim MS13-009
-   [Tencent Security Team](http://security.tencent.com/)
-   por relatar um problema descrito no boletim MS13-011
-   James Forshaw, da [Context Information Security](http://www.contextis.com/), por relatar um problema descrito no boletim MS13-015
-   [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   da
-   [Google Inc](http://www.google.com)
-   e
-   [Tencent Security Team](http://security.tencent.com/)
-   por relatarem dois problemas descritos no boletim MS13-016
-   [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   , da
-   [Google Inc](http://www.google.com/)
-   , por relatar 25 problemas descritos no boletim MS13-016
-   [Gynvael Coldwind](http://gynvael.coldwind.pl/)
-   e
-   [Mateusz “j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   da
-   [Google Inc](http://www.google.com)
-   , por relatarem três problemas descritos no boletim MS13-016
-   [Gynvael Coldwind](http://gynvael.coldwind.pl/)
-   e
-   [Mateusz “j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   da
-   [Google Inc](http://www.google.com)
-   , por relatarem dois problemas descritos no boletim MS13-017
-   Max DeLiso, por trabalhar conosco em um problema descrito no boletim MS13-019.
-   Um pesquisador anônimo, que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar um problema descrito no boletim MS13-020

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617,aspx)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (12 de fevereiro de 2013): Resumo de boletins publicado.
-   V1.1 (12 de fevereiro de 2013): No boletim MS13-009, foi corrigida a Avaliação de exploração do último lançamento de software no **Índice de exploração** para CVE-2013-0022.
-   V1.2 (13 de fevereiro de 2013): No boletim MS13-014, foi corrigida a Avaliação de exploração do último lançamento de software no **Índice de exploração** para CVE-2013-1281.

*Built at 2014-04-18T01:50:00Z-07:00*
