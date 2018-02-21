---
TOCTitle: Realocando o banco de dados de log
Title: Realocando o banco de dados de log
ms:assetid: '34ea8045-dc94-422e-9601-29927cfc1534'
ms:contentKeyID: 18123556
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720238(v=WS.10)'
---

Realocando o banco de dados de log
==================================

A configuração padrão do RMS coloca o banco de dados de configuração e o banco de dados de registro no mesmo servidor. Verifique regularmente se o SQL Server tem espaço suficiente disponível para os dois bancos de dados.

Se o banco de dados de registro ficar muito grande, você pode movê-lo para outro servidor a qualquer momento. Não é possível realocar o banco de dados de registro usando o site de administração. Será necessário fazê-lo manualmente, executando as seguintes etapas:

1.  Desative o log conforme descrito na seção [Ativar ou desativar o log](https://technet.microsoft.com/8e672f95-566f-4070-9a2a-2f70f087148f), mais adiante neste tema.
2.  Copie o banco de dados de registro do servidor de origem para o servidor de destino usando o SQL Server Enterprise Manager. Certifique-se de que as tabelas e os procedimentos armazenados sejam criados no novo banco de dados. Uma maneira de fazer isso é usar o Assistente para Copiar Banco de Dados do SQL Enterprise Manager.
3.  Altere o banco de dados de configuração de modo a refletir os nomes do novo servidor e do banco de dados. Na tabela DRMS\_ClusterPolicies do banco de dados de configuração do cluster para o qual o banco de dados está sendo movido, proceda da seguinte forma:
    -   Altere o valor da diretiva LoggingDatabaseServer de modo a refletir o nome do novo servidor do banco de dados.
    -   Altere o valor da diretiva LoggingDatabaseName para refletir o nome do novo banco de dados.

    > [!Note]  
    > O SQL Server Enterprise Manager não trabalha com campos db\_variant, portanto, não é possível usá-lo para essa tarefa. Para isso, você pode usar o Analisador de Consultas fornecido com o SQL Server ou outra ferramenta de edição de banco de dados. 

4.  Reinicie o IIS em todos os servidores que estão no cluster.
5.  Ative o registro novamente.
