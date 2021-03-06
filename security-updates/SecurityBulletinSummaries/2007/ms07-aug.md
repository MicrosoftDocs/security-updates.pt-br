---
TOCTitle: 'MS07-AUG'
Title: Resumo do Boletim de Segurança da Microsoft de agosto 2007
ms:assetid: 'ms07-aug'
ms:contentKeyID: 61233623
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms07-aug(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de agosto 2007
==========================================================

Publicado: terça-feira, 14 de agosto de 2007 | Atualizado: terça-feira, 24 de junho de 2008

**Versão:** 4.0

Este resumo de boletins lista os boletins de segurança lançados em agosto de 2007.

Com o lançamento dos boletins de agosto de 2007, este resumo de boletins substitui a notificação prévia de boletim lançada originalmente em 9 de agosto de 2007. Para obter mais informações sobre o serviço de notificação prévia de boletim, consulte [Notificação prévia do Boletim de Segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um Webcast para solucionar dúvidas dos clientes sobre esses boletins dia 15 de agosto de 2007, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de agosto](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344688&eventcategory=4&culture=en-us&countrycode=us). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações de alta prioridade que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

#### Sinopses

Os boletins de segurança deste mês são como se segue, em ordem de gravidade:

Crítica (6)
-----------

 
| Identificador do Boletim              | Boletim de segurança da Microsoft MS07-042                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no Microsoft XML Core Services pode permitir a execução remota de código (936227)**](http://technet.microsoft.com/security/bulletin/ms07-042)                                                                                                                                                                                                                                                                                                                                           |
| **Sinopse**                           | Esta atualização de segurança crítica elimina uma vulnerabilidade reportada em particular. Esta vulnerabilidade pode permitir a execução remota de código quando um usuário exibe uma página da Web especialmente criada usando o Internet Explorer. A vulnerabilidade pode ser explorada por meio de ataques no Microsoft XML Core Services. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Crítica](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                                                                                                                                                              |
| **Softwares afetados**                | **Windows, XML Core Services.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                   |

<p></p>
<p></p>
<p></p>


| Identificador do Boletim              | Boletim de segurança da Microsoft MS07-043                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade na automação OLE pode permitir a execução remota de código (921503)**](http://technet.microsoft.com/security/bulletin/ms07-043)                                                                                                                                                                                                                                                                                                            |
| **Sinopse**                           | Esta atualização de segurança crítica elimina uma vulnerabilidade reportada em particular. Esta vulnerabilidade pode permitir a execução remota de código caso um usuário tenha exibido uma página da Web especialmente criada. A vulnerabilidade pode ser explorada por meio de ataques no OLE. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Crítica](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização exigirá uma reinicialização.                                                                                                                                                                                                                                                                                                       |
| **Softwares afetados**                | **Windows, Visual Basic, Office para Mac**. Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                          |
<p></p>
<p></p>
<p></p>


| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-044                                                                                                                                                                                                                                                                                                                                                                                                                     |
|---------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no Microsoft Excel pode permitir a execução remota de código (940965)**](http://technet.microsoft.com/security/bulletin/ms07-044)                                                                                                                                                                                                                                                                                                           |
| **Sinopse**                           | Esta atualização de segurança elimina uma vulnerabilidade reportada em particular, além de outros problemas de segurança identificados durante a investigação. Essas vulnerabilidades podem permitir a execução remota de código quando um usuário abre um arquivo do Excel especialmente criado. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Crítica](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização não requererá reinicialização.                                                                                                                                                                                                                                                                                                      |
| **Softwares afetados**                | **Office**. Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                           |

<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-045                                                                                                                                                                                                                                                                                                                                                                              |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Atualização de segurança cumulativa para Internet Explorer (937143)**](http://technet.microsoft.com/security/bulletin/ms07-045)                                                                                                                                                                                                                                                                                      |
| **Sinopse**                           | Esta atualização de segurança crítica elimina três vulnerabilidades reportadas em particular. Essas vulnerabilidades podem permitir a execução remota de código quando um usuário exibe uma página da Web especialmente criada usando o Internet Explorer. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Crítica](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                 |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                               |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                                                                           |
| **Softwares afetados**                | **Windows, Internet Explorer**. Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                |
<p></p>
<p></p>
<p></p>


| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-046                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no GDI pode permitir a execução remota de código (938829)**](http://technet.microsoft.com/security/bulletin/ms07-046)                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Sinopse**                           | Esta atualização de segurança crítica elimina uma vulnerabilidade reportada em particular. Existe uma vulnerabilidade de execução remota de código no mecanismo de processamento de elementos gráficos no modo como administra imagens especialmente criadas. Um invasor pode explorar essa vulnerabilidade criando uma imagem específica que possa permitir a execução remota de código se o usuário abrir um anexo em email especialmente criado. O invasor que explorar com êxito essa vulnerabilidade poderá assumir o controle total de um sistema afetado. |
| **Classificação Máxima de Gravidade** | [Crítica](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Softwares afetados**                | **Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                                                                            |


<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-050                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade na VML (Vector Markup Language) pode permitir a execução remota de código (938127)**](http://go.microsoft.com/fwlink/?linkid=94737)                                                                                                                                                                                                                                                                                                                      |
| **Sinopse**                           | Esta atualização de segurança elimina uma vulnerabilidade reportada em particular na implementação de VML (Vector Markup Language) no Windows. Esta vulnerabilidade pode permitir a execução remota de código caso um usuário tenha exibido uma página da Web especialmente criada usando o Internet Explorer. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Crítica](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                                                                                                                               |
| **Softwares afetados**                | **Windows, Internet Explorer**. Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                    |

Importante (3)
--------------

 
| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-047                                                                                                                                                                                                                                                                                                                                                                     |
|---------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no Windows Media Player pode permitir a execução remota de código (936782)**](http://technet.microsoft.com/security/bulletin/ms07-047)                                                                                                                                                                                                                                                      |
| **Sinopse**                           | Esta importante atualização de segurança elimina duas vulnerabilidades relatadas em particular. Essas vulnerabilidades podem permitir a execução de código caso um usuário tenha exibido um arquivo especialmente criado no Windows Media Player. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Importante](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                     |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                      |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização não requererá reinicialização.                                                                                                                                                                                                                                                      |
| **Softwares afetados**                | **Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                          |

<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-048                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidades nos Gadgets do Windows podem permitir a execução remota de código (938123)**](http://technet.microsoft.com/security/bulletin/ms07-048)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Sinopse**                           | Esta importante atualização de segurança elimina duas vulnerabilidades reportadas em particular, além de outras vulnerabilidades identificadas durante a investigação. Essas vulnerabilidades podem permitir a um invasor remoto anônimo executar código com os privilégios de usuário conectado. Se um usuário assinar um RSS feed mal-intencionado no gadget de manchetes de feed ou adicionar um arquivo de contatos mal-intencionado ao gadget de contatos ou se um usuário clicar em um link mal-intencionado no gadget de Temperatura, um invasor potencialmente poderá executar código no sistema. Em todos os vetores de ataque, os usuários cujas contas tenham sido configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Importante](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Softwares afetados**                | **Windows** **Vista.** Para obter mais informações, consulte a seção Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
<p></p>
<p></p>
<p></p>


| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-049                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no Virtual PC e no Virtual Server pode permitir a elevação de privilégio (937986)**](http://technet.microsoft.com/security/bulletin/ms07-049)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Sinopse**                           | Esta importante atualização de segurança elimina uma vulnerabilidade reportada em particular. Esta é uma vulnerabilidade de elevação de privilégio. A vulnerabilidade no Microsoft Virtual PC e no Microsoft Virtual Server pode permitir a um usuário de sistema operacional convidado executar código no sistema hospedeiro ou em outros sistemas operacionais convidados. Somente usuários de sistema operacional convidado a quem tenham sido concedidas permissões administrativas para o sistema operacional convidado podem explorar esta vulnerabilidade. Os usuários de sistema operacional convidado a quem não tiverem sido concedidas permissões administrativas para o sistema operacional convidado não têm como explorar esta vulnerabilidade. |
| **Classificação Máxima de Gravidade** | [Importante](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Impacto da Vulnerabilidade**        | Elevação de privilégio                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização não requer reinicialização.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Softwares afetados**                | **Virtual PC, Virtual Server.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |

Softwares afetados e Locais de download
---------------------------------------

 
**Como devo usar a tabela?**  

Use esta tabela para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança é necessária. Se houver um programa ou um componente de software listado, o impacto da vulnerabilidade estará relacionado e também haverá um hiperlink para a atualização de software disponível.

**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.

#### Softwares afetados e locais de download dos boletins MS07-042 a MS07-046

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
<th style="border:1px solid black;" >
Detalhes        
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
[**MS07-042**](http://technet.microsoft.com/security/bulletin/ms07-042)
</td>
<td style="border:1px solid black;">
[**MS07-043**](http://technet.microsoft.com/security/bulletin/ms07-043)
</td>
<td style="border:1px solid black;">
[**MS07-044**](http://technet.microsoft.com/security/bulletin/ms07-044)
</td>
<td style="border:1px solid black;">
[**MS07-045**](http://technet.microsoft.com/security/bulletin/ms07-045)
</td>
<td style="border:1px solid black;">
[**MS07-046**](http://technet.microsoft.com/security/bulletin/ms07-046)
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
</tr>
<tr>
<th colspan="6">
Softwares do Windows afetados
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=5c35b6e8-732a-4451-b5d4-23ed63e6e792)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=8fc8340b-c2b3-4559-835c-caa00cf086b9)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=6e8de050-8589-4831-ae19-075c93509485)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=dc29475d-c0bb-4d35-8dd6-4ca1cac32315)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=b85bb583-dc61-4d37-b458-208f5bb07ece)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=3c81730a-981a-4649-b2d9-45144230d512)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=b85bb583-dc61-4d37-b458-208f5bb07ece)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=15d4d4fa-9bab-4da5-978e-f89c78c8086a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=5374583d-de68-4d65-bca8-598d6b98b8b3)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=15d4d4fa-9bab-4da5-978e-f89c78c8086a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=6608d722-3ef8-4085-b771-7b17bb0ba06e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=c3359f27-e03e-4a4f-b896-3bda39f69f7e)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=6608d722-3ef8-4085-b771-7b17bb0ba06e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows Server 2003 com SP1 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=fc04451a-0696-4a21-b2b6-f02d4e2c33bf)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=92822479-2060-4357-a340-ed096f180b2b)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=fc04451a-0696-4a21-b2b6-f02d4e2c33bf)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="6">
Componentes do sistema operacional Windows afetados
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 5.01 Service Pack 4 no Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=fcf9440f-bb36-4ed1-9b6b-74a4f055650b)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 Service Pack 1 quando instalado no Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=8db75461-4dca-43db-aa30-c7e67ce954ad)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 para Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=5d31d916-867f-4dbf-b8a4-c75ea83f4f51)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 para Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=b15b2442-d6da-41dd-a424-11c9893be595)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 para Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=f2f9fb69-0399-4df0-9f5b-8f42a130c581)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 para Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=d0bd886d-2c80-4dd7-82b7-1bd1f8d398cc)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 para Microsoft Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=bf41033a-d6f0-451e-9b69-4cbe2bb3f804)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 para Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=7a2b4395-eaba-45ec-8d0c-932ebcc3d344)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 para Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=cd7ed4d5-7790-41db-8b68-cfd59105ca36)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 para Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Baixa](http://www.microsoft.com/downloads/details.aspx?familyid=4f8daed8-9925-494d-b2f5-1e29f4040f6a)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 para Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Baixa](http://www.microsoft.com/downloads/details.aspx?familyid=34669ca2-46b0-4fbf-8fbd-ad7a13920103)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 para Microsoft Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Baixa](http://www.microsoft.com/downloads/details.aspx?familyid=5bd7bcbd-528a-4a16-a39a-a5ff5f69a2e2)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 no Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=9ae27b2f-aca4-4758-8ce4-a98f1ff6ba70)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 no Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=53497e53-d10c-43af-ad56-9f07739a5284)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) quando instalado no Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=245214ea-76f9-4755-8a14-a74232e20c1c)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) no Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=dea6a48f-fb00-43f3-a374-3220f9759c2d)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) no Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=b8862ca9-1203-4056-a257-29271838ac0d)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) no Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=12618ad0-aefd-4c9a-a769-4b14a7603d6e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) no Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=61bf00a9-aeea-431a-86d3-526a4a373bb7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) no Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=b0285dd7-bf66-4226-9948-26e8aae99046)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) no Windows Vista
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=c734d7de-5d87-4904-81c3-714db2cb8b0d)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) no Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=0a465d77-a737-4d26-82a1-570f9c788a8a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) no Windows XP Service Pack 2 e Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Windows Vista e Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Windows Server 2008 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Windows Server 2008 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) quando instalado no Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0  
(KB933579) quando instalado no Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) quando instalado no Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) quando instalado no Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) quando instalado no Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) quando instalado no Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) quando instalado no Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Moderada](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) no Windows Vista
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=14270529-3ae5-43bf-a471-722ab010d81e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) no Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=928da3d2-b0b9-447a-b37a-4350497fe563)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="6">
Softwares do Office afetados
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=082b98f7-9556-4f1f-823a-c41ddf5a7c9a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=91308769-2577-4f9f-8209-06f2c8c8a86f)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=b0130e9e-8845-4d79-aaa1-a21cc9388abe)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 com Microsoft XML Core Services 5.0 (KB936048)
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=a339cb7b-e08a-47f8-ac0b-df449191424a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer 2003
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=c4a87572-3128-44f7-8069-95535a78500a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer 2003 com Microsoft XML Core Services 5.0 (KB936048)
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=a339cb7b-e08a-47f8-ac0b-df449191424a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 para Mac
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/mac/downloads.aspx)
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/mac/downloads.aspx)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Office System com Microsoft XML Core Services 5.0 (KB936960)
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=7a97478a-832c-4a6b-b074-0e18b1e4ed33)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Server 2007 com Microsoft XML Core Services 5.0 (KB936056)
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=e875613b-2f32-4f28-a635-664a25c95c18)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server com Microsoft XML Core Services 5.0 (KB936056)
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=e875613b-2f32-4f28-a635-664a25c95c18)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="6">
Outro software afetado
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Basic 6.0 Service Pack 6 (KB924053)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=e1646fb0-29d5-4a6e-a8d2-304c4d7735b7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>

