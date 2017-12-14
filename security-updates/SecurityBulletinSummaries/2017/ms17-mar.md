---
TOCTitle: 'MS17-MAR'
Title: Resumo dos boletins de segurança da Microsoft de março de 2017
ms:assetid: 'ms17-mar'
ms:contentKeyID: 74430759
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms17-mar(v=Security.10)'
---

Modelo do MSRC ppDocument

Resumo dos boletins de segurança da Microsoft de março de 2017
==============================================================

Publicado em: 14 de março de 2017 | Atualizada: 8 de agosto de 2017

**Versão:** 4.0

Este resumo de boletins lista os boletins publicados em março de 2017.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft forem lançados, visite [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações**.

Como lembrete, o [Guia de Atualizações de Segurança](https://portal.msrc.microsoft.com/pt-br/security-guidance) substituirá os boletins de segurança. Para obter mais detalhes, consulte nossa postagem de blog, [Furthering our commitment to security updates](https://blogs.technet.microsoft.com/msrc/2016/11/08/furthering-our-commitment-to-security-updates/) (Ampliando nosso compromisso com as atualizações de segurança).

Resumos executivos
------------------

<span id="sectionToggle0"></span>
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os Software afetado, consulte a próxima seção, **Software afetado**.

<p></p>
<table style="width:100%;" style="border:1px solid black;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ID do Boletim</strong></td>
<td style="border:1px solid black;"><strong>Título do boletim e Resumo executivo</strong></td>
<td style="border:1px solid black;"><strong>Classificação máxima de gravidade<br />
e impacto da vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>Requisito de reinicialização</strong></td>
<td style="border:1px solid black;"><strong>Problemas<br />
conhecidos</strong></td>
<td style="border:1px solid black;"><strong>Softwares afetados</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842208">MS17-006</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança Cumulativa para Internet Explorer (4013073)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Internet Explorer. A vulnerabilidade mais grave poderá permitir a execução remota de código se um usuário visualizar uma página da Web especialmente criada usando o Internet Explorer. Um invasor que conseguir explorar essas vulnerabilidades poderá obter os mesmos direitos que o usuário atual. Se o usuário atual estiver conectado com direitos administrativos, o invasor que explorar com êxito essa vulnerabilidade poderá obter o controle total do sistema afetado. O invasor poderá então instalar programas, visualizar, alterar ou excluir dados ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842207">MS17-007</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança Cumulativa para Microsoft Edge (4013071)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Edge. Essas vulnerabilidades poderão permitir a execução remota de código se um usuário visualizar uma página da Web especialmente criada usando o Microsoft Edge. Um invasor que conseguir explorar essas vulnerabilidades poderá adquirir o controle de um sistema afetado. O invasor poderá então instalar programas, visualizar, alterar ou excluir dados ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842215">MS17-008</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para Windows Hyper-V (4013082)<br />
</strong>Essa atualização de segurança resolve vulnerabilidades no Microsoft Windows. A mais grave das vulnerabilidades poderá permitir a execução remota de código se um invasor autenticado em um sistema operacional convidado executar um aplicativo especialmente criado que causa a execução de um código arbitrário pelo sistema operacional do host Hyper-V. Os clientes que não habilitaram a função do Hyper-V não serão afetados.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839436">MS17-009</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para biblioteca de PDF do Microsoft Windows (4010319)<br />
</strong>Essa atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade poderá permitir a execução remota de código se um usuário visualizar um conteúdo em PDF especialmente criado online ou abrir um documento PDF especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=843149">MS17-010</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Microsoft Windows SMB Server (4013389)<br />
</strong>Essa atualização de segurança resolve vulnerabilidades no Microsoft Windows. A mais grave das vulnerabilidades poderá permitir a execução remota de código se um invasor enviar mensagens especialmente criadas para um servidor Microsoft SMBv1 (Server Message Block 1.0).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842211">MS17-011</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Windows Uniscribe (4013076)<br />
</strong>Essa atualização de segurança resolve vulnerabilidades no Windows Uniscribe. A mais grave dessas vulnerabilidades poderá permitir a execução remota de código se um usuário visitar um site especialmente criado ou abrir um documento especialmente criado. Os usuários cujas contas estão configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles com direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842212">MS17-012</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Microsoft Windows (4013078)<br />
</strong>Essa atualização de segurança resolve vulnerabilidades no Microsoft Windows. A mais grave das vulnerabilidades poderá permitir a execução remota de código se um invasor executar um aplicativo especialmente criado que se conecta ao iSNS Server e depois envia solicitações mal-intencionadas a esse servidor.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842210">MS17-013</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o componente de gráficos da Microsoft (4013075)<br />
</strong>Essa atualização de segurança resolve vulnerabilidades no Microsoft Windows, Microsoft Office, Skype for Business, Microsoft Lync e Microsoft Silverlight. A mais grave dessas vulnerabilidades poderá permitir a execução remota de código, se um usuário visitar um site especialmente criado ou abrir um documento especialmente criado. Os usuários cujas contas estão configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles com direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br />
Microsoft Office,<br />
Skype for Business,<br />
Microsoft Lync,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842278">MS17-014</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Microsoft Office (4013241)</strong><br />
Essa atualização de segurança resolve vulnerabilidades no Microsoft Office. A mais grave das vulnerabilidades poderá permitir a execução remota de código se um usuário abrir um arquivo do Microsoft Office especialmente criado. Um invasor que conseguir explorar as vulnerabilidades poderá executar um código arbitrário no contexto do usuário atual. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Serviços do Microsoft Office e Aplicativos Web,<br />
Software para Servidores Microsoft,<br />
Software e Plataformas do Microsoft Communications</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842279">MS17-015</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Microsoft Exchange Server (4013242)<br />
</strong>Essa atualização de segurança resolve uma vulnerabilidade no Microsoft Exchange Outlook Web Access (OWA). A vulnerabilidade poderá permitir a execução remota de código no Exchange Server se um invasor enviar um email com um anexo especialmente criado a um servidor Exchange vulnerável.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842209">MS17-016</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para Windows IIS (4013074)<br />
</strong>Essa atualização de segurança resolve uma vulnerabilidade no IIS (Serviços de Informações da Internet da Microsoft). A vulnerabilidade pode permitir a elevação de privilégio quando um usuário clica em uma URL especialmente criada, hospedada por um servidor IIS da Microsoft afetado. Um invasor que conseguir explorar essa vulnerabilidade poderá executar scripts no navegador do usuário para obter informações das sessões da Web.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842216">MS17-017</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Kernel do Windows (4013081)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. As vulnerabilidades poderão permitir a elevação de privilégios se um invasor executar um aplicativo especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Elevação de Privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842217">MS17-018</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para drivers do modo Kernel do Windows (4013083)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. As vulnerabilidades poderão permitir a elevação de privilégio se um invasor se conectar a um sistema afetado e executar um aplicativo especialmente criado, capaz de explorar as vulnerabilidades e assumir o controle total do sistema afetado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Elevação de Privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839438">MS17-019</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para os Serviços de Federação do Active Directory (4010320)<br />
</strong>Essa atualização de segurança resolve uma vulnerabilidade nos Serviços de Federação do Active Directory (AD FS). A vulnerabilidade poderá permitir a divulgação não autorizada de informações se um invasor enviar uma solicitação especialmente criada a um servidor ADFS, permitindo que esse invasor leia informações confidenciais sobre o sistema de destino.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Divulgação de informações</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=836272">MS17-020</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Criador de DVD do Windows (3208223)<br />
</strong>Essa atualização de segurança resolve uma vulnerabilidade de divulgação não autorizada de informações no Criador de DVD do Windows. A vulnerabilidade pode permitir que um invasor obtenha informações de forma a comprometer ainda mais um sistema de destino.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Divulgação de informações</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839434">MS17-021</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Windows DirectShow (4010318)<br />
</strong>Essa atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade poderá permitir a divulgação não autorizada de informações se o Windows DirectShow abrir um conteúdo de mídia especialmente criado e hospedado em um site mal-intencionado. Um invasor que conseguir explorar a vulnerabilidade poderá obter informações de forma a comprometer ainda mais um sistema de destino.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Divulgação de informações</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839435">MS17-022</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Microsoft XML Core Services (4010321)<br />
</strong>Essa atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade poderá permitir a divulgação não autorizada de informações se um usuário visitar um site mal-intencionado. No entanto, em todos os casos um invasor não teria como forçar um usuário a clicar em um link especialmente criado. Um invasor teria que convencer um usuário a clicar no link, geralmente na forma de um atrativo em um email ou mensagem instantânea.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Divulgação de informações</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=844066">MS17-023</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Adobe Flash Player (</strong>4014329)<br />
Essa atualização de segurança resolve vulnerabilidades no Adobe Flash Player quando instalado em todas as edições com suporte do Windows 8.1, Windows Server 2012, Windows Server 2012 R2, Windows RT 8.1, Windows 10 e Windows Server 2016.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

Índice de exploração
--------------------

<span id="sectionToggle1"></span>
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas por ID do boletim e depois por ID do CVE. Estão incluídas nos boletins somente vulnerabilidades com classificação de gravidade Crítica ou Importante.

**Como devo usar esta tabela?**

Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que significam essas classificações e como elas são determinadas, consulte o [Índice de Exploração da Microsoft](http://technet.microsoft.com/pt-br/security/cc998259).

Nas colunas a seguir, "Versão mais recente de software" se refere ao software e "Versões mais antigas de software" se refere a todas as versões mais antigas do software compatíveis, conforme listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.

<p></p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**ID do CVE**                    
</td>
<td style="border:1px solid black;">
**Título da vulnerabilidade**
</td>
<td style="border:1px solid black;">
**Avaliação da capacidade de exploração da  
última versão de software**
</td>
<td style="border:1px solid black;">
**Avaliação da capacidade de exploração de  
versão mais antiga de software**
</td>
<td style="border:1px solid black;">
**Avaliação do risco de exploração  
para negação de serviço**
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-006: Atualização de segurança cumulativa para o Internet Explorer (4013073)**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0008](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0008)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informação do Internet Explorer
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0009)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no navegador da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0012](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0012)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de falsificação do navegador da Microsoft
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0018](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0018)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0033)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de falsificação do navegador da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0037)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0040](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0040)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0049](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0049)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do mecanismo de script
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0059](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0059)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informação do Internet Explorer
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0130](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0130)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0149](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0149)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer
</td>
<td style="border:1px solid black;">
0 - Exploração detectada
</td>
<td style="border:1px solid black;">
0 - Exploração detectada
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0154](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0154)
</td>
<td style="border:1px solid black;">
Vulnerabilidade na Elevação de Privilégio do Internet Explorer
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-007: Atualização de segurança cumulativa do Microsoft Edge (4013071)**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0009)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no navegador da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0010](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0010)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0011](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0011)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações do Microsoft Edge
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0012](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0012)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de falsificação do navegador da Microsoft
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0015)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0017](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0017)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações do Microsoft Edge
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0023](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0023)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória de PDF da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0032)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0033)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de falsificação do navegador da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0034](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0034)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Edge
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0035](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0035)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0037)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0065](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0065)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações no navegador da Microsoft
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0066](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0066)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de bypass do recurso de segurança do Microsoft Edge
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0067](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0067)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0068](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0068)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações do Microsoft Edge
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0069](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0069)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de falsificação do Microsoft Edge
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0070](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0070)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0071](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0071)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0094](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0094)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0131](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0131)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0132)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0133)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0134](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0134)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0135)
</td>
<td style="border:1px solid black;">
Bypass do recurso de segurança do Microsoft Edge
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0136)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0137](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0137)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0138)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0140](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0140)
</td>
<td style="border:1px solid black;">
Bypass do recurso de segurança do Microsoft Edge
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0141)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0150](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0150)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0151](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0151)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção da memória do mecanismo de script
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-008: Atualização de segurança para o Windows Hyper-V (4013082)**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0021](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0021)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Hyper-V vSMB
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0051](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0051)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço em comutadores de rede com Microsoft Hyper-V
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0074](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0074)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço do Hyper-V
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0075](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0075)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Hyper-V
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0076](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0076)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço do Hyper-V
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0095)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Hyper-V vSMB
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0096](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0096)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações do Hyper-V
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0097](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0097)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço do Hyper-V
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0098](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0098)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço do Hyper-V
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0099)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço do Hyper-V
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0109](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0109)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Hyper-V
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-009: Atualização de segurança para a biblioteca de PDFs do Microsoft Windows (4010319)**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0023](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0023)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória de PDF da Microsoft
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-010: Atualização de segurança para o Microsoft Windows SMB Server (4013389)**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0143](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0143)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Windows SMB
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0144](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0144)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Windows SMB
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0145](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0145)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Windows SMB
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0146](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0146)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Windows SMB
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0147](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0147)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Windows SMB
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0148)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Windows SMB
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-011: Atualização de segurança para o Windows Uniscribe (4013076)**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0072](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0072)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0083](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0083)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0084)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Uniscribe
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0085](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0085)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0086](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0086)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0087)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0088)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0089)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0090](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0090)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0091](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0091)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0092](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0092)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0111](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0111)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0112](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0112)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0113](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0113)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0114)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0115](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0115)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0116](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0116)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0117)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0118)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0119](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0119)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0120](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0120)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0121](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0121)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0122](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0122)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0123](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0123)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0124](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0124)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0125](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0125)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0126](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0125)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0127)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0128](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0128)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Uniscribe
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-012: Atualização de segurança para Microsoft Windows (4013078)**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0007](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0007)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de bypass de recurso de segurança do Device Guard
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0016)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço de desreferência nula do SMBv2/SMBv3
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0039](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0039)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código de carregamento de DLL do Windows
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0057](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0057)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações de consultas DNS do Windows
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0100](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0100)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio de HelpPane do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0104](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0104)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do iSNS Server
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-013: Atualização de segurança para o componente gráfico da Microsoft (4013075)**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0001](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0001)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Windows GDI
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0005](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0005)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Windows GDI
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
0 – Exploração detectada
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0014](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0014)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do GDI+
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0025](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0025)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Windows GDI
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0038](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0038)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações dos componentes gráficos do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0047](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0047)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Windows GDI
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0060)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações de GDI+
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0061)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações de gerenciamento de cores da Microsoft
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0062)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações de GDI+
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0063](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0063)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações de gerenciamento de cores da Microsoft
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0073](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0073)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Windows GDI+
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0108](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0108)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código do componente de gráficos do Windows
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-014: Atualização de segurança para o Microsoft Office (4013241)**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0006](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0006)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0019](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0019)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0020)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0027](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0027)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações do Microsoft Office
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0029)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço no Microsoft Office
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0030](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0030)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0031](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0031)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0052](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0052)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0053](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0053)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0105](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0105)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0107](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0107)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de XSS no Microsoft SharePoint
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0129](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0129)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de validação de certificado do Microsoft Lync for Mac
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-015: Atualização de segurança para o Microsoft Exchange Server (4013242)**](https://go.microsoft.com/fwlink/?linkid=842279)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0110](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0110)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Microsoft Exchange Server
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-016: Atualização de segurança para o Windows IIS (4013074)**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0055](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0055)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio de XSS do Servidor IIS da Microsoft
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-017: Atualização de segurança para kernel do Windows (4013081)**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0050](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0050)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio de kernel do Windows
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0101](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0101)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Windows
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0102](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0102)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Windows
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0103](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0103)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio de Registro do Windows
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-018: Atualização de segurança para drivers de modo Kernel do Windows (4013083)**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0024](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0024)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0026](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0026)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0056](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0056)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0078](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0078)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0079)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0080)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0081](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0081)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0082](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0082)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-019: Atualização de segurança para os Serviços de Federação do Active Directory (4010320)**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0043](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0043)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações nos Serviços de Federação do Active Directory da Microsoft
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Temporário
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-020: Atualização de segurança para o Criador de DVD do Windows (3208223)**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0045](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0045)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de solicitação intersite forjada do Criador de DVD do Windows
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-021: Atualização de segurança para Windows DirectShow (4010318)**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0042](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0042)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Windows DirectShow
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-022: Atualização de segurança para Microsoft XML Core Services (4010321)**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0022](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0022)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Microsoft XML Core Services
</td>
<td style="border:1px solid black;">
0 - Exploração detectada
</td>
<td style="border:1px solid black;">
0 - Exploração detectada
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-023: Atualização de segurança para o Adobe Flash Player (4014329)**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB17-07](http://helpx.adobe.com/br/security/products/flash-player/apsb17-07.html)
</td>
<td style="border:1px solid black;">
Consulte o Boletim de segurança da Adobe [APSB17-07](http://helpx.adobe.com/br/security/products/flash-player/apsb17-07.html) para ver classificações de prioridade da atualização e de gravidade da vulnerabilidade
</td>
<td style="border:1px solid black;">
---------
</td>
<td style="border:1px solid black;">
---------
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
</table>
 

Softwares afetados
------------------

<span id="sectionToggle2"></span>
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.

Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.

**Observação** Talvez seja necessário instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.

### Sistemas operacionais do Windows e componentes (Tabela 1 de 2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
**Nenhuma**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(Crítica)  
API do Microsoft Internet Messaging  
(3218362)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4012598)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4012583)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3217587)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4017018)  
(Crítica)  
Windows Vista Service Pack 2  
(4012584)  
(Importante)  
Windows Vista Service Pack 2  
(4012497)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(Crítica)  
API do Microsoft Internet Messaging  
(3218362)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3211306)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012598)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012583)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3217587)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4017018)  
(Crítica)  
Windows Vista x64 Edition Service Pack 2  
(4012584)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(4012497)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(Moderada)  
API do Microsoft Internet Messaging  
(3218362)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(4012598)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(4012583)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3217587)  
(Importante)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(4012021)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(4017018)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(4012584)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(4012497)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(Moderada)  
API do Microsoft Internet Messaging  
(3218362)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(3211306)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(4012598)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(4012583)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(3217587)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(4012021)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(4017018)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(4012584)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(4012497)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(4012598)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(4012583)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3217587)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(4017018)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(4012584)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(4012497)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
**Nenhuma**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
Apenas segurança
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012212)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012215)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
Apenas segurança
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
Apenas segurança
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
Apenas segurança
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012212)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012215)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
Apenas segurança
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012213)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012216)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
Apenas segurança
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 e Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Nenhuma**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
Apenas segurança
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4012204)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4012217)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
Apenas segurança
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(Crítico)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012606)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025338)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(4012606)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(4012606)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(4012606)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012606)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025338)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(4012606)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64  
(4012606)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64  
(4012606)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64  
(4012606)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013198)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025344)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(4013198)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(4013198)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(4013198)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013198)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025344)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(4013198)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64  
(4013198)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64  
(4013198)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64  
(4013198)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025339)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(4013429)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025339)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas baseados em x64  
(4013429)  
(Crítico)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64  
(4013429)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1703 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025342)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1703 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025342)  
(Crítico)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
(Moderada)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4013429)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Opção de instalação Server Core**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)
</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)
</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)
</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)
</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)
</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)
</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
**Nenhuma**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(4012598)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(4012583)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3217587)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(4017018)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(4012584)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(4012497)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(3211306)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(4012598)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(4012583)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(3217587)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(4017018)  
(Crítica)  
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(4012584)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(4012497)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(instalação Server Core)  
Apenas segurança
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012212)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012212)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(instalação Server Core)  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012215)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012215)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
Apenas segurança
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012214)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012214)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012214)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012214)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012217)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012217)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
Apenas segurança
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012213)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012213)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012216)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012216)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)  
(4013429)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)  
(4013429)  
(Crítica)
</td>
</tr>
</table>
 
