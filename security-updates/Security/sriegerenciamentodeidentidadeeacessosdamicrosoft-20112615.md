---
TOCTitle: Série Gerenciamento de identidade e acessos da Microsoft
Title: Série Gerenciamento de identidade e acessos da Microsoft
ms:assetid: '8c4a4104-9d1e-47c5-b762-a15842254221'
ms:contentKeyID: 20112615
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc162924(v=TechNet.10)'
---

Série Gerenciamento de identidade e acessos da Microsoft
========================================================

### Visão geral

Publicado em: 11 de maio de 2004 | Atualizado em: 26 de junho de 2006

Esta série de artigos fornece diversos conceitos de gerenciamento de identidade e acessos, técnicas e soluções para uso em ambientes heterogêneos de TI.

O *Gerenciamento de identidade e acessos* combina processos, tecnologias e diretivas para gerenciar identidades digitais e especificar como elas são usadas para acessar recursos.

Envie seus comentários, perguntas e pedidos para artigos futuros para [secwish@microsoft.com](mailto:secwish@microsoft.com?subject=microsoft%20identity%20and%20access%20management%20series).

Este guia inclui os seguintes documentos:

##### Nesta página

[](#egaa)[Visão geral da série Gerenciamento de identidade e acessos da Microsoft](#eg)  
[]([](#efaa)[Parte I – A base do gerenciamento de identidade e acessos](#ef)  
[]([](#eeaa)[Parte II – Gerenciamento do ciclo de vida de identidades](#ee)  
[]([](#edaa)[Parte III – Gerenciamento de acessos e logon único](#ed)  
[]([](#ecaa)[Soluções complementares da Microsoft](#ec)  
[]([](#ebaa)[Recursos relacionados](#eb)  
[]([](#eaaa)[Envie seus comentários](#ea)  
[](
### Visão geral da série Gerenciamento de identidade e acessos da Microsoft

[**Visão geral da série Gerenciamento de identidade e acessos da Microsoft**](http://www.microsoft.com/brasil/technet/security/topics/identitymanagement/idmanage/overview.mspx)

A visão geral descreve a série, como ela é estruturada e fornece informações sobre:

-   Como acessar Ferramentas e Modelos.

-   Convenções de estilo nos artigos.

-   Serviços de consultoria e integradores de sistemas.

-   Fornecedores de hardware e software independentes.

[](#mainsection)[Início da página](#mainsection)

### Parte I – A base do gerenciamento de identidade e acessos

[**Conceitos essenciais**](http://www.microsoft.com/brasil/technet/security/topics/identitymanagement/idmanage/p1fund.mspx)

Este artigo inclui conceitos-chave, terminologia e tecnologias, bem como desafios e abordagens de gerenciamento de identidade e acessos para superá-los. A leitura deste artigo é pré-requisito para os outros artigos da série.

[**Plataforma e infra-estrutura**](http://www.microsoft.com/brasil/technet/security/topics/identitymanagement/idmanage/p1plat.mspx)

Este artigo define os requisitos de plataforma comum e uma infra-estrutura de tecnologia de todas as soluções de gerenciamento de identidade e acessos da série.

[](#mainsection)[Início da página](#mainsection)

### Parte II – Gerenciamento do ciclo de vida de identidades

[**Agregação e sincronização de identidades**](http://www.microsoft.com/technet/security/topics/identitymanagement/idmanage/p2ident.mspx)

Este artigo descreve as abordagens e tecnologias disponíveis para integração de armazenamento de identidade em um ambiente heterogêneo. Também oferece diretrizes detalhadas de implementação de agregação e sincronização de identidades entre florestas do serviço de diretório do Microsoft® Active Directory®, Sun ONE Directory Server 5.1 (anteriormente denominado iPlanet Directory Server) e Lotus Notes usando o Microsoft Identity Integration Server 2003, Enterprise Edition (MIIS 2003) com Service Pack 1 (SP1).

[**Gerenciamento de senhas**](http://www.microsoft.com/technet/security/topics/identitymanagement/idmanage/p2pass.mspx)

Este artigo descreve diversas abordagens de gerenciamento de senhas e inclui diretrizes sobre diretivas de senha e habilitação de redefinição de senha, alteração de senha e sincronização de senhas para vários armazenamentos de autenticação usando o MIIS 2003 com SP1. Também fornece diretrizes detalhadas de implementação, além de exemplos de códigos ASP.NET (no Microsoft Visual C\#® e no Microsoft Visual Basic® .NET) para:

-   Gerenciameno de senhas da intranet: Este cenário usa uma floresta do Active Directory da intranet como senha mestre (para diretiva), propagando alterações de senhas para o Lotus Notes e Sun ONE Directory Server 5.1 usando o MIIS 2003 com SP1.

-   Gerenciameno de senhas da extranet: Este cenário usa o código ASP.NET de exemplo para alteração de senha, redefinição de senha pessoal, relatórios e um script agendado para notificação de vencimento da senha.

[**Configuração e fluxo de trabalho**](http://www.microsoft.com/technet/security/topics/identitymanagement/idmanage/p2prov.mspx)

Este artigo discute como configurar identidades automaticamente em diversos diretórios e armazenamento de identidade em um ambiente heterogêneo, gerenciar associação em grupos de emails e segurança e implementar processos de fluxo de trabalho que estendem os processos automatizados. Também fornece diretrizes detalhadas de implementação, além de exemplos de códigos ASP.NET (no Microsoft Visual C\#® e no Microsoft Visual Basic® .NET) para:

-   Configuração controlada por recursos humanos: Este cenário descreve como os recursos humanos podem ser usados para controlar totalmente a configuração automatizada em um ambiente heterogêneo. O cenário usará o sistema SAP como sistema de recursos humanos e configurará contas no Active Directory da intranet, no Active Directory da extranet, no Lotus Notes e no Sun ONE Directory Server 5.1 (anteriormente denominado iPlanet Directory Server) usando o MIIS 2003 SP1.

-   Gerenciamento de grupos: Este cenário descreve como ter grupos de segurança e listas de distribuição gerenciados automaticamente com base nos atributos de identidade, como gerenciador, local etc. O cenário usará o Group Populator (incluso no MIIS 2003 SP1), uma tabela SQL para definições de grupo e fornecerá uma interface do usuário da Web ASP.NET básica para facilitar o trabalho do administrador ao estabelecer grupos computados com base no gerenciador, no local e em outros atributos.

-   Configuração da conta do prestador de serviço: Este cenário descreve como implementar um aplicativo de fluxo de trabalho de configuração usando o ASP.NET e o MIIS 2003 SP1 que facilita a criação e a configuração de contas de prestadores de serviços no ambiente heterogêneo da Contoso.

[](#mainsection)[Início da página](#mainsection)

### Parte III – Gerenciamento de acessos e logon único

[**Gerenciamento de acesso à intranet**](http://www.microsoft.com/technet/security/topics/identitymanagement/idmanage/p3intran.mspx)

Este artigo descreve as abordagens disponíveis para logon único (SSO) da intranet, gerenciamento de acessos e integração de aplicativos e plataformas. Também fornece diretrizes detalhadas de implementação para:

-   Integração de estações de trabalho UNIX com Active Directory.

-   Integração de autenticação do servidor de aplicativos do sistema SAP R/3 usando o protocolo de autenticação do Kerberos, versão 5.

[**Gerenciamento de acesso à extranet**](http://www.microsoft.com/technet/security/topics/identitymanagement/idmanage/p3extran.mspx)

Este artigo descreve as abordagens disponíveis para logon único na extranet, gerenciamento de acessos e fornecimento de Business to Consumer (B2C), Business to Business (B2B) e Business to Employee (B2E). Também fornece diretrizes detalhadas de implementação para:

-   Acesso à Web via extranet B2E e SSO usando certificados X.509.

-   Acesso à Web via extranet B2C e SSO usando o Microsoft Passport.

[**Desenvolvendo aplicativos ASP.NET com reconhecimento de identidades**](http://www.microsoft.com/technet/security/topics/identitymanagement/idmanage/p3aspd.mspx)

Este artigo descreve abordagens para a construção de aplicativos ASP.NET da Microsoft de várias camadas integrados ao Active Directory (para autenticação, autorização e log de segurança), além de diretrizes detalhadas de implementação e exemplos de códigos ASP.NET (no Microsoft Visual C\#® e no Microsoft Visual Basic® .NET) para:

-   Aplicativos para Web da intranet que usam autenticação integrada ao Windows e Gerenciador de autorização do Windows.

-   Aplicativos para Web da extranet para cenários B2B, B2C e B2E que usam autenticação do Windows (incluindo autenticação com base em formulários, certificados X.509 e Microsoft Passport) e Gerenciador de autorização do Windows.

[](#mainsection)[Início da página](#mainsection)

### Soluções complementares da Microsoft

**Microsoft Solutions for Security**

Esta série é a última diretriz do Microsoft Solutions for Security (MSS), que também produziu o [*Guia de Segurança do Windows Server 2003*](http://go.microsoft.com/fwlink/?linkid=14845) e o [*Guia de Segurança do Windows XP*](http://go.microsoft.com/fwlink/?linkid=14839). A *série Gerenciamento de identidade e acessos da Microsoft* foi preparada e testada em computadores configurados com esses guias de segurança.

**Arquitetura de referência do Windows Server System**

Esta diretriz inclui plantas de arquitetura comprovadas e testadas em laboratório e diretrizes de implementação. A *série Gerenciamento de identidade e acessos da Microsoft* foi preparada e testada em um ambiente baseado nas diretrizes da Arquitetura de referência do Windows Server System (WSSRA). Para obter mais infomações sobre WSSRA, consulte a página [Arquitetura de referência do Windows Server System](http://www.microsoft.com/technet/itsolutions/wssra/default.mspx) em Microsoft.com.

**Guia de soluções de Segurança do Windows e Serviços de diretório para UNIX**

O [Guia de soluções de Segurança do Windows e Serviços de diretório para UNIX](http://go.microsoft.com/fwlink/?linkid=23115) fornece diretrizes para habilitar o Microsoft Windows Server™ 2003 Active Directory, o protocolo Kerberos versão 5 e os serviços LDAP para autenticação e autorização em ambientes heterogêneos do Windows e do UNIX.

[](#mainsection)[Início da página](#mainsection)

### Recursos relacionados

Na equipe do Microsoft Solutions for Security and Compliance (MSSC), leia [outras soluções de segurança](http://www.microsoft.com/technet/community/columns/sectip/st0805.mspx).

[](#mainsection)[Início da página](#mainsection)

### Envie seus comentários

A equipe do Microsoft Solutions for Security and Compliance (MSSC) agradece suas idéias e outras soluções de segurança.

Tem uma opinião? Comente-a no [Blog de soluções de segurança](http://blogs.technet.com/secguide/) do profissional de TI.

Ou envie email com seus comentários para o seguinte endereço: [SecWish@microsoft.com](mailto:secwish@microsoft.com?subject=microsoft%20identity%20and%20access%20management%20series). Sempre respondemos os comentários dessa caixa de correio.

Aguardamos suas opiniões.

[](#mainsection)[Início da página](#mainsection)

**Download**

[Obtenha a série Gerenciamento de identidade e acessos da Microsoft](http://go.microsoft.com/fwlink/?linkid=14842)

**Notificações de atualização**

[Inscreva-se para receber informações sobre atualizações e novas versões](http://go.microsoft.com/fwlink/?linkid=54982)

**Comentários**

[Envie seus comentários ou suas sugestões](mailto:secwish@microsoft.com?subject=microsoft%20identity%20and%20access%20management%20series)

[](#mainsection)[Início da página](#mainsection)
