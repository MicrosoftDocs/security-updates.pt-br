---
TOCTitle: 'MS14-NOV'
Title: Resumo dos Boletins de Segurança Microsoft de novembro de 2014
ms:assetid: 'ms14-nov'
ms:contentKeyID: 63355308
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms14-nov(v=Security.10)'
---

 

Resumo dos Boletins de Segurança da Microsoft de novembro de 2014
=================================================================

Publicado em: 11 de novembro de 2014 | Atualizado em: 18 de dezembro de 2014

**Versão:** 2.1

Este resumo relaciona os boletins de segurança lançados em novembro de 2014.

Com o lançamento dos boletins de segurança de novembro de 2014, este resumo substitui a notificação antecipada de boletins emitida originalmente em 06 de novembro de 2014. Para obter mais informações sobre o serviço de notificação antecipada de boletins consulte [Notificação Antecipada de Boletins de Segurança Microsoft](http://technet.microsoft.com/pt-br/security/gg309152.aspx).

execução remota de código

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

Resumo executivo
----------------

 
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados**.

 
<p></p>

<table style="border:1px solid black;">
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ID do boletim</strong></td>
<td style="border:1px solid black;"><strong>Título do boletim e Resumo executivo</strong></td>
<td style="border:1px solid black;"><strong>Classificação máxima de gravidade e impacto da vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>Requisitos de reinicialização</strong></td>
<td style="border:1px solid black;"><strong>Software afetado</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-064">MS14-064</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Windows OLE podem permitir a execução remota de código (3011443)</strong><br />
<br />
Esta atualização de segurança resolve duas vulnerabilidades relatadas de forma privada no componente OLE do Microsoft Windows. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário visualizar uma página da Web criada especialmente usando o Internet Explorer. Um invasor que tenha conseguido explorar as vulnerabilidades pode executar um código arbitrário no contexto do usuário atual. Se o usuário atual estiver conectado com direitos de administrador, um invasor poderá instalar programas, exibir, alterar ou excluir dados e criar novas contas com direitos totais do usuário. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-065">MS14-065</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (3003057)<br />
<br />
</strong>Esta atualização de segurança resolve dezessete vulnerabilidades relatadas de forma privada no Internet Explorer. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário visualizar uma página da Web criada especialmente usando o Internet Explorer. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-066">MS14-066</a></td>
<td style="border:1px solid black;"><strong>Uma vulnerabilidade no Schannel pode permitir a execução remota de código (2992611)<br />
<br />
</strong>Esta atualização de segurança 2976627 resolve uma vulnerabilidade relatada de forma privada no pacote de segurança Microsoft Security Channel (Schannel) no Windows. A vulnerabilidade pode permitir a execução remota de código se um invasor enviar pacotes especialmente criados para um servidor Windows.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-067">MS14-067</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no XML Core Services pode permitir a execução remota de código (2993958)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um usuário conectado visitar um site especialmente criado, projetado para invocar o Microsoft XML Core Services (MSXML) pelo Internet Explorer. No entanto, em todos os casos, um invasor não teria como forçar os usuários a visitarem os sites. Em vez disso, um invasor tem que convencer os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um email ou uma mensagem instantânea que leve o usuário ao site do invasor.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-068">MS14-068</a></td>
<td style="border:1px solid black;"><strong>Uma vulnerabilidade no Kerberos pode permitir elevação de privilégios (3011780)<br />
</strong><br />
Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada no Microsoft Windows Kerberos KDC, que pode permitir que um invasor eleve privilégios de conta de usuário do domínio não privilegiáveis para aqueles da conta de administrador do domínio. Um invasor pode usar esses privilégios elevados para comprometer qualquer computador do domínio, inclusive os controladores de domínio. O invasor precisa ter credenciais de domínio válidas para explorar essa vulnerabilidade. O componente afetado fica disponível remotamente para usuários que tenham contas de usuário padrão com credenciais de domínio; este não é o caso de usuários que possuam apenas credenciais de contas locais. Quando este boletim de segurança foi emitido, a Microsoft estava ciente de ataques limitados e direcionados que tentaram explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Crítico</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-069">MS14-069</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Office podem permitir a execução remota de código (3009710)<br />
<br />
</strong>Esta atualização de segurança resolve três vulnerabilidades relatadas de forma privada no Microsoft Office. Essas vulnerabilidades podem permitir a execução remota de código se um arquivo especialmente criado for aberto em uma edição afetada do Microsoft Office 2007. Um invasor que consiga explorar essa vulnerabilidade pode obter os mesmos direitos de usuário que o usuário atual. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-070">MS14-070</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no TCP/IP pode permitir a elevação de privilégio (2989935)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada de forma pública no TCP/IP, que ocorre durante o processamento de controle de entrada/saída (IOCTL). Essa vulnerabilidade pode permitir a elevação de privilégio se um invasor fizer logon em um sistema e executar um aplicativo especialmente criado. O invasor que explorar a vulnerabilidade com êxito poderá executar código arbitrário no contexto de outro processo. Se este processo for executado com privilégios de administrador, um invasor poderá instalar programas, exibir, alterar ou excluir dados e criar novas contas com direitos totais do usuário.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-071">MS14-071</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no serviço de áudio do Windows pode permitir a elevação de privilégio (3005607)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um aplicativo usar o serviço de áudio do Microsoft Windows. A vulnerabilidade não permite, por si só, que um código arbitrário seja executado. Para isso, ela tem que ser usada com outra vulnerabilidade que permita a execução remota de código.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-072">MS14-072</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no .NET Framework pode permitir elevação de privilégio (3005210)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada no Microsoft .NET Framework. A vulnerabilidade pode permitir elevação de privilégio se um invasor enviar dados criados especialmente para uma estação de trabalho ou servidor afetado que use comunicação remota no .NET. Somente aplicativos personalizados que tenham sido especificamente projetados para usar comunicação remota no .NET podem expor o sistema à vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-073">MS14-073</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft SharePoint Foundation pode permitir a elevação de privilégio (3000431)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada no Microsoft SharePoint Server. Um invasor autenticado que consiga explorar essa vulnerabilidade pode executar um script arbitrário no contexto do usuário no site atual do SharePoint. Em um cenário de ataque com base na Web, um invasor pode hospedar um site especialmente criado para explorar essas vulnerabilidade e convencer um usuário a visualizar o site. O invasor também pode tirar proveito dos sites comprometidos e de sites que aceitam ou hospedam o conteúdo fornecido pelo usuário ou anúncios. Esses sites podem conter conteúdo especialmente criado para explorar essas vulnerabilidades. No entanto, em todos os casos, o invasor não tem como forçar os usuários a exibir o conteúdo controlado pelo invasor. Em vez disso, o invasor precisa convencer os usuários a executar uma ação, normalmente clicando em um link em uma mensagem de email ou em uma mensagem do Instant Messenger que leve os usuários ao site do invasor ou abrindo um anexo enviado por email.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-074">MS14-074</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Remote Desktop Protocol pode permitir o desvio do recurso de segurança (3003743)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada no Microsoft Windows. A vulnerabilidade pode permitir o desvio do recurso de segurança quando o protocolo RDP (Remote Desktop Protocol) não consegue registrar eventos de auditoria corretamente. Por padrão, o RDP não está habilitado em nenhum sistema operacional Windows. Sistemas que não têm o RDP habilitado não correm risco.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Desvio do recurso de segurança</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-076">MS14-076</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade nos Serviços de Informações da Internet (IIS) pode permitir o desvio de um recurso de segurança (2982998)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada nos Serviços de Informações da Internet (IIS) da Microsoft, que pode fazer com que o recurso de segurança &quot;restrições de IP e domínio&quot; seja ignorado. Se bem sucedida, a exploração dessa vulnerabilidade pode permitir que clientes de domínios restritos ou bloqueados tenham acesso a recursos Web restritos.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Desvio do recurso de segurança</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-077">MS14-077</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade nos Serviços de Federação do Active Directory pode permitir a divulgação de informações (3003381)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada nos Serviços de Federação do Active Directory (AD FS). A vulnerabilidade pode permitir a divulgação de informações se o usuário deixar o navegador aberto após terminar uma sessão de um aplicativo e um invasor reabrir o aplicativo no navegador imediatamente após o término da sessão.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Importante</a><br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-078">MS14-078</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no IME (japonês) pode permitir elevação de privilégio (2992719)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada no Microsoft IME (Input Method Editor) (japonês). A vulnerabilidade pode permitir uma fuga da área de segurança com base na diretiva da área de segurança em um sistema onde uma versão afetada do Microsoft IME (japonês) está instalada. Um invasor que explorar com êxito esta vulnerabilidade pode escapar da área de segurança de um aplicativo vulnerável e ter acesso ao sistema com direitos de usuário conectado. Se o sistema afetado estiver conectado com direitos administrativos, um invasor poderá instalar programas, exibir, alterar ou excluir dados e criar novas contas com direitos totais de administração.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Moderado</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/pt-br/library/security/ms14-079">MS14-079</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no driver do modo kernel pode permitir a negação de serviço (3002885)<br />
<br />
</strong>Esta atualização de segurança resolve uma vulnerabilidade relatada de forma privada no Microsoft Windows. A vulnerabilidade pode permitir negação de serviço se um invasor colocar uma fonte TrueType especialmente criada em um compartilhamento de rede e o usuário navegar por ela com o Windows Explorer. Em um cenário de ataque baseado na Web, o invasor pode hospedar um site que contenha uma página da Web usada para explorar essa vulnerabilidade. Além disso, sites comprometidos e sites que aceitem ou hospedem conteúdo fornecido pelo usuário ou anúncios podem conter conteúdo especialmente criado que pode explorar esta vulnerabilidade. No entanto, em todos os casos, um invasor não teria como forçar os usuários a visitarem os sites. Em vez disso, o invasor teria que persuadir os usuários a visitar um site, geralmente fazendo com que cliquem em um link em uma mensagem de email ou do Instant Messenger que os leve para esse site.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/gg309177.aspx">Moderado</a><br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
 
  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidade são listadas em ordem de ID do boletim, depois de ID do CVE. Só serão incluídas as vulnerabilidades que tiverem uma classificação de gravidade Crítica ou Importante nos boletins.
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Índice de Exploração da Microsoft](http://technet.microsoft.com/pt-br/security/cc998259).
  
Nas colunas a seguir, "Versão mais Recente de Software" se refere ao software, e "Versões mais Antigas de Software se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**ID do boletim**

</td>
<td style="border:1px solid black;">
**Título da vulnerabilidade**

</td>
<td style="border:1px solid black;">
**ID do CVE**

</td>
<td style="border:1px solid black;" colspan="2">
**Avaliação da capacidade de exploração da última versão de software**

</td>
<td style="border:1px solid black;" colspan="2">
**Avaliação da capacidade de exploração de versão mais antiga de software**

</td>
<td style="border:1px solid black;">
**Avaliação do risco de exploração para negação de serviço**

</td>
<td style="border:1px solid black;">
**Principais observações**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-064](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código na matriz de automação do Windows OLE

</td>
<td style="border:1px solid black;">
[CVE-2014-6332](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6332)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-064](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código no Windows OLE

</td>
<td style="border:1px solid black;">
[CVE-2014-6352](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6352)

</td>
<td style="border:1px solid black;" colspan="2">
0 - Exploração detectada

</td>
<td style="border:1px solid black;" colspan="2">
0 - Exploração detectada

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
A Microsoft está ciente dos ataques limitados que tentam explorar essa vulnerabilidade.  
Essa vulnerabilidade for descrita pela primeira vez no Comunicado de Segurança da Microsoft [3010060](https://technet.microsoft.com/pt-br/library/security/3010060.aspx).

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-4143](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4143)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações na área de transferência do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6323](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6323)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Essa é uma vulnerabilidade de divulgação não autorizada de informações.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6337](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6337)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de desvio de ASLR no Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6339](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6339)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de desvio de recurso de segurança.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Internet Explorer em domínios

