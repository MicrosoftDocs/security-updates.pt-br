---
TOCTitle: 'MS15-JAN'
Title: Microsoft Security Bulletin Summary for January 2015
ms:assetid: 'ms15-jan'
ms:contentKeyID: 63898367
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms15-jan(v=Security.10)'
---

 

Resumo dos boletins de segurança da Microsoft de janeiro de 2015
================================================================

Publicado em: 13 de janeiro de 2015

**Versão:** 1.0

Este resumo de boletins lista os boletins de segurança publicados em janeiro de 2015.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, visite [Notificações de Segurança Técnica da Microsoft](http://technet.microsoft.com/pt-br/security/dd252948.aspx).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

Resumo executivo
----------------

 
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados**.

 
<p></p>

<table style="border:1px solid black;">
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ID do Boletim</strong></td>
<td style="border:1px solid black;"><strong>Título do boletim e Resumo executivo</strong></td>
<td style="border:1px solid black;"><strong>Classificação máxima de gravidade e impacto da vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>Necessidade de Reinicialização</strong></td>
<td style="border:1px solid black;"><strong>Software afetado</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522536">MS15-001</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no cache de compatibilidade de aplicativo do Windows pode permitir a elevação de privilégio (3023266)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade publicamente divulgada no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um invasor fizer logon em um sistema e executar um aplicativo especialmente criado. Um invasor autenticado que explorou com êxito essa vulnerabilidade pode ignorar as verificações de permissão existentes que são realizadas durante a modificação de cache no componente Compatibilidade de Aplicativo do Microsoft Windows e execute código arbitrário com privilégios elevados.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de Privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522537">MS15-002</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade do serviço do Windows Telnet pode permitir a execução de código remoto (3020393)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada privadamente no Microsoft Windows. A vulnerabilidade pode permitir a execução de código remoto se um invasor enviar pacotes especialmente criados para um servidor Windows afetado. Por padrão, o Telnet não é instalado em qualquer versão de sistema operacional afetado. Apenas clientes que instalam manualmente esse serviço provavelmente estarão vulneráveis.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a> <br />
Execução de código remoto</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522528">MS15-003</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade do serviço do Windows User Profile pode permitir a elevação de privilégio (3021674)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada privadamente no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um invasor faz logon no sistema e executar um aplicativo especialmente criado. Um invasor local que explorou com êxito essa vulnerabilidade pode executar código arbitrário em um sistema de destino com privilégios elevados. Um invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de Privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522521">MS15-004</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Windows Components pode permitir a elevação de privilégio (3025421)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada privadamente no Microsoft Windows. A vulnerabilidade pode permitir a elevação de privilégio se um invasor convencer um usuário a executar um aplicativo especialmente criado. Um invasor que explorar com êxito as vulnerabilidades pode obter os mesmos direitos que o usuário atual. Se o usuário atual estiver conectado com direitos de administrador, um invasor poderá instalar programas, exibir, alterar ou excluir dados e criar novas contas com direitos totais do usuário. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de Privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522531">MS15-005</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Network Location Awareness Service pode permitir ignorar recursos (3022777)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada privadamente no Microsoft Windows. A vulnerabilidade pode permitir ignorar um recurso de segurança através do relaxamento não intencional da política de firewall e/ou configuração de determinados serviços quando um invasor na mesma rede que a vítima falsifica respostas para o tráfego DNS e LDAP iniciado pela vítima.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Ignorar Recurso de Segurança</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522535">MS15-006</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Windows Error Reporting pode ignorar o recurso de segurança (3004365)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada privadamente no Windows Error Reporting (WER). A vulnerabilidade pode permitir ignorar o recurso de segurança se for explorada com êxito por um invasor. Um invasor que explorou com êxito essa vulnerabilidade pode obter acesso à memória de um processo em execução. Os usuários cujas contas estão configuradas para ter menos direitos de usuário podem ser menos afetados do que os usuários que têm direitos de administrador.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Ignorar Recurso de Segurança</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519134">MS15-007</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade na implementação do Network Policy Server RADIUS Implementation pode causar negação de serviço (3014029)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada privadamente no Microsoft Windows. A vulnerabilidade pode permitir a negação de serviço em um Internet Authentication Service (IAS) ou Network Policy Server (NPS) se um invasor enviar o nome de usuário especialmente criado para o IAS ou NPS. Observe que a vulnerabilidade de negação de serviço não permitirá que um invasor execute código ou eleve direitos do usuário. No entanto, pode evitar autenticação RADIUS no IAS ou NPS.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522533">MS15-008</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no driver do modo Windows Kernel pode permitir a elevação de privilégio (3019215)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada privadamente no Microsoft Windows. A vulnerabilidade pode permitir a elevação de privilégios se um invasor executar um aplicativo especialmente criado em um sistema afetado. Um invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a> <br />
Elevação de Privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
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
  
Nas colunas a seguir, "Versão Mais Recente de Software" se refere ao software, e "Versões Mais Antigas de Software" se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.
  
<p></p>

<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ID do Boletim</strong></td>
<td style="border:1px solid black;"><strong>Título da vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>ID do CVE</strong></td>
<td style="border:1px solid black;"><strong>Avaliação da capacidade de exploração da última versão de software</strong></td>
<td style="border:1px solid black;"><strong>Avaliação da capacidade de exploração de versão mais antiga de software</strong></td>
<td style="border:1px solid black;"><strong>Avaliação do risco de exploração para negação de serviço</strong></td>
<td style="border:1px solid black;"><strong>Principais observações</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522536">MS15-001</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Microsoft Application Compatibility Infrastructure</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0002">CVE-2015-0002</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta vulnerabilidade foi divulgada publicamente.<br />
<br />
Esta é uma vulnerabilidade de elevação de privilégio.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522537">MS15-002</a></td>
<td style="border:1px solid black;">Vulnerabilidade de sobrefluxo de armazenamento de serviço do Windows Telnet</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0014">CVE-2015-0014</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de execução de código remoto.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522528">MS15-003</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Microsoft User Profile Service</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0004">CVE-2015-0004</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de elevação de privilégio.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522521">MS15-004</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do Directory Traversal</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0016">CVE-2015-0016</a></td>
<td style="border:1px solid black;">0 - Exploração detectada</td>
<td style="border:1px solid black;">0 - Exploração detectada</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Esta é uma vulnerabilidade de elevação de privilégio.<br />
<br />
Esta vulnerabilidade está sendo usada em ataques direcionados limitados como ignorar uma área restrita.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522531">MS15-005</a></td>
<td style="border:1px solid black;">Vulnerabilidade para ignorar o recurso de segurança do NLA - CVE-2015-0006</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0006">CVE-2015-0006</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522535">MS15-006</a></td>
<td style="border:1px solid black;">Vulnerabilidade para ignorar o recurso de segurança do Windows Error Reporting</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0001">CVE-2015-0001</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de desvio de recurso de segurança.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519134">MS15-007</a></td>
<td style="border:1px solid black;">Vulnerabilidade da negação de serviço da implementação do Network Policy Server RADIUS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0015">CVE-2015-0015</a></td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">3 - Exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Esta vulnerabilidade resulta na negação de serviço.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522533">MS15-008</a></td>
<td style="border:1px solid black;">Vulnerabilidade de elevação de privilégio do WebDAV</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0011">CVE-2015-0011</a></td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">2 - Probabilidade menor de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de elevação de privilégio.</td>
</tr>
</tbody>
</table>

<p></p>

  
 
  
Software afetado  
----------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
### Componentes e sistema operacional Windows

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
Windows Server 2003 Service Pack 2  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2<sup>[1]</sup>
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3014029)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2<sup>[1]</sup>
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3014029)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium<sup>[1]</sup>
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(3014029)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(3019215)  
(Importante)

