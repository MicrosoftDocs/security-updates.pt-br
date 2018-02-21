---
TOCTitle: 'MS12-NOV'
Title: Resumo do Boletim de Segurança da Microsoft de novembro 2012
ms:assetid: 'ms12-nov'
ms:contentKeyID: 61233692
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms12-nov(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de novembro 2012
============================================================

Publicado: terça-feira, 13 de novembro de 2012 | Atualizado: quarta-feira, 14 de novembro de 2012

**Versão:** 2.0

Este resumo relaciona os boletins de segurança lançados em novembro de 2012.

Com o lançamento dos boletins de novembro de 2012, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 8 de novembro de 2012. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 14 de novembro de 2012, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de novembro.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522560&culture=en-us) Depois dessa data, este webcast estará disponível [sob demanda](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522560&culture=en-us).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

#### Sinopses

A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados e locais de download**.

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-071">MS12-071</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para</strong> <strong>o Internet Explorer (2761451)  <br />
<br />
</strong>Esta atualização de segurança resolve três vulnerabilidades relatadas em particular no Internet Explorer. As vulnerabilidades podem permitir a execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-072">MS12-072</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Shell do Windows podem permitir a</strong> <strong>execução remota de código (2727528)  <br />
<br />
</strong>Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Microsoft Windows. As vulnerabilidades podem permitir a execução remota de código se um usuário acessar um porta-arquivos especialmente criado no Windows Explorer. Um invasor que explorar com êxito essa vulnerabilidade pode executar o código arbitrário como o usuário real. Se o usuário atual estiver conectado com direitos administrativos, o invasor poderá assumir o controle total do sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-074">MS12-074</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades</strong> <strong>no .NET Framework podem permitir a execução remota de código (2745030)  <br />
<br />
</strong>Esta atualização de segurança elimina cinco vulnerabilidades relatadas particularmente no .NET Framework. A mais severa destas vulnerabilidades pode permitir a execução remota de código se um invasor convencer o usuário de um sistema de destino a usar um arquivo de configuração automática de um proxy mal-intencionado e então injetar código no aplicativo atualmente em execução.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-075">MS12-075</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades em drivers do modo do</strong> <strong>kernel</strong> <strong>do Windows podem permitir a execução remota de</strong> <strong>código (2761226)  <br />
<br />
</strong>Esta atualização de segurança elimina três vulnerabilidades relatadas em particular no Microsoft Windows. A mais rigorosa dessas vulnerabilidades pode permitir a execução remota do código se um usuário abrir um documento especialmente criado ou visitar uma página da Web mal-intencionada que incorpore arquivos de fonte TrueType. O invasor deve convencer os usuários a visitar o site, geralmente fazendo com que eles cliquem em um link em um e-mail que os leve ao site do invasor.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-076">MS12-076</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Excel podem permitir a execução remota de código (2720184)  <br />
<br />
</strong>Esta atualização de segurança elimina quatro vulnerabilidades relatadas em particular no Microsoft Office. As vulnerabilidades podem permitir a execução remota de código se um usuário abrir um arquivo do Excel especialmente criado com uma versão afetada do Microsoft Excel. O invasor que explorar com êxito as vulnerabilidades poderá ganhar os mesmos direitos de usuário que o usuário em questão. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-073">MS12-073</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Internet</strong> <strong>Information</strong> <strong>Services (IIS) podem permitir divulgação não autorizada de informações (2733829)  <br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e uma vulnerabilidade relatada em particular no Microsoft Internet Information Services (IIS). A mais severa das vulnerabilidades pode permitir a divulgação não autorizada de informações se um invasor enviar comandos especialmente criados do FTP para o servidor.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Moderada</a> <br />
Divulgação não autorizada de informação</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
  
