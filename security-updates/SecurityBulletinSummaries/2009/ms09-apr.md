---
TOCTitle: 'MS09-APR'
Title: Resumo do Boletim de Segurança da Microsoft de abril 2009
ms:assetid: 'ms09-apr'
ms:contentKeyID: 61233646
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms09-apr(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de abril 2009
=========================================================

Publicado: terça-feira, 14 de abril de 2009 | Atualizado: quinta-feira, 16 de abril de 2009

**Versão:** 1.1

Este resumo de boletins lista os boletins de segurança lançados em abril de 2009.

Com o lançamento dos boletins de abril de 2009, este resumo de boletins substitui a notificação antecipada de boletim lançada originalmente em 9 de abril de 2009. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada de boletins de segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 15 de abril de 2009, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de abril](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395126). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações de alta prioridade que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

Sinopses
--------

 
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Software afetado e locais de download**.

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-010">MS09-010</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades nos conversores de texto do WordPad e do Office podem permitir a execução remota de código (960477)</strong><br />
<br />
Esta atualização de segurança resolve duas vulnerabilidades divulgadas publicamente e duas reportadas em particular nos conversores de texto do Microsoft WordPad e do Microsoft Office. Essas vulnerabilidades podem permitir a execução remota de código se um arquivo especialmente criado for aberto no WordPad ou no Microsoft Office Word. Não abra arquivos do Microsoft Office, RTF, Write ou WordPerfect de fontes não confiáveis usando versões afetadas do WordPad ou do Microsoft Office Word.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-013">MS09-013</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Windows HTTP Services podem permitir a execução remota de código (960803)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade divulgada publicamente e duas reportadas em particular no Microsoft Windows HTTP Services (WinHTTP). A vulnerabilidade mais grave pode permitir a execução remota de código. O invasor que explorar com êxito essa vulnerabilidade poderá assumir o controle total de um sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-014">MS09-011</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft DirectShow pode permitir a execução remota de código (961373)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft DirectX. Essa vulnerabilidade pode permitir a execução remota de código se o usuário abrir um arquivo MJPEG especialmente criado. O invasor que explorar com êxito essa vulnerabilidade poderá assumir o controle total de um sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-014">MS09-014</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para Internet Explorer (963027)</strong><br />
<br />
Esta atualização de segurança crítica resolve quatro vulnerabilidades no Internet Explorer reportadas em particular e duas divulgadas publicamente. As vulnerabilidades podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer ou se um usuário se conectar ao servidor de um invasor por meio do protocolo HTTP. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-009">MS09-009</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Office Excel podem permitir a execução remota de código (968557)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular e uma vulnerabilidade divulgada publicamente no Microsoft Office Excel. Essas vulnerabilidades podem permitir a execução remota de código quando um usuário abre um arquivo do Excel especialmente criado. O invasor que explorar com êxito as vulnerabilidades poderá assumir o controle total de um sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-012">MS09-012</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Windows podem permitir elevação de privilégio (959454)</strong><br />
<br />
Esta atualização de segurança elimina quatro vulnerabilidades divulgadas publicamente no Microsoft Windows. As vulnerabilidades podem permitir elevação de privilégio se um invasor puder se conectar ao sistema e executar um aplicativo especialmente criado. O invasor precisa ser capaz de executar código na máquina local para explorar esta vulnerabilidade. O invasor que explorar com êxito qualquer uma dessas vulnerabilidades poderá ter o controle total do sistema afetado.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-016">MS09-016</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft ISA Server e no Forefront Threat Management Gateway (Medium Business Edition) podem causar negação de serviço (961759)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular e uma vulnerabilidade divulgada publicamente no Microsoft ISA Server and Acceleration (ISA) Server e Microsoft Forefront Threat Management Gateway (TMG), Medium Business Edition (MBE). Estas vulnerabilidades podem permitir a negação de serviço se um invasor enviar pacotes de rede especialmente criados ao sistema afetado, ou a divulgação não autorizada de informações se um usuário clicar em uma URL mal-intencionada ou visitar um site que contenha conteúdo controlado pelo invasor.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Importante</a><br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Forefront Edge Security</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-015">MS09-015</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade de ameaças combinadas no SearchPath pode permitir a elevação de privilégio (959426)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente na função Windows SearchPath que pode permitir a elevação de privilégio se um usuário baixar um arquivo especialmente criado em um local específico e abrir um aplicativo que pode carregar o arquivo sob determinadas circunstâncias.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderada</a><br />
Elevação de privilégio</td>
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
  