</td>
</tr>
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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2 (com o Remote Desktop Client 7.0 instalado)  
(3023299)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3019215)  
(Importante)

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
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2 (com Remote Desktop Client 7.0 instalado)  
(3023299)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3019215)  
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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3014029)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3019215)  
(Importante)

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
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3014029)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64  
(3019215)  
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
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3022777)  
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
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3019978)  
(Importante)  
Windows 7 Service Pack 1 para sistemas de 32 bits (com Remote Desktop Client 8.0 instalado)  
(3020387)  
(Importante)  
Windows 7 Service Pack 1 para sistemas de 32 bits (com Remote Desktop Client 8.1 instalado)  
(3020388)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3019978)  
(Importante)  
Windows 7 Service Pack 1 para sistemas baseados em x64 (com Remote Desktop Client 8.0 instalado)  
(3020387)  
(Importante)  
Windows 7 Service Pack 1 para sistemas baseados em x64 (com Remote Desktop Client 8.1 instalado)  
(3020388)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3019215)  
(Importante)

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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3019978)  
(Importante)  
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (com Remote Desktop Client 8.0 instalado)  
(3020387)  
(Importante)  
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (com Remote Desktop Client 8.1 instalado)  
(3020388)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3014029)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados no Itanium

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em Itanium  
(3022777)  
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
<td style="border:1px solid black;" colspan="9">
**Windows 8 e Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3004365)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3004365)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em 32 bits

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em 32 bits  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em 32 bits  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em 32 bits  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em 32 bits  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em 32 bits  
(3022777) )  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em 32 bits  
(3004365)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em 32 bits  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 8,1 para sistemas baseados em x64  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8,1 para sistemas baseados em x64  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8,1 para sistemas baseados em x64  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8,1 para sistemas baseados em x64  
(3004365)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8,1 para sistemas baseados em x64  
(3019215)  
(Importante)

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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3004365)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3014029)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3004365)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3014029)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT e Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows RT  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT  
(3004365)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT  
(3019215)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3004365)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3019215)  
(Importante)

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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3022777)  
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
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3022777)  
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
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3022777)  
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
Windows Server 2012 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3004365)  
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
Windows Server 2012 R2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3023266)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3020393)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3021674)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3019978)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3022777)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3004365)  
(Importante)

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

 
**Observação para o MS15-005**

