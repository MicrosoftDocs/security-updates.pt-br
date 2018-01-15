---
TOCTitle: Descoberta do serviço de certificação de conta
Title: Descoberta do serviço de certificação de conta
ms:assetid: '293a2f91-4712-45ec-8b74-7533f4144cbd'
ms:contentKeyID: 18123541
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720224(v=WS.10)'
---

Descoberta do serviço de certificação de conta
==============================================

O serviço Certificação de conta do RMS concede certificados de conta de direitos aos usuários. Cada certificado de conta de direitos é válido apenas para um computador ou dispositivo específico e requer que o usuário solicitante possua um certificado de máquina válido.

Somente o servidor ou cluster raiz de certificação executa o serviço de certificação de conta. Para fazer uma solicitação de certificado de conta, primeiro o cliente recupera, a partir do Active Directory, a URL para o diretório virtual de certificação do servidor raiz de certificação, onde o serviço de certificação de conta está localizado. Em seguida, ele anexa o caminho para o serviço de certificação de conta.

Por exemplo, a URL de certificação do servidor raiz de certificação é armazenada, no Active Directory, na seguinte forma:

http://*nome\_do\_servidor*/\_wmcs/Certification

Quando um cliente solicita um certificado de conta de direitos, ele acrescenta à URL o nome de arquivo do serviço de certificação de conta, da seguinte maneira:

http://*nome\_do\_servidor*/\_wmcs/Certification/Certification.asmx

| ![](images/Cc720224.note(WS.10).gif)Observação                 |
|---------------------------------------------------------------------------------------------|
| Se você habilitou a SSL no servidor RMS, essas URLs usarão o protocolo de conexão https://. |
