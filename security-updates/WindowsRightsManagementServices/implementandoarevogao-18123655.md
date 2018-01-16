---
TOCTitle: Implementando a revogação
Title: Implementando a revogação
ms:assetid: '4735f060-7197-4ae2-830a-f91bcc4de30a'
ms:contentKeyID: 18123655
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747554(v=WS.10)'
---

Implementando a revogação
=========================

Certificados e licenças podem ser revogados por qualquer entidade que esteja na cadeia de confiança do certificado ou licença. Qualquer certificado ou licença emitido por um servidor raiz de certificação pode ser revogado por esse servidor raiz de certificação. Além disso, os certificados podem ser revogados por um terceiro que é escolhido pelo administrador do RMS.

Para revogar um certificado ou licença concedido por seu servidor RMS, você pode criar e distribuir uma lista de revogação e, em seguida, exigir a lista em um modelo de diretiva de direitos, conforme descrito nas seguintes etapas:

1.  Crie uma lista de revogação que especifique as entidades a serem revogadas. Esse é um arquivo de texto simples em formato XML que obedece ao vocabulário XrML. Para obter mais informações, consulte "[Criando listas de revogação](https://technet.microsoft.com/1ef75199-3344-4225-84de-a863a777696a)", mais adiante neste tema.
2.  Gere um par de chaves para a lista de revogação. Em seguida, assine o arquivo com a chave particular usando a ferramenta Assinatura da Lista de Revogação fornecida para esse fim. Para obter instruções, consulte "Inserindo uma assinatura em uma lista de revogação", mais adiante nesta seção. Você deve automatizar esse processo de forma que ele ocorra regularmente, de preferência diariamente.
3.  Coloque o arquivo da lista de revogação em um local acessível a todos os usuários que precisem dela. É recomendável colocar o arquivo em um local acessível tanto de sua rede como da Internet, de preferência em um site. Isso garante que os usuários possam acessar o arquivo tanto de dentro como de fora de sua rede corporativa.
4.  Crie um modelo de diretiva de direitos que inclua um requisito para a lista de revogação. Para obter mais informações, consulte "[Criando e modificando modelos de diretiva de direitos](https://technet.microsoft.com/6014176f-ef71-4d29-b3e3-da129c18563d)", mais adiante neste tema.

Também é possível revogar o certificado de licenciante servidor raiz de certificação. Como esse certificado foi emitido pelo Serviço de Inscrição Microsoft, a Microsoft pode revogar o certificado de licenciante servidor raiz de certificação. Para fazer isso, a Microsoft adiciona o certificado de licenciante servidor à sua lista de revogação e a disponibiliza publicamente.

Além disso, seu certificado de licenciante servidor raiz de certificação pode ser revogado por uma terceira autoridade se o administrador do RMS optar por habilitar essa opção durante a configuração. Se você usar essa opção, uma lista de revogação que inclua esse certificado de licenciante servidor que foi assinado pela chave particular da terceira autoridade deverá ser disponibilizada aos clientes. Para obter mais informações, consulte "[Revogando certificados de licenciante para servidor](https://technet.microsoft.com/8020861d-d196-4431-8282-044675ef5616)", mais adiante neste tema.

> [!Caution]  
> Tenha cuidado ao implementar revogação. Com base no intervalo de atualização especificado, você deve renovar uma lista de revogação periodicamente ou ela expirará automaticamente, o que impedirá que os usuários consumam conteúdo que exija essa lista. Para evitar que você impeça usuários de consumir conteúdo inadvertidamente, avalie cuidadosamente o intervalo requerido para atualizar a lista de revogação. Além disso, verifique se a lista de revogação pode ser acessada tanto de dentro como de fora da rede. Para obter mais informações, consulte "[Definindo diretivas de revogação](https://technet.microsoft.com/e2fffe9f-def7-439b-a8aa-43f8a065813d)", já mencionado neste tema. 