<sup>[1]</sup>O Windows Server 2003 é afetado, mas uma atualização não está sendo lançada. Consulte o boletim para obter mais informações.

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns.

O WSUS (Windows Server Update Services), SMS (Systems Management Server) e SCCM (System Center Configuration Manager) ajudam os administradores a distribuir as atualizações de segurança.

Os componentes do Avaliador de Compatibilidade de Atualizações, incluídos no Kit de Ferramentas de Compatibilidade de Aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para obter mais informações sobre essas e outras ferramentas disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/pt-br/security/cc297183). 

Agradecimentos
--------------

 
A Microsoft reconhece os esforços dos membros da comunidade de segurança que nos ajudam a proteger os consumidores graças à divulgação responsável de vulnerabilidades. Consulte [Agradecimentos](https://technet.microsoft.com/pt-br/library/security/dn820091.aspx) para obter mais informações.

Outras informações
------------------

 
### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

Em relação ao lançamento de boletins que ocorre na segunda terça-feira do mês, a Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows no Windows Update, Microsoft Update, Windows Server Update Services e Centro de Download. Nenhuma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows está disponível para os lançamentos de boletins de segurança desvinculados.

### Atualizações não relacionadas à segurança no MU, WU e WSUS

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 do Banco de Dados de Conhecimento da Microsoft](https://support.microsoft.com/kb/894199/pt-br): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
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
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter informações adicionais, consulte o [artigo 913086 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/kb/913086/pt-br).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://technet.microsoft.com/pt-br/security/cc136632.aspx).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://support2.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle).

Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/pt-br/security/bb980617)

Ajuda a proteger seu computador executando o Windows contra vírus e malware: [Centro de Segurança e Solução de Vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=pt-br)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx?ln=pt-br)

### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Dados de Conhecimento da Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (13.01.15): Resumo do boletim publicado.

*Página gerada em 08.01.2015 14:01Z-08:00.*
