---
TOCTitle: 'MS16-FEB'
Title: Resumo do Boletim de Segurança da Microsoft para fevereiro de 2016
ms:assetid: 'ms16-feb'
ms:contentKeyID: 72239060
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms16-feb(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft para fevereiro de 2016
==================================================================

Publicado em: 9 de fevereiro de 2016 | Atualizado em: 24 de fevereiro de 2016

**Versão:** 3.1

Este resumo do boletim lista boletins de segurança lançados em fevereiro de 2016.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft forem emitidos, visite [Notificações de Segurança Técnica da Microsoft](http://technet.microsoft.com/pt-br/security/dd252948.aspx).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

Sinopse
-------

 
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados**.
<p></p>
<p></p>

<table style="width:100%;">
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
<td style="border:1px solid black;"><strong>Título do boletim e Sinopse</strong></td>
<td style="border:1px solid black;"><strong>Classificação Máxima de Severidade<br />
e Impacto da Vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>Requisito de reinicialização</strong></td>
<td style="border:1px solid black;"><strong>Problemas<br />
Conhecidos</strong></td>
<td style="border:1px solid black;"><strong>Softwares Afetados</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-009">MS16-009</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança Cumulativa para o Internet Explorer (3134220)</strong> <br />
Esta atualização de segurança resolve vulnerabilidades no Internet Explorer. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário visualizar uma página da Web criada especialmente usando o Internet Explorer. O atacante que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Se o usuário atual estiver conectado com direitos administrativos, o atacante que explorar com êxito essa vulnerabilidade poderá obter o controle total do sistema afetado. O atacante poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/pt-br/kb/3134814">3134814</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-011">MS16-011</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa do Microsoft Edge (3134225) <br />
</strong>Esta atualização de segurança elimina vulnerabilidades no Microsoft Edge. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário visualizar uma página da Web criada especialmente usando o Microsoft Edge. O atacante que explorar com êxito as vulnerabilidades poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-012">MS16-012</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para a biblioteca de PDF do Microsoft Windows para abordar a execução remota de código (3138938) <br />
</strong>Esta atualização de segurança elimina vulnerabilidades no Microsoft Windows. A mais grave das vulnerabilidades pode permitir a execução remota de código, se a biblioteca de PDF do Microsoft Windows lidar de maneira inadequada com as chamadas da API (Interface de Programação de Aplicativo), o que poderia permitir que um atacante executasse código arbitrário no sistema do usuário. O atacante que explorar com êxito as vulnerabilidades poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. No entanto, um atacante não teria como forçar os usuários a baixar ou abrir um documento PDF malicioso.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-013">MS16-013</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Diário do Windows para abordar a execução remota de código (3134811)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário abrir um arquivo de Diário especialmente criado. Os usuários cujas contas estão configuradas para ter menos direitos de usuário podem ser menos afetados do que os usuários que têm direitos de administrador.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-014">MS16-014</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Microsoft Windows para corrigir execução remota de código (3134228)</strong><br />
Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. A mais grave destas vulnerabilidades poderá permitir a execução remota de código se um atacante conseguir iniciar sessão em um sistema de destino e executar um aplicativo especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/pt-br/kb/3126041">3126041</a><br />
<a href="https://support.microsoft.com/pt-br/kb/3126587">3126587</a><br />
<a href="https://support.microsoft.com/pt-br/kb/3126593">3126593</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-015">MS16-015</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Microsoft Office para corrigir execução remota de código (3134226)</strong><br />
Esta atualização de segurança elimina vulnerabilidades no Microsoft Office. A mais grave das vulnerabilidades pode permitir a Execução remota de código se um usuário abrir um arquivo do Microsoft Office especialmente criado. Um atacante que tenha conseguido explorar as vulnerabilidades pode executar um código arbitrário no contexto do usuário atual. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office, <br />
Microsoft Office Services e Web Apps,<br />
Microsoft Server Software </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-016">MS16-016</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança do WebDAV para abordar elevação de privilégio (3136041)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um atacante usa o cliente Microsoft Web Distributed Authoring and Versioning (WebDAV) para enviar entrada especialmente criada para um servidor.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-017">MS16-017</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para driver de exibição da área de trabalho remota para abordar elevação de privilégio (3134700)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um atacante autenticado faz logon no sistema alvo usando RDP e envia dados especialmente criados através da conexão. Por padrão, o RDP não está habilitado em nenhum sistema operacional Windows. Sistemas que não têm o RDP habilitado não correm risco.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/pt-br/kb/3134700">3134700</a><br />
<a href="https://support.microsoft.com/pt-br/kb/3126446">3126446</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-018">MS16-018</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança dos drivers de modo kernel do Windows para corrigir elevação de privilégio (3136082)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A mais severa destas vulnerabilidades poderá permitir a elevação de privilégio se um atacante se conectar a um sistema afetado e executar um aplicativo especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-019">MS16-019</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança do .NET Framework para abordar negação de serviço (3137893) <br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Microsoft .NET Framework. A mais grave das vulnerabilidades pode causar negação de serviço se um atacante insere XSLT especialmente criado em uma web part XML do lado do cliente, fazendo com que o servidor compile de forma recursiva transformações XSLT.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-020">MS16-020</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para Serviços de Federação do Active Directory para abordar negação de serviço (3134222)<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade nos Serviços de Federação do Active Directory (ADFS). A vulnerabilidade pode permitir negação de serviço se um atacante envia determinados dados de entrada durante autenticação baseada em formulários para um servidor do ADFS, fazendo com o que servidor pare de responder.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-021">MS16-021</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança do servidor NPS RADIUS para abordar negação de serviço (3133043) <br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode causar negação de serviço em um NPS (Servidor de Políticas de Rede) se um atacante envia cadeias de caracteres de nome de usuário especialmente criadas para o NPS, o que poderia evitar a autenticação RADIUS no NPS.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms16-022">MS16-022</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Adobe Flash Player (3135782)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Adobe Flash Player, quando instalado em todas as edições com suporte do Windows Server 2012, do Windows 8.1, do Windows Server 2012 R2, do Windows RT 8.1 e do Windows 10.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>

<p></p>

 

Índice de exploração
--------------------

 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidade são listadas em ordem de ID do boletim, depois de ID do CVE. Só serão incluídas as vulnerabilidades que tiverem uma classificação de gravidade Crítica ou Importante nos boletins.

**Como devo usar a tabela?**  

Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Índice de Exploração da Microsoft](http://technet.microsoft.com/pt-br/security/cc998259).

Nas colunas a seguir, "Versão Mais Recente de Software" se refere ao software, e "Versões Mais Antigas de Software" se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares Afetados" e "Softwares não afetados" do boletim.

<p></p> 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**ID do CVE**                    
</td>
<td style="border:1px solid black;">
**Título da vulnerabilidade**
</td>
<td style="border:1px solid black;" colspan="2">
**Avaliação de exploração para  
Versão de software mais recente**
</td>
<td style="border:1px solid black;">
**Avaliação de exploração para  
Versão de software mais antiga**
</td>
<td style="border:1px solid black;">
**Negação de Serviço  
Avaliação de exploração**
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-009: Atualização de segurança cumulativa para o Internet Explorer (3134220)**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0041](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código de carregamento de DLL
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0059](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0059)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informação do Internet Explorer
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0063](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0063)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0064](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0064)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0067](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0067)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0068](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0068)
</td>
<td style="border:1px solid black;">
Vulnerabilidade na Elevação de Privilégio do Internet Explorer
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0069](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0069)
</td>
<td style="border:1px solid black;">
Vulnerabilidade na Elevação de Privilégio do Internet Explorer
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0071](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0071)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0072](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0072)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de falsificação do Microsoft Browser
</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-011: Atualização de segurança cumulativa do Microsoft Edge (3134225)**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do navegador da Microsoft
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de falsificação do Microsoft Browser
</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0080)
</td>
<td style="border:1px solid black;">
Bypass de ASLR do Microsoft Edge
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0084)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Edge
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-012: Atualização de segurança para a biblioteca de PDF do Microsoft Windows para abordar a execução remota de código (3138938) **](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0046](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0046)
</td>
<td style="border:1px solid black;">
Vulnerabilidade do Leitor do Microsoft Windows
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0058](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0058)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de estouro de buffer da biblioteca de PDF da Microsoft
</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-013: Atualização de segurança para o Diário do Windows para abordar a execução remota de código (3134811)**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0038](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0038)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Diário do Windows
</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-014: Atualização de segurança para o Microsoft Windows para corrigir execução remota de código (3134228)**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0040](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0040)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Windows
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0041](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código de carregamento de DLL
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0042](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0042)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código de carregamento de DLL do Windows
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0044](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0044)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço de carregamento DLL no Windows
</td>
<td style="border:1px solid black;" colspan="2">
4- Não afetado
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
[CVE-2016-0049](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0049)
</td>
<td style="border:1px solid black;">
Desvio de Recurso de Segurança do Kerberos do Windows
</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-015: Atualização de segurança para o Microsoft Office para corrigir execução remota de código (3134226)**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0022](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0022)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0039](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0039)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de XSS no Microsoft SharePoint
</td>
<td style="border:1px solid black;">
3 - Exploração improvável
</td>
<td style="border:1px solid black;" colspan="2">
4- Não afetado
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0052](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0052)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0053](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0053)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0054](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0054)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0055](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0055)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0056](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0056)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Microsoft Office
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-016: Atualização de segurança do WebDAV para abordar elevação de privilégio (3136041)**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0051](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0051)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do WebDAV
</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
2 - Probabilidade menor de exploração
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-017: Atualização de segurança para driver de exibição da área de trabalho remota para abordar elevação de privilégio (3134700)**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0036](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0036)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio para protocolo RDP
</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-018: Atualização de segurança dos drivers de modo kernel do Windows para corrigir elevação de privilégio (3136082)**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0048](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0048)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio do Win32k
</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-019: Atualização de segurança do .NET Framework para abordar negação de serviço (3137893)**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0033)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço de excedente de pilha do. NET Framework
</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0047](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0047)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação de informações de formulários do Windows
</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-020: Atualização de segurança para Serviços de Federação do Active Directory para abordar negação de serviço (3134222)**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0037)
</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviço de Serviços de Federação do Microsoft Active Directory
</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável
</td>
<td style="border:1px solid black;">
4- Não afetado
</td>
<td style="border:1px solid black;">
Permanente
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-021: Atualização de segurança do servidor NPS RADIUS para abordar negação de serviço (3133043)**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0050](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0050)
</td>
<td style="border:1px solid black;">
Vulnerabilidade da negação de serviço da implementação do Network Policy Server RADIUS
</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-022: Atualização de segurança para o Adobe Flash Player (3135782)**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-04](https://helpx.adobe.com/br/security/products/flash-player/apsb16-04.html)
</td>
<td style="border:1px solid black;">
Consulte o [Boletim de segurança da Adobe APSB16-04](https://helpx.adobe.com/br/security/products/flash-player/apsb16-04.html) para classificações da prioridade da atualização e gravidade da vulnerabilidade.
</td>
<td style="border:1px solid black;" colspan="2">
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

 

Softwares Afetados
------------------

 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.

Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.

**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.

 

### Sistemas operacionais do Windows e componentes (Tabela 1 de 2)

<p></p> 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3126587)  
(Importante)  
Windows Vista Service Pack 2  
(3126593)  
(Importante)  
Windows Vista Service Pack 2  
(3126041)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3124280)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3126587)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(3126593)  
(Importante)  
Windows Vista x64 Edition Service Pack 2  
(3126041)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3124280)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3126587)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3126593)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3126041)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3124280)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3126587)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3126593)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3126041)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3124280)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(Moderado)
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
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3126587)  
(Importante)  
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3126593)  
(Importante)  
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3126041)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3126587)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(3126593)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3124280)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3126587)  
(Importante)  
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3126593)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3124280)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3126587)  
(Importante)  
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3126593)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3124280)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(Moderado)
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
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3126587)  
(Importante)  
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3126593)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8,1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3123294)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3126587)  
(Importante)  
Windows 8.1 para sistemas de 32 bits  
(3126593)  
(Importante)  
Windows 8.1 para sistemas de 32 bits  
(3126041)  
(Importante)  
Windows 8.1 para sistemas de 32 bits  
(3126434)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3124280)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3123294)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3126587)  
(Importante)  
Windows 8.1 para sistemas baseados em x64  
(3126593)  
(Importante)  
Windows 8.1 para sistemas baseados em x64  
(3126041)  
(Importante)  
Windows 8.1 para sistemas baseados em x64  
(3126434)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3124280)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 e Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3134814)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3123294)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3126587)  
(Importante)  
Windows Server 2012  
(3126593)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3124280)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(Moderado)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3123294)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3115858)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126587)  
(Importante)  
Windows Server 2012 R2  
(3126593)  
(Importante)  
Windows Server 2012 R2  
(3126041)  
(Importante)  
Windows Server 2012 R2  
(3126434)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3124280)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
Windows RT 8.1  
(3126587)  
(Importante)  
Windows RT 8.1  
(3126593)  
(Importante)  
Windows RT 8.1  
(3126434)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3124280)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3135174)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3135174)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3135174)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3135174)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3135174)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3135174)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3135174)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3135174)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3135173)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3135173)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3135173)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3135173)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3135173)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3135173)  
(Moderado)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Opção de instalação Server Core**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-009**](https://technet.microsoft.com/pt-br/library/security/ms16-009)
</td>
<td style="border:1px solid black;">
[**MS16-011**](https://technet.microsoft.com/pt-br/library/security/ms16-011)
</td>
<td style="border:1px solid black;">
[**MS16-012**](https://technet.microsoft.com/pt-br/library/security/ms16-012)
</td>
<td style="border:1px solid black;">
[**MS16-013**](https://technet.microsoft.com/pt-br/library/security/ms16-013)
</td>
<td style="border:1px solid black;">
[**MS16-014**](https://technet.microsoft.com/pt-br/library/security/ms16-014)
</td>
<td style="border:1px solid black;">
[**MS16-016**](https://technet.microsoft.com/pt-br/library/security/ms16-016)
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
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
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
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3126587)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3126593)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3126041)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)
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
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3126587)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3126593)  
(Importante)  
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3126041)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)
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
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3126587)  
(Importante)  
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3126593)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)
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
Windows Server 2012 (instalação Server Core)  
(3126587)  
(Importante)  
Windows Server 2012 (instalação Server Core)  
(3126593)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
(3123294)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3126587)  
(Importante)  
Windows Server 2012 R2 (instalação Server Core)  
(3126593)  
(Importante)  
Windows Server 2012 R2 (instalação Server Core)  
(3126041)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
 

