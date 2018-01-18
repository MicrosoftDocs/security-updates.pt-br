---
TOCTitle: 'MS07-SEP'
Title: Resumo do Boletim de Segurança da Microsoft de setembro 2007
ms:assetid: 'ms07-sep'
ms:contentKeyID: 61233633
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms07-sep(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de setembro 2007
============================================================

Publicado: terça-feira, 11 de setembro de 2007

**Versão:** 1.0

Este resumo do boletim lista boletins de segurança lançados para setembro de 2007.

Com o lançamento dos boletins de setembro de 2007, este resumo do boletim substitui a notificação prévia de boletim lançada originalmente em 6 de setembro de 2007. Para obter mais informações sobre o serviço de notificação prévia de boletim, consulte [Notificação prévia do Boletim de Segurança da Microsoft](http://www.microsoft.com/brasil/technet/seguranca/bulletin/advance.mspx).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://www.microsoft.com/brasil/security/alertas.mspx).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 12 de setembro de 2007, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de setembro](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344690&eventcategory=4&culture=en-us&countrycode=us). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://www.microsoft.com/brasil/technet/seguranca/bulletin/summary.mspx)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações de alta prioridade que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

#### Sinopses

Os boletins de segurança deste mês são como se segue, em ordem de gravidade:

Crítica (1)
-----------

 


<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-051                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no Microsoft Agent pode permitir a execução remota de código (938827)**](http://technet.microsoft.com/security/bulletin/ms07-051)                                                                                                                                                                                                                                                                                                                                              |
| **Sinopse**                           | Esta atualização de segurança crítica elimina uma vulnerabilidade reportada em particular. Existe uma vulnerabilidade de execução remota de código no Microsoft Agent na forma como ele trata determinadas URLs especialmente criadas. A vulnerabilidade pode permitir que um invasor execute código remotamente no sistema afetado. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Crítica](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                                                                                                                                                     |
| **Softwares afetados**                | **Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                             |

Importante (3)
--------------

 


<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-052                                                                                                                                                                                                                                                                                                                                                 |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no Crystal Reports para Visual Studio pode permitir a execução remota de código (941522)**](http://technet.microsoft.com/security/bulletin/ms07-052)                                                                                                                                                                                                                    |
| **Sinopse**                           | Esta importante atualização de segurança elimina uma vulnerabilidade divulgada publicamente. Essa vulnerabilidade pode permitir a execução remota de código quando um usuário abre um arquivo RPT especialmente desenvolvido. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                  |
| **Detecção**                          | O Microsoft Baseline Security Analyzer e o Enterprise Scan Tool podem detectar se seu sistema de computador exige esta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                       |
| **Softwares afetados**                | **Visual Studio.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-053                                                                                                                                                                                                                                                                                                                          |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no Windows Services for UNIX pode permitir a elevação de privilégio (939778)**](http://technet.microsoft.com/security/bulletin/ms07-053)                                                                                                                                                                                                         |
| **Sinopse**                           | Esta importante atualização de segurança elimina uma vulnerabilidade informada publicamente. Existe uma vulnerabilidade no Windows Services for UNIX 3.0, no Windows Services for UNIX 3.5 e no Subsistema para Aplicativos Baseados em UNIX onde a execução de determinados arquivos binários setuid pode permitir que um invasor consiga elevar seus privilégios. |
| **Classificação Máxima de Gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                         |
| **Impacto da Vulnerabilidade**        | Elevação de privilégio                                                                                                                                                                                                                                                                                                                                              |
| **Detecção**                          | O Microsoft Baseline Security Analyzer e o Enterprise Scan Tool podem detectar se seu sistema de computador exige esta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                |
| **Softwares afetados**                | **Windows Services for UNIX, Subsistema para Aplicativos Baseados em UNIX.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                               |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS07-054                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do Boletim**                 | [**Vulnerabilidade no MSN Messenger e Windows Live Messenger pode permitir a execução remota de código (942099)**](http://technet.microsoft.com/security/bulletin/ms07-054)                                                                                                                                                                                                                                                                                                                                                             |
| **Sinopse**                           | Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente no MSN Messenger e Windows Live Messenger. A vulnerabilidade pode permitir a execução remota de código quando um usuário aceita um convite de conversa com vídeo de um invasor. O invasor que explorar com êxito essa vulnerabilidade poderá assumir o controle total do sistema afetado. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação Máxima de Gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Impacto da Vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Detecção**                          | Esses produtos fornecem mecanismos incorporados para detecção automática e implantação de atualizações. A atualização não requer reinicialização.                                                                                                                                                                                                                                                                                                                                                                                       |
| **Softwares afetados**                | **MSN Messenger, Windows Live Messenger.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                     |

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
[**MS07-051**](http://technet.microsoft.com/security/bulletin/ms07-051)
</td>
<td style="border:1px solid black;">
[**MS07-052**](http://technet.microsoft.com/security/bulletin/ms07-052)
</td>
<td style="border:1px solid black;">
[**MS07-053**](http://technet.microsoft.com/security/bulletin/ms07-053)
</td>
<td style="border:1px solid black;">
[**MS07-054**](http://go.microsoft.com/fwlink/?linkid=99364)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Classificação Máxima de Gravidade**
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
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<th colspan="5">
Sistema operacional Windows
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Crítica](http://www.microsoft.com/downloads/details.aspx?familyid=7cd248ed-d154-4dce-89ef-ceefd2700965)
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
Windows XP Service Pack 2
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
Windows Server 2003 Service Pack 1
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
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
Windows Server 2003 x64 Edition
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2
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
Windows Vista
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
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
<th colspan="5">
Componentes do sistema operacional Windows
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Services for UNIX 3.0 no Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Services for UNIX 3.5 no Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Services for UNIX 3.0 no Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Services for UNIX 3.5 no Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Services for UNIX 3.0 no Windows Server 2003 Service Pack 1 e no Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Services for UNIX 3.5 no Windows Server 2003 Service Pack 1 e no Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Subsistema para Aplicativos Baseados em UNIX no Windows Server 2003 Service Pack 1 e no Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=8ab5cc43-0b9c-45eb-aa51-47568ab6ce3f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Subsistema para Aplicativos Baseados em UNIX no Windows Server 2003 x64 Edition e no Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=1d21e3e8-b5f6-4044-9db6-054af836492b)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Subsistema para Aplicativos Baseados em UNIX no Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=4d52e4f4-2888-42df-8163-85c648e65b29)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Subsistema para Aplicativos Baseados em UNIX no Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=4be667cc-c239-480b-a9a0-939bcd27f0de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
Plataformas e ferramentas de desenvolvimento
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2002 Service Pack 1  
(KB937057)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=2608c83b-e1b2-4449-9a0e-1e566aac3d76)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio .NET 2003  
(KB937058)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=d612ad41-5a0d-4e13-99ea-d6a5589786d6)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2003 Service Pack 1  
(KB937059)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=0b10b04b-932c-4bff-9cbc-b3eeb15064b1)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio 2005  
(KB937060)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=21073cc2-919c-40df-8ebb-aa3db06050d2)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio 2005 Service Pack 1  
(KB937061)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Importante](http://www.microsoft.com/downloads/details.aspx?familyid=967d43c8-efba-4221-beb0-981e7deef33a)**<sup>[2]</sup>**
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
MSN Messenger 6.2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
MSN Messenger 7.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
MSN Messenger 7.5
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
MSN Messenger 8.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[3]</sup>**
</td>
</tr>
</table>

<p></p>

 
**Observações**

**<sup>[1]</sup>** Há uma atualização de segurança disponível para esse sistema operacional. Consulte o software ou o componente afetado na tabela e o boletim de segurança apropriado para obter mais detalhes. 

**<sup>[2]</sup>** Nem todas as edições desta versão do Visual Studio são afetadas. Consulte o boletim de segurança adequado para obter uma lista específica de edições afetadas. 

**<sup>[3]</sup>** Há uma atualização disponível para esse software. Consulte o software ou o componente afetado na tabela e o boletim de segurança apropriado para obter mais detalhes. 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de Segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://go.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://www.microsoft.com/brasil/security/guidance) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://go.microsoft.com/fwlink/?linkid=85102), onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) e [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "patch\_de\_segurança". Por fim, as atualizações de segurança podem ser baixadas do Catálogo do Windows Update. Para obter mais informações sobre o Catálogo do Windows Update, consulte o [artigo 323166 (em inglês) da Base de Conhecimento Microsoft](http://support.microsoft.com/kb/323166).

**Orientação para detecção e implantação**

A Microsoft está oferecendo uma orientação de detecção e implantação para as atualizações de segurança deste mês. Esta orientação também ajudará aos profissionais de TI a entender como eles podem usar as várias ferramentas para ajudar a implantar a atualização de segurança, tal como o Windows Update, Microsoft Update, Atualização do Office, as ferramentas MBSA (Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server (SMS), Extended Security Update Inventory Tool e a EST (Enterprise Update Scan Tool). Para obter mais informações, consulte o [artigo 910723 da Base de Conhecimento Microsoft](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer e** **EST** **Update Scan Tool**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite [Microsoft Baseline Security Analyzer](http://www.microsoft.com/brasil/technet/seguranca/mbsa/).

Quando o MBSA 1.2.1 não tiver suporte para detectar uma atualização de segurança específica, a Microsoft lança uma versão da Enterprise Scan Tool (EST) para essa atualização de segurança. Para obter mais informações sobre a EST, visite [Enterprise Scan Tool](http://support.microsoft.com/kb/894193/pt-br).

**Observação** Após 9 de outubro de 2007, o arquivo MSSecure.XML usado pelo MBSA 1.2.1 não será mais atualizado. Após esta data, nenhuma nova atualização de segurança será adicionada ao arquivo MSSecure.XML usado pelo MBSA 1.2.1 e nenhuma nova versão da Enterprise Scan Tool será lançada. Para obter mais informações, visite [Microsoft Baseline Security Analyzer](http://www.microsoft.com/brasil/technet/seguranca/mbsa/).

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Windows 2000 e posterior, Office XP e superior, Exchange Server 2003, e SQL Server 2000 nos sistemas operacionais Windows 2000 e superior.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://www.microsoft.com/brasil/technet/seguranca/wsus/default.mspx).

**Systems Management Server**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários. Para obter mais informações sobre como os administradores podem usar o SMS 2003 para implantar atualizações de segurança, visite [Gerenciamento de Patches de Segurança do SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939). Os usuários do SMS 2.0 também podem usar o [Software Updates Service Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) (em inglês) para ajudar a implantar atualizações de segurança. Para obter informações sobre o SMS, visite [Microsoft Systems Management Server](http://www.microsoft.com/brasil/sms).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer e a ferramenta de detecção do Microsoft Office para fornecer amplo suporte à detecção e à implantação de atualizações do boletim de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para apontar as atualizações de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) e no [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) (sites em inglês) para instalar essas atualizações.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações de alta prioridade que não são de segurança no MU, WU e WSUS:

Durante este mês:

-   A Microsoft não lançou nenhuma atualização de alta prioridade que **não seja de segurança** no Microsoft Update (MU) e no Windows Server Update Services (WSUS).
-   A Microsoft não lançou nenhuma atualização de alta prioridade que **não seja de segurança** para Windows no Windows Update (WU).

Observe que estas informações se referem **somente** a atualizações de alta prioridade que **não são de segurança** no Microsoft Update, Windows Update e Windows Server Update Services lançadas no mesmo dia que o resumo do boletim de segurança. **Não** serão fornecidas informações sobre atualizações que **não são de segurança** lançadas em outros dias.

#### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de Segurança para Gerenciamento de Patches](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "patch\_de\_segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [artigo 913086 (em inglês) da Base de Conhecimento Microsoft](http://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://www.microsoft.com/brasil/technet/seguranca) (em inglês).

#### Agradecimentos

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) à pessoa citada abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   A equipe de Pesquisa de vulnerabilidade da [Assurent Secure Technologies](http://www.assurent.com/), por relatar um problema descrito no boletim [MS07-051](http://technet.microsoft.com/security/bulletin/ms07-051)
-   Yamata Li, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar um problema descrito no boletim [MS07-051](http://technet.microsoft.com/security/bulletin/ms07-051)
-   Um pesquisador anônimo que trabalha com o [iDefense VCP](http://labs.idefense.com/), por relatar um problema descrito no boletim [MS07-051](http://technet.microsoft.com/security/bulletin/ms07-051)
-   Brian A. Reiter, da WolfeReiter, por trabalhar conosco em um problema relatado no boletim [MS07-053](http://technet.microsoft.com/security/bulletin/ms07-053)
-   Woo Shi, da [team 509](http://www.team509.com/), por relatar um problema descrito no boletim [MS07-054](http://go.microsoft.com/fwlink/?linkid=99364)

#### Suporte

-   O software afetado listado foi testado a fim de determinar que versões são afetadas. Outras versões pasaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos EUA e Canadá podem receber suporte técnico dos [Serviços de suporte ao produto Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Conhecimento Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, conseqüenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos conseqüenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (11 de setembro de 2007): Resumo do boletim publicado.

*Built at 2014-04-18T01:50:00Z-07:00*
