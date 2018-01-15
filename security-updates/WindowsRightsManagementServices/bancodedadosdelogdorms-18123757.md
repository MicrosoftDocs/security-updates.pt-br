---
TOCTitle: Banco de dados de log do RMS
Title: Banco de dados de log do RMS
ms:assetid: '8ba147f3-16e4-4d9a-ac8f-f05ba2ba11bb'
ms:contentKeyID: 18123757
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747669(v=WS.10)'
---

Banco de dados de log do RMS
============================

Para cada cluster raiz de certificação ou de licenciamento, a instalação do RMS instala um banco de dados de log na mesma instância do servidor do banco de dados que hospeda o banco de dados de configuração. A instalação também cria uma fila particular de mensagens para log no Enfileiramento de Mensagens. O serviço ouvinte do log transmite dados dessa fila de mensagens para o banco de dados de log.

O Grupo de Serviço RMS tem permissões de Execução nos procedimentos armazenados que estão no banco de dados de log.

O serviço ouvinte do log envia grandes quantidades de dados para o banco de dados de log, portanto os administradores podem criar filtros para que o banco de dados de log armazene somente as informações que são necessárias às suas organizações.
