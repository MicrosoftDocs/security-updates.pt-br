---
TOCTitle: 'Planejando a infra-estrutura do servidor de banco de dados'
Title: 'Planejando a infra-estrutura do servidor de banco de dados'
ms:assetid: 'b12354bd-3143-4d1f-b5aa-450c4550653c'
ms:contentKeyID: 18123818
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747731(v=WS.10)'
---

Planejando a infra-estrutura do servidor de banco de dados
==========================================================

Como o RMS usa bancos de dados e procedimentos armazenados para oferecer suporte às suas operações, faz-se necessária uma infra-estrutura de banco de dados para usar o RMS na sua organização. O servidor de banco de dados pode estar no mesmo servidor do RMS ou em um outro servidor. Caso não disponha de um servidor de banco de dados na infra-estrutura para oferecer suporte ao RMS, você poderá usar o Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Versão A como servidor de banco de dados para testar o RMS.

É recomendável que o Microsoft SQL Server Desktop Engine seja usado para oferecer suporte aos bancos de dados RMS somente em ambientes de teste, porque ele não inclui as ferramentas necessárias para ser totalmente funcional e oferecer suporte a um banco de dados de toda a empresa. Além disso, como o MSDE não oferece suporte a redes remotas, você deverá instalá-lo no mesmo servidor do RMS e não poderá adicionar servidores RMS extras ao cluster do RMS. Os termos de uso do Microsoft SQL Server Desktop Engine especificam que você não pode usar as ferramentas de cliente do SQL Server para manipular um banco de dados Microsoft SQL Server Desktop Engine. Com essa restrição, não será possível fazer backup e recuperar o banco de dados de configuração do RMS, exibir informações de log ou modificar os dados armazenados diretamente no banco de dados de configuração.

Se você pretende ter os bancos de dados em um servidor diferente daquele da instalação do RMS, será necessário usar um produto completo de servidor de banco de dados, como o SQL Server, para fornecer suporte a banco de dados. Certifique-se de que foram fornecidas à conta de serviço RMS as permissões apropriadas para ler, gravar e criar bancos de dados que se encontram no servidor de banco de dados que você utiliza para oferecer suporte ao RMS.

Apesar de o RMS ter sido desenvolvido e testado em servidores de banco de dados que executam o SQL Server 2000 e o MSDE, e apesar de a Microsoft não oferecer suporte para a utilização do RMS com um provedor de banco de dados diferente do SQL Server 2000 ou do MSDE, o RMS pode ser executado em outros servidores de banco de dados que usem as interfaces ADO.NET fornecidas pelo Microsoft .NET Framework. Portanto, outros fornecedores de bancos de dados podem ter desenvolvido provedores de banco de dados compatíveis com o RMS. Você pode usar qualquer provedor de banco de dados com o RMS, desde que o respectivo servidor de banco de dados esteja de acordo com os seguintes critérios:

-   O servidor de banco de dados deve ser compatível com Transact-SQL, porque os scripts de inicialização e os procedimentos armazenados do RMS utilizam essa linguagem.
-   O servidor do banco de dados deve oferecer suporte a todas as extensões específicas do Microsoft SQL Server.

O provedor de banco de dados deve ser capaz de:

-   Responder às chamadas de método do namespace System.Data.SqlClient do .NET Framework.
-   Fornecer a respectiva funcionalidade do namespace System.Data.SqlClient.
-   Usar a Autenticação integrada do Windows em vez da autenticação da SQL.

Se você usa o RMS em qualquer outra configuração, entre em contato com o fornecedor de banco de dados ou provedor de soluções apropriado, cujo provedor de banco de dados esteja sendo usado na sua implantação personalizada.

> [!Caution]  
> Por padrão, todos os bancos de dados do RMS são criados com recuperação Completa, mas não há trabalhos de backup de registro de transações. Isto pode fazer com que o disco rígido do seu servidor fique cheio e assim causar uma falha no servidor de banco de dados. Recomenda-se a recuperação completa para o banco de dados DRMS\_configuration; os demais bancos de dados DRMS podem ser configurados para usar um modelo de recuperação diferente, conforme apropriado para a organização. 

Esta seção inclui:

-   [Estimando o crescimento do banco de dados](https://technet.microsoft.com/87652cc2-b886-4797-8d40-356669768089)
-   [Mantendo o banco de dados de serviços de diretório](https://technet.microsoft.com/911a62f2-c1d6-4091-99b0-b53211be27a7)
-   [Mantendo o banco de dados de log](https://technet.microsoft.com/de55058b-0d1a-4997-8a45-e14678ddd13f)
