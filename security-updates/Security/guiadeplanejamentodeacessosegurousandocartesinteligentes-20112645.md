---
TOCTitle: Guia de Planejamento de Acesso Seguro Usando Cartões Inteligentes
Title: Guia de Planejamento de Acesso Seguro Usando Cartões Inteligentes
ms:assetid: 'd2a7a146-1779-4f8d-b618-1fd51e24dd85'
ms:contentKeyID: 20112645
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc170941(v=TechNet.10)'
---

Guia de Planejamento de Acesso Seguro Usando Cartões Inteligentes
=================================================================

### Visão geral

Atualizado em: 30 de junho de 2005

Os administradores estão cada vez mais cientes dos perigos resultantes de contar apenas com nomes de usuário e senhas para fornecer autenticação para acesso a recursos de rede. Os invasores podem decifrar nomes de usuários ou usar informações públicas disponíveis, como um endereço de email em um cartão de visita, para identificar um nome de usuário. Quando um invasor sabe o nome de usuário, o único mecanismo de segurança restante é a senha do usuário.

Segredos únicos como senhas podem ser controles de segurança eficazes. Uma senha longa de mais de 10 caracteres contendo letras, números e caracteres especiais aleatórios pode ser muito difícil de decifrar. Infelizmente, nem sempre os usuários conseguem se lembrar de senhas como essas, em parte por causa das limitações humanas básicas.

Uma pesquisa realizada por George A. Miller, publicada na revista *Psychological Review* em 1956, concluiu que o cérebro humano tem um limite de memória de curta duração que registra entre cinco e nove caracteres aleatórios, com uma média de sete. No entanto, a maioria das orientações de segurança recomenda utilizar uma senha de ao menos oito caracteres aleatórios. Como a maioria dos usuários não consegue decorar uma senha de oito caracteres aleatórios, muitos optam por anotá-la em um pedaço de papel.

Raramente os usuários usam discrição ao anotar suas senhas, e isso oferece oportunidades aos invasores de violar suas credenciais. Quando não há restrições na complexidade de senhas, os usuários tendem a escolher senhas fáceis de serem lembradas, como por exemplo a palavra "senha" ou outras palavras fáceis de serem adivinhadas.

Frases secretas são senhas mais longas e mais fáceis de serem lembradas. O Microsoft® Windows® 2000 e as versões posteriores do sistema operacional Windows aceitam senhas de até 127 caracteres de comprimento. Uma frase secreta segura, como "Eu gosto do mês de 10-zembro" dificulta consideravelmente a violação de senha por ferramentas que usam métodos agressivos, além de ser mais fácil de ser lembrada que uma combinação aleatória de letras e números.

Os sistemas de autenticação de dois fatores superam os problemas de autenticação de segredo único, exigindo um segundo segredo. A autenticação de dois fatores usa uma combinação dos seguintes itens:

-   Algo que o usuário tenha, como um token de hardware ou um cartão inteligente.

-   Algo que seja de conhecimento do usuário, como um número de identificação pessoal (PIN).

Os cartões inteligentes e seus respectivos PINs constituem um método de autenticação de dois fatores cada vez mais conhecido, confiável e econômico. Com os controles adequados em funcionamento, o usuário deve ter o cartão inteligente e saber o PIN para obter acesso aos recursos de rede. O requisito de dois fatores reduz consideravelmente a probabilidade de acesso não autorizado à rede de uma organização.

Os cartões inteligentes oferecem um controle de segurança particularmente eficaz em dois cenários: para proteger contas de administrador e para proteger acesso remoto. Este guia aborda esses dois cenários como as áreas prioritárias nas quais se deve implementar o uso de cartões inteligentes.

Devido à grande variedade de direitos de usuários presente em contas de nível de administrador, a violação de uma dessas contas pode conceder a um invasor o acesso a todos os recursos de rede. É essencial proteger o acesso no nível de administrador porque o roubo de credenciais de conta no nível de administrador do domínio prejudica a integridade do domínio, e possivelmente a floresta inteira, juntamente com quaisquer outras florestas confiáveis. A autenticação de dois fatores é essencial para a autenticação de administrador.

