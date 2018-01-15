---
TOCTitle: Fazendo backup e restaurando modelos de diretiva de direitos
Title: Fazendo backup e restaurando modelos de diretiva de direitos
ms:assetid: 'a6ed3328-4128-45e8-9236-3de484b460de'
ms:contentKeyID: 18123731
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747625(v=WS.10)'
---

Fazendo backup e restaurando modelos de diretiva de direitos
============================================================

Para proteger modelos de diretiva de direitos valiosos, faça backup dos dados do modelo no banco de dados de configuração em mídia regularmente e coloque essa mídia em local protegido. Se ocorrer uma falha no sistema, você poderá restaurar os modelos de diretiva de direitos a partir da cópia de backup.

Proceda de uma das seguintes maneiras:

-   Faça backup de todo o banco de dados de configuração que inclui os dados do modelo de diretiva de direitos. Para obter mais informações sobre como fazer backup de um banco de dados SQL Server, consulte a documentação do SQL Server.
    -ou-
-   Faça backup somente dos dados do modelo de diretiva de direitos que estão no banco de dados de configuração. Para isso, você pode exportar as informações sobre GUID e TemplateData da tabela DRMS\_RightsTemplate para um novo arquivo de texto. Para obter mais informações sobre como exportar dados de um banco de dados SQL Server, consulte a documentação do SQL Server.

Se precisar restaurar os dados do modelo de diretiva de direitos do banco de dados de configuração, extraia as informações sobre GUID e TemplateData da tabela DRMS\_RightsTemplate na cópia de backup do banco de dados de configuração ou simplesmente importe os dados do arquivo de texto. Para obter mais informações sobre como executar essas tarefas, consulte a documentação do SQL Server.

| ![](images/Cc747625.note(WS.10).gif)Observação                                      |
|------------------------------------------------------------------------------------------------------------------|
| Para estabelecer um plano de backup dos modelos de diretiva de direitos, consulte o administrador do SQL Server. |