</td>
<td style="border:1px solid black;">
[CVE-2014-6340](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6340)

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Essa é uma vulnerabilidade de divulgação não autorizada de informações.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6341](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6341)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6342](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6342)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6343](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6343)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6344](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6344)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Internet Explorer em domínios

</td>
<td style="border:1px solid black;">
[CVE-2014-6345](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6345)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Essa é uma vulnerabilidade de divulgação não autorizada de informações.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações do Internet Explorer em domínios

</td>
<td style="border:1px solid black;">
[CVE-2014-6346](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6346)

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Essa é uma vulnerabilidade de divulgação não autorizada de informações.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6347](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6347)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
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
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6348](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6348)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Elevação de Vulnerabilidade de Privilégio do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6349](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6349)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de elevação de privilégio.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Elevação de Vulnerabilidade de Privilégio do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6350](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6350)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de elevação de privilégio.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6351](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6351)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-065](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de corrupção de memória do Internet Explorer

</td>
<td style="border:1px solid black;">
[CVE-2014-6353](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6353)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-066](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código no Microsoft Schannel

</td>
<td style="border:1px solid black;">
[CVE-2014-6321](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6321)

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;">
Permanente

</td>
<td style="border:1px solid black;">
(Nenhum)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-067](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código no MSXML

</td>
<td style="border:1px solid black;">
[CVE-2014-4118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4118)

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

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
[MS14-068](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
Vulnerabilidade na soma de verificação do Kerberos

</td>
<td style="border:1px solid black;" colspan="2">
[CVE-2014-6324](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6324)

</td>
<td style="border:1px solid black;">
1 - Probabilidade maior de exploração

</td>
<td style="border:1px solid black;">
0 - Exploração detectada

</td>
<td style="border:1px solid black;" colspan="2">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de elevação de privilégio.  
A Microsoft está ciente dos ataques direcionados limitados que tentam explorar essa vulnerabilidade.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-069](https://technet.microsoft.com/pt-br/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código de eliminação dupla no Microsoft Office

</td>
<td style="border:1px solid black;">
[CVE-2014-6333](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6333)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

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
[MS14-069](https://technet.microsoft.com/pt-br/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código de índice falso no Microsoft Office

</td>
<td style="border:1px solid black;">
[CVE-2014-6334](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6334)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

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
[MS14-069](https://technet.microsoft.com/pt-br/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de execução remota de código de ponteiro inválido no Microsoft Office

</td>
<td style="border:1px solid black;">
[CVE-2014-6335](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6335)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
1 - Probabilidade maior de exploração

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
[MS14-070](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio no TCP/IP

</td>
<td style="border:1px solid black;">
[CVE-2014-4076](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4076)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;">
Permanente

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de elevação de privilégio.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-071](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
Vulnerabilidade no serviço de áudio do Windows

</td>
<td style="border:1px solid black;">
[CVE-2014-6322](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6322)

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de elevação de privilégio.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-072](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de TypeFilterLevel

</td>
<td style="border:1px solid black;">
[CVE-2014-4149](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4149)

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de elevação de privilégio.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-073](https://technet.microsoft.com/pt-br/library/security/ms14-073)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio no SharePoint

</td>
<td style="border:1px solid black;">
[CVE-2014-4116](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4116)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
2 - Probabilidade menor de exploração

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de elevação de privilégio.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-074](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
Incapacidade do protocolo RDP (Remote Desktop Protocol) de auditar vulnerabilidade

</td>
<td style="border:1px solid black;">
[CVE-2014-6318](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6318)

</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável

</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de desvio de recurso de segurança.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-076](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de desvio de recurso de segurança de IIS

</td>
<td style="border:1px solid black;">
[CVE-2014-4078](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4078)

</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável

</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de desvio de recurso de segurança.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-077](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de divulgação não autorizada de informações nos Serviços de Federação do Active Directory

</td>
<td style="border:1px solid black;">
[CVE-2014-6331](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6331)

</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável

</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Essa é uma vulnerabilidade de divulgação não autorizada de informações.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-078](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de elevação de privilégio no Microsoft IME (japonês)

</td>
<td style="border:1px solid black;">
[CVE-2014-4077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4077)

</td>
<td style="border:1px solid black;" colspan="2">
Não afetado

</td>
<td style="border:1px solid black;" colspan="2">
0 - Exploração detectada

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Esta é uma vulnerabilidade de elevação de privilégio.

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[MS14-079](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
<td style="border:1px solid black;">
Vulnerabilidade de negação de serviços do driver do modo kernel no Windows

</td>
<td style="border:1px solid black;">
[CVE-2014-6317](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6317)

</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável

</td>
<td style="border:1px solid black;" colspan="2">
3 - Exploração improvável

</td>
<td style="border:1px solid black;">
Permanente

</td>
<td style="border:1px solid black;">
Essa é uma vulnerabilidade de negação de serviço.

</td>
</tr>
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
<td style="border:1px solid black;" colspan="14">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3006226)  
(Crítico)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(Moderado)  
Internet Explorer 7  
(3003057)  
(Moderado)  
Internet Explorer 8  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2989935)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2978114)  
(Importante)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2978124)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
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
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3006226)  
(Crítico)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(Moderado)  
Internet Explorer 7  
(3003057)  
(Moderado)  
Internet Explorer 8  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2989935)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978124)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
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
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(3006226)  
(Crítico)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(Moderado)  
Internet Explorer 7  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(2989935)  
(Importante)

