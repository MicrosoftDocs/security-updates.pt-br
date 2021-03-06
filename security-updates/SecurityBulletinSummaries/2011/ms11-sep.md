---
TOCTitle: 'MS11-SEP'
Title: Resumo do Boletim de Segurança da Microsoft de setembro 2011
ms:assetid: 'ms11-sep'
ms:contentKeyID: 61233682
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms11-sep(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de setembro 2011
============================================================

Publicado: terça-feira, 13 de setembro de 2011 | Atualizado: terça-feira, 13 de setembro de 2011

**Versão:** 1.1

Este resumo de boletins lista os boletins de segurança lançados em setembro de 2011.

Com o lançamento dos boletins de setembro de 2011, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 8 de setembro de 2011. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 14 de setembro de 2011, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de setembro](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487951). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://go.microsoft.com/fwlink/?linkid=217214)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

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
<th style="border:1px solid black;" >Necessidade de Reinicialização</th>
<th style="border:1px solid black;" >Softwares afetados</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade em WINS poderia permitir elevação de privilégio (2571621)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade em particular relatada no Serviço de cadastramento na Internet do Windows (WINS). A vulnerabilidade poderia permitir a elevação de privilégio se um usuário recebesse um pacote de replicação WINS especialmente criado em um sistema afetado que estivesse executando o serviço WINS. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade em componentes do Windows poderia permitir execução remota de código</strong> <strong>(2570947)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade publicamente divulgada no Microsoft Windows. A vulnerabilidade poderia permitir a execução remota de código se um usuário abrisse um arquivo legítimo em formato rich text (.rtf), um arquivo de texto (.txt) ou um documento do Word (.doc) localizado no mesmo diretório de rede que um arquivo de biblioteca de link dinâmico (DLL) especialmente criado. O invasor que explorar com êxito a vulnerabilidade poderá obter os mesmos direitos que o usuário local. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Excel poderiam permitir execução remota de código (2587505)</strong><br />
<br />
Esta atualização de segurança resolve cinco vulnerabilidades em particular relatadas no Microsoft Office. As vulnerabilidades podem permitir a execução remota de código quando um usuário abre um arquivo do Excel especialmente criado. O invasor que explorar com êxito qualquer uma destas vulnerabilidades poderá obter os mesmos direitos que o usuário local. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. Instalar e configurar Validação de Arquivo de Office (OFV) para evitar a abertura de arquivos suspeitos bloqueia os vetores de ataque que exploram as vulnerabilidades descritas em CVE-2011-1986 e CVE-2011-1987.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office, <br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Office poderiam permitir execução remota de código (2587634)</strong><br />
<br />
Esta atualização de segurança resolve cinco vulnerabilidades em particular relatadas no Microsoft Office. As vulnerabilidades podem permitir a execução remota de código se um usuário abrir um arquivo do Office especialmente criado ou se um usuário abrir um arquivo do Office legítimo localizado no mesmo diretório de rede que um arquivo de biblioteca especialmente criado. O invasor que explorar com êxito qualquer uma destas vulnerabilidades poderá obter os mesmos direitos que o usuário com acesso. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft SharePoint poderiam permitir elevação de privilégio (2451858)</strong><br />
<br />
Esta atualização de segurança resolve cinco vulnerabilidades em particular relatadas e uma publicamente divulgada no Microsoft SharePoint e Windows SharePoint Services. As vulnerabilidades mais graves podem permitir elevação de privilégio se um usuário clicar em uma URL ou visitar um site especialmente criado. Para as vulnerabilidades mais graves, usuários do Internet Explorer 8 e Internet Explorer 9 procurando por um site de SharePoint na zona da Internet correm menos risco, por padrão, porque o Filtro de XSS no Internet Explorer 8 e Internet Explorer 9 ajuda a bloquear os ataques na zona da Internet. Entretanto, o Filtro de XSS no Internet Explorer 8 e no Internet Explorer 9 não é habilitado por padrão na zona de Intranet.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office, <br />
Microsoft Server Software</td>
</tr>
</tbody>
</table>

<p></p>

 

Índice de exploração
--------------------

 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas por ordem de ID do boletim e de ID da CVE. Só são incluídas as vulnerabilidades com uma classificação de gravidade Crítica ou Importante nos boletins.

