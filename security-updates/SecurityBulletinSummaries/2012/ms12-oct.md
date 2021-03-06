---
TOCTitle: 'MS12-OCT'
Title: Resumo do Boletim de Segurança da Microsoft de outubro 2012
ms:assetid: 'ms12-oct'
ms:contentKeyID: 61233693
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms12-oct(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de outubro 2012
===========================================================

Publicado: terça-feira, 9 de outubro de 2012 | Atualizado: quarta-feira, 10 de outubro de 2012

**Versão:** 1.1

Este resumo de boletins lista os boletins de segurança lançados em outubro de 2012.

Com o lançamento dos boletins de outubro de 2012, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 4 de outubro de 2012. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte Notificação antecipada dos boletins de segurança da Microsoft.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as Notificações de segurança técnica da Microsoft.

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 10 de outubro de 2012, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de outubro](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522558&culture=en-us). Depois dessa data, este webcast estará disponível sob demanda.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-064">MS12-064</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Word podem permitir a execução remota de código (2742319)</strong> <br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft Office. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário abrir ou exibir um arquivo RTF criado especialmente. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;">Crítica <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-065">MS12-065</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Works pode permitir a execução remota de código (2754670)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Works. A vulnerabilidade pode permitir a execução remota de código se um usuário abrir um arquivo do Microsoft Word especialmente criado usando o Microsoft Works. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;">Importante <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-066">MS12-066</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade de limpeza de HTML pode permitir a elevação de privilégios (2741517)</strong> <br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade publicamente divulgada no Microsoft Office, Plataformas de Comunicações Microsoft, softwares de servidor da Microsoft e Microsoft Office Web Apps. A vulnerabilidade pode permitir a elevação de privilégios se um invasor enviar conteúdo especialmente criado para um usuário.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software,<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-067">MS12-067</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades na análise do FAST Search Server 2010 for SharePoint podem permitir execução remota de código (2742321)</strong> <br />
<br />
Esta atualização de segurança resolve vulnerabilidades divulgadas publicamente no Microsoft FAST Search Server 2010 for SharePoint. As vulnerabilidades podem permitir execução remota de código no contexto de segurança da conta do usuário com um token restrito. O FAST Search Server for SharePoint somente será afetado pelo problema se o Advanced Filter Pack estiver habilitado. Por padrão, o Advanced Filter Pack está desabilitado.</td>
<td style="border:1px solid black;">Importante <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-068">MS12-068</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Kernel do Windows pode permitir a elevação de privilégio (2724197)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular em todas as edições com suporte do Microsoft Windows, exceto Windows 8 e Windows Server 2012. Esta atualização de segurança é classificada como Importante para todas as edições com suporte do Windows XP, Windows Server 2003, Windows Vista, Windows Server 2008, Windows 7 e Windows Server 2008 R2.<br />
<br />
A vulnerabilidade pode permitir elevação de privilégio se um invasor faz logon no sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-069">MS12-069</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Kerberos pode permitir a negação de serviço (2743555)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade poderá permitir negação de serviço se um invasor remoto enviar uma solicitação de sessão especialmente criada ao servidor Kerberos. As práticas recomendadas para firewall e as configurações de firewall padrão podem ajudar a proteger as redes contra ataques com origem externa ao perímetro da empresa. Essas práticas também recomendam que os sistemas conectados à Internet tenham um número mínimo de portas expostas.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-070">MS12-070</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no SQL Server pode permitir a elevação de privilégio</strong> <strong>(2754849)</strong> <br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada em particular no Microsoft SQL Server em sistemas que executam o SQL Server Reporting Services (SSRS). A vulnerabilidade é um scripting entre sites (XSS) que pode permitir elevação de privilégio, possibilitando que um invasor execute comandos arbitrários no site SSRS no contexto do usuário de destino. O invasor pode explorar essa vulnerabilidade enviando um link especialmente criado ao usuário e convencendo-o a clicar no link. O invasor também pode hospedar um site que contém uma página da Web projetada para explorar a vulnerabilidade. Além disso, sites comprometidos e sites que aceitem ou hospedem conteúdo fornecido pelo usuário ou anúncios podem conter conteúdo especialmente criado que pode explorar esta vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
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
<th style="border:1px solid black;" >Avaliação da capacidade de exploração da última versão de software</th>
<th style="border:1px solid black;" >Avaliação da capacidade de exploração de versão mais antiga de software</th>
<th style="border:1px solid black;" >Avaliação do risco de exploração para negação de serviço</th>
<th style="border:1px solid black;" >Principais observações</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-064">MS12-064</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção da seção PAPX do Word</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0182">CVE-2012-0182</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-064">MS12-064</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do listid de arquivo RTF</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2528">CVE-2012-2528</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-065">MS12-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro do Works</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2550">CVE-2012-2550</a></td>
<td style="border:1px solid black;">2 - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-066">MS12-066</a></td>
<td style="border:1px solid black;">Vulnerabilidade de limpeza de HTML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2520">CVE-2012-2520</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">MS12-067</td>
<td style="border:1px solid black;">O Advanced Filter Pack no FAST Search Server 2010 para SharePoint contém várias vulnerabilidades que podem ser exploradas</td>
<td style="border:1px solid black;">O Oracle Outside In contém várias vulnerabilidades que podem ser exploradas</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">*Várias vulnerabilidades, consulte o boletim MS12-067 para obter detalhes.<br />
<br />
Estas vulnerabilidades foram divulgadas publicamente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-068">MS12-068</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de número inteiro de Kernel do Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2529">CVE-2012-2529</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-069">MS12-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desreferência NULL do Kerberos</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2551">CVE-2012-2551</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MS12-070</td>
<td style="border:1px solid black;">Vulnerabilidade do XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2552">CVE-2012-2552</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
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
<th colspan="3">
Windows XP (site em inglês)  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-068)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-069)
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6aa1e4b3-273a-49ff-8086-0d2c16dd14f3)   
(KB2724197)  
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
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3c509cc0-63a1-4cc7-b7f9-cc9f0f12b378)   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-068)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-069)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6c7dd00a-a983-477b-88b1-dc16f1b5e42a)   
(KB2724197)  
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
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eaac4dae-62e6-4020-8b4d-a95e7e0e11f1)   
(KB2724197)  
(Importante)
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
Windows Server 2003 com SP2 para sistemas baseados no Itanium   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-068)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-069)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2   
(KB2724197)  
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
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=731d67dc-e028-42e4-8ef3-454f74835593)   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-068)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-069)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2   
(KB2724197)  
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
Windows Server 2008 para sistemas baseados em x64 Service Pack 2   
(KB2724197)  
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
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-068)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-069)
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
Windows 7 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits   
(KB2743555)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1   
(KB2743555)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64   
(KB2743555)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64   
(KB2743555)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-068)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-069)
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
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64   
(KB2743555)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64   
(KB2743555)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium   
(KB2743555)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium   
(KB2743555)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Opção de instalação de núcleo de servidor
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-068)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-069)
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
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)   
(KB2724197)  
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
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do núcleo do servidor)   
(KB2724197)  
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
Windows Server 2008 R2 para sistemas baseados em x64 (instalação do núcleo do servidor)   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 (instalação do núcleo do servidor)   
(KB2743555)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)   
(KB2724197)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)   
(KB2743555)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft Office Suites e componentes
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-064)
</td>
<td style="border:1px solid black;">
[**MS12-065**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-065)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-066)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e49eadec-0fe1-43ce-9c25-a92aad17d940)   
(KB2687483)  
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
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=be58b650-ee4f-405e-ab3c-c28aca48345b)<sup>[1]</sup>   
(KB2687315)  
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
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=be58b650-ee4f-405e-ab3c-c28aca48345b)<sup>[1]</sup>   
(KB2687315)  
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
Microsoft Office 2010 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 1 (edições de 32 bits)   
(KB2553488)  
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
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 1 (edições de 64 bits)   
(KB2553488)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-064)
</td>
<td style="border:1px solid black;">
[**MS12-065**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-065)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-066)
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
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=1e392ff8-92e9-408d-bb14-1e0a6b4b6c9d)   
(KB2687485)  
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
Pacote de compatibilidade do Microsoft Office Service Pack 2
</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 2   
(KB2687314)  
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
Pacote de compatibilidade do Microsoft Office Service Pack 3
</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3   
(KB2687314)  
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
Microsoft InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0989a9f-3a7a-4343-9dd0-b2d694a0813b)   
(KB2687439)  
(Importante)  
[Microsoft InfoPath 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=29330e1a-6bac-4c54-98ef-b9a831801247)   
(KB2687440)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a0989a9f-3a7a-4343-9dd0-b2d694a0813b)   
(KB2687439)  
(Importante)  
[Microsoft InfoPath 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=29330e1a-6bac-4c54-98ef-b9a831801247)   
(KB2687440)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=724b12b9-84bf-4102-912e-56aa9ee0878c)   
(KB2687436)  
(Importante)  
Microsoft InfoPath 2010 Service Pack 1 (edições de 32 bits)   
(KB2687417)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1 (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=17b36fa3-9964-480a-bff8-b028619c5dfd)   
(KB2687436)  
(Importante)  
Microsoft InfoPath 2010 Service Pack 1 (edições de 64 bits)   
(KB2687417)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=7e48cd96-4b91-4f7b-b8a0-2b88131ba51d)   
(KB2754670)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**Observações para o boletim MS12-064**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