**Observação para o MS17-013**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nesta seção para obter informações adicionais sobre softwares afetados.

 

### Sistemas operacionais Windows e componentes (Tabela 2 de 2)

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4012373)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4011981)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4012497)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3205715)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3214051)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012373)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4011981)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012497)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3205715)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3214051)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Windows Server 2008 Service Pack 2 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(4012373)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(4011981)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(4012497)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3217882)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3214051)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(4012373)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(4011981)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(4012497)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(3217882)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(3214051)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(4012373)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(4011981)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(4012497)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3217882)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3214051)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 e Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4015548)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4015551)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012606)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013198)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1703 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1703 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Opção de instalação Server Core**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)
</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)
</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)
</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)
</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)
</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)
</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)
</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(4012373)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(4011981)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(4012497)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(4012373)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(4011981)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas com base em x64 (instalação Server Core)  
(4012497)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(instalação Server Core)  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64  
(instalação Server Core)  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas com base em x64 (instalação Server Core)  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012214)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0)  
(4012217)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
Apenas segurança
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64  
(instalação Server Core)  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
</table>
 
 

### Microsoft Office Suites e software

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3127945)  
(Crítica)  
Microsoft Office 2007 Service Pack 3  
(3141535)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3178676)  
(Importante)  
Microsoft Word 2007 Service Pack 3  
(3178683)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(3127958)  
(Crítica)  
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(3178688)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(3178686)  
(Importante)  
Microsoft Excel 2010 Service Pack 2 (edições de 32 bits)  
(3178690)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 32 bits)  
(3178687)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(3127958)  
(Crítica)  
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(3178688)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(3178686)  
(Importante)  
Microsoft Excel 2010 Service Pack 2 (edições de 64 bits)  
(3178690)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 64 bits)  
(3178687)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (edições de 32 bits)  
(3172542)  
(Importante)  
Microsoft Word 2013 Service Pack 1 (edições de 32 bits)  
(3172464)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (edições de 64 bits)  
(3172542)  
(Importante)  
Microsoft Word 2013 Service Pack 1 (edições de 64 bits)  
(3172464)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Office 2013 RT Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3172542)  
(Importante)  
Microsoft Word 2013 RT Service Pack 1  
(3172464)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Office 2016 (edição de 32 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (edição de 32 bits)  
(3178673)  
(Importante)  
Microsoft Word 2016 (edição de 32 bits)  
(3178674)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 64 bits)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (edição de 64 bits)  
(3178673)  
(Importante)  
Microsoft Word 2016 (edição de 64 bits)  
(3178674)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office para Mac 2011**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Office para Mac 2011
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Excel para Mac 2011  
(3198809)  
(Importante)  
Microsoft Excel para Mac 2011  
(3212218)  
(Importante)  
Microsoft Word para Mac 2011  
(3198809)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016 para Mac**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Office 2016 para Mac
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft Office 2016 para Mac  
(Importante)  
Microsoft Excel 2016 para Mac  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Outros softwares do Office**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Pacote de Compatibilidade do Microsoft Office Service Pack 3  
(3178677)  
(Importante)  
Pacote de Compatibilidade do Microsoft Office Service Pack 3  
(3178682)  
(Importante)
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
Microsoft Excel Viewer  
(3178680)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3178693)  
(Crítica)  
Microsoft Word Viewer  
(3178653)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3178694)  
(Importante)
</td>
</tr>
</table>
 