</td>
<td style="border:1px solid black;">
Não aplicável

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978124)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
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
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados em Itanium  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
**Nenhuma**

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
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3006226)  
(Crítico)  
Windows Vista Service Pack 2  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(Crítico)  
Internet Explorer 8  
(3003057)  
(Crítico)  
Internet Explorer 9  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3011780)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3003743)  
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
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3006226)  
(Crítico)  
Windows Vista x64 Edition Service Pack 2  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(Crítico)  
Internet Explorer 8  
(3003057)  
(Crítico)  
Internet Explorer 9  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3011780)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3003743)  
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
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(3006226)  
(Crítico)  
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(Moderado)  
Internet Explorer 8  
(3003057)  
(Moderado)  
Internet Explorer 9  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Não aplicável

</td>
<td style="border:1px solid black;">
Serviços de Federação do Active Directory 2.0  
(3003381)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(3006226)  
(Crítico)  
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(Moderado)  
Internet Explorer 8  
(3003057)  
(Moderado)  
Internet Explorer 9  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Não aplicável

</td>
<td style="border:1px solid black;">
Serviços de Federação do Active Directory 2.0  
(3003381)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para Sistemas baseados em x64  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3006226)  
(Crítico)  
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em Itanium  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
**Nenhuma**

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
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3006226)  
(Crítico)  
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(Crítico)  
Internet Explorer 9  
(3003057)  
(Crítico)  
Internet Explorer 10  
(3003057)  
(Crítico)  
Internet Explorer 11  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3011780)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3003743)  
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
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas de 32 bits  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3006226)  
(Crítico)  
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(Crítico)  
Internet Explorer 9  
(3003057)  
(Crítico)  
Internet Explorer 10  
(3003057)  
(Crítico)  
Internet Explorer 11  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3011780)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3003743)  
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
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows 7 Service Pack 1 para sistemas baseados em x64  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3006226)  
(Crítico)  
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(Moderado)  
Internet Explorer 9  
(3003057)  
(Moderado)  
Internet Explorer 10  
(3003057)  
(Moderado)  
Internet Explorer 11  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Não aplicável

