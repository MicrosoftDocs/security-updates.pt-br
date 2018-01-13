---
TOCTitle: Registro do cliente do RMS
Title: Registro do cliente do RMS
ms:assetid: '9c1d07bf-7235-4694-8291-ac2e5b221f4a'
ms:contentKeyID: 18123716
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747613(v=WS.10)'
---

Registro do cliente do RMS
==========================

Os computadores clientes podem ser registrados com o serviço de publicação do RMS para receber um certificado de licenciante para cliente do RMS, o qual permite que os autores publiquem conteúdo protegido pelo RMS quando seus computadores não estiverem conectados à rede corporativa. Nesse caso, o computador cliente, e não o serviço de publicação, assina e emite as licenças de publicação que contêm as informações sobre os direitos de uso para o conteúdo protegido pelo RMS publicado com esse computador.

O serviço de publicação do RMS emite certificados de licenciante para cliente.

O registro do cliente inclui as seguintes etapas:

1.  O computador cliente envia o certificado de conta de direitos do usuário em uma solicitação de registro ao serviço de publicação que está sendo executado no servidor ou cluster raiz de certificação, ou em um servidor ou cluster de licenciamento.
2.  O servidor confirma que o registro do cliente foi permitido, com base nas configurações do administrador da rede, e que o certificado de conta de direitos não está em uma lista de exclusão no banco de dados de configuração. Para obter informações sobre como criar listas de exclusão, consulte "Gerenciando diretivas de exclusão" em "Operando um servidor RMS”, nesta coleção de documentos.
3.  O serviço de publicação cria um par de chaves para o computador cliente. Ele cria um certificado de licenciante para cliente e coloca a chave pública no certificado. Ele criptografa a chave particular com a chave pública do certificado de conta de direitos e depois a coloca no certificado.
4.  O serviço de publicação emite um certificado de licenciante para cliente para o computador cliente.