<sup>[1]</sup>Para o Microsoft Office Word 2007, além do pacote de atualização de segurança KB2687315, os clientes também precisam instalar a atualização de segurança para o Pacote de compatibilidade do Microsoft Office (KB2687314) para se protegerem das vulnerabilidades descritas neste boletim.

**Observações para o MS12-066**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-064)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-066)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-067)
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
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2007 Service Pack 2 (coreserver) (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=a8a818bb-67a3-4558-aac1-aaa33c6f4584)<sup>[1]</sup>   
(KB2687405)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2007 Service Pack 3 (coreserver) (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=a8a818bb-67a3-4558-aac1-aaa33c6f4584)<sup>[1]</sup>   
(KB2687405)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2007 Service Pack 2 (coreserver) (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=93f4e385-880a-4edc-9cde-24f38a11a41d)<sup>[1]</sup>   
(KB2687405)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2007 Service Pack 3 (coreserver) (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=93f4e385-880a-4edc-9cde-24f38a11a41d)<sup>[1]</sup>   
(KB2687405)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Serviços de automação do Word   
(KB2598237)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1 (wosrv)](http://www.microsoft.com/downloads/details.aspx?familyid=af3ade8e-349f-4eec-a5c3-c5a70071582d)   
(KB2687435)  
(Importante)  
[Microsoft SharePoint Server 2010 Service Pack 1 (coreserver)](http://www.microsoft.com/downloads/details.aspx?familyid=5518b70b-cac9-4aff-b049-156d3c08b04b)   
(KB2589280)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="4">
Microsoft FAST Search Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-064)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-066)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-067)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft FAST Search Server 2010 for SharePoint
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Advanced Filter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=17909d1f-c679-4a20-b39d-b99f9cc7dbc1)  
(KB2553402)  
(Importante)
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-064)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-066)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-067)
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
Nenhuma
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
[Microsoft Groove Server 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=80552d2c-98f2-4c99-bfc6-e091fd1d51c4)   
(KB2687402)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="4">
Windows SharePoint Services e Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-064)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-066)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-067)
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
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (versão de 32 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (versão de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=e3a31cd4-bba3-4572-ab24-7b1dd0c4c01c)   
(KB2687356)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (versões de 64 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (versões de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=77cab67c-be97-4808-9fb4-4defad563851)   
(KB2687356)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
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
[Microsoft SharePoint Foundation 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=79724c7c-7cdf-44c9-9e25-577104c5004b)   
(KB2687434)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-064)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-066)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-067)
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
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e7a2dd61-36d5-4313-a8dc-15456b275b9c)   
(KB2687401)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e7a2dd61-36d5-4313-a8dc-15456b275b9c)   
(KB2687401)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**Observações para o MS12-064**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

