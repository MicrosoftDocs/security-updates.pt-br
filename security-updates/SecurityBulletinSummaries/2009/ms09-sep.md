---
TOCTitle: 'MS09-SEP'
Title: Resumo do Boletim de Segurança da Microsoft de setembro 2009
ms:assetid: 'ms09-sep'
ms:contentKeyID: 61233657
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms09-sep(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de setembro 2009
============================================================

Publicado: terça-feira, 8 de setembro de 2009 | Atualizado: terça-feira, 10 de novembro de 2009

**Versão:** 3.0

Este resumo de boletins lista os boletins de segurança lançados em setembro de 2009.

Com o lançamento dos boletins de setembro de 2009, este resumo de boletins substitui a notificação antecipada de boletins lançada originalmente em 3 de setembro de 2009. Para obter mais informações sobre o serviço de notificação antecipada de boletins, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 9 de setembro de 2009, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de setembro](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407486&eventcategory=4&culture=en-us&countrycode=us). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-045">MS09-045</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no mecanismo de script JScript pode permitir execução remota de código (971961)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no mecanismo de script JScript, que pode permitir a execução remota de código se um usuário abrir um arquivo especialmente criado ou visitar um site especialmente criado e chamar um script malformado. Se um usuário tiver feito logon com direitos administrativos, o invasor que explorar com êxito essa vulnerabilidade poderá ter o controle total do sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-049">MS09-049</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Serviço de Configuração Automática de LAN Sem Fio pode permitir execução remota de código (970710)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Serviço de Configuração Automática de Rede Sem Fio. A vulnerabilidade pode permitir a execução remota de código se um cliente ou servidor com uma interface de rede sem fio habilitada receber quadros sem fio especialmente criados. Os sistemas sem uma placa sem fio habilitada não correm risco com esta vulnerabilidade.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-047">MS09-047</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Windows Media Format podem permitir a execução remota de código (973812)</strong><br />
<br />
Esta atualização de segurança elimina duas vulnerabilidades relatadas em particular no Windows Media Format. Essa vulnerabilidade pode permitir a execução remota de código se o usuário abrir um arquivo de mídia especialmente criado. Se um usuário tiver feito logon com direitos administrativos, o invasor que explorar com êxito essa vulnerabilidade poderá ter o controle total do sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-048">MS09-048</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Windows TCP/IP podem permitir a execução remota de código (967723)</strong><br />
<br />
Esta atualização de segurança resolve várias vulnerabilidades relatadas em particular no processamento do protocolo TCP/IP. As vulnerabilidades podem permitir a execução remota de código se um invasor enviar pacotes TCP/IP especialmente criados a um computador com um serviço de escuta pela rede. As práticas recomendadas para firewall e as configurações de firewall padrão podem ajudar a proteger as redes contra ataques com origem externa ao perímetro da empresa. Essas práticas também recomendam que os sistemas conectados à Internet tenham um número mínimo de portas expostas.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-046">MS09-046</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no controle ActiveX do componente de edição DHTML pode permitir a execução remota de código (956844)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no controle ActiveX do componente de edição DHTML. Um invasor pode explorar a vulnerabilidade criando uma página da Web especialmente desenvolvida. Se um usuário exibir a página da Web, a vulnerabilidade poderá permitir a execução remota de código. O invasor que explorar com êxito a vulnerabilidade poderá obter os mesmos direitos que o usuário conectado. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a><br />
Execução Remota de Código</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
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
  