| ID do Boletim                                                             | Título da vulnerabilidade                                                     | ID do CVE                                                                        | Avaliação da capacidade de exploração da última versão de software                                                  | Avaliação da capacidade de exploração de versão mais antiga de software                                             | Avaliação do risco de exploração para negação de serviço | Principais observações                                   |  
|---------------------------------------------------------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------|----------------------------------------------------------|  
| [MS12-071](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071) | Vulnerabilidade de uso após liberação do CFormElement                         | [CVE-2012-1538](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1538) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |  
| [MS12-071](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071) | Vulnerabilidade de uso após liberação do CTreePos                             | [CVE-2012-1539](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1539) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Temporário                                               | (Nenhum)                                                 |  
| [MS12-071](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071) | Vulnerabilidade de uso após liberação do CTreeNode                            | [CVE-2012-4775](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4775) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |  
| [MS12-072](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072) | Vulnerabilidade de subfluxo de número inteiro de porta-arquivos do Windows    | [CVE-2012-1527](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1527) | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |  
| [MS12-072](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072) | Vulnerabilidade de estouro de número inteiro de porta-arquivos do Windows     | [CVE-2012-1528](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1528) | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Temporário                                               | (Nenhum)                                                 |  
| [MS12-074](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074) | Vulnerabilidade de desvio de reflexo                                          | [CVE-2012-1895](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1895) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |  
| [MS12-074](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074) | Vulnerabilidade de divulgação de informações de segurança de acesso ao código | [CVE-2012-1896](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1896) | Não afetado                                                                                                         | [3](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Código de exploração improvável                    | Não Aplicável                                            | Essa é uma vulnerabilidade de divulgação de informações. |  
| [MS12-074](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074) | Vulnerabilidade de carregamento não seguro de bibliotecas do .NET Framework   | [CVE-2012-2519](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2519) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |  
| [MS12-074](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074) | Vulnerabilidade de autolocalização do Web proxy                               | [CVE-2012-4776](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4776) | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Permanente                                               | (Nenhum)                                                 |  
| [MS12-074](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074) | Vulnerabilidade de otimização de desvio WPF                                   | [CVE-2012-4777](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4777) | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |  
| [MS12-075](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075) | Vulnerabilidade de uso após liberação do Win32k                               | [CVE-2012-2530](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2530) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Permanente                                               | (Nenhum)                                                 |  
| [MS12-075](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075) | Vulnerabilidade de uso após liberação do Win32k                               | [CVE-2012-2553](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2553) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Permanente                                               | (Nenhum)                                                 |  
| [MS12-075](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075) | Vulnerabilidade de análise de fonte TrueType                                  | [CVE-2012-2897](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2897) | [2](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - O código de exploração seria difícil de ser criado | [2](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - O código de exploração seria difícil de ser criado | Permanente                                               | (Nenhum)                                                 |  
| [MS12-076](http://technet.microsoft.com/pt-br/security/bulletin/ms12-076) | Vulnerabilidade de estouro de heap de SerAuxErrBar do Excel                   | [CVE-2012-1885](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1885) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |  
| [MS12-076](http://technet.microsoft.com/pt-br/security/bulletin/ms12-076) | Vulnerabilidade de corrupção de memória do Excel                              | [CVE-2012-1886](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1886) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |  
| [MS12-076](http://technet.microsoft.com/pt-br/security/bulletin/ms12-076) | Vulnerabilidade de uso após liberação de extensão inválida do Excel           | [CVE-2012-1887](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1887) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |  
| [MS12-076](http://technet.microsoft.com/pt-br/security/bulletin/ms12-076) | Vulnerabilidade de estouro de pilha do Excel                                  | [CVE-2012-2543](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2543) | Não afetado                                                                                                         | [1](http://technet.microsoft.com/pt-br/security/cc998259.aspx) - Possível código de exploração                      | Não Aplicável                                            | (Nenhum)                                                 |
  
Softwares afetados e locais de download  
---------------------------------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
**Como uso estas tabelas?**  
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, haverá também um hiperlink para a atualização de software disponível e a classificação de gravidade da atualização de software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
#### Componentes e sistema operacional Windows

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="6">
Windows XP (site em inglês)  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fcc633d6-fe18-4220-9b68-ff1479e4dec5)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f5472e86-2b2f-42bd-abca-6adf84973efa)  
(KB2698035)  
(Somente Media Center Edition 2005 Service Pack 3 e Tablet PC Edition 2005 Service Pack 3)  
(Importante)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=31f2c645-b171-4f11-884b-f5056ef57b4f)  
(KB2761226)  
(Crítica)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a736c3f0-0326-4a0a-9c12-f61bafa537bb)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=828699ac-eb88-4ff8-9110-69c206f5ef54)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0383bdea-53d1-4799-b380-14da1595882a)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=efe0de22-8ca3-474e-acda-7203bf66d0a3)  
(KB2698032)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=73f5dec6-ccda-426d-8d2c-a2db3e59734a)  
(KB2761226)  
(Crítica)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=615a96fe-88a5-498b-ae20-bbfc43e3b652)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dc9cd62a-c42d-4c54-bc14-7abd34aeb865)  
(KB2761226)  
(Crítica)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=36962e96-0eaa-45a9-b2d6-6bec3242c73e)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=e4ec19ea-06f2-4164-8e39-84f1d7a47ae7)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=205f1cf3-5431-4740-96c2-eaf019edeeeb)   
(KB2761451)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c19585e3-a358-40b0-80a3-8dbb25ba8557)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c4b3fb44-338d-48be-9981-53fa2cf3094a)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 para IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1785af2-a211-467e-a696-d53840581bca)<sup>[1]</sup>
(KB2716513)  
(Moderada)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=b91091d0-176f-4ff9-98d2-74768b747c3a)<sup>[1]</sup>
(KB2716513)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7e7b681c-c580-4671-a515-e5b469002c93)   
(KB2761451)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=31f5ad28-ffe9-4370-b3fc-62eb9fc0c4dd)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7a58e874-f3fc-4db8-8de0-cbfc6ebbf349)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 para IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=2db93767-f364-49c6-9a03-39604173771f)<sup>[1]</sup>
(KB2716513)  
(Moderada)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=0c499445-595f-459f-86cf-b821cbb5fa65)<sup>[1]</sup>
(KB2716513)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0161baaa-5d7b-4442-a202-41c64a73c9a8)   
(KB2761451)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=258048b5-d992-4821-8836-72262a7b5bb7)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 para IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup>
(KB2716513)  
(Moderada)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup>
(KB2716513)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=52f652bd-edc4-4450-91b4-f19401d2201c)   
(KB2761451)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1c067cb2-71a5-4f8d-9b11-243c9e5318ce)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 para IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup>
(KB2716513)  
(Moderada)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup>
(KB2716513)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(Importante)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fab87b20-398f-4043-9cbe-ffcae8e19ff0)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)   
(KB2761451)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)   
(KB2761451)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)   
(KB2761451)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)   
(KB2761451)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)   
(KB2761451)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)   
(KB2761451)  
(Moderada)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(Moderada)
</td>
</tr>
<tr>
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
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="6">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=d7c93ade-f7e3-4b6f-b93d-894ca313282f)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b120a7a2-0eff-41d6-981e-60e5ecd55869)<sup>[2]</sup>
(KB2756872)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=24ce3f78-fb25-4f51-8bb0-8cebf19d8843)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 para sistemas de 64 bits
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=7c4a17b7-bb7f-456c-9cb3-3a355e192734)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c7a417e6-72e5-4087-bb89-fb8e7f57894c)<sup>[2]</sup>
(KB2756872)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
[Windows 8 para sistemas de 64 bits](http://www.microsoft.com/downloads/details.aspx?familyid=72c49d94-757c-4da4-a895-96d0830bc667)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=ad6189ae-9341-409b-a53e-486fef094fd0)  
(KB2727528)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>
(KB2756872)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa)  
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
**Nenhuma**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>
(KB2737084)  
(Importante)  
Microsoft .NET Framework 4.5<sup>[2]</sup><sup>[3]</sup>
(KB2756872)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2761226)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="6">
Opção de instalação de núcleo de servidor
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-071)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-072)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-074)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-075)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-073)
</td>
</tr>
<tr class="alternateRow">
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
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc) (instalação do núcleo do servidor)  
(KB2761226)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 para IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup>
(KB2716513)  
(Moderada)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup>
(KB2716513)  
(Moderada)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883) (instalação do núcleo do servidor)  
(KB2761226)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.0 para IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup>
(KB2716513)  
(Moderada)  
[Microsoft FTP Service 7.5 for IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup>
(KB2716513)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 (instalação do núcleo do servidor)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30) (instalação do núcleo do servidor)  
(KB2761226)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
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
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(Crítica)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30) (instalação do núcleo do servidor)  
(KB2761226)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft FTP Service 7.5 for IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(Moderada)  
[Serviços de Informações da Internet 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(Moderada)
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
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(Crítica)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(Importante)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>
(KB2756872)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa) (instalação Server Core)  
(KB2761226)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**Observação para o MS12-073**