</td>
<td style="border:1px solid black;">
Serviços de Federação do Active Directory 2.0  
(3003381)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(3006226)  
(Crítico)  
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados no Itanium  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados no Itanium  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados no Itanium  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 8 e Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
**Nenhuma**

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
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3006226)  
(Crítico)  
Windows 8 para sistemas de 32 bits  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3011780)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.0  
(2982998)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3006226)  
(Crítico)  
Windows 8 para sistemas baseados em x64  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3011780)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(2978121)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
IIS (Serviços de Informações da Internet) 8.0 da Microsoft  
(2982998)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3006226)  
(Crítico)  
Windows 8.1 para sistemas de 32 bits  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3011780)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(2978122)  
(Importante)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Internet Information Services 8.5  
(2982998)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3006226)  
(Crítico)  
Windows 8.1 para sistemas baseados em x64  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3011780)  
(Nenhuma classificação de gravidade)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(2978122)  
(Importante)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
IIS (Serviços de Informações da Internet) 8.5 da Microsoft  
(2982998)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2012 e Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3006226)  
(Crítico)  
Windows Server 2012  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(2978121)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
IIS (Serviços de Informações da Internet) 8.0 da Microsoft  
(2982998)  
(Importante)

</td>
<td style="border:1px solid black;">
Serviços de Federação do Active Directory 2,1  
(3003381)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3006226)  
(Crítico)  
Windows Server 2012 R2  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(2978122)  
(Importante)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
IIS (Serviços de Informações da Internet) 8.5 da Microsoft  
(2982998)  
(Importante)