**Observação para o MS17-013 e o MS17-014**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nesta seção para obter informações adicionais sobre softwares afetados.

 

### Microsoft Office Services e Web Apps

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Serviços do Excel (edição de 32 bits)  
(3178678)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Serviços do Excel (edição de 64 bits)  
(3178678)  
(Importante)
</td>
</tr>
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Serviços do Excel  
(3178685)  
(Importante)  
Serviços de Automação do Word  
(3178684)  
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Serviços do Excel  
(3172431)  
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3178689)  
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3172457)  
(Importante)
</td>
</tr>
</table>
 
**Observação para o MS17-014**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nesta seção para obter informações adicionais sobre softwares afetados.

 

### Microsoft Server Software

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft SharePoint Foundation 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3172540)  
(Importante)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Exchange Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(4012178)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Atualização cumulativa 14 do Microsoft Exchange Server 2013
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Atualização cumulativa 14 do Microsoft Exchange Server 2013  
(4012178)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Atualização cumulativa 3 do Microsoft Exchange Server 2016
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Atualização cumulativa 3 do Microsoft Exchange Server 2016  
(4012178)  
(Importante)
</td>
</tr>
</table>
 
**Observação para o MS17-014 e o MS17-015**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nesta seção para obter informações adicionais sobre softwares afetados.

 

