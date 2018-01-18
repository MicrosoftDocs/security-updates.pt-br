---
TOCTitle: 'MS12-MAR'
Title: Resumo do Boletim de Segurança da Microsoft de março 2012
ms:assetid: 'ms12-mar'
ms:contentKeyID: 61233690
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms12-mar(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de março 2012
=========================================================

Publicado: terça-feira, 13 de março de 2012

**Versão:** 1.0

Este resumo de boletins lista os boletins de segurança lançados em março de 2012.

Com o lançamento dos boletins de segurança de março de 2012, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 8 de março de 2012. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte Notificação antecipada dos boletins de segurança da Microsoft.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as Notificações de segurança técnica da Microsoft.

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 14 de março de 2012, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de março](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499508). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte Webcasts e resumos dos boletins de segurança da Microsoft.

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras** **informações.**

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
<th style="border:1px solid black;" >Requisitos de reinicialização</th>
<th style="border:1px solid black;" >Softwares afetados</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-020">MS12-020</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades na área de trabalho remota podem permitir a execução remota de código (2671387)</strong> <br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas particularmente no Protocolo de Área de Trabalho Remota. A mais severa das vulnerabilidades poderá permitir a execução remota de código se um invasor enviar uma sequência de pacotes de RDP especialmente criada para um sistema afetado. Por padrão, o RDP (Remote Desktop Protocol, Protocolo de Área de Trabalho Remota) não é habilitado em nenhum sistema operacional do Windows. Os sistemas que não têm RDP habilitado não estão em risco.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-017">MS12-017</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no DNS Server pode permitir a</strong> <strong>negação de serviço (2647170)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a negação de serviço se um invasor não autenticado remoto enviar uma consulta DNS especialmente criada ao servidor DNS de destino.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-018">MS12-018</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade nos drivers do modo do kernel do Windows pode permitir a elevação de privilégio (2641653)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir elevação de privilégio se um invasor fizer logon em um sistema e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-021">MS12-021</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Visual Studio pode permitir a elevação de privilégio (2651019)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Visual Studio. A vulnerabilidade pode permitir a elevação de privilégio se um invasor colocar um suplemento especialmente criado no caminho usado pelo Visual Studio e convencer um usuário com os privilégios mais altos a iniciar o Visual Studio. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade. Essa vulnerabilidade não pode ser explorada remotamente por usuários anônimos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-022">MS12-022</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Expression Design pode permitir a</strong> <strong>execução remota de código (2651018)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Expression Design. A vulnerabilidade pode permitir a execução remota de código se um invasor convencer um usuário a abrir um arquivo legítimo (como um arquivo .xpr ou .DESIGN) localizado no mesmo diretório de rede que um arquivo de biblioteca de link dinâmico (DLL) especialmente criado. Em seguida, ao abrir o arquivo legítimo, o Microsoft Expression Design pode tentar carregar o arquivo .DLL e executar o código contido nele. Para que um ataque seja bem-sucedido, o usuário precisa visitar um local no sistema de arquivos remoto não confiável ou um compartilhamento de WebDAV e abrir um arquivo legítimo (como um .xpr ou .DESIGN) desse local que seja então carregado por um aplicativo vulnerável.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Expression Design</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-019">MS12-019</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no DirectWritepode permitir a negação de serviço (2665364)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente no DirectWrite do Windows. Em um cenário de ataque baseado no Instant Messenger, a vulnerabilidade pode permitir a negação de serviço se um invasor enviar uma sequência especialmente criada de caracteres Unicode diretamente a um cliente do Instant Messenger. O aplicativo de destino pode parar de responder no momento que o DirectWrite processar a sequência especialmente criada de caracteres Unicode.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Moderada</a> <br />
Negação de Serviço</td>
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
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o Índice de exploração da Microsoft.
  