| ID do Boletim                                                       | Título do Boletim                                                                                                                                 | ID do CVE                                                                            | Avaliação do índice de exploração                                                                                     | Principais observações                                                                                                                                                                                                                                                                                    |  
|---------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-009](http://technet.microsoft.com/security/bulletin/ms09-009) | Vulnerabilidades no Microsoft Office Excel podem permitir a execução remota de código (968557)                                                    | [CVE-2009-0100](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0100)     | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                  |  
| [MS09-009](http://technet.microsoft.com/security/bulletin/ms09-009) | Vulnerabilidades no Microsoft Office Excel podem permitir a execução remota de código (968557)                                                    | [CVE-2009-0238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0238)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | **No momento, esta vulnerabilidade está sendo explorada no ecossistema da Internet.**                                                                                                                                                                                                                     |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | Vulnerabilidades nos conversores de texto do WordPad e do Office podem permitir a execução remota de código (960477)                              | [CVE-2008-4841](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4841)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | **No momento, esta vulnerabilidade está sendo explorada no ecossistema da Internet.**                                                                                                                                                                                                                     |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | Vulnerabilidades nos conversores de texto do WordPad e do Office podem permitir a execução remota de código (960477)                              | [CVE-2009-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0087)     | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | Esta é uma vulnerabilidade complexa devido a vários caminhos de código. A maioria dos códigos de exploração apresenta resultados inconsistentes. Os fatores atenuantes padrão protegem contra este vetor.                                                                                                 |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | Vulnerabilidades nos conversores de texto do WordPad e do Office podem permitir a execução remota de código (960477)                              | [CVE-2009-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0088)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | Esta vulnerabilidade pode ser explorada, mas afeta somente as versões mais antigas e um formato de arquivo incomum mais antigo. As versões mais novas, como o 2007 Microsoft Office System e o Microsoft Office 2003 Service Pack 3, não são afetadas.                                                    |  
| [MS09-010](http://technet.microsoft.com/security/bulletin/ms09-010) | Vulnerabilidades nos conversores de texto do WordPad e do Office podem permitir a execução remota de código (960477)                              | [CVE-2009- 0235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0235)    | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | Esta vulnerabilidade de corrupção de memória é facilmente explorável.                                                                                                                                                                                                                                     |  
| [MS09-011](http://technet.microsoft.com/security/bulletin/ms09-014) | Vulnerabilidade no Microsoft DirectShow pode permitir a execução remota de código (961373)                                                        | [CVE-2009-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0084)     | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                  |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Vulnerabilidades no Windows podem permitir elevação de privilégio (959454)                                                                        | [CVE-2008-1436](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-1436)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | **No momento, esta vulnerabilidade está sendo explorada no ecossistema da Internet.**                                                                                                                                                                                                                     |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Vulnerabilidades no Windows podem permitir elevação de privilégio (959454)                                                                        | [CVE-2009-0078](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0078)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | **No momento, esta vulnerabilidade está sendo explorada no ecossistema da Internet.**                                                                                                                                                                                                                     |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Vulnerabilidades no Windows podem permitir elevação de privilégio (959454)                                                                        | [CVE-2009-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0079)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | **No momento, esta vulnerabilidade está sendo explorada no ecossistema da Internet.**                                                                                                                                                                                                                     |  
| [MS09-012](http://technet.microsoft.com/security/bulletin/ms09-012) | Vulnerabilidades no Windows podem permitir elevação de privilégio (959454)                                                                        | [CVE-2009-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0080)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | **No momento, esta vulnerabilidade está sendo explorada no ecossistema da Internet.**                                                                                                                                                                                                                     |  
| [MS09-013](http://technet.microsoft.com/security/bulletin/ms09-013) | Vulnerabilidades no Windows HTTP Services podem permitir a execução remota de código (960803)                                                     | [CVE-2009-0086](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0086)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | Esta é uma vulnerabilidade de memória facilmente controlável com vários vetores de ataque para exploração devido a uso generalizado desta tecnologia.                                                                                                                                                     |  
| [MS09-013](http://technet.microsoft.com/security/bulletin/ms09-013) | Vulnerabilidades no Windows HTTP Services podem permitir a execução remota de código (960803)                                                     | [CVE-2009-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0089)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                  |  
| [MS09-013](http://technet.microsoft.com/security/bulletin/ms09-013) | Vulnerabilidades no Windows HTTP Services podem permitir a execução remota de código (960803)                                                     | [CVE-2009-0550](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)\*\* | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | O código de exploração foi divulgado publicamente.                                                                                                                                                                                                                                                        |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Atualização de segurança cumulativa para Internet Explorer (963027)                                                                               | [CVE-2008-2540](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Os detalhes do ataque foram divulgados, mas não existe nenhum vetor de ataque conhecido para este problema. A exploração bem-sucedida desta vulnerabilidade requer a execução de uma série de etapas complexas pelo invasor e pelo usuário, o que inclui salvar arquivos específicos na área de trabalho. |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Atualização de segurança cumulativa para Internet Explorer (963027)                                                                               | [CVE-2009-0550](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)\*\* | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | O código de exploração foi divulgado publicamente.                                                                                                                                                                                                                                                        |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Atualização de segurança cumulativa para Internet Explorer (963027)                                                                               | [CVE-2009-0551](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0551)     | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                                                                                                                                                                                  |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Atualização de segurança cumulativa para Internet Explorer (963027)                                                                               | [CVE-2009-0552](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0552)     | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Fatores atenuantes para o Internet Explorer 7 evitam a execução de código. O Internet Explorer 6 e versões anteriores têm probabilidade mais alta de exploração se não estiverem em dia com todas as atualizações de segurança.                                                                           |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Atualização de segurança cumulativa para Internet Explorer (963027)                                                                               | [CVE-2009-0553](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0553)     | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | (Nenhum)                                                                                                                                                                                                                                                                                                  |  
| [MS09-014](http://technet.microsoft.com/security/bulletin/ms09-014) | Atualização de segurança cumulativa para Internet Explorer (963027)                                                                               | [CVE-2009-0554](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0554)     | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                                                                                                                                                                                  |  
| [MS09-015](http://technet.microsoft.com/security/bulletin/ms09-015) | Vulnerabilidade de ameaças combinadas no SearchPath pode permitir a elevação de privilégio (959426)                                               | [CVE-2008-2540](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | Os detalhes do ataque foram divulgados, mas não existe nenhum vetor de ataque conhecido para este problema. A exploração bem-sucedida desta vulnerabilidade requer a execução de uma série de etapas complexas pelo invasor e pelo usuário, o que inclui salvar arquivos específicos na área de trabalho. |  
| [MS09-016](http://technet.microsoft.com/security/bulletin/ms09-016) | Vulnerabilidades no Microsoft ISA Server e Forefront Threat Management Gateway (Medium Business Edition) podem causar negação de serviço (961759) | [CVE-2009-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0077)     | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | A negação de serviço baseada em serviços é altamente provável. No entanto, a execução de código não é possível.                                                                                                                                                                                           |  
| [MS09-016](http://technet.microsoft.com/security/bulletin/ms09-016) | Vulnerabilidades no Microsoft ISA Server e Forefront Threat Management Gateway (Medium Business Edition) podem causar negação de serviço (961759) | [CVE-2009-0237](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-0237)          | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | A divulgação não autorizada de informações é possível. A execução de código é altamente improvável.                                                                                                                                                                                                       |
  
\*Este par de vulnerabilidades às quais foi atribuído o mesmo número na CVE é resolvido em duas atualizações de segurança. Consulte os respectivos boletins para obter mais informações.
  
\*\*Este par de vulnerabilidades às quais foi atribuído o mesmo número na CVE é resolvido em duas atualizações de segurança. Consulte os respectivos boletins para obter mais informações.
  
Softwares afetados e Locais de download  
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
</tr>
<tr>
<th colspan="7">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=552d322a-5282-42c7-9c1e-1d8c494a7318)  
(KB923561)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=39d5468e-5733-4c3e-9e75-3adac8ac8cb9)  
(Crítica)
</td>
<td style="border:1px solid black;">
[DirectX 8.1](http://www.microsoft.com/downloads/details.aspx?familyid=0ec5b7c7-13d3-467a-b24e-3cc6fb47adf6)  
(Crítica)  
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=8b98ed5c-a3ab-45a7-a61e-349eae304bc6)\*\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=7799fd05-5b26-449f-8a14-50227c9164d1)  
(Crítica)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=87f0c380-5c31-4099-a6a9-c12f9d69b03b)  
(Crítica)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=52b756e7-636f-4d9e-8a17-dbf467bfbe4d)  
(KB952004)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=c4e408d7-6716-4a12-ad3a-8029667f5c84)  
(Nenhuma classificação de gravidade)
</td>
</tr>
<tr>
<th colspan="7">
Windows XP (site em inglês)
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 e Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=50a8519a-503e-43dd-a78a-c1bc764fd213)  
(KB923561)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=35af4151-1858-4c9a-85e4-9ff45feca1a4)  
(Crítica)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=feb5d821-f210-40e8-b1aa-2ca3170df8df)\*\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=052c29fc-e8df-402c-9ab1-1079bc738e1b)  
(Crítica)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=55d6729a-9f96-4da4-b564-676c0a0c9390)  
(Crítica)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=90fe715e-8190-43e9-9c43-df5be564d923)  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=73d2324f-be59-4b0c-b1ac-9876a13c2c03)  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3de0684d-605c-489b-bdc7-08bce9b2d4f6)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c)  
(KB923561)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=49b16f0f-f6c3-4ca8-8041-392f4f7b5bbb)  
(Crítica)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f1be8b7c-4874-4342-99b3-76ff725fbb9a)\*\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=84c62211-2e82-4ccc-9f9b-26462b026d86)  
(Crítica)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=191c2f20-89ae-4e1c-bdd4-24b4abfe6b6c)  
(Crítica)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a794c32a-9a0c-47d9-9c57-ff5d4a8e4944)  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b2f12ae5-0e46-47e1-ac5b-93550d030189)  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b743a7fe-7bf4-420d-a72e-39471e5659fa)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
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
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2233a4d2-7c8a-4c89-b020-100d9afb43c8)  
(KB923561)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=42509f5a-d0f9-444a-9445-5eabdb555011)  
(Crítica)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=c1b4cd76-1dd6-43fa-bb9a-20c428985bfd)\*\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f73a3669-c17f-4b18-8456-96cb7d52ed86)  
(Importante)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6a45dbd0-0520-4d9b-b76e-3f5109dd310d)  
(Importante)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=25adec10-db8c-4cac-bf74-2c784678150a)  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=42aba890-8b76-4c5a-8fb6-609797d19831)  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=992bb0cd-fbc7-4a7c-9088-f7f9d9a3ead0)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c)  
(KB923561)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7373ea32-bc2e-49f1-8b9f-4eeda5acc74c)  
(Crítica)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f0e1e1db-94a5-451c-ab11-6b431fa065f1)\*\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=03a9d581-2bd5-4151-9826-17b96e16f606)  
(Importante)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=60ccc1d6-ea31-420c-b630-d7878a8dc527)  
(Importante)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b014c399-f404-4cb2-8f9d-864df382efeb)  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0609f65-82d9-4d82-9f48-f3266e8de123)  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f0a58e8c-7d63-4d7d-ba95-b3787cf408f0)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=e840b9cb-f1f4-482a-aa07-eb6b42b477c4)  
(KB923561)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=05e33cc5-cff6-4c71-be71-285f66a95e01)  
(Crítica)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=8f36c215-fa8a-40c2-b680-6b1fece03b8d)\*\*\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=53d13c07-80b0-4f05-b372-a2dac17e6157)  
(Importante)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0abaa2fb-7c4f-4149-993d-1575888bfc84)  
(Importante)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=6ada372b-ba17-433e-b022-d2c57b35af8a)  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=fda8837c-e5d2-4489-9b44-4c24a1102e77)  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=00c6479d-f81f-445d-b8e4-7b71d77d540a)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista e Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f071d770-3b6b-4040-9911-d4de8cde4c68)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d743849d-f3b5-4114-adef-ade2716d55ac)  
(Crítica)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f111b99a-e555-4f29-8d1f-e9ec03d5cf1f)  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d0ea1598-45cb-4c79-8945-caae98969675)  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2b672d45-f33b-4edc-9f22-2f2c8c726a8b)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7ceef2d0-f316-48d1-aecc-d74f91cc5e1f)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d191c8dc-a965-4a6a-b6d8-1470505eb55f)  
(Crítica)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=fa153bdc-6b48-4df2-9e5e-abacd6da782c)  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6dd82f4b-bb33-41ec-90a7-9ef91329b240)  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7576e7d5-5bb1-4a53-b568-1ee0500ce721)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://technet.microsoft.com/security/bulletin/ms09-015)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=4c36548f-c8c9-4318-91e2-9e0501339548)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e2c6313c-3ba9-4f7c-b259-b4582a390146)\*\*  
(Importante)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=9e3c7b52-65a7-42fb-beb5-1b374934737f)\*  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=d58702af-bbf8-4f1b-ae72-ced9ef23d581)\*  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=6b73cf5e-66fe-4b7d-95fc-91a1c262c1e5)\*  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=1c3f0997-a8a9-4340-ae0c-2c4d6792c65c)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ebbade9d-704c-440b-8796-6d64225ac01a)\*\*  
(Importante)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=eebb4d4d-29d2-4247-8cbb-63a3b17585ec)\*  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=20bf4e9b-909b-4bc3-ae43-322d74a4f1c3)\*  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=7e60847c-b341-4c38-bc25-2e3cf2d4ae14)\*  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=0885b3b0-b78e-4980-902d-dff3886bcaac)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1b04aa6f-b787-4122-bf82-0d150618fe7a)  
(Importante)
</td>
<td style="border:1px solid black;">
Atualização do MSDTC Transaction Facility:  
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=cc383c24-b0f6-47c1-9e89-6a378b09e82f)  
(KB952004)  
(Importante)  
Atualização do Windows Service Isolation:  
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=bcc2b18f-67db-4109-a9f4-764f985423ee)  
(KB956572)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=de1c2b4b-af47-4b9a-8363-720e5527573c)  
(Moderada)
</td>
</tr>
</table>

