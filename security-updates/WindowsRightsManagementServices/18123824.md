---
TOCTitle: Gerenciando diretivas de exclusão
Title: Gerenciando diretivas de exclusão
ms:assetid: 'ee31e099-e095-4648-95da-0009fbeb48cb'
ms:contentKeyID: 18123824
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747730(v=WS.10)'
---

Gerenciando diretivas de exclusão
=================================

É possível implementar diretivas de exclusão do lado do servidor para negar solicitações de certificado e de licença baseadas no certificado de conta de direitos ou na versão do cofre. Diretivas de exclusão recusam novas solicitações de certificado e de licença feitas por entidades comprometidas mas, ao contrário da revogação, as diretivas de exclusão não invalidam as entidades. Os administradores também podem excluir aplicativos potencialmente perigosos ou comprometidos, para que eles não possam descriptografar o conteúdo protegido pelo RMS. Além disso, os administradores podem excluir determinadas versões do sistema operacional Windows, evitando assim que conteúdo protegido pelo RMS seja consumido em computadores clientes que estão executando essas versões.

Quando uma entidade é excluída, as licenças de uso criadas pelo servidor RMS terão essa entidade especificada na lista de exclusão. Se, depois de um período, você decidir excluir uma entidade que foi incluída anteriormente na diretiva de exclusão, poderá excluir a entidade na página Diretivas de exclusão do site de administração. Isso removerá a entidade da lista de exclusão. As novas solicitações de certificação ou de licenciamento não considerarão essa entidade como excluída.

A menos que tenha excluído uma entidade inadvertidamente, é recomendável que você não remova uma entidade de uma diretiva de exclusão até que possa ter certeza de que todos os certificados emitidos antes da criação da diretiva de exclusão tenham expirado. Caso contrário, os certificados antigos e novos permitirão que o conteúdo seja descriptografado, o que pode não ser o que sua organização deseja.

Este tópico fornece informações sobre como gerenciar diretiva de exclusão. Para obter instruções detalhadas sobre como excluir entidades, consulte a seção "[Habilitar diretivas de exclusão](https://technet.microsoft.com/bbb1ce50-bc11-41cf-b75b-a6756141908f)", mais adiante neste tema.

Esta seção inclui:

-   [Excluindo versões do cofre](https://technet.microsoft.com/e287f026-aab2-43ab-93bc-48087da82f36)
-   [Excluindo certificados de conta de direitos](https://technet.microsoft.com/cba5e901-942c-4d06-9865-e6c4648c95e6)
-   [Excluindo versões do Windows](https://technet.microsoft.com/8b8a184d-ac0e-4a43-822c-d2fae2faf484)
-   [Excluindo aplicativos](https://technet.microsoft.com/b68ae4b2-b9ba-44ae-90cb-c88df600ec86)
