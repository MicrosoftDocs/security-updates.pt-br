---
TOCTitle: Gerenciando o tamanho do log
Title: Gerenciando o tamanho do log
ms:assetid: '431b32b3-02f0-4666-b52c-183eb65154fd'
ms:contentKeyID: 18123641
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720271(v=WS.10)'
---

Gerenciando o tamanho do log
============================

O serviço de log envia grandes quantidades de dados para o banco de dados do SQL Server. Você deve verificar o banco de dados de registro regularmente para verificar se existe espaço em disco suficiente para os dados. Se a quantidade de dados for excessiva e suas necessidades de relatório não exigirem algumas das informações, uma opção seria configurar filtros do SQL Server para reduzir os arquivos de log para armazenar somente os logs necessários. Para obter instruções sobre como filtrar informações do registro, consulte a Ajuda do SQL Server Enterprise Manager.

Se o banco de dados de log estiver ficando muito grande para o espaço em disco disponível, será possível movê-lo para outro servidor, conforme descrito na seção [Realocando o banco de dados de log](https://technet.microsoft.com/34ea8045-dc94-422e-9601-29927cfc1534), mais adiante neste tema.

> [!Important]  
> Você também deve usar o Monitor do Sistema para monitorar regularmente o tamanho de saída da fila de mensagens de registro. Se o tamanho da fila aumentar substancialmente, verifique se o serviço ouvinte de registro está funcionando corretamente. Para obter mais informações sobre o uso do Monitor do Sistema, consulte o Centro de ajuda e suporte do Windows Server 2003. 