| ID do Boletim                                                       | Título do Boletim                                                                                                      | ID do CVE                                                                        | Avaliação do índice de exploração                                                                                     | Principais observações                                                                                                                   |  
|---------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-045](http://technet.microsoft.com/security/bulletin/ms09-045) | Vulnerabilidade no mecanismo de script JScript pode permitir execução remota de código (971961)                        | [CVE-2009-1920](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1920) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                 |  
| [MS09-046](http://technet.microsoft.com/security/bulletin/ms09-046) | Vulnerabilidade no controle ActiveX do componente de edição DHTML pode permitir a execução remota de código (956844)   | [CVE-2009-2519](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2519) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | (Nenhum)                                                                                                                                 |  
| [MS09-047](http://technet.microsoft.com/security/bulletin/ms09-047) | Vulnerabilidades no Windows Media Format podem permitir a execução remota de código (973812)                           | [CVE-2009-2498](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2498) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                 |  
| [MS09-047](http://technet.microsoft.com/security/bulletin/ms09-047) | Vulnerabilidades no Windows Media Format podem permitir a execução remota de código (973812)                           | [CVE-2009-2499](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2499) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração consistente        | (Nenhum)                                                                                                                                 |  
| [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) | Vulnerabilidades no Windows TCP/IP podem permitir a execução remota de código (967723)                                 | [CVE-2008-4609](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4609) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Esse é um tipo de negação de serviço de consumo de memória.                                                                              |  
| [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) | Vulnerabilidades no Windows TCP/IP podem permitir a execução remota de código (967723)                                 | [CVE-2009-1925](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1925) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | O funcionamento do código de exploração é possível, mas provavelmente não é confiável. A negação de serviço é o resultado mais possível. |  
| [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) | Vulnerabilidades no Windows TCP/IP podem permitir a execução remota de código (967723)                                 | [CVE-2009-1926](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1926) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Código de exploração em funcionamento improvável | Esse é um tipo de negação de serviço de consumo de memória.                                                                              |  
| [MS09-049](http://technet.microsoft.com/security/bulletin/ms09-049) | Vulnerabilidade no Serviço de Configuração Automática de Rede Sem Fio pode permitir execução remota de código (970710) | [CVE-2009-1132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1132) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Possível código de exploração inconsistente      | As proteções de heap dificultam a exploração confiável desta vulnerabilidade.                                                            |
  
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
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
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
Nenhuma
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Importante**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[JScript 5.1 e JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=2bb3af8d-f36c-4497-9f48-fc59bcff2583)  
(KB971961)  
(Crítica)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=b2773db5-b17d-4b98-b4e2-219b23854abd)  
(KB975542)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Tempo de Execução do Windows Media Format 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=02b9dc42-38c2-44b1-a77c-34854f4a86c4)  
(KB968816)  
(Crítica)
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4<sup>[3]</sup>
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=6dd4b0f8-6b54-49a6-a6df-9420f9fd3333)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="6">
Windows XP (site em inglês)
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Baixa**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[JScript 5.6 no Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0af373b2-2240-4079-a748-a38d1bc06f39)  
(KB971961)  
(Crítica)  
[JScript 5.7 no Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a)<sup>[1]</sup>
(KB971961)  
(Crítica)  
[JScript 5.7 no Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a)  
(KB971961)  
(Crítica)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=992602d8-d857-41cf-b7b1-527afdc1dc0f)<sup>[2]</sup>
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Tempo de Execução do Windows Media Format 9.0, Tempo de Execução do Windows Media Format 9.5 e Tempo de Execução do Windows Media Format 11](http://www.microsoft.com/downloads/details.aspx?familyid=6ffc081e-f892-4818-acb9-6d79e15d473c)  
(KB968816)  
(Crítica)  
(Windows XP Service Pack 2 somente)  
[Tempo de Execução do Windows Media Format 9.0, Tempo de Execução do Windows Media Format 9.5 e Tempo de Execução do Windows Media Format 11](http://www.microsoft.com/downloads/details.aspx?familyid=31585f5a-9aaa-40da-b15a-11284b4b800c)  
(KB968816)  
(Crítica)  
(Windows XP Service Pack 3 somente)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 2 e Windows XP Service Pack 3<sup>[3]</sup>
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8523d5be-88a2-4124-9b02-660f612e2a12)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=0d671004-da4e-4dbd-a066-861b53b0c59c)  
(KB971961)  
(Crítica)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=9aae426d-ee9a-4736-b0a2-e0f8890a6895)<sup>[1]</sup>
(KB971961)  
(Crítica)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=00bae02a-64eb-4b91-965f-da2dc987a2ff)<sup>[2]</sup>
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Tempo de Execução do Windows Media Format 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=3780d565-d027-4f54-8fc0-05f5c3c6ba1a)  
(KB968816)  
(Crítica)  
[Tempo de Execução do Windows Media Format 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ce515188-db3c-4694-85da-177c8f76b68c)  
(KB968816)  
(Crítica)  
[Tempo de Execução do Windows Media Format 11](http://www.microsoft.com/downloads/details.aspx?familyid=9a465f92-3067-4a5a-9882-1fc2cf796c99)  
(KB968816)  
(Crítica)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2<sup>[3]</sup>
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dbc33f6b-61bf-409a-89b5-60002192e0e0)  
(Crítica)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=6acc9d2d-b71f-4b5c-9aea-b217b6ae240b)  
(KB971961)  
(Crítica)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=6af5d034-fd89-42e2-bc18-d44b7a6b0a85)<sup>[1]</sup>
(KB971961)  
(Crítica)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ecf9f7e2-3104-4de2-8b3d-99dcdcae6e62)<sup>[2]</sup>
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Tempo de Execução do Windows Media Format 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=4ab34e3d-34cb-4e35-a2da-b348ace8a8f7)  
(KB968816)  
(Crítica)  
[Windows Media Services 9.1](http://www.microsoft.com/downloads/details.aspx?familyid=61cd0581-c36e-4da6-ae95-41609adbe922)  
(KB972554)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48d82036-2fde-4bb0-a60e-92eed83ddc3f)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7478f73f-dd20-4cfa-a650-4c84f37ada2f)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=d0de3ab1-73e9-4a09-841f-81ade41a8c81)  
(KB971961)  
(Crítica)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=8f48bc05-ffac-4a21-8d21-dd20355cda8a)<sup>[1]</sup>
(KB971961)  
(Crítica)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=643f9e2f-2e5b-48dd-b1a0-22ccb633ed18)<sup>[2]</sup>
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Tempo de Execução do Windows Media Format 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=8654ee33-6083-447f-ae5b-43ef8d8b613d)  
(KB968816)  
(Crítica)  
[Tempo de Execução do Windows Media Format 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ce515188-db3c-4694-85da-177c8f76b68c)  
(KB968816)  
(Crítica)  
[Windows Media Services 9.1](http://www.microsoft.com/downloads/details.aspx?familyid=67c46f26-e6df-4ba2-9c03-1590b31e454c)  
(KB972554)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0298ddf-026e-4137-8197-ed9d9b889825)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=88bf502d-1a7c-447a-ac4c-401e1698669b)  
(Moderada)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=e78cf021-54f5-4526-b5f0-f781aebf9d72)  
(KB971961)  
(Crítica)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=fb1ca290-cea4-49c0-a37e-613a654bff3c)<sup>[1]</sup>
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=c948c4d8-5788-4c1a-9fb6-a969b06a888d)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=8d881ff8-f51f-4476-8cb6-2bebd5b2047f)  
(Moderada)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=bcb12e57-f5d6-4b4e-88ab-13c28137f11a)  
(KB971961)  
(Crítica)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=80e7390f-df39-4d99-b2e1-01c7f6a951bb)<sup>[2]</sup>
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e9fe967f-d78d-43c2-bbcc-5098bd20267e)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Tempo de Execução do Windows Media Format 11 e Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=d2bdefcc-f6b9-47c3-a55d-a4f33f967828)  
(KB968816)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 e Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d72f845-9feb-4685-a669-f9d6ab54f9ed)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=8b1b76d5-a6b0-4c2f-8768-e55e82c2c118)  
(KB971961)  
(Crítica)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=24457cdd-1973-40c9-9c2d-c1a75fdfa7fa)<sup>[2]</sup>
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f93470bd-2e6d-4340-88c6-bb212baf750a)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Tempo de Execução do Windows Media Format 11 e Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=97f00b25-fb8f-4300-80c0-c63179f32182)  
(KB968816)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 e Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b2930ff1-5f0a-4a5d-bf2a-9fb76dd8da63)  
(Crítica)
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
<tr>
<td style="border:1px solid black;">
**Identificador do Boletim**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
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
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nenhuma
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=df88e6e5-78d3-4fa6-858d-b935d812cada)\*  
(KB971961)  
(Crítica)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=e7b07be6-a4f8-4847-9c55-9b3d2965fa77)\* <sup>[2]</sup>
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ac3f6800-bc3e-4b35-a482-54e1a2da1ab5)\*\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Tempo de Execução do Windows Media Format 11 e Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=9c111bff-aff6-4ff7-81f6-e736cfcbe3ed)\*\*  
(KB968816)  
(Crítica)  
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=2801f69b-37d0-4d0f-9632-31382b824d36)\*  
(KB972554)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits e Windows Server 2008 para sistemas de 32 bits Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=35c1d5a9-a953-4fc6-90c0-d2358c7b89e6)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x-64 e Windows Server 2008 para sistemas baseados em x-64 Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=f584f8ca-f6b1-4285-a44c-3df5e51e75de)\*  
(KB971961)  
(Crítica)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=9eddbb89-4178-49c2-836a-2d292fe50936)\* <sup>[2]</sup>
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d1b9b4f-bf35-44aa-a660-afb2ef2c9e30)\*\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Tempo de Execução do Windows Media Format 11 e Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=59615c8b-a07f-4326-836d-f17b2fcc4695)\*\*  
(KB968816)  
(Crítica)  
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=7fad3793-174f-46db-9d0a-873a0ea8be65)\*  
(KB972554)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64 e Windows Server 2008 para sistemas baseados em x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e46822e-f79d-492d-ad01-ee680ad324f5)\*  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=b84fca1d-914d-45af-a48c-d9bc5d20c6b7)  
(KB971961)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium e Windows Server 2008 para sistemas baseados no Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ac76ee2-b1b6-4300-9cba-af33d9dd54eb)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**Observações para o Windows Server 2008**

