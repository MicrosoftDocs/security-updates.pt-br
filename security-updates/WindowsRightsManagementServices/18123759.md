---
TOCTitle: Exclusão no RMS
Title: Exclusão no RMS
ms:assetid: 'c17e393e-b6a9-4ae5-aee5-18baa6b32d4d'
ms:contentKeyID: 18123759
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747656(v=WS.10)'
---

Exclusão no RMS
===============

A exclusão impede que determinadas entidades adquiram novas licenças de um determinado servidor ou cluster do RMS. No entanto, ao contrário da revogação, a exclusão não invalida as entidades. Todas as licenças existentes que estiverem associadas a entidades excluídas ainda são válidas. Somente novas solicitações de licença serão negadas.

Cada servidor ou cluster do RMS mantém suas próprias diretivas de exclusão, e essas diretivas não são propagadas por todo o sistema. No site **Administração do RMS**, os administradores definem diretivas de exclusão para cada servidor ou cluster do RMS.

Os administradores podem excluir entidades com base na versão do cofre, versão do Windows, certificado de conta de direitos ou aplicativo habilitado para RMS.
