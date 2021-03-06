---
TOCTitle: 'MS13-JUN'
Title: Resumo do Boletim de Segurança da Microsoft de junho 2013
ms:assetid: 'ms13-jun'
ms:contentKeyID: 61233701
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms13-jun(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de junho 2013
=========================================================

Publicado: terça-feira, 11 de junho de 2013

**Versão:** 1.0

Este resumo de boletins lista os boletins de segurança lançados em junho de 2013.

Com o lançamento dos boletins de segurança de junho de 2013, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 6 de junho de 2013. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 12 de junho de 2013, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de junho](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us). Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

#### Sinopses

A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados**.

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-047">MS13-047</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para o Internet Explorer (2838727)  <br />
<br />
</strong>Esta atualização de segurança elimina 19 vulnerabilidades relatadas em particular no Internet Explorer. As vulnerabilidades mais graves podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que conseguir explorar a mais severa das vulnerabilidades poderá obter os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-048">MS13-048</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no kernel do Windows pode permitir a divulgação não autorizada de informações (2839229)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Windows. A vulnerabilidade pode permitir a divulgação de informações se um invasor fizer logon em um sistema e executar um aplicativo especialmente criado ou se convencer um usuário local conectado a executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade. Observe que essa vulnerabilidade não permite que um invasor execute códigos nem aumente seus direitos de usuário diretamente, mas ela pode ser usada para gerar informações úteis que poderiam ser usadas para tentar comprometer ainda mais o sistema afetado.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-049">MS13-049</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no driver do modo kernel pode permitir negação de serviço (2845690)</strong> <strong><br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a negação de serviço se um invasor enviar pacotes especialmente criados ao servidor. As práticas recomendadas para firewall e as configurações de firewall padrão podem ajudar a proteger as redes contra ataques com origem externa ao perímetro da empresa.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-050">MS13-050</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade nos componentes do spooler de impressão do Windows pode permitir a elevação de privilégio (2839894)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a elevação de privilégio se um invasor autenticado excluir a conexão com uma impressora. O invasor precisa ter credenciais de logon válidas e poder fazer logon para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms13-051">MS13-051</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no</strong> <strong>Microsoft Office pode permitir a execução remota de código (2839571)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office. A vulnerabilidade poderá permitir execução remota de código se um usuário abrir um documento Office especialmente criado usando uma versão afetada de software do Microsoft Office, visualizar ou abrir uma mensagem de email especialmente criada no Outlook ao usar o Microsoft Word como leitor de emails. O invasor que explorar com êxito essa vulnerabilidade poderá obter os mesmos direitos que o usuário atual. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
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
  
