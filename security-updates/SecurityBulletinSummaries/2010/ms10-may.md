---
TOCTitle: 'MS10-MAY'
Title: Resumo do Boletim de Segurança da Microsoft de maio 2010
ms:assetid: 'ms10-may'
ms:contentKeyID: 61233666
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms10-may(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de maio 2010
========================================================

Publicado: terça-feira, 11 de maio de 2010 | Atualizado: quarta-feira, 19 de maio de 2010

**Versão:** 1.2

Este resumo de boletins lista os boletins de segurança lançados em maio de 2010.

Com o lançamento dos boletins de maio de 2010, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 6 de maio de 2010. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 12 de maio de 2010, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de maio](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032427724&culture=en-us). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-030">MS10-030</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Outlook Express e no Windows Mail pode permitir a execução remota de código (978542)</strong><br />
<br />
Esta atualização de segurança resolve uma vulnerabilidade relatada em particular no Outlook Express, Windows Mail e Windows Live Mail. A vulnerabilidade poderá permitir a execução remota de código se um usuário visitar um servidor de email mal-intencionado. O invasor que explorar com êxito a vulnerabilidade poderá obter os mesmos direitos que o usuário local. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-031">MS10-031</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Microsoft Visual Basic for Applications pode permitir a execução remota de código (978213)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Visual Basic for Applications. A vulnerabilidade poderá permitir a execução remota de código se um aplicativo de host for aberto e transmitir um arquivo especialmente criado para o tempo de execução do Visual Basic for Applications. Se um usuário tiver feito logon com direitos administrativos, o invasor que explorar com êxito essa vulnerabilidade poderá ter o controle total do sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Visual Basic for Applications</td>
</tr>
</tbody>
</table>

<p></p>

  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas em ordem decrescente de nível de avaliação de exploração e depois de ID do CVE. Só são incluídas as vulnerabilidades com uma classificação de gravidade Crítica ou Importante nos boletins.
  
**Como devo usar a tabela?**  
  
Use esta tabela para conhecer a probabilidade de o código de exploração em funcionamento ser lançado em 30 dias contados do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Você deve revisar cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade a sua implantação. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| ID do Boletim                                                       | Título da vulnerabilidade                                                      | ID do CVE                                                                        | Avaliação do índice de exploração                                                                                | Principais observações                                                                                            |  
|---------------------------------------------------------------------|--------------------------------------------------------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|  
| [MS10-031](http://technet.microsoft.com/security/bulletin/ms10-031) | Vulnerabilidade de corrupção de memória de pilha VBE6.DLL                      | [CVE-2010-0815](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0815) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente | (Nenhum)                                                                                                          |  
| [MS10-030](http://technet.microsoft.com/security/bulletin/ms10-030) | Vulnerabilidade de estouro de número inteiro do Outlook Express e Windows Mail | [CVE-2010-0816](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0816) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente | A exploração no Windows Vista e em sistemas operacionais posteriores é menos provável devido a atenuações de heap |
  
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
</tr>
<tr>
<th colspan="2">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=661f5de3-a593-4961-8e8d-2777797eb5c5)  
(KB978542)  
(Crítica)  
[Microsoft Outlook Express 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=cda75174-b535-4559-a52d-b5ec3a1df349)  
(KB978542)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Windows XP (site em inglês)
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 e Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=99707c3d-a3cb-47da-b38e-8ae0227fd703)  
(KB978542)  
(Crítica)  
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=99707c3d-a3cb-47da-b38e-8ae0227fd703)<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=44bc97bb-6f76-4c96-af72-69daaea80fff)  
(KB978542)  
(Crítica)  
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=44bc97bb-6f76-4c96-af72-69daaea80fff)<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=eb9742fc-0934-4b38-9ec4-3597fc71ec00)  
(KB978542)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=5678515a-97ea-4e00-8700-d3f2fcdc0efc)  
(KB978542)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=60ef635b-cb6d-402f-b904-e69b519d797f)  
(KB978542)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="2">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows Vista Service Pack 1 e Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?familyid=a970c869-24fe-4ef4-b189-7a6bac2411f1)  
(KB978542)  
(Crítica)  
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=a970c869-24fe-4ef4-b189-7a6bac2411f1)<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?familyid=9a7853b5-4f9f-4467-9530-eea2efd504a5)  
(KB978542)  
(Crítica)  
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=9a7853b5-4f9f-4467-9530-eea2efd504a5)<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?familyid=5f77a640-247c-4ed2-9fca-4b7344f4dc7c)\*\*  
(KB978542)  
(Crítica)  
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=5f77a640-247c-4ed2-9fca-4b7344f4dc7c)\*\*<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x-64 e Windows Server 2008 para sistemas baseados em x-64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?familyid=b0eab011-5847-44e4-bc0d-5c5355e1e8d0)\*\*  
(KB978542)  
(Crítica)  
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=b0eab011-5847-44e4-bc0d-5c5355e1e8d0)\*\*<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Mail](http://www.microsoft.com/downloads/details.aspx?familyid=da01ae82-895e-4739-916f-a63b9095a076)  
(KB978542)  
(Crítica)  
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=da01ae82-895e-4739-916f-a63b9095a076)<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows 7 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=1f0c17be-ba4c-4a1c-b9c3-8ac368800947)<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=a70f15e1-512c-44ca-a308-928e237ac0ce)<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
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
Windows Server 2008 R2 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=e2e25c02-38ce-4868-a01a-39fc7d2a4150)\*\* <sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Live Mail](http://www.microsoft.com/downloads/details.aspx?familyid=53ed1055-b5ee-4fde-9550-f8b401916467)<sup>[1]</sup>
(KB978542)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observação para Windows Server 2008 e Windows Server 2008 R2**

**\*\*Instalação de Núcleo de Servidor não afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) e [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (em inglês) do MSDN. Observe que a opção de instalação do Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Observação para o boletim MS10-030**

<sup>[1]</sup>Windows Live Mail é um componente pronto para uso neste sistema operacional que deve ser instalado separadamente para que a vulnerabilidade exista.

#### Microsoft Office Suites e software

 
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
Microsoft Office Suites, sistemas e componentes
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-031**](http://technet.microsoft.com/security/bulletin/ms10-031)
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=72c23b0f-4e24-4334-bc8a-334adc8bc42b)<sup>[1]</sup>   
(KB976380)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f8eac9bc-8389-4ac8-8b29-9a8180d9fd34)<sup>[1]</sup>   
(KB976382)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office System 2007
</td>
<td style="border:1px solid black;">
[Sistema Microsoft Office 2007 Service Pack 1 e Sistema Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=160ad53e-6475-4550-90c2-444e4abea730)<sup>[1]</sup>   
(KB976321)  
(Importante)
</td>
</tr>
</table>

