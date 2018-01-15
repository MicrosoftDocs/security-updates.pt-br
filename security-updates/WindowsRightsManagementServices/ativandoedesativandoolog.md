---
TOCTitle: Ativando e desativando o log
Title: Ativando e desativando o log
ms:assetid: '50ccd827-2d39-41e7-a395-3d5f5836869b'
ms:contentKeyID: 18123668
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747565(v=WS.10)'
---

Ativando e desativando o log
============================

O registro do cluster ou servidor atual é ativado ou ativado na página **Configurações de registro**. A desativação do registro pára o envio de dados registrados pelos serviços do RMS na Web para a fila de mensagens de registro. Ela também pára o serviço ouvinte de registro. Não há suporte para a desativação do registro usando-se a ferramenta de administração dos Serviços do Windows Server 2003.

Os registros do RMS são enviados ao servidor do banco de dados pelo Enfileiramento de Mensagens. Se não houver uma conexão com o servidor do banco de dados, o Enfileiramento de Mensagens armazenará os registros em um cache local até que a conectividade seja restaurada. Na primeira habilitação do registro, você deve certificar-se de que o servidor RMS possui uma conexão com o servidor do banco de dados e de que o servidor do banco de dados foi iniciado. Se você estiver usando o SQL Server como servidor do banco de dados, poderá verificar se os registros estão sendo gravados no banco de dados, usando as seguintes etapas:

-   No SQL Server Enterprise Manager, vá ao banco de dados de registro, expanda **Bancos de Dados** e, em seguida, expanda o banco de dados que contém o banco de dados de registro do RMS.
-   Clique no banco de dados de log, clique em **Tabelas**, clique com o botão direito em **DRMS\_log\_master** e, em seguida, clique em **Abrir tabela - retornar todas as linhas**. Se os arquivos de log estiverem sendo criados, você verá um ou mais arquivos de log.
