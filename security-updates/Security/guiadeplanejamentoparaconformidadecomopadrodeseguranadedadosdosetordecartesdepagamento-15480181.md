---
TOCTitle: Guia de Planejamento para Conformidade com o Padrão de Segurança de Dados do Setor de Cartões de Pagamento
Title: Guia de Planejamento para Conformidade com o Padrão de Segurança de Dados do Setor de Cartões de Pagamento
ms:assetid: '6687efc1-44db-4015-ae35-d1a853dc8a06'
ms:contentKeyID: 15480181
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Bb821241(v=TechNet.10)'
---

Guia de Planejamento para Conformidade com o Padrão de Segurança de Dados do Setor de Cartões de Pagamento
==========================================================================================================

##### On This Page

[![Introdução](images/Bb821241.arrow_px_down(pt-br,TechNet.10).gif)](#ecaa)[Introdução](#ec)  
[]([![Atendendo aos requisitos do PCI DSS](images/Bb821241.arrow_px_down(pt-br,TechNet.10).gif)](#ebaa)[Atendendo aos requisitos do PCI DSS](#eb)  
[]([![Apêndices](images/Bb821241.arrow_px_down(pt-br,TechNet.10).gif)](#eaaa)[Apêndices](#ea)  
[](
### Introdução

O *Guia de Planejamento para Conformidade com o Padrão de Segurança de Dados do Setor de Cartões de Pagamento* foi criado para atender aos requisitos do PCI DSS (padrão de segurança de dados do setor de cartões de pagamento). Especificamente, este guia tem como alvo os comerciantes que aceitam cartões de pagamento, as instituições financeiras que processam transações com cartões de pagamento e os prestadores de serviços — empresas terceirizadas que fornecem serviços de processamento de cartões de pagamento ou de armazenamento de dados. As soluções de TI para cada um desses grupos devem atender a todos os requisitos do PCI DSS. O objetivo deste guia é ampliar o [*guia de planejamento para conformidade com os regulamentos*](http://www.microsoft.com/technet/security/guidance/complianceandpolicies/compliance/rcguide/default.mspx?mfr=true) (em inglês), que apresenta uma abordagem baseada em estruturas para criação de controles de TI como parte de seus esforços para estar em conformidade com diversos regulamentos e padrões. Também descreve as soluções de produtos e tecnologias Microsoft que podem ser usados para implementar uma série de controles de TI para ajudar a atender aos requisitos do PCI DSS, bem como qualquer outra obrigação regulamentar que a sua organização possa ter.

**Observação**   Se a sua organização oferece caixas eletrônicos como parte de seus serviços, a Microsoft fornece orientação de arquitetura e segurança para softwares, sistemas e redes com suporte para caixas eletrônicos. Para obter mais informações, consulte a página do [centro de downloads do setor bancário](http://msdn2.microsoft.com/en-us/architecture/86e3451d-8219-46af-bf99-4a610e4bf1f4.aspx) da Microsoft no site do MSDN.

Este guia não contém informações abrangentes sobre como manter a conformidade com o PCI DSS para todas as organizações. Para obter respostas para perguntas específicas sobre conformidade com relação à sua organização, entre em contato com o seu consultor jurídico ou auditor.

A introdução deste guia inclui as seguintes seções:

-   **Sinopse**. Esta seção fornece uma visão geral sobre os requisitos do PCI DSS e os objetivos principais do guia de planejamento. Ela aborda o conhecimento que os gerentes de TI precisam ter para começar a atender aos seus requisitos para conformidade com o PCI DSS.

-   **Quem deve ler este guia?** Esta seção descreve o público-alvo deste guia, seu propósito e escopo, além de advertências e avisos de isenção de responsabilidade sobre as limitações deste guia.

-   **O que é o padrão de segurança de dados do setor de cartões de pagamento?** Esta seção fornece uma visão geral sobre o PCI DSS e seus requisitos.

-   **Planejando a conformidade com o PCI DSS**. Esta seção apresenta como usar uma estrutura para satisfazer aos requisitos do PCI DSS. Essa abordagem inclui a criação de vários tipos de controles de TI, como esses controles funcionam em conjunto e por que são componentes importantes que a sua organização pode usar para atender aos requisitos do PCI DSS e outras obrigações de conformidade com regulamentos.

-   **O processo de auditoria do PCI DSS**. Esta seção fornece uma visão geral sobre o processo de auditoria do PCI DSS usado pelos auditores para avaliar a conformidade de uma organização com os requisitos do PCI DSS.

Como este informe oficial tem como objetivo complementar *o guia de planejamento para conformidade com os regulamentos* (em inglês), use esse guia como referência também quando planejar uma solução completa para atender a todos os requisitos de regulamentação aplicáveis à sua organização.

#### Sinopse

Se a sua organização processa, armazena ou transmite informações sobre titulares de cartão de pagamento, a sua empresa precisa estar em conformidade com o padrão de segurança de dados do setor de cartões de pagamento (PCI DSS). Os requisitos definidos nesses padrões, que foram desenvolvidos pelo PCI Security Standards Council, destinam-se a criar um nível de segurança mínimo aceitável para os titulares de cartão que usam os serviços da sua organização.

Três questões tornam essa situação complexa: A primeira é que estar em conformidade com os requisitos do PCI DSS pode ter um impacto em toda a sua organização. É importante coordenar os esforços em relação à conformidade em todos os departamentos, e ter uma estratégia para conformidade com o PCI DSS que englobe toda a empresa. A segunda complicação é que a sua organização pode precisar estar em conformidade com vários regulamentos, cada um regendo um conjunto distinto de requisitos. Obviamente, muitas empresas encontram dificuldades em entender como responder de modo apropriado a essa diversidade de requisitos regulamentares, usando ao mesmo tempo processos e procedimentos de baixo custo para manter sua conformidade com regulamentos. O terceiro fator de complexidade é que o PCI DSS menciona os controles de TI de modo superficial, assim como muitos outros regulamentos, deixando aos gerentes de TI a tarefa de determinar com exatidão o que eles devem fazem para atender e manter a conformidade com os regulamentos, com pouca orientação.

-   O *Guia de Planejamento para Conformidade com o Padrão de Segurança de Dados do Setor de Cartões de Pagamento* é orientado aos gerentes de TI responsáveis por atender às obrigações do PCI DSS de suas empresas. O objetivo deste guia é ajudar os gerentes de TI a entender como podem começar a atender a muitos dos requisitos de controle de TI que se aplicam às suas organizações, incluindo os requisitos para conformidade com o PCI DSS. Para alcançar esse objetivo, este guia fornece informações sobre soluções que você pode usar nesse processo.

-   Para obter uma descrição mais abrangente sobre como estar em conformidade com os diversos padrões regulamentares, consulte o [*guia de planejamento para conformidade com os regulamentos*](http://www.microsoft.com/technet/security/guidance/complianceandpolicies/compliance/rcguide/default.mspx?mfr=true).

**Importante**   Este guia de planejamento não fornece aconselhamento jurídico. Ele fornece apenas informações baseadas em fatos e técnicas sobre conformidade com regulamentos. Não dependa exclusivamente deste guia para obter aconselhamento sobre como atender aos seus requisitos de regulamentação. Para perguntas específicas, consulte seu consultor jurídico ou auditor.

#### Quem deve ler este documento:

O *Guia de Planejamento para Conformidade com o PCI DSS* tem como público-alvo principal os indivíduos que são responsáveis por garantir que a sua organização colete, processe, transmita e armazene os dados dos titulares de cartão de modo seguro e confiável, mantendo a privacidade do portador do cartão. O público-alvo deste guia inclui gerentes de TI que ocupam as seguintes posições em suas organizações:

-   **Diretores de Informática (CIOs)** preocupados com a implantação e a operação de sistemas e com os processos relacionados com TI.

-   **Diretor de Segurança das Informações (CISOs)** preocupados com o programa geral de segurança das informações e a conformidade com as diretivas de segurança das informações.

-   **Diretores financeiros (CFOs)** preocupados com o ambiente geral de controle de suas organizações.

-   **Diretores de Privacidade (CPOs)** responsáveis pela implementação de diretivas relacionadas ao gerenciamento de informações pessoais, incluindo diretivas que dão suporte à conformidade com leis de proteção de dados e privacidade.

-   **Responsáveis pelas decisões técnicas** que determinam as soluções tecnológicas apropriadas para resolver alguns problemas comerciais.

-   **Gerentes de operações de TI** que administram os sistemas e os processos que executam o programa de conformidade com o PCI DSS.

-   **Arquitetos de segurança de TI** que criam os sistemas de controle de TI e segurança que fornecem um nível de segurança apropriado para atender às necessidades comerciais de suas organizações.

-   **Arquitetos de infra-estrutura de TI** que criam infra-estruturas que podem dar suporte à segurança de TI e aos controles projetados por Arquitetos de segurança de TI.

-   **Consultores e parceiros** que aconselham ou implementam práticas recomendadas de privacidade e segurança para alcançar os objetivos de conformidade com o PCI DSS de seus clientes.

Além desse público-alvo, os profissionais a seguir também podem ter interesse neste guia:

-   **Diretores de risco/conformidade** responsáveis pelo gerenciamento de risco geral para atender aos requisitos do PCI DSS em suas organizações.

-   **Gerentes de auditoria de TI** preocupados com os sistemas de auditoria de TI e em reduzir a carga de trabalho dos auditores de TI internos e externos.

#### O que é o padrão de segurança de dados do setor de cartões de pagamento?

O padrão de segurança de dados do setor de cartões de pagamento é um conjunto abrangente de requisitos criados para garantir que as informações do cartão de crédito e débito do portador do cartão permaneçam protegidas, independentemente de como ou onde sejam coletadas, processadas, transmitidas e armazenadas. Desenvolvido pelos membros fundadores do PCI Security Standards Council — incluindo American Express, Discover Financial Services, JCB, MasterCard Worldwide e Visa International — o PCI DSS destina-se a encorajar a adoção internacional de medidas de segurança de dados uniformes.

Os requisitos do PCI DSS são endereçados a empresas e organizações que lidam com dados de titulares de cartão em suas operações diárias. Especificamente, o PCI DSS define requisitos para instituições financeiras, comerciantes e prestadores de serviços que lidam com dados de titulares de cartão durante todo um dia de transações comerciais normais. O PCI DSS é formado por uma lista de requisitos para gerenciamento de segurança, diretivas, procedimentos, arquitetura de rede, design de software e outras medidas para proteção dos dados de titulares de cartão.

O PCI DSS versão 1.1 é a versão mais recente do padrão, lançada em setembro de 2006. Ele é organizado em um grupo de seis princípios e doze requisitos. Cada requisito contém sub-requisitos para os quais você deve implementar processos, diretivas ou soluções de tecnologia para estar em conformidade com o requisito. As diretivas e os requisitos do PCI DSS incluem:

-   Construir e manter uma rede segura

    -   Requisito 1: Instalar e manter uma configuração de firewall para proteger os dados de titulares de cartão.

    -   Requisito 2: Não usar senhas padrão de sistema e outros parâmetros de segurança criados pelo fornecedor.

-   Proteger os dados de titulares de cartão

    -   Requisito 3: Proteger os dados armazenados de titulares de cartão.

    -   Requisito 4: Criptografar a transmissão de dados de titulares de cartão em redes públicas abertas.

-   Manter um programa de gerenciamento de vulnerabilidade

    -   Requisito 5: Usar e atualizar regularmente o software antivírus.

    -   Requisito 6: Desenvolver e manter sistemas e aplicativos seguros.

-   Implementar medidas eficientes de controle de acesso

    -   Requisito 7: Restringir o acesso aos dados de titulares de cartão aos que realmente precisam deles para trabalhar.

    -   Requisito 8: Atribuir um ID exclusivo a cada pessoa com acesso a um computador.

    -   Requisito 9: Restringir o acesso físico aos dados de titulares de cartão.

-   Monitorar e testar as redes regularmente

    -   Requisito 10: Controlar e monitorar todos os acessos aos recursos de rede e aos dados de titulares de cartão.

    -   Requisito 11: Testar regularmente os sistemas e os processos de segurança.

-   Manter uma diretiva de segurança das informações

    -   Requisito 12: Manter uma diretiva que aborde a segurança das informações.

Os requisitos 9 e 12 não requerem que você implemente soluções tecnológicas. O requisito 9 o instrui a abordar a segurança física dos locais onde os dados de titulares de cartão são armazenados e processados. Isso pode incluir a implementação de segurança no acesso ao edifício, a instalação e a manutenção de equipamento de vigilância, e a verificação de identidade de todos que trabalhem em suas instalações ou as visitem. O requisito 12 o orienta sobre como criar uma diretiva de segurança das informações e difundi-la entre seus funcionários, fornecedores e outras pessoas da sua organização que trabalhem com dados de titulares de cartão.

#### Planejando a conformidade com o PCI DSS

Não é nem eficiente nem econômico criar sozinho suas soluções para conformidade com o PCI DSS. Existem vários outros regulamentos que devem ser considerados quando você planejar a sua abordagem com relação à conformidade com os requisitos do PCI DSS. Eis um exemplo desses regulamentos:

-   Lei americana Sarbanes-Oxley (SOX)

-   Lei americana Gramm-Leach-Bliley (GLBA)

-   Lei americana HIPAA (Health Insurance Portability Accountability Act)

-   Diretiva de Proteção de Dados da União Européia (EUDPD)

-   ISO 17799:2005 Código de Práticas de Gestão de Segurança das Informações (ISO 17799)

**Observação**   Se a sua organização é uma empresa multinacional, você precisa estar em conformidade com os regulamentos de todas as nações em que sua empresa está presente. A Microsoft sugere que você consulte seu departamento jurídico para ter conhecimento de todos os regulamentos dos locais onde sua empresa opera.

Para obter mais informações sobre o planejamento dos esforços em relação à conformidade com todos esses regulamentos, consulte o [*guia de planejamento para conformidade com os regulamentos*](http://www.microsoft.com/technet/security/guidance/complianceandpolicies/compliance/rcguide/default.mspx?mfr=true).

As soluções de conformidade com o PCI DSS criadas pela sua organização devem ser desenvolvidas com conhecimento total dos seguintes itens:

-   As soluções atuais existentes que satisfazem a outros requisitos de regulamentação

-   Os métodos mais eficazes de criar novas soluções que atendam a todos os requisitos de regulamentação

Para alcançar os seus objetivos de conformidade com eficiência, a Microsoft recomenda que você use uma estrutura de controle para ajudar a cumprir os objetivos de conformidade com regulamentos da sua organização. O uso de uma estrutura de controle permite que a sua organização mapeie os regulamentos e os padrões aplicáveis à estrutura. Dessa forma, a sua organização poderá focalizar com maior eficiência seus esforços de controle de TI para atender aos requisitos definidos na estrutura, em vez de regulamentos individuais.

Além disso, como os novos regulamentos e padrões afetam a organização, você pode mapeá-los em relação à estrutura e então concentrar seus esforços nas partes da estrutura em que os requisitos foram alterados. Você também pode mapear uma ampla variedade de requisitos baseados em controle de TI em relação à estrutura, incluindo requisitos específicos do setor, como os requisitos de segurança do setor de cartões de pagamento, diretivas internas e assim por diante.

O uso de uma estrutura proporciona muitos benefícios significativos para organizações que anseiam por atingir seus objetivos de conformidade com os regulamentos. A abordagem baseada em estrutura para conformidade com regulamentos permite que as organizações:

-   Combinem os controles de TI para atender aos vários padrões regulamentares, como os do PCI DSS e do EUDPD, para evitar auditorias separadas.

-   Atendam aos novos regulamentos com rapidez, assim que são introduzidos.

-   Priorizem os gastos ao escolher os controles de TI que terão maior impacto.

-   Evitem trabalho dobrado para atender aos objetivos de conformidade em diferentes unidades de negócios dentro da mesma empresa.

-   Atualizem os regulamentos atuais com maior eficiência, por meio de alterações incrementais aos controles de TI existentes na sua organização.

-   Estabeleçam um denominador comum entre o departamento de TI e os auditores.

Obviamente, você deve analisar pessoalmente o PCI DSS antes de dar início aos seus esforços em relação à conformidade. Você pode baixar o PCI DSS em <https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf> (em inglês). Além disso, o PCI Security Standards Council criou um questionário de auto-avaliação que pode ajudar a sua organização a determinar se está em conformidade com o PCI DSS. Ele também pode ser usado para ajudá-lo a planejar os esforços da sua organização em relação à conformidade com o PCI DSS. Você pode baixar o questionário de auto-avaliação do PCI DSS em <https://www.pcisecuritystandards.org/pdfs/pci_saq_v1-0.pdf> (em inglês).

Para obter mais informações sobre como atender aos requisitos de regulamentação usando controles de TI em uma estrutura de controle, consulte *o guia de planejamento para conformidade com* os *regulamentos*.

#### O processo de auditoria do PCI DSS

O processo de auditoria para conformidade com o PCI DSS é muito semelhante ao processo definido no [*guia de planejamento para conformidade com os regulamentos*](http://www.microsoft.com/technet/security/guidance/complianceandpolicies/compliance/rcguide/default.mspx?mfr=true). Entretanto, existem alguns detalhes específicos à auditoria do PCI DSS que você deve saber.

As verificações de auditoria do PCI DSS são realizadas por dois tipos de empresas de terceiros, conhecidas como QSAs (Qualified Security Assessors, assessores de segurança qualificados) e ASVs (Approved Scanning Vendors, agentes de verificação aprovados). Os QSAs se encarregam da parte local da auditoria, enquanto os ASVs realizam as verificações de vulnerabilidade dos ambientes de Internet da sua organização. As empresas que se tornam QSAs e ASVs precisam ser examinadas e aprovadas pelo PCI Data Security Council (PCI DSC) anualmente.

O QSA é necessário para preparar um relatório após a auditoria da sua organização e esse relatório deve seguir orientações específicas definidas pelo PCI DSC. Essas orientações são apresentadas em um documento de procedimentos de auditoria do PCI, que você pode baixar em <https://www.pcisecuritystandards.org/pdfs/pci_audit_procedures_v1-1.pdf> (em inglês). Elas especificam como deve ser organizado o relatório apresentado pelo QSA após a auditoria. Esse relatório inclui as informações de contato da sua organização, a data da auditoria, uma sinopse, uma descrição do escopo do trabalho e da abordagem que o QSA usou na auditoria da sua organização, os resultados de verificação trimestrais, bem como as conclusões e as observações do QSA. A última seção contém a maior parte das informações sobre a conformidade da sua organização com o PCI DSS. Nela, o QSA usa um modelo para avaliar a conformidade da sua organização com cada um dos requisitos e sub-requisitos do PCI DSS.

Antes de agendar auditorias de PCI DSS para a sua organização, ou, melhor ainda, conforme estiver planejando a sua conformidade com o PCI DSS, os principais membros da sua organização devem analisar os procedimentos de auditoria do PCI DSS. Isso pode ajudar a compreender exatamente o que o QSA analisará durante a auditoria.

O ASV também deve preparar um relatório sobre os resultados das verificações de vulnerabilidade dos ambientes de Internet da sua organização. As orientações para esse relatório encontram-se em um documento de procedimentos de verificação de auditoria do PCI, que você pode baixar em <https://www.pcisecuritystandards.org/pdfs/pci_scanning_procedures_v1-1.pdf> (em inglês). Esse documento especifica os elementos do ambiente da sua organização que o ASV deve verificar e inclui uma legenda que o ajudará a ler e interpretar o relatório do ASV.

Como comerciante ou prestador de serviços, a sua organização deve seguir os requisitos de relatório de conformidade de cada empresa de cartão de pagamento para garantir que cada uma compreenda o status de conformidade da sua organização. Em outras palavras, se a sua organização é um prestador de serviços que lida com dados de titulares de cartão associados a Visa e American Express, você deve enviar seus relatórios de conformidade para o Visa e o American Express.

Cada empresa de cartão de pagamento possui regras e procedimentos de conformidade distintos. Para obter mais informações sobre requisitos específicos para conformidade com o PCI DSS e os programas de suporte que cada empresa oferece para permitir a conformidade do comerciante ou prestador de serviços, entre em contato com as empresas de cartão de pagamento para as quais a sua organização processa, transmite ou armazena dados de titulares de cartão.

[![](images/Bb821241.arrow_px_up(pt-br,TechNet.10).gif)](#mainsection)[Top Of Page](#mainsection)

### Atendendo aos requisitos do PCI DSS

Esta seção detalha as soluções tecnológicas da Microsoft que a sua organização pode considerar ao planejar a conformidade com o PCI DSS. Você deve incorporar as soluções que escolher nas operações diárias da sua organização. Conforme mencionado na seção Planejando a conformidade com o PCI DSS, as diretivas organizacionais, os procedimentos e as soluções tecnológicas devem levar em consideração a conformidade com regulamentos em toda a organização e você deve considerar como a conformidade com o PCI DSS afetará todas as partes da sua empresa.

Para obter uma descrição detalhada sobre as considerações envolvidas no mapeamento dos controles de TI em relação às soluções tecnológicas, consulte o [*guia de planejamento para conformidade com os regulamentos*](http://www.microsoft.com/technet/security/guidance/complianceandpolicies/compliance/rcguide/default.mspx?mfr=true).

#### Gerenciamento de documentos

As soluções de gerenciamento de documentos combinam softwares e processos para ajudá-lo a gerenciar as informações não estruturadas da sua organização. Essas informações podem existir em vários formatos digitais, incluindo documentos, imagens, arquivos de áudio e vídeo, e arquivos XML.

##### Requisitos do PCI DSS atendidos

A implementação de soluções de gerenciamento de documentos ajuda na conformidade com o PCI DSS de duas formas. Primeiro, usar essas soluções para gerenciar documentos que contêm dados de titulares de cartão pode ajudar a atender aos requisitos do PCI DSS relacionados a acesso, gerenciamento e proteção de dados. Especificamente, você pode usar as soluções de gerenciamento de documentos para atender ao requisito 7 e ao sub-requisito 10.2.1. Segundo, você pode usar os sistemas de gerenciamento de documentos para manter e publicar diretivas como as exigidas nas seções 3.6, 6.4, 9.2 e 12.  

Para obter o texto completo desses requisitos, consulte o [*PCI DSS (Payment Card Industry Data Security Stantard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece algumas tecnologias que você pode usar em conjunto e separadamente para criar controles de TI para gerenciamento de documentos. Você deve projetar esses controles para atender aos requisitos do PCI DSS, bem como a quaisquer outros requisitos de regulamentação aplicáveis à sua organização.

-   **Microsoft® Windows® Rights Management Services**. O RMS (Windows Rights Management Services) é uma plataforma de software que auxilia os aplicativos a proteger informações digitais contra uso não autorizado — tanto online como offline e dentro e fora do firewall. O RMS é a tecnologia de base por trás dos recursos de IRM (Information Rights Management) do Microsoft Office e do Windows SharePoint® Services. É necessário um servidor RMS, seja implantado internamente ou acessado por meio de um serviço hospedado, para usar esses recursos.

    O RMS pode ampliar a estratégia de segurança da sua organização protegendo as informações através de diretivas de uso persistentes, que permanecem com as informações, independentemente de seu destino. Os aplicativos compatíveis com RMS podem ser usados para gerenciar e controlar o acesso a documentos que contenham informações sobre o titular de cartão, bem como para fazer auditoria desse acesso. O cliente RMS está integrado ao sistema operacional Windows Vista™. Para outras versões do Windows, o cliente RMS está disponível para download gratuito.
    Para obter mais informações, consulte a página do [Windows Rights Management Services](http://www.microsoft.com/rms) em <http://www.microsoft.com/rms> (pode estar em inglês).  

-   **Microsoft Office SharePoint Server**. O SharePoint Server é um servidor de colaboração e gerenciamento de conteúdo que permite que você tenha uma plataforma integrada para dar suporte às necessidades de gerenciamento de documentos e portal da sua organização. Ele permite que você ofereça suporte a aplicativos de intranet, extranet e Web em toda a empresa e oferece aos seus profissionais de TI e desenvolvedores a plataforma e as ferramentas de que precisam para administração de servidores, expansibilidade de aplicativos e interoperabilidade. O SharePoint Server pode ser usado como um repositório central para documentos que contêm dados de titulares de cartão, bem como para documentos que descrevem diretivas e processos. O SharePoint Server 2007 está integrado ao RMS, de forma que as diretivas de controle de acesso possam ser aplicadas a todas as cópias de conteúdo baixadas do SharePoint Server 2007. Esse recurso permite aos administradores de site proteger os downloads contra uma biblioteca de documentos com IRM. Quando um usuário tenta baixar um arquivo da biblioteca, o Microsoft Windows SharePoint Services verifica se o usuário possui permissões para o determinado arquivo e emite uma licença que permite que ele acesse o arquivo dentro do nível de permissões apropriado. Então, o Windows SharePoint Services baixa o arquivo para o computador do usuário em um formato criptografado e com direitos gerenciados.
    Para obter mais informações, consulte o site sobre [produtos e tecnologias Microsoft SharePoint](http://go.microsoft.com/fwlink/?linkid=12632) em <http://go.microsoft.com/fwlink/?linkid=12632> (pode estar em ingles).

-   **Microsoft Exchange Server**. Para a maioria das empresas hoje em dia, o email é a ferramenta de comunicação fundamental usada pelos funcionários para obter os melhores resultados. Essa grande dependência no email aumentou o número de mensagens enviadas e recebidas, a quantidade e variedade de trabalho realizado via email e até mesmo a própria velocidade nos negócios. O Exchange Server oferece uma rica plataforma de mensagens para gerenciar a troca de informações na sua organização, ao mesmo tempo em que ajuda a alcançar os objetivos de conformidade com o PCI DSS. O Exchange Server 2007 inclui mensagens unificadas, o que consolida as mensagens de email, voz e fax enviadas a um usuário em uma única caixa de entrada. Ele também oferece recursos que permitem que a sua organização aplique regras de retenção, verifique e execute ações com relação a mensagens em transporte, crie diários com flexibilidade e realize pesquisas em rich text em todas as caixas de correio implantadas.
    Para obter mais informações, consulte o site do Microsoft Exchange Server em <http://www.microsoft.com/exchange/default.mspx> (pode estar em inglês).

-   **Microsoft Office**. O Office é o principal pacote de aplicativos de produtividade para empresas. O recurso de IRM do Microsoft Office ajuda as organizações a controlar o acesso a informações confidenciais, como dados de titulares de cartão.

    Mais especificamente o recurso de IRM do Office ajuda a sua organização ao:

    -   Prevenir que um destinatário autorizado de informações protegidas encaminhe, copie, modifique, imprima, envie como fax ou corte e cole as informações para uso não autorizado.

    -   Impedir que informações protegidas sejam copiadas com a função Windows Print Screen.

    -   Fornecer informações com o mesmo nível de proteção independentemente de seu destino. Isso é conhecido como *proteção persistente*.

    -   Fornecer o mesmo nível de proteção aos anexos de email, desde que os anexos sejam arquivos criados com outros programas do Office, como Microsoft Excel® ou Microsoft Word.

    -   Proteger informações em mensagens de email ou documentos que tenham sido definidas para expirar, de forma que as informações não possam ser visualizadas após determinado período de tempo.

    -   Aplicar diretivas corporativas que controlam o uso e a difusão de informações dentro e fora da empresa.

    Para obter mais informações, consulte o site do Microsoft Office em <http://office.microsoft.com/en-us/default.aspx>.

#### Avaliação de riscos

Avaliação de riscos é o processo pelo qual a sua organização identifica e prioriza os riscos aos seus negócios. Normalmente, você usa um método sistemático para identificar os ativos de um sistema de processamento de informações, as ameaças a esses ativos e a vulnerabilidade do sistema frente a essas ameaças. No contexto da conformidade com regulamentos, a avaliação de riscos é o processo de avaliar o nível de conformidade e as inadequações de conformidade dentro da sua organização. Ao planejar a conformidade com o PCI DSS, sua principal preocupação será identificar os riscos aos dados de titulares de cartão e priorizar essas ameaças.

##### Requisitos do PCI DSS atendidos

A avaliação de riscos pode ajudar a atender aos requisitos do PCI DSS de várias maneiras. Permite identificar as áreas da sua rede que precisam ser atualizadas para entrar em conformidade. Mesmo depois de ter obtido uma conformidade inicial, a avaliação de riscos é importante para determinar se a sua organização continua em conformidade com o passar do tempo. Como a avaliação de riscos pode ser usada para lidar com alguns problemas potenciais, ela também pode ajudá-lo a entrar em conformidade com vários requisitos do PCI DSS, incluindo os requisitos 1, 3, 4, 5, 6, 7, 8 e 11.

Para obter o texto completo desses requisitos, consulte o [*PCI DSS (Payment Card Industry Data Security Stantard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece algumas tecnologias que você pode usar em conjunto e separadamente para criar controles de TI para avaliação de riscos. Você deve projetar esses controles para atender aos requisitos do PCI DSS, bem como a quaisquer outros requisitos de regulamentação aplicáveis à sua organização.

-   **Microsoft Baseline Security Analyzer (MBSA)**. Uma das principais ferramentas que você pode usar para avaliar o risco aos dados de titulares de cartão na sua organização é o MBSA. O MBSA é uma ferramenta fácil de usar que identifica problemas comuns de configuração de segurança em vários produtos da Microsoft, incluindo sistemas operacionais Microsoft Windows, Serviços de Informações da Internet (IIS), SQL Server™, Microsoft Internet Explorer® e Microsoft Office. O MBSA também verifica atualizações de segurança, conjuntos de atualizações e service packs ausentes que tenham sido publicados no Microsoft Update. Você pode executar o MBSA a partir do prompt de comando ou de sua interface gráfica do usuário, além de usá-lo com o Microsoft Update e o Microsoft Windows Server® Update Services. Como a atualização de seus sistemas é muito importante para proteger os dados de titulares de cartão, o MBSA pode ser uma ferramenta inestimável na avaliação de risco de dados na sua organização.

    Para obter mais informações sobre o MBSA, consulte a página do Microsoft Baseline Security Analyzer em <http://www.microsoft.com/technet/security/tools/mbsahome.mspx>.

-   **Microsoft Systems Management Server**. Se a sua organização usa o SMS (Systems Management Server) para gerenciar computadores cliente e servidores, você já deve ter algumas das ferramentas de que precisa para realizar uma avaliação de riscos de dados de titulares de cartão. Com o SMS, a sua organização pode gerenciar remotamente as configurações de segurança em computadores que executam sistemas operacionais Windows em redes distribuídas. Você pode criar um inventário com os computadores da sua rede que receberam as atualizações de software necessárias e acompanhar o andamento das atualizações distribuídas a esses computadores. O SMS também permite que você gere relatórios que identifiquem seu inventário completo de hardware e software, os detalhes de configuração e o status dos computadores na sua rede, bem como o status das implantações de software e erros de implantação. Esses recursos do SMS podem ser muito importantes na avaliação de riscos de dados de titulares de cartão dentro da sua organização.

    Para obter mais informações sobre o SMS, consulte a página do Microsoft Systems Management Server em <http://www.microsoft.com/smserver/default.mspx> (pode estar em inglês).

-   **Coleta de auditoria para o Microsoft System Center Operations Manager**. O Operations Manager 2007 pode extrair e coletar de modo seguro e eficiente logs de segurança de sistemas operacionais Windows e armazená-los para posterior análise e relatório. Os logs extraídos são armazenados em um banco de dados de coleta de auditoria separado. O Operations Manager será acompanhado de relatórios que podem ser usados para os dados de coleta de auditoria. A coleta de auditoria pode ser usada para gerar vários relatórios de conformidade, como as auditorias de suporte Sarbanes-Oxley. Além disso, ela também pode ser usada para análises de segurança, como detecção de intrusão e tentativas de acesso não autorizado.

    Para obter mais informações, consulte a página sobre os serviços de coleta de auditoria em <http://technet.microsoft.com/en-us/library/bb381258.aspx> (pode estar em inglês).

-   **Windows Server Update Services**.** **O Windows Server Update Services com Service Pack 1 permite que a sua organização implante muitas das últimas atualizações de produto da Microsoft publicadas no site Microsoft Update. O Windows Server Update Services é um componente de atualização do Windows Server e oferece um modo eficaz e rápido de ajudar a manter os sistemas atualizados. O WSUS oferece uma infra-estrutura de avaliação de riscos que consiste no seguinte:

    -   **Microsoft Update**. O site da Microsoft ao qual os componentes do WSUS se conectam para baixar atualizações de produtos da Microsoft.

    -   **Servidor Windows Server Update Services**. O componente de servidor instalado em um computador que executa o sistema operacional Microsoft Windows 2000 Server com Service Pack 4 (SP4) ou Windows Server 2003 dentro do firewall corporativo. O servidor Windows Server Update Services oferece os recursos de que os administradores precisam para gerenciar e distribuir atualizações por meio de uma ferramenta baseada na Web, que pode ser acessada pelo Internet Explorer ou qualquer computador com Windows na rede corporativa. Além disso, um servidor Windows Server Update Services pode ser a fonte de atualização para outros servidores Windows Server Update Services.

    -   **Atualizações Automáticas**. O componente do computador cliente incorporado aos sistemas operacionais Microsoft Windows Vista, Windows Server 2003, Windows XP e Windows 2000 com Service Pack 3. O recurso Atualizações Automáticas permite que tanto o servidor como o computador cliente recebam atualizações do Microsoft Update ou de um servidor que executa Windows Server Update Services.

    Esses serviços permitem que você forneça as últimas correções de segurança da Microsoft a todos os ambientes de host da sua rede para os produtos instalados naquele host.  

    Para obter mais informações, consulte a página do Windows Server Update Services em <http://www.microsoft.com/windowsserversystem/updateservices/default.mspx> (pode estar em inglês)

-   **Diretiva de Grupo**. Diretiva de Grupo é uma infra-estrutura que permite que os seus profissionais de TI implementem configurações específicas para usuários e computadores. As configurações de Diretiva de Grupo estão contidas nos GPOs (Objetos de Diretiva de Grupo), que estão relacionados aos seguintes contêineres do serviço de diretório Active Directory®: sites, domínios ou UOs (unidades organizacionais). Você pode gerenciar centralmente os computadores em uma rede distribuída usando Diretiva de Grupo. Como os seus administradores podem usar a Diretiva de Grupo para distribuir software em um site, domínios ou unidades organizacionais, ela pode ser uma importante ferramenta para determinar os riscos potenciais do ambiente de TI da sua organização.

    Você pode usar o GPMC (Console de Gerenciamento de Diretiva de Grupo) da Microsoft para gerenciar as configurações de Diretiva de Grupo. O GPMC foi criado para simplificar o gerenciamento da Diretiva de Grupo fornecendo um único local para gerenciar os principais aspectos dela. O GPMC aborda os principais requisitos de implantação de Diretiva de Grupo, conforme solicitado pelos clientes, fornecendo:

    -   Uma interface de usuário que facilita o uso de Diretiva de Grupo.

    -   A capacidade de fazer backup e restaurar GPOs.

    -   A capacidade de importar e exportar, assim como de copiar e colar GPOs e filtros WMI (Instrumentação de Gerenciamento do Windows).

    -   Um modo simplificado de gerenciar a segurança relacionada a Diretiva de Grupo.

    -   A capacidade de gerar relatórios em HTML para configurações de GPO e dados de RSoP (conjunto de diretivas resultantes).

    -   A capacidade de criar scripts de operações de GPO expostas pelo GPMC — mas não a capacidade de criar configurações de script dentro de um GPO.

    Para obter mais informações, consulte a página sobre a diretiva de grupo do Windows Server 2003 em <http://technet2.microsoft.com/windowsserver/en/technologies/featured/gp/default.mspx> (pode estar em inglês) e a apresentação do Console de Gerenciamento de Diretiva de Grupo em <http://www.microsoft.com/windowsserver2003/gpmc/gpmcintro.mspx> (pode estar em inglês).

#### Gerenciamento de alterações

O gerenciamento de alterações é um processo estruturado através do qual sua organização avalia as alterações em um plano de projeto, uma infra-estrutura de TI, implantações de software ou outros processos ou procedimentos na sua organização. Um sistema de gerenciamento de alterações pode ajudá-lo a definir uma alteração, avaliar o impacto da alteração, determinar as ações necessárias para implementar a alteração e difundir as informações sobre a alteração por toda a sua organização. E também pode ajudá-lo a controlar as alterações que faz em toda a organização. Isso permite manter seu ambiente de TI sob controle enquanto faz suas alterações.

Por exemplo, o sistema de uma organização pode ter um banco de dados para auxiliar os funcionários a tomar melhores decisões sobre alterações futuras, tomando como base o histórico de dados indicando o sucesso ou o fracasso de alterações semelhantes que foram feitas no passado. O gerenciamento de alterações também é um processo estruturado que comunica a existência e o status de alterações a todas as partes afetadas. O processo pode gerar um sistema de inventário que indica que ações foram tomadas e quando as ações afetam o status de recursos importantes, ajudando a prever e eliminar problemas e a simplificar o gerenciamento de recursos.

##### Requisitos do PCI DSS atendidos

O gerenciamento de alterações é fundamental para a conformidade com o PCI DSS, assim como para quaisquer outros esforços em relação à conformidade com regulamentos. Se a sua organização não sabe quais alterações foram feitas ao seu ambiente de TI, é difícil afirmar que o ambiente é seguro. O controle das alterações na rede, nos sistemas, nas diretivas e nos procedimentos ajuda a atender aos requisitos 6 e 11 do PCI DSS.

Para obter o texto completo desses requisitos, consulte o [*PCI DSS (Payment Card Industry Data Security Stantard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece várias tecnologias que você deve considerar ao projetar suas soluções de gerenciamento de alterações.

-   **Microsoft Office SharePoint Server**. Além de ser uma opção de tecnologia para suas soluções de gerenciamento de documentos, o Microsoft Office SharePoint Server também pode ser um elemento-chave no sistema de gerenciamento de alterações da sua organização. Você pode usar seus recursos de verificação de versão para monitorar as alterações nos documentos de diretivas e processos, atualizações e outras alterações a aplicativos, além de alterações em software aprovado com o passar do tempo.

    Para obter mais informações, consulte a seção sobre gerenciamento de documentos no site de [produtos e tecnologias Microsoft SharePoint](http://go.microsoft.com/fwlink/?linkid=12632) em <http://go.microsoft.com/fwlink/?linkid=12632>.

-   **Microsoft Systems Management Server**. Além de usar o SMS para gerenciar a avaliação de riscos para a sua organização, você também pode usar seus recursos de gerenciamento para controlar as alterações nos sistemas de computadores em toda a sua organização. Ele controlará as alterações de configuração de segurança e também os aplicativos instalados nos servidores e computadores cliente em toda a rede. Além disso, você pode usar a eficiente funcionalidade de relatório integrada do SMS para revisar as alterações feitas nos computadores da organização e verificar se elas atendem aos requisitos de segurança estabelecidos.

    Para obter mais informações sobre o SMS, consulte a página do Microsoft Systems Management Server em <http://www.microsoft.com/smserver/default.mspx> (pode estar em inglês).

-   **Microsoft SMS 2003 Desired Configuration Monitoring 2.0**. Você pode ampliar as operações do SMS com o recurso DCM (Desired Configuration Monitoring) do SMS 2003. O DCM pode ser usado para automatizar as auditorias de monitoramento de configuração entre configurações desejadas ou definidas e configurações reais. O DCM faz isso permitindo que o usuário defina as configurações desejadas de hardware, sistema operacional e aplicativo em várias fontes de dados de configuração. Em seguida, usando o mecanismo de auditoria fornecido, o DCM compara as configurações desejadas com as configurações reais e cria um relatório de conformidade de configuração.

    O DCM pode ajudá-lo a reduzir o tempo de inatividade de serviço não planejado, correlacionar os dados de configuração e reduzir os custos de suporte. Ele oferece uma ferramenta de edição de XML fácil de utilizar e orientação para definir os itens de configuração de hardware e software. Além disso, o DCM também fornece relatórios de conformidade detalhados para auxiliá-lo na detecção e correção de erros de configuração.

-   **Microsoft Desktop Optimization Pack para Software Assurance**. O Microsoft Desktop Optimization Pack para Software Assurance é um serviço de assinatura que reduz os custos de implantação do aplicativo, permite a entrega de aplicativos como serviços, e oferece melhor gerenciamento e controle de ambientes desktop empresariais. O Desktop Optimization Pack permite que você aprimore os processos e as reversões de gerenciamento de alterações por meio de:

    -   Gerenciamento de Diretiva de Grupo aprimorado.

    -   Tempo de inatividade reduzido.

    -   Acesso por demanda a aplicativos para usuários aprovados.

    O Microsoft Desktop Optimization Pack está disponível apenas para clientes com cobertura Software Assurance em seus desktops. Para obter mais informações, consulte a página sobre como otimizar a área de trabalho do Windows em <http://www.microsoft.com/windows/products/windowsvista/buyorupgrade/optimizeddesktop.mspx> (pode estar em inglês).

#### Segurança de rede

As soluções de segurança de rede constituem uma ampla categoria de soluções desenvolvida para abordar a segurança de todos os aspectos da rede da organização, incluindo firewalls, servidores, clientes, roteadores, comutadores e pontos de acesso. O planejamento e o monitoramento da segurança da rede da sua organização consistem em um elemento fundamental para estar em conformidade com o PCI DSS. Embora exista uma ampla variedade de soluções disponíveis para abordar a segurança de rede, a sua organização provavelmente já deve ter muitos dos elementos que tornam uma rede segura. É muito mais eficiente e econômico trabalhar a partir das soluções de segurança de rede que você já tenha implementado do que começar do zero.

Entretanto, você deve considerar fazer alterações em algumas das tecnologias usadas por sua organização, ou convém implementar novas soluções que ainda não tenha incluído na sua estratégia de segurança de rede. A Microsoft oferece várias soluções de tecnologia e materiais de referência para implementar soluções de segurança de rede que atendam às necessidades da sua organização.

##### Requisitos do PCI DSS atendidos

O padrão de segurança de dados do setor de cartões de pagamento é muito claro em relação à necessidade de estabelecer redes seguras em toda a organização para estar em conformidade. A diretiva 1 afirma que para estar em conformidade, uma organização deve criar e manter uma rede segura. O requisito 1 afirma que as organizações devem instalar e manter uma configuração de firewall para proteger os dados de titulares de cartão. O requisito 2 afirma que as organizações devem alterar as configurações padrão do fornecedor para senhas de sistema e outros parâmetros de segurança. As soluções de segurança de rede também ajudam a sua organização a atender aos requisitos 4 e 10, que exigem que você criptografe a transmissão de dados de titulares de cartão em toda a rede e que controle e monitore todos os acessos de rede, respectivamente.

Para obter o texto completo desses requisitos, consulte o [*PCI DSS (Payment Card Industry Data Security Stantard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece algumas tecnologias à sua escolha para atender aos dois primeiros requisitos do PCI DSS.

-   **Microsoft Windows Firewall**. O Windows XP Service Pack 2 (SP2) inclui o Windows Firewall, que substituiu o ICF (Firewall de conexão com a Internet). O Windows Firewall é um firewall com monitoração de estado baseado em host que elimina o tráfego recebido não solicitado que não corresponde ao tráfego enviado em resposta a uma solicitação do computador (tráfego solicitado) ou tráfego não solicitado que foi especificado como permitido (tráfego excetuado). O Windows Firewall oferece um nível de proteção contra usuários e programas mal-intencionados que usam tráfego recebido não solicitado para atacar computadores em uma rede. Esses recursos foram aprimorados no Windows Firewall com Segurança Avançada no Windows Vista e Windows Server ”Longhorn”.

    O Windows Firewall com Segurança Avançada permite que você bloqueie conexões de entrada e de saída com base nas configurações feitas através do snap-in do MMC (Console de Gerenciamento Microsoft). Esse snap-in não só oferece uma interface para configurar o Windows Firewall localmente, como também para configurá-lo em computadores remotos usando Diretiva de Grupo. As funções do firewall agora estão integradas às configurações de proteção do protocolo IPsec, reduzindo a possibilidade de conflito entre os dois mecanismos de proteção. O Windows Firewall com Segurança Avançada dá suporte a perfis separados para quando os computadores estão associados a um domínio ou conectados a uma rede privada ou pública. Ele também dá suporte à criação de regras para aplicação de diretivas de isolamento de servidor e domínio. O Windows Firewall com Segurança Avançada dá suporte a regras mais granulares, incluindo usuários e grupos do Microsoft Active Directory, endereços de IP de origem e de destino, número de porta IP, configurações de ICMP, configurações de IPsec, tipos específicos de interfaces, serviços e muito mais.

    Para obter mais informações, consulte a página do Windows Firewall em <http://www.microsoft.com/technet/network/wf/default.mspx> (pode estar em inglês).  

-   **Microsoft Internet Security and Acceleration Server**. O Microsoft Internet Security and Acceleration (ISA) Server pode ajudar a proteger a sua rede de várias maneiras. Em primeiro lugar, você pode usá-lo para permitir que usuários tenham acesso remoto aos aplicativos corporativos através da Internet. Para isso, você pode configurar o ISA Server para pré-autenticar as solicitações recebidas de usuários, inspecionar todo o tráfego na camada de aplicativo (incluindo tráfego criptografado) e fornecer ferramentas de publicação automatizadas. Em segundo lugar, se a sua organização tem filiais, o ISA Server permite que você use compactação HTTP, armazenamento de conteúdo em cache e recursos de rede virtual privada (VPN) para tornar a expansão da sua rede fácil e segura. Em terceiro lugar, com o ISA Server você pode proteger a sua rede contra ameaças baseadas em Internet tanto internas quanto externas. Ele faz isso através de sua arquitetura de firewall proxy, recursos de inspeção de conteúdo, configurações granulares de diretiva e recursos de monitoramento e alerta abrangentes.

    Para obter mais informações, consulte a página sobre o Microsoft Internet Security and Acceleration Server em <http://www.microsoft.com/isaserver/default.mspx> (pode estar em inglês).

-   **Isolamento de servidor e domínio usando protocolo IPsec e Diretiva de Grupo do Active Directory**. O isolamento de servidor e domínio cria uma camada de proteção ponta a ponta que pode reduzir drasticamente o risco de ataques mal-intencionados de alto custo e acesso não autorizado aos seus recursos de rede. Baseada no IPsec do Windows e na Diretiva de Grupo do Active Directory, essa solução permite que você segmente dinamicamente o seu ambiente Windows em redes lógicas isoladas e mais seguras. Há diversas maneiras de criar uma rede isolada, o que lhe proporciona a flexibilidade de isolar logicamente todo um domínio gerenciado ou criar redes virtuais mais seguras de servidores específicos, dados confidenciais e clientes, limitando dessa forma o acesso a somente usuários autenticados e autorizados, ou exigindo que servidores ou redes específicas protejam todos os dados usando criptografia. Ao exigir a criptografia de dados para o tráfego entre sub-redes ou hosts de rede específicos, você pode atender aos requisitos de regulamentação e de parceiros comerciais para a criptografia de dados enquanto eles atravessam a rede.

    Para obter mais informações, consulte a página sobre isolamento de servidor e domínio no site do Microsoft TechNet em <http://www.microsoft.com/technet/network/sdiso/default.mspx> (pode estar em inglês).

-   **Assistente de Configuração de Segurança do Windows Server 2003**. O Assistente de Configuração de Segurança (ACS) pode ajudá-lo a proteger a sua rede reduzindo a superfície de ataque em seus servidores que executam o Windows Server 2003, Service Pack 1. O Assistente de Configuração de Segurança determina as funcionalidades mínimas necessárias para as funções de um servidor e desabilita as funcionalidades que não são necessárias. Especificamente, o Assistente de Configuração de Segurança:

    -   Desativa serviços desnecessários.

    -   Bloqueia portas não utilizadas.

    -   Permite outras restrições de segurança ou endereço para portas que foram deixadas abertas.

    -   Proíbe extensões do IIS na Web desnecessárias, se aplicável.

    -   Reduz a exposição de protocolo dentro de blocos de mensagem de servidor (SMB), LanMan e protocolo LDAP.

    -   Define uma diretiva de auditoria de sinal/ruído de alta segurança.

    O Assistente de Configuração de Segurança pode orientar os seus profissionais de TI através do processo de criação, edição, aplicação ou reversão de uma diretiva de segurança com base nas funções selecionadas do servidor. As diretivas de segurança criadas com o ACS são arquivos XML que, quando aplicados, configuram serviços, segurança de rede, valores de Registro específicos, diretiva de auditoria e IIS, se aplicável.

    Para obter mais informações, consulte a página do Assistente de Configuração de Segurança para o Windows Server 2003 em <http://www.microsoft.com/windowsserver2003/technologies/security/configwiz/defaul.mspx> (pode estar em inglês).

-   **Conexão da Área de Trabalho Remota usando autenticação de servidor**. A Conexão da Área de Trabalho Remota é um modo eficaz de permitir que os usuários tenham acesso a computadores e servidores cliente compartilhados. Essa tecnologia pode ser um modo econômico de criar computadores de desenvolvimento e teste compartilhados. Além disso, você pode usar esses computadores como pontos de acesso centrais para vários tipos de projeto, e pode permitir que os usuários de fora da rede tenham acesso a esses computadores, isolando dessa forma os riscos que possam oferecer à segurança da rede. Além disso, a atualização do cliente Remote Desktop Connection 6.0 permite que seus profissionais de TI configurem a autenticação de servidor. Com a autenticação de servidor, você pode impedir que os usuários se conectem a computadores ou servidores diferentes dos autorizados, impedindo a possível exposição de informações confidenciais. A Microsoft introduziu esse recurso no Windows Vista e no Windows Server “Longhorn”. O cliente Remote Desktop Connection 6.0 pode ser usado por computadores que executam Windows Server 2003 com Service Pack 1 ou Windows XP com Service Pack 2 (SP2). O cliente pode ser usado para conexão com servidores de terminal ou área de trabalho remota como antes, mas a autenticação de servidor ocorre apenas quando o computador remoto está executando o Windows Vista ou o Windows Server “Longhorn”.

    Para obter mais informações, consulte a página sobre atualização do cliente Remote Desktop Connection 6.0 disponível para download no Centro de Download da Microsoft em <http://support.microsoft.com/kb/925876>.

-   **Wi-Fi Protected Access 2**. Se a sua organização usa uma rede sem fio, considere a atualização dos roteadores sem fio, pontos de acesso e outros dispositivos com suporte para a certificação de produto Wi-Fi Protected Access 2 (WPA2). O WPA2 é uma certificação de produto disponível por meio da Wi-Fi Alliance que certifica equipamentos sem fio como sendo compatíveis com o padrão IEEE 802,11i. O objetivo da certificação WPA2 é dar suporte a recursos de segurança obrigatórios adicionais do padrão IEEE 802,11i não incluídos em produtos com suporte para WPA. Por exemplo, o WPA2 exige suporte tanto para criptografia TKIP como para AES. O WPA2 está disponível em dois modos diferentes:

    -   O WPA2-Enterprise usa autenticação 802,1X e foi desenvolvido para redes com modo de infra-estrutura média e grande.

    -   O WPA2-Personal usa uma PSK para autenticação e foi desenvolvido para redes com modo de infra-estrutura SOHO.

    O WPA2 tem suporte no Windows XP Service Pack 2 e no Windows Vista e Windows Server “Longhorn”. Para obter mais informações, consulte a página sobre tecnologias de LAN sem fio e Microsoft Windows em <http://www.microsoft.com/technet/prodtechnol/winxppro/evaluate/wrlsxp.mspx> (pode estar em inglês) e a visão geral do WPA2 em <http://www.microsoft.com/technet/community/columns/cableguy/cg0505.mspx>(pode estar em inglês).

-   **Proteção de Acesso à Rede**. A Proteção de Acesso à Rede (NAP) é uma plataforma para Windows Server “Longhorn” e Windows Vista. Ela oferece componentes de aplicação de diretiva que ajudam a garantir que os computadores conectados à rede ou que se comunicam através de uma rede atendam aos requisitos definidos pelo administrador para a integridade do sistema. A sua organização pode usar uma combinação de componentes de validação de diretiva e de limitação de acesso para controlar o acesso à rede ou a comunicação. Você também pode decidir limitar temporariamente o acesso dos computadores que não atendem aos requisitos de uma rede restrita. Dependendo da configuração escolhida, a rede restrita pode conter recursos necessários para a atualização dos computadores, de forma que possam atender aos requisitos de integridade para acesso de rede ilimitado e comunicação normal. A NAP inclui uma interface de programação de aplicativo (API) configurada para que desenvolvedores e fornecedores criem soluções completas para validação de integridade de diretiva, limitação de acesso de rede e conformidade de integridade contínua. A NAP oferece componentes de aplicação de limitação de acesso para IPsec, conexões de rede com autenticação IEEE 802,1X, VPNs e Protocolo DHCP. Você pode usar essas tecnologias em conjunto ou separadamente. Com esses recursos, a NAP pode ser uma ferramenta poderosa para ajudá-lo a garantir a integridade e a segurança da sua rede.

    Para obter mais informações, consulte a página sobre a Proteção de Acesso à Rede em <http://www.microsoft.com/technet/network/nap/default.mspx>.

-   **Microsoft Virtual Server**. O Microsoft Virtual Server 2005 R2 oferece uma plataforma de virtualização que executa a maioria dos principais sistemas operacionais x86 em ambiente de convidado. Ele tem suporte da Microsoft como host para os sistemas operacionais Windows Server e aplicativos Windows Server System. Sua integração com uma ampla variedade de ferramentas de gerenciamento existentes da Microsoft e de terceiros permite que os administradores gerenciem sem conflitos um ambiente Virtual Server 2005 R2 com as suas ferramentas físicas existentes de gerenciamento de servidor. Como o Microsoft Virtual Server permite que a sua organização execute vários sistemas operacionais em um computador, ele pode ajudá-lo a atender ao requisito 2.2.1 do PCI DSS, que exige que a sua organização execute apenas uma única função principal por servidor. Por exemplo, você pode usar o Virtual Server para implantar um servidor Web virtual, um servidor de banco de dados virtual e um servidor de arquivos virtual no mesmo computador.

    O Microsoft Virtual Server está disponível para download gratuito da Microsoft. Para obter mais informações, consulte a página do Microsoft Virtual Server em <http://www.microsoft.com/windowsserversystem/virtualserver/default.mspx> (pode estar em inglês).  

#### Controle de host

As soluções de controle de host controlam os sistemas operacionais nos servidores e estações de trabalho. As soluções de controle de host também incluem a implementação de práticas recomendadas de segurança em todos os níveis do sistema operacional em cada host, mantendo as mais recentes atualizações e hotfixes e usando métodos seguros para as operações diárias.

##### Requisitos do PCI DSS atendidos

As soluções de controle de host podem ajudá-lo a atender aos requisitos do PCI DSS mantendo os sistemas operacionais atualizados e com configuração segura. Especificamente, o controle de host pode ajudá-lo a estar em conformidade com os requisitos 6 e 11 do PCI DSS.

Para obter o texto completo desses requisitos, consulte o [*PCI DSS (Payment Card Industry Data Security Stantard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece algumas tecnologias que você pode usar em conjunto e separadamente para criar soluções de controle de host. Assim como em outras soluções de tecnologia, você deve projetar essas soluções para atender aos requisitos do PCI DSS, bem como a quaisquer outros requisitos de regulamentação aplicáveis à sua organização.

-   **Microsoft Baseline Security Analyzer (MBSA)**. Uma das principais ferramentas que você pode usar para avaliar o risco aos dados de titulares de cartão na sua organização é o MBSA. O MBSA é uma ferramenta de fácil utilização que identifica problemas comuns de configuração de segurança em vários produtos Microsoft, incluindo o sistema operacional Windows, Serviços de Informações da Internet, SQL Server, Internet Explorer e Microsoft Office. O MBSA também verifica atualizações de segurança, conjuntos de atualizações e service packs ausentes que tenham sido publicados no Microsoft Update. Você pode executar o MBSA a partir do prompt de comando ou de uma GUI e ele pode ser usado com o Microsoft Update e com o Windows Server Update Services. Como a atualização de seus sistemas é muito importante para proteger os dados de titulares de cartão, o MBSA pode ser uma ferramenta inestimável na avaliação de risco de dados na sua organização.

    Para obter mais informações, consulte a página sobre o Microsoft Baseline Security Analyzer em <http://www.microsoft.com/technet/security/tools/mbsahome.mspx> (pode estar em inglês).

-   **Windows Server Update Services da Microsoft**.** **O Windows Server Update Services (WSUS) da Microsoft com Service Pack 1 permite que a sua organização implante muitas das últimas atualizações de vários produtos Microsoft publicadas no site do Microsoft Update. O WSUS é um componente de atualização do Windows Server que oferece um modo eficaz e rápido de ajudar a manter os sistemas atualizados. O WSUS oferece uma infra-estrutura de gerenciamento que consiste em:

    -   **Microsoft Update**. O site da Microsoft ao qual os componentes do WSUS se conectam para baixar atualizações de produtos da Microsoft.

    -   **Servidor Windows Server Update Services**. O componente de servidor instalado em um computador que executa o sistema operacional Microsoft Windows 2000 Server com Service Pack 4 (SP4) ou Windows Server 2003 dentro do firewall corporativo. O servidor WSUS oferece os recursos de que os administradores precisam para gerenciar e distribuir atualizações com uma ferramenta baseada na Web, que pode ser acessada por meio do Internet Explorer em qualquer computador com Windows na rede corporativa. Além disso, um servidor WSUS pode ser a fonte de atualização para outros servidores WSUS.

    -   **Atualizações Automáticas**. O componente de computador cliente incorporado aos sistemas operacionais Windows Vista, Windows Server 2003, Windows XP e Windows 2000 com SP3. Com o recurso Atualizações Automáticas, tanto o servidor como o computador cliente recebem atualizações do Microsoft Update ou de um servidor que executa o WSUS.

    Esses serviços permitem que você mantenha todos os ambientes de host da sua rede atualizados com as últimas correções de segurança da Microsoft para os produtos instalados em um host específico.  

    Para obter mais informações, consulte a página do Windows Server Update Services em <http://www.microsoft.com/windowsserversystem/updateservices/default.mspx> (pode estar em inglês)

-   **Microsoft Systems Management Server**. Se a sua organização usa o SMS para gerenciar computadores cliente e servidores, você já deve ter algumas das ferramentas de que precisa para realizar uma avaliação de riscos de dados de titulares de cartão. Com o SMS, a sua organização pode gerenciar remotamente as configurações de segurança em computadores que executam sistemas operacionais Windows em redes distribuídas. Você pode criar um inventário com os computadores da sua rede que receberam as atualizações de software necessárias e acompanhar o andamento das atualizações distribuídas a esses computadores. O SMS também permite que você gere relatórios que identifiquem seu inventário completo de hardware e software, os detalhes de configuração e o status dos computadores na sua rede, bem como o status das implantações de software e erros de implantação. Esses recursos do SMS podem ser muito importantes na avaliação de riscos de dados de titulares de cartão dentro da sua organização.

    Para obter mais informações sobre o SMS, consulte a página do Microsoft Systems Management Server em <http://www.microsoft.com/smserver/default.mspx> (pode estar em inglês).

-   **Microsoft Desktop Optimization Pack para Software Assurance**. O Microsoft Desktop Optimization Pack para Software Assurance é um serviço de assinatura que reduz os custos de implantação do aplicativo, permite a entrega de aplicativos como serviços, e oferece melhor gerenciamento e controle de ambientes desktop empresariais. O Desktop Optimization Pack é uma solução eficaz de controle de host que permite:

    -   Simplificar e acelerar o ciclo de vida de gerenciamento do aplicativo, desde o planejamento e a implantação previsível até a utilização, a manutenção e a migração de software.

    -   Aprimorar o gerenciamento dos ativos de software da sua organização.

    -   Acelerar e simplificar as implantações e as migrações de desktops.

    O Microsoft Desktop Optimization Pack está disponível apenas para clientes com cobertura Software Assurance em seus desktops. Para obter mais informações, consulte a página sobre como otimizar a área de trabalho do Windows em <http://www.microsoft.com/windows/products/windowsvista/buyorupgrade/optimizeddesktop.mspx> (pode estar em inglês).

Para obter links para orientações e procedimentos específicos sobre segurança de host para vários produtos Microsoft, consulte a seção sobre controle de host do [*guia de planejamento para conformidade com os regulamentos*](http://www.microsoft.com/technet/security/guidance/complianceandpolicies/compliance/rcguide/default.mspx?mfr=true).

#### Prevenção contra software mal-intencionado

As soluções de prevenção contra software mal-intencionado são elementos fundamentais para a proteção dos dados de titulares de cartão na sua rede. Ao prevenir spam e manter os sistemas da rede livres de vírus e spyware, essas soluções podem garantir que os sistemas de toda a rede estejam funcionando com o máximo desempenho e que os dados confidenciais não sejam transmitidos de forma não-intencional a terceiros não autorizados.

##### Requisitos do PCI DSS atendidos

As soluções de prevenção contra software mal-intencionado que você escolher podem ajudar a atender aos requisitos 5 e 6 do PCI DSS.

Para obter o texto completo desses requisitos, consulte o [*PCI DSS (Payment Card Industry Data Security Stantard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece algumas tecnologias que você pode usar em conjunto e separadamente para a prevenção contra software mal-intencionado. Considere essas tecnologias nos seus esforços mais abrangentes para a conformidade com o PCI DSS, bem como para quaisquer requisitos de regulamentação mais amplos para a sua organização.

-   **Microsoft Forefront™**. O Forefront é um conjunto de produtos de segurança de linha de negócios que oferece proteção para sistemas operacionais cliente, servidores de aplicativos e borda de rede. Você pode usar o Forefront com a sua infra-estrutura de TI existente para proteger os seus servidores e computadores cliente contra malware e outros ataques mal-intencionados com origem dentro ou fora da sua organização.

    Em particular, o Forefront Client Security oferece proteção contra software mal-intencionado para clientes em toda a sua organização. A solução Forefront Client Security é dividida em duas partes. A primeira é o Security Agent — instalado nos sistemas operacionais de desktops empresariais, laptops e servidores — que proporciona proteção em tempo real e verificações programadas contra ameaças como spyware, vírus e rootkits. A segunda é o servidor de gerenciamento central, que permite ao administrador gerenciar e atualizar com facilidade agentes de proteção contra malware pré-configurados ou personalizados e gerar relatórios e alertas sobre o status de segurança do ambiente.

    Para obter mais informações, consulte a página do Microsoft Forefront em <http://www.microsoft.com/forefront/default.mspx> (pode estar em inglês)

-   **Ferramenta de Remoção de Software Mal-Intencionado**. A Ferramenta de Remoção de Software Mal-Intencionado verifica se há infecções por softwares mal-intencionados específicos e predominantes em computadores com Windows XP, Windows 2000 e Windows Server 2003 e ajuda a remover quaisquer infecções encontradas. Quando o processo de detecção e remoção estiver concluído, a ferramenta exibirá um relatório descrevendo o resultado, que incluirá, se houver, qualquer software mal-intencionado detectado e removido. A Microsoft lança uma versão atualizada dessa ferramenta na segunda terça-feira de cada mês e, quando necessário, para responder aos incidentes de segurança.

    Para obter mais informações, consulte a página da Ferramenta de Remoção de Software Mal-Intencionado em <http://www.microsoft.com/security/malwareremove/default.mspx>.

    **Observação**   O Windows Defender e a Ferramenta de Remoção de Software Mal-Intencionado também podem ajudar a descobrir se um programa mal-intencionado usa um rootkit. Os rootkits são mecanismos que o criador de software mal-intencionado usa para esconder sua presença de bloqueadores de spyware, bem como de utilitários antivírus e de gerenciamento de sistema. Para obter mais informações sobre rootkits e como detectá-los, consulte a página [http://www.microsoft.com/technet/sysinternals/utilities/RootkitRevealer.mspx](http://www.microsoft.com/technet/sysinternals/utilities/rootkitrevealer.mspx) (pode estar em inglês).   

-   **Filtros de terceiros com o Microsoft ISA Server**. Além de fornecer soluções de segurança de rede, o ISA Server pode ajudar a proteger sua organização contra ataques de malware. Isso pode ser feito com a utilização de filtros personalizados ou de terceiros que removem o malware antes que ele atinja sua rede corporativa.

    Para obter mais informações, consulte a página sobre o Microsoft Internet Security and Acceleration Server em <http://www.microsoft.com/isaserver/default.mspx> (pode estar em inglês).

#### Segurança de aplicativos

Para atender aos requisitos do PCI DSS, considere as soluções de segurança de aplicativos em duas situações. Em primeiro lugar, você deve exigir que quaisquer novos aplicativos criados pelos desenvolvedores de sua organização estejam em conformidade com as práticas seguras de desenvolvimento. Em segundo lugar, certifique-se de que você esteja usando as orientações de segurança fornecidas nos aplicativos adquiridos na própria Microsoft ou em qualquer fornecedor terceirizado.

##### Requisitos do PCI DSS atendidos

Desenvolver e manter aplicativos seguros, com base na Web ou no Windows, é uma etapa importante nas tarefas em relação à conformidade com o PCI DSS. Em particular, essas soluções de tecnologia permitem atender ao requisito 6.

Para obter o texto completo do requisito, consulte o [*PCI DSS (Payment Card Industry Data Security Standard) versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece orientações e ferramentas específicas para o desenvolvimento de aplicativos seguros. Também são oferecidas orientações específicas sobre como usar de maneira segura os principais produtos de servidor.

-   **Microsoft Visual Studio® 2005**. O Visual Studio 2005 fornece muitas ferramentas que permitem aos desenvolvedores verificarem seus códigos de violação de segurança durante a fase de desenvolvimento:

    -   O FxCop verifica o código gerenciado em busca de falhas, inclusive falhas de segurança.

    -   O PREfast é uma ferramenta de análise estática para os códigos C e C++. Essa ferramenta pode ajudar os desenvolvedores a localizarem vários problemas de segurança.

    -   O Standard Annotation Language ajuda os desenvolvedores a localizarem erros de segurança que podem passar despercebidos pelos compiladores do código C ou C++.

    -   Ao compilar um código não gerenciado em C ou C++, os desenvolvedores sempre devem realizar a compilação com o recurso de detecção de saturação de pilha /GS e vincular o código à opção /SafeESH.

    -   Os desenvolvedores RPC devem compilar seu código com o sinalizador MIDL/robusto especificado.  

    O Security Development Lifecycle (SDL) sugere a utilização de ferramentas como o FxCop, o PREfast e a opção de compilador GS C++ para verificar se o código pode ser executado sem comprometer os problemas de segurança conhecidos.

    Para obter mais informações, consulte a página do Visual Studio em <http://msdn2.microsoft.com/en-us/vstudio/default.aspx> (pode estar em inglês).

-   **Microsoft Intelligent Application Gateway (IAG) 2007**. Como parte do Microsoft Forefront Network Edge Security, o IAG fornece uma VPN SSL, um firewall de aplicativo Web e gerenciamento de segurança de ponto de extremidade que permitem controle de acesso, autorização e inspeção de conteúdo para uma ampla variedade de aplicativos de linha de negócios. Juntas, essas tecnologias fornecem aos profissionais móveis e remotos acesso seguro fácil e flexível a partir de um ampla rede de dispositivos e locais, incluindo quiosques, computadores e dispositivos móveis. O IAG também permite aos administradores de TI aplicarem a conformidade com o aplicativo e as orientações de utilização de informações por meio de uma política de acesso remoto personalizada com base em dispositivo, usuário, aplicativo ou outros critérios comerciais. Os principais benefícios incluem:

    -   Uma combinação exclusiva de acesso com base em VPN SSL, integrado à proteção de aplicativo e gerenciamento de segurança de ponto de extremidade.

    -   Um poderoso firewall de aplicativo Web que ajuda a afastar o tráfego mal-intencionado e manter as informações confidenciais.

    -   Menor complexidade de gerenciamento de acesso seguro e proteção de ativos comerciais com base em uma plataforma abrangente e fácil de usar.

    -   Interoperabilidade com a principal infra-estrutura de aplicativos Microsoft, sistemas empresariais de terceiros e ferramentas internas personalizadas.

    Para obter mais informações, consulte a página de visão geral do produto Intelligent Application Gateway 2007 em <http://www.microsoft.com/forefront/edgesecurity/iag/overview.mspx> (pode estar em inglês).  

##### Orientações

-   **Security Development Lifecycle**. Se a sua organização decide desenvolver algumas de suas próprias soluções para manipular dados de titulares de cartão, é preciso considerar a necessidade de os desenvolvedores usarem o Security Development Lifecycle projetado pela Microsoft. Trata-se de uma abordagem abrangente para o desenvolvimento de aplicativos de segurança para desktops e Web que devem ser utilizados em organizações que processam e armazenam informações confidenciais, como, por exemplo, os dados de titulares de cartão. O Security Development Lifecycle começa com o planejamento de aplicativos seguros, garantindo a utilização de técnicas de codificação seguras, além assegurar que os aplicativos sejam testados e implantados com segurança após a conclusão do desenvolvimento.

    Para obter mais informações, consulte a página de detalhes sobre o Security Development Lifecycle da Microsoft em [http://msdn.microsoft.com/msdnmag/issues/05/11/SDL/](http://msdn.microsoft.com/msdnmag/issues/05/11/sdl/) (pode estar em inglês).

-   **Siga as orientações de segurança do produto**. A Microsoft oferece orientações de segurança para muitos de seus produtos. O interesse específico das organizações de médio e grande portes são as orientações de segurança para o Exchange Server, Systems Management Server e SQL Server. Para obter mais informações sobre as orientações de segurança para esses produtos, consulte a seção de segurança de aplicativos do [*guia de planejamento para conformidade com os regulamentos*](http://www.microsoft.com/technet/security/guidance/complianceandpolicies/compliance/rcguide/default.mspx?mfr=true).

#### Serviço de mensagens e colaboração

Para atender aos requisitos do PCI DSS, é preciso verificar se todos os softwares de mensagens e colaboração utilizados por sua organização estão configurados e instalados com segurança. Como os aplicativos de mensagens e colaboração tornaram-se ferramentas essenciais no setor de cartões de pagamento, é primordial que você faça tudo o que estiver ao seu alcance para se certificar de que todos os documentos ou mensagens de email que possam conter dados de titulares de cartão estejam seguros.

##### Requisitos do PCI DSS atendidos

Os métodos comuns para ajudar a evitar as violações de segurança em mensagens incluem gateways, servidores seguros e filtro de conteúdo para mensagens. Tanto os gateways quanto os filtros de conteúdo para os sistemas de mensagens encaminham as mensagens para um aplicativo de software especializado. Esse aplicativo pode usar diversos métodos para isolar uma determinada seqüência de caracteres, números, padrões ou outros itens, dependendo do modo como a solução foi desenvolvida. As mensagens que contêm tais palavras-chave ou seqüências podem ser colocadas em quarentena até que as informações suspeitas das mensagens sejam verificadas ou a solução pode simplesmente excluir e limpar a mensagem. Esses métodos podem ajudá-lo a manter a segurança de todos os dados dos titulares de cartão quando forem enviados por email ou por documentos em um ambiente de colaboração. Todas essas técnicas e soluções podem ajudá-lo a atender ao requisito 4 do PCI DSS.

Para obter o texto completo do requisito, consulte o [*PCI DSS (Payment Card Industry Data Security Standard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft fornece várias soluções que podem ajudar a manter a segurança dos softwares de colaboração e envio e mensagens. Cada uma dessas soluções fornece uma solução para diferentes aspectos de sua empresa. As soluções devem ser implantadas de maneira organizada para que possa ter o mínimo possível de vulnerabilidades de segurança após a conclusão.

-   **Microsoft Exchange Server**. Com o gerenciamento de documentos, o Exchange pode ajudá-lo a definir poderosas soluções para o sistema de mensagens necessárias para que sua organização continue a manter seguros todos os dados dos titulares de cartão em mensagens de email. O Exchange Server 2007 inclui mensagens unificadas, o que consolida as mensagens de email, voz e fax enviadas a um usuário em uma única caixa de entrada. Ele também oferece recursos que permitem que a sua organização aplique regras de retenção, verifique e execute ações com relação a mensagens em transporte, crie diários com flexibilidade e realize pesquisas em rich text em todas as caixas de correio implantadas.
    Para obter mais informações, consulte o site do Microsoft Exchange Server em <http://www.microsoft.com/exchange/default.mspx> (pode estar em inglês).  

-   **Microsoft Forefront Security para Exchange Server**. O Microsoft Forefront Security para Exchange Server ajuda a proteger sua infra-estrutura de email das infecções e do tempo de inatividade, usando uma abordagem que enfatiza as defesas de camada, a otimização do desempenho e da disponibilidade do Exchange Server e o controle de gerenciamento simplificado.

    -   **Proteção total**. O Microsoft Forefront Security para Exchange Server inclui vários mecanismos de verificação das principais empresas de segurança do setor integrados em uma única solução para ajudar as empresas a proteger seus ambientes de mensagens do Exchange contra vírus, worms e spams.

    -   **Desempenho otimizado**. Por meio de uma forte integração com o Exchange Server, inovações de verificação e controles de desempenho, o Forefront Security para Exchange Server ajuda a proteger os ambientes de mensagens, mantendo o tempo de atividade e otimizando o desempenho do servidor.

    -   **Gerenciamento simplificado**. O Forefront Security para Exchange Server também permite que os administradores gerenciem facilmente a configuração, a operação, as atualizações de assinaturas do mecanismo de verificação automatizado e a geração de relatórios no servidor e na empresa.

    Para obter mais informações, consulte a página do Microsoft Forefront em <http://www.microsoft.com/forefront/default.mspx> (pode estar em inglês)

-   **Microsoft Exchange Hosted Services**. O Microsoft Exchange Hosted Services para gerenciamento e segurança do sistema de mensagens é composto por quatro serviços distintos que ajudam as organizações na proteção contra emails mal-intencionados, na satisfação dos requisitos de retenção para conformidade, na criptografia dos dados para preservar a confidencialidade e na preservação do acesso aos emails durante e após situações de emergência. Os serviços são implantados via Internet usando um modelo de “software como um serviço” que ajuda a minimizar o investimento de capital adicional, liberando recursos de TI que poderão ser utilizados em outras iniciativas de produção de valores, e reduzir os riscos do sistema de mensagens antes que possam atingir o firewall da empresa.

    Para obter mais informações, consulte a página do Microsoft Exchange Hosted Services em <http://www.microsoft.com/exchange/services/default.mspx> (pode estar em inglês).

-   **Information Right Management (IRM) do Microsoft Office**. O Office é o principal pacote de aplicativos de produtividade para empresas. O recurso IRM do Microsoft Office pode ajudar as organizações a controlar o acesso a informações confidenciais, como os dados de titulares de cartão.

    Mais especificamente, o recurso IRM do Office ajuda a organização a:

    -   Impedir que um destinatário autorizado ao acessar informações protegidas possa encaminhar, copiar, modificar, imprimir, enviar fax ou recortar e colar as informações para uso não autorizado.

    -   Impedir que informações protegidas sejam copiadas com a função Print Screen do Microsoft Windows.

    -   Fornecer informações com o mesmo nível de proteção, independentemente de seu destino. Isso é conhecido como "proteção persistente".

    -   Fornecer o mesmo nível de proteção aos anexos de email, desde que os anexos sejam arquivos criados com outros programas do Office, como o Excel ou o Word.

    -   Proteger informações em mensagens de email ou documentos que tenham sido definidas para expirar, de forma que as informações não possam ser visualizadas após um determinado período de tempo.

    -   Aplicar diretivas corporativas que controlam o uso e a difusão de informações dentro e fora da empresa.

    O IRM do Office foi criado sob a plataforma do Microsoft Windows Rights Management Services. Para ativar esse recurso no Office, é preciso adquirir as licenças do servidor RMS.

    Para obter mais informações, consulte o site do Microsoft Office em <http://office.microsoft.com/en-us/default.aspx>.

-   **Information Rights Management (IRM) do Microsoft Windows SharePoint Services**. Com as soluções de gerenciamento de documentos, o IRM do SharePoint Services pode ajudar a fazer com que suas soluções de colaboração atendam aos requisitos do PCI DSS. Essa tecnologia permite criar um conjunto de controles de acesso persistente que estão vinculados ao conteúdo, e não a um local de rede específico; desse modo, você poderá controlar o acesso aos arquivos mesmo após deixarem o controle direto. O IRM está disponível para arquivos localizados em bibliotecas de documentos e armazenados como anexos aos itens da lista. Os administradores de sites podem impedir os downloads de uma biblioteca de documentos com o IRM. Quando um usuário tenta baixar um arquivo da biblioteca, o Windows SharePoint Services verifica se o usuário possui permissões para o arquivo e emite uma licença que permite que ele acesse o arquivo dentro do nível de permissões apropriado. Então, o Windows SharePoint Services baixa o arquivo para o computador do usuário em um formato criptografado e com direitos gerenciados.

    O IRM do Office foi criado sob a plataforma do Microsoft Windows Rights Management Services. Para habilitar esse recurso no Office, é preciso adquirir as licenças do servidor RMS.

    Para obter mais informações, consulte o site sobre [produtos e tecnologias Microsoft SharePoint](http://go.microsoft.com/fwlink/?linkid=12632) em <http://go.microsoft.com/fwlink/?linkid=12632>.

#### Classificação e proteção de dados

As soluções de classificação e proteção de dados são elementos essenciais para garantir que os requisitos do PCI DSS sejam atendidos e que os dados de titulares de cartão fiquem seguros. Essas soluções tratam sobre como aplicar os níveis de classificação de segurança aos dados de titulares de cartão tanto em um sistema quanto em uma transmissão. Essa categoria de solução também lida com a proteção de dados com relação a fornecer confidencialidade e integridade aos dados que estejam em armazenamento ou transmissão. As soluções de criptografia compõem o método mais comum utilizado pelas organizações para fornecer proteção de dados.

##### Requisitos do PCI DSS atendidos

As soluções de classificação e proteção de dados ajudam a cumprir os requisitos do PCI DSS, oferecendo segurança aos dados dos titulares de cartão quando armazenados em um banco de dados, transmitidos de um servidor para outro ou quando são transmitidos dentro de sua rede no momento em que o titular do cartão faz uma compra. O uso dessas soluções permite atender aos requisitos 3 e 7 do PCI DSS.

Para obter o texto completo desses requisitos, consulte o [*PCI DSS (Payment Card Industry Data Security Stantard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece algumas tecnologias que podem ajudá-lo a classificar e a proteger os dados de titulares de cartão, independentemente de serem transmitidos em sua rede, armazenados em um documento no computador de um funcionário ou armazenados em um banco de dados. São elas:

-   **Criptografia de Unidade de Disco BitLocker™**. O recurso Criptografia de Unidade de Disco BitLocker ajuda a proteger os dados de titulares de cartão, oferecendo criptografia da unidade e verificação de integridade em componentes inicializados anteriormente. A criptografia de unidade de disco protege os dados, evitando que usuários não autorizados possam violar a proteção do sistema e de arquivos do Windows em computadores perdidos ou roubados. Essa proteção é obtida ao criptografar todo o volume do Windows. Com o BitLocker, todos os arquivos do usuário e do sistema são criptografados, inclusive os arquivos de troca e hibernação. A verificação de integridade dos componentes inicializados anteriormente ajuda a verificar se a decodificação de dados é executada apenas quando os componentes aparecem sem modificações e se a unidade criptografada está no computador original. O BitLocker está disponível no Windows Vista Enterprise e Ultimate e no Windows Server “Longhorn”.

    Para obter mais informações, consulte a visão geral executiva sobre o BitLocker Drive Encryption no site <http://technet.microsoft.com/en-us/windowsvista/aa906018.aspx> (pode estar em inglês).

-   **Sistema de arquivos com criptografia do Windows (EFS)**. O EFS fornece a principal tecnologia de criptografia de arquivos utilizada para armazenar arquivos criptografados em volumes de sistema de arquivos NTFS. Depois de criptografar um arquivo ou uma pasta, trabalhe com esse arquivo ou pasta da mesma maneira como trabalha com os outros arquivos e pastas.

    A criptografia torna-se transparente para o usuário que criptografou o arquivo. Isso significa que você não precisa descriptografar manualmente um arquivo criptografado antes de utilizá-lo, podendo abri-lo e alterá-lo normalmente.

    O uso do EFS é semelhante ao uso de permissões em arquivos e pastas. Ambos os métodos podem ser usados para restringir o acesso aos dados. No entanto, um intruso que obtém acesso físico não autorizado às pastas ou aos arquivos criptografados não conseguirá lê-los. O intruso que tentar abrir ou copiar o arquivo ou a pasta criptografada receberá uma mensagem de acesso negado. As permissões de arquivos e pastas não protegem contra ataques físicos não autorizados.

    Para obter mais informações, consulte a visão geral do Sistema de Arquivos com Criptografia em <http://www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/encrypt_overview.mspx?mfr=true> (pode estar em inglês) ou a página do Sistema de Arquivos com Criptografia em <http://www.microsoft.com/windows/products/windowsvista/features/details/encryptingfilesystem.mspx> (pode estar em inglês).

-   **Microsoft Windows Rights Management Services**. O RMS (Windows Rights Management Services) é uma plataforma de software que auxilia os aplicativos a proteger os dados de titulares de cartão contra o uso não autorizado — tanto online quanto offline, dentro e fora do firewall.

    O RMS amplia a estratégia de segurança da sua organização, protegendo as informações por meio de diretivas de uso persistentes, que permanecem com as informações independentemente de seu destino. Os aplicativos compatíveis com RMS podem ser usados para gerenciar e controlar o acesso a documentos que contenham informações sobre o titular de cartão, bem como para fazer auditoria desse acesso. O cliente RMS está integrado ao sistema operacional Windows Vista. Para outras versões do Windows, o cliente RMS está disponível para download gratuito.
    Para obter mais informações, consulte a página do [Windows Rights Management Services](http://www.microsoft.com/rms) em <http://www.microsoft.com/rms> (pode estar em inglês).  

-   **Criptografia no Microsoft SQL Server**. Quando você armazena os dados de titulares de cartão no SQL Server, esses dados são criptografados com criptografia hierárquica e infra-estrutura de gerenciamento de chave. Cada camada criptografa a próxima camada usando uma combinação de certificados, chaves simétricas e assimétricas. Existe uma chave mestre para o próprio SQL Server e uma chave separada para cada banco de dados dentro dessa instância do SQL Server. Isso fornece segurança para o armazenamento de dados dos titulares de cartão de sua organização.

    Para obter mais informações, consulte a página do Microsoft SQL Server em [h](http://www.microsoft.com/sql/default.mspx)[ttp://www.microsoft.com/sql/default.mspx](http://www.microsoft.com/sql/default.mspx)</a>.

#### Gerenciamento de identidade

O gerenciamento de identidade é um elemento importante para estar em conformidade com o PCI DSS. As soluções de gerenciamento de identidade permitem limitar os funcionários que poderão acessar, processar e transmitir dados de titulares de cartão. Sua organização pode usar essas soluções de gerenciamento de identidade para ajudar a gerenciar as identidades e as permissões digitais de seus funcionários, clientes e parceiros.

##### Requisitos do PCI DSS atendidos

O uso das soluções de gerenciamento de identidade pode permitir que você atenda ao requisito 8 do PCI DSS, ajudando-o a criar e atribuir uma identificação exclusiva para cada pessoa que tenha acesso a um computador em sua organização. Essas soluções também podem ajudar a restringir o acesso aos dados de titulares de cartão com base na identificação exclusiva, o princípio do requisito 7 do PCI DSS.

Para obter o texto completo do requisito, consulte o [*PCI DSS (Payment Card Industry Data Security Standard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece várias tecnologias para ajudá-lo a atender aos requisitos de gerenciamento de identidades de sua organização.

-   **Microsoft Active Directory**. O Active Directory oferece suporte a várias técnicas que podem ajudá-lo a controlar as pessoas que terão acesso aos dados de titulares de cartão dentro ou fora de sua rede. Primeiro, o Active Directory oferece suporte à autenticação Kerberos, uma das técnicas de autenticação padrão do Windows. O Kerberos fornece autenticação segura de usuário com um padrão que permite interoperabilidade. O controlador de domínio do Active Directory mantém informações de conta de usuário e de logon para oferecer suporte ao serviço Kerberos. Em segundo lugar, o Active Directory oferece suporte à autenticação de cartões inteligentes. Você pode exigir que os usuários ou os administradores remotos dos sistemas que contêm os dados de titulares de cartão só possam acessar a rede com um cartão inteligente e um PIN. Em terceiro lugar, o Active Directory oferece suporte ao roaming de credencial, um serviço que permite aos usuários que usam vários computadores utilizarem as mesmas credenciais em cada um desses computadores. Em quarto lugar, o Active Directory permite à sua organização personalizar os provedores de credenciais usados para autenticar os usuários. Esses recursos podem ajudá-lo a controlar como as contas do Active Directory poderão acessar os dados de titulares de cartão e quais contas terão acesso a esses dados.

    Para obter mais informações, consulte a página sobre o centro de tecnologia do Windows Server 2003 para o Active Directory em <http://www.microsoft.com/windowsserver2003/technologies/directory/activedirectory/default.mspx> (pode estar em inglês).  

-   **Microsoft Active Directory Federation Services**. Com o Active Directory Federation Services (ADFS), você pode criar soluções de gerenciamento de identidade que vão além dos limites tradicionais do Active Directory. Ao implantar o ADFS, sua organização pode estender a infra-estrutura já existente do Active Directory para fornecer acesso aos recursos que são oferecidos por parceiros confiáveis via Internet. Esses parceiros confiáveis podem incluir parceiros terceirizados ou outros departamentos ou filiais da mesma organização.

    O ADFS está bem integrado ao Active Directory. Ele recupera atributos de usuários do Active Directory e autentica os usuários usando o Active Directory. O ADFS também usa a autenticação integrada do Windows. Esse serviço está disponível nos sistemas operacionais Windows Server 2003 R2 e Windows Server “Longhorn”.

    Para obter mais informações, consulte a visão geral do Active Directory Federation Services (ADFS) no Windows Server 2003 R2 em [http://www.microsoft.com/WindowsServer2003/R2/Identity\_Management/ADFSwhitepaper.mspx](http://www.microsoft.com/windowsserver2003/r2/identity_management/adfswhitepaper.mspx) (pode estar em inglês).

-   **Microsoft Identity Lifecycle Manager**. O Microsoft Identity Lifecycle Manager (ILM) simplifica o processo de correspondência e gerenciamento dos registros de identidade de diferentes repositórios de dados e evita erros, como a ativação de registros de funcionários que já saíram da organização. O ILM oferece à organização uma estrutura de diretiva para controlar e rastrear a identidade e os dados de acesso que ajudam o gerenciamento. Isso também inclui as ferramentas de auto-ajuda para usuários finais, permitindo ao departamento de TI melhorar a eficiência, delegando várias tarefas aos usuários finais de maneira mais segura. Um outro recurso-chave do ILM é que ele inclui uma solução de gerenciamento certificada com base no Windows que se integra ao sistema operacional Windows Server 2003 e ao Active Directory para fornecer uma solução decisiva para o gerenciamento do ciclo de vida de ponta a ponta de cartões inteligentes e certificados digitais para a Autoridade de Certificação do Windows Server 2003.

    O ILM permite que sua organização:

    -   Sincronize as informações de identidade por meio de uma série de armazenamentos heterogêneos de identidades que sejam ou não em diretórios. Isso permite automatizar o processo de atualização das informações de identidade por diferentes plataformas enquanto mantém a integridade e a propriedade dos dados na empresa.

    -   Configure e desconfigure as contas de usuários e as informações de identidade, como distribuição, contas de email e grupos de segurança por meio de sistemas e plataformas. As novas contas para funcionários podem ser criadas rapidamente com base em eventos ou alterações em armazenamentos autorizados como o sistema de recursos humanos. Além disso, quando os funcionários deixam a empresa, eles podem ser imediatamente removidos dos mesmos sistemas.

    -   Gerencie certificados e cartões inteligentes. O ILM inclui uma solução baseada em diretiva e fluxo de trabalho que permite às organizações gerenciarem facilmente o ciclo de vida dos certificados digitais e cartões inteligentes. O ILM aproveita os serviços do Active Directory Services e do Active Directory Certificate Services para oferecer certificados digitais e cartões inteligentes, com fluxo de trabalho automatizado para gerenciar todo o ciclo de vida das credenciais que se baseiam em certificados. O ILM reduz significativamente os custos associados aos certificados digitais e cartões inteligentes, permitindo que as organizações implantem, gerenciem e mantenham com mais eficiência uma infra-estrutura baseada em certificado. Isso também simplifica o fornecimento, a configuração e o gerenciamento dos certificados digitais e cartões inteligentes, enquanto aumenta a segurança, usando uma tecnologia de autenticação forte e de multifatores.

    Para obter mais informações, consulte a página do Microsoft Identity Lifecycle Manager em <http://www.microsoft.com/windowsserver/ilm2007/default.mspx> (pode estar em inglês).  

-   **Microsoft SQL Server**. O SQL Server pode ser usado em conjunto com outras tecnologias para criar soluções de gerenciamento de identidade. Use os bancos de dados do SQL Server para armazenar as informações de nome de usuário e senha, além de mapear os certificados para contas de usuário e outras soluções. Você pode usar o SQL Server em conjunto com Microsoft ILM, Active Directory, Diretiva de Grupo e ACLs para restringir o acesso dos usuários aos dados de titulares de cartão armazenados em outro banco de dados, em documentos ou em diretórios.

    Para obter mais informações, consulte a página do Microsoft SQL Server em [h](http://www.microsoft.com/sql/default.mspx)[ttp://www.microsoft.com/sql/default.mspx](http://www.microsoft.com/sql/default.mspx)</a>.

##### Recursos de suporte ao sistema operacional

-   **Infra-estrutura de chave pública**. Uma infra-estrutura de chave pública (PKI) é um sistema de certificados digitais, autoridades de certificação (CAs) e outras autoridades de registro que verifica e autentica a validade de cada parceiro envolvido em uma transação eletrônica pelo uso da criptografia de chave pública. Essa estrutura permite proteger e trocar dados de titulares de cartão, com alta segurança, por meio de Internet, extranets, intranets e aplicativos.

    O suporte à PKI está disponível no Windows Server 2000, Windows XP Professional, Windows Server 2003, Windows Vista e Windows Server “Longhorn”.

    Para obter mais informações, consulte a página sobre a infra-estrutura de chave pública no Windows Server 2003 em <http://www.microsoft.com/windowsserver2003/technologies/pki/default.mspx> (pode estar em inglês).

#### Autenticação, autorização e controle de acesso

Autenticação é o processo de identificação de um usuário. Em ambientes de TI, normalmente a autenticação envolve um nome de usuário e uma senha, mas ela pode incluir métodos adicionais para verificar a identidade, como, por exemplo, cartão inteligente, verificação de retina, reconhecimento de voz ou impressões digitais. O objetivo da autorização é determinar se a identidade autenticada tem permissão para acessar os recursos solicitados. Você pode escolher entre conceder ou negar o acesso com base em diversos critérios, como o endereço de rede do cliente, o período do dia ou o navegador que a pessoa usa.

Ao planejar a autenticação, a autorização e a estratégia de controle de acesso, também será preciso desenvolver uma estratégia para conceder permissões à conta de usuário para todos os recursos da rede. Para obter mais informações, consulte [*Aplicando o princípio de contas de usuário sem privilégios administrativos no Windows XP *](http://www.microsoft.com/technet/prodtechnol/winxppro/maintain/luawinxp.mspx) (a página pode estar em inglês).

##### Requisitos do PCI DSS atendidos

A autenticação, a autorização e o controle de acesso são peças-chave de sua estratégia de segurança dos dados de titulares de cartão, especialmente em combinação com a classificação e a proteção de dados e as soluções de gerenciamento de identidade. Nesse contexto, as soluções de autenticação, autorização e controle de acesso podem ajudar sua organização a atender aos requisitos 6, 7 e 8 do PCI DSS.

Para obter o texto completo desses requisitos, consulte o [*PCI DSS (Payment Card Industry Data Security Stantard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece várias tecnologias que podem ajudá-lo a criar e integrar as estratégias de autenticação, autorização e controle de acesso na solução completa de conformidade com o PDI DSS.

-   **Microsoft Active Directory**. Grande parte do serviço Active Directory no Microsoft Windows 2000 Server, no Windows Server 2003 e no Windows Server “Longhorn” está voltada para a autenticação, a autorização e o controle de acesso. Por exemplo, o Active Directory oferece suporte à autenticação Kerberos, uma das técnicas de autenticação padrão do Windows. O Kerberos fornece autenticação segura de usuário com um padrão que permite interoperabilidade. O controlador de domínio do Active Directory mantém informações de conta de usuário e de logon para oferecer suporte ao serviço Kerberos. Em segundo lugar, o Active Directory oferece suporte à autenticação de cartões inteligentes. Você pode exigir que os usuários ou os administradores remotos dos sistemas que contêm os dados de titulares de cartão só possam acessar a rede com um cartão inteligente e um PIN. O Active Directory oferece suporte ao roaming de credencial, um serviço que permite aos usuários que utilizam vários computadores a usarem as mesmas credenciais em cada um desses computadores. Com o Active Directory, sua organização também pode personalizar os provedores de credenciais usados para autenticar os usuários. Além disso, ele permite delegar tarefas administrativas através da organização. Esses recursos podem ajudá-lo a controlar como as contas do Active Directory poderão acessar os dados de titulares de cartão e quais contas terão acesso a esses dados.

    Para obter mais informações, consulte a página sobre o centro de tecnologia do Windows Server 2003 para o Active Directory em <http://www.microsoft.com/windowsserver2003/technologies/directory/activedirectory/default.mspx> (pode estar em inglês).  

-   **Serviço de Autenticação da Internet da Microsoft**. O serviço de autenticação da Internet (IAS) é a implementação da Microsoft de um servidor e proxy RADIUS (Remote Authentication Dial-in User Service). Assim como no servidor RADIUS, o IAS executa a autenticação, a autorização e o controle de contas centralizados de conexões em muitos tipos de acesso de rede, incluindo conexões sem fio e VPN. Assim como no proxy RADIUS, o IAS encaminha as mensagens de autenticação e controle de contas a outros servidores RADIUS. Sendo assim, o IAS executa as etapas de autenticação das conexões remotas antes que elas atinjam a rede da organização. Com as credenciais do usuário indicadas para se conectar remotamente, você pode autorizar que eles tenham acesso apenas aos recursos necessários para que eles possam realizar seus trabalhos.

    Para obter mais informações, consulte a página do serviço de autenticação da Internet em <http://www.microsoft.com/technet/network/ias/default.mspx> (pode estar em inglês).

##### Recursos de suporte ao sistema operacional

-   **Usando listas de controle de acesso para conceder permissões a recursos**. Uma lista de controle de acesso (ACL) é um mecanismo usado por sistemas operacionais do Microsoft Windows NT para proteger recursos, como arquivos e pastas. As ACLs contêm várias entradas de controle de acesso (ACEs) que associam uma conta principal (geralmente uma conta de usuário ou um grupo de contas) a uma regra que rege o uso do recurso. As ACLs e as ACEs permitem que sua organização conceda ou negue direitos aos recursos com base nas permissões que podem ser associadas às contas do usuário. Por exemplo, você pode criar uma ACE e aplicá-la a uma ACL de um arquivo para impedir que qualquer pessoa, exceto um administrador, leia o arquivo. Essa tecnologia deve ser usada com a solução de gerenciamento de identidade, mas continuará sendo uma boa maneira de restringir o acesso aos dados de titulares de cartão apenas para as pessoas que precisam deles para trabalhar.

    Para obter mais informações, consulte a visão geral da tecnologia ACL em <http://msdn2.microsoft.com/en-us/library/ms229742.aspx> (pode estar em inglês).

-   **Windows Firewall no Microsoft Windows Vista e no Windows Server “Longhorn”**. Como discutido anteriormente, o Windows Firewall no Windows Vista e no Windows Server “Longhorn” pode ajudar a proteger seus sistemas e redes de ataques mal-intencionados. Isso pode ajudá-lo a controlar quais usuários, computadores e grupos poderão acessar determinados recursos em um computador ou domínio. Quando você usa o Windows Firewall com a Segurança Avançada, pode criar regras que filtram as conexões de usuário, computador ou grupo do Active Directory. Para criar esses tipos de regras, é preciso conectar-se de maneira bastante segura com o IPsec usando as credenciais que transportam as informações da conta do Active Directory, como o Kerberos versão 5.

    Para obter mais informações, consulte a página do Windows Firewall em <http://www.microsoft.com/technet/network/wf/default.mspx> (pode estar em inglês).

Para obter os links que o conduzirá às informações conceituais e ao guia de planejamentos sobre autenticação, autorização e controle de acesso, consulte a seção sobre autenticação, autorização e controle de acesso do [*guia de planejamento para conformidade com os regulamentos*](http://www.microsoft.com/technet/security/guidance/complianceandpolicies/compliance/rcguide/default.mspx?mfr=true).

#### Identificação de vulnerabilidade

As soluções de identificação de vulnerabilidade fornecem ferramentas que podem ser usadas pela sua organização para ajudar a testar as vulnerabilidades de seus sistemas de informações. Sua equipe de TI deve estar ciente das vulnerabilidades no ambiente de TI antes de poder solucioná-las com eficácia. Na identificação das vulnerabilidades, também deve estar presente a capacidade de restaurar os dados que foram inadvertidamente perdidos devido a um erro do usuário.

##### Requisitos do PCI DSS atendidos

As soluções de vulnerabilidades permitem que sua organização atenda ao requisito 11 do PCI DSS, que testa regularmente os sistemas e procedimentos de segurança.

Para obter o texto completo do requisito, consulte o [*PCI DSS (Payment Card Industry Data Security Standard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf).

##### Tecnologias disponíveis

A Microsoft oferece soluções que podem ajudá-lo a criar as soluções de identificação de vulnerabilidades para atender aos requisitos do PCI DSS.

-   **Microsoft Baseline Security Analyzer (MBSA)**. Da mesma forma como se avalia o risco ao projetar muitos de seus controles de proteção aos dados de titulares de cartão, o MBSA permite analisar periodicamente as vulnerabilidades que possam comprometer a segurança dos dados dos titulares de cartão. O MBSA pode ser usado para localizar problemas comuns de configuração de segurança em vários produtos da Microsoft, incluindo o sistema operacional Windows, Serviços de Informações da Internet, SQL Server, Internet Explorer e Microsoft Office. O MBSA também verifica atualizações de segurança, conjuntos de atualizações e service packs ausentes que tenham sido publicados no Microsoft Update. Você pode executar o MBSA a partir do prompt de comando ou de uma GUI, e ele pode ser usado com o Microsoft Update e com o Windows Server Update Services. Como a atualização de seus sistemas é muito importante para proteger os dados dos titulares de cartão, o MBSA pode ser uma ferramenta inestimável para determinar se suas instalações têm criado vulnerabilidades aos dados de titulares de cartão com o passar do tempo.

    Para obter mais informações, consulte a página sobre o Microsoft Baseline Security Analyzer em <http://www.microsoft.com/technet/security/tools/mbsahome.mspx> (pode estar em inglês).

#### Monitoramento, auditoria e relatório

As soluções de monitoramento e relatório coletam os logs resultantes da autenticação e do acesso aos sistemas, e faz auditoria desses logs. Você pode projetar essas soluções para coletar informações específicas com base no PCI DSS ou usar os relatórios existentes criados nos sistemas operacionais ou pacotes de software.

Uma subcategoria de monitoramento e relatório é a coleta, a análise e a correlação de todos os dados registrados em sua organização. Algumas vezes, esse processo é acompanhado por uma solução do tipo painel, em que você pode analisar melhor as diversas informações obtidas por toda a organização. Esse tipo de solução permite que o gerenciamento de TI determine melhor se há uma correlação entre os eventos.

##### Requisitos do PCI DSS atendidos

As soluções de monitoramento, auditoria e relatório podem ajudá-lo a atender ao requisito 10 do PCI DSS, cujo objetivo é controlar e monitorar todos os acessos aos recursos de rede e dados de titulares de cartão.

##### Tecnologias disponíveis

A Microsoft oferece algumas tecnologias que permitem monitorar o acesso à rede e aos dados dos titulares de cartão.

-   **Coleta de auditoria para o Microsoft System Center Operations Manager**. O Operations Manager 2007 pode extrair e coletar de modo seguro e eficiente logs de segurança de sistemas operacionais Windows e armazená-los para posterior análise e relatório. Os logs extraídos são armazenados em um banco de dados de coleta de auditoria separado. O Operations Manager será acompanhado de relatórios que podem ser usados para os dados de coleta de auditoria. A coleta de auditoria pode ser usada para gerar vários relatórios de conformidade, como as auditorias de suporte Sarbanes-Oxley. Além disso, ela também pode ser usada para análises de segurança, como detecção de intrusão e tentativas de acesso não autorizado.

    Para obter mais informações, consulte a página sobre os serviços de coleta de auditoria em <http://technet.microsoft.com/en-us/library/bb381258.aspx> (pode estar em inglês).

-   **Infra-estrutura de logon de evento do Microsoft Windows Vista**. Os aperfeiçoamentos da infra-estrutura de registro de eventos do Windows tornam o Windows Vista mais fácil de gerenciar e monitorar, além de fornecer melhores informações para a solução de problemas. Os padrões rígidos asseguram que os eventos sejam significativos, que permitam a tomada de ações e que sejam bem documentados. Muitos dos componentes que armazenavam informações de log em arquivos de texto nas versões anteriores do Windows agora adicionam os eventos ao log de eventos. Com o encaminhamento de eventos, os administradores podem gerenciar os eventos de forma central usando um computador em qualquer lugar na rede, facilitando a identificação dos problemas anteriores de forma proativa e a correlação dos problemas que afetam vários computadores. Por fim, a ferramenta Visualizar Evento foi completamente reformulada para permitir que os usuários possam criar exibições personalizadas, associando facilmente os eventos às tarefas e permitindo a visualização remota de registros a partir de outros computadores. Essa contribuição torna o trabalho dos administradores muito mais prático quando eles utilizam o log de eventos para solucionar os problemas dos usuários.

    Para obter mais informações, consulte os recursos de gerenciamento do Windows Vista em <http://technet.microsoft.com/en-us/windowsvista/aa905069.aspx> (pode estar em inglês).

-   **Microsoft SQL Server**. Os serviços de relatório do SQL Server compõem uma solução abrangente com base em servidor que permite a criação, o gerenciamento e a distribuição de relatórios tradicionais, impressos em papel, e interativos, com base na Web. Parte integrada da estrutura da inteligência comercial da Microsoft, os serviços de relatório combinam os recursos de gerenciamento de dados do SQL Server e do Microsoft Windows Server com poderosos e comuns aplicativos do sistema do Microsoft Office, distribuindo as informações em tempo real e, conseqüentemente, oferecendo suporte às operações diárias e decisões da unidade. Esses serviços podem ser usados para gerar relatórios que analisam os dados de titulares de cartão e controlam suas alterações. Os serviços de relatório também podem ser usados para facilitar o monitoramento dos padrões de utilização da rede e do fluxo de informações.

    Para obter mais informações, consulte a página do Microsoft SQL Server em [h](http://www.microsoft.com/sql/default.mspx)[ttp://www.microsoft.com/sql/default.mspx](http://www.microsoft.com/sql/default.mspx)</a>.

##### Recursos de suporte ao sistema operacional

-   **Listas de controle de acesso ao sistema NTFS**. A organização pode usar as Listas de controle de acesso ao sistema NTFS (SACLs) em arquivos e diretórios para ajudá-lo a controlar as alterações realizadas em arquivos ou pastas em um sistema. Ao definir uma SACL em um arquivo ou uma pasta, sempre que um usuário executar uma ação no arquivo ou pasta em questão, a SACL indicará ao sistema operacional do Windows que ele deverá registrar a ação e informar quem a executou. Não é possível definir SACLs em sistemas formatados para o sistema de arquivos FAT; por isso, a organização deve usar o formato do sistema de arquivos NTFS em todos os volumes que armazenam dados de usuário e dados de titulares de cartão.

    Para obter mais informações, consulte a página de gerenciamento de configurações e dados de usuário em <http://www.microsoft.com/technet/prodtechnol/winxppro/maintain/xpusrdat.mspx> (pode estar em inglês).

#### Gerenciando as soluções de tecnologia do PCI DSS

O uso dos produtos de gerenciamento não ajudará sua organização a cumprir os requisitos específicos do PCI DSS, mas pode ajudá-lo a acompanhar os controles de TI que forem implementados para fins de conformidade. Na criação de uma estrutura de controles de TI, é sempre importante ter a capacidade de gerenciar esses controles centralmente, com o menor número possível de administradores.

##### Tecnologias disponíveis

A Microsoft oferece duas ferramentas principais para o gerenciamento da estrutura de controles de TI que você implementou para atender aos requisitos do PCI DSS e a outros requisitos de regulamentação.

-   **Microsoft Forefront**. O Forefront é um conjunto de produtos de segurança de linha de negócios que oferece proteção para sistemas operacionais cliente, servidores de aplicativos e borda de rede. O Forefront pode ser usado com sua infra-estrutura de TI existente para proteger seus servidores e computadores cliente de ataques mal-intencionados e malware — tudo isso com uma fácil integração com os servidores de aplicativos, como Exchange, SharePoint e Instant Messaging. Ele também permite integração incorporada com o Active Directory e usa o ISA Server para trabalhar com o Active Directory para oferecer suporte a RADIUS, DHCP e cartão inteligente. O Forefront também fornece uma ferramenta de gerenciamento centralizada para um local central de relatórios, junto com um local centralizado para definir as medidas de controle de diretiva.

    Para obter mais informações, consulte a página do Microsoft Forefront em <http://www.microsoft.com/forefront/default.mspx> (pode estar em inglês)

-   **Microsoft System Center**. O Microsoft System Center é uma família de produtos de gerenciamento destinada a fornecer à sua organização as ferramentas necessárias para automatizar o gerenciamento do sistema. O System Center inclui tecnologias que automatizam as tarefas mais comuns de gerenciamento, oferecendo ferramentas que ajudam os profissionais de TI a detectar, diagnosticar e corrigir problemas em seu ambiente computacional. O System Center oferece produtos que desenvolvem as seguintes funções:

    -   Monitoramento de hardware e software em um ambiente distribuído para detectar problemas, fornecendo ferramentas para solucionar esses problemas.

    -   Automatização do processo de instalação, atualização e correção de software.

    -   Fornecimento de implementações de processos padrão para o gerenciamento de sistemas.

    -   Uso de backup e restauração de dados do servidor de arquivos do Windows.

    -   Atendimento aos requisitos de configuração e monitoramento de organizações menores.

    -   Gerenciamento de máquinas virtuais. Como um hardware mais rápido permite a execução de mais aplicativos em cada máquina, as organizações estão aumentando significativamente a virtualização para isolar esses aplicativos.

    -   Dimensionamento adequado das instalações, fornecendo ferramentas para estimar os recursos necessários.

    Para obter mais informações, consulte a página do Microsoft System Center em <http://www.microsoft.com/systemcenter/default.aspx> (pode estar em inglês).  

#### Resumo

Esta seção fornece uma descrição das soluções tecnológicas que sua organização pode usar para atingir e a manter a conformidade com o PCI DSS. Ela discute porque essas soluções são importantes e oferece links para as orientações e as tecnologias da Microsoft que podem ajudar sua organização a atingir a conformidade com as regulamentações.

O efeito de implementar essas soluções não ajuda apenas a fornecer segurança e padrões de conformidade ao seu ambiente de TI, mas também tem um efeito positivo nos processos comerciais da organização. Antes de implementar qualquer uma das soluções identificadas, não deixe de obter aconselhamento de seus auditores e consultores jurídicos sobre suas próprias necessidades de estar em conformidade com o PCI DSS e considere cuidadosamente o impacto dessas soluções em toda a organização, não apenas em termos de conformidade. A Microsoft compromete-se em fornecer pesquisas e soluções mais detalhadas com relação ao PCI DSS e outra conformidade regulamentar. No entanto, você também pode pesquisar publicamente para buscar mais informações sobre esse complexo e importante assunto.

[![](images/Bb821241.arrow_px_up(pt-br,TechNet.10).gif)](#mainsection)[Top Of Page](#mainsection)

### Apêndices

Esta seção contém as perguntas mais comuns feitas pelos clientes sobre as soluções tecnológicas da Microsoft e como elas se ajustam para estar em conformidade com os requisitos do PCI DSS. Aqui você também encontrará um mapa com as soluções que podem ajudar sua organização a atender a esses requisitos.

#### Perguntas freqüentes

**P: Por que minha organização deve se preocupar em estar em conformidade com o padrão de segurança de dados do setor de cartões de pagamento? Este não é mais um padrão pouco útil e muito caro para ser obedecido?**

R: Existem três motivos para que sua organização trabalhe para estar em conformidade com o PCI DSS. O primeiro deles é que as bandeiras de cartões, como a Visa, comprometem-se a fornecer incentivos financeiros para quem estiver em conformidade com o PCI e visa aplicar penalidades para os não-conformes. Segundo, estar em conformidade pode ajudar a reduzir a responsabilidade em caso de perda de dados. Em terceiro lugar, como uma análise adequada e um projeto apropriado de seus sistemas, o processo pode ajudá-lo a controlar melhor os dados de seus clientes e, conseqüentemente, ajudá-lo a melhorar o seu serviço de atendimento e satisfação ao cliente.

**P: A Microsoft está vendendo suas tecnologias para a aplicação de conformidade com o PCI DSS?**

R: A situação de cada organização é diferente e este guia pretende ser o mais abrangente possível. A Microsoft pode desenvolver orientações específicas para mercados verticais. Você também pode entrar em contato com o seu representante de vendas da Microsoft para obter as orientações. Como definido anteriormente, você pode obter melhores resultados comerciais se observar esse ponto não apenas como um projeto para conformidade, mas sim como uma forma de melhorar seus processos de controle e gerenciamento de informações dos clientes.

**P: Este informe descreve muitas tecnologias que ajudam a estar em conformidade com o PCI DSS,** **mas muito poucas soluções de conformidade. Por quê?**

R: Cada situação é exclusiva e, por isso, não é possível propor uma solução única que possa se ajustar a todos. A Microsoft se compromete a oferecer à sua organização informações mais detalhadas, conforme mencionado no resumo.

**P: O que a Microsoft pode fazer para ajudar a minha organização a adquirir um certificado do PCI DSS?**

R: A Microsoft pode oferecer softwares e serviços que podem ajudá-lo a atender aos requisitos do PCI DSS, mas não pode garantir que sua organização obterá a conformidade. Como fornecedor, estamos muitos interessados em ajudar a sua organização a atender a tais requisitos, mas estar em conformidade é uma ação que deve ser considerada entre sua organização, seus auditores e as financeiras de cartões com as quais você trabalha.

**P: A Seção 3.4.1 não insinua que as tecnologias de proteção de dados da Microsoft não podem ser usadas?**

R: Não. A seção informa:

“Se a criptografia de um disco é adotada (não importando se o processo é aplicado a um arquivo, coluna ou banco de dados), o acesso lógico deve ser gerenciado de maneira independente dos mecanismos de controle de acesso do sistema operacional original (por exemplo, não utilizando contas do sistema local ou do Active Directory). As chaves de descriptografia não devem estar ligadas às contas de usuário.”

As tecnologias de proteção de dados da Microsoft não ligam as chaves de descriptografia às contas de usuário. Por exemplo, a Criptografia de Unidade de Disco BitLocker nunca vincula as chaves de descriptografia (PINs ou senhas de recuperação) às contas de usuário no Active Directory. O Sistema de arquivos com criptografia (EFS) também não vincula as chaves de descriptografia às contas de usuário. Sua organização pode revogar a capacidade de uma pessoa para descriptografar um documento sem alterar os privilégios de acesso do sistema. Em determinadas configurações, o EFS tenta otimizar a experiência do usuário, posicionando automaticamente algumas chaves de descriptografia nos perfis de determinados usuários. Entretanto, esse comportamento pode ser alterado usando uma configuração adequada para tal.

#### Requisitos do PCI DSS e soluções de tecnologia associadas

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Requisito</th>
<th style="border:1px solid black;" >Seções de solução de tecnologia</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Requisito 1</td>
<td style="border:1px solid black;"><a href="#_risk_assessment">Avaliação de riscos</a>; <a href="#_network_security">Segurança de rede</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Requisito 2</td>
<td style="border:1px solid black;"><a href="#_network_security">Segurança de rede</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Requisito 3</td>
<td style="border:1px solid black;"><a href="#_document_management">Gerenciamento de documentos</a>; <a href="#_risk_assessment">Avaliação de riscos</a>; <a href="#_data_classification_and_protection">Classificação e proteção de dados</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Requisito 4</td>
<td style="border:1px solid black;"><a href="#_risk_assessment">Avaliação de riscos</a>; <a href="#_messaging_and_collaboration">Serviço de mensagens e colaboração</a>; <a href="#_data_classification_and_protection">Classificação e proteção de dados</a>; <a href="#_network_security">Segurança de rede</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Requisito 5</td>
<td style="border:1px solid black;"><a href="#_risk_assessment">Avaliação de riscos</a>; <a href="#_malicious_software_prevention">Prevenção contra software mal-intencionado</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Requisito 6</td>
<td style="border:1px solid black;"><a href="#_document_management">Gerenciamento de documentos</a>; <a href="#_risk_assessment">Avaliação de riscos</a>; <a href="#_change_management">Gerenciamento de alterações</a>; <a href="#_host_control">Controle de host</a>; <a href="#_malicious_software_prevention">Prevenção contra software mal-intencionado</a>; <a href="#_application_security">Segurança de aplicativos</a>; <a href="#_authentication,_authorization,_and_">Autenticação, autorização e controle de acesso</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Requisito 7</td>
<td style="border:1px solid black;"><a href="#_document_management">Gerenciamento de documentos</a>; <a href="#_risk_assessment">Avaliação de riscos</a>; <a href="#_identity_management">Gerenciamento de identidade</a>; <a href="#_authentication,_authorization,_and_">Autenticação, autorização e controle de acesso</a>; <a href="#_data_classification_and_protection">Classificação e proteção de dados</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Requisito 8</td>
<td style="border:1px solid black;"><a href="#_risk_assessment">Avaliação de riscos</a>; <a href="#_authentication,_authorization,_and_">Autenticação, autorização e controle de acesso</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Requisito 9</td>
<td style="border:1px solid black;"><a href="#_document_management">Gerenciamento de documentos</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Requisito 10</td>
<td style="border:1px solid black;"><a href="#_document_management">Gerenciamento de documentos</a>; <a href="#_change_management">Gerenciamento de alterações</a>; <a href="#_monitoring,_auditing,_and_reporting">Monitoramento, Auditoria e Relatório</a>; <a href="#_network_security">Segurança de rede</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Requisito 11</td>
<td style="border:1px solid black;"><a href="#_risk_assessment">Avaliação de riscos</a>; <a href="#_host_control">Controle de host</a>; <a href="#_vulnerability_identification">Identificação de vulnerabilidade</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Requisito 12</td>
<td style="border:1px solid black;"><a href="#_document_management">Gerenciamento de documentos</a></td>
</tr>
</tbody>
</table>
  
#### Recursos adicionais
  
[*PCI DSS (Payment Card Industry Data Security Standard),* *versão 1.1*](https://www.pcisecuritystandards.org/pdfs/pci_dss_v1-1.pdf)
  
[*Guia de planejamento para conformidade com os regulamentos (em inglês)*](http://www.microsoft.com/technet/security/guidance/complianceandpolicies/compliance/rcguide/default.mspx?mfr=true)
  
[*Questionário de auto-avaliação do PCI DSS (em inglês)*](https://www.pcisecuritystandards.org/pdfs/pci_saq_v1-0.pdf)
  
[*Procedimentos de auditoria de PCI DSS do QSA (em inglês)*](https://www.pcisecuritystandards.org/pdfs/pci_audit_procedures_v1-1.pdf)
  
[*Procedimentos de verificação de PCI DSS do ASV (em inglês)*](https://www.pcisecuritystandards.org/pdfs/pci_scanning_procedures_v1-1.pdf)** **
  
[*Aplicando o princípio de contas de usuário sem privilégios administrativos no Windows XP (em inglês) *](http://www.microsoft.com/technet/prodtechnol/winxppro/maintain/luawinxp.mspx)* *
  
[*Práticas recomendadas para delegar a administração do Active Directory (em inglês)*](http://www.microsoft.com/downloads/details.aspx?familyid=631747a3-79e1-48fa-9730-dae7c0a1d6d3&displaylang=en)
  
[Centro de downloads do setor bancári*o*](http://msdn2.microsoft.com/en-us/architecture/86e3451d-8219-46af-bf99-4a610e4bf1f4.aspx)
  
#### Comentários
  
Envie suas dúvidas e seus comentários sobre este guia para <cisfdbk@microsoft.com>.
  
[![Top Of Page](images/Bb821241.arrow_px_up(pt-br,TechNet.10).gif)](#mainsection)[Top Of Page](#mainsection)