<p></p>

 
**Observações para o boletim MS10-031**

<sup>[1]</sup>Estas atualizações para o Microsoft Office aplicam-se a todos os Microsoft Office Suites com suporte e outros softwares Microsoft Office que contenham o componente Office compartilhado vulnerável. Isto inclui, sem limitação, versões com suporte do Microsoft Office Visio e Microsoft Office Project.

Consulte também outras categorias de software nesta seção, **Softwares afetados e locais de download**, para obter mais arquivos de atualização com o mesmo identificador de boletim. Este boletim abrange mais de uma categoria de software.

#### Software e ferramentas para desenvolvedor da Microsoft

 
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
Microsoft Visual Basic for Applications
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS10-031**](http://technet.microsoft.com/security/bulletin/ms10-031)
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
Microsoft Visual Basic for Applications
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic for Applications](http://www.microsoft.com/downloads/details.aspx?familyid=436a8a66-352e-44d1-a610-c825083ad24a)<sup>[1]</sup>
(KB974945)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK
</td>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK<sup>[2]</sup><sup>[3]</sup>
(Crítica)
</td>
</tr>
</table>

<p></p>

 
**Observações para o boletim MS10-031**

<sup>[1]</sup>Este pacote de atualização se aplica a versões suportadas do tempo de execução do Microsoft Visual Basic for Applications (Vbe6.dll) e está disponível apenas no Centro de Download da Microsoft.

<sup>[2]</sup>As versões com suporte do VBA SDK são Microsoft Visual Basic for Applications SDK 6.3, Microsoft Visual Basic for Applications SDK 6.4 e Microsoft Visual Basic for Applications SDK 6.5.

<sup>[3]</sup>A versão atualizada do Visual Basic for Applications SDK que aborda a vulnerabilidade descrita neste boletim está disponível para fornecedores de software independentes (ISVs) junto à [Summit Software Company](http://www.summsoft.com/).

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

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Microsoft Windows 2000 e posteriores, Office XP e posteriores, Exchange Server 2003 e SQL Server 2000 nos sistemas operacionais Microsoft Windows 2000 e posteriores.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários. O próximo lançamento do SMS, System Center Configuration Manager 2007, já está disponível; consulte também [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Para obter mais informações sobre como os administradores podem usar o SMS 2003 para instalar atualizações de segurança, consulte [Gerenciamento de Patches de Segurança do SMS 2003.](http://go.microsoft.com/fwlink/?linkid=22939) Usuários do SMS 2.0 também podem usar o Security Update Inventory Tool (SUIT) para ajudar a implantar atualizações de segurança. Para obter informações sobre o SMS, visite [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) (sites em inglês) para instalar essas atualizações.

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

-   Francis Provencher, do Protek Research Lab, por relatar um problema descrito no boletim MS10-030
-   [NSFocus Security Team](http://www.nsfocus.com/), por relatar um problema descrito no boletim MS10-031

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do [Suporte de Segurança](http://go.microsoft.com/fwlink/?linkid=21131) ou pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas. Para obter mais informações sobre as opções de suporte disponíveis, consulte [Ajuda e Suporte da Microsoft](http://support.microsoft.com/).
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (11 de maio de 2010): Resumo de boletins publicado.
-   V1.1 (12 de maio de 2010): Requisitos de reinicialização corrigidos para o boletim MS10-030.
-   V1.2 (19 de maio de 2010): Foram removidas referências incorretas do boletim MS10-030 ao Windows Mail quando instalado no Windows 7 e no Windows Server 2008 R2. Também foi adicionada uma observação ao software afetado do boletim MS10-031 a fim de esclarecer que as atualizações para o Microsoft Office aplicam-se a todos os Microsoft Office Suites com suporte e outros softwares Microsoft Office que contenham uma versão vulnerável da VBE6.dll.

*Built at 2014-04-18T01:50:00Z-07:00*
