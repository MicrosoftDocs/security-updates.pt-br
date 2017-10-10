---
TOCTitle: Descoberta do serviço de licenciamento
Title: Descoberta do serviço de licenciamento
ms:assetid: '4eabbb76-b359-443a-b737-098c5659e9c6'
ms:contentKeyID: 18123589
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720269(v=WS.10)'
---

Descoberta do serviço de licenciamento
======================================

O serviço de licenciamento do RMS emite licenças de uso, as quais permitem que usuários autenticados consumam conteúdo protegido.

Esse serviço é executado nos servidores ou em clusters raiz de certificação e de licença. Para criar uma solicitação de licença, um cliente primeiro recupera a URL para o diretório virtual de licenciamento do cluster raiz de certificação, onde o serviço de licenciamento está localizado, do Active Directory. Em seguida, ele anexa o caminho para o serviço de licenciamento.

Por exemplo, a URL para o diretório virtual de licenciamento de um cluster é armazenado no Active Directory da seguinte forma:

http://*nome\_do\_servidor*/\_wmcs/Licensing

Quando um servidor solicita uma licença de uso, ele anexa o nome do arquivo do serviço de licenciamento à URL, da seguinte forma:

http://*nome\_do\_servidor*/\_wmcs/Licensing/License.asmx

O local de serviço é o servidor RMS ou a conta do .NET Passport que emitiu a licença de publicação; a URL é incluída na licença de publicação.

| ![](images/Cc720269.note(WS.10).gif)Observação                 |
|---------------------------------------------------------------------------------------------|
| Se você habilitou a SSL no servidor RMS, essas URLs usarão o protocolo de conexão https://. |
