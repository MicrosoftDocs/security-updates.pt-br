---
TOCTitle: 'MS09-OCT'
Title: Resumo do Boletim de Segurança da Microsoft de outubro 2009
ms:assetid: 'ms09-oct'
ms:contentKeyID: 61233656
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms09-oct(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de outubro 2009
===========================================================

Publicado: quinta-feira, 1 de outubro de 2009 | Atualizado: terça-feira, 22 de junho de 2010

**Versão:** 4.2

Este resumo de boletins lista os boletins de segurança lançados em outubro de 2009.

Com o lançamento dos boletins de outubro de 2009, este resumo de boletins substitui a notificação antecipada de boletim lançada originalmente em 8 de outubro de 2009. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada do Boletim de Segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 14 de outubro de 2009, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de outubro](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407488&culture=en-us). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações de alta prioridade que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-050">MS09-050</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no SMBv2 podem permitir a execução remota de código (975517)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e duas reportadas em particular no Procotocolo SMB Versão 2 (SMBv2). A mais severa das vulnerabilidades pode permitir a execução remota de código se um invasor enviar um pacote SMB especialmente criado a um computador que esteja executando o serviço de Servidor. As práticas recomendadas de firewall e as configurações de firewall padrão podem ajudar a proteger as redes contra ataques com origem externa ao perímetro da empresa. Essas práticas também recomendam que os sistemas conectados à Internet tenham um número mínimo de portas expostas.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-051">MS09-051</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Tempo de execução do Windows Media podem permitir a execução remota de código (975682)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Tempo de execução do Windows Media. As vulnerabilidades podem permitir a execução remota de código se um usuário abrir um arquivo de mídia especialmente criado ou conteúdo de fluxo especialmente criado recebido de um site ou de qualquer aplicativo que entregue conteúdo da Web. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário local. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-052">MS09-052</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Windows Media Player pode permitir a execução remota de código (974112)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Windows Media Player. A vulnerabilidade pode permitir a execução remota de código se um arquivo ASF especialmente criado for reproduzido usando o Windows Media Player 6.4. Um invasor que explorar com êxito esta vulnerabilidade pode ganhar os mesmos direitos de usuário do usuário local. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-054">MS09-054</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para Internet Explorer (974455)</strong><br />
<br />
Esta atualização de segurança crítica resolve três vulnerabilidades no Internet Explorer reportadas em particular e uma divulgada publicamente. As vulnerabilidades podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. Os usuários do Firefox que executam o plug-in Windows Presentation Foundation (WPF) e não o desabilitaram também devem aplicar esta atualização de segurança. Para obter mais informações sobre este problema, consulte a seção de Perguntas frequentes da Vulnerabilidade de manipulação de componente HTML – CVE-2009-2529.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-055">MS09-055</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa de Kill Bits do ActiveX (973525)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular, comum a vários controles ActiveX, que está sendo explorada no momento. A vulnerabilidade que afeta os controles ActiveX que foram compiladas com a versão vulnerável da Microsoft Active Template Library (ATL) pode permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada com o Internet Explorer, instanciando o controle ActiveX. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-060">MS09-060</a></td>
<td style="border:1px solid black;"><strong>nos Controles ActiveX da Microsoft Active Template Library (ATL) para Microsoft Office podem permitir a execução remota de código (973965)</strong><br />
<br />
Esta atualização de segurança elimina várias vulnerabilidades relatadas em particular nos Controles ActiveX do Microsoft Office que foram compilados com uma versão vulnerável da Microsoft Active Template Library (ATL). As vulnerabilidades podem permitir a execução remota de código se um usuário carregar um componente ou controle especialmente criado. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-061">MS09-061</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no CLR do Microsoft .NET podem permitir a execução remota de código (974378)</strong><br />
<br />
Esta atualização de segurança elimina três vulnerabilidades relatadas em particular no Microsoft .NET Framework e no Microsoft Silverlight. As vulnerabilidades podem permitir a execução remota de código em um sistema cliente se o usuário exibir uma página da Web especialmente criada usando um navegador da Web que possa executar Aplicativos de navegador XAML (XBAPs) ou Silverlight, ou se um invasor conseguir convencer o usuário a executar um aplicativo Microsoft .NET especialmente criado. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. As vulnerabilidades também podem permitir a execução remota de código em um sistema de servidor que esteja executando o IIS, se esse servidor permitir o processamento de páginas ASP.NET e um invasor conseguir carregar uma página ASP.NET especialmente criada nesse servidor e executá-la, como pode ser o caso em um cenário de hospedagem na Web. Os aplicativos Microsoft .NET, Silverlight, XBAPs e páginas ASP.NET que não são mal-intencionados não correm risco de serem comprometidos por esta vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-062">MS09-062</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no GDI+ pode permitir a execução remota de código (957488)</strong><br />
<br />
Esta atualização de segurança elimina várias vulnerabilidades relatadas em particular no Microsoft Windows GDI+. Estas vulnerabilidades podem permitir a execução remota de código se um usuário visualizar um arquivo de imagem especialmente criado usando software afetado ou procurar um site que contenha conteúdo especialmente criado. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer,<br />
Microsoft .NET Framework,<br />
Microsoft Office,<br />
Microsoft SQL Server,<br />
Ferramentas para desenvolvedor da Microsoft,<br />
Microsoft Forefront</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-053">MS09-053</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Serviço FTP para Serviços de Informações da Internet podem permitir a execução remota de código (975254)</strong><br />
<br />
Esta atualização de segurança resolve duas vulnerabilidades divulgadas publicamente no Serviço FTP nos Serviços de Informações da Internet (ISS) 5.0 da Microsoft, Serviços de Informações da Internet (ISS) 5.1 da Microsoft, Serviços de Informações da Internet (ISS) 6.0 da Microsoft e Serviços de Informações da Internet (ISS) 7.0 da Microsoft. No IIS 7.0, somente o Serviço FTP 6.0 é afetado. As vulnerabilidades podem permitir a execução remota de código (RCE) em sistemas que executam o Serviço FTP no IIS 5.0 ou negação de serviço (DoS) em sistemas que executam o Serviço FTP no IIS 5.0, IIS 5.1, IIS 6.0 ou IIS 7.0.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-056">MS09-056</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Windows CryptoAPI podem permitir falsificação (974571)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades divulgadas publicamente no Microsoft Windows. As vulnerabilidades podem permitir falsificação se um invasor conseguir obter acesso ao certificado usado pelo usuário final para autenticação.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Falsificação</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-057">MS09-057</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no serviço de indexação pode permitir a execução remota de código (969059)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um invasor configurar uma página da Web mal-intencionada que invoque o Serviço de Indexação por meio de uma chamada do seu componente ActiveX. Esta chamada pode incluir uma URL mal-intencionada e explora a vulnerabilidade, concedendo acesso ao invasor ao sistema cliente com privilégios do usuário que está navegando na página da Web. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-058">MS09-058</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades do kernel do Windows podem permitir a elevação de privilégio (971486)</strong><br />
<br />
Esta atualização de segurança elimina várias vulnerabilidades relatadas em particular no kernel do Windows. A mais severa das vulnerabilidades poderá permitir a elevação de privilégio se um invasor se conectar ao sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essas vulnerabilidades. Essas vulnerabilidades não podem ser exploradas remotamente ou por usuários anônimos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-059">MS09-059</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no LSASS (Local Security Authority Subsystem Service) pode permitir negação de serviço (975467)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir negação de serviço se um invasor enviar um pacote criado com intuito de ser mal-intencionado durante o processo de autenticação de NTLM.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas em ordem de ID do boletim e de ID da CVE.
  
