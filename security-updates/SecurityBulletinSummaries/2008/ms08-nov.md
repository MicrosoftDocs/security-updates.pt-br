---
TOCTitle: 'MS08-NOV'
Title: Resumo do Boletim de Segurança da Microsoft de novembro 2008
ms:assetid: 'ms08-nov'
ms:contentKeyID: 61233643
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms08-nov(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de novembro 2008
============================================================

Publicado: terça-feira, 11 de novembro de 2008 | Atualizado: terça-feira, 12 de julho de 2011

**Versão:** 4.0

Este resumo de boletins lista os boletins de segurança lançados em novembro de 2008.

Com o lançamento dos boletins de novembro de 2008, este resumo de boletins substitui a notificação antecipada de boletim lançada originalmente em 6 de novembro de 2008. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada do Boletim de Segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 12 de novembro de 2008, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de novembro.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374642) Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações de alta prioridade que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

#### Sinopses

Os boletins de segurança deste mês são como se segue, em ordem de gravidade:

Crítica (1)
-----------

 



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-069                                                                                                                                                                                                                                                                                                                                                                                          |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**Vulnerabilidades no Microsoft XML Core Services podem permitir a execução remota de código (955218)**](http://technet.microsoft.com/security/bulletin/ms08-069)                                                                                                                                                                                                                                                                  |
| **Sinopse**                           | Esta atualização de segurança resolve várias vulnerabilidades no Microsoft XML Core Services. A vulnerabilidade mais severa pode permitir a execução remota de código caso um usuário tenha exibido uma página da Web especialmente criada usando o Internet Explorer. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação máxima de gravidade** | [Crítica](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                            |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                                                                                       |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                     |

Importante (1)
--------------

 



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-068                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**Vulnerabilidade no SMB pode permitir a execução remota de código (957097)**](http://technet.microsoft.com/security/bulletin/ms08-068)                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Sinopse**                           | Esta atualização de segurança resolve uma vulnerabilidade relatada publicamente no protocolo SMB (Server Message Block) da Microsoft. A vulnerabilidade pode permitir a execução remota de código em sistemas afetados. Um invasor que explorar com êxito essa vulnerabilidade pode instalar programas; exibir, alterar ou excluir dados ou criar contas novas com direitos de usuário totais. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação máxima de gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                                                             |

Índice de exploração
--------------------

 
**Como devo usar a tabela?**  

Use esta tabela para conhecer a probabilidade de o código de exploração em funcionamento ser lançado em 30 dias contados do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Você deve revisar cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade a sua implantação. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Microsoft Exploitability Index](http://technet.microsoft.com/pt-br/security/cc998259.aspx).

| ID do Boletim                                                       | Título do Boletim                                                                                                                                              | ID do CVE                                                                        | Avaliação do índice de exploração                                                                            | Principais observações                                                                                                                   |
|---------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| [MS08-068](http://technet.microsoft.com/security/bulletin/ms08-068) | [Vulnerabilidade no SMB pode permitir a execução remota de código (957097)](http://technet.microsoft.com/security/bulletin/ms08-068)                           | [CVE-2008-4037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4037) | [1 - Possível código de exploração consistente](http://technet.microsoft.com/pt-br/security/cc998259.aspx)   | O código de exploração atualmente é público para essa vulnerabilidade no Windows XP.                                                     |
| [MS08-069](http://technet.microsoft.com/security/bulletin/ms08-069) | [Vulnerabilidades no Microsoft XML Core Services podem permitir a execução remota de código (955218)](http://technet.microsoft.com/security/bulletin/ms08-069) | [CVE-2008-4029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4029) | [1 - Possível código de exploração consistente](http://technet.microsoft.com/pt-br/security/cc998259.aspx)   | O código de exploração para a divulgação de informações é possível, pois isso pode ser usado nos ataques entre domínios.                 |
| [MS08-069](http://technet.microsoft.com/security/bulletin/ms08-069) | [Vulnerabilidades no Microsoft XML Core Services podem permitir a execução remota de código (955218)](http://technet.microsoft.com/security/bulletin/ms08-069) | [CVE-2007-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2007-0099) | [2 - Possível código de exploração inconsistente](http://technet.microsoft.com/pt-br/security/cc998259.aspx) | Esta vulnerabilidade envolve uma condição de corrida no carregamento de arquivos XML. Portanto, é difícil explorar de forma consistente. |
| [MS08-069](http://technet.microsoft.com/security/bulletin/ms08-069) | [Vulnerabilidades no Microsoft XML Core Services podem permitir a execução remota de código (955218)](http://technet.microsoft.com/security/bulletin/ms08-069) | [CVE-2008-4033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4033) | [2 - Possível código de exploração inconsistente](http://technet.microsoft.com/pt-br/security/cc998259.aspx) |                                                                                                                                          |

Softwares afetados e locais de download
---------------------------------------

 
**Como devo usar a tabela?**  

Use esta tabela para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança é necessária. Se um programa de software ou componente estiver listado, haverá também um hiperlink para a atualização de software disponível e a classificação de gravidade da atualização de software também estará listada.

**Observação** Talvez seja necessário instalar várias atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.

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
</tr>
<tr>
<th colspan="3">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=559cd4b6-24b7-4e60-8749-37d9b833d3eb)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=44c971e6-96fc-4bba-8f4a-f9d46bda2b6c)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Windows XP (site em inglês)
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.http//www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=7493fa37-2cbf-4d66-8690-d50d63da4096)  
(KB954459)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=1b79f220-ebfc-49c1-963b-58bbda21b6e7)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9501b33b-d639-43e7-ad5a-9e76ed66effd)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=0a0f8385-e908-4b5f-b9bf-80b7dabfcafd)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Baixa)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=57a0606d-ea7a-4e5b-8b8b-7b77a444ef75)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=347c8c83-4269-4a0e-af6f-4be2e824d22b)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Baixa)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=915e001f-9aa0-4fb0-9c2a-0f0c72b4f056)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=3a65e1cd-eb4e-44b6-8868-a5a84be2cb32)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Baixa)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=6abf7ba9-825f-4ee2-a2fe-6b1cd9fab622)  
(Importante)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista e Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=affbc957-1867-4bbe-924d-6f0696ae0895)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cb6c4315-8c6d-43af-978b-b190b1a1577a)  
(KB954459)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5612815f-8685-45d2-af4a-164c298a0869)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b01a5f31-8c57-4c5c-909e-b37caf0439b0)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=39443046-2093-4c87-ac7b-679deab96414)  
(KB954459)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=727ce9b6-827f-4350-b4ff-c08e8ac541a6)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=90a04164-4d02-4ce9-b3d8-bddb1ec27618)\*\*  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Baixa)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=dea9f227-967f-47c7-bb2a-ed68f13645d9)\*\*  
(KB954459)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=b305e894-61ec-46b4-91ee-4c9ac59bc47e)\*  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b7bfe3f4-835f-402c-95b5-6d49b6935308)\*\*  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Baixa)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f16e2a5f-37fd-4ee1-aef0-597214323dc4)\*\*  
(KB954459)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=e8d26dfd-b347-4f10-b5b6-27dfff5e4f47)\*  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4e0d1efe-70ac-459b-b330-c0149b74f520)  
(KB955069)  
(Crítica)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Baixa)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d4ae74e2-1b09-4a99-8cf5-8a8ca8ac6f7f)  
(KB954459)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d565467d-e10f-4ddc-a278-3f81a3798686)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
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
Windows 7 para sistemas de 32 bits e Windows 7 para sistemas de 32 bits Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas baseados em x-64 e Windows 7 para Sistemas Service Pack 1 baseados em x-64
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Baixa**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 e Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em Itanium e Windows Server 2008 R2 para sistemas Service Pack 1 baseados no Itanium
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**\*Instalação do núcleo do servidor afetada.** Esta atualização se aplica, com a mesma classificação de gravidade, às edições com suporte do Windows Server 2008 e do Windows Server 2008 R2, conforme indicado, independentemente de terem sido instalados ou não com a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) e [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (em inglês) do MSDN. Observe que a opção de instalação do Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Instalação de Núcleo de Servidor afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 ou Windows Server 2008 R2 com suporte, conforme indicado, quando ele for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre esta opção de instalação, consulte os artigos [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) e [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (em inglês) do MSDN. Observe que a opção de instalação do Núcleo do Servidor não se aplica a certas edições do Windows Server 2008 e Windows Server 2008 R2; consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
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
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3)  
(KB951535)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Sistema Microsoft Office 2007 e Sistema Microsoft Office 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(Importante)
</td>
</tr>
<tr>
<th colspan="2">
Outros softwares do Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
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
Microsoft Word Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3)  
(KB951535)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 e Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web e Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 e Microsoft Office SharePoint Server 2007 Service Pack 1 (edições de 32 bits)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=a208f2b5-2b0d-43bb-8f8a-58d4a3fc64f5)  
(KB951597)  
(Importante)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 e Microsoft Office SharePoint Server 2007 Service Pack 1 (edições de 64 bits)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c)  
(KB951597)  
(Importante)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c)  
(KB951597)  
(Importante)
</td>
</tr>
</table>

