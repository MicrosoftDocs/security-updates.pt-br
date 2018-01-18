---
TOCTitle: Registro do servidor raiz de certificação
Title: Registro do servidor raiz de certificação
ms:assetid: 'f08bc919-f090-4843-b2ce-b40d558012ce'
ms:contentKeyID: 18123830
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747734(v=WS.10)'
---

Registro do servidor raiz de certificação
=========================================

O registro com o Microsoft Enrollment Service é obrigatório para o primeiro servidor de uma implantação do RMS. Esse servidor, denominado servidor raiz de certificação, pode ser automaticamente registrado durante a configuração, se o servidor estiver conectado à Internet, ou pode ser registrado manualmente, se ele fizer parte de uma rede fechada. Para obter mais informações sobre o registro manual de servidores, consulte "Registrar manualmente um servidor raiz de certificação" em "Operando um servidor RMS", nesta coleção de documentos.

A solicitação de registro usa os seguintes parâmetros de entrada:

-   Uma chave pública de 1024 bits. Trata-se da chave pública do RMS.
-   A versão, o nome e a URL do servidor RMS a ser registrado.

O Microsoft Enrollment Service usa as informações somente para criar o certificado de licenciante para servidor e armazena as informações somente para fins de revogação.

O Microsoft Enrollment Service retorna uma cadeia de certificados que contém a cadeia de certificados de licenciante para o servidor de registro, bem como um certificado que é assinado pelo servidor de registro. O certificado contém a chave pública do servidor que é assinada com a chave particular de registro e a versão e a URL do servidor registrado. O certificado concede ao servidor raiz de certificação o direito de emitir, para servidores de licenciamento, certificados de licenciante para servidor, além de emitir certificados de conta de direitos, certificados de licenciante para cliente e licenças de publicação e de uso.

O certificado de licenciante para servidor é válido por um ano. O período de validade começa quando o certificado é emitido. No final do período de validade, o certificado pode ser renovado. Certificados e licenças que são emitidos pelo servidor são válidos por sete anos. O período de validade começa quando o certificado ou licença é emitido.

Informações sobre revogação do certificado são adicionadas ao certificado de licenciante para servidor na forma como é especificada na solicitação de registro. A chave pública do Microsoft Enrollment Service é adicionada ao certificado como uma chave de revogação. Além disso, se for especificada uma chave de revogação de terceiros, ela também será adicionada ao certificado como uma chave de revogação.