<p></p>

 
**Observações**

**<sup>[1]</sup>** Há uma atualização de segurança disponível para esse sistema operacional. Consulte o software ou o componente afetado na tabela e o boletim de segurança apropriado para obter mais detalhes. 

#### Softwares afetados e locais de download dos boletins MS07-047 a MS07-050

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
[**MS07-047**](http://go.microsoft.com/fwlink/?linkid=88628)
</td>
<td style="border:1px solid black;">
[**MS07-048**](http://go.microsoft.com/fwlink/?linkid=94465)
</td>
<td style="border:1px solid black;">
[**MS07-049**](http://go.microsoft.com/fwlink/?linkid=92734)
</td>
<td style="border:1px solid black;">
[**MS07-050**](http://go.microsoft.com/fwlink/?linkid=94737)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Classificação Máxima de Gravidade**
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="5">
Softwares do Windows afetados
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 com SP1 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=49a5bd84-da71-4529-b4d3-ac57dab59e01)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=24443f59-b908-480b-9b72-7094d4b5e128)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<th colspan="5">
Componentes do sistema operacional Windows afetados
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 5.01 Service Pack 4 no Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=31e63d6f-b6b7-41d7-8ae6-dd7fcf89d477)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 Service Pack 1 quando instalado no Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=7099d33a-0ef6-423f-824e-757482517612)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 para Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=4447d74f-09ea-4be0-9dae-c243ce657fb7)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 para Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=98ccd207-f4d0-4625-aeab-0ebf1643a5fd)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 para Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=463535aa-e04e-4a30-b3ab-8cd6d8cdd13c)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 para Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=9d4375d4-fb9b-4771-bd6f-e5d23eedbc6b)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 para Microsoft Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=c7be313b-3405-42e1-9e4b-0cb6bf3d2cb1)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 para Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=9f5da816-194c-478e-8a96-9421a0c52c9f)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 para Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=1c3168a9-d959-4137-868a-ec70da737c21)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 para Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=59884e97-4912-4a9a-8a31-8182ea2d24db)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 para Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=42060e27-de14-4d0c-92a0-138cb57fe2b5)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 para Microsoft Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=a536206e-9d1b-49a8-81a1-53d46f2de973)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 no Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=2dd908a4-6152-4976-aaaa-01f5f37c9143)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 no Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=592435bc-1d43-4544-bd8a-4a2d829dc1a1)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 7.1 no Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=9f46b1fc-ee7b-437f-9492-67d003711021)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Media Player 9 quando instalado no Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=bd4a6474-5fde-415e-840e-7d973cb71c95)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 9 no Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=bd4a6474-5fde-415e-840e-7d973cb71c95)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Media Player 10 quando instalado no Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=48f5a9d3-b859-4cb6-a68e-abde76a14782)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 10 no Windows XP Professional x64 Edition e no Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=949580be-cbb3-4271-8ca0-0ead7f2d8801)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Media Player 10 no Windows Server 2003 Service Pack 1 e no Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=8d9f1fdf-6d4c-44d4-9b5f-bdbe8ac28d7f)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 10 no Windows Server 2003 x64 Edition e no Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=2c04c7f2-728e-43bd-8574-26e411fcd129)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Media Player 11 quando instalado no Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=a690d042-1137-4aaf-bd0e-565ea04d1f2b)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 11 no Windows XP Professional X64 Edition e no Windows XP Professional X64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=bdc89f34-c1ff-46ab-b52d-c02d51c5c373)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Media Player 11 no Windows Vista
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=80e5167c-4f75-4ce3-8b15-2f50958deec8)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 11 no Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=bf30b714-d6e7-47ea-b79e-84c18370a661)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
Outro software afetado
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC 2004
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=cbdeaa50-7115-4673-97c4-10009f9c5c42)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2004 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=17ffe5a2-3551-4858-93b6-5e25af87d808)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 Standard Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=bc02ea6d-2884-4637-9894-3413a71329ee)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 Enterprise Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=da474b6f-9f0c-43f6-b432-050f7e76967d)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 Standard Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=43fa1327-8e5e-4c92-901f-1ff2a0a087b4)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 Enterprise Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=c2fc16c4-1fb0-4c09-b04a-684b40df8517)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC para Mac versão 6.1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/mac/downloads.aspx)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC para Mac versão 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/mac/downloads.aspx)
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>

