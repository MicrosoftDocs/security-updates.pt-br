---
TOCTitle: Licenças de publicação
Title: Licenças de publicação
ms:assetid: '187228fc-370b-4e23-a53a-21bb296b84a1'
ms:contentKeyID: 18123593
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720211(v=WS.10)'
---

Licenças de publicação
======================

Os usuários de aplicativos habilitados para RMS podem atribuir a arquivos e informações digitais direitos de uso específicos que sejam consistentes com suas diretivas corporativas. Esses direitos de uso são armazenados em licenças de publicação que especificam os usuários que podem exibir o conteúdo, bem como de que modo eles podem editar e distribuir o conteúdo.

Uma licença de publicação pode ser emitida por um aplicativo cliente habilitado para RMS, pelo servidor raiz de certificação ou por um servidor de licenciamento RMS. Quando uma licença de publicação é emitida por um aplicativo cliente habilitado para RMS, o servidor RMS concede ao aplicativo um certificado de licenciante para cliente. Isto também é conhecido como publicação offline. É um método comum de publicação porque permite que os usuários dos aplicativos habilitados para RMS criem conteúdo protegido sem a necessidade de conectar-se ao servidor RMS. Se o aplicativo cliente habilitado para RMS não utilizar um certificado de licenciante para cliente, o usuário deverá estar conectado a um servidor RMS para receber uma licença de publicação para o conteúdo protegido.

A licença de publicação contém a chave simétrica de conteúdo para descriptografar o conteúdo que for criptografado com a chave pública do servidor RMS. Isso garante que somente o servidor possa descriptografar o conteúdo e emitir licenças de uso.

Uma licença de publicação é assinada pela chave particular do servidor que a está emitindo ou pela chave particular do certificado de licenciante para cliente.
