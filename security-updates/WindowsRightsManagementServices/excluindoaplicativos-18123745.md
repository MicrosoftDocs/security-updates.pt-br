---
TOCTitle: Excluindo aplicativos
Title: Excluindo aplicativos
ms:assetid: 'b68ae4b2-b9ba-44ae-90cb-c88df600ec86'
ms:contentKeyID: 18123745
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747644(v=WS.10)'
---

Excluindo aplicativos
=====================

Você pode especificar a versão de um aplicativo habilitado para RMS com o qual todas as solicitações de licença são verificadas. A exclusão de aplicativo marca cada licença de uso com uma condição em que a licença pode vincular-se somente a conteúdo protegido pelo RMS para o qual ela foi emitida, se o aplicativo que está solicitando a licença não estiver na lista de exclusão.

Isso pode ser útil, por exemplo, quando uma empresa implanta uma atualização de segurança para um aplicativo. Os administradores do sistema podem usar o mecanismo normal para fazer com que computadores clientes instalem a atualização de segurança. Em seguida, eles podem configurar diretivas de exclusão de aplicativo que estão definidas usando as informações da versão do aplicativo que está usando o site de administração. Essa diretiva de exclusão restringe a emissão de licenças pelo RMS para clientes que estão executando versões anteriores do software.

Aplicativos habilitados para RMS são excluídos pelo nome de seu arquivo e número de versão. Você pode desejar fazer isso para ter certeza de que os usuários instalem uma versão mais nova e mais segura de um aplicativo quando ela é disponibilizada. Por exemplo, você pode ter a versão 1.0.4.2315 de um aplicativo habilitado para RMS implantado em sua organização. Em seguida, o desenvolvedor do aplicativo descobre um problema de segurança e emite a versão 1.0.4.4200 que elimina o problema. Além de implementar a nova versão do aplicativo, você pode estabelecer uma diretiva de exclusão que impeça que os usuários consumam conteúdo protegido usando a versão anterior do aplicativo.

Como nos outros tipos de exclusão, você deve configurar a exclusão de aplicativo em cada cluster para o qual deseja que ela tenha efeito.

Quando você aplica esta diretiva de exclusão em seu servidor, os clientes não podem usar o aplicativo excluído para solicitar e vincular novas licenças de uso ao conteúdo protegido pelo RMS. No entanto, os clientes podem continuar a usar o aplicativo excluído para consumir arquivos licenciados anteriormente.

| ![](images/Cc747644.note(WS.10).gif)Observação                                                                                                                                                > [!Note]  
> O RMS exige que a versão do aplicativo seja especificada em um formato de 4 dígitos delimitados por pontos (\#.\#.\#.\# ). No entanto, alguns aplicativos especificam sua versão com números de 2 ou 3 dígitos delimitados por pontos. Nesse caso, você deve acrescentar um .0, se necessário, para fazer com que o número da versão corresponda ao formato exigido pelo RMS.
