---
TOCTitle: Definindo diretivas de confiança
Title: Definindo diretivas de confiança
ms:assetid: 'e8d78300-4b26-4f15-9e4f-5ae9eb827ef9'
ms:contentKeyID: 18123810
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747711(v=WS.10)'
---

Definindo diretivas de confiança
================================

É possível definir domínios de usuários confiáveis e de publicação da seguinte maneira:

-   **Domínios de usuários confiáveis**. Quando você adiciona um domínio de usuário, o RMS pode processar solicitações de licenças de uso de usuários cujos certificados de conta de direitos tenham sido emitidos por uma instalação do RMS de uma floresta diferente do Active Directory. Em outras palavras, um cluster raiz de certificação diferente. Você adiciona um domínio de usuário confiável importando o certificado de licenciante para servidor da instalação a confiar.
-   **Domínios de publicação confiáveis**. A adição de um domínio de publicação permite que um servidor RMS emita licenças de uso em relação a licenças de publicação que foram emitidas por um outro servidor RMS. Você adiciona um domínio de publicação confiável importando o certificado de licenciante para servidor e a chave particular do servidor a confiar.

Para obter mais informações, consulte as seções "[Adicionando e removendo domínios de usuário confiáveis](https://technet.microsoft.com/7c440b15-01c4-49f1-b43c-00f67f3388c1)" e "[Adicionando e removendo domínios de usuário confiáveis](https://technet.microsoft.com/d87b502d-5497-4ccd-badf-f6807d587cee)", mais adiante neste tema. Para obter instruções detalhadas, consulte a seção "[Estabelecer diretivas de confiança](https://technet.microsoft.com/6c2be3c2-1837-4de4-a72e-3ba3eec3321d)", mais adiante neste tema.
