---
TOCTitle: 'MS11-NOV'
Title: Resumo do Boletim de Segurança da Microsoft de novembro 2011
ms:assetid: 'ms11-nov'
ms:contentKeyID: 61233679
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms11-nov(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de novembro 2011
============================================================

Publicado: terça-feira, 8 de novembro de 2011

**Versão:** 1.0

Este resumo relaciona os boletins de segurança lançados em novembro de 2011.

Com o lançamento dos boletins de novembro de 2011, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 3 de novembro de 2011. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte Notificação antecipada dos boletins de segurança da Microsoft.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as Notificações de segurança técnica da Microsoft.

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 9 de novembro de 2011, às 11 horas - Hora do Pacífico (EUA e Canadá). Registre-se agora para participar do Webcast do boletim de segurança de novembro. Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte Webcasts e resumos dos boletins de segurança da Microsoft.

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-083">MS11-083</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no TCP/IP pode permitir a execução remota de código (2588516)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um invasor enviar um fluxo contínuo de pacotes UDP especialmente criados para uma porta fechada de um sistema de destino.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Crítica</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-085">MS11-085</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Windows Mail e Windows Meeting Space pode permitir a execução remota de código (2620704)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade pode permitir a execução remota de código se um invasor convencer um usuário a abrir um arquivo legítimo localizado no mesmo diretório de rede que um arquivo de biblioteca de link dinâmico (DLL) especialmente criado. Em seguida, ao abrir o arquivo legítimo, o Windows Mail ou Windows Meeting Space pode tentar carregar o arquivo DLL e executar qualquer código contido nele. Para que um ataque seja bem-sucedido, o usuário precisa visitar um local no sistema de arquivos remoto não confiável ou um compartilhamento de WebDAV e abrir um arquivo legítimo (como um .eml ou .wcinv) desse local que seja então carregado por um aplicativo vulnerável.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-086">MS11-086</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Active Directory pode permitir a elevação de privilégio (2630837)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Active Directory, no Modo de Aplicativo do Active Directory (ADAM) e no Active Directory Lightweight Directory Service (AD LDS). A vulnerabilidade pode permitir elevação de privilégio caso o Active Directory seja configurado para usar LDAP sobre SSL (LDAP) e um invasor adquira um certificado cancelado que esteja associado a uma conta de domínio válida e então use esse certificado para autenticação no domínio do Active Directory. Por padrão, o Active Directory não é configurado para usar LDAP sobre SSL.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.mspx">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/security/bulletin/ms11-084">MS11-084</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no modo kernel do Windows pode permitir</strong> <strong>negação de serviço (2617657)</strong> <br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Windows. A vulnerabilidade poderá permitir negação de serviço se um usuário abrir um arquivo de fonte TrueType especialmente criado como um anexo de email ou acessar um compartilhamento de rede ou local de WebDAV que contenha um arquivo de fonte TrueType especialmente criado. Para um ataque remoto ser bem-sucedido, o usuário deve visitar um local de sistema de arquivos remoto não confiável ou compartilhamento WebDAV que contenha um arquivo de fonte TrueType especialmente criado ou abrir o arquivo como um anexo de email. Em todos os casos, entretanto, o invasor não tem como forçar os usuários a realizar essas ações. Em vez disso, um invasor teria que convencer os usuários a fazer isso, normalmente convencendo-os a clicar em um link em uma mensagem de e-mail ou do Instant Messenger.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderada</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Exige reinicialização</td>
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
  
| ID do Boletim                                                             | Título da vulnerabilidade                                                                 | ID do CVE                                                                        | Avaliação do risco de exploração para execução de códigos do última versão do software                        | Avaliação do risco de exploração para execução de códigos das versões de software mais antigas                | Avaliação do risco de exploração para negação de serviço | Principais observações |  
|---------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|----------------------------------------------------------|------------------------|  
| [MS11-083](http://technet.microsoft.com/pt-br/security/bulletin/ms11-083) | Vulnerabilidade de estouro do contador de referência                                      | [CVE-2011-2013](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2013) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente? | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente? | Permanente                                               | (Nenhum)               |  
| [MS11-085](http://technet.microsoft.com/pt-br/security/bulletin/ms11-085) | Vulnerabilidade de carregamento não seguro de bibliotecas dos componentes do Windows Mail | [CVE-2011-2016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2016) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente    | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente    | Não Aplicável                                            | (Nenhum)               |  
| [MS11-086](http://technet.microsoft.com/pt-br/security/bulletin/ms11-086) | Vulnerabilidade de anulação de autenticação do LDAPS                                      | [CVE-2011-2014](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2014) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente    | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente    | Não Aplicável                                            | (Nenhum)               |
  
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
</tr>
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
[**MS11-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[**MS11-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[**MS11-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-084)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=8c7c21c5-677d-4a5d-8f2b-8ca7691b6b00)  
(KB2616310)  
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=989cca2d-cce1-4f52-b50e-43152693f240)  
(KB2616310)  
(Importante)
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
[**MS11-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[**MS11-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[**MS11-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-084)
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=08b27ce7-c32e-41e4-ad04-481c5eab17a7)  
(KB2601626)  
(Importante)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=f116824e-ea48-422d-b284-c9ffa7604bf5)  
(KB2616310)  
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=de5a74f2-2cc8-4677-b495-3a40fe3d6b9e)  
(KB2601626)  
(Importante)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=1af1b734-62c7-4e08-91c8-90b6d026da84)  
(KB2616310)  
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
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=6168bc67-3d59-450f-bd8a-02d61dabe16b)  
(KB2601626)  
(Importante)
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
[**MS11-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[**MS11-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[**MS11-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-084)
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
Nenhuma
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fc3fe87c-2493-431d-a904-dec9310f6042)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e08266d8-fffa-40bf-b8f6-10a65ee27524)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=2bd602cf-ae0d-4790-a5d0-6133fd7d01a0)  
(KB2601626)  
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
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=042c1a8f-834d-4eed-8a59-9e030ccc6d39)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4f2365ed-d50e-44d9-b859-1ec54d3b4d38)  
(Importante)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=783521ad-5c50-4194-a582-4e5a1c9999e7)  
(KB2601626)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
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
[**MS11-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[**MS11-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[**MS11-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-084)
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
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=79382bf2-d2cb-42ea-92dc-64f949353521)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f82dc413-668c-4ca8-a8c8-db74f05346bc)\*\*  
(Moderada)
</td>
<td style="border:1px solid black;">
[Active Directory e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=b5688923-3914-4f6c-8bc9-036fb4870cc6)\*  
(KB2601626)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=71ff3a89-d7ad-4dda-9e59-fab54b21bd5d)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=06ad5637-56a1-4478-aaa0-063e877503c9)\*\*  
(Moderada)
</td>
<td style="border:1px solid black;">
[Active Directory e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=51f47181-08f6-4de1-80e5-253355675965)\*  
(KB2601626)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b1c0cb05-c284-49b1-ae4f-92813fdf520f)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2de5de74-e643-4045-9c22-ff95b0dbcafc)  
(Moderada)
</td>
<td style="border:1px solid black;">
Não Aplicável
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
[**MS11-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[**MS11-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[**MS11-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-084)
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
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4ddb4c2a-bada-49b0-ad78-e07e7e11ced7)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2307fa93-8e45-4841-a5a9-7e89960712f9)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=b06f9f55-e3b2-4705-83d0-1b9f5de9d378)  
(KB2601626)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=156c1bd9-55bc-482c-874b-61998d1ef153)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64](http://www.microsoft.com/downloads/details.aspx?familyid=05eef5d7-acf6-46e4-abfc-dc83f0a7cae5)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64](http://www.microsoft.com/downloads/details.aspx?familyid=62603d18-1b21-400c-8eba-202193182960)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=790f1d99-96a5-438d-b433-895b692912ce)  
(KB2601626)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64](http://www.microsoft.com/downloads/details.aspx?familyid=5c7db930-5495-43f0-928c-d586ac9e80d0)  
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
[**MS11-083**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-083)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-085)
</td>
<td style="border:1px solid black;">
[**MS11-086**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-086)
</td>
<td style="border:1px solid black;">
[**MS11-084**](http://technet.microsoft.com/pt-br/security/bulletin/ms11-084)
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
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x-64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3f9f74a6-e984-4aab-837c-ef7286e7305f)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c9cf6a22-f9ab-427a-9b16-33c60baaabb5)\*\*  
(Baixa)
</td>
<td style="border:1px solid black;">
[Active Directory e Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=cc1e99af-fc67-400b-a82c-171f8c4d1ac9)\*  
(KB2601626)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5d810dae-5c52-4155-b5c2-163d27be6e78)\*\*\*  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b20bfcbd-a515-4074-b56e-b82539fe5bad)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=012777f5-51f2-4944-91af-a9c79b8081a1)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=395819e2-1028-44b7-ace4-ca754b1a7543)  
(Moderada)
</td>
</tr>
</table>