### Software e Plataformas do Microsoft Communications

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Skype for Business 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Skype for Business 2016 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Skype for Business 2016 (edições de 32 bits)  
(3178656)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (edições de 32 bits)  
(3178656)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Skype for Business 2016 (edições de 64 bits)  
(3178656)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (edições de 64 bits)  
(3178656)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Lync 2013 Service Pack 1 (32 bits)  
(Skype for Business)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 bits)  
(Skype for Business)  
(3172539)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 bits)  
(Skype for Business Basic)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 bits)  
(Skype for Business Basic)  
(3172539)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 bits)  
(Skype for Business)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 bits)  
(Skype for Business)  
(3172539)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 bits)  
(Skype for Business Basic)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 bits)  
(Skype for Business Basic)  
(3172539)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Lync 2010 (32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 bits)  
(4010299)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 bits)  
(4010299)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(instalação em nível de usuário)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(instalação de nível de usuário)  
(4010300)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(instalação de nível administrativo)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(instalação de nível de administrador)  
(4010301)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 Console**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Live Meeting 2007 Console
</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(4010303)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Suplemento do Microsoft Live Meeting 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Suplemento do Microsoft Live Meeting 2007
</td>
<td style="border:1px solid black;">
Suplemento do Microsoft Live Meeting 2007  
(4010304)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync for Mac**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
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
Microsoft Lync for Mac 2011
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
<td style="border:1px solid black;">
Microsoft Lync for Mac 2011  
(4012487)  
(Importante)
</td>
</tr>
</table>
 
