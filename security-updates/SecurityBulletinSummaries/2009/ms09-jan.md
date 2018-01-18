---
TOCTitle: 'MS09-JAN'
Title: Resumo do Boletim de Segurança da Microsoft de janeiro 2009
ms:assetid: 'ms09-jan'
ms:contentKeyID: 61233650
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms09-jan(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de janeiro 2009
===========================================================

Publicado: terça-feira, 13 de janeiro de 2009

**Versão:** 1.0

Este resumo de boletins lista os boletins de segurança lançados em janeiro de 2009.

Com o lançamento dos boletins de janeiro de 2009, este resumo de boletins substitui a notificação antecipada de boletim lançada originalmente em 8 de janeiro de 2009. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada do Boletim de Segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 14 de janeiro de 2009, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de janeiro.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395120) Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-001">MS09-001</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no SMB podem permitir a execução remota de código (958687)</strong><br />
<br />
Esta atualização de segurança resolve várias vulnerabilidades reportadas em particular no protocolo SMB (Server Message Block) da Microsoft. As vulnerabilidades podem permitir a execução remota de código em sistemas afetados. Um invasor que explorar com êxito essas vulnerabilidades poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. As práticas recomendadas para firewall e as configurações de firewall padrão podem ajudar a proteger as redes contra ataques com origem externa ao perímetro da empresa. Essas práticas também recomendam que os sistemas conectados à Internet tenham um número mínimo de portas expostas.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
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
  
| ID do Boletim                                                       | Título do Boletim                                                           | ID do CVE                                                                        | Avaliação do índice de exploração                                                                                     | Principais observações                                                                                                                                                                                                                                                                                                                                                                                                                                                          |  
|---------------------------------------------------------------------|-----------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-001](http://technet.microsoft.com/security/bulletin/ms09-001) | Vulnerabilidades no SMB podem permitir a execução remota de código (958687) | [CVE-2008-4114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4114) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Esta vulnerabilidade não pode ser utilizada para execução remota de código. O código público da prova de conceito existe para utilização desta vulnerabilidade para negação remota de serviço.                                                                                                                                                                                                                                                                                  |  
| [MS09-001](http://technet.microsoft.com/security/bulletin/ms09-001) | Vulnerabilidades no SMB podem permitir a execução remota de código (958687) | [CVE-2008-4834](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4834) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Embora esta seja uma vulnerabilidade de execução remota de código, é pouco provável que haja código de exploração em funcionamento. Para obter mais informações, consulte [Prioritizing the deployment of the SMB bulletin (Priorizando a implantação do boletim do SMB)](http://blogs.technet.com/swi/archive/2009/01/09/ms09-001-prioritizing-the-deployment-of-the-smb-bulletin.aspx) (em inglês) no blog de pesquisa e defesa de vulnerabilidade de segurança da Microsoft. |  
| [MS09-001](http://technet.microsoft.com/security/bulletin/ms09-001) | Vulnerabilidades no SMB podem permitir a execução remota de código (958687) | [CVE-2008-4835](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4835) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Embora esta seja uma vulnerabilidade de execução remota de código, é pouco provável que haja código de exploração em funcionamento. Para obter mais informações, consulte [Prioritizing the deployment of the SMB bulletin (Priorizando a implantação do boletim do SMB)](http://blogs.technet.com/swi/archive/2009/01/09/ms09-001-prioritizing-the-deployment-of-the-smb-bulletin.aspx) (em inglês) no blog de pesquisa e defesa de vulnerabilidade de segurança da Microsoft. |
  
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
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
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
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=e0678d14-c1b5-457a-8222-8e7682760ed4)  
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
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
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
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=eeafcdc5-df39-4b29-b6f1-7d32b64761e1)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=26898401-f669-4542-ad93-199ed1fe9a2a)  
(Crítica)
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
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
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
Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=588ca8e8-38a9-47ed-9c41-09aaf1022e49)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ee59441c-1e8f-4425-ae8d-dec14e7f13fb)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=caec9321-fa5b-42f0-9f26-61f673fe6eef)  
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
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
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
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9179c463-c10a-452a-990f-b7e37cdd889b)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6b26952e-b59d-4b0f-a52d-025e45ecd233)  
(Moderada)
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
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
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
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=7245b411-7c9e-41e5-9841-4c586336086c)\*  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=a241eaad-95a0-442b-978f-f21a6f0c7db4)\*  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ab7c7015-20bb-4a0c-977a-969f4e2a5189)  
(Moderada)
</td>
</tr>
</table>

<p></p>

 
**Observações para o Windows Server 2008**

**\*Instalação do núcleo de servidor do Windows Server 2008 afetada.** Essa atualização se aplica às edições do Windows Server 2008 com suporte, com a mesma classificação de gravidade, se o Windows Server 2008 tiver sido instalado usando a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre essa opção de instalação, consulte [Núcleo do Servidor](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008. Consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://go.microsoft.com/fwlink/?linkid=85102), onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) e [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis em sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Freqüentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

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
-   [Atualizações novas, revisadas e liberadas para produtos da Microsoft que não sejam o Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

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

-   Um pesquisador anônimo que trabalha na [TippingPoint](http://www.tippingpoint.com/) e na [Zero Day Initiative](http://www.zerodayinitiative.com/) por reportar um problema descrito no boletim MS09-001
-   Um pesquisador anônimo que trabalha na [TippingPoint](http://www.tippingpoint.com/) e na [Zero Day Initiative](http://www.zerodayinitiative.com/) por reportar outro problema descrito no boletim MS09-001

#### Suporte

-   O software afetado listado foi testado a fim de determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos EUA e Canadá podem receber suporte técnico dos [Serviços de suporte ao produto Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, conseqüenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos conseqüenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (13 de janeiro de 2009): Resumo do boletim publicado.

*Built at 2014-04-18T01:50:00Z-07:00*
