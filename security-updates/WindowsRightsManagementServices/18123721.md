---
TOCTitle: Banco de dados de configuração do RMS
Title: Banco de dados de configuração do RMS
ms:assetid: '769adbdc-f32f-464b-85c4-e8b160036187'
ms:contentKeyID: 18123721
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747634(v=WS.10)'
---

Banco de dados de configuração do RMS
=====================================

O RMS usa um servidor de banco de dados, como Microsoft® SQL Server ou Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Versão A para armazenar sua configuração e informações de diretivas. Há um banco de dados de configuração para cada servidor ou cluster do RMS; esse banco de dados armazena, compartilha e recupera dados da configuração, entre outros.

O banco de dados de configuração para o servidor ou cluster raiz de certificação contém uma lista de identidades de usuários do Windows e respectivos certificados de conta de direitos. O par de chaves do certificado é criptografado para a chave pública do servidor RMS antes de ser armazenado no banco de dados. Os bancos de dados de configuração de servidores de licença não contêm essas informações.

O grupo de serviço do RMS tem permissões de execução nos procedimentos armazenados do banco de dados.

**Importante** É recomendável que o MSDE 2000 seja usado para oferecer suporte aos bancos de dados RMS somente em ambientes de teste, porque o MSDE 2000 não oferece suporte a nenhuma interface de rede. Além disso, os termos de uso do MSDE 2000 especificam que você não pode usar as ferramentas de cliente do SQL Server para manipular um banco de dados MSDE 2000. Com essa restrição não será possível exibir informações de registro ou alterar dados armazenados no banco de dados de configuração.
