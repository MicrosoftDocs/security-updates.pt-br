---
TOCTitle: Alterando a chave particular do RMS
Title: Alterando a chave particular do RMS
ms:assetid: 'da32137e-394a-42b2-9552-ba20f4547c23'
ms:contentKeyID: 18123856
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747765(v=WS.10)'
---

Alterando a chave particular do RMS
===================================

Durante a configuração, o RMS cria sua chave particular para o servidor. A chave particular do RMS é criptografada e armazenada no banco de dados de configuração. É recomendável fazer backup da chave particular e armazená-la em local seguro. Além disso, pense em usar um módulo de segurança de hardware para proteger a chave particular do RMS, porque ela é usada no esquema de criptografia de todo o conteúdo protegido pelo servidor RMS. Se, por algum motivo, a chave particular do RMS for afetada, você deverá desconfigurar e reconfigurar o RMS no servidor para obter uma nova chave particular.

Se o servidor tiver sido usado para proteger conteúdo, todos os proprietários de conteúdo deverão ser notificados, e o conteúdo deverá ser republicado usando-se o servidor RMS com a nova chave particular. Quaisquer cópias do conteúdo protegido pela chave particular afetada deverão ser destruídas, pois não poderão ser consideradas adequadamente protegidas.

> [!Important]  
> Independentemente de o servidor ter sido inscrito com o Serviço de Inscrição da Microsoft, ele deverá repetir o processo de configuração para obter uma nova chave particular. Se você apenas tentar reinscrever um servidor RMS, a chave particular anterior do RMS será usada. 
