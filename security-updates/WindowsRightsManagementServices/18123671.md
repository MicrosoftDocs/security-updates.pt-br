---
TOCTitle: Retirando servidores
Title: Retirando servidores
ms:assetid: '52005e2e-9563-4ba0-906c-3cc76f9c378f'
ms:contentKeyID: 18123671
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747568(v=WS.10)'
---

Retirando servidores
====================

Pode haver circunstâncias em que é necessário retirar um servidor RMS, por exemplo, nas seguintes situações:

-   Problemas ou atualizações de equipamentos que resultem na substituição de servidores específicos.
-   Uma redução no tráfego de licenciamento e publicação que resulta no encerramento de alguns servidores.
-   Exigências legais para remoção de servidores de locais específicos que resultam no encerramento de um cluster inteiro.
-   Fusões ou vendas de divisões ou outras partes de uma organização que resultem na transferência de ativos.
-   Fusão de uma organização inteira com outra organização que também está executando o RMS, tornando as duas instalações do RMS redundantes.

Antes de retirar um servidor, faça backup de todos os bancos de dados do RMS usados pelo servidor, principalmente do banco de dados de configuração. Para obter mais informações sobre como fazer backups de bancos de dados, consulte "Fazendo backup e restaurando o sistema para o RMS", na seção "Planejando uma implantação do RMS" desta coleção de documentos. .

Depois de fazer backup dos bancos de dados, você pode remover o servidor. Os requisitos para remover um servidor RMS dependem da função do servidor e da topologia da instalação do RMS:

-   **Removendo um servidor de um cluster**. Se o servidor RMS a ser retirado estiver em um cluster no qual outros servidores RMS ainda são ativos e necessários, a remoção de um servidor RMS individual do cluster exigirá que você desconfigure e desinstale o RMS no servidor a ser retirado, remova o hardware do cluster e arquive os bancos de dados.

> [!NOTE]  
> Somente servidores no cluster raiz de certificação precisam ser desconfigurados antes da desinstalação do RMS. Este processo não é necessário para servidores de licenciamento.

-   **Retirando um servidor autônomo**. Se o servidor RMS que você deseja retirar estiver em um servidor RMS autônomo (isto é, que não faça parte de um cluster de vários servidores) que será substituído por um novo servidor, execute as seguintes etapas: Desconfigure e desinstale o servidor RMS existente, remova-o da rede e, em seguida, instale e configure imediatamente o RMS no servidor substituto. Configure o novo servidor RMS para usar a mesma URL e banco de dados de configuração que o servidor RMS retirado. Lembre-se de que, antes de o servidor substituto ser instalado e configurado, os usuários não poderão consumir conteúdo publicado pelo servidor retirado.

>[!IMPORTANT]  
> Se o servidor RMS que está sendo substituído usar um módulo de segurança de hardware, você deve transferir o ambiente de segurança para o novo servidor antes de instalar e configurar o RMS nele. Para obter instruções, consulte a documentação do módulo de segurança de hardware.

-   **Substituindo uma instalação do RMS por outra instalação existente**. Em algumas circunstâncias, talvez seja necessário retirar uma instalação do RMS e substituí-la por outra instalação existente, por exemplo, no caso de uma fusão de empresas em que as duas empresas estão executando o RMS.

Quando a configuração do servidor é removida e ele é desinstalado, o servidor é removido da tabela ClusterServer do banco de dados de configuração e o banco de dados de serviços de diretório é excluído do SQL Server. Para obter instruções sobre a desconfiguração e a desinstalação do RMS, consulte "[Desconfigurar o RMS](https://technet.microsoft.com/9fa63daa-5fb9-4afd-8371-b38248619857)" e "[Desinstalar o RMS](https://technet.microsoft.com/885e3b4f-ea32-466f-9f7f-d8440b0f7c28)", mais adiante neste tema.