**Como devo usar a tabela?**  
  
Use esta tabela para conhecer a probabilidade de o código de exploração em funcionamento ser lançado em 30 dias contados do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Você deve revisar cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade a sua implantação. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| ID do Boletim                                                       | Título do Boletim                                                                                                                                           | ID do CVE                                                                         | Avaliação do índice de exploração                                                                                     | Principais observações                                                                                                                                                                                                                                                                                                                                                                                                               |  
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-050](http://technet.microsoft.com/security/bulletin/ms09-050) | Vulnerabilidades no SMBv2 podem permitir a execução remota de código (975517)                                                                               | [CVE-2009-2526](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2526)  | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Essa é uma vulnerabilidade de negação de serviço limitada.                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-050](http://technet.microsoft.com/security/bulletin/ms09-050) | Vulnerabilidades no SMBv2 podem permitir a execução remota de código (975517)                                                                               | [CVE-2009-2532](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2532)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-050](http://technet.microsoft.com/security/bulletin/ms09-050) | Vulnerabilidades no SMBv2 podem permitir a execução remota de código (975517)                                                                               | [CVE-2009-3103](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3103)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | O código de exploração foi divulgado publicamente.                                                                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-051](http://technet.microsoft.com/security/bulletin/ms09-051) | Vulnerabilidades no Tempo de Execução do Windows Media podem permitir a execução remota de código (975682)                                                  | [CVE-2009- 0555](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0555) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-051](http://technet.microsoft.com/security/bulletin/ms09-051) | Vulnerabilidades no Tempo de Execução do Windows Media podem permitir a execução remota de código (975682)                                                  | [CVE-2009- 2525](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2525) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-052](http://technet.microsoft.com/security/bulletin/ms09-052) | Vulnerabilidade no Windows Media Player pode permitir a execução remota de código (974112)                                                                  | [CVE-2009-2527](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2527)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-053](http://technet.microsoft.com/security/bulletin/ms09-053) | Vulnerabilidades no Serviço FTP para Serviços de Informações da Internet podem permitir a execução remota de código (975254)                                | [CVE-2009-2521](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2521)  | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Essa é uma vulnerabilidade de negação de serviço (site em inglês). O código de exploração foi divulgado publicamente.                                                                                                                                                                                                                                                                                                                |  
| [MS09-053](http://technet.microsoft.com/security/bulletin/ms09-053) | Vulnerabilidades no Serviço FTP para Serviços de Informações da Internet podem permitir a execução remota de código (975254)                                | [CVE-2009-3023](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3023)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | O código de exploração foi divulgado publicamente.                                                                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-054](http://technet.microsoft.com/security/bulletin/ms09-054) | Atualização de segurança cumulativa para Internet Explorer (974455)                                                                                         | [CVE-2009-1547](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1547)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-054](http://technet.microsoft.com/security/bulletin/ms09-054) | Atualização de segurança cumulativa para Internet Explorer (974455)                                                                                         | [CVE-2009-2529](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2529)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-054](http://technet.microsoft.com/security/bulletin/ms09-054) | Atualização de segurança cumulativa para Internet Explorer (974455)                                                                                         | [CVE-2009-2530](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2530)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | Em Microsoft Windows 2000 sistemas, a falta de proteções de amontoado aumenta a avaliação de índice de exploitability a [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - código de exploração Coerente possível.                                                                                                                                                                                                 |  
| [MS09-054](http://technet.microsoft.com/security/bulletin/ms09-054) | Atualização de segurança cumulativa para Internet Explorer (974455)                                                                                         | [CVE-2009-2531](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2531)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      |                                                                                                                                                                                                                                                                                                                                                                                                                                      |  
| [MS09-055](http://technet.microsoft.com/security/bulletin/ms09-055) | Atualização de segurança cumulativa de kill bits do ActiveX (973525)                                                                                        | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493)  | Nenhuma                                                                                                               | (A avaliação do índice de exploração desta vulnerabilidade já foi feita no [resumo dos boletins de julho](http://technet.microsoft.com/security/bulletin/ms09-jul). Isso porque esta vulnerabilidade foi abordada primeiramente no boletim [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035).) Também foi atribuído o mesmo número no boletim [MS09-060](http://technet.microsoft.com/security/bulletin/ms09-060). |  
| [MS09-056](http://technet.microsoft.com/security/bulletin/ms09-056) | Vulnerabilidades no Windows CryptoAPI podem permitir falsificação (974571)                                                                                  | [CVE-2009-2510](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2510)  | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Essa é uma vulnerabilidade de falsificação.                                                                                                                                                                                                                                                                                                                                                                                          |  
| [MS09-056](http://technet.microsoft.com/security/bulletin/ms09-056) | Vulnerabilidades no Windows CryptoAPI podem permitir falsificação (974571)                                                                                  | [CVE-2009-2511](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2511)  | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Essa é uma vulnerabilidade de falsificação.                                                                                                                                                                                                                                                                                                                                                                                          |  
| [MS09-057](http://technet.microsoft.com/security/bulletin/ms09-057) | Vulnerabilidade no Serviço de Indexação pode permitir a execução remota de código (969059)                                                                  | [CVE-2009-2507](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2507)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-058](http://technet.microsoft.com/security/bulletin/ms09-058) | Vulnerabilidades no kernel do Windows podem permitir elevação de privilégio (971486)                                                                        | [CVE-2009-2515](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2515)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-058](http://technet.microsoft.com/security/bulletin/ms09-058) | Vulnerabilidades no kernel do Windows podem permitir elevação de privilégio (971486)                                                                        | [CVE-2009-2516](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2516)  | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Esta vulnerabilidade causa uma condição de negação de de serviço quando apontada para usar um compartilhamento de rede e uma condição de elevação de privilégio quando usada localmente para apontar para um sistema local.                                                                                                                                                                                                          |  
| [MS09-058](http://technet.microsoft.com/security/bulletin/ms09-058) | Vulnerabilidades no kernel do Windows podem permitir elevação de privilégio (971486)                                                                        | [CVE-2009-2517](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2517)  | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Essa é uma vulnerabilidade de negação de serviço (site em inglês).                                                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-059](http://technet.microsoft.com/security/bulletin/ms09-059) | Vulnerabilidade no serviço LSASS pode permitir negação de serviço (975467)                                                                                  | [CVE-2009-2524](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2524)  | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Essa é uma vulnerabilidade de negação de serviço limitada.                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-060](http://technet.microsoft.com/security/bulletin/ms09-060) | Vulnerabilidades nos controles ActiveX da Microsoft Active Template Library (ATL) para Microsoft Office podem permitir a execução remota de código (973965) | [CVE-2009-0901](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901)  | Nenhuma                                                                                                               | (A avaliação do índice de exploração desta vulnerabilidade já foi feita no [resumo dos boletins de julho](http://technet.microsoft.com/security/bulletin/ms09-jul). Isso porque esta vulnerabilidade foi abordada primeiramente no boletim [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035).)                                                                                                                     |  
| [MS09-060](http://technet.microsoft.com/security/bulletin/ms09-060) | Vulnerabilidades nos controles ActiveX da Microsoft Active Template Library (ATL) para Microsoft Office podem permitir a execução remota de código (973965) | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493)  | Nenhuma                                                                                                               | (A avaliação do índice de exploração desta vulnerabilidade já foi feita no [resumo dos boletins de julho](http://technet.microsoft.com/security/bulletin/ms09-jul). Isso porque esta vulnerabilidade foi abordada primeiramente no boletim [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035).) Também foi atribuído o mesmo número no boletim [MS09-055](http://technet.microsoft.com/security/bulletin/ms09-055). |  
| [MS09-060](http://technet.microsoft.com/security/bulletin/ms09-060) | Vulnerabilidades nos controles ActiveX da Microsoft Active Template Library (ATL) para Microsoft Office podem permitir a execução remota de código (973965) | [CVE-2009-2495](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495)  | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Essa é uma vulnerabilidade de divulgação de informações.                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-061](http://technet.microsoft.com/security/bulletin/ms09-061) | Vulnerabilidades no Microsoft .NET Common Language Runtime podem permitir a execução remota de código (974378)                                              | [CVE-2009-0090](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0090)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-061](http://technet.microsoft.com/security/bulletin/ms09-061) | Vulnerabilidades no Microsoft .NET Common Language Runtime podem permitir a execução remota de código (974378)                                              | [CVE-2009-0091](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0091)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-061](http://technet.microsoft.com/security/bulletin/ms09-061) | Vulnerabilidades no Microsoft .NET Common Language Runtime podem permitir a execução remota de código (974378)                                              | [CVE-2009-2497](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2497)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | Existe um potencial para ataques que causam impacto na Internet.                                                                                                                                                                                                                                                                                                                                                                     |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | Vulnerabilidades no GDI+ podem permitir a execução remota de código (957488)                                                                                | [CVE-2009-2500](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2500)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | Vulnerabilidades no GDI+ podem permitir a execução remota de código (957488)                                                                                | [CVE-2009-2501](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2501)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | Vulnerabilidades no GDI+ podem permitir a execução remota de código (957488)                                                                                | [CVE-2009-2502](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2502)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | Vulnerabilidades no GDI+ podem permitir a execução remota de código (957488)                                                                                | [CVE-2009-2503](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2503)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | Vulnerabilidades no GDI+ podem permitir a execução remota de código (957488)                                                                                | [CVE-2009-2504](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2504)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | Vulnerabilidades no GDI+ podem permitir a execução remota de código (957488)                                                                                | [CVE-2009-2518](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2518)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | Vulnerabilidades no GDI+ podem permitir a execução remota de código (957488)                                                                                | [CVE-2009-2528](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2528)  | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-062](http://technet.microsoft.com/security/bulletin/ms09-062) | Vulnerabilidades no GDI+ podem permitir a execução remota de código (957488)                                                                                | [CVE-2009-3126](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3126)  | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                                                                                                                                             |
  
Softwares afetados e locais de download  
---------------------------------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
**Como uso estas tabelas?**  
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, haverá também um hiperlink para a atualização de software disponível e a classificação de gravidade da atualização de software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
#### Componentes e sistema operacional Windows

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="13">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
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
<td style="border:1px solid black;">
[**Nenhum**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[DirectShow WMA Voice Codec](http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
(Crítica)  
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=8f850a82-61f9-447b-a0aa-a2c192cc5d2e)  
(KB954155)  
(Crítica)  
[Gerenciador de Compactação de Áudio](http://www.microsoft.com/downloads/details.aspx?familyid=6dfd5405-cabe-4bd7-9330-b6bde1d99194)  
(KB975025)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=13035ef7-7e47-487c-8b7c-7795d33ce7de)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=26515c7b-d7a6-4405-96b5-a518dcb39d38)  
(Crítica)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8154ba37-0fbc-4d31-9d6e-0b21586ad65a)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=edfea805-9544-4dc0-a52c-d7594205657b)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f3fef608-dafb-4b37-a65a-9cc4ae8e2c4c)  
(KB958869)  
(Crítica)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ecf78619-80fa-417d-852b-1b5b2cf574e2)  
(KB971108)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3e534aa8-29c2-4379-9f57-931a6ff47418)  
(KB971110)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e6f5e730-85cc-4c08-a50d-c456b1e9f5bc)  
(KB971111)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=7fecd367-aaff-458b-91bc-8925c8e57528)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=52b9198d-b65f-467a-a5ab-141e23d64a86)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=b34d94b5-b828-4e16-a636-04344c60d945)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=bdfa6583-28a2-4d6b-91d2-157a8518b664)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="13">
Windows XP (site em inglês)
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
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
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 e Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[DirectShow WMA Voice Codec](http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
(Crítica)  
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=4516c219-e357-485e-a52b-23dcb8ee49d8)  
(KB954155)  
(Crítica)  
(Windows XP Service Pack 2 somente)  
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=746d3440-5a6a-421e-9286-7b534a1dfe54)  
(KB954155)  
(Crítica)  
(Windows XP Service Pack 3 somente)  
[Gerenciador de Compactação de Áudio](http://www.microsoft.com/downloads/details.aspx?familyid=6ecc7129-8caa-4daf-a8e2-8f3536225fb3)  
(KB975025)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=b2efe1ac-d8d7-41bb-b87d-fc5e22afef0f)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9aacf890-afb4-46a7-a13f-dd9fe3c0ca4a)  
(Crítica)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dc166dc6-577f-4d8d-94df-dd963233dd85)  
(Crítica)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8799159d-df69-49f6-9db5-49147690ce0c)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=171d43d3-669c-4923-b266-e47591833c05)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=1bc56c26-1c7c-47e3-94f4-37af7e00392c)  
(KB953295)  
(Crítica)  
(Somente Tablet PC Edition 2005 e Media Center Edition 2005)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e2acde20-a6d3-4135-b6eb-1214f743d474)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2ae0bdd4-f8b2-420a-b1ac-d2cdaa87c828)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9c5ab624-e37b-418a-a919-d8f652b15679)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=768fd74e-0a2f-4353-ac22-65d0d6321739)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cece4c55-0756-4357-9d2d-6709e8426068)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e997ea40-668e-40df-bd50-0ca53437b375)<sup>[1]</sup>
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[DirectShow WMA Voice Codec](http://www.microsoft.com/downloads/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a)  
(KB969878)  
(Crítica)  
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=4729de51-8fd8-46c6-b4ad-9c9f25202684)  
(KB954155)  
(Crítica)  
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2) no Windows Media Format SDK 9.5 x64 Edition  
(KB954155)  
(Crítica)  
[Decodificador de voz do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=a866a490-6d3a-4ecd-acf4-770312ba2fd6) no Windows Media Format SDK 11  
(KB954155)  
(Crítica)  
[Gerenciador de Compactação de Áudio](http://www.microsoft.com/downloads/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b)  
(KB975025)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=a9e7dfd8-7ba1-4f14-8e60-92ef00d91467)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=89a2cf2a-a7a2-4d4b-aa6f-24dde288d500)  
(Crítica)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=bd54e595-25f2-4839-a838-2a0f809bde2b)  
(Crítica)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=77b18fc2-e769-47c6-8e72-916716a49e58)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c08623bf-94bc-4c50-8c10-f50fb8448a0b)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad92503a-8c91-4d73-98b0-942d7961637d)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=819dd2d1-cad5-4784-9baf-185d8a76df5d)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad29696d-4611-4a12-9dfa-74fa6866b759)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=270ec100-5ba1-4f8c-aa36-105d30ad57bf)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5459b7d4-1fab-4a04-ab9d-b8323505c1e2)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=17008892-7950-44c4-850d-002c8d73495f)<sup>[1]</sup>
(Importante)
</td>
</tr>
<tr>
<th colspan="13">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[DirectShow WMA Voice Codec](http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
(Crítica)  
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=00b3cb86-c9eb-4fbe-987e-2b0d94271d87)  
(KB954155)  
(Crítica)  
[Gerenciador de Compactação de Áudio](http://www.microsoft.com/downloads/details.aspx?familyid=ab1803ff-2371-487f-a7b6-95747c46ba4e)  
(KB975025)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=5f82d01c-573e-425e-b9f2-86a54f377b19)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=8101625d-ee93-46e5-aec2-3bdbf2d86472)  
(Crítica)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4647bcf1-69fb-4ad6-9e03-7bc22d8a914b)  
(Crítica)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9eae7eca-1a6f-4397-a6e2-7dda6b9d5276)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f3249c99-82e4-45dc-a254-28e647e822c8)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d1b4a58b-f0b1-4400-a6e6-0255b0513bd1) (KB953298)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=414466a4-39a0-476d-9a43-ae7674cbd6a0)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48256ea3-b433-4e84-9019-22300069cfc1)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=78072164-84d1-44da-8ede-2a9d212d47a9)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1e3f3842-f8fd-4969-a2cf-706db38d7580)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9dff4662-7771-4bdc-87ec-7899d79b3a55)<sup>[1]</sup>
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[DirectShow WMA Voice Codec](http://www.microsoft.com/downloads/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a)  
(KB969878)  
(Crítica)  
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=13ba4839-7fa9-4bbb-95f6-3fafb6c49f20)  
(KB954155)  
(Crítica)  
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2) no Windows Media Format SDK 9.5 x64 Edition  
(KB954155)  
(Crítica)  
[Gerenciador de Compactação de Áudio](http://www.microsoft.com/downloads/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b)  
(KB975025)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=65e9036e-2e1b-40ff-a84b-c507107bcce8)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2f966053-01eb-4a23-a9d5-71deac2498ea)  
(Crítica)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e7d77bd9-8317-42f3-9ad1-a0b8bfa65b53)  
(Crítica)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=708a549d-11fd-43bf-a6e1-309e3205d59d)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1ad3f7b3-58d5-4507-ae20-a265e47cee9c)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eb95e8d9-6ef5-4526-99d2-507e50de049b)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=61bded07-201e-4815-ac1e-468bf907e063)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8aa1f97d-ad53-4450-bb93-4a147dd10a87)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=95286b8d-4b53-4e6c-af59-e9e18fad3559)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8df7a2d9-2f97-4f18-84e8-415a1632cf09)<sup>[1]</sup>
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
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
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=79a1a94d-3b47-47e9-9476-2f591c3f6a59)  
(Crítica)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=07e66c09-2cd7-47ba-bf87-d3da602184b4)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=575e75d9-e348-4fbb-9eaa-43240e4d715e)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=a678ceb9-a37a-4c29-8bd1-f209922990e5)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b99d4d9b-e0cc-4a8c-ad99-6a53958b37c8)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2ede1eb9-7f5f-411d-bbc3-5db46d80e0bb)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=fb5678b9-5ef1-42db-902e-c9ea02880e0a)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=faef714b-5f46-47f2-bea7-881df05a1bc0)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=83c77015-7f96-4c0d-bd56-60aef90ea2f8)<sup>[1]</sup>
(Importante)
</td>
</tr>
<tr>
<th colspan="13">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
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
Nenhuma
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=29842c0c-8930-4b5f-83c6-1a718974b63f)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Decodificador de voz de áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=f17ee0ea-f1e2-49f4-9f90-60296246ddfe)  
(KB954155)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f6995616-2a84-4c26-9599-26f1314873ed)  
(Crítica)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e8f6014f-950b-4e11-a105-51d298069f1a)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7313c03b-8844-4086-a0cc-43dfdb3ca48c)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Crítica)  
[Microsoft .NET Framework 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63) (KB974468)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882) (KB974292)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233) (KB974467)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=19aa01f3-026d-4264-85f8-216d0597969b)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bb96eb1c-66a2-4276-9773-eea22179bcd4)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b5a9a95-9439-40c8-acef-000b919daa04)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=04ae306b-0d0d-4767-ab54-cc11aec477ed)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda) (KB974291)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8) (KB974469)  
(Crítica)
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4) (KB974470)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97)  
(Moderada)
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=62ed5d0a-5ca6-4942-80c9-7808b14cb6b5)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Decodificador de voz de áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=26905f12-92c7-4d45-99e7-227f03d2cb82)  
(KB954155)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b3de5236-afdd-436e-8648-5382d564cc99)  
(Crítica)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=85978f28-5fc0-481b-9b03-2021c785889b)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7216bcb1-ff16-402b-ad1b-1500d46d0157)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Crítica)  
[Microsoft .NET Framework 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63) (KB974468)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882) (KB974292)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233) (KB974467)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8f5f0c1d-1dd6-47fa-aef2-d3c96c8fc06e)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bce096c8-833b-45c8-99cd-1280f0744f2f)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4a60f789-1a4a-49a8-8d13-fda989ed40be)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=58c995ca-f308-4e07-8e60-2e542384d95d)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda) (KB974291)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8) (KB974469)  
(Crítica)
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Crítica)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4) (KB974470)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434)  
(Moderada)
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
</tr>
<tr>
<th colspan="13">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Nenhuma
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
Windows Server 2008 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ff6bfcf3-76c9-4c45-b57d-22f94458dd6e)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=2eaa9857-a147-4f31-9bf4-b9e2cf4c15c3)\*\*  
(KB954155)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=72dd580e-eb53-41da-a5c0-a392ad388bfc)\*\*  
(Crítica)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1baf7e96-ba3e-47e7-8ea3-eb092e653a39)\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=51eb56fa-8204-45f3-86d7-6d03a2c8d78d)\*\*  
(Baixa)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda)\*\*  
(KB974291)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)\*\*  
(KB974469)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=fd1694af-8873-43aa-9243-91f7cde452b7)\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d9c5039f-d0cf-4d84-850f-f2f7701dcb79)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f9b487af-fe73-42a8-b240-d59c4321f95b)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f2f617c2-f149-4e9b-bfdd-08ed0f3f99db)\*  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)\*\*  
(KB974470)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423)\*  
(Moderada)
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aff6f9c7-4a72-48f2-b750-204d796c7daa)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Decodificador de voz e áudio do Windows Media](http://www.microsoft.com/downloads/details.aspx?familyid=70aabba3-53d6-4b52-be83-6d3f3869ecbd)\*\*  
(KB954155)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0111d741-bda4-4a50-a12b-d3337ff4441d)\*\*  
(Crítica)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a4b755b-7fa0-43aa-8862-c1d0c7d94c2c)\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=131b047a-ae93-4a99-83e5-71d5a79e96ea)\*\*  
(Baixa)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda)\*\*  
(KB974291)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)\*\*  
(KB974469)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=41bc4cdb-273a-4a6e-80d9-c8ce20e32da9)\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=db969ddc-708e-42b7-9956-6c27bf346bbb)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0d8a2a3e-d7d4-47fb-8364-16fce28e4d38)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=deb84cb8-2ba3-47e3-9185-2bbc5b0a7e18)\*  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)\*\*  
(KB974470)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94)\*  
(Moderada)
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7b70108b-7f59-4898-ab4e-76be990de878)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e81f30b7-ef05-4488-b62a-d330e17129cf)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3d16c5bf-ee5c-4220-9755-5cb92eac2aae)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)  
(KB953297)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda)  
(KB974291)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)  
(KB974469)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=a4f42085-1cb9-4b8d-a931-85be71fdf06d)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a221451a-cb4e-4a43-a225-4b1e86e87525)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8962f0b6-f346-4e88-9d83-4d15b699dd9d)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aac0e3e-9b49-4a4a-ab17-707ff03b4d9b)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)  
(KB953297)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)  
(KB974470)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
(Moderada)
</td>
<td style="border:1px solid black;">
O mesmo que acima
</td>
</tr>
<tr>
<th colspan="13">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits
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
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=89d1fb78-68cd-48dd-afc2-15a79ebe9fde)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=b64bcc14-38a7-45b9-8f85-acc573777506)  
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
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=ad6f06d5-27db-445d-a8b2-c42adc90afc0)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=35b85783-90df-4f67-a3cb-02351432133e)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
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
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=10d9f7ac-65f4-437c-91cc-171632c69b0e)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=809e29f3-ec68-4a2b-b04e-11759dd16001)  
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
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=70cd0270-77e9-492a-82d9-798364640c10)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=97010f2c-6c10-4fda-84fd-6c8749968db5)  
(Importante)
</td>
</tr>
<tr>
<th colspan="13">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://technet.microsoft.com/security/bulletin/ms09-059)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f50307d6-7869-4996-9ff7-23f87d08994b)\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=bcd2b944-6852-48f2-820b-cce7d195e391)\*\*  
(Baixa)
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
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=ce78c019-ec08-4ec6-abec-334f5ec5cb76)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=597ac3a7-e02d-49a5-9b8e-d097e867acea)\*  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
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
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9b6a28ae-b3f2-42b0-8209-e3950ec37abb)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=85e76e55-3766-4ffe-9a18-8655de935b7c)  
(Baixa)
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
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=6442a77a-3c0d-4beb-b2d2-2885376c2135)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=abc94857-37d8-4bb8-ad9e-46e687fca40e)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observações para Windows Server 2008 e Windows Server 2008 R2**