**Observações para o MS12-066**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

<sup>[1]</sup>Para edições com suporte do Microsoft SharePoint Server 2007, além do pacote de atualização de segurança para o Microsoft SharePoint 2007 (KB2687405), os clientes também precisam instalar a atualização de segurança para Microsoft Windows SharePoint Services 3.0 (KB2687356) para ficarem protegidos contra a vulnerabilidade descrita neste boletim.

#### Software e Plataformas do Microsoft Communications

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Communicator
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-066)
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
Microsoft Communicator 2007 R2
</td>
<td style="border:1px solid black;">
Microsoft Communicator 2007 R2   
(KB2726391)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Lync
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-066)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 bits)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 (32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=6ea3afea-baa2-4b74-9747-8051c544ddf7)   
(KB2726382)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 bits)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 (64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=670c20e6-4f26-47b9-b6e0-25f195bf7000)   
(KB2726382)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendee](http://www.microsoft.com/downloads/details.aspx?familyid=7f98cb55-027a-40bf-b539-d8fa38ffcc83)   
(instalação de nível administrativo)  
(KB2726384)  
(Importante)  
Microsoft Lync 2010 Attendee<sup>[1]</sup>   
(instalação de nível usuário)  
(KB2726388)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observações para o MS12-066**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

<sup>[1]</sup>Esta atualização está disponível somente no Centro de Download da Microsoft.

#### Microsoft SQL Server

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
SQL Server 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-070)
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
Microsoft SQL Server 2000 Reporting Services Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Reporting Services Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1c70a2cb-e8a9-439f-b34a-7d1641daf325)   
(KB983814)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
SQL Server 2005
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-070)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 Express Edition com Advanced Services Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 Express Edition com Advanced Services Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>   
(GDR)  
(KB2716429)  
(Importante)  
[Microsoft SQL Server 2005 Express Edition com Advanced Services Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)<sup>[1]</sup>   
(QFE)  
(KB2716427)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 para sistemas de 32 bits Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 para sistemas de 32 bits Service Pack](http://www.microsoft.com/downloads/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)4<sup>[1]</sup>   
(GDR)  
(KB2716429)  
(Importante)  
Microsoft SQL Server 2005 para sistemas de 32 bits Service Pack 4<sup>[1]</sup>   
(QFE)  
(KB2716427)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 para sistemas baseados em x64 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 para sistemas baseados em x64 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>   
(GDR)  
(KB2716429)  
(Importante)  
Microsoft SQL Server 2005 para sistemas baseados em x64 Service Pack 4<sup>[1]</sup>   
(QFE)  
(KB2716427)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 para sistemas baseados em Itanium Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 para sistemas baseados em Itanium Service Pack](http://www.microsoft.com/downloads/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)4<sup>[1]</sup>   
(GDR)  
(KB2716429)  
(Importante)  
[Microsoft SQL Server 2005 para sistemas baseados em Itanium Service Pack](http://www.microsoft.com/downloads/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)4<sup>[1]</sup>   
(QFE)  
(KB2716427)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
SQL Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-070)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1bf8dc30-2a90-4196-814c-717ccd74ea13)<sup>[1]</sup>   
(GDR)  
(KB2716434)  
(Importante)  
[Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d8b1b25-45ad-4f19-ba50-e77debf2b463)<sup>[1]</sup>   
(QFE)  
(KB2716433)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=04621a83-c2e2-4a60-9198-10104372b120)<sup>[1]</sup>   
(GDR)  
(KB2716436)  
(Importante)  
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3<sup>[1]</sup>   
(QFE)  
(KB2716435)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1bf8dc30-2a90-4196-814c-717ccd74ea13)<sup>[1]</sup>   
(GDR)  
(KB2716434)  
(Importante)  
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 2<sup>[1]</sup>   
(QFE)  
(KB2716433)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=04621a83-c2e2-4a60-9198-10104372b120)<sup>[1]</sup>   
(GDR)  
(KB2716436)  
(Importante)  
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3<sup>[1]</sup>   
(QFE)  
(KB2716435)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1bf8dc30-2a90-4196-814c-717ccd74ea13)<sup>[1]</sup>   
(GDR)  
(KB2716434)  
(Importante)  
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 2<sup>[1]</sup>   
(QFE)  
(KB2716433)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=04621a83-c2e2-4a60-9198-10104372b120)<sup>[1]</sup>   
(GDR)  
(KB2716436)  
(Importante)  
[Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4c4597d2-dea0-49b9-a5a9-a7771a3d64c0)<sup>[1]</sup>   
(QFE)  
(KB2716435)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
SQL Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-070)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=215a9184-71c5-41e6-b4d5-03602182a88f)<sup>[1]</sup>   
(GDR)  
(KB2716440)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 1<sup>[1]</sup>   
(QFE)  
(KB2716439)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=215a9184-71c5-41e6-b4d5-03602182a88f)<sup>[1]</sup>   
(GDR)  
(KB2716440)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 1<sup>[1]</sup>   
(QFE)  
(KB2716439)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=215a9184-71c5-41e6-b4d5-03602182a88f)<sup>[1]</sup>   
(GDR)  
(KB2716440)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 1<sup>[1]</sup>   
(QFE)  
(KB2716439)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
SQL Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-070)
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
Microsoft SQL Server 2012 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2012 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=e79b4e5b-1549-4e76-afef-b771b432365b)<sup>[1]</sup>   
(GDR)  
(KB2716442)  
(Importante)  
[Microsoft SQL Server 2012 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=ebfcb341-e240-4107-92f1-ab75cc28151a)<sup>[1]</sup>   
(QFE)  
(KB2716441)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2012 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2012 para sistemas x64](http://www.microsoft.com/downloads/details.aspx?familyid=e79b4e5b-1549-4e76-afef-b771b432365b)<sup>[1]</sup>   
(GDR)  
(KB2716442)  
(Importante)  
Microsoft SQL Server 2012 para sistemas x64<sup>[1]</sup>   
(QFE)  
(KB2716441)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para o MS12-070**

<sup>[1]</sup>Esta atualização somente é oferecida a clientes que executam o SQL Server Reporting Services (SSRS).

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o Centro de Gerenciamento de Atualização do Technet. O site TechNet Security TechCenter fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar Microsoft Safety & Security Center, onde essas informações também estão disponíveis, clicando em “Atualizações de segurança”.

As atualizações de segurança estão disponíveis no Microsoft Update e no Windows Update. As atualizações de segurança também estão disponíveis no Centro de Download da Microsoft. Você poderá encontrá-las com mais facilidade executando uma pesquisa com a palavra-chave "atualização de segurança".

Para os clientes do Microsoft Office for Mac, o Microsoft AutoUpdate for Mac pode ajudar a manter seu software Microsoft atualizado. Para obter mais informações sobre como usar o Microsoft AutoUpdate for Mac, consulte Check for software updates automatically.

Por fim, as atualizações de segurança podem ser baixadas do Microsoft Update Catalog. O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS12-001"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as Perguntas Frequentes sobre Microsoft Update Catalog.

**Orientação de detecção e implantação:**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o Artigo 961747 (em inglês) da Microsoft Knowledge Base.

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, consulte Microsoft Baseline Security Analyzer.

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite Windows Server Update Services.

**System Center Configuration Manager**

O gerenciamento de atualizações de software do System Center Configuration Manager simplifica a complexa tarefa de fornecer e gerenciar atualizações a sistemas de TI pela empresa. Com o System Center Configuration Manager, os administradores de TI podem fornecer atualizações de produtos da Microsoft a uma variedade de dispositivos, inclusive desktops, laptops, servidores e dispositivos móveis.

A avaliação automatizada de vulnerabilidade no System Center Configuration Manager detecta as necessidades de atualizações e relatórios com relação a ações recomendadas. O gerenciamento de atualizações de software no System Center Configuration Manager é integrado ao Microsoft Windows Software Update Services (WSUS), uma infraestrutura de atualização testada quanto à confiabilidade, que é familiar aos administradores de TI do mundo todo. Para obter mais informações sobre o System Center Configuration Manager, consulte: System Center Technical Resources.

**Systems Management Server 2003**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários.

**Observação** O System Management Server 2003 está fora de suporte principal desde 12 de janeiro de 2010. Para obter mais informações sobre ciclos de vida de produtos, acesse Ciclo de Vida do Suporte Microsoft. A próxima versão do SMS, System Center Configuration Manager, já está disponível; consulte a seção anterior: **System Center Configuration Manager**.

Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, consulte [Cenários e procedimentos para o Microsoft Systems Management Server 2003: Distribuição de software e Gerenciamento de patches](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f). Para obter informações sobre o SMS, acesse: Microsoft Systems Management Server TechCenter.

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte Implementando atualizações de software usando o Recurso Distribuição de Software do SMS. Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no SMS 2003 Administration Feature Pack) para instalar essas atualizações.

