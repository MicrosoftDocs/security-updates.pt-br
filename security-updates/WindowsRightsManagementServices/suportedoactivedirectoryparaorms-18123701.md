---
TOCTitle: Suporte do Active Directory para o RMS
Title: Suporte do Active Directory para o RMS
ms:assetid: '9589127d-19b3-44f1-b7a1-01992e78218a'
ms:contentKeyID: 18123701
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747604(v=WS.10)'
---

Suporte do Active Directory para o RMS
======================================

O RMS usa o Active Directory para os seguintes propósitos:

-   **Fornecer autenticação de usuário.** O Active Directory fornece os serviços de diretório que são usados para autenticar os usuários do RMS. Para obter mais informações sobre autenticações e o RMS, consulte "[Modelo de segurança do RMS](https://technet.microsoft.com/665db831-366d-4dca-9bb3-cc2912481fe1)", mais adiante neste tema.
-   **Resolver participações de grupos e identidades de contas de usuários individuais.** O Active Directory fornece as informações sobre participação de grupo que o RMS utiliza para conceder licenças de uso ao conteúdo protegido pelo RMS quando a licença de publicação concede direitos a grupos em vez de concedê-los a contas de usuários individuais. A fim de reduzir o número de consultas LDAP feitas ao Active Directory, o RMS armazena em cache as informações obtidas em um cache local, bem como em um banco de dados dos serviços de diretório centralizado. Para obter mais informações, consulte "[Cache do Active Directory do RMS](https://technet.microsoft.com/c721a2eb-2fe9-4346-b426-3cc169b97265)" e "[Banco de dados dos serviços de diretório do RMS](https://technet.microsoft.com/6f6b8586-5d17-4a40-94a3-4dc738195301)", já mencionados neste tema.
-   **Armazenar o local de descoberta de serviços do RMS.** As solicitações de serviços (como para uma licença de uso, licença de publicação ou sub-registro de um servidor de licenciamento) devem ser enviadas à URL do módulo executável do serviço da Web que está concedendo a solicitação. Todas as solicitações de serviço começam com uma consulta do Active Directory para a URL do serviço da Web do servidor (Server.asmx) que por sua vez fornece a URL apropriada para a solicitação de serviço. Para obter mais informações, consulte a seção "[Publicação e descoberta de serviços do RMS](https://technet.microsoft.com/336c0d55-fd7f-4aa9-b3e6-bfd6565b1086)", mais adiante neste tema.