**\*Instalação de Núcleo de Servidor afetada.** Esta atualização se aplica, com a mesma classificação de gravidade, às edições com suporte do Windows Server 2008 e do Windows Server 2008 R2, conforme indicado, independentemente de terem sido instalados ou não com a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) e [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (em inglês) do MSDN. Observe que a opção de instalação do Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Instalação de Núcleo de Servidor não afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) e [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (em inglês) do MSDN. Observe que a opção de instalação do Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Observação para o boletim MS09-061**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

**Observações para o boletim MS09-062**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

**Observação para o boletim MS09-059**

<sup>[1]</sup>Esse sistema operacional só é afetado quando KB968389, Proteção Estendida para Autenticação (consulte o [Comunicado de Segurança da Microsoft 973811](http://technet.microsoft.com/security/advisory/973811)), foi instalado. Para obter mais informações, consulte a entrada em Perguntas frequentes relacionadas a esta atualização de segurança no [MS09-059](http://technet.microsoft.com/security/bulletin/ms09-059).

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Office Suites, sistemas e componentes
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-060**](http://technet.microsoft.com/security/bulletin/ms09-060)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=04878c2c-eb97-426f-be08-89036a6799db)  
(KB973702)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d)<sup>[2]</sup>
(KB974811)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=79e2b2e8-d5e8-4014-b489-720af2b5083d)  
(KB973705)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7)<sup>[3]</sup>
(KB972580)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Sistema Microsoft Office 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2007 Service Pack 1 e Microsoft Office Outlook 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d39234a3-c62c-44ba-a626-3179a183ca09)  
(KB972363)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Sistema Microsoft Office 2007 Service Pack 1 e Sistema Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Outros softwares do Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-060**](http://technet.microsoft.com/security/bulletin/ms09-060)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=920ee70b-c5c1-47b5-8f33-938ffe14eea4)  
(KB975365)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio Viewer
</td>
<td style="border:1px solid black;">
Microsoft Visio 2002 Viewer<sup>[1]</sup>
(Crítica)  
Microsoft Office Visio 2003 Viewer<sup>[1]</sup>
(Crítica)  
[Microsoft Office Visio Viewer 2007 Service Pack 1 e Microsoft Office Visio Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d20004c5-dd01-459e-8120-5f127e20c085)  
(KB973709)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio Viewer 2007 Service Pack 1 e Microsoft Office Visio Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d)<sup>[2]</sup>
(KB974811)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer, Microsoft Office Excel Viewer e Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer 2003 Service Pack 3 e Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7)<sup>[3]</sup>
(KB972580)  
(Importante)  
[Microsoft Office Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(Importante)  
[PowerPoint Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 1 e Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](http://www.microsoft.com/downloads/details.aspx?familyid=6f96de9a-62d8-428f-9567-51d55c129be6)  
(KB973636)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observações para o boletim MS09-060**

<sup>[1]</sup>A Microsoft recomenda que os usuários do Microsoft Visio Viewer 2002 e Microsoft Visio Viewer 2003 atualizem para o Microsoft Office Visio Viewer 2007 Service Pack 2.

**Observações para o boletim MS09-062**

<sup>[2]</sup>Essas atualizações são idênticas.

<sup>[3]</sup>Essas atualizações são idênticas.

<sup>[4]</sup>Essas atualizações são idênticas.

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
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
SQL Server 2000 Reporting Services Service Pack 2
</td>
<td style="border:1px solid black;">
Atualização de GDR  
Não Aplicável  
Atualização de QFE:  
[SQL Server 2000 Reporting Services Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=33554f96-5af7-4683-a537-9db293b67b8d)  
(KB970899)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
Atualização de GDR:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23)<sup>[1]</sup>
(KB970895)  
(Crítica)  
Atualização de QFE:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235)<sup>[1]</sup>
(KB970896)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Atualização de GDR:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23)<sup>[1]</sup>
(KB970895)  
(Crítica)  
Atualização de QFE:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235)<sup>[1]</sup>
(KB970896)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Atualização de GDR:  
[SQL Server 2005 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23)<sup>[1]</sup>
(KB970895)  
(Crítica)  
Atualização de QFE:  
[SQL Server 2005 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235)<sup>[1]</sup>
(KB970896)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 3
</td>
<td style="border:1px solid black;">
Atualização de GDR  
[SQL Server 2005 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce)<sup>[2]</sup>
(KB970892)  
(Crítica)  
Atualização de QFE:  
[SQL Server 2005 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f)<sup>[2]</sup>
(KB970894)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 3
</td>
<td style="border:1px solid black;">
Atualização de GDR:  
[SQL Server 2005 x64 Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce)<sup>[2]</sup>
(KB970892)  
(Crítica)  
Atualização de QFE:  
[SQL Server 2005 x64 Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f)<sup>[2]</sup>
(KB970894)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 para sistemas baseados no Itanium Service Pack 3
</td>
<td style="border:1px solid black;">
Atualização de GDR:  
[SQL Server 2005 para sistemas baseados no Itanium Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce)<sup>[2]</sup>
(KB970892)  
(Crítica)  
Atualização de QFE:  
[SQL Server 2005 para sistemas baseados no Itanium Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f)<sup>[2]</sup>
(KB970894)  
(Crítica)
</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS09-062**

