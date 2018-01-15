---
TOCTitle: Guia de Planejamento de Implementação dos Serviços de Quarentena com VPN da Microsoft
Title: Guia de Planejamento de Implementação dos Serviços de Quarentena com VPN da Microsoft
ms:assetid: '40028620-c153-4851-bf15-d79d55d056bd'
ms:contentKeyID: 20112621
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc162926(v=TechNet.10)'
---

Guia de Planejamento de Implementação dos Serviços de Quarentena com VPN da Microsoft
=====================================================================================

### Visão geral

Atualizado em: 24/5/2005

A ampla disponibilidade da Internet gerou mudanças significativas na maneira como muitas organizações trabalham. Para manter uma vantagem competitiva, as organizações necessitam de que cada vez mais funcionários se conectem a redes corporativas a partir de locais remotos como residências, escritórios, hotéis, Internet cafés ou instalações de clientes. Essas conexões remotas são normalmente implementadas com tecnologias VPN (rede virtual privada).

As conexões VPN permitem que funcionários e parceiros se conectem a uma LAN (rede local) corporativa através de uma rede pública de maneira segura. O acesso remoto que usa tecnologias VPN é um fator impulsionador importante para muitas novas oportunidades de negócios, como administração remota e aplicativos de alta segurança. Um grande número de grupos e usuários de negócios utilizam aplicativos de produtividade e administração que requerem acesso remoto freqüente e seguro a LANs corporativas.

Embora a VPN forneça acesso seguro criptografando os dados através de seu encapsulamento, ela não impede invasões por softwares mal-intencionados, como vírus ou worms, que são iniciados no computador de acesso remoto. Os ataques de vírus ou worms podem originar-se de computadores infectados conectados à LAN.

Visto que organizações como as do setor de serviços financeiros precisam manter sua reputação para transações seguras, até mesmo a menor violação de segurança pode prejudicar a percepção pública de uma empresa. Por isso, as conexões VPN devem estar sujeitas a rigorosas verificações e validações de requisitos de acesso.

O acesso à VPN potencialmente não seguro ocorre quando o computador remoto não atende aos requisitos de segurança da organização. A maioria das implementações de VPN não pode verificar se um computador remoto tem as atualizações de segurança ou as assinaturas de vírus mais recentes antes de estabelecer conexão com a rede corporativa. Portanto, muitas organizações não consideram que o acesso remoto baseado em VPN atende a seus requisitos de segurança.

A quarentena VPN oferece um mecanismo para tratar essas questões. Ela garante que computadores que se conectam à rede por meio de protocolos VPN se submetam a verificações antes e após a conexão e fiquem isolados até que atendam à diretiva de segurança necessária. Essas verificações, realizadas com scripts personalizados, podem examinar versões de service pack, atualizações de segurança e se um programa antivírus aprovado está sendo executado com os arquivos de definição de vírus mais recentes. As organizações podem testar outros requisitos nesses scripts personalizados.

A solução de quarentena VPN inclui em uma rede de quarentena todos os computadores de conexão que atendem à diretiva de acesso remoto especificada e verifica se esses computadores estão em conformidade com a diretiva de segurança da organização. O servidor VPN de acesso remoto suspende as restrições de quarentena e permite acesso a recursos da rede corporativa somente quando o computador de acesso remoto passa por todas as verificações de conexão.

Este guia descreve os desafios do planejamento e da implementação dos serviços de quarentena com VPN através dos novos recursos disponíveis no Microsoft® Windows Server™ 2003 com Service Pack 1 (SP1).

##### Nesta página

