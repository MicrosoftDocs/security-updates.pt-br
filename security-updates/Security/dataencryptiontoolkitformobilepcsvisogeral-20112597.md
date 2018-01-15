---
TOCTitle: 'Data Encryption Toolkit for Mobile PCs: Visão geral'
Title: 'Data Encryption Toolkit for Mobile PCs: Visão geral'
ms:assetid: 'abfc4696-a39a-43df-b559-133633e4bd5e'
ms:contentKeyID: 20112597
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc162811(v=TechNet.10)'
---

Data Encryption Toolkit for Mobile PCs - Análise de Segurança
=============================================================

### Visão geral

Publicado em: 4 de abril de 2007

Até alguns anos atrás, os laptops ainda eram relativamente raros na maioria das empresas. Os laptops visavam normalmente apenas as pessoas que viajavam com freqüência a trabalho e os executivos. Hoje, os laptops estão mais potentes do que nunca, mas também se tornaram figurinhas fáceis. Eles não são mais privilégio de poucos — e chegam até a superar o número de desktops em certas organizações. E à medida que sua capacidade de armazenamento vem crescendo, eles vêm se tornando repositórios cada vez mais valiosos para todos os tipos de dados confidenciais.

O grande aumento no número de laptops foi seguido por um aumento correspondente no número de laptops perdidos ou roubados. A segurança dos laptops é um problema sério para a maioria das empresas de médio e grande portes. Em uma pesquisa recente realizada pelo Ponemon Institute, "[Confidential Data at Risk](http://www.csoonline.com/read/080106/col_ponemon.html)", "81% dos 484 participantes da pesquisa informaram que suas organizações sofreram com a perda ou desaparecimento de laptops contendo informações comerciais sigilosas ou confidenciais nos últimos 12 meses". Embora o custo da reposição seja significativo, são ainda maiores os gastos diretos e indiretos de uma quebra na segurança decorrente do roubo de um laptop contendo dados importantes ou confidenciais armazenados no seu disco rígido.

Certos tipos de informação são protegidos por legislação federal ou nacional, outros, por legislações estaduais, municipais ou regionais, e outros, por regulamentos do setor. O número de legislações, jurisdições e classificações sigilosas vem crescendo proporcionalmente ao número de laptops. A perda de um laptop poderia expor uma organização a multas significativas e penalidades civis, dependendo da quantidade de esforço investido em medidas de segurança preemptivas. E os custos diretos e indiretos após uma falha na segurança podem incluir dificuldade em manter os clientes e perda da credibilidade e reputação.

A Microsoft fornece ferramentas para lidar com as preocupações com a segurança de laptops. Se os dados forem devidamente criptografados em um laptop pode ser muito mais difícil recuperar dados confidenciais em caso de perda ou roubo do laptop. Mediante o uso correto da Criptografia de Unidade de Disco BitLocker™ da Microsoft (BitLocker) e do EFS (Sistema de arquivos criptografados), os dados confidenciais podem ser protegidos contra uma vasta gama de vetores comuns de ataque.

Este guia, o *Microsoft Data Encryption Toolkit for Mobile PCs - Análise de Segurança*, oferece detalhes específicos sobre os níveis de segurança que podem ser atingidos com o uso do BitLocker e do EFS. As edições Enterprise e Ultimate do Windows Vista™ são compatíveis com toda a série de recursos de segurança descrita neste guia, e há um subconjunto significativo e útil disponível no Microsoft Windows® XP. Há vários níveis de proteção disponíveis, dependendo dos recursos e configurações aplicados. Nas configurações mais seguras, um ataque mal-intencionado exigiria uma quantidade extraordinária de recursos para descriptografar os dados em uma unidade de disco rígido.

A *Análise de Segurança* irá ajudá-lo a entender como os recursos do Windows Vista e Windows XP ajudam a atenuar riscos de segurança específicos em sua empresa. Este guia irá ajudá-lo a:

-   Identificar riscos e vetores de ameaça comuns no seu ambiente.

-   Saber como atenuar riscos e ameaças específicos usando o BitLocker e o EFS, seja individualmente ou em conjunto.

-   Preparar-se para combater as ameaças à segurança não abrangidas pelo BitLocker ou pelo EFS.

-   Conhecer recursos e tecnologias de segurança selecionados disponíveis no Windows Vista.

Os recursos de segurança abordados neste guia foram desenvolvidos com o uso de tecnologias aprovadas no setor. Por exemplo, a implementação da Microsoft dos algoritmos criptográficos usados para o BitLocker e EFS é certificada de acordo com o US Federal Government Federal Information Processing Standard (FIPS) 140-1, e os algoritmos implementados são todos amadurecidos. Esta adesão a tecnologias aprovadas no setor é importante porque algumas leis estaduais e nacionais que regem a confidencialidade de dados oferecem brechas ou fatores atenuantes para as empresas que puderem provar que se empenharam para seguir as práticas recomendadas para segurança dos dados.

##### Nesta página