### Sistemas operacionais do Windows e componentes (Tabela 2 de 2)

<p></p> 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
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
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2,0 Service Pack 2  
(3122646)  
(Importante)  
Microsoft .NET Framework 2,0 Service Pack 2  
(3127219)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(Importante)  
Microsoft .NET Framework 4.6  
(3122661)  
(Importante)  
Microsoft .NET Framework 4.6  
(3127233)  
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
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2,0 Service Pack 2  
(3122646)  
(Importante)  
Microsoft .NET Framework 2,0 Service Pack 2  
(3127219)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(Importante)  
Microsoft .NET Framework 4.6  
(3122661)  
(Importante)  
Microsoft .NET Framework 4.6  
(3127233)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2,0 Service Pack 2  
(3122646)  
(Importante)  
Microsoft .NET Framework 2,0 Service Pack 2  
(3127219)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(Importante)  
Microsoft .NET Framework 4.6  
(3122661)  
(Importante)  
Microsoft .NET Framework 4.6  
(3127233)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2,0 Service Pack 2  
(3122646)  
(Importante)  
Microsoft .NET Framework 2,0 Service Pack 2  
(3127219)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(Importante)  
Microsoft .NET Framework 4.6  
(3122661)  
(Importante)  
Microsoft .NET Framework 4.6  
(3127233)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2,0 Service Pack 2  
(3122646)  
(Importante)  
Microsoft .NET Framework 2,0 Service Pack 2  
(3127219)  
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
<td style="border:1px solid black;" colspan="7">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
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
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3126446)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
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
Windows 7 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3126446)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(3127220)  
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
<td style="border:1px solid black;" colspan="7">
**Windows 8,1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3126446)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3122651)  
(Importante)  
Microsoft .NET Framework 3,5  
(3127222)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3126446)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3122651)  
(Importante)  
Microsoft .NET Framework 3,5  
(3127222)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 e Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3126446)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3122649)  
(Importante)  
Microsoft .NET Framework 3,5  
(3127221)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122655)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127227)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126446)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3122651)  
(Importante)  
Microsoft .NET Framework 3,5  
(3127222)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(Importante)
</td>
<td style="border:1px solid black;">
Serviços de Federação do Active Directory 3,0  
(3134222)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3122654)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3135174)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3135174)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3135174)  
(Importante)  
Microsoft .NET Framework 4.6  
(3135174)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3135174)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3135174)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3135174)  
(Importante)  
Microsoft .NET Framework 4.6  
(3135174)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits  
(3135173)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3135173)  
(Importante)  
Microsoft .NET Framework 4.6.1  
(3135173)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas baseados em x64  
(3135173)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3135173)  
(Importante)  
Microsoft .NET Framework 4.6.1  
(3135173)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3135782)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Opção de instalação Server Core**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-017**](https://technet.microsoft.com/pt-br/library/security/ms16-017)
</td>
<td style="border:1px solid black;">
[**MS16-018**](https://technet.microsoft.com/pt-br/library/security/ms16-018)
</td>
<td style="border:1px solid black;">
[**MS16-019**](https://technet.microsoft.com/pt-br/library/security/ms16-019)
</td>
<td style="border:1px solid black;">
[**MS16-020**](https://technet.microsoft.com/pt-br/library/security/ms16-020)
</td>
<td style="border:1px solid black;">
[**MS16-021**](https://technet.microsoft.com/pt-br/library/security/ms16-021)
</td>
<td style="border:1px solid black;">
[**MS16-022**](https://technet.microsoft.com/pt-br/library/security/ms16-022)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(instalação Server Core)  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(instalação Server Core)  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(instalação Server Core)  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3126446)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3122649)  
(Importante)  
Microsoft .NET Framework 3,5  
(3127221)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122655)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127227)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(instalação Server Core)  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3126446)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
(3134214)  
(Importante)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(3122651)  
(Importante)  
Microsoft .NET Framework 3,5  
(3127222)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(Importante)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(Importante)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(Importante)
</td>
<td style="border:1px solid black;">
Serviços de Federação do Active Directory 3,0  
(3134222)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(instalação Server Core)  
(3133043)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
 

### Microsoft Office Suites e software

<p></p> 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3114742)  
(Importante)  
Microsoft Excel 2007 Service Pack 3  
(3114741)  
(Importante)  
Microsoft Word 2007 Service Pack 3  
(3114748)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(3114752)  
(Importante)  
Microsoft Excel 2010 Service Pack 2 (edições de 32 bits)  
(3114759)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 32 bits)  
(3114755)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(3114752)  
(Importante)  
Microsoft Excel 2010 Service Pack 2 (edições de 64 bits)  
(3114759)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 64 bits)  
(3114755)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (edições de 32 bits)  
(3114734)  
(Importante)  
Microsoft Word 2013 Service Pack 1 (edições de 32 bits)  
(3114724)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (edições de 64 bits)  
(3114734)  
(Importante)  
Microsoft Word 2013 Service Pack 1 (edições de 64 bits)  
(3114724)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3114734)  
(Importante)  
Microsoft Word 2013 RT Service Pack 1  
(3114724)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 32 bits)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (edição de 32 bits)  
(3114698)  
(Importante)  
Microsoft Word 2016 (edição de 32 bits):  
(3114702)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (edição de 64 bits)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (edição de 64 bits)  
(3114698)  
(Importante)  
Microsoft Word 2016 (edição de 64 bits):  
(3114702)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office para Mac**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Críticoº**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office para Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Excel para Mac 2011  
(3137721)  
(Importante)  
Microsoft Word para Mac 2011  
(3137721)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 para Mac
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 para Mac  
(3134241)  
(Importante)  
Microsoft Word 2016 para Mac  
(3134241)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Outros softwares do Office**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3
</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(3114548)  
(Importante)  
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(3114745)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114747)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114773)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS16-015**

