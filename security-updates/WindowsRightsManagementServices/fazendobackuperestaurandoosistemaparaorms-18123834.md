---
TOCTitle: Fazendo backup e restaurando o sistema para o RMS
Title: Fazendo backup e restaurando o sistema para o RMS
ms:assetid: 'c11f3ac1-e512-402b-bf13-9ff21f5fe745'
ms:contentKeyID: 18123834
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747745(v=WS.10)'
---

Fazendo backup e restaurando o sistema para o RMS
=================================================

No planejamento da recuperação do sistema, os seus planos devem levar em conta falhas do servidor de banco de dados e falhas de um servidor RMS. No caso de falha do servidor de banco de dados, é possível restaurar a funcionalidade do servidor ou cluster RMS a partir de uma cópia de backup do banco de dados de configuração. Para isso, não é necessário obter um novo certificado de licenciante para servidor ou uma chave particular para o servidor RMS, porque esses itens estão armazenados no banco de dados de configuração.

Planejando o backup do sistema RMS
----------------------------------

Além da chave do servidor, os dados dos usuários, inclusive informações sobre a chave pública, estão armazenados no banco de dados de configuração. Para proteger dados valiosos de chaves, faça backup do banco de dados de configuração em mídia e coloque a mídia em local protegido. O banco de dados de configuração do cluster raiz de certificação é alterado com freqüência; portanto, é recomendável executar backups freqüentes. Quanto maior a freqüência de adição de novos usuários à sua organização, maior deve ser a freqüência da execução de backups. Se estiver fazendo o backup do servidor raiz de certificação, não deixe de incluir a tabela **sysmessages** do banco de dados mestre do backup. Se essa tabela não incluir mensagens específicas do RMS, o servidor raiz de certificação não poderá funcionar e retornará um erro. Se essa tabela não estiver no backup, ela poderá ser recriada pela repetição do processo de configuração com um banco de dados existente.

O banco de dados do log do RMS contém logs que podem fornecer soluções de problemas e dados estatísticos interessantes, mas em geral isso não é crítico para um sistema RMS. O banco de dados dos serviços de diretório é um cache local do banco de dados do Active Directory, sendo, portanto, recriado automaticamente quando se restaura um sistema RMS. Para estabelecer um plano de backup para os bancos de dados do RMS, consulte o administrador do SQL Server.

Se estiver usando um módulo de segurança de hardware para proteger as chaves particulares do RMS, você deve também fazer backup da configuração do módulo de segurança de hardware. Para obter mais informações sobre como fazer backup e restaurar a configuração do módulo de segurança do hardware, consulte a documentação do módulo de segurança do hardware.

> [!Note]  
> Se você usou um provedor de serviços de criptografia baseado em software diferente do provedor padrão baseado em software para criptografar chaves particulares do RMS, certifique-se de que possui práticas organizacionais de gerenciamento de chaves (como procedimentos de backup e de restauração) implementados para esse provedor, antes de usá-lo com o RMS. 

Planejando restaurar um sistema RMS
-----------------------------------

Se estiver restaurando um servidor de banco de dados a partir do backup, certifique-se de que a versão do RMS em execução seja a mesma versão que estava sendo executada quando o backup foi criado. Informe os usuários do sistema RMS que, ao começarem a usar o sistema RMS depois da data do backup, eles serão solicitados a obter um novo certificado de conta de direitos. Como resultado, nenhum conteúdo protegido se perde.

Para restaurar um único servidor RMS de um cluster, recrie o servidor, reinstale o RMS e, em seguida, associe o servidor ao cluster usando o banco de dados existente. Essa atividade não afetará os usuários do sistema RMS porque os servidores em cluster operam em conjunto.