<p></p>

 
**Observações para o Windows Server 2008**

**\*Instalação do núcleo de servidor do Windows Server 2008 afetada.** Essa atualização se aplica às edições do Windows Server 2008 com suporte, com a mesma classificação de gravidade, se o Windows Server 2008 tiver sido instalado usando a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre essa opção de instalação, consulte [Núcleo do Servidor](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008. Consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Instalação do núcleo de servidor do Windows Server 2008 não afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 com suporte se o Windows Server 2008 for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre essa opção de instalação, consulte [Núcleo do Servidor](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008. Consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Observação para o boletim MS09-010**

Consulte também a seção, **Microsoft Office Suites e Software** para obter mais arquivos de atualização. Este boletim abrange tanto o sistema operacional Windows e seus componentes quanto os conjuntos e softwares do Microsoft Office.

**Observação para o boletim MS09-011**

\*\*\*A atualização para DirectX 9.0 também se aplica ao DirectX 9.0a, DirectX 9.0b e DirectX 9.0c.

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
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://technet.microsoft.com/security/bulletin/ms09-009)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=95876927-e612-414c-bdec-3632a3100415)  
(KB921606)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3dc8b670-25a5-4f46-b7de-12bc693b628a)  
(KB959964)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e1db55c6-78fb-498d-89a5-9ad54d971546)  
(KB933399)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9a52bf4b-05f6-4b73-94b9-28ed7e20f86c)  
(KB959988)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d9dbfa63-c0cb-4c84-9b8a-6e52568045b0)  
(KB959995)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=50d8630b-1365-4007-81a0-18c0d6d4b86e)\*  
(KB959997)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office para Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://technet.microsoft.com/security/bulletin/ms09-009)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 para Mac
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 para Mac](http://www.microsoft.com/downloads/details.aspx?familyid=52271140-89be-4b9c-baa2-cea09097d703)  
(KB968695)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 para Mac
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 para Mac](http://www.microsoft.com/downloads/details.aspx?familyid=f6e407eb-11a5-433f-8006-4b822953ca98)  
(KB968694)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Outros softwares do Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://technet.microsoft.com/security/bulletin/ms09-009)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c72e6087-b48f-4d2d-8366-01d9f5ff6b6c)  
(KB959993)  
(Importante)  
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=58b3929c-5373-47a4-aa97-66d179758792)  
(KB960000)  
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
[Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=05f7c517-e551-4dcd-b24a-5d548f2d09cf)  
(KB960003)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=d763fae3-b2af-47f9-a554-ec786766b3c3)  
(KB960476)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS09-010**