Este boletim abrange mais de uma categoria de software. Consulte as outras tabelas nesta seção para saber quais softwares foram afetados.

 

### Microsoft Office Services e Web Apps

<p></p> 
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
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
Excel Services  
(3114432)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
Excel Services  
(3114432)  
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
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(3114401)  
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
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Excel Services  
(3114335)  
(Importante)  
Serviços de Automação do Word  
(3114481)  
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
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3114407)  
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
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3114338)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS16-015**

Este boletim abrange mais de uma categoria de software. Consulte as outras tabelas nesta seção para saber quais softwares foram afetados.

 

### Microsoft Server Software

<p></p> 
<p></p>

<table style="border:1px solid black;">
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
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3039768)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Foundation 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS16-015**](https://technet.microsoft.com/pt-br/library/security/ms16-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3114733)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para MS16-015**

Este boletim abrange mais de uma categoria de software. Consulte as outras tabelas nesta seção para saber quais softwares foram afetados.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns.

O WSUS (Windows Server Update Services), SMS (Systems Management Server) e SCCM (System Center Configuration Manager) ajudam os administradores a distribuir as atualizações de segurança.

Os componentes do Avaliador de Compatibilidade de Atualizações, incluídos no Kit de Ferramentas de Compatibilidade de Aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para obter mais informações sobre essas e outras ferramentas disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/pt-br/security/cc297183). 

