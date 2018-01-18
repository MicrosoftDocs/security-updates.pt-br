---
TOCTitle: Revogação no RMS
Title: Revogação no RMS
ms:assetid: '72689f90-f3c5-4b61-94ea-d825f3199b3b'
ms:contentKeyID: 18123710
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747622(v=WS.10)'
---

Revogação no RMS
================

A revogação é um mecanismo que revoga uma credencial que já foi emitida, como um certificado ou uma licença. A principal finalidade da revogação é impedir que as entidades que não são mais confiáveis participem de um sistema RMS. Por exemplo, a revogação pode ser aplicada nos seguintes cenários:

-   Para impedir que o conteúdo seja consumido quando houver um comprometimento de uma entidade ou identidade que está na cadeia de confiança, como ocorre quando uma pessoa deixa a organização e não mais deve ser capaz de exibir conteúdo protegido pelo RMS.
-   Para impedir que um determinado aplicativo habilitado para RMS abra conteúdo, se o aplicativo deixou de ser confiável.
-   Para impedir que conteúdo contestável que já foi distribuído e licenciado para consumo continue sendo consumido.

A revogação funciona no cliente para evitar que usuários consumam uma parte do conteúdo, mesmo que uma licença de uso já tenha sido emitida para ele. Quando você habilita a revogação, ela é acionada sempre que um usuário tenta consumir conteúdo protegido, não importando se o usuário possui uma cópia da licença de uso armazenada localmente ou se está solicitando uma nova licença ao servidor RMS no momento do consumo.

A seção fornece uma visão geral da revogação. Para obter informações sobre como usar a revogação com o RMS, consulte "Gerenciando a revogação" em "Operando um servidor RMS”, nesta coleção de documentos.

Esta seção inclui:

-   [Como a revogação do RMS funciona](https://technet.microsoft.com/469e3938-a59b-4c92-9779-ead64e724d00)
-   [Listas de revogação do RMS](https://technet.microsoft.com/688d4dfa-c928-4b2f-8116-2f9e87d2b6f7)
-   [Revogação nos modelos de diretiva de direitos](https://technet.microsoft.com/287c5b92-fcb5-4295-9c2b-4e37e643beb2)
-   [Revogação e autores desconectados](https://technet.microsoft.com/a9cf0541-9101-4e90-9c56-7c1b9a8deca6)