<p></p>

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://www.microsoft.com/fwlink/?linkid=69903). O site [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://www.microsoft.com/pt-br/security), onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) e [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://www.microsoft.com/downloads/search.aspx?displaylang=pt-br). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

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

**Avaliador de compatibilidade com atualizações e Kit de ferramentas de compatibilidade de aplicativos**

As atualizações frequentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) incluídos no [Kit de ferramentas de compatibilidade de aplicativos 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Application Compatibility Toolkit (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações de alta prioridade que não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Descrição dos serviços de atualização de software e de alterações nos serviços do Windows Server no conteúdo para 2008. Inclui todo o conteúdo do Windows.
-   [Atualizações novas, revisadas e liberadas para produtos da Microsoft que não sejam o Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Comunidade e estratégias de segurança

**Estratégias de gerenciamento de atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://www.microsoft.com/downloads/search.aspx?displaylang=pt-br). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [Artigo 913086 (em inglês) da Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (em inglês).

#### Agradecimentos

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) à pessoa citada abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   Gregory Fleischer por relatar um problema descrito no boletim MS08-069
-   Stefano Di Paola da [Minded Security](http://www.mindedsecurity.com/) por relatar um problema descrito no boletim MS08-069

#### Suporte

-   Os softwares afetados listados foram testados para determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos EUA e Canadá podem receber suporte técnico dos [Serviços de suporte ao produto Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (11 de novembro de 2008): Resumo do boletim publicado.
-   V2.0 (29 de abril de 2009): Microsoft XML Core Services 4.0 (KB954430) adicionado como software afetado às edições de 32 bits e baseadas em x-64 do Windows Vista Service Pack 2 e às edições de 32 bits, baseadas em x64 e baseadas no Itanium do Windows Server 2008 Service Pack 2 do MS08-069. Esta é apenas uma alteração de detecção; não houve nenhuma alteração aos binários. Os clientes que já instalaram a atualização KB954430 com êxito não necessitam reinstalá-la.
-   V3.0 (13 de outubro de 2009): Microsoft XML Core Services 4.0 (KB954430) adicionado como software afetado às edições de 32 bits e baseadas em x64 do Windows 7 e às edições baseadas em x64 e baseadas no Itanium do Windows Server 2008 R2 do MS08-069. Esta é apenas uma alteração de detecção; não houve nenhuma alteração aos binários. Os clientes que já instalaram a atualização KB954430 com êxito não necessitam reinstalá-la.
-   V4.0 (12 de julho de 2011): Foi adicionado o Microsoft XML Core Services 4.0 (KB954430) adicionado como software afetado às edições de 32 bits e baseadas em x64 do Windows 7 Service Pack 1 e às edições baseadas em x64 e baseadas no Itanium do Windows Server 2008 R2 Service Pack 1 do MS08-069. Esta é apenas uma alteração de detecção; não houve nenhuma alteração aos binários. Os clientes que já instalaram a atualização KB954430 com êxito não necessitam reinstalá-la.

*Built at 2014-04-18T01:50:00Z-07:00*