Agradecimentos
--------------

 
A Microsoft reconhece os esforços dos membros da comunidade de segurança que nos ajudam a proteger os consumidores graças à divulgação responsável de vulnerabilidades. Consulte [Agradecimentos](https://technet.microsoft.com/pt-br/library/security/dn903755.aspx) para obter mais informações.

Outras informações
------------------

 
### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

Em relação ao lançamento de boletins que ocorre na segunda terça-feira do mês, a Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows no Windows Update, Microsoft Update, Windows Server Update Services e Centro de Download. Nenhuma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows está disponível para os lançamentos de boletins de segurança desvinculados.

### Atualizações não relacionadas à segurança no MU, WU e WSUS

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 do Banco de Dados de Conhecimento da Microsoft](https://support.microsoft.com/pt-br/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/pt-br/windowsserver/bb332157.aspx). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://technet.microsoft.com/pt-br/security/dn467918).

### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://technet.microsoft.com/pt-br/library/bb466251.aspx) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://www.microsoft.com/downloads/results.aspx?displaylang=pt-br&freetext=security%20update). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=pt-br).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter informações adicionais, consulte o [artigo 913086 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://technet.microsoft.com/pt-br/security/cc136632.aspx).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle).

Soluções de segurança para profissionais de TI: [Suporte e Solução de Problemas de Segurança do TechNet](http://technet.microsoft.com/pt-br/security/bb980617)

Ajuda a proteger seu computador executando o Windows contra vírus e malware: [Central de Segurança e Solução contra Vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=pt-br)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx?ln=pt-br)

### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Dados de Conhecimento da Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (09.02.16): Resumo do boletim publicado.
-   V2.0 (10 de fevereiro de 2016): Para o MS16-014, o Resumo do Boletim foi revisado para informar a disponibilidade da atualização 3126041 para o Microsoft Windows Vista, Windows Server 2008, Windows Server 2008 para os sistemas com base em processadores Itanium, Windows 8.1 e Windows Server 2012 R2. Os clientes devem aplicar as atualizações aplicáveis para estarem protegidos das vulnerabilidades abordadas neste boletim. A maioria dos clientes tem o recurso de atualizações automáticas habilitado e não precisará tomar nenhuma providência porque as atualizações serão baixadas e instaladas automaticamente. Para o MS16-021 foi corrigida a Avaliação da Capacidade de exploração para CVE-2016-0050.
-   V3.0 (16 de fevereiro de 2016): Para o MS16-015, foi adicionada a atualização 3134241 para o Microsoft Office 2016 para Mac e a atualização 3137721 para o Microsoft Office para Mac 2011, que estão disponíveis a partir de 16 de fevereiro de 2016. Para obter mais informações, consulte o [artigo 3134241 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/3134241) e o [artigo 3137721 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/3137721).
-   V3.1 (24 de fevereiro de 2016) : Adicionada uma referência de problemas conhecidos à tabela de sinopses para o MS16-014. Para obter mais informações, consulte o [artigo 3126041 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/3126041). Observe também que um segundo problema conhecido, que inclui soluções alternativas, foi adicionado ao [artigo 3126587 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/3126587).

*Página gerada em 24/02/2016 às 13:45-08:00.*