[](#egaa)[Quem deve ler este guia?](#eg)  
[]([](#efaa)[Conteúdo dos capítulos](#ef)  
[]([](#eeaa)[Convenções de estilo](#ee)  
[]([](#edaa)[Mais informações](#ed)  
[]([](#ecaa)[Suporte e comentários](#ec)  
[]([](#ebaa)[Agradecimentos](#eb)  
[](
### Quem deve ler este guia?

Este guia foi formulado para atender a especialistas em segurança responsáveis por tomar decisões e fornecer recomendações sobre diretivas e tecnologias relacionadas a dezenas ou até milhares de computadores clientes, principalmente laptops. A tecnologia em si e as ameaças relacionadas em geral não se aplicam a um usuário ou rede doméstica. Você deve ler este guia se for de sua responsabilidade:

-   Tomar decisões ou fazer recomendações sobre diretivas e tecnologias de segurança.

-   Implementar diretiva de segurança de servidor ou cliente.

-   Avaliar a tecnologia de segurança.

-   Integrar a diretiva de segurança a outras diretivas ou tecnologias de gerenciamento de computadores.

As informações contidas neste guia são avançadas e detalhadas, e não visam atender a iniciantes em segurança, criptografia, sistemas de arquivos ou outros tópicos fundamentais de segurança e administração de sistemas.

[](#mainsection)[Início da página](#mainsection)

### Conteúdo dos capítulos

Esta seção apresenta uma visão geral dos capítulos deste guia.

[Capítulo 1: Discussão sobre riscos](http://www.microsoft.com/brasil/technet/security/guidance/clientsecurity/dataencryption/analysis/df2c6d71-98f7-4212-b3b7-b9eb2f501348.mspx) - apresenta as ameaças à segurança que podem ser combatidas pelo BitLocker e EFS. Aborda também os cenários usados no restante da *Análise de Segurança* para fornecer uma estrutura mais concreta de discussão dos riscos e benefícios.

[Capítulo 2: Criptografia de Unidade de Disco BitLocker](http://www.microsoft.com/brasil/technet/security/guidance/clientsecurity/dataencryption/analysis/80c0d0af-2c2e-45d6-9b29-f850926296bb.mspx) - focaliza a tecnologia BitLocker Drive Encryption lançada com o Windows Vista. O capítulo mostra como você pode usar o BitLocker para ajudá-lo a combater as ameaças específicas à segurança descritas no Capítulo 1, e inclui amostras de configuração que você pode usar como ponto de partida para desenvolver uma implementação sólida do BitLocker em sua empresa.

[Capítulo 3: EFS (Sistema de arquivos criptografados)](http://www.microsoft.com/brasil/technet/security/guidance/clientsecurity/dataencryption/analysis/dc2cde72-a84d-4716-9a30-f62b608efda1.mspx) - descreve como o EFS funciona e como você pode usá-lo para combater ameaças específicas no seu ambiente.

[Capítulo 4: BitLocker e EFS juntos](http://www.microsoft.com/brasil/technet/security/guidance/clientsecurity/dataencryption/analysis/80c0d0af-2c2e-45d6-9b29-f850926296bb.mspx) - mostra como combinar o BitLocker e o EFS para combater ameaças com mais eficiência do que seria possível com cada tecnologia isoladamente.

[Capítulo 5: Escolhendo a solução certa](http://www.microsoft.com/brasil/technet/security/guidance/clientsecurity/dataencryption/analysis/b77d6369-10e9-4e66-8c67-c9f8cb073ced.mspx) - apresenta abordagens e ferramentas que visam ajudar os especialistas em segurança a escolher a melhor combinação de recursos e itens de configuração para suas empresas.

[](#mainsection)[Início da página](#mainsection)

### Convenções de estilo

Esse guia usa as convenções de estilo descritas na tabela a seguir.

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Elemento</th>
<th style="border:1px solid black;" >Significado</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Fonte em negrito</strong></td>
<td style="border:1px solid black;">Caracteres digitados exatamente como exibidos, inclusive comandos, opções e nomes de arquivos. Elementos da interface do usuário também aparecem em negrito.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>Fonte em itálico</em></td>
<td style="border:1px solid black;">Títulos de livros e de outras publicações significativas aparecem em <em>itálico</em>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>&lt;Itálico&gt;</em></td>
<td style="border:1px solid black;">Espaços reservados que aparecem em itálico e entre colchetes angulares - &lt; <em>nome de arquivo</em>&gt; - representam variáveis.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><pre><code>Fonte monospace</code></pre></td>
<td style="border:1px solid black;">Define exemplos de código e de scripts.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Observação</strong></td>
<td style="border:1px solid black;">Chama a atenção do leitor para informações complementares.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Importante</strong></td>
<td style="border:1px solid black;">Chama a atenção do leitor para informações complementares essenciais.</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[Início da página](#mainsection)
  
### Mais informações
  
Além desta *Análise de Segurança*, o [Data Encryption Toolkit for Mobile PCs](http://go.microsoft.com/fwlink/?linkid=86127) inclui outros documentos e ferramentas que podem ser úteis:
  
-   O *Guia de Planejamento e Implementação* descreve como planejar e implementar o BitLocker e o EFS para proteger seus PCs móveis.
  
-   A ferramenta Microsoft Encrypting File System Assistant (Assistente do EFS) ajuda-o a automatizar o processo de localização e criptografia de arquivos confidenciais em computadores que operam com Windows XP e Windows Vista.
  
-   O *Guia do Administrador do Assistente do EFS* (pode estar em inglês) explica como os administradores podem implantar e gerenciar um Assistente do EFS em computadores de domínio conjunto para oferecer proteção uniforme pelas unidades empresariais ou por toda a empresa.
  
Há vários recursos valiosos disponíveis para ajudar as pessoas responsáveis pela tomada de decisões a ter acesso a um contexto mais amplo ou a adquirir um conhecimento mais profundo sobre as questões de segurança em redes Microsoft Windows. Um ótimo ponto de partida é a página do [Security Guidance](http://www.microsoft.com/technet/security/guidance/default.mspx) no Microsoft TechNet.
  
Recomendações específicas para lidar com requisitos de segurança de gerenciamento de domínio podem ser encontradas em [Best Practice Guide for Securing Windows Server Active Directory Installations](http://www.microsoft.com/windowsserver2003/techinfo/overview/adsecurity.mspx).
  
[](#mainsection)[Início da página](#mainsection)
  
### Suporte e comentários
  
A equipe do Solution Accelerators – Security and Compliance (SASC) gostaria de saber sua opinião sobre este e outros Aceleradores de Solução. Para contribuir com opiniões e comentários, escreva para [secwish@microsoft.com](mailto:secwish@microsoft.com?subject=data%20encryption%20toolkit%20for%20mobile%20pcs%20security%20analysis%20on%20technet). Queremos saber sua opinião.
  
O Solution Accelerators fornece orientações prescritivas e automação para a integração entre produtos. Ele contém ferramentas comprovadas e conteúdo para que você possa planejar, desenvolver, implantar e operar a tecnologia da informação com confiança. Para ver a extensa linha do Solution Accelerators e obter informações adicionais, visite a página [Solution Accelerators](http://go.microsoft.com/fwlink/?linkid=51571) no Microsoft TechNet.
  
[](#mainsection)[Início da página](#mainsection)
  
### Agradecimentos
  
A equipe do Solution Accelerators – Security and Compliance (SA-SC) gostaria de agradecer à equipe que produziu o *Data Encryption Toolkit for Mobile PC - Análise de Segurança*. As pessoas a seguir foram responsáveis diretas ou deram substancial contribuição na redação, desenvolvimento e testes desta solução.
  
**Chefes de Desenvolvimento**
  
Mike Smith-Lonergan - *Microsoft*
  
David Mowers - *Securitay, Inc.*
  
**Gerente de programa**
  
Bill Canning - *Microsoft*
  
**Desenvolvedores de conteúdo**
  
Paul Flynn - *3Sharp, LLC*
  
Tommy Phillips - *Butternut Software*
  
Paul Robichaux - *3Sharp, LLC*
  
**Editor**
  
Steve Wacker - *Wadeware LLC*
  
**Revisores**
  
Vijay Bharadwaj - *Microsoft*
  
Tom Daemen - *Microsoft*
  
Mike Danseglio - *Microsoft*
  
Kurt Dillard - *Microsoft*
  
Jeff Hatfield - *Wireless Ink Inc.*
  
Erik Holt - *Microsoft*
  
Russell Humphries - *Microsoft*
  
David Kennedy - *Microsoft*
  
Douglas MacIver - *Microsoft*
  
Josh Phillips
  
Greg Petersen - *Avanade Inc.*
  
Ben Wilson - *ASG Group*
  
**Gerentes de produto**
  
Alain Meeus - *Microsoft*
  
Jim Stuart - *Microsoft*
  
**Gerente de lançamento**
  
Karina Larson - *Microsoft*
  
**Testadores**
  
Gaurav Singh Bora - *Microsoft*
  
Sumit Ajitkumar Parikh - *Infosys Technologies Ltd.*
  
Swaminathan Viswanathan - *Infosys Technologies Ltd.*
  
Swapna Rangachari Jagannathan - *Infosys Technologies Ltd.*
  
Neethu Thomas - *Infosys Technologies Ltd.*
  
[](#mainsection)[Início da página](#mainsection)
  
**Download**
  
[Obtenha o Data Encryption Toolkit for Mobile PCs](http://go.microsoft.com/fwlink/?linkid=81666)
  
**Participe**
  
[Inscreva-se para participar do programa beta do Data Encryption Toolkit for Mobile PCs](https://www.microsoft.com/brasil/technet/security/guidance/clientsecurity/dataencryption/analysis/default.mspx)
  
**Notificações de atualizações**
  
[Inscreva-se para obter informações sobre atualizações e novos lançamentos](http://go.microsoft.com/fwlink/?linkid=54982)
  
**Comentários**
  
[Envie-nos seus comentários e sugestões](mailto:secwish@microsoft.com?subject=data%20encryption%20toolkit%20for%20mobile%20pcs%20security%20analysis%20on%20technet)
  
[](#mainsection)[Início da página](#mainsection)
