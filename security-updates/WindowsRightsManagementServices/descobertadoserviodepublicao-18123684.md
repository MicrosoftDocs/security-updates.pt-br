---
TOCTitle: Descoberta do serviço de publicação
Title: Descoberta do serviço de publicação
ms:assetid: '5d500841-a202-4865-b5d2-d0775d4e1bbc'
ms:contentKeyID: 18123684
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747580(v=WS.10)'
---

Descoberta do serviço de publicação
===================================

O serviço de publicação do RMS emite licenças de publicação, as quais são usadas para proteger conteúdo. Ele também emite certificados de licenciante para cliente que permitem que usuários publiquem conteúdo enquanto não estão conectados à rede corporativa.

O serviço de publicação está disponível no cluster raiz de certificação ou nos servidores de licença. Um aplicativo habilitado para RMS solicita esse serviço quando um autor publica conteúdo protegido pelo RMS. Para fazer uma solicitação de serviço de publicação, primeiro o aplicativo recupera, a partir do Active Directory, a URL para o diretório virtual Licenciamento do servidor, onde o serviço de publicação está localizado. Em seguida, ele anexa o caminho para o serviço de publicação.

Por exemplo, a URL para o diretório virtual Licenciamento de um servidor é armazenada no Active Directory, na seguinte forma:

http://*nome\_do\_servidor*/\_wmcs/Licensing

Quando um servidor solicita uma licença de publicação, ele anexa o nome do arquivo do serviço de publicação à URL, da seguinte forma:

http://*nome\_do\_servidor*/\_wmcs/Licensing/Publish.asmx

Se o RMS detectar que o certificado de conta de direitos baseia-se na autenticação de usuário do Windows, o local do serviço de publicação será determinado pela floresta do Active Directory. Isso se aplica aos usuários internos e externos que se conectam à rede corporativa por meio de uma rede virtual privada (VPN).

Se o RMS detectar que o certificado de conta de direitos baseia-se no Microsoft® .NET Passport, o local do serviço de publicação será a conta do .NET Passport especificada no conteúdo protegido pelo RMS.

> [!Note]  
> Se você habilitou a SSL no servidor RMS, essas URLs usarão o protocolo de conexão https://.
