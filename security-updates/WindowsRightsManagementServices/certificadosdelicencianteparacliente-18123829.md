---
TOCTitle: Certificados de licenciante para cliente
Title: Certificados de licenciante para cliente
ms:assetid: 'bfb36387-3e15-4cde-8b8f-482219569a64'
ms:contentKeyID: 18123829
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747744(v=WS.10)'
---

Certificados de licenciante para cliente
========================================

Um certificado de licenciante para cliente concede ao usuário o direito de publicar conteúdo protegido pelo RMS sem estar conectado à rede corporativa.

Para obter um certificado de licenciante para cliente, um autor inicia uma solicitação de registro do cliente para o servidor raiz de certificação ou para um servidor de licença de um computador cliente. Em seguida, o servidor retorna um certificado de licenciante para cliente ao computador.

Um certificado de licenciante para cliente contém a chave pública de licenciante para cliente, juntamente com a chave particular do licenciante que é criptografada pela chave pública do autor que solicitou o certificado. Ele também contém a chave pública do servidor que emitiu o certificado, que é assinado pela chave particular do servidor que emitiu o certificado. A chave particular de licenciante para cliente é usada para assinar licenças de publicação criadas pelo autor.