<sup>[1]</sup>Serviço de FTP não padrão para este sistema operacional.

**Observações para o MS12-074**

<sup>[1]</sup>**.NET Framework 4 e .NET Framework 4** **Client** **Profile afetados.** Os pacotes redistribuíveis do .Net Framework versão 4 estão disponíveis em dois perfis: .NET Framework 4 e .NET Framework 4 Client Profile. O .NET Framework 4 Client Profile é um subconjunto do .NET Framework 4. A vulnerabilidade abordada nesta atualização afeta tanto o .NET Framework 4 quanto o .NET Framework 4 Client Profile. Para obter mais informações, consulte o artigo de MSDN, [Instalando o .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

<sup>[2]</sup>Clientes executando Microsoft .NET Framework 4.5 em Windows 8, Windows Server 2012, e Windows RT não são afetados por este problema. A Atualização cumulativa de disponibilidade geral do Windows 8 Client e Windows Server 2012 (KB2756872), lançada em 10 de outubro de 2012, contém alterações adicionais relacionadas à segurança. Os clientes que ainda não instalaram esta atualização devem fazê-lo como uma medida de proteção abrangente. Consulte a seção Mais informações no [artigo 2745030 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/2745030) para mais detalhes. Para baixar links e outras informações, consulte o [Artigo 2756872 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/2756872). Observe que esta atualização contém conteúdo não relacionado à segurança.

<sup>[3]</sup>As atualizações de segurança do Windows RT são fornecidas apenas pelo [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

**Observação para o MS12-075**

<sup>[1]</sup>A atualização está disponível apenas no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130).

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office Suites e componentes
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-076**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-076)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=5bb12b2b-a8e2-4324-afee-e4d26dbc658f)  
(KB2687481)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>
(KB2687307)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>
(KB2687307)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1 (edições de 32 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=37a1074d-bf4f-4b96-b394-1edc581748d0)  
(KB2597126)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1 (edições de 64 bits)](http://www.microsoft.com/downloads/details.aspx?familyid=5db02eae-966e-41a9-8b64-ddda5f8b2e2a)  
(KB2597126)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office para Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-076**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-076)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 para Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 para Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d3d801a2-d57f-4b4c-970a-c296bc716521)  
(KB2764048)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=0f4e073f-4fec-440d-a9bf-1e01ee9e92ad)  
(KB2764047)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Outros softwares do Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-076**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-076)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=a0917aeb-1e94-4142-bc20-5f1998ac249c)<sup>[2]</sup>
(KB2687313)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 2
</td>
<td style="border:1px solid black;">
[Pacote de compatibilidade do Microsoft Office Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office Service Pack 3
</td>
<td style="border:1px solid black;">
[Pacote de compatibilidade do Microsoft Office Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observações para o MS12-076**

<sup>[1]</sup>Para o Microsoft Excel 2007, além do pacote de atualização de segurança KB2687307, os clientes também precisam instalar a atualização de segurança para o Pacote de compatibilidade do Microsoft Office (KB2687311) para se protegerem das vulnerabilidades descritas neste boletim.

<sup>[2]</sup> O Microsoft Excel Viewer deve ser atualizado a um nível com suporte (Excel Viewer 2007 Service Pack 2 ou Excel Viewer 2007 Service Pack 3) antes de instalar esta atualização. Para obter mais informações sobre os visualizadores do Office, consulte o [Artigo 979860 (em inglês) do Microsoft Knowledge Base](http://support.microsoft.com/kb/979860).

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Microsoft Safety & Security Center](http://go.microsoft.com/fwlink/?linkid=85102), onde essas informações também estão disponíveis, clicando em “Atualizações de segurança”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) e no [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://www.microsoft.com/downloads/search.aspx?displaylang=pt-br). Você poderá encontrá-las com mais facilidade executando uma pesquisa com a palavra-chave "atualização de segurança".

Para os clientes do Microsoft Office for Mac, o Microsoft AutoUpdate for Mac pode ajudar a manter seu software Microsoft atualizado. Para obter mais informações sobre como usar o Microsoft AutoUpdate for Mac, consulte [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS12-001"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Frequentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

**Orientação de detecção e implantação:**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o [Artigo 961747 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Microsoft** **Baseline** **Security** **Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, consulte [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://technet.microsoft.com/wsus/default).

**SystemCenter** **Configuration** **Manager**

O gerenciamento de atualizações de software do System Center Configuration Manager simplifica a complexa tarefa de fornecer e gerenciar atualizações a sistemas de TI pela empresa. Com o System Center Configuration Manager, os administradores de TI podem fornecer atualizações de produtos da Microsoft a uma variedade de dispositivos, inclusive desktops, laptops, servidores e dispositivos móveis.

A avaliação automatizada de vulnerabilidade no System Center Configuration Manager detecta as necessidades de atualizações e relatórios com relação a ações recomendadas. O gerenciamento de atualizações de software no System Center Configuration Manager é integrado ao Microsoft Windows Software Update Services (WSUS), uma infraestrutura de atualização testada quanto à confiabilidade, que é familiar aos administradores de TI do mundo todo. Para obter mais informações sobre o System Center Configuration Manager, consulte: [System Center Technical Resources](http://technet.microsoft.com/systemcenter/bb980621).

**Systems Management Server 2003**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários.

**Observação** O System Management Server 2003 está fora de suporte principal desde 12 de janeiro de 2010. Para obter mais informações sobre ciclos de vida de produtos, acesse [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742). A próxima versão do SMS, System Center Configuration Manager, já está disponível; consulte a seção anterior: **System Center** **Configuration** **Manager**.

Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, consulte [Cenários e procedimentos para o Microsoft Systems Management Server 2003: Distribuição de software e Gerenciamento de patches](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f). Para obter informações sobre o SMS, acesse: [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)) para instalar essas atualizações.

**Avaliador de compatibilidade com atualizações e Kit de ferramentas de compatibilidade de aplicativos**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet.microsoft.com/library/cc749197) incluídos no [Kit de ferramentas de compatibilidade de aplicativos](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

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

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://www.microsoft.com/downloads/search.aspx?displaylang=pt-br). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [Artigo 913086 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (em inglês).

#### Agradecimentos

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) às pessoas mencionadas abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   Jose A. Vazquez, do spa-s3c.blogspot.com, que trabalha com a [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar dois problemas descritos no MS12-071
-   [Omair](http://krash.in/)
-   , por relatar um problema descrito no boletim MS12-071
-   Cheng-da Tsai (Orange), Sung-ting Tsai e Ming-chieh Pan (Nanika), da [Trend Micro](http://www.trendmicro.com/), por relatarem um problema descrito no boletim MS12-071
-   Tal Zeltzer, que trabalha com a [VeriSign iDefense Labs](http://labs.idefense.com/), por relatar dois problemas descritos no boletim MS12-072
-   Justin Royce, da ProDX, por relatar um problema descrito no boletim MS12-073
-   James Forshaw, da Context Information Security, por reportar quatro problemas descritos no boletim MS12-074
-   [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/)
-   , da
-   [Google Inc](http://www.google.com)
-   ., por relatar um problema descrito no boletim MS12-075
-   Eetu Luodemaa e Joni Vähämäki, da [Documill](http://www.documill.com), por relatarem um problema descrito no boletim MS12-075
-   Sean Larsson, que trabalha na [iDefense VCP](http://labs.idefense.com), por relatar um problema descrito no boletim MS12-076
-   Um pesquisador anônimo, que trabalha com a [iDefense VCP](http://labs.idefense.com), por relatar um problema descrito no boletim MS12-076
-   Um pesquisador anônimo, que trabalha com a [iDefense VCP](http://labs.idefense.com), por relatar um problema descrito no boletim MS12-076
-   Um pesquisador anônimo, que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/), por relatar um problema descrito no boletim MS12-076

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617,aspx)
-   Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (13 de novembro de 2012): Resumo de boletins publicado.
-   V1.1 (13 de novembro de 2012): Para o MS12-075, corrigido o título de CVE e a Avaliação do risco de exploração para negação de serviço no **Índice de exploração** para CVE-2012-2897.
-   V2.0 (14 de novembro de 2012): Para MS12-073, a Microsoft revisou o resumo do boletim para anunciar que já está disponível a atualização KB2716513 no Windows Vista e Windows Server 2008 em todos os canais de distribuição, inclusive no Windows Update e Microsoft Update. Consulte o boletim MS12-073 para obter informações detalhadas.

*Built at 2014-04-18T01:50:00Z-07:00*
