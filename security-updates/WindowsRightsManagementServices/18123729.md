---
TOCTitle: 'Sub-registro do servidor de licenciamento'
Title: 'Sub-registro do servidor de licenciamento'
ms:assetid: '7bc63397-9186-464c-8824-867038adce9b'
ms:contentKeyID: 18123729
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747640(v=WS.10)'
---

Sub-registro do servidor de licenciamento
=========================================

Os servidores de licenciamento são registrados automaticamente durante a configuração, em um processo chamado sub-registro. Entretanto, quando você adiciona um novo servidor a um cluster de servidor de licenciamento, o sub-registro do novo servidor não é feito explicitamente porque esse servidor utiliza o certificado de licenciante para servidor e o banco de dados de configuração do cluster.

Em vez de enviar a solicitação de sub-registro ao Microsoft Enrollment Service, o servidor de licenciamento envia a solicitação ao servidor raiz de certificação. A solicitação de sub-registro para um servidor de licenciamento é idêntica a uma solicitação de registro para o servidor raiz de certificação.

Quando o servidor raiz de certificação recebe uma solicitação de sub-registro, ele confirma que a solicitação está bem-formada e depois retorna uma cadeia de certificados que contém a cadeia de certificados de licenciante do servidor raiz de certificação e um certificado assinado pelo servidor raiz de certificação. O certificado contém a chave pública do servidor que é assinada com a chave particular do servidor de certificação. Ele concede ao servidor de licença o direito de emitir licenças de uso e de publicação.

O certificado de licenciante para servidor é válido por um ano. O período de validade começa quando o certificado é emitido. No final do período de validade, o certificado pode ser renovado. Certificados e licenças que são emitidos pelo servidor são válidos por sete anos. O período de validade começa quando o certificado ou licença é emitido.

Por padrão, o serviço necessário para processar uma solicitação de sub-registro no servidor raiz de certificação, SubEnrollService.asmx, é configurado para recusar todo acesso. Você deve alterar as listas de controle de acesso condicionais para permitir o acesso do administrador do RMS antes do processamento de uma solicitação.