Nas colunas a seguir, "Versão mais Recente de Software" se refere ao software, e "Versões mais Antigas de Software se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID do Boletim</th>
<th style="border:1px solid black;" >Título da vulnerabilidade</th>
<th style="border:1px solid black;" >ID do CVE</th>
<th style="border:1px solid black;" >Avaliação da capacidade de exploração da última versão de software</th>
<th style="border:1px solid black;" >Avaliação da capacidade de exploração de versão mais antiga de software</th>
<th style="border:1px solid black;" >Avaliação do risco de exploração para negação de serviço</th>
<th style="border:1px solid black;" >Principais observações</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-017">MS12-017</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço de DNS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0006">CVE-2012-0006</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-018">MS12-018</a></td>
<td style="border:1px solid black;">Vulnerabilidade da Função PostMessage</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0157">CVE-2012-0157</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">2</a> - O código de exploração seria difícil de ser criado</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-020">MS12-020</a></td>
<td style="border:1px solid black;">Vulnerabilidade do Protocolo de área de trabalho remota</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0002">CVE-2012-0002</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de execução remota de código não autenticada.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-020">MS12-020</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço do Terminal Server</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0152">CVE-2012-0152</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">3</a> - Código de exploração improvável</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).<br />
<br />
Somente a última versão é afetada pelo Dos.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-021">MS12-021</a></td>
<td style="border:1px solid black;">Vulnerabilidade de Suplemento do Visual Studio</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0008">CVE-2012-0008</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms12-022">MS12-022</a></td>
<td style="border:1px solid black;">Vulnerabilidade de carregamento não seguro de biblioteca do Expression Design</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0016">CVE-2012-0016</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/cc998259.aspx">1</a> - Possível código de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
</tbody>
</table>

<p></p>

  
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
<th colspan="5">
Windows XP (site em inglês)  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador** **do** **boletim**
</td>
<td style="border:1px solid black;">
[**MS12-020**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-020)
</td>
<td style="border:1px solid black;">
[**MS12-017**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-017)
</td>
<td style="border:1px solid black;">
[**MS12-018**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-018)
</td>
<td style="border:1px solid black;">
[**MS12-019**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-019)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=18a1fe48-1318-4b93-afad-206950bb1ae5)  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2922411c-9755-461b-9904-f6940322af19)  
(Importante)
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
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eccf865d-399a-4862-b26f-f35580419875)  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e72b6b1f-68f5-4e1a-878e-290a5f03ca30)  
(Importante)
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
[**MS12-020**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-020)
</td>
<td style="border:1px solid black;">
[**MS12-017**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-017)
</td>
<td style="border:1px solid black;">
[**MS12-018**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-018)
</td>
<td style="border:1px solid black;">
[**MS12-019**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-019)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b69b4b9b-c0a1-4c1e-b081-8529eaf1536a)  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b04da098-666f-4760-90da-d2a17e78bf47)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=599e5db1-3bf1-4d44-bc7c-81bc545c58ec)  
(Importante)
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
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8081e67f-288c-4714-bff8-e0ff9777692f)  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=647eaf09-3959-439e-8418-fd25221eb6b9)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=482c2890-8d4c-4e13-820f-d5ff256b6a3a)  
(Importante)
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
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=521baa02-5d7a-4cba-8a1a-2af1b6e4cbe4)  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=92f3af60-9a9b-4419-9e95-55f5cb54cf00)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ccd0f116-73c2-4471-a6d9-e07d1dbdd406)  
(Importante)
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
[**MS12-020**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-020)
</td>
<td style="border:1px solid black;">
[**MS12-017**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-017)
</td>
<td style="border:1px solid black;">
[**MS12-018**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-018)
</td>
<td style="border:1px solid black;">
[**MS12-019**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-019)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=39abdf7b-ea9d-4b95-a28d-4140374d531d)  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f4e73a92-583b-4352-b19d-7a8e3ef162b7)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7da5b341-6a6f-46de-8d01-448da38e9908)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e5970daf-4440-42fa-8efc-e6190c6a22aa)  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ead9d29b-becf-448e-bff4-d5bb12d02c64)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1ba25d9c-0fef-471f-8e30-045fe9586a9c)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-020**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-020)
</td>
<td style="border:1px solid black;">
[**MS12-017**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-017)
</td>
<td style="border:1px solid black;">
[**MS12-018**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-018)
</td>
<td style="border:1px solid black;">
[**MS12-019**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-019)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fef2c1d7-2004-43d7-aa49-673c6f374670)\*  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=233c62b7-f2b1-49ce-9a7f-e51435be0d26)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2\*  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2\*\*  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2\*  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2\*  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2\*  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2\*\*  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(KB2621440)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
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
[**MS12-020**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-020)
</td>
<td style="border:1px solid black;">
[**MS12-017**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-017)
</td>
<td style="border:1px solid black;">
[**MS12-018**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-018)
</td>
<td style="border:1px solid black;">
[**MS12-019**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-019)
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
Nenhuma
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
Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=16b0195c-84d3-4c08-8b98-ff2c80d144e1)  
(KB2621440)  
(Crítica)  
[Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3a6c7fdf-105a-4886-ad52-c892f37e32d1)  
(KB2667402)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 e Windows 7 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x64 e Windows 7 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=40b62d08-d2a2-4900-b01c-46fc761973d0)  
(KB2621440)  
(Crítica)  
[Windows 7 para sistemas baseados em x64 e Windows 7 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1bbe7cda-4bee-4d65-8127-3c13624a1168)  
(KB2667402)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 e Windows 7 para sistemas baseados em x64 Service Pack 1  
(Importante)
</td>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64 e Windows 7 para sistemas baseados em x64 Service Pack 1  
(Moderada)
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
[**MS12-020**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-020)
</td>
<td style="border:1px solid black;">
[**MS12-017**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-017)
</td>
<td style="border:1px solid black;">
[**MS12-018**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-018)
</td>
<td style="border:1px solid black;">
[**MS12-019**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-019)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
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
Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7c1774cc-e00c-47f3-97a2-bc90de857793)\*  
(KB2621440)  
(Crítica)  
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7ec21f41-1673-4592-b45c-6438ad57e08c)\*  
(KB2667402)  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1\*  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1\*  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1\*\*  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium  
(KB2621440)  
(Crítica)  
Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium  
(KB2667402)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium  
(Importante)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium  
(Moderada)
</td>
</tr>
</table>

