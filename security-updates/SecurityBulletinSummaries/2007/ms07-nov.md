---
TOCTitle: 'MS07-NOV'
Title: Resumo do Boletim de Segurança da Microsoft de novembro 2007
ms:assetid: 'ms07-nov'
ms:contentKeyID: 61233631
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms07-nov(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de novembro 2007
============================================================

Publicado: terça-feira, 13 de novembro de 2007

**Versão:** 1.0

Este resumo do boletim lista boletins de segurança lançados para novembro de 2007.

Com o lançamento dos boletins de novembro de 2007, este resumo do boletim substitui a notificação prévia de boletim lançada originalmente em 8 de novembro de 2007. Para obter mais informações sobre o serviço de notificação prévia de boletim, consulte [Notificação prévia do Boletim de Segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 14 de novembro de 2007, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de novembro.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344694&eventcategory=4&culture=en-us&countrycode=us) Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações de alta prioridade que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

#### Sinopses

Os boletins de segurança deste mês são como se segue, em ordem de gravidade:

Crítica (1)
-----------

 


<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-061                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade na manipulação de URI do Windows pode permitir a execução remota de código (943521)**](http://technet.microsoft.com/security/bulletin/ms07-061)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Sinopse**                           | Essa atualização elimina uma vulnerabilidade divulgada publicamente. Existe uma vulnerabilidade de execução remota de código na forma como o Shell do Windows manipula URIs especialmente criados transmitidos a ele. Se o Shell do Windows não validou suficientemente esses URIs, um invasor pode explorar essa vulnerabilidade e executar um código arbitrário. A Microsoft só identificou as maneiras pelas quais essa vulnerabilidade pode ser explorada e que está presente nos sistemas que usam o Internet Explorer 7. No entanto, a vulnerabilidade existe em um arquivo do Windows, Shell32.dll, incluído em todas as edições com suporte do Windows XP e Windows Server 2003. |
| **Classificação Máxima de Gravidade** | [Crítica](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Softwares afetados**                | **Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

Importante (1)
--------------

 


<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-062                                                                                                                                                                                                                                                                                                                |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no DNS pode permitir falsificação (941672)**](http://technet.microsoft.com/security/bulletin/ms07-062)                                                                                                                                                                                                                                 |
| **Sinopse**                           | Esta atualização de segurança importante elimina uma vulnerabilidade reportada em particular. Essa vulnerabilidade de falsificação existe nos servidores DNS do Windows e pode permitir que um invasor envie respostas especialmente criadas para solicitações do DNS, falsificando ou redirecionando o tráfego de Internet a partir de locais legítimos. |
| **Classificação Máxima de Gravidade** | [Importante](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                |
| **Impacto da Vulnerabilidade**        | Falsificação                                                                                                                                                                                                                                                                                                                                              |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização não exigirá uma reinicialização, exceto em determinadas situações.                                                                                                                                                             |
| **Softwares afetados**                | **Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                     |

Softwares afetados e Locais de download
---------------------------------------

 
**Como devo usar a tabela?**  

Use esta tabela para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança é necessária. Se houver um programa ou um componente de software listado, o impacto da vulnerabilidade estará relacionado e também haverá um hiperlink para a atualização de software disponível.

**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.

**Softwares afetados e Locais de download**

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
Detalhes        
</th>
<th style="border:1px solid black;" >
Detalhes        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS07-061**](http://go.microsoft.com/fwlink/?linkid=103190)
</td>
<td style="border:1px solid black;">
[**MS07-062**](http://go.microsoft.com/fwlink/?linkid=99391)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Classificação Máxima de Gravidade**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="3">
Sistema operacional Windows
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Server Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=c80fcd9b-d0f8-44db-96fc-bf2ead054ff4)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=8ba1c2f9-1bde-4e97-b327-21259c5e5104)
</td>
<td style="border:1px solid black;">
 
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">
 
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b)
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b)
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 com SP1 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
</table>

