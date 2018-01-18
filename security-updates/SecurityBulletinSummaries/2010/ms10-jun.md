---
TOCTitle: 'MS10-JUN'
Title: Resumo do Boletim de Segurança da Microsoft de junho 2010
ms:assetid: 'ms10-jun'
ms:contentKeyID: 61233664
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms10-jun(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de junho 2010
=========================================================

Publicado: terça-feira, 8 de junho de 2010 | Atualizado: terça-feira, 13 de setembro de 2011

**Versão:** 2.0

Este resumo de boletins lista os boletins de segurança lançados em junho de 2010.

Com o lançamento dos boletins de junho de 2010, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 3 de junho de 2010. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte Notificação antecipada dos boletins de segurança da Microsoft.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as notificações de segurança técnica da Microsoft.

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 9 de junho de 2010, às 11 horas - Hora do Pacífico (EUA e Canadá). Registre-se agora para participar do Webcast do boletim de segurança de junho. Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte Webcasts e resumos dos boletins de segurança da Microsoft.

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações de alta prioridade que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras** **informações.**

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades na descompactação de mídia podem permitir a execução remota de código (979902)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft Windows. Essas vulnerabilidades podem permitir a execução remota de código se um usuário abrir um arquivo de mídia especialmente criado ou receber conteúdo de fluxo especialmente criado de um site ou de qualquer aplicativo que forneça conteúdo da Web. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário local. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159">MS10-034</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa de Kill Bits do ActiveX (980195)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular para softwares da Microsoft. Esta atualização de segurança foi classificada como Crítica para todas as edições com suporte do Microsoft Windows 2000, Windows XP, Windows Vista e Windows 7, e como Moderada para todas as edições com suporte do Windows Server 2003, Windows Server2008 e Windows Server 2008 R2.<br />
<br />
As vulnerabilidades poderão permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada que instancie um controle ActiveX específico usando o Internet Explorer. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. Esta atualização também inclui kill bits para quatro controles ActiveX de terceiros.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (982381)</strong><br />
<br />
Esta atualização de segurança elimina cinco vulnerabilidades relatadas em particular e uma divulgada publicamente no Internet Explorer. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades nos drivers do modo do kernel do Windows podem permitir a elevação de privilégio (979559)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades divulgadas publicamente e uma vulnerabilidade relatada em particular nos drivers do modo do kernel do Windows. As vulnerabilidades poderão permitir a elevação de privilégio se um usuário exibir conteúdo processado em uma fonte TrueType especialmente criada.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190554">MS10-036</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade na validação COM do Microsoft Office pode permitir a execução remota de código (983235)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular na validação COM do Microsoft Office. A vulnerabilidade poderá permitir a execução remota de código se um usuário abrir um arquivo Excel, Word, Visio, Publisher ou PowerPoint especialmente criado com uma versão afetada do Microsoft Office. A vulnerabilidade não pode ser explorada automaticamente por email. Para que um ataque seja bem sucedido, um usuário deve abrir um anexo enviado em uma mensagem de email.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508">MS10-037</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no driver CFF (Compact Font Format) OpenType pode permitir a elevação de privilégio (980218)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no driver CFF OpenType do Windows. A vulnerabilidade poderá permitir a elevação de privilégio se um usuário exibir conteúdo processado em uma fonte CFF especialmente criada. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade. Essa vulnerabilidade não pode ser explorada remotamente por usuários anônimos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Office Excel podem permitir a execução remota de código (2027452)</strong><br />
<br />
Esta atualização de segurança elimina quatorze vulnerabilidades relatadas em particular no Microsoft Office. As vulnerabilidades mais graves poderão permitir a execução remota de código se um usuário abrir um arquivo Excel especialmente criado. O invasor que explorar com êxito qualquer uma destas vulnerabilidades poderá obter os mesmos direitos que o usuário local. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft SharePoint podem permitir a elevação de privilégio (2028554)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e duas vulnerabilidades relatadas em particular no Microsoft SharePoint. A vulnerabilidade mais grave poderá permitir a elevação de privilégio se um invasor convencer um usuário de um site visado do SharePoint a clicar em um link especialmente criado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788">MS10-040</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade nos Serviços de Informações da</strong> <strong>Internet pode permitir a execução remota de código (982666)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular nos Serviços de Informações da Internet (IIS). A vulnerabilidade poderá permitir a execução remota de código se um usuário receber uma solicitação HTTP especialmente criada. O invasor que explorar com êxito essa vulnerabilidade poderá assumir o controle total de um sistema afetado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042">MS10-041</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft .NET Framework pode permitir falsificação (981343)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente no Microsoft .NET Framework. A vulnerabilidade pode permitir a falsificação de dados de conteúdo XML assinado, sem ser detectada. Em aplicativos personalizados, o impacto de segurança depende de como o conteúdo assinado é usado no aplicativo específico. Os cenários em que as mensagens XML assinadas são transmitidas através de um canal seguro (como SSL) não são afetados por esta vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Falsificação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>

<p></p>

  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas em ordem decrescente de nível de avaliação de exploração e depois de ID do CVE. Só são incluídas as vulnerabilidades com uma classificação de gravidade Crítica ou Importante nos boletins.
  
**Como devo usar a tabela?**  
  
Use esta tabela para conhecer a probabilidade de o código de exploração em funcionamento ser lançado em 30 dias contados do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Você deve revisar cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade a sua implantação. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o Microsoft Exploitability Index.
  
| ID do Boletim                                             | Título da vulnerabilidade                                                            | ID do CVE                                                                        | Avaliação do índice de exploração                                                                                     | Principais observações                                                                             |  
|-----------------------------------------------------------|--------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|  
| [MS10-032](http://go.microsoft.com/fwlink/?linkid=184917) | Vulnerabilidade na criação de janelas do Win32k                                      | [CVE-2010-0485](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0485) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905) | Vulnerabilidade de scripts entre sites (XSS) Help.aspx                               | [CVE-2010-0817](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0817) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | Esta vulnerabilidade foi relatada pela primeira vez no Comunicado de Segurança da Microsoft 983438 |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de estouro de pilha de objetos do Excel                              | [CVE-2010-0822](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0822) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de memória de registros do Excel                        | [CVE-2010-0824](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0824) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de memória de registros do Excel                        | [CVE-2010-1245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1245) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de memória RTD do Excel                                 | [CVE-2010-1246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1246) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de memória do Excel                                     | [CVE-2010-1247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1247) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de memória HFPicture do Excel                           | [CVE-2010-1248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1248) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de memória do Excel                                     | [CVE-2010-1249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1249) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de memória EDG do Excel                                 | [CVE-2010-1250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1250) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de objeto ADO do Excel                                               | [CVE-2010-1253](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1253) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de permissões Open XML do Office para Mac                            | [CVE-2010-1254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1254) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Vulnerabilidade de corrupção de memória não inicializada                             | [CVE-2010-1259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1259) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Vulnerabilidade de corrupção de memória                                              | [CVE-2010-1262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1262) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-036](http://go.microsoft.com/fwlink/?linkid=190554) | Vulnerabilidade de validação COM                                                     | [CVE-2010-1263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-033](http://go.microsoft.com/fwlink/?linkid=191065) | Vulnerabilidade de descompactação de mídia                                           | [CVE-2010-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1879) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                           |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Vulnerabilidade de divulgação de informações entre domínios                          | [CVE-2010-0255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0255) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | Esta vulnerabilidade foi relatada pela primeira vez no Comunicado de Segurança da Microsoft 980088 |  
| [MS10-032](http://go.microsoft.com/fwlink/?linkid=184917) | Vulnerabilidade de validação de dados incorreta do Win32k                            | [CVE-2010-0484](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0484) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | (Nenhum)                                                                                           |  
| [MS10-037](http://go.microsoft.com/fwlink/?linkid=190508) | Vulnerabilidade de corrupção de memória do driver CFF (Compact Font Format) OpenType | [CVE-2010-0819](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0819) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de memória na análise de registros do Excel             | [CVE-2010-0821](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0821) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de memória do Excel                                     | [CVE-2010-0823](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0823) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de corrupção de pilha de registros do Excel                          | [CVE-2010-1251](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1251) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | (Nenhum)                                                                                           |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Vulnerabilidade de variável de cadeia de caracteres do Excel                         | [CVE-2010-1252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1252) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | (Nenhum)                                                                                           |  
| [MS10-032](http://go.microsoft.com/fwlink/?linkid=184917) | Vulnerabilidade de análise de fonte TrueType do Win32k                               | [CVE-2010-1255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1255) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | (Nenhum)                                                                                           |  
| [MS10-040](http://go.microsoft.com/fwlink/?linkid=191788) | Vulnerabilidade de corrupção de memória de autenticação IIS                          | [CVE-2010-1256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1256) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | (Nenhum)                                                                                           |  
| [MS10-033](http://go.microsoft.com/fwlink/?linkid=191065) | Vulnerabilidade de descompactação de mídia MJPEG                                     | [CVE-2010-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1880) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente?     | (Nenhum)                                                                                           |  
| [MS10-041](http://go.microsoft.com/fwlink/?linkid=185042) | Vulnerabilidade de anulação de autenticação de truncamento HMAC na assinatura XML    | [CVE-2009-0217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0217) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração de funcionamento improvável | Isto é uma vulnerabilidade de falsificação                                                         |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Vulnerabilidade de divulgação de informações de toStaticHTML                         | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração de funcionamento improvável | Esta vulnerabilidade também afeta o boletim MS10-039                                               |  
| [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905) | Vulnerabilidade de divulgação de informações de toStaticHTML                         | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração de funcionamento improvável | Esta vulnerabilidade também afeta o boletim MS10-035                                               |  
| [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905) | Vulnerabilidade de negação de serviço de página de ajuda do SharePoint               | [CVE-2010-1264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1264) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração de funcionamento improvável | (Nenhum)                                                                                           |
  
Softwares afetados e locais de download  
---------------------------------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
**Como uso estas tabelas?**  
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, haverá também um hiperlink para a atualização de software disponível e a classificação de gravidade da atualização de software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
#### Componentes e sistema operacional Windows

 
<p></p>

<table style="border:1px solid black;">
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows 2000</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP (site em inglês)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 7</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 R2</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Identificador do Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917"><strong>MS10-032</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065"><strong>MS10-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159"><strong>MS10-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898"><strong>MS10-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508"><strong>MS10-037</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788"><strong>MS10-040</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042"><strong>MS10-041</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;">Nenhuma</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=60c8579b-1540-40d8-80a0-956edadd63ce">Microsoft Windows 2000 Service Pack 4</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a51c53bd-f9c1-4d53-8ed2-034fd57bc75a">Quartz.dll (DirectShow) (DirectX 9)</a>[1]<br />
(KB975562)<br />
(Crítica)<br />
<br />
Windows Media Format Runtime 9[2]<br />
(KB978695)<br />
(Crítica)<br />
<br />
Windows Media Encoder 9 x86<br />
(KB979332)<br />
(Importante)<br />
<br />
Asycfilt.dll (COM component)<br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d3955983-0079-476e-a488-99713097259c">Microsoft Windows 2000 Service Pack 4</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0a6c09e5-c655-41a0-a133-78d55267a527">Internet Explorer 5.01 Service Pack 4</a><br />
(Nenhuma classificação de gravidade)[1]<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=e2f27eeb-54be-40be-a00e-72867090b8e7">Internet Explorer 6 Service Pack 1</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5d645891-31e9-42c4-b12b-eb351473fd0c">Microsoft Windows 2000 Service Pack 4</a><br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
(KB979906)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2</a><br />
(KB979909)<br />
(Importante)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Identificador</strong> <strong>do</strong> <strong>Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917"><strong>MS10-032</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065"><strong>MS10-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159"><strong>MS10-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898"><strong>MS10-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508"><strong>MS10-037</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788"><strong>MS10-040</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042"><strong>MS10-041</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;">Nenhuma</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2 e Windows XP Service Pack 3</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=023a777a-3d83-4a4e-8029-da8b095b074b">Windows XP Service Pack 2 e Windows XP Service Pack 3</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e77d5af8-e8e0-425c-a809-4cf274e17cc5">Quartz.dll (DirectShow)</a><br />
(KB975562)<br />
(Crítica)<br />
<br />
Windows XP Service Pack 2 apenas:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=bf8b9b46-ba28-4f48-9dac-6a90b7d592d3">Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 e Windows Media Format Runtime 11</a><br />
(KB978695)<br />
(Crítica)<br />
<br />
Windows XP Service Pack 3 apenas:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=ebbccd82-c637-4c88-86ea-d39ae713c085">Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 e Windows Media Format Runtime 11</a><br />
(KB978695)<br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf">Windows Media Encoder 9 x86</a><br />
(KB979332)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=55c05cb8-aa6c-460b-9aa7-084842dab280">Asycfilt.dll (componente COM)</a><br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8c3f2e81-c0ea-494a-a47c-4f8982effb49">Windows XP Service Pack 2 e Windows XP Service Pack 3</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bfe87761-ed9e-4fec-a393-d7fddb919db4">Internet Explorer 6</a><br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=fc02fc7e-ee85-4377-b54c-012fa60a8c9c">Internet Explorer 7</a><br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=9cff9aba-7743-4c33-87c7-37d06ed60a21">Internet Explorer 8</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b42a17c5-997e-4504-ba5b-bfa62166b460">Windows XP Service Pack 2 e Windows XP Service Pack 3</a><br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Windows XP Media Center Edition 2005 somente:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394">Microsoft .NET Framework 1.0 Service Pack 3</a><br />
(KB979904)<br />
(Importante)<br />
<br />
Windows XP Media Center Edition 2005 e Windows XP Tablet PC Edition 2005 apenas:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394">Microsoft .NET Framework 1.0 Service Pack 3</a><br />
(KB979904)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
(KB979906)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />
(KB982865)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET 3.5 Service Pack 1</a><br />
(KB979909)<br />
(Importante)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3aac9d-7747-435f-9678-f621e314e070">Windows XP Professional x64 Edition Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7914fdae-9a7a-4a10-8ce7-c621eb903452">Quartz.dll (DirectShow)</a><br />
(KB975562)<br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=b56839e3-e7d3-48da-b90c-d403d8dbeed2">Windows Media Format Runtime 9.5</a><br />
(KB978695)<br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555">Windows Media Format Runtime 9.5 x64 Edition</a>[3]<br />
(KB978695)<br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=d2887448-9d3c-472f-a0bd-ab083a65eafc">Windows Media Format Runtime 11</a><br />
(KB978695)<br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9">Windows Media Encoder 9 x86</a><br />
(KB979332)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7">Windows Media Encoder 9 x64</a><br />
(KB979332)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c110d26e-9a1e-4e47-9ce2-4068f2733a2f">Asycfilt.dll (componente COM)</a><br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f3e462fb-df95-4b79-a8bc-5359c2967503">Windows XP Professional x64 Edition Service Pack 2</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7780af61-a206-49aa-a805-a49bdcbb5419">Internet Explorer 6</a><br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=6c7cda29-161e-49b4-976a-c718c0aa11a0">Internet Explorer 7</a><br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=37cd7533-ddad-4d0d-85c0-1491308e1ff8">Internet Explorer 8</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=dc835b94-3368-4c1c-8f29-40517c73540e">Windows XP Professional x64 Edition Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
(KB979906)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />
(KB982865)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a> (KB979909)<br />
(Importante)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Identificador do Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917"><strong>MS10-032</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065"><strong>MS10-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159"><strong>MS10-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898"><strong>MS10-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508"><strong>MS10-037</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788"><strong>MS10-040</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042"><strong>MS10-041</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Moderada</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Moderada</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=79a11dcd-5d88-4d83-beae-6580ef6fc2c0">Windows Server 2003 Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fc15c43b-d48f-4872-8f9d-ed973170db9a">Quartz.dll (DirectShow)</a><br />
(KB975562)<br />
(Crítica)<br />
<br />
Windows Media Format Runtime 9.5<br />
(KB978695)<br />
(Crítica)<br />
<br />
Windows Media Encoder 9 x86<br />
(KB979332)<br />
(Importante)<br />
<br />
Asycfilt.dll (componente COM)<br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3c0bd349-aa77-47de-ba1d-1fcc72dcad28">Windows Server 2003 Service Pack 2</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bfb9acdb-2d9c-4c22-963c-8b9ce247350f">Internet Explorer 6</a><br />
(Moderada)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=f0187b69-3ed9-494c-89f1-90a35e22078c">Internet Explorer 7</a><br />
(Moderada)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=ebab6101-fcf1-4842-b22d-893a20c1c10f">Internet Explorer 8</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ca49b5b5-db8e-4ebc-9a3c-b1ace09ac3c0">Windows Server 2003 Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0761c207-5465-4f42-b61f-bd02efcef27d">Internet Information Services 6.0</a>[1]<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f82e1b73-7f8b-4f4c-8187-4050a11db44c">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
(KB979907)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />
(KB982865)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a><br />
(KB979909)<br />
(Importante)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f42cc5d4-1bea-4a4a-8a08-b3eb92503588">Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d28ecdf7-9fd4-437e-9db7-c6b579248abe">Quartz.dll (DirectShow)</a><br />
(KB975562)<br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=41faf16f-c7a8-4ce0-b388-a65478576163">Windows Media Format Runtime 9.5</a><br />
(KB978695)<br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555">Windows Media Format Runtime 9.5 x64 Edition</a>[3]<br />
(KB978695)<br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9">Windows Media Encoder 9 x86</a><br />
(KB979332)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7">Windows Media Encoder 9 x64</a><br />
(KB979332)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=77b1d55c-b015-4863-aab0-6463b90d4bf7">Asycfilt.dll (componente COM)</a><br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4aa0ec4f-5502-4f2a-9732-975518c34444">Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=81644c43-22c0-4c61-b395-3264516516a6">Internet Explorer 6</a><br />
(Moderada)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=50b8ee2e-31f8-473d-83d1-822c89c28070">Internet Explorer 7</a><br />
(Moderada)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=87e13912-f861-4985-ab9d-260a5898dfd4">Internet Explorer 8</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b0794e7e-c925-4672-b7a5-4bb3f847f045">Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=023572ff-ce5d-4428-a96b-1245db6ff312">Internet Information Services 6.0</a>[1]<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
(KB979906)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />
(KB982865)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a><br />
(KB979909)<br />
(Importante)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 com SP2 para sistemas baseados no Itanium</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=50efb1cf-9d89-4522-929d-f87fd98d6fe8">Windows Server 2003 com SP2 para sistemas baseados em Itanium</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7f101f4c-dcc8-474c-a844-fe0c45d6697c">Quartz.dll (DirectShow)</a><br />
(KB975562)<br />
(Crítica)<br />
<br />
Asycfilt.dll (componente COM)<br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=55d9d7f0-f9d9-4833-b5cc-eb87a62da6a8">Windows Server 2003 com SP2 para sistemas baseados em Itanium</a><br />
(Moderado)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=abcdc3bb-4659-4b63-a9bd-e448f8bed90a">Internet Explorer 6</a><br />
(Moderada)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=123bf547-9005-451f-9eba-97a68037304e">Internet Explorer 7</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6e76ebea-bde1-4352-a283-dd71c2cc51a1">Windows Server 2003 com SP2 para sistemas baseados em Itanium</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f1f3e524-8ac6-4210-a3a8-4ffc58a606ea">Internet Information Services 6.0</a>[1]<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
(KB979906)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />
(KB982865)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a><br />
(KB979909)<br />
(Importante)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Identificador do Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917"><strong>MS10-032</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065"><strong>MS10-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159"><strong>MS10-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898"><strong>MS10-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508"><strong>MS10-037</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788"><strong>MS10-040</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042"><strong>MS10-041</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista Service Pack 1 e Windows Vista Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7cb64633-d2a0-4e38-be35-ec32ea655a04">Windows Vista Service Pack 1 e Windows Vista Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;">Windows Vista Service Pack 1 somente:<br />
Quartz.dll (DirectShow)<br />
(KB975562)<br />
(Crítica)<br />
<br />
Asycfilt.dll (componente COM)<br />
(KB979482)<br />
(Crítica)<br />
<br />
Windows Media Encoder 9 x86<br />
(KB979332)<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2ddaa4b3-1a98-4183-94af-ebdae4e7b76a">Windows Vista Service Pack 1 e Windows Vista Service Pack 2</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=661c9528-917d-4df6-a330-c89f39dc5ce4">Internet Explorer 7</a><br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=640f9216-3e99-46b6-aac8-cd051eedad3c">Internet Explorer 8</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=363b503a-2e1e-4284-a029-9695d2acfcb6">Windows Vista Service Pack 1 e Windows Vista Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=01382926-2313-4769-a0a5-262c4f9f18a1">Internet Information Services 7.0</a>[1]<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
(KB979906)<br />
(Importante)<br />
<br />
Windows Vista Service Pack 1 apenas:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5</a><br />
(KB979913)<br />
(Importante)<br />
<br />
Windows Vista Service Pack 1 apenas:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a><br />
(KB979911)<br />
(Importante)<br />
<br />
Windows Vista Service Pack 2 apenas:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a> (KB979910)<br />
(Importante)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bbfc4d80-67eb-4deb-9595-cb67942a0df2">Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 1 somente:<br />
Quartz.dll (DirectShow)<br />
(KB975562)<br />
(Crítica)<br />
<br />
Asycfilt.dll (COM component)<br />
(KB979482)<br />
(Crítica)<br />
<br />
Windows Media Encoder 9 x86<br />
(KB979332)<br />
(Importante)<br />
<br />
Windows Media Encoder 9 x64<br />
(KB979332)<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ddf55e74-dbaa-45f7-ac5b-ae3da24e0e33">Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d9f5feb0-fa1a-40c1-9971-9b8af6f0b4a5">Internet Explorer 7</a><br />
(Crítica)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=3076d1ea-7716-4b54-8ec4-660374f14dcb">Internet Explorer 8</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3f512b86-3a99-47f7-a90e-1ae9b291385c">Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7fb6f2b8-c7a6-4239-99f3-cf3aacf89b0f">Internet Information Services 7.0</a>[1]<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
(KB979906)<br />
(Importante)<br />
<br />
Windows Vista x64 Edition Service Pack 1 apenas:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5</a><br />
(KB979913)<br />
(Importante)<br />
<br />
Windows Vista x64 Edition Service Pack 1 apenas:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a><br />
(KB979911)<br />
(Importante)<br />
<br />
Windows Vista x64 Edition Service Pack 2 apenas:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a><br />
(KB979910)<br />
(Importante)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Identificador do Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917"><strong>MS10-032</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065"><strong>MS10-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159"><strong>MS10-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898"><strong>MS10-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508"><strong>MS10-037</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788"><strong>MS10-040</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042"><strong>MS10-041</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Moderada</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Moderada</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=22d550fe-ba35-4750-a9d6-624858b67c94">Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2</a>\*<br />
(Importante)</td>
<td style="border:1px solid black;">Somente Windows Server 2008 para sistemas de 32 bits:<br />
Quartz.dll (DirectShow)\*\*<br />
(KB975562)<br />
(Crítica)<br />
<br />
Asycfilt.dll (componente COM)\*<br />
(KB979482)<br />
(Crítica)<br />
<br />
Windows Media Encoder 9 x86\*\*<br />
(KB979332)<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a06b9f42-47ac-4ff2-ac32-e4958cdb611e">Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2</a>\*\*<br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bed14484-7fc5-455d-b996-3192467543cc">Internet Explorer 7</a><br />
(Moderada)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=24ed08c7-a474-4458-8269-3b9de5e22385">Internet Explorer 8</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e78ad607-d209-48c4-b0f3-ed4c70993174">Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2</a>\*<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=84a54246-5d9e-49e2-8170-af48b43f984d">Internet Information Services 7.0</a>\*[1]<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>\*\*<br />
(KB979906)<br />
(Importante)<br />
<br />
Somente Windows Server 2008 para sistemas de 32 bits:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5</a>\*\*<br />
(KB979913)<br />
(Importante)<br />
<br />
Somente Windows Server 2008 para sistemas de 32 bits:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a>\*\*<br />
(KB979911)<br />
(Importante)<br />
<br />
Somente Windows Server 2008 para sistemas de 32 bits Service Pack 2:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a>\*\*<br />
(KB979910)<br />
(Importante)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=09025626-4116-4a31-8700-215382898ee2">Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2</a>\*<br />
(Importante)</td>
<td style="border:1px solid black;">Somente Windows Server 2008 para sistemas baseados em x64:<br />
Quartz.dll (DirectShow)\*\*<br />
(KB975562)<br />
(Crítica)<br />
<br />
Asycfilt.dll (componente COM)\*<br />
(KB979482)<br />
(Crítica)<br />
<br />
Windows Media Encoder 9 x86\*\*<br />
(KB979332)<br />
(Importante)<br />
<br />
Windows Media Encoder 9 x64\*\*<br />
(KB979332)<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6d0a3f7c-2617-4bc6-a4c7-cda26c6471e1">Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2</a>\*\*<br />
(Moderado)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a24554e8-213b-4c24-b062-ec424d64128e">Internet Explorer 7</a><br />
(Moderada)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=cf84469b-ce6d-45e8-8336-7b4501c6cf91">Internet Explorer 8</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=85f6fc5d-efd1-4351-b4c0-b9b7080e6173">Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2</a>\*<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=38286e43-89a6-4895-8ff9-69452df38706">Internet Information Services 7.0</a>\*[1]<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>\*\*<br />
(KB979906)<br />
(Importante)<br />
<br />
Somente Windows Server 2008 para sistemas baseados em x64:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5</a>\*\*<br />
(KB979913)<br />
(Importante)<br />
<br />
Somente Windows Server 2008 para sistemas x64:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a>\*\*<br />
(KB979911)<br />
(Importante)<br />
<br />
Somente Windows Server 2008 para sistemas x64 Service Pack 2:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a>\*\*<br />
(KB979910)<br />
(Importante)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0035cfe2-d38d-41cd-b704-ec1feda307d8">Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;">Somente Windows Server 2008 para sistemas baseados no Itanium:<br />
Quartz.dll (DirectShow)<br />
(KB975562)<br />
(Crítica)<br />
<br />
Asycfilt.dll (componente COM)<br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=38347fa6-5946-4bb5-9fea-a5b2f4e7c1f2">Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=dee5c0c0-b844-490d-8daf-6e6ec8a39e35">Internet Explorer 7</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c6f1aae5-e8fd-4121-89b2-b97c571e8223">Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8ad19eba-9821-48b4-a942-4ee4f002f913">Internet Information Services 7.0</a>[1]<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
(KB979906)<br />
(Importante)<br />
<br />
Somente Windows Server 2008 para sistemas baseados em Itanium:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 e Microsoft .NET Framework 3.5</a><br />
(KB979913)<br />
(Importante)<br />
<br />
Somente Windows Server 2008 para sistemas baseados em Itanium:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a><br />
(KB979911)<br />
(Importante)<br />
<br />
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2 somente:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 e Microsoft .NET Framework 3.5 Service Pack 1</a><br />
(KB979910)<br />
(Importante)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Identificador do Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917"><strong>MS10-032</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065"><strong>MS10-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159"><strong>MS10-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898"><strong>MS10-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508"><strong>MS10-037</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788"><strong>MS10-040</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042"><strong>MS10-041</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 7 para sistemas de 32 bits</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3e0ff389-4612-4c92-bbff-bb45b5bdfc6a">Windows 7 para sistemas de 32 bits</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=63567e99-087d-4804-953a-f23bdeba7772">Asycfilt.dll (componente COM)</a><br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5bce87fe-dcbb-4638-b248-3f0755537b00">Windows 7 para sistemas de 32 bits</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5c835885-9375-4882-a92f-4d4cfcacc005">Internet Explorer 8</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=969af8d6-f6da-4dd1-a7d7-2de54a5a8978">Windows 7 para sistemas de 32 bits</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=588167cb-f62a-4fb8-8a18-ac15dc322495">Internet Information Services 7.5</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a><br />
(KB979916)<br />
(Importante)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 7 para sistemas baseados em x64</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2b1e4aff-605a-4e94-88f9-135ce35f0646">Windows 7 para sistemas x64</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6c261dbf-14c6-4071-8523-e8ba8059fa54">Asycfilt.dll (componente COM)</a><br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ee68ecd0-5b8a-4c1e-bdee-bd8616558d43">Windows 7 para sistemas x64</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5cfc5776-0c6b-4092-bc98-94df077c60d8">Internet Explorer 8</a><br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b069e5b2-aa2d-452e-b687-8734b5ba0051">Windows 7 para sistemas x64</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1c45d0c8-1629-470b-8167-c6bf66054595">Internet Information Services 7.5</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a><br />
(KB979916)<br />
(Importante)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Identificador do Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917"><strong>MS10-032</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065"><strong>MS10-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159"><strong>MS10-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898"><strong>MS10-035</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508"><strong>MS10-037</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788"><strong>MS10-040</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042"><strong>MS10-041</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx"><strong>Crítica</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Moderada</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Moderada</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 R2 para sistemas baseados em x64</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4272277f-b2dd-4406-8bbd-bc461c9923b8">Windows Server 2008 R2 para sistemas baseados em x64</a>\*<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1331f2bc-7479-4be7-a413-52afb488a330">Asycfilt.dll (componente COM)\*</a><br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=901f7c89-02af-4f87-8592-dad318997d77">Windows Server 2008 R2 para sistemas baseados em x64</a>\*\*<br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7c4ff5ae-eadd-431e-b982-d5f179efb8c0">Internet Explorer 8</a>\*\*<br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=45242c7c-3752-44bf-a766-024ad7d28f53">Windows Server 2008 R2 para sistemas baseados em x64</a>\*<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5d9b7705-6280-4d2e-94fa-3160b3ce5cfa">Internet Information Services 7.5</a>\*<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a>\*<br />
(KB979916)<br />
(Importante)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2008 R2 para sistemas baseados no Itanium</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7d636f82-e828-468c-ac36-808ff9d37c7f">Windows Server 2008 R2 para sistemas baseados em Itanium</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7a1ee54f-3f73-4557-9071-5af236e70937">Asycfilt.dll (componente COM)</a><br />
(KB979482)<br />
(Crítica)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4958b221-2776-43d7-9e1c-1e1cb318a694">Windows Server 2008 R2 para sistemas baseados em Itanium</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=52c04d85-911f-47be-852e-c9bb4934744d">Internet Explorer 8</a><br />
(Moderada)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0a271fb5-da5b-4a17-9593-e56b9a843b8f">Windows Server 2008 R2 para sistemas baseados em Itanium</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=869e900a-0063-4d8b-9b7c-7d12f6be12cd">Internet Information Services 7.5</a><br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a><br />
(KB979916)<br />
(Importante)</td>
</tr>
</tbody>
</table>

<p></p>

 

**Observações para Windows Server 2008 e Windows Server 2008 R2**

**\*Instalação do núcleo do servidor afetada.** Esta atualização se aplica, com a mesma classificação de gravidade, às edições com suporte do Windows Server 2008 e do Windows Server 2008 R2, conforme indicado, independentemente de terem sido instalados ou não com a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos Server Core e [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (em inglês) do MSDN. Observe que a opção de instalação do Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**\*\*Instalação de Núcleo de Servidor não afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos Server Core e [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (em inglês) do MSDN. Observe que a opção de instalação do Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**Observação para o boletim MS10-033**

<sup>[1]</sup>A atualização para Quartz.dll (Direct Show) (DirectX 9) também se aplica a DirectX 9.0a, DirectX 9.0b e DirectX 9.0c.

<sup>[2]</sup>Este pacote de atualização se aplica ao Tempo de Execução do Windows Media Format 9 SDK no Microsoft Windows 2000 com a atualização para Media Players habilitados para DRM (KB891122). Para obter mais informações, consulte o Artigo 974316 (em inglês) da Microsoft Knowledge Base.

<sup>[3]</sup>Se você tiver instalado o Windows Media Format Runtime 9.5 x64 Edition, deverá aplicar as atualizações de segurança do Windows Media Format Runtime 9.5 e Windows Media Format Runtime 9.5 x64 Edition para ficar totalmente protegido contra a vulnerabilidade descrita no boletim MS10-033.

**Observação para o boletim MS10-035**

<sup>[1]</sup>Classificações de gravidade não se aplicam a esta atualização porque as vulnerabilidades abordadas neste boletim não afetam este software. No entanto, esta atualização está sendo oferecida para corrigir um problema de regressão originado no boletim MS09-054. Consulte o boletim 035 MS10 para obter detalhes.

**Observação para o boletim MS10-040**

<sup>[1]</sup>Este sistema operacional só é afetado quando a Proteção Estendida para Autenticação está instalada. Consulte o [Artigo 973917 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/973917)

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office Suites, sistemas e componentes</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office para Mac</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Outros softwares do Office</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Identificador</strong> <strong>do</strong> <strong>Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190554"><strong>MS10-036</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053"><strong>MS10-038</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905"><strong>MS10-039</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office XP Service Pack 3</td>
<td style="border:1px solid black;">Microsoft Office XP Service Pack 3[1]<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fec14a92-79a1-4281-8ee2-659b2dfd283f">Microsoft Office Excel 2002 Service Pack 3</a><br />
(KB982299)<br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=80fdd134-2a86-4115-aea1-841f19af92e3">Microsoft Office 2003 Service Pack 3</a><br />
(KB982311)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1">Microsoft Office Excel 2003 Service Pack 3</a>[2]<br />
(KB982133)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=6b6204c1-559f-45a5-8f6c-a1e216192efc">Microsoft Office PowerPoint 2003 Service Pack 3</a>[2]<br />
(KB982157)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=87bac893-81ec-4ede-aca1-a9aa48b92cd4">Microsoft Office Publisher 2003 Service Pack 3</a>[2]<br />
(KB982122)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=1595ada3-bb4f-40f6-8137-23eba918bc8a">Microsoft Office Visio 2003 Service Pack 3</a>[2]<br />
(KB982126)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=d2c40eb5-1149-4466-840c-84f406f64245">Microsoft Office Word 2003 Service Pack 3</a>[2]<br />
(KB982134)<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1">Microsoft Office Excel 2003 Service Pack 3</a><br />
(KB982133)<br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Sistema Microsoft Office 2007 Service Pack 1 e Sistema Microsoft Office 2007 Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6deb4fb0-cbfc-40df-8f62-35fa1db0e167">2007 Microsoft Office System Service Pack 1 e 2007 Microsoft Office System Service Pack 2</a><br />
(KB982312)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec">Microsoft Office Excel 2007 Service Pack 1 e Microsoft Office Excel 2007 Service Pack 2</a>[3]<br />
(KB982308)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=decb834d-3958-45cc-a5ae-4283adb2462a">Microsoft Office PowerPoint 2007 Service Pack 1 e Microsoft Office PowerPoint 2007 Service Pack 2</a>[3]<br />
(KB982158)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=6a74b986-1e99-4aa1-828f-757a36896f65">Microsoft Office Publisher 2007 Service Pack 1 e Microsoft Office Publisher 2007 Service Pack 2</a>[3]<br />
(KB982124)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=d5df052e-1f38-4308-bcca-296cff22729b">Microsoft Office Visio 2007 Service Pack 1 e Microsoft Office Visio 2007 Service Pack 2</a>[3]<br />
(KB982127)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=7e9708f0-8cd6-4f0b-8585-bccc54fa2755">Microsoft Office Word 2007 Service Pack 1 e Microsoft Office Word 2007 Service Pack 2</a>[3]<br />
(KB982135)<br />
(Importante)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec">Microsoft Office Excel 2007 Service Pack 1 e Microsoft Office Excel 2007 Service Pack 2</a>[1]<br />
(KB982308)<br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Identificador do Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190554"><strong>MS10-036</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053"><strong>MS10-038</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905"><strong>MS10-039</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;">Nenhuma</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;">Nenhuma</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2004 para Mac</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=16c71ab8-9284-407a-856a-93c67995f125">Microsoft Office 2004 para Mac</a><br />
(KB2028866)<br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2008 para Mac</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d46255bd-6470-4106-9fe2-ea67acd3f1bd">Microsoft Office 2008 para Mac</a><br />
(KB2028864)<br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Open XML File Format Converter para Mac</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b6ca7b05-cf97-43a2-95eb-7b5caf7c1528">Open XML File Format Converter para Mac</a><br />
(KB2078051)<br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Identificador do Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190554"><strong>MS10-036</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053"><strong>MS10-038</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905"><strong>MS10-039</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;">Nenhuma</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Excel Viewer Service Pack 1 e Microsoft Office Excel Viewer Service Pack 2</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=033b3bf3-7826-4064-b001-11e4dce2d91a">Microsoft Office Excel Viewer Service Pack 1 e Microsoft Office Excel Viewer Service Pack 2</a><br />
(KB982333)<br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 1 e Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 2</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7f89a734-cda4-4abb-9a10-f6dfe560e8d0">Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 1 e Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 2</a><br />
(KB982331)<br />
(Importante)</td>
<td style="border:1px solid black;">Não Aplicável</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office InfoPath 2003 Service Pack 3</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4f79d376-0ea2-4218-9200-3c34c83ba336">Microsoft Office InfoPath 2003 Service Pack 3</a><br />
(KB980923)<br />
(Importante)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office InfoPath 2007 Service Pack 1 e Microsoft Office InfoPath 2007 Service Pack 2</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bfa8765a-7970-4feb-996c-7c27d71c97c6">Microsoft Office InfoPath 2007 Service Pack 1 e Microsoft Office InfoPath 2007 Service Pack 2</a><br />
(KB979441)<br />
(Importante)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 Service Pack 1 e Microsoft Office SharePoint Server 2007 Service Pack 2</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df">Microsoft Office SharePoint Server 2007 Service Pack 1 (edições de 32 bits)</a>[1]<br />
(KB979445)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df">Microsoft Office SharePoint Server 2007 Service Pack 2 (edições de 32 bits)</a>[1]<br />
(KB979445)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90">Microsoft Office SharePoint Server 2007 Service Pack 1 (edições de 64 bits)</a>[1]<br />
(KB979445)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90">Microsoft Office SharePoint Server 2007 Service Pack 2 (edições de 64 bits)</a>[1]<br />
(KB979445)<br />
(Importante)</td>
</tr>
</tbody>
</table>

<p></p>

 

**Observações para o boletim MS10-036**

<sup>[1]</sup>Nenhuma atualização disponível. Consulte o boletim para obter detalhes.

<sup>[2]</sup>Além desta atualização, os clientes também precisam instalar a atualização para o Microsoft Office 2003 Service Pack 3 (KB982311) para ficarem protegidos contra a vulnerabilidade descrita neste boletim.

<sup>[3]</sup>Além desta atualização, os clientes também precisam instalar a atualização para o Sistema Microsoft Office 2007 Service Pack 1 e o Sistema Microsoft Office 2007 Service Pack 2 (KB982312) para ficarem protegidos contra a vulnerabilidade descrita neste boletim.

**Observação para o boletim MS10-038**

<sup>[1]</sup>Além desta atualização, os clientes também precisam instalar a atualização de segurança para o Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 1 e o Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 2 (KB982308) para ficarem protegidos contra as vulnerabilidades descritas neste boletim.

**Observações para o boletim MS10-039**

<sup>[1]</sup>Para edições com suporte do Microsoft Office SharePoint Server 2007, além do pacote de atualização de segurança KB979445, os clientes também precisam instalar a atualização de segurança para Microsoft Windows SharePoint Services 3.0 (KB983444) para ficarem protegidos contra as vulnerabilidades descritas neste boletim.

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Windows SharePoint Services</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Identificador do Boletim</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905"><strong>MS10-039</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Avaliação de gravidade agregada</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Importante</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Windows SharePoint Services 3.0 Service Pack 1 e Microsoft Windows SharePoint Services 3.0 Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3841ceda-d0af-4e5e-8a1a-7dd954850783">Microsoft Windows SharePoint Services 3.0 Service Pack 1 e Microsoft Windows SharePoint Services 3.0 Service Pack 2 (versões de 32 bits)</a><br />
(KB983444)<br />
(Importante)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=94bc76d4-78e4-4bda-8922-36c3a9d3854f">Microsoft Windows SharePoint Services 3.0 Service Pack 1 e Microsoft Windows SharePoint Services 3.0 Service Pack 2 (versões de 64 bits)</a><br />
(KB983444)<br />
(Importante)</td>
</tr>
</tbody>
</table>

<p></p>

 

**Observação para o boletim MS10-039**

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o Centro de Gerenciamento de Atualização do Technet. O site TechNet Security Center fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar Segurança em Casa, no qual essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no Microsoft Update e no Windows Update. As atualizações de segurança também estão disponíveis no Centro de Download da Microsoft. Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Por fim, as atualizações de segurança podem ser baixadas do Microsoft Update Catalog. O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as Perguntas Freqüentes sobre Microsoft Update Catalog.

**Observação** A partir de 1º de agosto de 2009, a Microsoft descontinuará o suporte à Atualização do Office e à Ferramenta de Inventário da Atualização do Office. Para continuar obtendo as últimas atualizações para produtos Microsoft Office, use o Microsoft Update. Para obter mais informações, consulte Sobre a Atualização do Microsoft Office: Perguntas frequentes.

**Orientação para detecção e implantação**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o Artigo 961747 (em inglês) da Microsoft Knowledge Base.

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite Microsoft Baseline Security Analyzer.

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite Windows Server Update Services.

**Systems Management Server**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários. O próximo lançamento do SMS, System Center Configuration Manager 2007, já está disponível; consulte também System Center Configuration Manager 2007. Para obter mais informações sobre como os administradores podem usar o SMS 2003 para instalar atualizações de segurança, consulte Gerenciamento de Patches de Segurança do SMS 2003. Usuários do SMS 2.0 também podem usar o Security Update Inventory Tool (SUIT) para ajudar a implantar atualizações de segurança. Para obter informações sobre o SMS, visite Microsoft Systems Management Server.

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte Implementando atualizações de software usando o Recurso Distribuição de Software do SMS. Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no SMS 2.0 Administration Feature Pack) (sites em inglês) para instalar essas atualizações.

**Avaliador** **de Compatibilidade com Atualizações e Application Compatibility Toolkit**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do Avaliador de compatibilidade com atualizações incluídos no Kit de ferramentas de compatibilidade de aplicativos para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações de alta prioridade que não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199)
-   : Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)
-   . Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em Parceiros do MAPP (Microsoft Active Protections Program).

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

A Microsoft agradece à pessoa citada abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   Sebastien Renaud, da VUPEN Vulnerability Research Team, por relatar um problema descrito no boletim MS10-032
-   [Secunia Research](http://secunia.com/)
-   , por trabalhar conosco em um problema descrito no boletim MS10-032
-   Yamata Li, da Palo Alto Networks, por relatar dois problemas descritos no boletim MS10-033
-   Shaun Colley, da NGS Software, por relatar um problema descrito no boletim MS10-034
-   Chris Ries, dos serviços de computação da Carnegie Mellon University, por relatar um problema descrito no boletim MS10-034
-   Chris Weber, da Casaba Security, por relatar um problema descrito nos boletins MS10-035 e MS10-039
-   Takeshi Terada, da Mitsui Bussan Secure Directions, Inc., por relatar um problema descrito no boletim MS10-035
-   Michal Zalewski, da Google Inc., por relatar um problema descrito no boletim MS10-035
-   Chris Rohlf, da Matasano Security, por relatar dois problemas descritos no boletim MS10-035
-   Peter Vreugdenhil, que trabalha com a Zero Day Initiative da [TippingPoint](http://www.tippingpoint.com/), por relatar um problema descrito no boletim MS10-035
-   David Dewey, da IBM ISS X-Force, e Ryan Smith, da Accuvant, anteriormente da VeriSign iDefense Labs, por trabalhar conosco nas alterações de defesa profunda incluídas no boletim MS10-036
-   Chris Carton, da Laserforce International, que trabalha com a Secunia, por relatar um problema descrito no boletim MS10-037
-   Um pesquisador anônimo, que trabalha com a Zero Day Initiative da [TippingPoint](http://www.tippingpoint.com/), por relatar um problema descrito no boletim MS10-038
-   Nicolas Joly, da VUPEN Vulnerability Research Team, por relatar oito problemas descritos no boletim MS10-038
-   Bing Liu, da Fortinet's FortiGuard Labs, por relatar um problema descrito no boletim MS10-038
-   Carsten Eiram, da Secunia, por relatar dois problemas descritos no boletim MS10-038
-   Um pesquisador anônimo, que trabalha com a Zero Day Initiative da [TippingPoint](http://www.tippingpoint.com/), por relatar um problema descrito no boletim MS10-038
-   Rick Glaspie, das Gilbert Public Schools, em Gilbert, AZ, por relatar um problema descrito no boletim MS10-038
-   Rik Jones, do Dallas County Community College District, por relatar um problema descrito no boletim MS10-039
-   Arian Evans, da WhiteHat Security, por relatar o problema de anulação da validação de solicitação ASP.NET eliminado no boletim MS10-041 por meio de uma alteração de defesa profunda

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site Ciclo de Vida do Suporte Microsoft.
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do Suporte de Segurança ou pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas. Para obter mais informações sobre as opções de suporte disponíveis, consulte Ajuda e Suporte da Microsoft.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de Ajuda e Suporte Internacional.

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (8 de junho de 2010): Resumo de boletins publicado.
-   V1.1 (9 de junho de 2010): Foram revisadas as observações para o boletim MS10-033 na seção **Softwares afetados e locais de download**.
-   V2.0 (13 de setembro de 2011): Boletim MS10-035 relançado para oferecer outras atualizações do Internet Explorer no Microsoft Windows 2000 e no Windows XP para eliminar um problema de detecção. Não houve nenhuma alteração para os arquivos de atualização de segurança. Os clientes que já atualizaram seus sistemas com êxito não precisam fazer mais nada.

*Built at 2014-04-18T01:50:00Z-07:00*