[](#eeaa)[O desafio comercial](#eeaa)  
[](#edaa)[Os benefícios comerciais](#edaa)  
[](#ecaa)[A quem este guia se destina](#ecaa)  
[](#ebaa)[Pré-requisitos do leitor](#ebaa)  
[](#eaaa)[Visão geral do Guia de Planejamento](#eaaa)

### O desafio comercial

As organizações enfrentam vários desafios ao conceder acesso remoto através de conexões VPN. Esses desafios variam de acordo com os serviços fornecidos, a estrutura normativa em que a empresa funciona e o ambiente de segurança. Os desafios comuns incluem como:

-   Definir uma diretiva de acesso VPN eficiente.

-   Reduzir a probabilidade de que computadores infectados ou não compatíveis possam se conectar à LAN corporativa.

-   Atender a requisitos legais para a manutenção da segurança dos dados e de informações pessoais.

[](#mainsection)[Início da página](#mainsection)

### Os benefícios comerciais

As organizações que implementam serviços de quarentena VPN eficientes podem perceber vários benefícios importantes. Esses benefícios incluem:

-   **Acesso mais seguro a ativos corporativos**. A quarentena VPN aumenta a segurança do acesso à rede através da conformidade com os requisitos de atualização antivírus e de segurança.

-   **Administração simplificada e manutenção de serviços**.** **As organizações podem padronizar a implementação VPN com base nas tecnologias mais atualizadas e seguras. Elas podem remover as implementações VPN de hardware, como sistemas de computadores para acesso remoto especializado na infra-estrutura de rede e, desse modo, simplificar as ferramentas de suporte, a documentação e os processos de conexão. Essa simplificação melhora o suporte operacional diário da solução de acesso VPN e compensa os custos de gerenciamento da implementação de uma solução de quarentena.

-   **Previsibilidade e aplicação mais abrangentes do acesso remoto**.** **A segurança e a aplicação mais abrangentes estimulam os funcionários a usar o serviço VPN, proporcionando maior confiança na proteção de trabalhos importantes e recursos corporativos essenciais.

-   **TCO (custo total de propriedade) reduzido**. Se os computadores remotos forem forçados a atender às diretivas rígidas para computadores confiáveis, os custos gerais de administração e suporte serão reduzidos. Essa economia resulta da redução das ligações para o suporte e do menor tempo gasto no tratamento de ataques de vírus e worms.

-   **Maior segurança para informações comerciais críticas**. As informações dos clientes são de fundamental importância para a maioria das organizações, especialmente para as que funcionam em um ambiente normativo. O armazenamento dessas informações da maneira mais segura possível ajuda a atender aos requisitos normativos e a manter a reputação comercial da organização.

-   **Processos de negócios aprimorados**. A implementação de uma solução de quarentena VPN aumenta a disponibilidade de aplicativos e processos de negócios para gerentes de vendas de campo, gerentes de contas de clientes e consultores. Essa maior disponibilidade permite retorno mais rápido das decisões e mais flexibilidade no fornecimento de produtos e serviços.

Para obter mais informações sobre esses benefícios, consulte o Capítulo 2, "Abordagens da quarentena VPN".

[](#mainsection)[Início da página](#mainsection)

### A quem este guia se destina

Este guia fornece informações úteis para as pessoas de uma organização de grande porte que lidam com estritas questões de privacidade e para as que trabalham em uma estrutura normativa de aplicação rígida. Ele também se aplica a organizações de todos os tamanhos que necessitam de proteção de identidade e controle de acesso aos dados.

O público-alvo deste guia abrange responsáveis por decisões técnicas, arquitetos empresariais e administradores de segurança empresariais que planejam, implantam ou operam links de acesso remoto e a segurança da rede. Essas informações também devem ser úteis para consultores que planejam, implantam ou operam redes VPN baseadas no Microsoft Windows®.

[](#mainsection)[Início da página](#mainsection)

### Pré-requisitos do leitor

Este guia pressupõe que seus leitores tenham conhecimento funcional sobre os conceitos e as tecnologias de gerenciamento do acesso remoto. Para implementar as soluções apresentadas no guia, os leitores devem conhecer e estar familiarizados com as seguintes áreas e tecnologias:

-   Acesso remoto ao Windows Server 2003

-   IAS (Serviço de Autenticação da Internet) ou outras implementações do RADIUS (Remote Authentication Dial-In User Service)

-   Gerenciador de conexões e CMAK (Kit de Administração do Gerenciador de Conexões)

-   Scripts ou programas de arquivo em lotes

-   Serviços de certificação e PKI (infra-estrutura de chave pública)

Este guia aborda os quadrantes de modelo do processo Operação e Suporte dentro do MOF (Microsoft Operations Framework). Ele também aborda as SMFs (funções de gerenciamento de serviços) de administração de segurança e gerenciamento de incidentes no MOF. Para obter mais informações sobre o MOF, consulte o site [Microsoft Operations Framework](http://www.microsoft.com/mof) em http://www.microsoft.com/mof.

[](#mainsection)[Início da página](#mainsection)

### Visão geral do Guia de Planejamento

Este guia é composto dos seguintes capítulos:

**Capítulo 1: Introdução**

Este capítulo oferece um resumo executivo, apresenta os desafios e benefícios comerciais que envolvem a implantação de VPNs com o serviço de quarentena, sugere o público-alvo para este guia, lista os pré-requisitos do leitor e fornece uma visão geral dos capítulos e cenários de solução do guia.

**Capítulo 2: Abordagens da Quarentena VPN**

Este capítulo descreve os métodos de acesso da quarentena VPN. Também aborda os elementos essenciais do acesso VPN para uma solução no cenário de telecomutador.

**Capítulo 3: Problemas e requisitos**

Este capítulo apresenta o cenário do Woodgrove National Bank. Em seguida, define informações gerais, questões comerciais, questões técnicas e de segurança, bem como os requisitos de soluções para os cenários de quarentena VPN para o Woodgrove National Bank. Este capítulo também aborda o cenário de solução para o acesso VPN referente a telecomutadores, examinando os desafios comerciais, técnicos e de segurança desse cenário.

**Capítulo 4: Projeto da solução**

Este capítulo descreve em detalhes como planejar a solução do cenário de acesso VPN para telecomutadores. Além disso, aborda o conceito de solução, os pré-requisitos e a arquitetura da solução, bem como o funcionamento da solução. Por fim, o capítulo descreve como estender a solução.

Além de uma discussão geral sobre como usar a VPN com serviços de quarentena, este guia oferece orientação prescritiva para a implementação de uma solução segura de acesso remoto, criada com base no cenário do Woodgrove National Bank apresentado nesta série. Esse cenário ensina a implementar o acesso VPN seguro para telecomutadores.

A Microsoft criou o cenário do Woodgrove National Bank para ilustrar os desafios comuns enfrentados pelas organizações com o intuito de fornecer serviços de quarentena da rede VPN, e como as tecnologias Microsoft podem superar esses desafios. Este cenário ensina a:

-   Implementar acesso remoto altamente seguro para os vendedores de campo que raramente estão no escritório.

-   Proporcionar continuidade de negócios logo após um incidente climático grave, de modo que os funcionários possam continuar a ser produtivos em casa.

-   Propiciar condições de trabalho flexíveis para que os trabalhadores possam optar por trabalhar em casa.

-   Fornecer atualizações de software periódicas para computadores remotos.

#### Faça seus comentários

A Microsoft gostaria de receber seus comentários sobre este material. Em particular, qualquer comentário sobre as questões abaixo será apreciado:

-   Qual foi a utilidade das informações fornecidas?

-   Os procedimentos passo a passo eram precisos?

-   Os capítulos eram de fácil leitura e interessantes?

-   No geral, como você classificaria a solução?

Se preferir, envie por email seus comentários para o seguinte endereço: [SecWish@microsoft.com](mailto:secwish@microsoft.com). Normalmente, respondemos aos comentários enviados para essa caixa de correio.

Esperamos seus comentários.

[](#mainsection)[Início da página](#mainsection)

##### Neste artigo

-   Visão geral
-   [Capítulo 1 - Introdução](http://www.microsoft.com/brasil/technet/security/prodtech/windowsserver2003/quarantineservices/vppgch01.mspx)
-   [Capítulo 2 - Abordagens da quarentena da rede virtual privada](http://www.microsoft.com/brasil/technet/security/prodtech/windowsserver2003/quarantineservices/vppgch02.mspx)
-   [Capítulo 3 - Problemas e requisitos](http://www.microsoft.com/brasil/technet/security/prodtech/windowsserver2003/quarantineservices/vppgch03.mspx)
-   [Capítulo 4 - Projeto da solução](http://www.microsoft.com/brasil/technet/security/prodtech/windowsserver2003/quarantineservices/vppgch04.mspx)
-   [Apêndice A - Exemplos de scripts de quarentena](http://www.microsoft.com/brasil/technet/security/prodtech/windowsserver2003/quarantineservices/vppgappa.mspx)
-   [Apêndice B - Parâmetros dos Serviços de Quarentena de Acesso Remoto](http://www.microsoft.com/brasil/technet/security/prodtech/windowsserver2003/quarantineservices/vppgappb.mspx)
-   [Apêndice C - Links relacionados](http://www.microsoft.com/brasil/technet/security/prodtech/windowsserver2003/quarantineservices/vppgappc.mspx)
-   [Agradecimentos](http://www.microsoft.com/brasil/technet/security/prodtech/windowsserver2003/quarantineservices/vppgacks.mspx)

##### Download

[Guia de Planejamento de Implementação dos Serviços de Quarentena com VPN da Microsoft](http://go.microsoft.com/fwlink/?linkid=41308)

|                                                  |                                                                                                                                                                                                         |
|--------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [](#mainsection)[Início da página](#mainsection) | 1 de 9[![](images/Cc162926.pageRight(pt-br,TechNet.10).gif)](http://www.microsoft.com/brasil/technet/security/prodtech/windowsserver2003/quarantineservices/vppgch01.mspx) |