**Observação para o MS17-013 e o MS17-014**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nesta seção para obter informações adicionais sobre softwares afetados.

 

### Ferramentas e softwares para desenvolvedores Microsoft

<p></p> 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de clientes Microsoft Windows
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de clientes Microsoft Windows  
(4013867)  
**(**Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime quando instalado em todas as versões com suporte de clientes Microsoft Windows
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime quando instalado em todas as versões com suporte de clientes Microsoft Windows  
(4013867)  
**(**Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de servidores Microsoft Windows
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 quando instalado em todas as versões com suporte de servidores Microsoft Windows  
(4013867)  
**(**Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime quando instalado em todas as versões com suporte de servidores Microsoft Windows
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime quando instalado em todas as versões com suporte de servidores Microsoft Windows  
(4013867)  
**(**Crítica)
</td>
</tr>
</table>
 
**Observação para o MS17-013**

Este boletim abrange mais de uma categoria de software. Consulte outras tabelas nesta seção para obter informações adicionais sobre softwares afetados.

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

<span id="sectionToggle3"></span>
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O MBSA (Microsoft Baseline Security Analyzer) permite que os administradores verifiquem, em sistemas locais e remotos, se há atualizações de segurança ausentes e erros comuns de configuração de segurança.

O WSUS (Windows Server Update Services), SMS (Systems Management Server) e SCCM (System Center Configuration Manager) ajudam os administradores a distribuir as atualizações de segurança.

Os componentes do Avaliador de Compatibilidade de Atualizações, incluídos no Kit de Ferramentas de Compatibilidade de Aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para obter mais informações sobre essas e outras ferramentas disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/pt-br/security/cc297183). 

Agradecimentos
--------------

<span id="sectionToggle4"></span>
A Microsoft reconhece os esforços dos membros da comunidade de segurança que nos ajudam a proteger os consumidores graças à divulgação responsável de vulnerabilidades. Consulte [Agradecimentos](https://technet.microsoft.com/pt-br/library/security/mt745121.aspx) para obter mais informações.

Outras informações
------------------

<span id="sectionToggle5"></span>
### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

Em relação ao lançamento de boletins que ocorre na segunda terça-feira do mês, a Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows no Windows Update, Microsoft Update, Windows Server Update Services e Centro de Download. Nenhuma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows está disponível para os lançamentos de boletins de segurança desvinculados.

### Atualizações não relacionadas à segurança no MU, WU e WSUS

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 da Base de Dados de Conhecimento da Microsoft](https://support.microsoft.com/pt-br/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/pt-br/wsus/bb456965). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões com base em rede ou sistemas de prevenção de invasões com base em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://go.microsoft.com/fwlink/?linkid=215201).

### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [artigo 913086 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e otimizar a infraestrutura de TI e participe de discussões sobre tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida de suporte para sua versão de software, visite o site [Ciclo de vida de suporte da Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).

Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança do TechNet](http://technet.microsoft.com/pt-br/security/bb980617)

Ajuda a proteger seu computador executando o Windows contra vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/pt-br/contactus/cu_sc_virsec_master)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/pt-br/common/international.aspx)

### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Dados de Conhecimento Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (14 de março de 2017): Resumo do boletim publicado.
-   V2.0 (11 de abril de 2017): Resumo de boletins revisado para anunciar as seguintes atualizações:
    -   Para MS17-013, o lançamento da atualização 4017018 para Windows Vista e Windows Server 2008. A atualização substitui a atualização 4012583 apenas para a CVE-2017-0038, para lidar amplamente com a vulnerabilidade. A Microsoft recomenda que os clientes que executam o software afetado instalem a atualização de segurança para se protegerem completamente contra a vulnerabilidade descrita neste boletim. Consulte o [artigo 4017018 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/4017018) para obter mais informações.
    -   Para MS17-014, para lidar amplamente com a CVE-2017-0027 apenas para o Office para Mac 2011, a Microsoft está lançando a atualização de segurança 3212218. A Microsoft recomenda que os clientes que executam o Office para Mac 2011 instalem a atualização 3212218 para serem totalmente protegidos contra essa vulnerabilidade. Consulte o [artigo 3212218 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/3212218) para obter mais informações.
    -   Para MS17-021, as atualizações de segurança aplicáveis à CVE-2017-0042 para o Windows Server 2012 estão disponíveis agora. Os clientes que executam o Windows Server 2012 devem instalar a atualização 4015548 (Apenas Segurança) ou 4015551 (Pacote Cumulativo Mensal) para ficarem totalmente protegidos contra essa vulnerabilidade. Os clientes que executam outras versões do Microsoft Windows não precisam tomar nenhuma medida adicional.
-   V2.1 (14 de abril2017) CVE-2017-0022 revisada para atualizar o Índice de exploração para 0 - Exploração detectada. Esta é apenas uma alteração informativa.
-   V3.0 (9 de maio de 2017): Para a MS17-013, a Microsoft voltou a lançar a atualização de segurança 4017018 para as edições afetadas do Windows Server 2008. Esse novo lançamento foi reclassificado como uma atualização de segurança. A Microsoft recomenda que os clientes instalem a atualização 4017018 para ficarem totalmente protegidos contra a CVE-2017-0038. Não há mais nenhuma ação para os clientes que já instalaram esta atualização.
-   V4.0 (8 de agosto de 2017): Para MS17-007, para abordar o CVE-2017-0071 de maneira abrangente, a Microsoft lançou as atualizações de segurança de julho para todas as versões do Windows 10. Observe que o Windows 10 para sistemas de 32 bits, o Windows 10 para sistemas baseados em x64, o Windows 10 Versão 1703 para sistemas de 32 bits e o Windows 10 Versão 1703 para sistemas baseados em x64 foram adicionados à tabela de Produtos Afetados, pois também são afetados por essa vulnerabilidade. A Microsoft recomenda que os clientes que ainda não fizeram isso instalem as atualizações de segurança de julho de 2017 para ficarem totalmente protegidos contra essa vulnerabilidade.

*Página gerada em 2017-08-02 12:34-07:00.*