<p></p>

 
**Observações para Windows Server 2008 e Windows Server 2008 R2**

**\*Instalação do núcleo do servidor afetada.** Esta atualização se aplica, com a mesma classificação de gravidade, às edições com suporte do Windows Server 2008 e do Windows Server 2008 R2, conforme indicado, independentemente de terem sido instalados ou não com a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**\*\*Instalação de Núcleo de Servidor afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

#### Software e ferramentas para desenvolvedor da Microsoft

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-021**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-021)
</td>
<td style="border:1px solid black;">
[**MS12-022**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-022)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de** **gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=99d7c39a-14f1-4e7e-8a4f-2466b16821eb)  
(KB2669970)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2010
</td>
<td style="border:1px solid black;">
Microsoft Visual Studio 2010  
(KB2644980)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e2aaec35-b2c0-48f0-8a51-34e44f6d12fb)  
(KB2645410)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Expression Design
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS12-021**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-021)
</td>
<td style="border:1px solid black;">
[**MS12-022**](http://technet.microsoft.com/pt-br/security/bulletin/ms12-022)
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design](http://www.microsoft.com/downloads/details.aspx?familyid=49e12f3a-718d-4d54-82be-b78efb372d07)  
(KB2675064)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Design Service Pack 1
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=899c6860-6081-429b-971a-4d689444920f)  
(KB2667724)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design 2
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ca4fb5a-3ab4-410b-b42b-075eb1d70410)  
(KB2667725)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Design 3
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 3](http://www.microsoft.com/downloads/details.aspx?familyid=73b44e97-6dda-4e24-9758-e86a1de4c0c8)  
(KB2667727)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design 4
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 4](http://www.microsoft.com/downloads/details.aspx?familyid=be56221e-4271-42dc-a6e4-ebf0290e4ad8)  
(KB2667730)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o Centro de Gerenciamento de Atualização do Technet. O site TechNet Security Center fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar Segurança em Casa, onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no Microsoft Update e no Windows Update. As atualizações de segurança também estão disponíveis no Centro de Download da Microsoft. Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Para os clientes do Microsoft Office for Mac, o Microsoft AutoUpdate for Mac pode ajudar a manter seu software Microsoft atualizado. Para obter mais informações sobre como usar o Microsoft AutoUpdate for Mac, consulte Check for software updates automatically.

Por fim, as atualizações de segurança podem ser baixadas do Microsoft Update Catalog. O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis à sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as Perguntas Frequentes sobre Microsoft Update Catalog.

**Orientação de detecção e implantação:**

A Microsoft oferece orientações de detecção e implantação de atualizações de segurança. Essas orientações contêm recomendações e informações que podem ajudar os profissionais de TI a entender como usar várias ferramentas para detecção e implantação de atualizações de segurança. Para obter mais informações, consulte o Artigo 961747 (em inglês) da Microsoft Knowledge Base.

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite Microsoft Baseline Security Analyzer.

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite Windows Server Update Services.

**System Center Configuration Manager 2007**

O gerenciamento de atualizações de software do Configuration Manager 2007 simplifica a complexa tarefa de fornecer e gerenciar atualizações a sistemas de TI pela empresa. Com o Configuration Manager 2007, os administradores de TI podem fornecer atualizações de produtos da Microsoft a uma variedade de dispositivos, inclusive desktops, laptops, servidores e dispositivos móveis.

A avaliação automatizada de vulnerabilidade no Configuration Manager 2007 detecta as necessidades de atualizações e relatórios com relação a ações recomendadas. O gerenciamento de atualizações de software no Configuration Manager 2007 é integrado ao Microsoft Windows Software Update Services (WSUS), uma infraestrutura de atualização testada quanto à confiabilidade, que é familiar aos administradores de TI do mundo todo. Para obter mais informações sobre como os administradores podem usar o Configuration Manager 2007 para implantar atualizações, consulte Gerenciamento de atualizações de software. Para obter mais informações sobre o Configuration Manager, acesse: System Center Configuration Manager.

**Systems Management Server 2003**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários.

**Observação** O System Management Server 2003 está fora de suporte principal desde 12 de janeiro de 2010. Para obter mais informações sobre ciclos de vida de produtos, acesse Ciclo de Vida do Suporte Microsoft. A próxima versão do SMS, System Center Configuration Manager 2007, já está disponível; consulte também o **System Center Configuration Manager 2007**.

Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, consulte Cenários e procedimentos para o Microsoft Systems Management Server 2003: Distribuição de software e Gerenciamento de patches. Para obter informações sobre o SMS, acesse: Microsoft Systems Management Server TechCenter.

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte Implementando atualizações de software usando o Recurso Distribuição de Software do SMS. Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no SMS 2003 Administration Feature Pack) para instalar essas atualizações.

