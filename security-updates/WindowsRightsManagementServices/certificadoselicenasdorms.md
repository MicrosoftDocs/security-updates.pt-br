---
TOCTitle: Certificados e licenças do RMS
Title: Certificados e licenças do RMS
ms:assetid: '91916ecb-9e5d-49e8-ab65-ef2c56339b83'
ms:contentKeyID: 18123698
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747600(v=WS.10)'
---

Certificados e licenças do RMS
==============================

Os diferentes componentes de uma instalação do RMS possuem conexões confiáveis que são implementadas por um conjunto de certificados. A aplicação da validade desses certificados é uma das principais funções da tecnologia do RMS. Cada parte de conteúdo protegido pelo RMS é publicada com uma licença que expressa suas respectivas regras de uso, e cada consumidor desse conteúdo recebe uma licença exclusiva que lê, interpreta e aplica essas regras de uso. Nesse contexto, uma licença é um tipo específico de certificado.

O RMS utiliza um vocabulário XML para expressar direitos de uso para o conteúdo protegido pelo RMS, o XrML (eXtensible rights Markup Language), versão 1.2.1. Para obter mais informações, consulte "XrML" mais adiante neste tema.

Os certificados e licenças que se encontram no RMS estão conectados em uma hierarquia, de modo que o RMS sempre poderá seguir uma cadeia de um determinado certificado ou licença, passando por certificados confiáveis, até um par de chaves confiáveis. Para obter mais informações, consulte "[Hierarquia de confiança do RMS](https://technet.microsoft.com/2d44182f-a653-4383-aba1-dade53f7cf9a)", mais adiante neste tema.

Esta seção inclui:

-   [Resumo dos certificados e licenças do RMS](https://technet.microsoft.com/637ccfca-318e-4346-85b5-0945b058fb9c)
-   [Certificados de licenciante para servidor](https://technet.microsoft.com/0b35fbcd-25a9-4587-898d-9a30fd1d3c5b)
-   [Certificados de licenciante para cliente](https://technet.microsoft.com/bfb36387-3e15-4cde-8b8f-482219569a64)
-   [Certificados de máquina do RMS](https://technet.microsoft.com/1841d53e-d01b-47c3-9d43-3805ceefed5a)
-   [Certificados de conta de direitos](https://technet.microsoft.com/2ff315cc-211d-4e6e-85e8-56867c2abd94)
-   [Licenças de publicação](https://technet.microsoft.com/187228fc-370b-4e23-a53a-21bb296b84a1)
-   [Licenças de uso](https://technet.microsoft.com/6e609db3-49b3-4cac-a34c-8a96da627067)
