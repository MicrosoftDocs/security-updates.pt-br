---
TOCTitle: Backups de sistema para RMS
Title: Backups de sistema para RMS
ms:assetid: 'c29894da-ee00-428c-8d48-80d8e5a83678'
ms:contentKeyID: 18123832
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747746(v=WS.10)'
---

Backups de sistema para RMS
===========================

Antes de configurar a infra-estrutura e instalar o RMS, faça o backup dos seguintes componentes, conforme apropriado:

-   Se estiver usando um banco de dados existente do SQL Server para hospedar os bancos de dados de configuração e log, faça o backup de todos os bancos de dados e configuração do servidor. Se estiver atualizando uma versão anterior do RMS ou reinstalando o RMS, não deixe de fazer o backup dos bancos de dados de configuração e log anteriores.
-   Faça o backup do estado do sistema do servidor em que planeja instalar o RMS. Esse backup armazena as chaves do Registro e os valores que contêm as informações necessárias para restaurar o servidor, se necessário.
-   Use o snap-in de certificados para exportar os seus certificados para um arquivo. O snap-in de certificados também é usado para o backup dos dados da chave particular do RMS para um arquivo PKCS \#12, que é criptografado com uma senha. Se estiver atualizando ou reinstalando o RMS e tiver usado a criptografia padrão baseada em software para proteger a chave particular do RMS, a chave particular estará criptografada e armazenada com o backup do banco de dados de configuração.
-   Se usar um módulo de segurança de hardware para proteger a chave particular, você deve fazer backup da configuração dessa chave usando os métodos recomendados pelo fabricante.

Os arquivos de backup devem ser mantidos em um local de armazenamento seguro, juntamente com a senha usada para criptografar as chaves particulares.
