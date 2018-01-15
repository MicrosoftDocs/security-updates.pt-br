---
TOCTitle: Hierarquia de confiança do RMS
Title: Hierarquia de confiança do RMS
ms:assetid: '2d44182f-a653-4383-aba1-dade53f7cf9a'
ms:contentKeyID: 18123614
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720232(v=WS.10)'
---

Hierarquia de confiança do RMS
==============================

Os componentes envolvidos em um sistema RMS incluem o Microsoft Enrollment Service, servidores RMS organizacionais, computadores clientes e usuários do sistema. Um certificado que estabelece sua identidade no sistema é emitido para cada componente. A hierarquia de confiança define o relacionamento de confiança entre esses certificados e portanto as entidades que os mantém. Ela também define o relacionamento de confiança entre entidades confiáveis e as licenças que elas emitem para outras entidades confiáveis.

A hierarquia de confiança conecta certificados e licenças em uma cadeia de confiança que o RMS sempre poderá seguir, de um determinado certificado ou licença até um par de chaves confiáveis. A cadeia de confiança inclui o certificado atual, o certificado da entidade que o emitiu, o certificado da entidade que emitiu esse certificado da entidade e assim por diante, acima na cadeia até a raiz de confiança.

Para o RMS, a raiz de confiança, ou a "âncora de confiança", é um par de chaves da Microsoft. Essa raiz comum de confiança permite que uma organização construa um ecossistema de confiança que abrange entidades confiáveis, como usuários e parceiros, tanto dentro como fora da organização.

O diagrama a seguir exibe a hierarquia de confiança em uma organização. A cadeia de confiança retorna até os serviços Microsoft que emitiram os certificados básicos.

![](images/Cc720232.6c169175-94fb-4ec0-93bc-12748aae3ac4(WS.10).gif)
1.  Para cada computador cliente, é emitido um cofre exclusivo que contém a chave pública da raiz da Microsoft.
2.  Ao receber uma solicitação de licença, o RMS valida as entidades, seguindo o caminho que está na hierarquia de confiança até a raiz de confiança.
3.  O RMS verifica a autenticidade da entidade confiável indicada na licença.
4.  O RMS verifica se o certificado da entidade confiável foi emitido por um servidor que está na hierarquia de confiança.

Em cada nível da cadeia de certificados, o RMS valida a licença ou certificado e depois verifica se estabelece conexão com uma raiz de confiança conhecida através de uma cadeia de confiança. Cada licença ou certificado da cadeia é verificado pelo RMS para validar as seguintes condições:

-   Seu XrML é válido.
-   A assinatura do emissor é válida.
-   As semânticas da licença são apropriadas para o uso pretendido.
-   As condições (como datas de validade) são atendidas.
-   A licença não foi revogada.
-   A chave de assinatura da licença e a chave do emissor do certificado correspondem.