| ID do Boletim                                                             | Título da vulnerabilidade                                             | ID do CVE                                                                         | Avaliação da capacidade de exploração da última versão de software                                                  | Avaliação da capacidade de exploração de versão mais antiga de software                          | Avaliação do risco de exploração para negação de serviço | Principais observações                                                                     |  
|---------------------------------------------------------------------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|----------------------------------------------------------|--------------------------------------------------------------------------------------------|  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3110](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3110)  | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3111](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3111)  | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3112](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3112)  | [2](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - O código de exploração seria difícil de ser criado | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3113](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3113)  | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3114)  | [2](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - O código de exploração seria difícil de ser criado | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3116](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3116)  | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3117)  | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3118)  | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não afetado                                                                                      | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3119](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3119)  | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3120](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3120)  | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não afetado                                                                                      | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3121](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3121)  | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3122](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3122)  | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3123](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3123)  | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3124](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3124)  | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013- 3125](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3125) | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não afetado                                                                                      | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3139](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3139)  | Não Aplicável                                                                                                       | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | Esta é uma medida de proteção abrangente nos softwares mais recentes.                      |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3141)  | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-047](http://technet.microsoft.com/pt-br/security/bulletin/ms13-047) | Vulnerabilidade de corrupção de memória do Internet Explorer          | [CVE-2013-3142](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3142)  | [2](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - O código de exploração seria difícil de ser criado | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | (Nenhum)                                                                                   |  
| [MS13-048](http://technet.microsoft.com/pt-br/security/bulletin/ms13-048) | Vulnerabilidade de divulgação não autorizada de informações do kernel | [CVE-2013-3136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3136)  | 3 - Código de exploração improvável                                                                                 | [3](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Código de exploração improvável | Permanente                                               | Essa é uma vulnerabilidade de divulgação de informações.                                   |  
| [MS13-049](http://technet.microsoft.com/pt-br/security/bulletin/ms13-049) | Vulnerabilidade de estouro de número inteiro no TCP/IP                | [CVE-2013-3138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3138)  | [3](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Código de exploração improvável                    | [3](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Código de exploração improvável | Permanente                                               | Essa é uma vulnerabilidade de negação de serviço (site em inglês).                         |  
| [MS13-050](http://technet.microsoft.com/pt-br/security/bulletin/ms13-050) | Vulnerabilidade no spooler de impressão                               | [CVE-2013-1339](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1339)  | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Permanente                                               | (Nenhum)                                                                                   |  
| [MS13-051](http://technet.microsoft.com/pt-br/security/bulletin/ms13-051) | Vulnerabilidade de estouro de buffer no Office                        | [CVE-2013-1331](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1331)  | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração   | Não Aplicável                                            | A Microsoft está ciente dos ataques direcionados que tentam explorar essa vulnerabilidade. |
  
Softwares afetados  
------------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
**Como uso estas tabelas?**  
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
#### Componentes e sistema operacional Windows

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="5">
Windows XP (site em inglês)  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
**Nenhuma**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2838727)  
(Crítica)  
Internet Explorer 7   
(2838727)  
(Crítica)  
Internet Explorer 8   
(2838727)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2839229)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2838727)  
(Crítica)  
Internet Explorer 7   
(2838727)  
(Crítica)  
Internet Explorer 8   
(2838727)  
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
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2838727)  
(Moderada)  
Internet Explorer 7  
(2838727)  
(Moderada)  
Internet Explorer 8  
(2838727)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2839229)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2838727)  
(Moderada)  
Internet Explorer 7  
(2838727)  
(Moderada)  
Internet Explorer 8  
(2838727)  
(Moderada)
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
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2838727)  
(Moderada)  
Internet Explorer 7  
(2838727)  
(Moderada)
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
<th colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
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
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(Crítica)  
Internet Explorer 8  
(2838727)  
(Crítica)  
Internet Explorer 9   
(2838727)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2839229)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(Crítica)  
Internet Explorer 8  
(2838727)  
(Crítica)  
Internet Explorer 9   
(2838727)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador** **do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Internet Explorer 7  
(2838727)  
(Moderada)  
Internet Explorer 8  
(2838727)  
(Moderada)  
Internet Explorer 9   
(2838727)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2839229)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(Moderada)  
Internet Explorer 8  
(2838727)  
(Moderada)  
Internet Explorer 9   
(2838727)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2  
(2839894)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
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
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(Crítica)  
Internet Explorer 9   
(2838727)  
(Crítica)  
Internet Explorer 10   
(2838727)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2839229)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1  
(2839894)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(Crítica)  
Internet Explorer 9   
(2838727)  
(Crítica)  
Internet Explorer 10   
(2838727)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade** **agregada**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(Moderada)  
Internet Explorer 9   
(2838727)  
(Moderada)  
Internet Explorer 10   
(2838727)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64  
(2839894)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2838727)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2839229)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2845690)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2839894)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2838727)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits  
(2845690)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2838727)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845690)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<th colspan="5">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2838727)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows RT  
(2845690)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows RT  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<th colspan="5">
Opção de instalação de núcleo de servidor
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)  
(2839229)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação do núcleo do servidor)  
(2839894)  
(Importante)
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
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do núcleo do servidor)  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação do núcleo do servidor)  
(2839894)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)  
(2845690)  
(Moderada)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação do núcleo do servidor)  
(2839894)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
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
(2845690)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2839894)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Softwares do Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS13-051**](http://go.microsoft.com/fwlink/?linkid=296303)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de severidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
(2817421)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2848689)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

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

**System Center Configuration Manager**

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

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199)
-   : Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965)
-   . Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

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

**MS13-047**

-   Scott Bell, da [Security-Assessment.com](http://www.security-assessment.com/), por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3110)
-   SkyLined, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP,](http://www.hpenterprisesecurity.com/products) por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3111)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3112)
-   Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google](http://www.google.com/), por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3113)
-   Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google](http://www.google.com/), por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3114)
-   Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google](http://www.google.com/), por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3116)
-   Ivan Fratric e Ben Hawkes, da [Equipe de segurança do Google](http://www.google.com/), por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3117)
-   [Omair](http://krash.in/)
-   , que trabalha com a
-   [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)
-   [da HP](http://www.zerodayinitiative.com/)
-   , por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3118)
-   Stephen Fewer, da [Harmony Security](http://www.harmonysecurity.com), que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3119)
-   SkyLined, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP,](http://www.hpenterprisesecurity.com/products) por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3120)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3121)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3122)
-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com)
-   , que trabalha com a
-   [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)
-   [da HP](http://www.zerodayinitiative.com/)
-   , por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3123)
-   [Omair](http://krash.in/)
-   , que trabalha com a
-   [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)
-   [da HP](http://www.zerodayinitiative.com/)
-   , por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3124)
-   Amol Naik, que trabalha com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)[da HP](http://www.zerodayinitiative.com/), por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3124)
-   [Omair](http://krash.in/)
-   , que trabalha com a
-   [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)
-   [da HP](http://www.zerodayinitiative.com/)
-   , por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3125)
-   Amol Naik, que trabalha com a [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)[da HP](http://www.zerodayinitiative.com/), por reportar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3125)
-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com)
-   , que trabalha com a
-   [Zero Day Initiative](http://www.hpenterprisesecurity.com/products)
-   [da HP](http://www.zerodayinitiative.com/)
-   , por reportar a vulnerabilidade de depuração de script do Internet Explorer (CVE-2013-3126)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3141)
-   Toan Pham Van, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2013-3142)

**MS13-048**

-   [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)
-    da 
-   [Google Inc](http://www.google.com/)
-    por informar a vulnerabilidade da divulgação de informações do kernel (CVE-2013-3136)

**MS13-051**

-   Andrew Lyons e Neel Mehta da [Google Inc](http://www.google.com/) por informar a vulnerabilidade de estouro de buffer do Office (CVE-2013-1331)

#### Suporte

-   O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (11 de junho de 2013): Resumo de boletins publicado.

*Built at 2014-04-18T01:50:00Z-07:00*
