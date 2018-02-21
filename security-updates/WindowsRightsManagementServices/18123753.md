---
TOCTitle: Excluindo contas de usuários
Title: Excluindo contas de usuários
ms:assetid: 'bf73b141-d4d1-4807-a773-3aaff58b0db6'
ms:contentKeyID: 18123753
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747653(v=WS.10)'
---

Excluindo contas de usuários
============================

Quando você exclui uma conta de usuário do Active Directory, a entrada do certificado de conta de direitos do usuário que está na tabela de chaves do usuário no banco de dados de configuração do cluster raiz de certificação não é excluída automaticamente. Por isso, a tabela de chaves do usuário pode crescer sem limites, à medida que novas chaves de usuários são adicionadas e as antigas não são excluídas.

Para manter o banco de dados de configuração, você pode executar um procedimento armazenado que exclui uma chave de usuário pelo seu identificador de segurança toda vez que a conta do usuário associado for removida do Active Directory. Como alternativa, você pode executar periodicamente um script que exclua todas as chaves de usuários do banco de dados de configuração quando suas identificações de segurança associadas não mais existirem no Active Directory. Observe que fazer isso cria uma grande carga no SQL Server e no Active Directory.