Consulte também a seção **Componentes e sistema operacional Windows** para obter mais arquivos de atualização. Este boletim abrange tanto o sistema operacional Windows quanto os componentes e o software de servidor da Microsoft.

**Observação para o boletim MS09-009**

\*Para o Microsoft Office Excel 2007 Service Pack 1, os clientes também precisam instalar a atualização de segurança para o Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 1 para se protegerem das vulnerabilidades descritas neste boletim.

#### Microsoft Server e software de segurança

 
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
Microsoft Forefront
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-016**](http://technet.microsoft.com/security/bulletin/ms09-016)
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
Microsoft Forefront Threat Management Gateway
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Threat Management Gateway, Medium Business Edition](http://www.microsoft.com/downloads/details.aspx?familyid=6abf9fb4-42d0-4c67-935f-8dc67850148b)\*  
(KB968075)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Internet Security and Acceleration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-016**](http://technet.microsoft.com/security/bulletin/ms09-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=adf623fa-2d74-4f2a-9835-4b8debdb0e1b)\*\*  
(KB960995)  
(Importante)  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d1d55ab6-3de5-4811-9693-8d43f49f5fe8)  
(KB960995)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770)  
(KB968078)  
(Importante)  
[Atualização de Suporte do Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770)  
(KB968078)  
(Importante)  
[Microsoft Internet Security and Acceleration Server 2006 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770)  
(KB968078)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS09-016**