**\*Instalação do núcleo de servidor do Windows Server 2008 afetada.** Essa atualização se aplica às edições do Windows Server 2008 com suporte, com a mesma classificação de gravidade, se o Windows Server 2008 tiver sido instalado usando a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre essa opção de instalação, consulte [Núcleo do Servidor](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008. Consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Instalação do núcleo de servidor do Windows Server 2008 não afetada.** As vulnerabilidades abordadas por esta atualização não afetam as edições do Windows Server 2008 com suporte se o Windows Server 2008 for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre essa opção de instalação, consulte [Núcleo do Servidor](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008. Consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Observações para o boletim MS09-045**

<sup>[1]</sup>Em sistemas com Internet Explorer 7 instalado

<sup>[2]</sup>Em sistemas com Internet Explorer 8 instalado

**Observação para o boletim MS09-048**

<sup>[3]</sup> Nenhuma atualização disponível. Para obter mais informações, consulte a entrada **Perguntas frequentes relacionadas a esta atualização de segurança** no boletim [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048).

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

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Windows 2000 e posterior, Office XP e superior, Exchange Server 2003, e SQL Server 2000 nos sistemas operacionais Windows 2000 e superior.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários. O próximo lançamento do SMS, System Center Configuration Manager 2007, já está disponível; consulte também [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Para obter mais informações sobre como os administradores podem usar o SMS 2003 para instalar atualizações de segurança, consulte [Gerenciamento de Patches de Segurança do SMS 2003.](http://go.microsoft.com/fwlink/?linkid=22939) Usuários do SMS 2.0 também podem usar o Security Update Inventory Tool (SUIT) para ajudar a implantar atualizações de segurança. Para obter informações sobre o SMS, visite [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer para fornecer amplo suporte à detecção e à implantação de atualizações de boletins de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para as atualizações alvo de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) e no [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) (sites em inglês) para instalar essas atualizações.

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

-   Ling e Wushi, da [team509](http://www.team509.com/), que trabalham com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da Tipping Point, por relatar um problema descrito no boletim MS09-045.
-   Tavis Ormandy, da [Google Inc.](http://www.google.com/), por relatar um problema descrito no boletim MS09-046
-   Peter Winter-Smith, da [NGS Software](http://www.ngssoftware.com/), por relatar um problema descrito no boletim MS09-047
-   Hiroshi Noguchi, do Alice Carroll fan club, por relatar um problema descrito no boletim MS09-047
-   Jack C. Louis, da [Outpost24](http://www.outpost24.com/), por relatar um problema descrito no boletim MS09-048
-   Fabian Yamaguchi, da [Recurity Labs GmbH](http://www.recurity-labs.com/), por relatar um problema descrito no boletim MS09-048

#### Suporte

-   O software afetado listado foi testado a fim de determinar que versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos Estados Unidos e no Canadá podem receber suporte técnico do [Suporte de Segurança](http://go.microsoft.com/fwlink/?linkid=21131) ou pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas. Para obter mais informações sobre as opções de suporte disponíveis, consulte [Ajuda e Suporte da Microsoft](http://support.microsoft.com/?ln=pt-br).
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://go.microsoft.com/fwlink/?linkid=21155).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, conseqüenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos conseqüenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (8 de setembro de 2009): Resumo do Boletim publicado.
-   V2.0 (9 de setembro de 2009): Windows XP Service Pack 2, Windows XP Service Pack 3 e Windows XP Professional x64 Edition Service Pack 2 foram adicionados à tabela Softwares afetados do boletim MS09-048. No entanto, nenhuma atualização está disponível para estas plataformas. Consulte a entrada em **Perguntas frequentes relacionadas a esta atualização de segurança** no boletim MS09-048. Não houve nenhuma alteração às atualizações de segurança oferecidas neste boletim.
-   V3.0 (10 de novembro de 2009): O JScript 5.7 no Microsoft Windows 2000 Service Pack 4 foi adicionado à tabela de Softwares afetados do boletim MS09-045.

*Built at 2014-04-18T01:50:00Z-07:00*
