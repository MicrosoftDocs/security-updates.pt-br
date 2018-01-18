---
TOCTitle: Excluindo versões do cofre
Title: Excluindo versões do cofre
ms:assetid: 'e287f026-aab2-43ab-93bc-48087da82f36'
ms:contentKeyID: 18123797
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747700(v=WS.10)'
---

Excluindo versões do cofre
==========================

Para garantir que os clientes usem uma versão mínima do software cliente do RMS, use a versão de cofre que foi associada ao cliente para excluir as versões anteriores do software cliente do RMS. Quando esse recurso é habilitado, você especifica a versão mínima do cofre que foi assinada pelo Serviço de Ativação Microsoft. Em seguida, habilita a exclusão de cofre no site de administração de cada cluster no qual deseja que ela tenha efeito. Todas as solicitações de certificação e licenciamento são verificadas para garantir que o cofre atenda aos critérios de versão mínima.

Se você tiver habilitado exclusão com base na versão do cofre, os clientes que estiverem usando o software de cofre anterior à versão especificada não poderão adquirir certificados de conta de direitos ou licenças de uso porque suas solicitações serão negadas. Esses clientes deverão instalar uma nova versão do software cliente do RMS para adquirir um novo cofre que use a versão atual do software.

O cliente do RMS para Service Pack 1 (SP1) usa uma versão de cofre superior ou igual à 5.0.0.0. Ao definir a exclusão de cofre com essa versão mínima, você força os clientes do RMS em sua organização a fazerem atualização para o cliente do RMS para SP1 a fim de consumirem conteúdo protegido pelo RMS.

Se um usuário que tem um cofre excluído teve licenças emitidas anteriormente para conteúdo, ele ainda poderá consumir esse conteúdo sem adquirir um novo cofre.
