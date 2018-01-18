---
TOCTitle: Mantendo o banco de dados de serviços de diretório
Title: Mantendo o banco de dados de serviços de diretório
ms:assetid: '911a62f2-c1d6-4091-99b0-b53211be27a7'
ms:contentKeyID: 18123764
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747680(v=WS.10)'
---

Mantendo o banco de dados de serviços de diretório
==================================================

O RMS inclui um banco de dados de serviços de diretório hospedado pelo servidor de banco de dados, o qual contém informações sobre usuários, identificadores (como endereços de email), identificações de segurança (SIDs), participações de grupos e identificadores alternativos. Essas informações são obtidas nas consultas LDAP feitas ao catálogo global do Active Directory pelo serviço de licenciamento do RMS e depois são armazenadas localmente em cache nesse banco de dados para melhorar a resposta do servidor quando os usuários solicitarem licenças de uso.

Como os dados armazenados nesse banco de dados são inseridos e excluídos com freqüência, ele está sujeito à fragmentação. Você deve periodicamente (diária ou semanalmente) reorganizar os índice de todas as tabelas do banco de dados DRMS\_DirectoryServices. Isso reconstruirá os índices e, assim, os dados não ficarão fragmentados. Dados fragmentados podem resultar em desempenho insatisfatório e até mesmo em falha do servidor, se não houver intervenção administrativa.

Se você estiver usando o SQL Server como servidor de banco de dados, as reorganizações do banco de dados poderão ser feitas com o Assistente para manutenção ou com o seu script personalizado no SQL Server Agent.

Se constatar que o log de transações cresce de forma inaceitável com a reindexação do banco de dados, você poderá minimizar esse crescimento alternando do modo Recuperação completa para o modo Registro em log em massa antes de reindexar.