\*O Microsoft Forefront Threat Management Gateway, Medium Business Edition, é fornecido como um produto autônomo e como um componente do Windows Essential Business Server 2008.

\*\*O Microsoft ISA Server 2004 Standard Edition é fornecido com um produto autônomo. O Microsoft ISA Server 2004 Standard Edition também é fornecido como um componente do Windows Small Business Server 2003 Enterprise Edition Service Pack 1 e do Windows Small Business Server 2003 R2 Enterprise Edition.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://go.microsoft.com/fwlink/?linkid=85102), no qual essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) e [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Frequentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

**Orientação para detecção e implantação**

A Microsoft está oferecendo uma orientação de detecção e implantação para as atualizações de segurança deste mês. Essa orientação também ajudará os profissionais de TI a entender como eles podem usar as várias ferramentas para ajudar a implantar a atualização de segurança, tal como o Windows Update, Microsoft Update, Atualização do Office, as ferramentas MBSA (Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server (SMS) e a Ferramenta Extended Security Update Inventory (ESUIT). Para obter mais informações, consulte o [Artigo 910723 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Windows 2000 e posterior, Office XP e superior, Exchange Server 2003, e SQL Server 2000 nos sistemas operacionais Windows 2000 e superior.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários. O próximo lançamento do SMS, System Center Configuration Manager 2007, já está disponível; consulte também [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Para obter mais informações sobre como os administradores podem usar o SMS 2003 para instalar atualizações de segurança, consulte [Gerenciamento de Patches de Segurança do SMS 2003.](http://go.microsoft.com/fwlink/?linkid=22939) Os usuários do SMS 2.0 também podem usar o [Software Updates Service Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) (em inglês) para ajudar a implantar atualizações de segurança. Para obter informações sobre o SMS, visite [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer e a ferramenta de detecção do Microsoft Office para fornecer amplo suporte à detecção e à implantação de atualizações do boletim de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para apontar as atualizações de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) e no [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) (sites em inglês) para instalar essas atualizações.

**Avaliador de Compatibilidade com Atualizações e Kit de Ferramentas de Compatibilidade de Aplicativo**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) incluídos no [Kit de ferramentas de compatibilidade de aplicativos 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Kit de ferramentas de compatibilidade de aplicativos (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações de alta prioridade que não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações novas, revisadas e liberadas para produtos da Microsoft que não sejam o Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

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

-   Haifei Li, da [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) da Fortinet, por relatar um problema descrito no boletim MS09-009
-   Sean Larsson e Jun Mao, da [VeriSign iDefense Labs](http://labs.idefense.com/), por relatarem um problema descrito no boletim MS09-010
-   Um pesquisador do [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) da Fortinet por relatar um problema descrito no MS09-010
-   Um pesquisador da [VeriSign iDefense Labs](http://labs.idefense.com/) por relatar um problema descrito no MS09-010
-   Piotr Bania, da [Kryptos Logic](http://www.kryptoslogic.com/), por relatar um problema descrito no MS09-011
-   Cesar Cerrudo, da [Argeniss](http://www.argeniss.com/) por relatar vários problemas descritos no MS09-012
-   Greg MacManus, da [iSIGHT Partners Labs](http://www.isightpartners.com/), por relatar um problema descrito no MS09-013
-   Wan-Teh Chang e Cem Paya, da [Google Inc.](http://www.google.com/), por relatar um problema descrito no MS09-013
-   [Aviv Raff](http://aviv.raffon.net/) por relatar um problema descrito no MS09-014
-   Michal Zalewski, da [Google Inc.](http://www.google.com/), por relatar um problema descrito no boletim MS09-014
-   Ivan Fratric, da [iSIGHT Partners Labs](http://www.isightpartners.com/), por relatar um problema descrito no MS09-014
-   Skylined, da [Google Inc.](http://www.google.com/), por relatar um problema descrito no boletim MS09-014
-   ADLab, da [Venus Tech](http://www.venustech.com.cn/), por relatar um problema descrito no MS09-014
-   [Aviv Raff](http://aviv.raffon.net/) por relatar um problema descrito no MS09-015
-   Diretor de Informações do Estado de Nova York/Escritório de Tecnologia por relatar um problema descrito no MS09-016

#### Suporte

-   O software afetado listado foi testado a fim de determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do [Suporte de Segurança](http://go.microsoft.com/fwlink/?linkid=21131) ou pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas. Para obter mais informações sobre as opções de suporte disponíveis, consulte [Ajuda e Suporte da Microsoft](http://support.microsoft.com/?ln=pt-br).
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (14 de abril de 2009): Resumo do Boletim publicado.
-   V1.1 (16 de abril de 2009): O Índice de exploração foi atualizado: as principais observações da vulnerabilidade CVE-2009-0089 foram removidas e as da CVE-2008-2540 foram alteradas nos boletins MS09-014 e MS09-015.

*Built at 2014-04-18T01:50:00Z-07:00*
