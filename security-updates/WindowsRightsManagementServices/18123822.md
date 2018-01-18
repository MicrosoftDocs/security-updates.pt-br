---
TOCTitle: Descoberta do serviço de registro
Title: Descoberta do serviço de registro
ms:assetid: 'bbeb00bd-04e0-4df6-8615-76aa8125b620'
ms:contentKeyID: 18123822
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747737(v=WS.10)'
---

Descoberta do serviço de registro
=================================

O primeiro servidor RMS a ser configurado em uma floresta deve ser conectado ao Microsoft Enrollment Service para fazer o registro e obter um certificado de licenciante para servidor. Para obter a URL para o Microsoft Enrollment Service, a instalação do RMS faz uma solicitação UDDI ao [site de UDDI da Microsoft](http://go.microsoft.com/fwlink/?linkid=14794) (http://go.microsoft.com/fwlink/?LinkId=14794). Servidores subseqüentes que são fornecidos como parte do cluster raiz de certificação não precisam obter certificados de licenciante para servidor porque compartilham a configuração do primeiro servidor raiz de certificação.