**Avaliador de compatibilidade com atualizações e Kit de ferramentas de compatibilidade de aplicativos**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do Avaliador de compatibilidade com atualizações incluídos no Kit de ferramentas de compatibilidade de aplicativos para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   Artigo 894199 (em inglês) da Microsoft Knowledge Base
-   : Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   Atualizações dos meses anteriores para o Windows Server Update Services
-   . Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em Parceiros do Microsoft Active Protections Program (MAPP).

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

A Microsoft agradece às pessoas mencionadas abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   [Nikolaos Bougalis](https://technet.microsoft.com/pt-BR/mailto:nikb@bougalis.net)
-   , por relatar um problema descrito no boletim MS12-018
-   Khaled M. Salameh por relatar um problema descrito no MS12-019
-   Luigi Auriemma, que trabalha com a Zero Day Initiative da [TippingPoint](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS12-020
-   [Laplinker](http://www.laplinker.com)
-   por relatar um problema descrito no boletim MS12-021
-   [Laplinker](http://www.laplinker.com)
-   por relatar um problema descrito no boletim MS12-022

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site Ciclo de Vida do Suporte Microsoft.
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do Suporte de Segurança ou pelo 1-866-PCSAFETY, telefone 1-866-727-2338. Para obter mais informações sobre as opções de suporte disponíveis, consulte Ajuda e Suporte da Microsoft.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de Ajuda e Suporte Internacional.

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (13 de março de 2012): Resumo de boletins publicado.

*Built at 2014-04-18T01:50:00Z-07:00*