</td>
<td style="border:1px solid black;">
Serviços de Federação do Active Directory 3,0  
(3003381)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows RT e Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Crítico**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

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
**Nenhuma**

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
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3006226)  
(Crítico)  
Windows RT  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows RT  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows RT  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(3003743)  
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
<td style="border:1px solid black;">
Windows RT  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3006226)  
(Crítico)  
Windows RT 8.1  
(3010788)  
(Importante)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2993958)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3005607)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3003743)  
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
<td style="border:1px solid black;">
Windows RT 8.1  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Opção de instalação Server Core**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://technet.microsoft.com/pt-br/library/security/ms14-064)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://technet.microsoft.com/pt-br/library/security/ms14-065)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://technet.microsoft.com/pt-br/library/security/ms14-066)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://technet.microsoft.com/pt-br/library/security/ms14-067)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://technet.microsoft.com/pt-br/library/security/ms14-068)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://technet.microsoft.com/pt-br/library/security/ms14-070)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://technet.microsoft.com/pt-br/library/security/ms14-071)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://technet.microsoft.com/pt-br/library/security/ms14-072)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://technet.microsoft.com/pt-br/library/security/ms14-074)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://technet.microsoft.com/pt-br/library/security/ms14-076)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://technet.microsoft.com/pt-br/library/security/ms14-077)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://technet.microsoft.com/pt-br/library/security/ms14-079)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

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
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Importante**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3006226)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3011780)  
(Crítico)

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
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas de 32 bits (instalação Server Core)  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3006226)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core) (2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core) (2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3011780)  
(Crítico)

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
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 Service Pack 2 para sistemas baseados em x64 (instalação Server Core)  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3006226)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(Importante)  
Microsoft .NET Framework 4  
(2978125)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(2991963)  
(Moderado)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 Service Pack 1 para sistemas baseados em x64 (instalação Server Core)  
(3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3006226)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core) (2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não aplicável

</td>
<td style="border:1px solid black;">
Não aplicável

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(2978121)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core) (3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2982998)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core) (3002885)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3006226)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(2992611)  
(Crítico)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(2993958)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3011780)  
(Crítico)

