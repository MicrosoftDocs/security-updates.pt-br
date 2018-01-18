---
TOCTitle: Protegendo servidores RMS
Title: Protegendo servidores RMS
ms:assetid: '7e6c4d3a-6cfb-4e96-9dda-ead83f961a6e'
ms:contentKeyID: 18123659
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747574(v=WS.10)'
---

Protegendo servidores RMS
=========================

É possível usar as seguintes recomendações para gerenciar contas de usuário e configurações de segurança que estão nos servidores RMS:

-   Os diretórios virtuais do site que você usa para administrar o RMS têm listas de controle de acesso condicional que permitem o acesso somente a administradores locais. Um administrador local pode criar um grupo de segurança adicional para controlar ainda mais o acesso adicionando e removendo membros e configurando entradas de controle de acesso adicionais nas páginas de administração da Web.
-   Para obter maior segurança, altere as configurações da lista de controle de acesso condicional da página da Web Configurações de segurança (SecurityPolicy.asmx). Para permitir a configuração, a entrada de controle de acesso padrão permite controle total à conta que configura o RMS. Depois da configuração, você deve alterar a entrada de controle de acesso para uma pessoa ou para um grupo de segurança restrito.
-   Além das permissões e direitos de cada servidor RMS, dê atenção especial aos requisitos de proteção do banco de dados de configuração, o que é vital para proteger toda a implantação. Para obter mais informações, consulte "[Protegendo o banco de dados de configuração](https://technet.microsoft.com/e023b96f-81d0-45fb-8cc5-becaf6d47ae1)", mais adiante neste tema.

Para obter mais informações sobre como proteger o Microsoft SQL Server™, consulte a página da Web do **SQL Server Security** no [site da Microsoft](http://www.microsoft.com/) (http://www.microsoft.com/).

Para obter mais informações sobre como proteger computadores que executam um membro da família de sistemas operacionais Microsoft Windows Server 2003, obtenha o "Guia de Segurança do Windows Server 2003" na Central de Download da Microsoft, disponível no [site da Microsoft](http://www.microsoft.com/%20(http://www.microsoft.com/)).
