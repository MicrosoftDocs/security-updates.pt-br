---
TOCTitle: 'MS17-FEB'
Title: Resumo do Boletim de Segurança da Microsoft para fevereiro de 2017
ms:assetid: 'ms17-feb'
ms:contentKeyID: 74419959
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms17-feb(v=Security.10)'
---

Modelo do MSRC ppDocument

Resumo do Boletim de Segurança da Microsoft para fevereiro de 2017
==================================================================

Publicado em: 21 de fevereiro de 2017

**Versão:** 1.0

Este resumo do boletim lista boletins de segurança lançados em fevereiro de 2017.

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft forem emitidos, visite [Notificações de Segurança Técnica da Microsoft.](http://go.microsoft.com/fwlink/?linkid=21163)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações**.

Como lembrete, o [Guia de Atualizações de Segurança](https://portal.msrc.microsoft.com/pt-br/security-guidance) substituirá os boletins de segurança. Para obter mais detalhes, consulte nossa postagem de blog, [Furthering our commitment to security updates](https://blogs.technet.microsoft.com/msrc/2016/11/08/furthering-our-commitment-to-security-updates/) (Ampliando nosso compromisso com as atualizações de segurança).

Resumos executivos
------------------

<span id="sectionToggle0"></span>
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os Software afetado, consulte a próxima seção, **Software afetado**.

<table style="width:100%;" style="border:1px solid black;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ID do Boletim</strong></td>
<td style="border:1px solid black;"><strong>Título do boletim e Resumo executivo</strong></td>
<td style="border:1px solid black;"><strong>Classificação máxima de gravidade<br />
e impacto da vulnerabilidade</strong></td>
<td style="border:1px solid black;"><strong>Requisito de reinicialização</strong></td>
<td style="border:1px solid black;"><strong>Problemas<br />
conhecidos</strong></td>
<td style="border:1px solid black;"><strong>Softwares afetados</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839437">MS17-005</a></td>
<td style="border:1px solid black;"><strong>Atualização de Segurança para Adobe Flash Player (4010250)<br />
</strong>Esta atualização de segurança resolve vulnerabilidades no Adobe Flash Player quando instalado em todas as edições com suporte do Windows 8.1, Windows Server 2012, Windows Server 2012 R2, Windows RT 8.1, Windows 10 e Windows Server 2016.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

Índice de exploração
--------------------

<span id="sectionToggle1"></span>
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas por ID do boletim e depois por ID do CVE. Estão incluídas nos boletins somente vulnerabilidades com classificação de gravidade Crítica ou Importante.

**Como devo usar esta tabela?**

Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que significam essas classificações e como elas são determinadas, consulte o [Índice de Exploração da Microsoft](http://technet.microsoft.com/pt-br/security/cc998259).

Nas colunas a seguir, "Versão mais recente de software" se refere ao software e "Versões mais antigas de software" se refere a todas as versões mais antigas do software compatíveis, conforme listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**ID do CVE**                    
</td>
<td style="border:1px solid black;">
**Título da vulnerabilidade**
</td>
<td style="border:1px solid black;">
**Avaliação da capacidade de exploração da  
última versão de software**
</td>
<td style="border:1px solid black;">
**Avaliação da capacidade de exploração de  
versão mais antiga de software**
</td>
<td style="border:1px solid black;">
**Avaliação do risco de exploração  
para negação de serviço**
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-005: Atualização de segurança para o Adobe Flash Player (4010250)**](https://go.microsoft.com/fwlink/?linkid=839437)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB17-04](http://helpx.adobe.com/br/security/products/flash-player/apsb17-04.html)
</td>
<td style="border:1px solid black;">
Consulte o Boletim de segurança da Adobe APSB17-04 para ver classificações de prioridade da atualização e de gravidade da vulnerabilidade
</td>
<td style="border:1px solid black;">
---------
</td>
<td style="border:1px solid black;">
---------
</td>
<td style="border:1px solid black;">
Não aplicável
</td>
</tr>
</table>
 

Softwares afetados
------------------

<span id="sectionToggle2"></span>
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.

Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.

**Observação** Talvez seja necessário instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.

### Sistemas operacionais Windows e componentes

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
Apenas segurança</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
Pacote cumulativo mensal</td>
<td style="border:1px solid black;">
Não aplicável</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
Apenas segurança</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas com base em x64  
Pacote cumulativo mensal</td>
<td style="border:1px solid black;">
Não aplicável</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 e Windows Server 2012 R2**</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**</td>
<td style="border:1px solid black;">
[**Moderada**](http://go.microsoft.com/fwlink/?linkid=21140)</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
Apenas segurança</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Moderada)</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
Pacote cumulativo mensal</td>
<td style="border:1px solid black;">
Não aplicável</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
Apenas segurança</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Moderada)</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
Pacote cumulativo mensal</td>
<td style="border:1px solid black;">
Não aplicável</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows RT 8.1**</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
Pacote cumulativo mensal
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1511 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Versão 1607 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS17-005**](https://go.microsoft.com/fwlink/?linkid=839437)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Classificação de gravidade agregada**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 para sistemas com base em x64
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4010250)  
(Crítica)
</td>
</tr>
</table>
 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

<span id="sectionToggle3"></span>
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O MBSA (Microsoft Baseline Security Analyzer) permite que os administradores verifiquem, em sistemas locais e remotos, se há atualizações de segurança ausentes e erros comuns de configuração de segurança.

O WSUS (Windows Server Update Services), SMS (Systems Management Server) e SCCM (System Center Configuration Manager) ajudam os administradores a distribuir as atualizações de segurança.

Os componentes do Avaliador de Compatibilidade de Atualizações, incluídos no Kit de Ferramentas de Compatibilidade de Aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para obter mais informações sobre essas e outras ferramentas disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/pt-br/security/cc297183). 

Agradecimentos
--------------

<span id="sectionToggle4"></span>
A Microsoft reconhece os esforços dos membros da comunidade de segurança que nos ajudam a proteger os consumidores graças à divulgação responsável de vulnerabilidades. Consulte [Agradecimentos](https://technet.microsoft.com/pt-br/library/security/mt745121.aspx) para obter mais informações.

Outras informações
------------------

<span id="sectionToggle5"></span>
### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

Em relação ao lançamento de boletins que ocorre na segunda terça-feira do mês, a Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows no Windows Update, Microsoft Update, Windows Server Update Services e Centro de Download. Nenhuma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows está disponível para os lançamentos de boletins de segurança desvinculados.

### Atualizações não relacionadas à segurança no MU, WU e WSUS

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 da Base de Dados de Conhecimento da Microsoft](https://support.microsoft.com/pt-br/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/pt-br/wsus/bb456965). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões com base em rede ou sistemas de prevenção de invasões com base em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://go.microsoft.com/fwlink/?linkid=215201).

### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [artigo 913086 da Base de Dados de Conhecimento Microsoft](https://support.microsoft.com/pt-br/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e otimizar a infraestrutura de TI e participe de discussões sobre tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida de suporte para sua versão de software, visite o site [Ciclo de vida de suporte da Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).

Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança do TechNet](http://technet.microsoft.com/pt-br/security/bb980617)

Ajuda a proteger seu computador executando o Windows contra vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/pt-br/contactus/cu_sc_virsec_master)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/pt-br/common/international.aspx)

### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Dados de Conhecimento Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (21 de fevereiro de 2017): Resumo do boletim publicado.

*Página gerada em 21/02/2017 07:05-08:00.*