<p></p>

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://go.microsoft.com/fwlink/?linkid=85102), onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) e [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis em sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Freqüentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

**Orientação para detecção e implantação**

A Microsoft está oferecendo uma orientação de detecção e implantação para as atualizações de segurança deste mês. Essa orientação também ajudará os profissionais de TI a entender como eles podem usar as várias ferramentas para ajudar a implantar a atualização de segurança, tal como o Windows Update, Microsoft Update, Atualização do Office, as ferramentas MBSA (Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server (SMS) e a Ferramenta Extended Security Update Inventory (ESUIT). Para obter mais informações, consulte o [artigo 910723 da Microsoft Knowledge Base](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Observação** Após 9 de outubro de 2007, o arquivo MSSecure.XML usado pelo MBSA 1.2.1 não será mais atualizado. Após esta data, nenhuma nova atualização de segurança será adicionada ao arquivo MSSecure.XML usado pelo MBSA 1.2.1 e nenhuma nova versão da Enterprise Scan Tool será lançada. Isso não afeta a Ferramenta Security Update Invetory Tool (SUIT) nem a Ferramenta (Extended Security Update Inventory Tool (ESUIT) para SMS 2.0 e SMS 2003. Para obter mais informações, consulte o [Microsoft Baseline Security Analyzer.](http://go.microsoft.com/fwlink/?linkid=21134)

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Windows 2000 e posterior, Office XP e superior, Exchange Server 2003, e SQL Server 2000 nos sistemas operacionais Windows 2000 e superior.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários. Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, visite [Gerenciamento de Patches de Segurança do SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939). Os usuários do SMS 2.0 também podem usar o [Software Updates Service Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) (em inglês) para ajudar a implantar atualizações de segurança. Para obter informações sobre o SMS, visite [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer e a ferramenta de detecção do Microsoft Office para fornecer amplo suporte à detecção e à implantação de atualizações do boletim de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para apontar as atualizações de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) e no [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) (sites em inglês) para instalar essas atualizações.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações de alta prioridade que não são de segurança no MU, WU e WSUS:

Durante este mês:

-   A Microsoft lançou três atualizações de alta prioridade que **não são de segurança** no Microsoft Update (MU) e no WSUS (Windows Server Update Services).
-   A Microsoft não lançou nenhuma atualização de alta prioridade que **não seja de segurança** para Windows no Windows Update (WU).

Observe que estas informações se referem **somente** a atualizações de alta prioridade que **não são de segurança** no Microsoft Update, Windows Update e Windows Server Update Services lançadas no mesmo dia que o resumo do boletim de segurança. **Não** serão fornecidas informações sobre atualizações que **não são de segurança** lançadas em outros dias.

#### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de Segurança para Gerenciamento de Patches](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [artigo 913086 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (em inglês).

#### Agradecimentos

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) à pessoa citada abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   Jesper Johansson por trabalhar conosco em um problema descrito no boletim MS07-061
-   Carsten H. Eiram da [Secunia](http://corporate.secunia.com/) por trabalhar conosco em um problema descrito no boletim MS07-061
-   Aviv Raff da [Finjan](http://www.finjan.com/) por trabalhar conosco em um problema descrito no boletim MS07-061
-   Petko Petkov da [GNUCITIZEN](http://www.gnucitizen.org/) por trabalhar conosco em um problema descrito no boletim MS07-061
-   Alla Berzroutchko da [Scanit](http://www.scanit.be/) por relatar um problema descrito no boletim MS07-062
-   Amit Klein da [Trusteer](http://www.trusteer.com/) por relatar um problema descrito no boletim MS07-062

#### Suporte

-   O software afetado listado foi testado a fim de determinar que versões são afetadas. Outras versões pasaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos EUA e Canadá podem receber suporte técnico dos [Serviços de suporte ao produto Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, conseqüenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos conseqüenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (13 de novembro de 2007): Resumo do boletim publicado.

*Built at 2014-04-18T01:50:00Z-07:00*
