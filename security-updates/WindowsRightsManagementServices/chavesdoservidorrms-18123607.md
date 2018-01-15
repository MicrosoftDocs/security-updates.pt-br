---
TOCTitle: Chaves do servidor RMS
Title: Chaves do servidor RMS
ms:assetid: '5f4100a1-9aa5-42af-85c8-4bc691022f06'
ms:contentKeyID: 18123607
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720280(v=WS.10)'
---

Chaves do servidor RMS
======================

Um servidor RMS possui um par de chaves com chaves RSA de 1024 bits.

A chave pública do servidor é usada para criptografar a chave de conteúdo que está em uma licença de publicação, de modo que apenas o servidor RMS possa recuperar a chave de conteúdo e emitir licenças de uso em relação a essa licença de publicação. O certificado de licenciante para servidor contém a chave pública do servidor.

A chave particular do servidor é usada para assinar todos os certificados e licenças emitidas pelo servidor.

Proteção da chave particular do servidor
----------------------------------------

Por padrão, durante a configuração, a chave particular do servidor é criada e armazenada no banco de dados do RMS, em formato criptografado. Como alternativa, durante a configuração, você pode especificar um provedor de serviços de criptografia que já esteja instalado no servidor.

É possível usar um provedor de serviços de criptografia de duas maneiras diferentes:

-   Escolher entre implementações de software de provedor de serviço de criptografia que estejam instaladas com o servidor.
    -ou-
-   Usar um CSP (provedor de serviços de criptografia) para software não-Microsoft que você instalou no servidor.

> [!Note]  
> Se desejar usar um módulo de segurança de hardware, certifique-se de selecionar um provedor de serviços de criptografia que ofereça suporte a módulos de segurança de hardware. 

Se você optar por proteger a chave particular do servidor usando um CSP, o RMS armazenará o nome do provedor e o nome do recipiente da chave que está no banco de dados de configuração.
