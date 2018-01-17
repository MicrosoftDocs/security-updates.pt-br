---
TOCTitle: 'MS15-JUL'
Title: Resumo de boletins de segurança da Microsoft de julho de 2015
ms:assetid: 'ms15-jul'
ms:contentKeyID: 66484746
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms15-jul(v=Security.10)'
---

 

Resumo de boletins de segurança da Microsoft de julho de 2015
=============================================================

Publicado em: 14 de julho de 2015 | Atualizado em: 25 de maio de 2016

**Versão:** 3.1

Este resumo de boletins lista os boletins de segurança lançados em julho de 2015.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft forem emitidos, visite [Notificações de Segurança Técnica da Microsoft](http://technet.microsoft.com/pt-br/security/dd252948.aspx).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

Sinopse
-------

 
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os Software afetado, consulte a próxima seção, **Software afetado**.

<p></p>

<table style="width:100%;">
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-058">MS15-058</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no SQL Server podem permitir a execução remota de código (3065718)</strong><br />
Esta atualização de segurança resolve vulnerabilidades no Microsoft SQL Server. As vulnerabilidades mais graves podem permitir a execução remota de código se um atacante não autenticado executa uma consulta especialmente criada que foi projetada para executar uma função virtual de um endereço incorreto, levando a uma chamada de função para uma memória não inicializada. Para explorar essa vulnerabilidade um atacante precisaria de permissões para criar ou modificar um banco de dados.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/pt-br/kb/3065718">3065718</a></td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança para o Internet Explorer (3076321)</strong> <br />
Esta atualização de segurança resolve vulnerabilidades no Internet Explorer. A vulnerabilidade mais grave pode permitir a Execução remota de código se um usuário visualizar uma página da Web criada especialmente usando o Internet Explorer. O atacante que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-066">MS15-066</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no mecanismo de script VBScript pode permitir a execução remota de código (3072604)</strong> <br />
Essa atualização de segurança elimina uma vulnerabilidade no mecanismo de script VBScript no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código caso um usuário visita um site especialmente criado. O atacante que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Se um usuário atual tiver feito logon com direitos administrativos, o atacante que explorar com êxito essa vulnerabilidade poderá obter o controle total do sistema afetado. O atacante poderia instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-067">MS15-067</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no RDP podem permitir a execução remota de código (3073094)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um atacante enviar uma sequência especialmente criada de pacotes para o sistema de destino com o Protocolo de Área de Trabalho Remota (RDP) habilitado. Por padrão, o RDP não está habilitado em nenhum sistema operacional Windows. Sistemas que não têm o RDP habilitado não correm risco.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-068">MS15-068</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Windows Hyper-V podem permitir a execução remota de código (3072000)</strong> <br />
Esta atualização de segurança elimina vulnerabilidades no Microsoft Windows. As vulnerabilidades podem permitir a execução remota de código em um contexto de host se um aplicativo especialmente criado é executado por um usuário com privilégios e autenticado em uma máquina virtual convidada hospedada pelo Hyper-V. Um atacante deve ter credencias válidas de logon para uma máquina virtual convidada para explorar esta vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-069">MS15-069</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Windows podem permitir a execução remota de código (3072631)</strong> <br />
Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. As vulnerabilidades podem permitir a execução remota de código se um atacante primeiro colocar um arquivo (DLL) da biblioteca de link dinâmico especialmente criado no diretório de trabalho atual do usuário e depois convence o usuário a abrir um arquivo RTF ou a iniciar um programa que foi desenvolvido para carregar um arquivo DLL confiável, mas ao invés carrega o arquivo DLL especialmente criado do atacante. Um atacante que conseguir explorar as vulnerabilidades pode assumir totalmente o controle do sistema afetado. O atacante poderia instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-070">MS15-070</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Office podem permitir a Execução remota de código (3072620)</strong> <br />
Esta atualização de segurança elimina vulnerabilidades no Microsoft Office. A mais grave das vulnerabilidades pode permitir a execução remota de código se um usuário abrir um arquivo do Microsoft Office especialmente criado. Um atacante que tenha conseguido explorar as vulnerabilidades pode executar um código arbitrário no contexto do usuário atual. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-071">MS15-071</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Netlogon pode permitir a elevação de privilégio (3068457)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a elevação de privilégio se um atacante com acesso a um controlador de domínio primário (PDC) em uma rede de destino executa um aplicativo especialmente criado para estabelecer um canal seguro com o PDC como um controlador de domínio de back-up (BDC).</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-072">MS15-072</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade nos componentes gráficos do Windows pode permitir a elevação de privilégio (3069392)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a elevação de privilégio se o componente gráfico do Windows não processar corretamente as conversões de bitmap. Um atacante autenticado que tenha explorado com êxito esta vulnerabilidade pode elevar privilégios em um sistema de destino. O atacante poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Um atacante deve primeiro se conectar ao sistema para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-073">MS15-073</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade em drivers do modo do kernel do Windows pode permitir a elevação de privilégio (3070102)</strong> <br />
Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. As vulnerabilidades poderá permitir a elevação de privilégio se um atacante se conectar a um sistema afetado e executar um aplicativo especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-074">MS15-074</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no serviço Windows Installer pode permitir a elevação de privilégio (3072630)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a elevação de privilégio se o serviço Windows Installer executar incorretamente scripts de ação personalizada. Um atacante deve primeiro comprometer um usuário que está conectado ao sistema de destino a explorar a vulnerabilidade. O atacante poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-075">MS15-075</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no OLE podem permitir a elevação de privilégio (3072633)</strong><br />
Esta atualização de segurança resolve vulnerabilidades no Microsoft Windows. As vulnerabilidades podem permitir a elevação de privilégio se usadas em conjunto com outras vulnerabilidades que permitem a execução do código arbitrário. Assim que a outra vulnerabilidade for explorada, um atacante pode então explorar as vulnerabilidades abordadas neste boletim para fazer com que um código arbitrário execute a um nível de integridade médio.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-076">MS15-076</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade na chamada de procedimento remoto do Windows pode permitir elevação de privilégio (3067505)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade, que existe na autenticação de Chamada de Procedimento Remoto (RPC) do Windows, pode permitir a elevação de privilégio se um atacante fizer logon em um sistema afetado e executar um aplicativo especialmente criado. O atacante que explorar com êxito essa vulnerabilidade poderá assumir o controle total do sistema afetado. O atacante poderia instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/pt-br/kb/3067505">3067505</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-077">MS15-077</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no driver de fonte ATM pode permitir a elevação de privilégio (3077657)</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um atacante fizer logon em um sistema de destino e executar um aplicativo especialmente criado. Um atacante que explore com êxito esta vulnerabilidade pode causar a execução de código arbitrário e assumir o controle total do sistema afetado. O atacante poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-078">MS15-078</a><br />
(Lançado de maneira desvinculada em 20 de julho de 2015)</td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Driver de fonte da Microsoft podem permitir a execução remota de código (3079904)</strong> <br />
Esta atualização de segurança resolve uma vulnerabilidade no Microsoft Windows. A vulnerabilidade pode permitir a execução remota do código se um usuário abrir um documento especialmente criado ou visitar uma página da Web não confiável que contém fontes OpenType incorporadas.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidade são listadas em ordem de ID do boletim, depois de ID do CVE. Só serão incluídas as vulnerabilidades que tiverem uma classificação de gravidade Crítico ou Importante nos boletins.
  
**Como devo usar a tabela?**  
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Índice de Exploração da Microsoft](http://technet.microsoft.com/pt-br/security/cc998259).
  
Nas colunas a seguir, "Versão Mais Recente de Software" se refere ao software, e "Versões Mais Antigas de Software" se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Software afetado" e "Softwares não afetados" do boletim.
  
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
<td style="border:1px solid black;"><strong>Título da vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>ID do CVE              </strong></td>
<td style="border:1px solid black;"><strong>Avaliação da capacidade de exploração para<br />
Versão de software mais recente</strong></td>
<td style="border:1px solid black;"><strong>Avaliação da capacidade de exploração para<br />
Versão de software mais antigo</strong></td>
<td style="border:1px solid black;"><strong>Negação de Serviço<br />
Avaliação da capacidade de exploração</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-058">MS15-058</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do SQL Server</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1761">CVE-2015-1761</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-058">MS15-058</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código do SQL Server</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1762">CVE-2015-1762</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-058">MS15-058</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código do SQL Server</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1763">CVE-2015-1763</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de informação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1729">CVE-2015-1729</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1733">CVE-2015-1733</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1738">CVE-2015-1738</a></td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1767">CVE-2015-1767</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do VBScript</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2372">CVE-2015-2372</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2383">CVE-2015-2383</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2384">CVE-2015-2384</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2385">CVE-2015-2385</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2388">CVE-2015-2388</a></td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2389">CVE-2015-2389</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2390">CVE-2015-2390</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2391">CVE-2015-2391</a></td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2397">CVE-2015-2397</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio de filtro XSS do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2398">CVE-2015-2398</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2401">CVE-2015-2401</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio na Internet</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2402">CVE-2015-2402</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2403">CVE-2015-2403</a></td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2404">CVE-2015-2404</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2406">CVE-2015-2406</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2408">CVE-2015-2408</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de informação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2410">CVE-2015-2410</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2411">CVE-2015-2411</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de informação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2412">CVE-2015-2412</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de informação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2413">CVE-2015-2413</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de informação do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2414">CVE-2015-2414</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória Jscript9</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2419">CVE-2015-2419</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Desvio de ASLR no Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2421">CVE-2015-2421</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2422">CVE-2015-2422</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-065">MS15-065</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2425">CVE-2015-2425</a></td>
<td style="border:1px solid black;">0 - Exploração detectada</td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-066">MS15-066</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do VBScript</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2372">CVE-2015-2372</a></td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-067">MS15-067</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código do Protocolo de Área de Trabalho Remota (RDP)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2373">CVE-2015-2373</a></td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-068">MS15-068</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estouro de buffer do Hyper-V</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2361">CVE-2015-2361</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Permanente</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-068">MS15-068</a></td>
<td style="border:1px solid black;">Vulnerabilidade de estrutura de dados do sistema do Hyper-V</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2362">CVE-2015-2362</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-069">MS15-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código do DLL do Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2368">CVE-2015-2368</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-069">MS15-069</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código de pré-carregamento do DLL</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2369">CVE-2015-2369</a></td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-070">MS15-070</a></td>
<td style="border:1px solid black;">Vulnerabilidade de desvio de ASLR do Microsoft Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2375">CVE-2015-2375</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-070">MS15-070</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2376">CVE-2015-2376</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-070">MS15-070</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2377">CVE-2015-2377</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-070">MS15-070</a></td>
<td style="border:1px solid black;">Vulnerabilidade de execução remota de código do Microsoft Excel DLL</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2378">CVE-2015-2378</a></td>
<td style="border:1px solid black;">4- Não afetado</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-070">MS15-070</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2379">CVE-2015-2379</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-070">MS15-070</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2380">CVE-2015-2380</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-070">MS15-070</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2415">CVE-2015-2415</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-070">MS15-070</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2424">CVE-2015-2424</a></td>
<td style="border:1px solid black;">0 - Exploração detectada</td>
<td style="border:1px solid black;">0 - Exploração detectada</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-071">MS15-071</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio no Netlogon</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2374">CVE-2015-2374</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-072">MS15-072</a></td>
<td style="border:1px solid black;">Vulnerabilidade no componente gráfico EOP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2364">CVE-2015-2364</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-073">MS15-073</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2363">CVE-2015-2363</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Permanente</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-073">MS15-073</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2365">CVE-2015-2365</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Permanente</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-073">MS15-073</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2366">CVE-2015-2366</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-073">MS15-073</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação não autorizada de informações do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2367">CVE-2015-2367</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-073">MS15-073</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação não autorizada de informações do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2381">CVE-2015-2381</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-073">MS15-073</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação não autorizada de informações do Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2382">CVE-2015-2382</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-074">MS15-074</a></td>
<td style="border:1px solid black;">Vulnerabilidade no Windows Installer EoP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2371">CVE-2015-2371</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-075">MS15-075</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio OLE</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2416">CVE-2015-2416</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-075">MS15-075</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio OLE</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2417">CVE-2015-2417</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-076">MS15-076</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Windows RPC</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2370">CVE-2015-2370</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-077">MS15-077</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do ATMFD.DLL</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2387">CVE-2015-2387</a></td>
<td style="border:1px solid black;">0 - Exploração detectada</td>
<td style="border:1px solid black;">0 - Exploração detectada</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms15-078">MS15-078</a></td>
<td style="border:1px solid black;">Vulnerabilidade do driver da fonte OpenType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2426">CVE-2015-2426</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
</tbody>
</table>

<p></p>

  
Softwares Afetados  
------------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
### Sistema operacional do Windows e componentes (Tabela 1 de 3)

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-065**](https://technet.microsoft.com/pt-br/library/security/ms15-065)

</td>
<td style="border:1px solid black;">
[**MS15-066**](https://technet.microsoft.com/pt-br/library/security/ms15-066)

</td>
<td style="border:1px solid black;">
[**MS15-067**](https://technet.microsoft.com/pt-br/library/security/ms15-067)

</td>
<td style="border:1px solid black;">
[**MS15-068**](https://technet.microsoft.com/pt-br/library/security/ms15-068)

</td>
<td style="border:1px solid black;">
[**MS15-069**](https://technet.microsoft.com/pt-br/library/security/ms15-069)

</td>
<td style="border:1px solid black;">
[**MS15-071**](https://technet.microsoft.com/pt-br/library/security/ms15-071)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)                                             

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx) 

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
[**Importante**                                 ](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2    

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3065822)  
(Moderado)  
Internet Explorer 7  
(3065822)  
(Moderado)  
Internet Explorer 8  
(3065822)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(3068404)  
(Crítico)  
VBScript 5.7  
(3068368)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2      
(3067903)  
(Importante)  
Windows Media Format SDK 11  
(3067903)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3065822)  
(Moderado)  
Internet Explorer 7  
(3065822)  
(Moderado)  
Internet Explorer 8  
(3065822)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3068404)  
(Crítica)  
VBScript 5.7   
(3068368)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2  
(3067903)  
(Importante)  
Windows Media Format SDK 11  
(3067903)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3065822)  
(Moderado)  
Internet Explorer 7  
(3065822)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3068404)  
(Crítica)  
VBScript 5.7  
(3068368)  
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
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 R2 Service Pack 2

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
Windows Server 2003 R2 Service Pack 2  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 R2 x64 Edition Service Pack 2

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
Windows Server 2003 R2 x64 Edition Service Pack 2  
(3068457)  
(Importante)

</td>
</tr>
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
[**MS15-065**](https://technet.microsoft.com/pt-br/library/security/ms15-065)

</td>
<td style="border:1px solid black;">
[**MS15-066**](https://technet.microsoft.com/pt-br/library/security/ms15-066)

</td>
<td style="border:1px solid black;">
[**MS15-067**](https://technet.microsoft.com/pt-br/library/security/ms15-067)

</td>
<td style="border:1px solid black;">
[**MS15-068**](https://technet.microsoft.com/pt-br/library/security/ms15-068)

</td>
<td style="border:1px solid black;">
[**MS15-069**](https://technet.microsoft.com/pt-br/library/security/ms15-069)

</td>
<td style="border:1px solid black;">
[**MS15-071**](https://technet.microsoft.com/pt-br/library/security/ms15-071)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
Internet Explorer 7  
(3065822)  
(Crítica)  
Internet Explorer 8  
(3065822)  
(Crítica)  
Internet Explorer 9  
(3065822)  
(Crítica)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3068368)  
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
(3067903)  
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
Internet Explorer 7  
(3065822)  
(Crítica)  
Internet Explorer 8  
(3065822)  
(Crítica)  
Internet Explorer 9  
(3065822)  
(Crítica)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3068368)  
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
(3067903)  
(Importante)

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
[**MS15-065**](https://technet.microsoft.com/pt-br/library/security/ms15-065)

</td>
<td style="border:1px solid black;">
[**MS15-066**](https://technet.microsoft.com/pt-br/library/security/ms15-066)

</td>
<td style="border:1px solid black;">
[**MS15-067**](https://technet.microsoft.com/pt-br/library/security/ms15-067)

</td>
<td style="border:1px solid black;">
[**MS15-068**](https://technet.microsoft.com/pt-br/library/security/ms15-068)

</td>
<td style="border:1px solid black;">
[**MS15-069**](http://go.microsoft.com/fwlink/?linkid=??????)

</td>
<td style="border:1px solid black;">
[**MS15-071**](https://technet.microsoft.com/pt-br/library/security/ms15-071)

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
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
Windows Server 2008 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3065822)  
(Moderado)  
Internet Explorer 8  
(3065822)  
(Moderado)  
Internet Explorer 9  
(3065822)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3068368)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3067903)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3065822)  
(Moderado)  
Internet Explorer 8  
(3065822)  
(Moderado)  
Internet Explorer 9  
(3065822)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3068368)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3046339)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3067903)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3065822)  
(Moderado)

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3068368)  
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
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3068457)  
(Importante)

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
[**MS15-065**](https://technet.microsoft.com/pt-br/library/security/ms15-065)

</td>
<td style="border:1px solid black;">
[**MS15-066**](https://technet.microsoft.com/pt-br/library/security/ms15-066)

</td>
<td style="border:1px solid black;">
[**MS15-067**](https://technet.microsoft.com/pt-br/library/security/ms15-067)

</td>
<td style="border:1px solid black;">
[**MS15-068**](https://technet.microsoft.com/pt-br/library/security/ms15-068)

</td>
<td style="border:1px solid black;">
[**MS15-069**](http://go.microsoft.com/fwlink/?linkid=??????)

</td>
<td style="border:1px solid black;">
[**MS15-071**](https://technet.microsoft.com/pt-br/library/security/ms15-071)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
Windows 7 para sistemas de 32 bits Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3065822)  
(Crítica)  
Internet Explorer 9  
(3065822)  
(Crítico)  
Internet Explorer 10  
(3065822)  
(Crítica)  
Internet Explorer 11  
(3065822)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3067904)  
(Crítica)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(3069762)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3067903)  
(Importante)  
Windows 7 para sistemas de 32 bits Service Pack 1  
(3070738)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para Sistemas baseados em x64 Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3065822)  
(Crítica)  
Internet Explorer 9  
(3065822)  
(Crítico)  
Internet Explorer 10  
(3065822)  
(Crítica)  
Internet Explorer 11  
(3065822)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas baseados em x64 Service Pack 1  
(3067904)  
(Crítica)  
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3069762)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas baseados em x64 Service Pack 1  
(3067903)  
(Importante)  
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3070738)  
(Importante)

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
[**MS15-065**](https://technet.microsoft.com/pt-br/library/security/ms15-065)

</td>
<td style="border:1px solid black;">
[**MS15-066**](https://technet.microsoft.com/pt-br/library/security/ms15-066)

</td>
<td style="border:1px solid black;">
[**MS15-067**](https://technet.microsoft.com/pt-br/library/security/ms15-067)

</td>
<td style="border:1px solid black;">
[**MS15-068**](https://technet.microsoft.com/pt-br/library/security/ms15-068)

</td>
<td style="border:1px solid black;">
[**MS15-069**](http://go.microsoft.com/fwlink/?linkid=??????)

</td>
<td style="border:1px solid black;">
[**MS15-071**](https://technet.microsoft.com/pt-br/library/security/ms15-071)

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
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
Internet Explorer 8  
(3065822)  
(Moderado)  
Internet Explorer 9  
(3065822)  
(Moderado)  
Internet Explorer 10  
(3065822)  
(Moderado)  
Internet Explorer 11  
(3065822)  
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
(3046339)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3067903)  
(Importante)  
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3070738)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3065822)  
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
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 e Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-065**](https://technet.microsoft.com/pt-br/library/security/ms15-065)

</td>
<td style="border:1px solid black;">
[**MS15-066**](https://technet.microsoft.com/pt-br/library/security/ms15-066)

</td>
<td style="border:1px solid black;">
[**MS15-067**](https://technet.microsoft.com/pt-br/library/security/ms15-067)

</td>
<td style="border:1px solid black;">
[**MS15-068**](https://technet.microsoft.com/pt-br/library/security/ms15-068)

</td>
<td style="border:1px solid black;">
[**MS15-069**](http://go.microsoft.com/fwlink/?linkid=??????)

</td>
<td style="border:1px solid black;">
[**MS15-071**](https://technet.microsoft.com/pt-br/library/security/ms15-071)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
Windows 8 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3065822)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3067904)  
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
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3065822)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3067904)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3046339)  
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
Windows 8.1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3065822)  
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
Windows 8.1 para sistemas de 32 bits  
(3061512)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3065822)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3046339)  
(Crítica)  
Windows 8.1 para sistemas baseados em x64  
(3046359)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3061512)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

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
[**MS15-065**](https://technet.microsoft.com/pt-br/library/security/ms15-065)

</td>
<td style="border:1px solid black;">
[**MS15-066**](https://technet.microsoft.com/pt-br/library/security/ms15-066)

</td>
<td style="border:1px solid black;">
[**MS15-067**](https://technet.microsoft.com/pt-br/library/security/ms15-067)

</td>
<td style="border:1px solid black;">
[**MS15-068**](https://technet.microsoft.com/pt-br/library/security/ms15-068)

</td>
<td style="border:1px solid black;">
[**MS15-069**](https://technet.microsoft.com/pt-br/library/security/ms15-069)

</td>
<td style="border:1px solid black;">
[**MS15-071**](https://technet.microsoft.com/pt-br/library/security/ms15-071)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderada**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3065822)  
(Moderado)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3067904)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046339)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3065822)  
(Moderado)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046339)  
(Crítica)  
Windows Server 2012 R2  
(3046359)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3061512)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT e Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-065**](https://technet.microsoft.com/pt-br/library/security/ms15-065)

</td>
<td style="border:1px solid black;">
[**MS15-066**](https://technet.microsoft.com/pt-br/library/security/ms15-066)

</td>
<td style="border:1px solid black;">
[**MS15-067**](https://technet.microsoft.com/pt-br/library/security/ms15-067)

</td>
<td style="border:1px solid black;">
[**MS15-068**](https://technet.microsoft.com/pt-br/library/security/ms15-068)

</td>
<td style="border:1px solid black;">
[**MS15-069**](http://go.microsoft.com/fwlink/?linkid=??????)

</td>
<td style="border:1px solid black;">
[**MS15-071**](https://technet.microsoft.com/pt-br/library/security/ms15-071)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
**Nenhuma**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3065822)  
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
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3065822)  
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
(3061512)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

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
[**MS15-065**](https://technet.microsoft.com/pt-br/library/security/ms15-065)

</td>
<td style="border:1px solid black;">
[**MS15-066**](https://technet.microsoft.com/pt-br/library/security/ms15-066)

</td>
<td style="border:1px solid black;">
[**MS15-067**](https://technet.microsoft.com/pt-br/library/security/ms15-067)

</td>
<td style="border:1px solid black;">
[**MS15-068**](https://technet.microsoft.com/pt-br/library/security/ms15-068)

</td>
<td style="border:1px solid black;">
[**MS15-069**](http://go.microsoft.com/fwlink/?linkid=??????)

</td>
<td style="border:1px solid black;">
[**MS15-071**](https://technet.microsoft.com/pt-br/library/security/ms15-071)

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
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3068368)  
(Nenhuma classificação de gravidade)

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
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3068368)  
(Nenhuma classificação de gravidade)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3046339)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3068457)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
VBScript 5.8  
(3068364)  
(Nenhuma classificação de gravidade)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3046339)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3068457)  
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
Windows Server 2012 (instalação Server Core)  
(3067904)  
(Crítica)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3046339)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3068457)  
(Importante)

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
Windows Server 2012 R2 (instalação Server Core)  
(3046339)  
(Crítica)  
Windows Server 2012 R2 (instalação Server Core)  
(3046359)  
(Crítica)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3068457)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
**Observação para o MS15-067**

As edições Enterprise e Ultimate do Windows 7 são afetadas. Todas as edições com suporte do Windows 7 serão afetadas se a RDP 8.0 estiver instalada no sistema.

**Observações para MS15-069**

Para a atualização 3067903, os sistemas Windows Server 2008 e Windows Server 2008 R2 são afetados somente se o recurso Desktop Experience está instalado.

Para a atualização 3070738, os sistemas são afetados apenas se RDP 8.1 está instalado.

### Sistema operacional do Windows e componentes (Tabela 2 de 3)

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)                                 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2            

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2              
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 R2 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 Service Pack 2  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 Service Pack 2  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 Service Pack 2  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 Service Pack 2  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 R2 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 x64 Edition Service Pack 2  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 x64 Edition Service Pack 2  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 x64 Edition Service Pack 2  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 R2 x64 Edition Service Pack 2  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
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
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3077657)  
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
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3077657)  
(Importante)

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
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para Sistemas baseados em x64 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3077657)  
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
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 e Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3077657)  
(Importante)

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
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT e Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3077657)  
(Importante)

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
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
Windows 10 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3074683)  
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
Windows 10 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3074683)  
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
**Opção de instalação Server Core**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-072**](https://technet.microsoft.com/pt-br/library/security/ms15-072)

</td>
<td style="border:1px solid black;">
[**MS15-073**](https://technet.microsoft.com/pt-br/library/security/ms15-073)

</td>
<td style="border:1px solid black;">
[**MS15-074**](https://technet.microsoft.com/pt-br/library/security/ms15-074)

</td>
<td style="border:1px solid black;">
[**MS15-075**](https://technet.microsoft.com/pt-br/library/security/ms15-075)

</td>
<td style="border:1px solid black;">
[**MS15-076**](https://technet.microsoft.com/pt-br/library/security/ms15-076)

</td>
<td style="border:1px solid black;">
[**MS15-077**](https://technet.microsoft.com/pt-br/library/security/ms15-077)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3077657)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3069392)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3070102)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3072630)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3072633)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3067505)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3077657)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
### Sistema operacional do Windows e componentes (Tabela 3 de 3)

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-078**](https://technet.microsoft.com/pt-br/library/security/ms15-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-078**](https://technet.microsoft.com/pt-br/library/security/ms15-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em Itanium Service Pack 2  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-078**](https://technet.microsoft.com/pt-br/library/security/ms15-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 Service Pack 1  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-078**](https://technet.microsoft.com/pt-br/library/security/ms15-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8 e Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-078**](https://technet.microsoft.com/pt-br/library/security/ms15-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 e Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-078**](https://technet.microsoft.com/pt-br/library/security/ms15-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows RT e Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-078**](https://technet.microsoft.com/pt-br/library/security/ms15-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-078**](https://technet.microsoft.com/pt-br/library/security/ms15-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits  
(3074683)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 10 para sistemas baseados em x64  
(3074683)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Opção de instalação Server Core**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-078**](https://technet.microsoft.com/pt-br/library/security/ms15-078)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas baseados em x64 Service Pack 1 (instalação Server Core)  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3079904)  
(Crítica)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3079904)  
(Crítica)

</td>
</tr>
</table>

<p></p>

 
### Microsoft SQL Server

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008 Service Pack 3**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-058**](https://technet.microsoft.com/pt-br/library/security/ms15-058)

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
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3  
(GDR)  
(3045305)  
(Importante)  
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 3  
(QFE)  
(3045303)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3  
(GDR)  
(3045305)  
(Importante)  
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 3  
(QFE)  
(3045303)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3  
(GDR)  
(3045305)  
(Importante)  
Microsoft SQL Server 2008 para sistemas baseados em Itanium Service Pack 3  
(QFE)  
(3045303)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008 Service Pack 4**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-058**](https://technet.microsoft.com/pt-br/library/security/ms15-058)

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
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 4

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 4  
(GDR)  
(3045311)  
(Importante)  
Microsoft SQL Server 2008 para sistemas de 32 bits Service Pack 4  
(QFE)  
(3045308)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 4

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 4  
(GDR)  
(3045311)  
(Importante)  
Microsoft SQL Server 2008 para sistemas baseados em x64 Service Pack 4  
(QFE)  
(3045308)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008 R2 Service Pack 2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-058**](https://technet.microsoft.com/pt-br/library/security/ms15-058)

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
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 2  
(GDR)  
(3045313)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 2  
(QFE)  
(3045312)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 2  
(GDR)  
(3045313)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 2  
(QFE)  
(3045312)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 2  
(GDR)  
(3045313)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas baseados em Itanium Service Pack 2  
(QFE)  
(3045312)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008 R2 Service Pack 3**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-058**](https://technet.microsoft.com/pt-br/library/security/ms15-058)

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
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 3  
(GDR)  
(3045316)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas de 32 bits Service Pack 3  
(QFE)  
(3045314)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 3  
(GDR)  
(3045316)  
(Importante)  
Microsoft SQL Server 2008 R2 para sistemas baseados em x64 Service Pack 3  
(QFE)  
(3045314)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012 Service Pack 1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-058**](https://technet.microsoft.com/pt-br/library/security/ms15-058)

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
Microsoft SQL Server 2012 para sistemas de 32 bits Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 para sistemas de 32 bits Service Pack 1  
(GDR)  
(3045318)  
(Importante)  
Microsoft SQL Server 2012 para sistemas de 32 bits Service Pack 1  
(QFE)  
(3045317)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 para sistemas baseados em x64 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 para sistemas baseados em x64 Service Pack 1  
(GDR)  
(3045318)  
(Importante)  
Microsoft SQL Server 2012 para sistemas baseados em x64 Service Pack 1  
(QFE)  
(3045317)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012 Service Pack 2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-058**](https://technet.microsoft.com/pt-br/library/security/ms15-058)

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
Microsoft SQL Server 2012 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 para sistemas de 32 bits Service Pack 2  
(GDR)  
(3045321)  
(Importante)  
Microsoft SQL Server 2012 para sistemas de 32 bits Service Pack 2  
(QFE)  
(3045319)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 para sistemas baseados em x64 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 para sistemas baseados em x64 Service Pack 2  
(GDR)  
(3045321)  
(Importante)  
Microsoft SQL Server 2012 para sistemas baseados em x64 Service Pack 2  
(QFE)  
(3045319)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-058**](https://technet.microsoft.com/pt-br/library/security/ms15-058)

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
Microsoft SQL Server 2014 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 para sistemas de 32 bits  
(GDR)  
(3045324)  
(Importante)  
Microsoft SQL Server 2014 para sistemas de 32 bits  
(QFE)  
(3045323)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014 para sistemas baseados em x64  
(GDR)  
(3045324)  
(Importante)  
Microsoft SQL Server 2014 para sistemas baseados em x64  
(QFE)  
(3045323)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
### Microsoft Office Suites e software

 
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
[**MS15-070**](https://technet.microsoft.com/pt-br/library/security/ms15-070)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2965281)  
(Importante)  
Microsoft PowerPoint 2007 Service Pack 3  
(2965283)  
(Importante)  
Microsoft Word 2007 Service Pack 3  
(3054996)  
(Importante)

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
[**MS15-070**](https://technet.microsoft.com/pt-br/library/security/ms15-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 32 bits)  
(3054971)  
(Importante)  
Microsoft Excel 2010 Service Pack 2 (edições de 32 bits)  
(3054981)  
(Importante)  
Microsoft PowerPoint 2010 Service Pack 2 (edições de 32 bits)  
(3054963)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 32 bits)  
(3054973)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (edições de 64 bits)  
(3054971)  
(Importante)  
Microsoft Excel 2010 Service Pack 2 (edições de 64 bits)  
(3054981)  
(Importante)  
Microsoft PowerPoint 2010 Service Pack 2 (edições de 64 bits)  
(3054963)  
(Importante)  
Microsoft Word 2010 Service Pack 2 (edições de 64 bits)  
(3054973)  
(Importante)

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
[**MS15-070**](https://technet.microsoft.com/pt-br/library/security/ms15-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 32 bits)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (edições de 32 bits)  
(3054949)  
(Importante)  
Microsoft PowerPoint 2013 Service Pack 1 (edições de 32 bits)  
(3054999)  
(Importante)  
Microsoft Word 2013 Service Pack 1 (edições de 32 bits)  
(3054990)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (edições de 64 bits)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (edições de 64 bits)  
(3054949)  
(Importante)  
Microsoft PowerPoint 2013 Service Pack 1 (edições de 64 bits)  
(3054999)  
(Importante)  
Microsoft Word 2013 Service Pack 1 (edições de 64 bits)  
(3054990)  
(Importante)

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
[**MS15-070**](https://technet.microsoft.com/pt-br/library/security/ms15-070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3054949)  
(Importante)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3054999)  
(Importante)  
Microsoft Word 2013 RT Service Pack 1  
(3054990)  
(Importante)

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
[**MS15-070**](https://technet.microsoft.com/pt-br/library/security/ms15-070)

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
Microsoft Office para Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel para Mac 2011  
(3073865)  
(Importante)

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
[**MS15-070**](https://technet.microsoft.com/pt-br/library/security/ms15-070)

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
Microsoft Excel Viewer 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer 2007 Service Pack 3  
(2965209)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3

</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(2965208)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3054958)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
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
[**MS15-070**](https://technet.microsoft.com/pt-br/library/security/ms15-070)

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
(2837612)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (edições de 64 bits)

</td>
<td style="border:1px solid black;">
Excel Services  
(2837612)  
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
[**MS15-070**](https://technet.microsoft.com/pt-br/library/security/ms15-070)

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
(3054968)  
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
[**MS15-070**](https://technet.microsoft.com/pt-br/library/security/ms15-070)

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
(3054861)  
(Importante)

</td>
</tr>
</table>

<p></p>

 

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

Ajuda a proteger seu computador executando o Windows contra vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=pt-br)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx?ln=pt-br)

### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Dados de Conhecimento da Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (14 de julho de 2015): Resumo do boletim publicado.
-   V2.0 (20 de julho de 2015): Resumo do boletim revisado para documentar a versão fora de banda do MS15-078.
-   V3.0 (29 de julho de 2015): Resumo do boletim revisado para MS15-074 e MS15-078 para comunicar a disponibilidade de um pacote de atualização para os sistemas do Windows 10. Os clientes que executam o Windows 10 devem aplicar a atualização 3074683 para estarem protegidos das vulnerabilidades abordadas neste boletim. A atualização está disponível apenas no Windows Update. A maioria dos clientes tem o recurso de atualizações automáticas habilitado e não precisará tomar nenhuma providência porque a atualização será baixada e instalada automaticamente.
-   V3.1 (25 de maio de 2016) : Para MS15-076, adicionado um problema conhecido à tabela de Sinopse. Para obter informações adicionais, consulte o [artigo 3067505 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/3067505). Para obter informações sobre a solução para esse problema conhecido, consulte o [artigo 3155218 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/3155218).

*Página gerada em 25/05/2016 10:57Z-07:00.*
