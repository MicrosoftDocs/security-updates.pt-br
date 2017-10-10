---
TOCTitle: Chaves do certificado de licenciante para cliente
Title: Chaves do certificado de licenciante para cliente
ms:assetid: '28781125-2692-4ff9-99b1-e09227d72966'
ms:contentKeyID: 18123547
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720221(v=WS.10)'
---

Chaves do certificado de licenciante para cliente
=================================================

Os autores podem adquirir certificados de licenciante para cliente, a fim de publicar conteúdo protegido pelo RMS, mesmo que não estejam conectados à rede habilitada para RMS. Um certificado de licenciante para cliente tem um par de chaves RSA de 1024 bits.

O cliente do RMS usa a chave pública do certificado de licenciante para cliente quando emite uma licença de publicação para executar as seguintes tarefas:

-   Criptografar a chave simétrica do conteúdo.
-   Assinar licenças de publicação que são emitidas localmente enquanto o usuário não está conectado à rede.