<sup>[1]</sup>Clientes do SQL Server 2005 Service Pack 2 com dependência do Sharepoint do Reporting Services também são solicitados a instalar o [Suplemento Microsoft SQL Server 2005 Reporting Services para Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=%20f4d4d0ae-e5d4-4ed1-8d78-7137578161ce&displaylang=en) a partir do Centro de Download da Microsoft.

<sup>[2]</sup>Clientes do SQL Server 2005 Service Pack 3 com dependência do Sharepoint do Reporting Services também são solicitados a instalar o [Suplemento Microsoft SQL Server 2005 Reporting Services para Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=%20648766ac-2a35-4238-a3f4-c26d7077f2a9&displaylang=en) a partir do Centro de Download da Microsoft.

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Software e ferramentas para desenvolvedor da Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
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
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](http://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup> quando instalado no Mac  
(KB970363)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](http://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup> quando instalado em todas as versões de clientes do Microsoft Windows  
(KB970363)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](http://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup> quando instalado em todas as versões de servidores do Microsoft Windows\*\*  
(KB970363)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9e3b52d3-b211-4d62-891c-ae8f2e4ffc6c)  
(KB971022)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e186aeed-e9d7-4a02-84b3-bbed116ca060)  
(KB971023)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=4fa10c93-ce20-43df-a725-ef4c77353747)  
(KB972221)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b904dee8-8a26-43f8-8ca9-86ad12cfdb52)  
(KB972222)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 8.0 Service Pack 1 quando instalado no Microsoft Windows 2000 Service Pack 4  
(KB971104)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e5d0d515-4b36-4025-bc6f-1c5cdf09e1af)  
quando instalado no Microsoft Windows 2000 Service Pack 4  
(KB971104)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 2 quando instalado no Microsoft Windows 2000 Service Pack 4  
(KB971105)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2a930f56-59ac-49a6-830f-bfae7c540ec7)  
quando instalado no Microsoft Windows 2000 Service Pack 4  
(KB971105)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Report Viewer
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=0dfaf300-2b53-4678-a779-0d805ddfe538)  
(KB971117)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 Redistributable Package
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=42ed040f-cf94-4754-b0b3-c8016fbcbe22)  
(KB971118)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 Redistributable Package Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 Redistributable Package Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6aaa74bd-a46e-4478-b4e1-2063d18d2d42)  
(KB971119)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Platform SDK Redistributable: GDI+
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK Redistributable: GDI+](http://www.microsoft.com/downloads/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(KB975337)  
(Nenhuma classificação de gravidade<sup>[2]</sup>)
</td>
</tr>
</table>

<p></p>

 
**Observações para o boletim MS09-061**

<sup>[1]</sup>Este download atualiza o Microsoft Silverlight 2 para Microsoft Silverlight 3, que elimina a vulnerabilidade descrita no boletim.

**\*\*Instalação de Núcleo de Servidor não afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) e [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (em inglês) do MSDN. Observe que a opção de instalação do Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

**Observações para o boletim MS09-062**

<sup>[2]</sup>As classificações de gravidade não se aplicam a esta atualização porque a Microsoft não identificou nenhum vetor de ataque relacionado às vulnerabilidades abordadas neste boletim específico para esses softwares. No entanto, esta atualização de segurança está sendo oferecida a desenvolvedores que usam este software para que possam publicar sua própria versão atualizada de seus aplicativos.

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Software de segurança da Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Client Security 1.0](http://www.microsoft.com/downloads/details.aspx?familyid=c0ce624c-8df3-4223-8a7a-5cba4ac334a8)  
quando instalado no Microsoft Windows 2000 Service Pack 4  
(KB975962)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS09-062**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://go.microsoft.com/fwlink/?linkid=85102), no qual essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) e no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Frequentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

**Observação** A partir de 1º de agosto de 2009, a Microsoft descontinuará o suporte à Atualização do Office e à Ferramenta de Inventário da Atualização do Office. Para continuar obtendo as últimas atualizações para produtos Microsoft Office, use o [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Para obter mais informações, consulte [Sobre a Atualização do Microsoft Office: Perguntas frequentes](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Orientação para detecção e implantação**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o [Artigo 961747 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Windows 2000 e posterior, Office XP e superior, Exchange Server 2003, e SQL Server 2000 nos sistemas operacionais Windows 2000 e superior.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários. O próximo lançamento do SMS, System Center Configuration Manager 2007, já está disponível; consulte também [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Para obter mais informações sobre como os administradores podem usar o SMS 2003 para instalar atualizações de segurança, consulte [Gerenciamento de Patches de Segurança do SMS 2003.](http://go.microsoft.com/fwlink/?linkid=22939) Usuários do SMS 2.0 também podem usar o Security Update Inventory Tool (SUIT) para ajudar a implantar atualizações de segurança. Para obter informações sobre o SMS, visite [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) e no [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) (sites em inglês) para instalar essas atualizações.

**Avaliador de Compatibilidade com Atualizações e Application Compatibility Toolkit**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) incluídos no [Kit de ferramentas de compatibilidade de aplicativos](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações de alta prioridade que não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do MAPP (Microsoft Active Protections Program)](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

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

-   [Matthieu Suiche](http://www.msuiche.net/) do [Netherlands Forensics Institute](http://www.nederlandsforensischinstituut.nl/) por relatar um problema descrito no boletim MS09-050
-   Ivan Fratric de [Zero Day Initiative](http://www.zerodayinitiative.com/) e Jun Xie da [McAfee Avert Labs](http://www.avertlabs.com/) por relatarem um problema descrito no boletim MS09-051
-   Vinay Anantharaman, da [Adobe Systems, Inc.](http://www.adobe.com/), por relatar um problema descrito no boletim MS09-051
-   Yamata Li, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar um problema descrito no boletim MS09-052
-   SkyLined, da [Google Inc.](http://www.google.com/), por relatar um problema descrito no boletim MS09-054
-   Mark Dowd, da [IBM ISS X-Force](http://www.iss.net/), por relatar um problema descrito no boletim MS09-054
-   [TippingPoint](http://www.tippingpoint.com/) e [Zero Day Initiative](http://www.zerodayinitiative.com/) por relatarem um problema descrito no boletim MS09-054
-   Sam Thomas, da eshu.co.uk, que trabalha com a [TippingPoint](http://www.tippingpoint.com/) e a [Zero Day Initiative](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS09-054
-   Ian Wright e Jean-Luc Giraud da [Citrix](http://www.citrix.com/) por trabalharem conosco no problema descrito no boletim MS09-056
-   Dan Kaminsky da [IOActive](http://www.ioactive.com/) por relatar dois problemas descritos no boletim MS09-056
-   Yamata Li, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar um problema descrito no boletim MS09-057
-   Tavis Ormandy e Neel Mehta da [Google Inc.](http://www.google.com/) por relatarem dois problemas descritos no boletim MS09-058
-   [NSFocus Security Team](http://www.nsfocus.com/) por relatar um problema descrito no boletim MS09-058
-   David Dewey, da [IBM ISS X-Force](http://www.iss.net/), por relatar um problema descrito no boletim MS09-060
-   Ryan Smith, da [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar dois problemas descritos no boletim MS09-060
-   [Pavel Minaev](http://int19h.org/) por relatar um problema descrito no boletim MS09-061
-   Jeroen Frijters, da [Sumatra](http://www.sumatra.nl/), por relatar um problema descrito no boletim MS09-061
-   Yamata Li, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar um problema descrito no boletim MS09-062
-   Thomas Garnier, da [SkyRecon](http://www.skyrecon.com/), por relatar um problema descrito no boletim MS09-062
-   Wushi, da [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar um problema descrito no boletim MS09-062
-   Ivan Fratric, da [Zero Day Initiative](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS09-062
-   Tavis Ormandy, da [Google Inc.](http://www.google.com/), por relatar dois problemas descritos no boletim MS09-062
-   Carlo Di Dato (também conhecido como shinnai) por relatar um problema descrito no boletim MS09-062
-   Marsu Pilami, da [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar um problema descrito no boletim MS09-062
-   Carsten H. Eiram, da [Secunia](http://secunia.com/), por relatar um problema descrito no boletim MS09-062

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do [Suporte de Segurança](http://go.microsoft.com/fwlink/?linkid=21131) ou pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas. Para obter mais informações sobre as opções de suporte disponíveis, consulte [Ajuda e Suporte da Microsoft](http://support.microsoft.com/).
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (13 de outubro de 2009): Resumo de boletins publicado.
-   V1.1 (14 de outubro de 2009): Corrigido o link para download do Windows XP x64 Edition Service Pack 2 para MS09-055.
-   V1.2 (18 de outubro de 2009): A Sinopse do MS09-054 foi revisada a fim de fornecer orientações para usuários do Firefox.
-   V2.0 (28 de outubro de 2009): Microsoft Office Visio Viewer 2007, Microsoft Office Visio Viewer 2007 Service Pack 1 e Microsoft Office Visio Viewer 2007 Service Pack 2 foram adicionados como softwares afetados no boletim MS09-062, e observações foram adicionadas para o boletim MS09-062 para clientes do SQL Server 2005 com dependência do Sharepoint do Reporting Services.
-   V3.0 (2 de novembro de 2009): Revisado para anunciar a disponibilidade de um hotfix para o boletim MS09-054 para resolver os problemas de compatibilidade de aplicativos. Os clientes que já aplicaram esta atualização podem instalar o hotfix a partir do Artigo 976749 (em inglês) da Microsoft Knowledge Base.
-   V3.1 (4 de novembro de 2009): Foram removidas referências incorretas à versão de lançamento original do Microsoft Office Visio Viewer 2007 como software afetado nos boletins MS09-060 e MS09-062.
-   V4.0 (10 de novembro de 2009): O boletim foi revisado para comunicar o relançamento da atualização para o Gerenciador de Compactação de Áudio no Microsoft Windows 2000 Service Pack 4 em MS09-051, com o objetivo de corrigir um problema de detecção. Esta é apenas uma alteração de detecção; não houve nenhuma alteração aos binários. Os clientes que atualizaram seus sistemas com êxito não necessitam reinstalar esta atualização.
-   V4.1 (12 de janeiro de 2010): Foram removidos o Microsoft Expression Web, Microsoft Expression Web 2, Microsoft Office Groove 2007 e Microsoft Office Groove 2007 Service Pack 1 como softwares afetados no boletim MS09-062.
-   V4.2 (22 de junho de 2010): O .NET Framework 1.1 Service Pack 1 foi removido da lista de componentes afetados no Windows 7 e no Windows Server 2008 R2 para o MS09-061.

*Built at 2014-04-18T01:50:00Z-07:00*