<p></p>

 
**Observaçõespara Windows Server 2008 e Windows Server 2008 R2**

**\*Instalação do núcleo do servidor afetada.** Esta atualização se aplica, com a mesma classificação de gravidade, às edições com suporte do Windows Server 2008 e do Windows Server 2008 R2, conforme indicado, independentemente de terem sido instalados ou não com a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**\*\*Instalação de Núcleo de Servidor afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

**\*\*\*Instalação Núcleo do Servidor não afetada.** A vulnerabilidade abordada por esta atualização não afeta as edições com suporte do Windows Server 2008 ou Windows Server 2008 R2, conforme indicado, quando instalada usando a opção de instalação Núcleo do Servidor, mesmo que os arquivos afetados por esta vulnerabilidade possam estar presentes no sistema. No entanto, esta atualização ainda será oferecida aos usuários com arquivos afetados porque os arquivos de atualização são mais novos (com números de versão mais altos) que os arquivos que estão atualmente no seu sistema. Para obter mais informações sobre esta opção de instalação, consulte os artigos da Technet Managing a Server Core Installation e [Servicing a Server Core Installation (em inglês).](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte Comparar opções de instalação de Núcleo do Servidor.

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o Centro de Gerenciamento de Atualização do Technet. O site TechNet Security Center fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://www.microsoft.com/brasil/security), onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

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

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199)
-   : Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)
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

-   Will Dorman, da CERT/CC, por relatar um problema descrito no boletim MS11-084
-   Ivan Sanchez, da EvilCode, por relatar um problema descrito no boletim MS11-085
-   Xavier Lassoie e Sébastien Godard, da Autosécurité, por relatar um problema descrito no boletim MS11-086

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site Ciclo de Vida do Suporte Microsoft.
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do Suporte de Segurança ou pelo 1-866-PCSAFETY, telefone 1-866-727-2338. As ligações para obter suporte associado a atualizações de segurança são gratuitas. Para obter mais informações sobre as opções de suporte disponíveis, consulte Ajuda e Suporte da Microsoft.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de Ajuda e Suporte Internacional.

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (8 de novembro de 2011): Resumo de boletins publicado.

*Built at 2014-04-18T01:50:00Z-07:00*