As organizações podem fornecer uma importante camada adicional de segurança se implementarem cartões inteligentes para os usuários que precisam de conectividade remota a recursos de rede. A autenticação de dois fatores é particularmente importante com usuários remotos, uma vez que não é possível fornecer qualquer forma de controle de acesso físico para conexões remotas. A autenticação de dois fatores com cartões inteligentes pode aumentar a segurança no processo de autenticação para usuários remotos que se conectam através de links de VPN.

##### Nesta página

[](#ehaa)[O desafio comercial](#ehaa)
[](#egaa)[Os benefícios comerciais](#egaa)
[](#efaa)[Quem deve ler este guia](#efaa)
[](#eeaa)[Pré-requisitos do leitor](#eeaa)
[](#edaa)[Visão geral do Guia de Planejamento](#edaa)
[](#ecaa)[Recursos relacionados](#ecaa)
[](#ebaa)[Faça seus comentários](#ebaa)

### O desafio comercial

A violação de credenciais de conta de administrador em computadores associados a um domínio pode prejudicar a integridade do domínio inteiro, da floresta na qual reside o domínio e de outras florestas e domínios que tenham relações de confiança com essa floresta. A violação de contas de acesso remoto pode resultar no acesso a informações confidenciais através de conexões dial-up ou VPN por invasores externos.

O desafio comercial de proteger as conexões de administrador e de acesso remoto consiste em fornecer um nível de segurança adequado que não comprometa seu uso prático. Uma organização que implementa a autenticação de dois fatores para melhorar a segurança não pode ter desempenho eficiente se os usuários não puderem acessar as informações de que precisam para desempenhar suas funções. É extremamente importante haver um equilíbrio entre autenticação de dois fatores e uso prático.

[](#mainsection)[Início da página](#mainsection)

### Os benefícios comerciais

O uso de cartões inteligentes para proteger contas importantes pode proporcionar os seguintes benefícios comerciais:

-   **Maior proteção aos dados confidenciais**. Os cartões inteligentes reduzem a ameaça de acesso não autorizado obtido através do uso de credenciais roubadas porque o hacker precisa roubar o cartão inteligente e obter o PIN.

-   **Melhor segurança para as credenciais de logon**. Os cartões inteligentes usam certificados digitais para credenciais de logon, que são difíceis de falsificar.

-   **Níveis mais elevados de conformidade normativa**. O fato de poder confirmar que o usuário conectado é quem alega ser proporciona maior credibilidade aos registros monitorados.

-   **Menor probabilidade de repúdio**. Com a autenticação através de cartão inteligente, fica mais difícil alguém negar suas ações.

-   **Melhor integração com sistemas de gerenciamento de acesso**. Alguns cartões inteligentes também funcionam como chaves para gerenciamento de acesso físico, tal como travas de portas controladas para acesso a um local físico e entre departamentos dentro de um local. A combinação de cartão inteligente e chave facilita o controle do nível exato de acesso à rede e físico de um usuário ou administrador, ao mesmo tempo em que reduz o receio de violação de segurança.

[](#mainsection)[Início da página](#mainsection)

### Quem deve ler este guia

O público-alvo deste guia inclui responsáveis por decisões técnicas, arquitetos empresariais e administradores de segurança empresariais que planejam, implantam ou operam links de acesso remoto e segurança de rede. Estas informações também podem ser úteis aos consultores que desejem planejar, implantar ou operar redes baseadas em Windows.

As informações neste guia aplicam-se a organizações de todos os portes que requerem proteção de identidade robusta e controle de acesso a dados.

[](#mainsection)[Início da página](#mainsection)

### Pré-requisitos do leitor

Para compreender as soluções apresentadas neste guia, os leitores devem entender e estar familiarizados com as seguintes áreas e tecnologias do Microsoft Windows Server™ 2003:

-   Roteamento e acesso remoto, incluindo componentes de VPN

-   Serviços de Certificados e PKI (Public Key Infrastructure)

-   Serviço de diretório do Active Directory®

-   Diretiva de grupo

Este guia aborda os quadrantes de modelo de processo Operação e Suporte dentro do MOF (Microsoft Operations Framework). Aborda também as funções de gerenciamento de serviços (SMFs) Administração de segurança e Gerenciamento de incidentes dentro do MOF. Para obter mais informações sobre o MOF, consulte a página [Microsoft Operations Framework](http://www.microsoft.com/mof) (em inglês) em www.microsoft.com/mof.

[](#mainsection)[Início da página](#mainsection)

### Visão geral do Guia de Planejamento

Este guia apresenta quatro capítulos que se concentram nas questões e conceitos essenciais necessários ao planejamento da autenticação com cartão inteligente. Esses capítulos são:

**Capítulo 1: Introdução**

Esse capítulo fornece um resumo executivo, analisa os desafios comerciais enfrentados e os benefícios obtidos com a implementação de autenticação com cartão inteligente. O capítulo sugere o público-alvo recomendado para o guia, relaciona os pré-requisitos do leitor e fornece uma visão geral dos capítulos e cenários das soluções.

**Capítulo 2: Tecnologias de cartão inteligente**

Esse capítulo descreve as abordagens sobre o uso de cartões inteligentes para proteger contas importantes. Ele também discute os elementos essenciais aos dois cenários de solução abordados nos capítulos 3 e 4. Por fim, esse capítulo apresenta o Woodgrove Bank, que serve de base para os dois cenários de solução.

**Capítulo 3: Usando cartões inteligentes para ajudar a proteger contas de administrador**

Esse capítulo descreve as considerações de projeto necessárias para proteger contas de administrador com cartões inteligentes. O capítulo prossegue examinando os problemas e os requisitos do Woodgrove Bank. Ele discute o conceito, os pré-requisitos, a arquitetura e a operação da solução para o cenário. Por fim, o capítulo avalia as possíveis opções de estender a solução para incorporar o processo de gerenciamento de alterações.

**Capítulo 4: Usando cartões inteligentes para ajudar a proteger contas de acesso remoto**

Esse capítulo descreve as considerações de projeto para acesso remoto com cartões inteligentes. O capítulo prossegue examinando os problemas e os requisitos para a implementação de acesso remoto seguro para o Woodgrove Bank. Ele discute o conceito, os pré-requisitos, a arquitetura e a operação da solução para o cenário. Por fim, o capítulo analisa a possibilidade de estender a solução para incorporar o controle de acesso físico.

[](#mainsection)[Início da página](#mainsection)

### Recursos relacionados

Leia [outras soluções de segurança](http://www.microsoft.com/technet/community/columns/sectip/st0805.mspx) da equipe do Microsoft Solutions for Security and Compliance (Parceiros).

[](#mainsection)[Início da página](#mainsection)

### Faça seus comentários

A equipe do Microsoft Solutions for Security and Compliance (MSSC) gostaria de saber sua opinião sobre esta e outras soluções de segurança.

Você tem uma opinião? Informe-nos no [Blog de soluções de segurança](http://blogs.technet.com/secguide) para o profissional de TI.

Ou envie seus comentários por email ao seguinte endereço: [SecWish@microsoft.com](mailto:secwish@microsoft.com). Freqüentemente respondemos os comentários enviados para essa caixa de correio.

Estamos ansiosos por receber seus comentários.

[](#mainsection)[Início da página](#mainsection)

##### Neste artigo

**Download**

[Obtenha o Guia de Planejamento de Acesso Seguro Usando Cartões Inteligentes](http://go.microsoft.com/fwlink/?linkid=41314)

**Notificações de atualizações**

[Inscreva-se para obter informações sobre atualizações e novos lançamentos](http://go.microsoft.com/fwlink/?linkid=54982)

**Comentários**

[Envie-nos seus comentários e sugestões](mailto:secwish@microsoft.com?subject=guia%20de%20planejamento%20de%20acesso%20seguro%20usando%20cartões%20inteligentes)

[](#mainsection)[Início da página](#mainsection)