</td>
<td style="border:1px solid black;">
Não aplicável

</td>
<td style="border:1px solid black;">
Não aplicável

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3,5  
(2978122)  
(Importante)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3003743)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(2982998)  
(Importante)

</td>
<td style="border:1px solid black;">
Serviços de Federação do Active Directory 3,0  
(3003381)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(3002885)  
(Moderado)

</td>
</tr>
</table>

<p></p>

 
**Observação para MS14-064, MS14-065 e MS14-067**

As visualizações técnicas do Windows e do Windows são afetadas. Os clientes que executam esses sistemas operacionais são incentivados a aplicar a atualização que está disponível no [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=pt-br).

**Observações para o MS14-068**

As visualizações técnicas do Windows e do Windows são afetadas. Os clientes que executam esses sistemas operacionais são incentivados a aplicar a atualização que está disponível no [Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=pt-br).

<sup>[1]</sup>As classificações de gravidade não se aplicam a esse sistema operacional porque a vulnerabilidade de que trata este boletim não está presente. Esta atualização fornece uma proteção extra de [defesa aprofundada](https://technet.microsoft.com/pt-br/library/security/dn848375.aspx) que não corrige qualquer vulnerabilidade conhecida. 

**Observação para o MS14-078**

Este boletim abrange mais de uma categoria de software. Consulte as outras tabelas nesta seção para saber quais softwares foram afetados.

 

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
[**MS14-069**](https://technet.microsoft.com/pt-br/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

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
[**Moderado**](http://technet.microsoft.com/pt-br/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2899527)  
(Importante)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 IME (japonês)  
(2889913)  
(Moderado)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Outros softwares do Microsoft Office**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-069**](https://technet.microsoft.com/pt-br/library/security/ms14-069)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://technet.microsoft.com/pt-br/library/security/ms14-078)

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
**Nenhuma**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2899553)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3

</td>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3  
(2899526)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
</table>

<p></p>

 
**Observação para o MS14-078**

Este boletim abrange mais de uma categoria de software. Consulte as outras tabelas nesta seção para saber quais softwares foram afetados.

 

### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
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
[**MS14-073**](https://technet.microsoft.com/pt-br/library/security/ms14-073)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2  
(2889838)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O Microsoft Baseline Security Analyzer (MBSA) permite aos administradores procurar em sistemas remotos e locais para as atualizações de segurança que ainda não foram instaladas e por erros comuns em configuração de segurança.

O Windows Server Update Services (WSUS), o Systems Management Server (SMS) e o System Center Configuration Manager ajudam os administradores a distribuir atualizações de segurança.

Os componentes do Avaliador de compatibilidade com atualizações, incluídos no Kit de Ferramentas de Compatibilidade de Aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para obter informações sobre estas e outras ferramentas disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/pt-br/security/cc297183).

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
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [artigo 913086 da Base de Dados de Conhecimento da Microsoft](https://support.microsoft.com/kb/913086/pt-br).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://technet.microsoft.com/pt-br/security/cc136632.aspx).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://support2.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle).

Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/pt-br/security/bb980617)

Ajude a proteger seu computador executando o Windows contra vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=pt-br)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx?ln=pt-br)

### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Dados de Conhecimento da Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (11 de novembro de 2014): Resumo do boletim publicado.
-   V2.0 (18 de novembro de 2014): Resumo do Boletim revisado para documentar o lançamento fora de banda do MS14-068 e, para o MS14-066, para anunciar a nova oferta da atualização 2992611 para os sistemas executando o Windows Server 2008 R2 e Windows Server 2012.
-   V2.1 (19 de dezembro de 2014): Resumo do Boletim revisado para incluir a instalação do Windows 2012 Server Core e a instalação do Windows 2012 Server Core na tabela do software afetado para MS14-076.

*Página gerada em 19.12.14 13:20Z-08:00.*