**Como devo usar a tabela?**  

Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Microsoft Exploitability Index](http://technet.microsoft.com/security/cc998259.aspx).

Nas colunas a seguir, "Versão mais Recente de Software" se refere ao software, e "Versões mais Antigas de Software se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
ID do Boletim
</th>
<th style="border:1px solid black;" >
Título da vulnerabilidade
</th>
<th style="border:1px solid black;" >
ID do CVE
</th>
<th style="border:1px solid black;" >
Avaliação do risco de exploração para execução de códigos do última versão do software
</th>
<th style="border:1px solid black;" >
Avaliação do risco de exploração para execução de códigos das versões de software mais antigas
</th>
<th style="border:1px solid black;" >
Avaliação do risco de exploração para negação de serviço
</th>
<th style="border:1px solid black;" >
Principais observações
</th>
</tr>
<tr>
<td style="border:1px solid black;">
[MS11-070](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio local do WINS
</td>
<td style="border:1px solid black;">
[CVE-2011-1984](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1984)
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
[MS11-071](http://go.microsoft.com/fwlink/?linkid=223632)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de carregamento não seguro de bibliotecas dos componentes do Windows
</td>
<td style="border:1px solid black;">
[CVE-2011-1991](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1991)
</td>
 
<td style="border:1px solid black;">
1 - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Esta vulnerabilidade foi divulgada publicamente.
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de uso do Excel após liberação de WriteAV
</td>
<td style="border:1px solid black;">
[CVE-2011-1986](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1986)
</td>
<td style="border:1px solid black;">
Não afetado
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de indexação de matriz fora dos limites do Excel
</td>
<td style="border:1px solid black;">
[CVE-2011-1987](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1987)
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de heap do Excel
</td>
<td style="border:1px solid black;">
[CVE-2011-1988](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1988)
</td>
<td style="border:1px solid black;">
Não afetado
</td>
<td style="border:1px solid black;">
[2](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração inconsistente?
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de análise de expressão condicional do Excel
</td>
<td style="border:1px solid black;">
[CVE-2011-1989](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1989)
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de indexação de matriz fora dos limites do Excel
</td>
<td style="border:1px solid black;">
[CVE-2011-1990](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1990)
</td>
<td style="border:1px solid black;">
Não afetado
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
[MS11-073](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de carregamento não seguro de biblioteca de componentes do Office
</td>
<td style="border:1px solid black;">
[CVE-2011-1980](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1980)
</td>
<td style="border:1px solid black;">
Não afetado
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS11-073](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de ponteiro de objeto não inicializado do Office
</td>
<td style="border:1px solid black;">
[CVE-2011-1982](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1982)
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Temporário
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de XSS no Calendário do SharePoint
</td>
<td style="border:1px solid black;">
[CVE-2011-0653](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0653)
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de limpeza de HTML
</td>
<td style="border:1px solid black;">
[CVE-2011-1252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252)
</td>
<td style="border:1px solid black;">
[3](http://technet.microsoft.com/security/cc998259.aspx) – Código de exploração de funcionamento improvável
</td>
<td style="border:1px solid black;">
[3](http://technet.microsoft.com/security/cc998259.aspx) – Código de exploração de funcionamento improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Essa é uma vulnerabilidade de divulgação de informações  
Esta vulnerabilidade foi divulgada publicamente
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de Inserção de Script do Editform
</td>
<td style="border:1px solid black;">
[CVE-2011-1890](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1890)
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de Detalhes de Contato Refletidos no XSS
</td>
<td style="border:1px solid black;">
[CVE-2011-1891](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1891)
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de Divulgação de Arquivo Remoto do SharePoint
</td>
<td style="border:1px solid black;">
[CVE-2011-1892](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1892)
</td>
<td style="border:1px solid black;">
[3](http://technet.microsoft.com/security/cc998259.aspx) – Código de exploração de funcionamento improvável
</td>
<td style="border:1px solid black;">
[3](http://technet.microsoft.com/security/cc998259.aspx) – Código de exploração de funcionamento improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Essa é uma vulnerabilidade de divulgação de informações
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de XSS no SharePoint
</td>
<td style="border:1px solid black;">
[CVE-2011-1893](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1893)
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
[1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
(Nenhum)
</td>
</tr>
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

<table summary="table"><tbody><tr class="thead"><th scope="col">Windows XP (site em inglês)</th></tr><tr class="thead"><th scope="row">Windows Server 2003</th></tr><tr class="thead"><th scope="row">Windows Vista</th></tr><tr class="thead"><th scope="row">Windows Server 2008</th></tr><tr class="thead"><th scope="row">Windows 7</th></tr><tr class="thead"><th scope="row">Windows Server 2008 R2</th></tr>
                <tr><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225825"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-070</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=223632"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-071</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>Nenhuma</td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=70f944b0-9bf0-4168-b150-67d2ff68df2d">Windows XP Service Pack 3</a>
                    <br>(Importante)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=4b9debed-edbb-43e1-b755-0faf01980289">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br>(Importante)</td></tr>              
                <tr><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225825"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-070</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=223632"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-071</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=1e6ac3b2-752e-49a0-84e5-5a8dfe955299">Windows Server 2003 Service Pack 2</a>
                    <br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=d44274d2-0401-4fd8-bc4f-c59f6d81c34f">Windows Server 2003 Service Pack 2</a>
                    <br>(Importante)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=f9378339-c58e-4e84-9427-85aeb35b0d99">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=935720ee-cee0-42c2-965e-ce1b07e95e1a">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br>(Importante)</td></tr>
                <tr><td>Windows Server 2003 com SP2 para sistemas baseados no Itanium</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=c35c71a8-13b4-47a6-9763-06f6f65327b1">Windows Server 2003 com SP2 para sistemas baseados em Itanium</a>
                    <br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=78c2ac72-da89-42a4-bff9-79551b5d3c4e">Windows Server 2003 com SP2 para sistemas baseados em Itanium</a>
                    <br>(Importante)</td></tr>              
                <tr class="alternateRow"><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225825"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-070</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=223632"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-071</strong></a>
                  </td></tr>
                <tr><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>Nenhuma</td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=15840336-4886-4a1b-8c1e-2c535c3938f7">Windows Vista Service Pack 2</a>
                    <br>(Importante)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=e80739b4-89bb-4317-8381-991244a71cb8">Windows Vista x64 Edition Service Pack 2</a>
                    <br>(Importante)</td></tr>              
                <tr class="alternateRow"><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225825"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-070</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=223632"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-071</strong></a>
                  </td></tr>
                <tr><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 para sistemas de 32 bits Service Pack 2</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=a9039660-3cc2-470d-a0a5-a70f78074495">Windows Server 2008 for 32-bit Systems Service Pack 2</a>\*<br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=05c39ab3-7b57-4147-8913-df5df6005799">Windows Server 2008 for 32-bit Systems Service Pack 2</a>\*<br>(Importante)</td></tr>
                <tr><td>Windows Server 2008 para sistemas baseados em x64 Service Pack 2</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=5ea78a9b-b1f7-4e94-b69e-c984e1622ae9">Windows Server 2008 para sistemas baseados em x64 Service Pack 2</a>\*<br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=1499d988-fd55-4317-b859-ec170907d547">Windows Server 2008 para sistemas baseados em x64 Service Pack 2</a>\*<br>(Importante)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 para sistemas baseados no Itanium Service Pack 2</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=6e2d2ea9-0af6-4d23-875d-3211722cd62f">Windows Server 2008 para sistemas baseados em Itanium Service Pack 2</a>
                    <br>(Importante)</td></tr>              
                <tr><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225825"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-070</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=223632"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-071</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>Nenhuma</td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr><td>Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=76b99ab2-7e99-4aad-a419-7996bae05c48">Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1</a>
                    <br>(Importante)</td></tr>
                <tr class="alternateRow"><td>Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=0f6d32de-d3ff-4af9-9b26-a4f12581f5fe">Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64</a>
                    <br>(Importante)</td></tr>              
                <tr><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225825"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-070</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=223632"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-071</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=f58cf343-946c-4e74-bd9c-40ac934a4986">Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1</a>\*<br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=a8a451bd-3e5c-4845-9941-daabd9418776">Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1</a>\*<br>(Importante)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=0fdfb1f9-20b3-4d61-8019-33d1003290c8">Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados em Itanium</a>
                    <br>(Important)</td></tr>
              </tbody></table>
<p></p>

  
**Observação para Windows Server 2008 e Windows Server 2008 R2**  

  
**\*Instalação do núcleo do servidor afetada.** Esta atualização se aplica, com a mesma classificação de gravidade, às edições com suporte do Windows Server 2008 e do Windows Server 2008 R2, conforme indicado, independentemente de terem sido instalados ou não com a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) e [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (em inglês). Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).


<p></p>


#### Microsoft Office Suites e software


 
<p></p>

<table summary="table"><tbody><tr class="thead"><th scope="col">Microsoft Office Suites e componentes</th></tr><tr class="thead"><th scope="row">Microsoft Office para Mac</th></tr><tr class="thead"><th scope="row">Microsoft Office Groove e Microsoft SharePoint Workspace</th></tr><tr class="thead"><th scope="row">Outros softwares do Microsoft Office</th></tr>
                <tr><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225047"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-072</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225103"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-073</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=204797"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-074</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td><td>Nenhuma</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=DEE4F3D7-BC4B-47FD-8E3F-9D2B0E82D0F6">Microsoft Excel 2003 Service Pack 3</a>
                    <br>(KB2553072)<br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=7FAA2F90-2E64-4DBF-AC93-BB8CFFC9B5FE">Microsoft Office 2003 Service Pack 3</a>
                    <br>(KB2584052)<br>(Importante)</td><td>Não Aplicável</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2007 Service Pack 2</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=498AC241-D728-4944-ABAC-EC8444CA6418">Microsoft Excel 2007 Service Pack 2</a>
                    <br>(KB2553073)<span class="sup">[1]</span><br>(Importante)Microsoft<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=DF04B9CE-2DAA-4B4D-A944-A873075656F9">Office 2007 Service Pack 2</a><br>(KB2553089)<span class="sup">[1]</span><br>(Importante)Microsoft<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=90EEF02B-DB1F-4FDD-BB1D-408063671E4D">Office 2007 Service Pack 2</a><br>(KB2553090)<span class="sup">[1]</span><br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=34BBEE95-0E83-4705-8BFE-02E4FB22F8E7">Microsoft Office 2007 Service Pack 2</a>
                    <br>(KB2584063)<br>(Importante)</td><td>Não Aplicável</td></tr>
                <tr><td>Microsoft Office 2010 e Microsoft Office 2010 Service Pack 1 (edições de 32 bits)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=4612C6E4-AC29-4CC4-9DA5-88779EA3643E">Microsoft Excel 2010 e Microsoft Excel 2010 Service Pack 1</a>
                    <br>(edições de 32 bits) (KB2553070)<br>(Importante)Microsoft<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=1FD15144-5547-4927-8583-8D9B06819226">Office 2010 e Microsoft Office 2010 Service Pack 1</a><br>(edições de 32 bits) (KB2553091)<br>(Importante)Microsoft<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=18840D78-944F-400A-ADDC-DCE7E570A569">Office 2010 e Microsoft Office 2010 Service Pack 1</a><br>(edições de 32 bits) (KB2553096)<br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=3C8FD04A-9DF6-4726-A9BC-811F49665981">Microsoft Office 2010 e Microsoft Office 2010 Service Pack 1 (edições de 32 bits)</a>
                    <br>(KB2584066)<br>(Importante)</td><td>Não Aplicável</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 e Microsoft Office 2010 Service Pack 1 (edições de 64 bits)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=D40DB27B-1318-4CA7-B44F-C90BB6342109">Microsoft Excel 2010 e Microsoft Excel 2010 Service Pack 1</a>
                    <br>(edições de 64 bits) (KB2553070)<br>(Importante)Microsoft<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=F83800AA-6403-4341-AFEA-D363E54D5831">Office 2010 e Microsoft Office 2010 Service Pack 1</a><br>(edições de 64 bits) (KB2553091)<br>(Importante)Microsoft<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=92787E00-6F30-4020-9C1A-70270BE5A623">Office 2010 e Microsoft Office 2010 Service Pack 1</a><br>(edições de 64 bits) (KB2553096)<br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=85360DC1-99E7-4E3E-BE6F-3795E8A8122F">Microsoft Office 2010 e Microsoft Office 2010 Service Pack 1 (edições de 64 bits)</a>
                    <br>(KB2584066)<br>(Importante)</td><td>Não Aplicável</td></tr>              
                <tr><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225047"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-072</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225103"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-073</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=204797"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-074</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td><td>Nenhuma</td><td>Nenhuma</td></tr>
                <tr><td>Microsoft Office 2004 para Mac</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?FamilyID=868f4d9f-3498-4d59-a017-59204553889c">Microsoft Office 2004 para Mac</a>
                    <br>(KB2598782)<br>(Importante)</td><td>Não Aplicável</td><td>Não Aplicável</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 para Mac</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?FamilyID=afa79cfc-6e8a-4d0b-88aa-0d7e05031e44">Microsoft Office 2008 para Mac</a>
                    <br>(KB2598781)<br>(Importante)</td><td>Não Aplicável</td><td>Não Aplicável</td></tr>
                <tr><td>Microsoft Office for Mac 2011</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?FamilyID=535fcf4a-eeb2-44eb-b2a6-9c512509c49d">Microsoft Office para Mac 2011</a>
                    <br>(KB2598783)<br>(Importante)</td><td>Não Aplicável</td><td>Não Aplicável</td></tr>
                <tr class="alternateRow"><td>Open XML File Format Converter para Mac</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?FamilyID=9796588d-238f-4694-9598-1aa8d2becb55">Open XML File Format Converter para Mac</a>
                    <br>(KB2598785)<br>(Importante)</td><td>Não Aplicável</td><td>Não Aplicável</td></tr>              
                <tr><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225047"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-072</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225103"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-073</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=204797"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-074</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>Nenhuma</td><td>Nenhuma</td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr><td>Para Microsoft Office Groove 2007 Service Pack 2</td><td>Não Aplicável</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=5ea6192b-55e5-4ca4-8d91-cc768ede8277">Microsoft Office Groove 2007 Service Pack 2</a>
                    <br>(KB2552997)<br>(Importante)</td></tr>
                <tr class="alternateRow"><td>Microsoft SharePoint Workspace 2010 e Microsoft SharePoint Workspace 2010 Service Pack 1 (edições de 32 bits)    </td><td>Não Aplicável</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=f6ee7e43-9da9-4b96-abd0-390cfcacb885">Microsoft SharePoint Workspace 2010 e Microsoft SharePoint Workspace 2010 Service Pack 1 (edições de 32 bits)</a>
                    <br>(KB2566445)<br>(Importante)</td></tr>
                <tr><td>Microsoft SharePoint Workspace 2010 e Microsoft SharePoint Workspace 2010 Service Pack 1 (edições de 64 bits)</td><td>Não Aplicável</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=234efac1-4f09-41f5-90a9-4a3c2e81c05e">Microsoft SharePoint Workspace 2010 e Microsoft SharePoint Workspace 2010 Service Pack 1 (edições de 64 bits)</a>
                    <br>(KB2566445)<br>(Importante)</td></tr>              
                <tr class="alternateRow"><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225047"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-072</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225103"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-073</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=204797"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-074</strong></a>
                  </td></tr>
                <tr><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td><td>Nenhuma</td><td>Nenhuma</td></tr>
                <tr class="alternateRow"><td>Microsoft Excel Viewer Service Pack 2</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=F82CA5DA-A55A-487C-8170-46A40000C8E3">Microsoft Excel Viewer Service Pack 2</a>
                    <br>(KB2553075)<br>(Importante)</td><td>Não Aplicável</td><td>Não Aplicável</td></tr>
                <tr><td>Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 2</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=01093F22-06B7-4C9B-BFF9-F54AC5D73BF8">Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 2</a>
                    <br>(KB2553074)<br>(Importante)</td><td>Não Aplicável</td><td>Não Aplicável</td></tr>
              </tbody></table>

<p></p>

  
**Observações para o boletim MS11-072**
  
<sup>[1]</sup>Para o Microsoft Excel 2007 Service Pack 2, além do pacote de atualização de segurança KB2553073, KB2553089 e KB2553090, os clientes também precisam instalar a atualização de segurança para o Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 2 (KB2553074) para se protegerem das vulnerabilidades descritas neste boletim.
  
Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.
  
**Observação para o boletim MS11-074**
  
Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

<p></p>
  
#### Microsoft Server Software
 
<p></p>

<table summary="table"><tbody><tr class="thead"><th scope="col">Microsoft SharePoint Server</th></tr><tr class="thead"><th scope="row">Microsoft Office Forms Server</th></tr><tr class="thead"><th scope="row">Microsoft Groove Server</th></tr><tr class="thead"><th scope="row">Microsoft Office Web Apps</th></tr><tr class="thead"><th scope="row">Windows SharePoint Services e Microsoft SharePoint Foundation</th></tr>
                <tr><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225047"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-072</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=204797"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-074</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr><td>Microsoft Office SharePoint Server&nbsp;2007 Service Pack&nbsp;2 (edições de 32&nbsp;bits)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=DD532201-485C-4270-88D3-63BD3F24327E">Microsoft Excel Services</a>
                    <br>(KB2553093)<span class="sup">[2]</span><br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=ad52c341-13ce-4b53-87b4-269cb3f41275">Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (edições de 32 bits)</a>
                    <br>(KB2508964)<span class="sup">[1]</span><br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=fd6189c9-ab3b-441f-a901-6ac7f3b202aa">Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (edições de 32 bits)</a><br>(KB2553001)<span class="sup">[1]</span><br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=d9601fae-4a80-45cd-a49b-ef441856d7e4">Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (edições de 32 bits)</a><br>(KB2553002)<span class="sup">[1]</span><br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=55b60e2f-ec68-4ccb-803a-5d03add8a1f1">Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (edições de 32 bits)</a><br>(KB2553003)<span class="sup">[1]</span><br>(Importante)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007 Service Pack&nbsp;2 (edições de 64 bits)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=1086A5B0-E441-4E26-A8D1-924A20121DDE">Microsoft Excel Services</a>
                    <br>(KB2553093)<span class="sup">[2]</span><br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=e5e60751-242a-4fdb-9852-6d94050d3d0e">Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (edições de 64 bits)</a>
                    <br>(KB2508964)<span class="sup">[1]</span><br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=b1466366-e2ae-498e-b964-135e034e7348">Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (edições de 64 bits)</a><br>(KB2553001)<span class="sup">[1]</span><br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=bb788c8d-8383-4e53-ac05-2a7dd9b83e70">Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (edições de 64 bits)</a><br>(KB2553002)<span class="sup">[1]</span><br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=e8e1a5bb-a552-45fe-8e81-e05fbfbb57ee">Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (edições de 64 bits)</a><span class="sup">[1]</span><br>(Importante)<br>(KB2553003)</td></tr>
                <tr><td>Microsoft Office SharePoint Server 2010 e Microsoft Office SharePoint Server 2010 Service Pack 1</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=0C150328-6A15-4852-A09C-4063142BD946">Microsoft Excel Services</a>
                    <br>(KB2553094)<br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=c17eb04d-cbbc-457e-a424-4ee26b7a9654">Microsoft Office SharePoint Server 2010 e Microsoft Office SharePoint Server 2010 Service Pack 1 (osrchwfe)</a>
                    <br>(KB2494022)<br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=2a80a849-b712-47d4-9def-9395ee54a265">Microsoft Office SharePoint Server 2010 e Microsoft Office SharePoint Server 2010 Service Pack 1 (osrv)</a><br>(KB2560885)<br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=b84c2bcb-0327-4916-871e-7a5c19b8c41b">Microsoft Office SharePoint Server 2010 e Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe)</a><br>(KB2560890) <br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=1597f295-02a9-4479-9d52-f18f0e83eaba">Microsoft Office SharePoint Server 2010 e Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmawfe)</a><br>(KB2566456)<br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=e6b666a4-a795-441c-9bda-23e2de2e7b05">Microsoft Office SharePoint Server 2010 e Microsoft Office SharePoint Server 2010 Service Pack 1 (dlc)</a><br>(KB2566954)<br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=57592ce4-5d99-45c2-830f-380d67af8899">Microsoft Office SharePoint Server 2010 e Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmamui)</a><br>(KB2566958)<br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=dd64a635-1e55-4b4d-9718-9b94c31c5625">Microsoft Office SharePoint Server 2010 e Microsoft Office SharePoint Server 2010 Service Pack 1 (wosrv)</a><br>(KB2566960)<br>(Importante)</td></tr>              
                <tr class="alternateRow"><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225047"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-072</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=204797"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-074</strong></a>
                  </td></tr>
                <tr><td>
                    <strong>Avaliação de gravidade  agregada</strong>
                  </td><td>Nenhuma</td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Forms Server 2007 Service Pack 2 (edições de 32 bits)</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=c4c8ad7e-50bd-460e-9678-d8c72c6ee7ab">Microsoft Office Forms Server 2007 Service Pack 2 (edições de 32 bits)</a>
                    <br>(KB2553005)<br>(Importante)</td></tr>
                <tr><td>Microsoft Office Forms Server 2007 Service Pack 2 (edições de 64 bits)</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=7390b526-f411-45a4-8587-8077b473ac17">Microsoft Office Forms Server 2007 Service Pack 2 (edições de 64 bits)</a>
                    <br>(KB2553005)<br>(Importante)</td></tr>              
                <tr class="alternateRow"><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225047"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-072</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=204797"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-074</strong></a>
                  </td></tr>
                <tr><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>Nenhuma</td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Groove Data Bridge Server 2007 Service Pack 2</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=5958247e-204e-409c-bdc1-7aff06e854b8">Microsoft Office Groove Data Bridge Server 2007 Service Pack 2</a>
                    <br>(KB2552999)<br>(Importante)</td></tr>
                <tr><td>Microsoft Office Groove Management Server 2007 Service Pack 2</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=6b5b4caf-6a95-487d-ac17-c4435225af3a">Microsoft Office Groove Management Server 2007 Service Pack 2</a>
                    <br>(KB2552998)<br>(Importante)</td></tr>
                <tr class="alternateRow"><td>Microsoft Groove Server 2010 e Microsoft Groove Server 2010 Service Pack 1</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?FamilyId=71c0f217-5112-4dca-b9aa-46c69f6099e4">Microsoft Groove Server 2010 e Microsoft Groove Server 2010 Service Pack 1</a>
                    <br>(KB2508965)<br>(Importante)</td></tr>              
                <tr><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225047"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-072</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=204797"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-074</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr><td>Microsoft Office Web Apps 2010 e Microsoft Office Web Apps 2010 Service Pack 1</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=73D49094-A9CF-407E-8921-1B22FBC30427">Microsoft Excel Web App 2010 e Microsoft Excel Web App 2010 Service Pack 1</a>
                    <br>(KB2553095)<br>(Importante)</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=288a7394-b8d5-4445-bd4c-65bbf4b10eaf">Microsoft Office Web Apps 2010 e Microsoft Office Web Apps 2010 Service Pack 1</a>
                    <br>(KB2566449)<br>(Importante)<br><br><a href="https://www.microsoft.com/downloads/details.aspx?familyid=152ff9f4-d720-41af-8f89-793133ece037">Microsoft Word Web App 2010 e Microsoft Word Web App 2010 Service Pack 1</a><br>(KB2566450)<br>(Importante)</td></tr>              
                <tr class="alternateRow"><td>
                    <strong>Identificador do Boletim</strong>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=225047"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-072</strong></a>
                  </td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=204797"><strong xmlns="http://www.w3.org/1999/xhtml">MS11-074</strong></a>
                  </td></tr>
                <tr><td>
                    <strong>Avaliação de gravidade agregada</strong>
                  </td><td>Nenhuma</td><td>
                    <a href="http://go.microsoft.com/fwlink/?LinkId=21140"><strong xmlns="http://www.w3.org/1999/xhtml">Importante</strong></a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Windows SharePoint Services&nbsp;2.0</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=71e32745-cb05-4b87-a447-741ccdac7450">Microsoft Windows SharePoint Services 2.0</a>
                    <br>(KB2494007)<br>(Importante)</td></tr>
                <tr><td>Microsoft Windows SharePoint Services 3.0 Service Pack 2 (versões de 32 bits)                  </td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=0f306cbd-a652-4e77-b394-1a6dc38ba83c">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (edições de 32 bits)</a>
                    <br>(KB2493987)<br>(Importante)</td></tr>
                <tr class="alternateRow"><td>Microsoft Windows SharePoint Services 3.0 Service Pack 2 (versões de 64 bits)</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=3137e4c6-783d-4461-88bd-90da064e3105">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (edições de 64 bits)</a>
                    <br>(KB2493987)<br>(Importante)</td></tr>
                <tr><td>Microsoft SharePoint Foundation 2010 e Microsoft SharePoint Foundation 2010 Service Pack 1</td><td>Não Aplicável</td><td>
                    <a href="https://www.microsoft.com/downloads/details.aspx?familyid=0db799e2-896f-464b-8cd5-ecf2014f0588">Microsoft SharePoint Foundation 2010 e Microsoft SharePoint Foundation 2010 Service Pack 1</a>
                    <br>(KB2494001)<br>(Importante)</td></tr>
              </tbody></table>
<p></p>

  
**Observações para o boletim MS11-072**
  
<sup>[2]</sup> Esta atualização aplica-se a servidores que tenham os Serviços do Excel instalados, como a configuração padrão do Microsoft Office SharePoint Server 2007 Enterprise e do Microsoft Office SharePoint Server 2007 para sites da Internet. O Microsoft Office SharePoint Server 2007 Standard não inclui os Serviços do Excel.
  
Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.
  
**Observações para o boletim MS11-074**
  
<sup>[1]</sup>Para edições com suporte do Microsoft Office SharePoint Server 2007, além dos pacotes de atualização de segurança para o Microsoft Office SharePoint 2007 (KB2508964, KB2553001, KB2553002 e KB2553003), os clientes também precisam instalar a atualização de segurança para Microsoft Windows SharePoint Services 3.0 (KB2493987) para ficarem protegidos contra as vulnerabilidades descritas neste boletim.
  
Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.
  
Orientação e ferramentas de detecção e implantação  
--------------------------------------------------
  
 
**Central de Segurança**
  
Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://go.microsoft.com/fwlink/?linkid=85102), no qual essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.
  
As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) e no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
  
Para os clientes do Microsoft Office for Mac, o Microsoft AutoUpdate for Mac pode ajudar a manter seu software Microsoft atualizado. Para obter mais informações sobre como usar o Microsoft AutoUpdate for Mac, consulte [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).
  
Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Freqüentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)
  
**Orientação para detecção e implantação**
  
A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o [Artigo 961747 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).
  
**Microsoft Baseline Security Analyzer**
  
O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).
  
**Windows Server Update Services**
  
Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.
  
Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).
  
**System Center Configuration Manager 2007**
  
O gerenciamento de atualizações de software do Configuration Manager 2007 simplifica a complexa tarefa de fornecer e gerenciar atualizações a sistemas de TI pela empresa. Com o Configuration Manager 2007, os administradores de TI podem fornecer atualizações de produtos da Microsoft a uma variedade de dispositivos, inclusive desktops, laptops, servidores e dispositivos móveis.
  
A avaliação automatizada de vulnerabilidade no Configuration Manager 2007 detecta as necessidades de atualizações e relatórios com relação a ações recomendadas. O gerenciamento de atualizações de software no Configuration Manager 2007 é integrado ao Microsoft Windows Software Update Services (WSUS), uma infraestrutura de atualização testada quanto à confiabilidade, que é familiar aos administradores de TI do mundo todo. Para obter mais informações sobre como os administradores podem usar o Configuration Manager 2007 para implantar atualizações, consulte [Gerenciamento de atualizações de software](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Para obter mais informações sobre o Configuration Manager, acesse: [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).
  
**Systems Management Server 2003**
  
O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários.
  
**Observação** O System Management Server 2003 está fora de suporte principal desde 12 de janeiro de 2010. Para obter mais informações sobre ciclos de vida de produtos, acesse [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). A próxima versão do SMS, System Center Configuration Manager 2007, já está disponível; consulte também o **System Center Configuration Manager 2007**.
  
Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, consulte [Cenários e procedimentos para o Microsoft Systems Management Server 2003: Distribuição de software e Gerenciamento de patches](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Para obter informações sobre o SMS, acesse: [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).
  
**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) para instalar essas atualizações.
  
**Avaliador de Compatibilidade com Atualizações e Application Compatibility Toolkit**
  
As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) incluídos no [Kit de ferramentas de compatibilidade de aplicativos](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.
  
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
  
Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do MAPP (Microsoft Active Protections Program)](http://go.microsoft.com/fwlink/?linkid=215201).
  
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
  
A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) à pessoa citada abaixo por trabalhar conosco para ajudar a proteger os clientes:
  
-   Nicolas Economou, da [Core Security Technologies](http://www.coresecurity.com/), por relatar um problema descrito no boletim MS11-070  
-   Um pesquisador anônimo, que trabalha com a [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar um problema descrito no boletim MS11-072.  
-   Sean Larsson, da [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar um problema descrito no boletim MS11-072  
-   Um pesquisador anônimo, que trabalha com a [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar um problema descrito no boletim MS11-072.  
-   Um pesquisador anônimo, que trabalha na [TippingPoint's](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) por relatar um problema descrito no boletim MS11-072  
-   Omair, que trabalha com a [Zero Day Initiative](http://www.tippingpoint.com/)[da TippingPoint](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS11-072  
-   Parvez Anwar, que trabalha na [Secunia Research](http://secunia.com/), por relatar um problema descrito no boletim MS11-073  
-   David Warren, da [CERT/CC](http://www.cert.org/), por relatar um problema descrito no boletim MS11-073  
-   Andrew Connell, da [Critical Path Training, LLC](http://www.criticalpathtraining.com/), por relatar um problema descrito no boletim MS11-074  
-   David Feldman, da [Raytheon](http://www.raytheon.com/), por relatar um problema descrito no boletim MS11-074  
-   Adi Cohen, da [IBM Rational Application Security](http://blog.watchfire.com/), por relatar um problema descrito no boletim MS11-074  
-   [Trend Micro](http://www.trendmicro.com/)  
-   por trabalhar conosco em um problema descrito no boletim MS11-074  
-   Pedro Jimenez, da [ITT](http://www.itt.com/), por relatar um problema descrito no boletim MS11-074  
-   [Investigador de solução de teste de segurança de aplicativo automática por relatar um problema descrito no boletim](http://www.seekersec.com/)  
-   MS11-074  
-   Nicolas Grégoire, da [Agarri,](http://www.agarri.fr/) por relatar um problema descrito no boletim MS11-074  
-   Jim LaValley, da [LaValley Consulting, LLC](http://www.lavalley.net), por relatar um problema descrito no boletim MS11-074  
-   Irene Abezgauz, da [Seeker](http://www.seekersec.com), por trabalhar conosco nas alterações de defesa profunda incluídas no boletim MS11-074
  
#### Suporte
  
-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).  
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do [Suporte de Segurança](http://go.microsoft.com/fwlink/?linkid=21131) ou pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas. Para obter mais informações sobre as opções de suporte disponíveis, consulte [Ajuda e Suporte da Microsoft](http://support.microsoft.com/).  
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).
  
#### Aviso de isenção de responsabilidade
  
As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.
  
#### Revisões
  
-   V1.0 (13 de setembro de 2011): Resumo de boletins publicado.  
-   V1.1 (13 de setembro de 2011): Para o MS11-074, foi adicionado um link de atualização para atualização do Microsoft Office SharePoint Server 2010 e Microsoft Office Server SharePoint 2010 Service Pack 1 (pplwfe) (KB2560890).
  
*Built at 2014-04-18T01:50:00Z-07:00*