**Avaliador de compatibilidade com atualizações e Kit de ferramentas de compatibilidade de aplicativos**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do Avaliador de compatibilidade com atualizações incluídos no Kit de ferramentas de compatibilidade de aplicativos para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   Artigo 894199 (em inglês) da Microsoft Knowledge Base
-   : Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   Atualizações dos meses anteriores para o Windows Server Update Services
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

-   Um pesquisador anônimo, que trabalha na Zero Day Initiative da [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/), por relatar um problema descrito no boletim MS12-064
-   Um pesquisador anônimo, que trabalha com o programa Beyond Security's SecuriTeam Secure Disclosure, por relatar um problema descrito no boletim MS12-064
-   Drew Hintz do Google Security Team por relatar um problema descrito no boletim MS12-066
-   Will Dorman da CERT/CC por trabalhar conosco em 13 problemas descritos no boletim MS12-067
-   Um pesquisador anônimo, que trabalha com a VeriSign iDefense Labs, por relatar um problema descrito no boletim MS12-068

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site Ciclo de Vida do Suporte Microsoft.
-   Soluções de segurança para profissionais de TI: Solução de problemas e suporte de segurança TechNet
-   Ajuda a proteger seu computador Windows de vírus e malware: Central de segurança e solução contra vírus
-   Suporte local de acordo com seu país: Suporte internacional

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (9 de outubro de 2012): Resumo de boletins publicado.
-   V1.1 (10 de outubro de 2012): Para MS12-068 e MS12-069, corrigida a avaliação de exploração para o último lançamento de software no **índice de exploração** de CVE-2012-2529 e CVE-2012-2551 respectivamente. Para MS12-066, corrigidos os números da KB do Microsoft Lync 2010 Attendee (instalação de nível administrativo) e do Microsoft Lync 2010 Attendee (instalação de nível usuário).

*Built at 2014-04-18T01:50:00Z-07:00*
