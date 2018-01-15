---
TOCTitle: Chaves de conteúdo do RMS
Title: Chaves de conteúdo do RMS
ms:assetid: '63c814bf-2809-477e-a2db-d90370442075'
ms:contentKeyID: 18123615
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720284(v=WS.10)'
---

Chaves de conteúdo do RMS
=========================

Quando um autor publica conteúdo protegido pelo RMS, um aplicativo habilitado para RMS cria uma chave simétrica de conteúdo e utiliza-a para criptografar o conteúdo. O RMS usa a criptografia AES (Padrão Avançado de Criptografia) para criar a chave de conteúdo.

A chave de conteúdo é incluída na licença de publicação; ela é criptografada com a chave pública do servidor RMS que emitiu a licença.

Quando esse servidor recebe uma solicitação para uma licença de uso, ele descriptografa a chave de conteúdo com a chave particular do servidor e, em seguida, criptografa novamente a chave de conteúdo com a chave pública do usuário (que ele recebeu como parte da solicitação). Em seguida, a chave de conteúdo é contida na licença de uso.
