---
TOCTitle: 'MS13-JAN'
Title: Resumo do Boletim de Segurança da Microsoft de janeiro de 2013
ms:assetid: 'ms13-jan'
ms:contentKeyID: 61233699
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms13-jan(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de janeiro de 2013
==============================================================

Publicado: terça-feira, 8 de janeiro de 2013 | Atualizado: terça-feira, 12 de março de 2013

**Versão:** 4.0

Este resumo de boletins lista os boletins de segurança lançados em janeiro de 2013.

Com o lançamento dos boletins de segurança de janeiro de 2013, este resumo de boletins substitui a notificação antecipada originalmente publicada em 3 de janeiro de 2013 e a notificação antecipada desvinculada publicada em 13 de janeiro de 2013. Para obter mais informações sobre o serviço de notificação antecipada de boletins, consulte [Notificação antecipada do boletim de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 9 de janeiro de 2013, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de janeiro.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623“&culture=en-us) Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623“&culture=en-us).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre o boletim desvinculado de segurança em 14 de janeiro de 2013, às 13h00, Horário do Pacífico (EUA e Canadá). [Registre-se agora mesmo para o webcast sobre o boletim de segurança desvinculado que será realizado no dia 14 de janeiro de 2013](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=en-us). Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Internet Explorer (2799329)</strong> <strong><br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente no Internet Explorer. A vulnerabilidade pode permitir a execução remota de código se um usuário visualizar uma página da Web especialmente criada no Internet Explorer. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade</strong> <strong>nos componentes do Spooler de impressão do Windows pode permitir execução remota de código</strong> <strong>(2769369)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um servidor de impressão receber um trabalho de impressão especialmente criado. As práticas recomendadas para firewall e as configurações de firewall padrão podem ajudar a proteger as redes contra ataques com origem externa ao perímetro da empresa. Essas práticas também recomendam que os sistemas conectados diretamente à Internet tenham um número mínimo de portas expostas.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft XML Core Services podem permitir a execução remota de código (2756145)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft XML Core Services. As vulnerabilidades podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. Não há como o invasor forçar os usuários a visitarem o site mal-intencionado. Em vez disso, o invasor precisa persuadir os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um email ou mensagem do Instant Messenger que leva o usuário ao site do invasor.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office,<br />
Ferramentas para desenvolvedor da Microsoft,<br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no System Center Operations Manager podem permitir a elevação de privilégio (2748552)</strong> <strong><br />
<br />
</strong>Esta atualização de segurança resolve duas vulnerabilidades em particular relatadas no Microsoft System Center Operations Manager. As vulnerabilidades podem permitir o aumento de privilégio se um usuário visitar um website afetado por meio de uma URL especialmente criada. Não há como o invasor forçar os usuários a visitarem o site mal-intencionado. Em vez disso, o invasor teria que persuadir os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um e-mail ou mensagem do Instant Messenger que leva o usuário ao site afetado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Não exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades</strong> <strong>no .NET</strong> <strong>Framework podem permitir elevação de privilégio</strong> <strong>(2769324)<br />
<br />
</strong>Esta atualização de segurança elimina quatro vulnerabilidades relatadas em particular no<strong></strong>.NET Framework. A mais severa destas vulnerabilidades pode permitir a elevação de privilégio se um usuário visualizar uma página da Web especialmente criada usando um navegador que pode executar Aplicativos de Navegador XAML (XBAPs). A vulnerabilidade também pode ser usada pelos aplicativos Windows .NET para anular as restrições do CAS (Code Access Security). O invasor que conseguir explorar essas vulnerabilidades poderá obter os mesmos direitos que o usuário com acesso. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no driver do modo do kernel do Windows pode permitir a elevação de privilégio</strong> <strong>(2778930)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a elevação de privilégio se um invasor executar um aplicativo especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft</strong> <strong>Windowspode permitir o desvio do recurso de segurança(2785220)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular na implementação de SSL e TLS no Microsoft Windows. A vulnerabilidade pode permitir desvio de recurso de segurança se um invasor interceptar handshakes criptografados de tráfego da Web.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Desvio de recurso de segurança</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Protocolo de Dados Abertos pode permitir a negação de serviço</strong> <strong>(2769327)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada particularmente no Protocolo de Dados Abertos (OData). A vulnerabilidade pode permitir a negação de serviço se um invasor não autenticado enviar solicitações HTTP especialmente criadas a um site afetado. As práticas recomendadas para firewall e as configurações de firewall padrão podem ajudar a proteger as redes contra ataques com origem externa ao perímetro da empresa. Essas práticas também recomendam que os sistemas conectados à Internet tenham um número mínimo de portas expostas.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Negação de Serviço</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;">Vulnerabilidade nos componentes do Spooler de impressão do Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0011">CVE-2013-0011</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">Vulnerabilidade de truncamento de número inteiro de MSXML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0006">CVE-2013-0006</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">Vulnerabilidade de XSLT no MSXML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0007">CVE-2013-0007</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">Vulnerabilidade no System Center Operations Manager Web Console XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0009">CVE-2013-0009</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">Vulnerabilidade no System Center Operations Manager Web Console XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0010">CVE-2013-0010</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de buffer do WinForms</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0002">CVE-2013-0002</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de buffer do S.DS.P</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0003">CVE-2013-0003</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">Vulnerabilidade de construção dupla</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0004">CVE-2013-0004</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;">Vulnerabilidade no controle de mensagens inadequadas do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0008">CVE-2013-0008</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio de recurso de segurança do protocolo TLS e Microsoft SSL Versão 3</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0013">CVE-2013-0013</a></td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço de substituição</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0005">CVE-2013-0005</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;">Vulnerabilidade de uso após liberação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4792">CVE-2012-4792</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente.<br />
<br />
A Microsoft está ciente dos ataques direcionados que tentam explorar essa vulnerabilidade no Internet Explorer 8.</td>
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
<th colspan="8">
Windows XP (site em inglês)
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=20d8d873-a709-4834-a956-f3d9d82dbb73)  
(KB2799329)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dcdcf814-e39d-4515-bc5d-12e11f214d08)  
(KB2799329)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4e0d584a-c684-408c-bc47-6bd4ecaa9b8a)  
(KB2799329)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=137cc5ee-abf0-4a10-b1c4-d464331cbcfd)  
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=155a2984-2cd9-40a4-abaa-c1ea21e76062)  
(KB2742607)  
(Somente Media Center Edition 2005 Service Pack 3 e Tablet PC Edition 2005 Service Pack 3)  
(Importante)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(Importante)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f35f2ea5-d60e-405a-9ed3-248e0d733c2b)  
(KB2799329)  
(Crítica)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=36c9d6a9-d939-4e19-b9f5-576fee048764)  
(KB2799329)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=396f26bd-8c8b-459d-9467-6ec17a11c9d4)  
(KB2799329)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d147f865-6a56-4db2-8d78-14f2bee6da18)  
(KB2757638)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9)  
(KB2758696)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(Importante)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=1a7cfc5a-2872-4516-a371-f42d4d3969a6)  
(KB2799329)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b7c2bcd-a732-46ba-9d09-cc192efd4755)  
(KB2799329)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7f134d1c-670d-4528-b755-22124aa4d8c9)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=6a12de5f-de80-48e4-8276-6c420f5a2948)  
(KB2758696)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f1a2eb6e-0290-4a53-b93c-017a48b19973)  
(KB2742604)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(Importante)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=00304f3b-069f-49dc-a416-b0b5fb97aa4b)  
(KB2799329)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4911899c-863f-4499-9477-340ef8daad29)  
(KB2799329)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b0cf6516-aea6-4879-9a6e-171d4825ae20)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=29985fdc-8aba-44b2-9420-970ca475052e)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9)  
(KB2758696)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(Importante)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b2c635b7-56ad-426b-8bd6-4aee9deadb69)  
(KB2799329)  
(Moderada)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b33197ab-f489-4c11-a229-044b186d7dda)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=bca95077-a28f-406c-9fe4-51dbcf6adee8)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb834cf7-d1fe-4291-8a0d-c866fdbdf0e6)  
(KB2758696)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=95d603e8-9440-4aa6-9765-20c77a55966a)  
(KB2799329)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=64b498a6-54fc-4b88-bcc3-2cc15a16abb5)  
(KB2799329)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d477235d-60f4-420d-8161-82194b4e62e7)  
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(Importante)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b1aef73-cfb2-4998-bca6-35cccfbb2078)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3107fadf-5ba8-48f6-bb23-0c0003b4ba76)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a35ccbff-c476-4ee2-be9c-5b6a4b1664e9)  
(KB2799329)  
(Crítica)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b427bace-5297-4593-9dd2-66847ae506c6)  
(KB2799329)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3)  
(KB2757638)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3)  
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(Importante)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4287381f-6f23-4a36-a7dc-f79c44bac124)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=098958e5-83cd-4ed2-b758-e970cef33325)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3ce450f1-f71f-4d5d-bf1c-db4742522d18)  
(KB2799329)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2d1266fc-f6b0-4062-9799-7b3721c2cf52)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(Importante)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0f87dd60-92c2-444c-a9ea-dfeb106c88fa)  
(KB2799329)  
(Moderada)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2f71f8e6-309c-4bea-abde-d91040c46611)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(Importante)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e47425e9-f53e-4e20-a7ec-b4c552bd66eb)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(Importante)  
[Microsoft .NET Framework 3.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d949fde9-31e7-4553-a34c-b41625a8cdc8)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ab117984-c4cb-473b-8c20-2b0d0409d8d6)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
Windows 7 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285)  
(KB2799329)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b)  
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285)  
(KB2799329)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b)  
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154)  
(KB2799329)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154)  
(KB2799329)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(Importante)
</td>
</tr>
<tr>
<th colspan="8">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
Windows 8 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e19d1373-a3f3-4f60-9142-c2484726aac8)  
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
(Importante)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=1f5441f1-a66d-42c0-bf0e-2f6867d4d43a)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=9f40864f-5347-44ef-bb08-afea45b5351b)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c)  
(KB2757638)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Crítica)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c)  
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
(Importante)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=9d71dc77-9c01-4a1f-b403-8a18ca10979d)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=1b40baad-784a-4eba-a4ef-703250248057)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
(Importante)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
Windows Server 2012
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
(Importante)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
(Importante)  
[Management OData IIS Extension](http://www.microsoft.com/downloads/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1)  
(KB2753596)  
(Importante)
</td>
</tr>
<tr>
<th colspan="8">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador** **do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
Windows RT
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0<sup>[1]</sup>
(KB2758694)  
(Crítica)  
Microsoft XML Core Services 6.0<sup>[1]</sup>
(KB2757638)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>
(KB2742614)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="8">
Opção de instalação de núcleo de servidor
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222) 
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45) (instalação do núcleo do servidor)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004) (instalação do núcleo do servidor)  
(KB2785220)  
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
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735) (Instalação de núcleo de servidor)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (Instalação de núcleo de servidor)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735) (Instalação de núcleo de servidor)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068) (instalação do núcleo do servidor)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc) (instalação do núcleo do servidor)  
(KB2785220)  
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
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19) (instalação do núcleo do servidor)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (Instalação de núcleo de servidor)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (Instalação de núcleo de servidor)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (Instalação de núcleo de servidor)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a) (Instalação do núcleo de servidor)  
(KB2742598)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127) (Instalação do núcleo de servidor)  
(KB2756920)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5) (instalação do núcleo do servidor)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e) (instalação do núcleo do servidor)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4) (Instalação do núcleo de servidor)  
(KB2736418)  
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
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19) (instalação do núcleo do servidor)  
(KB2769369)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (Instalação de núcleo de servidor)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (Instalação de núcleo de servidor)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (Instalação de núcleo de servidor)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0) (Instalação do núcleo de servidor)  
(KB2742599)  
(Importante)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3) (Instalação do núcleo de servidor)  
(KB2756921)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup> (Instalação do núcleo de servidor)  
(KB2742595)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0) (Instalação de núcleo de servidor)  
(KB2742613)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5) (instalação do núcleo do servidor)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e) (instalação do núcleo do servidor)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97) (Instalação do núcleo de servidor)  
(KB2736422)  
(Importante)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup> (Instalação do núcleo de servidor)  
(KB2736428)  
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
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528) (Instalação de núcleo de servidor)  
(KB2757638)  
(Moderada)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (Instalação de núcleo de servidor)  
(KB2758694)  
(Moderada)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528) (Instalação de núcleo de servidor)  
(KB2757638)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998) (Instalação do núcleo de servidor)  
(KB2742616)  
(Importante)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e) (Instalação do núcleo de servidor)  
(KB2756923)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a) (Instalação de núcleo de servidor)  
(KB2742614)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d) (instalação Server Core)  
(KB2778930)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a) (instalação Server Core)  
(KB2785220)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb) (Instalação do núcleo de servidor)  
(KB2736693)  
(Importante)  
[Management OData IIS Extension](http://www.microsoft.com/downloads/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1) (Instalação do núcleo de servidor)  
(KB2753596)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observações** **para MS13-002**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

<sup>[1]</sup>As atualizações de segurança do Windows RT são fornecidas pelo [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

**Observações para MS13-004**

<sup>[1]</sup>**.NET Framework 4 e .NET Framework 4 Client Profile afetados.** Os pacotes redistribuíveis do .Net Framework versão 4 estão disponíveis em dois perfis: .NET Framework 4 e .NET Framework 4 Client Profile. O .NET Framework 4 Client Profile é um subconjunto do .NET Framework 4. A vulnerabilidade abordada nesta atualização afeta tanto o .NET Framework 4 quanto o .NET Framework 4 Client Profile. Para obter mais informações, consulte o artigo de MSDN, [Instalando o .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

<sup>[2]</sup>Classificações de gravidade não se aplicam a esta atualização para o software especificado, porque os vetores de ataque conhecidos para a vulnerabilidade abordada neste boletim são bloqueados em uma configuração padrão. No entanto, como medida de defesa abrangente, a Microsoft recomenda que clientes deste software apliquem esta atualização de segurança.

<sup>[3]</sup>As atualizações de segurança do Windows RT são fornecidas pelo [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

**Observação** **para MS13-005**

<sup>[1]</sup>As atualizações de segurança do Windows RT são fornecidas pelo [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

**Observação** **para MS13-006**

<sup>[1]</sup>As atualizações de segurança do Windows RT são fornecidas pelo [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

**Observação para MS13-007**

<sup>[1]</sup>**.NET Framework 4 e .NET Framework 4 Client Profile afetados.** Os pacotes redistribuíveis do .Net Framework versão 4 estão disponíveis em dois perfis: .NET Framework 4 e .NET Framework 4 Client Profile. O .NET Framework 4 Client Profile é um subconjunto do .NET Framework 4. A vulnerabilidade abordada nesta atualização afeta tanto o .NET Framework 4 quanto o .NET Framework 4 Client Profile. Para obter mais informações, consulte o artigo de MSDN, [Instalando o .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office Suites e componentes
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=d108d56c-f9fb-4823-b38e-3d2f838592de)  
(KB2760574)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Outros softwares do Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
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
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(Crítica)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS13-002**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Ferramentas e softwares para desenvolvedores Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual Studio Team Foundation Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
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
Microsoft Expression Web Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(Crítica)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS13-002**

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
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-003**](http://go.microsoft.com/fwlink/?linkid=261863)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(Crítica)
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
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(Crítica)
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
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-003**](http://go.microsoft.com/fwlink/?linkid=261863)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft System Center Operations Manager
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-003**](http://go.microsoft.com/fwlink/?linkid=261863)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center Operations Manager 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f848d74d-fdae-4a19-a0f5-12d2d4389db9)<sup>[1]</sup>
(KB2809182)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft System Center Operations Manager 2007 R2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 R2](http://www.microsoft.com/downloads/details.aspx?familyid=4e1ab3bd-af0c-41f8-8ebc-1cdc68a3ee37)<sup>[1]</sup><sup>[2]</sup>
(KB2783850)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS13-002**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

**Observações** **para MS13-003**

<sup>[1]</sup>Esta atualização está disponível somente no Centro de Download da Microsoft.

<sup>[2]</sup>Esta atualização é cumulativa e substitui atualizações cumulativas anteriores do software especificado.

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

-   Nicolas Grégoire, da [Agarri](http://www.agarri.fr/), por relatar um problema descrito no boletim MS13-002
-   Andy Yang, da BAE Systems Detica, por relatar um problema descrito no boletim MS13-003
-   Jon Erickson, da [iSIGHT Partners Labs](http://www.isightpartners.com/), por relatar um problema descrito no boletim MS13-004
-   Vitaliy Toropov, que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) da [Tipping Point](http://www.tippingpoint.com/), por relatar dois problemas descritos no boletim MS13-004
-   James Forshaw, da Context Information Security, por reportar um problema descrito no boletim MS13-004
-   [Kenichiro Katayama](https://twitter.com/pin_ptr) por relatar um problema descrito no boletim MS13-006
-   [Exodus Intelligence](https://www.exodusintel.com) por trabalhar conosco em um problema no MS13-008

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617,aspx)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (8 de janeiro de 2013): Resumo de boletins publicado.
-   V1.1 (8 de janeiro de 2013): No MS13-002, adicionadas entradas de instalação de núcleo de servidor à seção Softwares afetados referente ao Microsoft XML Core Services 4.0 quando instalado no Windows Server 2008 para sistemas Service Pack 2 de 32 bits e ao Microsoft XML Core Services 6.0 no Windows Server 2008 para sistemas Service Pack 2 de 32 bits. Esta é apenas uma alteração informativa. Os clientes que já atualizaram seus sistemas com êxito não precisam fazer mais nada.
-   V2.0 (14 de janeiro de 2013): Adicionados o boletim de segurança MS13-008 da Microsoft, a atualização de segurança para o Internet Explorer (2799329) e o link para o webcast deste boletim de segurança desvinculado.
-   V3.0 (22 de janeiro de 2013): Para o MS13-004, a Microsoft relançou esse boletim para oferecer novamente a atualização KB2756920 para o Windows 7 e Windows Server 2008 R2 a sistemas que são executados em configurações específicas e que apresentam possibilidade de problemas de compatibilidade. Consulte o boletim para obter mais informações.
-   V4.0 (12 de março de 2013) : Para o MS13-003, boletim relançado para anunciar a disponibilização de uma atualização do Microsoft System Center Operations Manager 2007 Service Pack 1. Nenhum outro pacote de atualização será afetado por este comunicado. Consulte o boletim para obter mais informações.

*Built at 2014-04-18T01:50:00Z-07:00*
