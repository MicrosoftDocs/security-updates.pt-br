---
TOCTitle: Serviço ouvinte de log do RMS
Title: Serviço ouvinte de log do RMS
ms:assetid: 'e81ea57d-1a7d-4c02-abfc-dbc1597e176b'
ms:contentKeyID: 18123809
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747709(v=WS.10)'
---

Serviço ouvinte de log do RMS
=============================

O serviço Ouvinte de log é instalado no momento da instalação do RMS. Ele é executado nos servidores raiz de certificação e de licença. Cada serviço do RMS na Web registra em log todas as solicitações e respostas que ele recebe e envia e depois transmite os dados à fila de mensagens de log usando o Enfileiramento de Mensagens. Em seguida, o serviço ouvinte do registro transfere esses dados da fila de mensagens para o banco de dados de log do cluster.

É possível ativar ou desativar o log no site de administração. Fazer isso pára a execução de log dos serviços da Web e desativa o serviço ouvinte do registro.
