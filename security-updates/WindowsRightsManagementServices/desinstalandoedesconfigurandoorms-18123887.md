---
TOCTitle: Desinstalando e desconfigurando o RMS
Title: Desinstalando e desconfigurando o RMS
ms:assetid: 'cae1ed5b-f716-41f0-8e14-7cbfef405331'
ms:contentKeyID: 18123887
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747753(v=WS.10)'
---

Desinstalando e desconfigurando o RMS
=====================================

Por vários motivos, poderá ser necessário remover o RMS de um servidor. Para um servidor raiz de certificação, a primeira etapa é desconfigurar o RMS no servidor. Isso pode ser feito na **página Administração Global** do servidor que você deseja desconfigurar, clicando em **Remover o RMS deste site**. Você não precisa desconfigurar um servidor de licenciamento antes de desinstalar o RMS.

> [!Note]  
> Quando você desconfigura o último servidor raiz de certificação em uma floresta do Active Directory, o objeto do ponto de conexão do serviço é removido do Active Directory. Se você não desconfigurar esse servidor antes de desinstalar o RMS, só poderá configurar um novo servidor raiz de certificação naquela floresta depois de remover o objeto do ponto de conexão de serviço manualmente do Active Directory.

Em seguida, desinstale o RMS.

Quando você desconfigura e desinstala o RMS de um servidor autônomo ou do último servidor que está em um cluster, o banco de dados de serviços de diretório é removido. Os bancos de dados de configuração e de registro não são removidos. No entanto, se você atualizar ou reinstalar o RMS no servidor, o banco de dados de registro será substituído por um novo banco de dados de registro.

Quando você desconfigura e desinstala o RMS de um servidor existente em um cluster, os bancos de dados de configuração, de registro e dos serviços de diretório do cluster não são removidos. No entanto, a tabela DRMS\_ClusterServer do banco de dados de configuração é atualizada e passa a mostrar que o servidor foi removido do cluster.

Para obter mais informações sobre a retirada de servidores e os problemas envolvidos nessa operação, consulte "[Retirando servidores](https://technet.microsoft.com/52005e2e-9563-4ba0-906c-3cc76f9c378f)", já mencionado neste tema.