<p></p>

 
**Observações**

**<sup>[1]</sup>** Há uma atualização de segurança disponível para esse sistema operacional. Consulte o software ou o componente afetado na tabela e o boletim de segurança apropriado para obter mais detalhes. 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://go.microsoft.com/fwlink/?linkid=85102), onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) e [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "patch\_de\_segurança". Por fim, as atualizações de segurança podem ser baixadas do Catálogo do Windows Update. Para obter mais informações sobre o Catálogo do Windows Update, consulte o [Artigo 323166 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/323166).

**Orientação para detecção e implantação**

A Microsoft está oferecendo uma orientação de detecção e implantação para as atualizações de segurança deste mês. Esta orientação também ajudará aos profissionais de TI a entender como eles podem usar as várias ferramentas para ajudar a implantar a atualização de segurança, tal como o Windows Update, Microsoft Update, Atualização do Office, as ferramentas MBSA (Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server (SMS), Extended Security Update Inventory Tool e a EST (Enterprise Update Scan Tool). Para obter mais informações, consulte o [Artigo 910723 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer e** **EST** **Update Scan Tool**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

Quando o MBSA 1.2.1 não tiver suporte para detectar uma atualização de segurança específica, a Microsoft lança uma versão da Enterprise Scan Tool (EST) para essa atualização de segurança. Para obter mais informações sobre a EST, visite [Enterprise Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Observação** Após 9 de outubro de 2007, o arquivo MSSecure.XML usado pelo MBSA 1.2.1 não será mais atualizado. Após esta data, nenhuma nova atualização de segurança será adicionada ao arquivo MSSecure.XML usado pelo MBSA 1.2.1 e nenhuma nova versão da Enterprise Scan Tool será lançada. Para obter mais informações, visite [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

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

-   A Microsoft lançou quatro atualizações de alta prioridade que **não são de segurança** no Microsoft Update (MU) e no WSUS (Windows Server Update Services).
-   Microsoft lançou duas atualizações de alta prioridade que **não são de segurança** para Windows no Windows Update (WU).

Observe que estas informações se referem **somente** a atualizações de alta prioridade que **não são de segurança** no Microsoft Update, Windows Update e Windows Server Update Services lançadas no mesmo dia que o resumo de boletins de segurança. **Não** serão fornecidas informações sobre atualizações que **não são de segurança** lançadas em outros dias.

#### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de Segurança para Gerenciamento de Patches](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "patch\_de\_segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [Artigo 913086 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (em inglês).

#### Agradecimentos

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) à pessoa citada abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   Um pesquisador anônimo que trabalha com o [VeriSign iDefense VCP](http://idefense.com/) por relatar um problema descrito no [MS07-042.](http://technet.microsoft.com/security/bulletin/ms07-042)
-   Um pesquisador anônimo que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) por reportar um problema descrito no [MS07-042](http://technet.microsoft.com/security/bulletin/ms07-042).
-   Um pesquisador anônimo que trabalha com o [VeriSign iDefense VCP](http://idefense.com/) por relatar um problema descrito no [MS07-043.](http://technet.microsoft.com/security/bulletin/ms07-043)
-   Um pesquisador anônimo que trabalha na [Zero Day Initiative](http://www.zerodayinitiative.com/) por reportar um problema descrito no [MS07-043](http://technet.microsoft.com/security/bulletin/ms07-043).
-   Dyon Balding, da [Secunia](http://secunia.com/), por relatar um problema descrito no boletim [MS07-044](http://technet.microsoft.com/security/bulletin/ms07-044).
-   [NSFocus Security Team](http://www.nsfocus.com/) por relatar um problema descrito no boletim [MS07-045](http://technet.microsoft.com/security/bulletin/ms07-045).
-   Brett Moore, da [Security-Assessment.com](http://www.security-assessment.com/) por relatar um problema descrito no [MS07-045](http://technet.microsoft.com/security/bulletin/ms07-045).
-   [eEye Digital Security](http://www.eeye.com/) por relatar um problema descrito no [MS07-046](http://technet.microsoft.com/security/bulletin/ms07-046).
-   Piotr Bania, que trabalha com a [TippingPoint](http://www.tippingpoint.com/) e a [Zero Day Initiative](http://www.zerodayintiative.com/), por relatar um problema descrito no boletim [MS07-047](http://go.microsoft.com/fwlink/?linkid=88628).
-   Aviv Raff, da [Finjan](http://www.finjan.com/), por relatar um problema descrito no boletim [MS07-048.](http://go.microsoft.com/fwlink/?linkid=94465)
-   Aviv Raff, que trabalha na [iDefense Labs](http://labs.idefense.com/), por relatar um problema descrito no boletim [MS07-048](http://go.microsoft.com/fwlink/?linkid=94465).
-   Rafal Wojtczuk, da [McAfee Avert Labs](http://www.avertlabs.com/), por trabalhar com a Microsoft em um problema descrito no boletim [MS07-049](http://go.microsoft.com/fwlink/?linkid=92734).
-   [eEye Digital Security](http://www.eeye.com/) por relatar um problema descrito no boletim [MS07-050](http://go.microsoft.com/fwlink/?linkid=94737).

#### Suporte

-   O software afetado listado foi testado a fim de determinar que versões são afetadas. Outras versões pasaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos EUA e Canadá podem receber suporte técnico dos [Serviços de suporte ao produto Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, conseqüenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos conseqüenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (14 de agosto de 2007): Resumo do boletim publicado.
-   V1.1 (29 de agosto de 2007): Tabela de software afetado atualizada para alterar o software do Office afetado no boletim MS07-044 de "Office 2000", "Office XP" e "Office 2003” para "Excel 2000", "Excel 2002" e "Excel 2003," respectivamente.
-   V1.0 (13 de novembro de 2007): A tabela Software afetados foi atualizada para incluir links de download para o boletim MS07-049. Uma atualização de segurança revisada já está disponível para instalação no Microsoft Virtual PC 2004, Microsoft Virtual PC 2004 Service Pack 1, Microsoft Virtual Server 2005 Standard Edition, Microsoft Virtual Server 2005 Enterprise Edition, Microsoft Virtual Server 2005 R2 Standard Edition, Microsoft Virtual Server 2005 R2 Enterprise Edition.
-   V3.0 (9 de janeiro de 2008) : A tabela de Softwares afetados foi atualizada para adicionar o Microsoft Word Viewer 2003 no MS07-042. A mesma atualização para Microsoft Office 2003 Service Pack 2 aplica-se ao Microsoft Word Viewer 2003.
-   V4.0 (24 de junho de 2008) : A tabela de Softwares afetados foi atualizada para adicionar Windows XP Service Pack 3, Windows Vista Service Pack 1, Windows Vista x64 Edition Service Pack 1, Windows Server 2008 para sistemas de 32 bits, Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados no Itanium no MS07-042 para a atualização do KB936181 para Microsoft XML Core Services 4.0. Isto é somente uma alteração de detecção. Não houve nenhuma alteração ao binário.

*Built at 2014-04-18T01:50:00Z-07:00*
