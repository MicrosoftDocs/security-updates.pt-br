---
TOCTitle: Cache do Active Directory do RMS
Title: Cache do Active Directory do RMS
ms:assetid: 'c721a2eb-2fe9-4346-b426-3cc169b97265'
ms:contentKeyID: 18123888
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747662(v=WS.10)'
---

Cache do Active Directory do RMS
================================

Cada servidor ou cluster raiz de certificação e servidor de licenciamento do RMS possui um cache local do Active Directory que contém os resultados das consultas de participação de grupo do catálogo global do Active Directory. Além do cache que se encontra em cada servidor, há um cache compartilhado para cada cluster, o qual é armazenado no banco de dados dos serviços de diretório. O objetivo desses caches é reduzir o número de consultas que são submetidas ao catálogo global e reduzir o tempo de resposta das solicitações de licença.

Quando um usuário solicita uma licença de uso, o servidor que responde deve avaliar se esse usuário recebeu ou não os direitos necessários na licença de publicação. No caso mais simples, o usuário que solicita uma licença é nomeado explicitamente na licença de publicação. Em muitos cenários, no entanto, o autor concede direitos a um grupo, e não a usuários individuais.

Se a licença de publicação não nomear explicitamente o usuário solicitante, mas em vez disso conceder direitos a um grupo, o servidor deve avaliar as participações do grupo do usuário para determinar se o usuário é membro de um grupo que recebeu direitos. Para fazer isso, o servidor envia uma consulta LDAP para o catálogo global.

Os servidores do RMS armazenam em cache todos os resultados de consultas de participação de grupo, tanto no cache local do Active Directory quanto no banco de dados de serviços de diretório do cluster. Os servidores podem, em seguida, obter informações sobre participação de grupo desses caches, o que reduz o número de consultas que devem enviar ao catálogo global. Por padrão, a consulta é feita ao servidor mais próximo; entretanto, você pode configurar a chave do Registro GC para especificar os servidores do catálogo global a serem consultados. Para obter mais informações sobre essa configuração, consulte "Modificando as configurações do Registro do pool de conexão" em "Operando um servidor RMS", nesta coleção de documentos.

Para avaliar as participações do grupo de um usuário, o servidor primeiro verifica seu cache para ver se há informações sobre a participação do grupo do usuário que já estejam armazenadas ali. Caso contrário, o servidor verifica o banco de dados dos serviços de diretório do cluster. Se as informações de participação do grupo não estiverem armazenadas no banco de dados, o servidor consultará o catálogo global.

Para usuários e grupos, os seguintes atributos do Active Directory são armazenados em cache.

-   email
-   ProxyAddresses (somente endereços de email SMTP)
-   objectSID
-   sidHistory
-   memberOf (GUIDs de grupos dos quais o usuário ou grupo é membro)

As entradas no cache local do Active Directory têm a hora gravada. As configurações do Registro especificam o período de validade das entradas no cache, bem como o número total de entradas que podem ser armazenadas nele. Essas configurações podem interferir no desempenho dos servidores. Para obter mais informações, consulte "Modificando as configurações de cache do Active Directory" em "Operando um servidor RMS", nesta coleção de documentos.
