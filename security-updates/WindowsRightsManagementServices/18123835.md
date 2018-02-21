---
TOCTitle: Publicação offline
Title: Publicação offline
ms:assetid: 'f6384ed2-f917-442e-aa63-c1394a1c4d06'
ms:contentKeyID: 18123835
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747741(v=WS.10)'
---

Publicação offline
==================

A publicação offline difere da publicação online devido ao modo como o aplicativo habilitado para RMS adquire a licença de publicação.

Antes de publicar conteúdo offline, o autor deve adquirir um certificado de licenciante para cliente enquanto tem acesso à rede para o servidor raiz de certificação.

O processo de publicação offline envolve as seguintes etapas:

1.  O autor cria o documento usando um aplicativo habilitado para RMS e depois especifica os direitos e as condições para o conteúdo.
2.  Quando o autor salva o arquivo, o certificado de licenciante para cliente permite que o computador ou dispositivo local emita e assine uma licença de publicação para o arquivo.
    A licença de publicação contém duas cópias da chave de conteúdo: uma que é criptografada com a chave pública do certificado de licenciante para cliente e uma que é criptografada com a chave pública do servidor que emitiu o certificado de licenciante para cliente. Ela também contém a URL do servidor. As duas chaves públicas e a URL são oriundas do certificado de licenciante para cliente.
3.  O computador usa o certificado de licenciante para cliente a fim de criar uma licença de proprietário, que é uma licença de uso especial que concede ao autor o direito de consumir o conteúdo protegido pelo RMS, mesmo estando offline. O certificado de licenciante para cliente usa sua chave particular para descriptografar a chave simétrica do conteúdo da licença de publicação e a criptografa novamente para a licença de proprietário.
4.  O aplicativo criptografa o arquivo com a chave de conteúdo e vincula a licença de publicação ao arquivo. Somente o servidor RMS que emitiu a licença de publicação ou um servidor que seja membro de um domínio de publicação confiável pode emitir licenças para descriptografar esse arquivo.
