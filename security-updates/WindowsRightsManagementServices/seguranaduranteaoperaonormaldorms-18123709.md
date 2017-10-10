---
TOCTitle: Segurança durante a operação normal do RMS
Title: Segurança durante a operação normal do RMS
ms:assetid: '98f3d584-6320-4aa1-9959-7133cfdb6df7'
ms:contentKeyID: 18123709
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747609(v=WS.10)'
---

Segurança durante a operação normal do RMS
==========================================

Depois de instalar e configurar o RMS, os serviços do RMS na Web operam como aplicativos do Serviços de Informações da Internet (IIS), acessando vários recursos de sistema que requerem autenticação e autorização. Todos os recursos do sistema requerem autenticação e não podem ser configurados de outra forma. O restante desta página descreve o design da autorização no RMS.

Os serviços do RMS na Web são executados no contexto de um pool de aplicativos do IIS. Cada pool de aplicativos no IIS possui uma identidade exclusiva que pode corresponder a uma conta de usuário do domínio, a uma conta de usuário local, a uma conta local do serviço de rede ou a uma conta local do sistema local. Cada uma dessas contas possui níveis diferentes de autorização dentro do sistema. Quando o RMS é configurado, você pode optar por executar os serviços do RMS na Web como a conta do Sistema local ou como uma conta de usuário do domínio. Essa conta passará a ser a identificação do pool de aplicativos para o pool de aplicativos do RMS. O pool de aplicativos do site de Administração Global é o "Pool de Aplicativos DRMS." O pool de aplicativos do site que você configura é chamado de "\_DRMSAppPool1." O serviço de log do RMS é executado como um serviço independente do Windows sob a mesma conta, conforme especificado para a identificação do pool de aplicativos do RMS.

Os recursos que os serviços do RMS na Web precisam acessar incluem vários arquivos e pastas do sistema, bancos de dados e procedimentos armazenados no servidor de banco de dados, Registro local, Active Directory, cache de conjunto de módulos (assembly), memória e outros processos em execução no sistema. O serviço de log do RMS também precisa acessar a fila de log no sistema local. Cada um desses recursos possui suas próprias listas de controle de acesso condicional que definem quem está autorizado a acessar o recurso e o que pode ser feito com o recurso. 

Para simplificar a atribuição de permissões e o gerenciamento de contas de serviço, todas as permissões necessárias são atribuídas ao grupo de serviço do RMS local que o RMS criou durante a configuração. Como a conta de serviço RMS é um membro desse grupo, ela recebe todas as permissões atribuídas ao grupo.

A lista a seguir resume as permissões que são concedidas ao grupo de serviço do RMS:

-   Permissão de leitura para os diretórios raiz virtuais
-   Permissão de gravação para o diretório de montagem de cache
-   Permissão de gravação para o diretório temporário do sistema
-   Permissão de gravação para a fila de log
-   Permissão de leitura para o Active Directory

Se você estiver usando o Microsoft SQL Server 2000 como servidor de banco de dados, deve estar ciente de que ele usa um método de atribuição de permissões um pouco diferente daquele utilizado pelo Windows Server 2003. Ao configurar o RMS, é criado um logon para a conta de serviço RMS no SQL Server. Caso você opte por configurar o RMS usando a conta do Sistema local, será criado um login para o SQL Server usando o formato *DOMÍNIO\\nome\_computador*, onde *DOMÍNIO* é o nome do domínio do Active Directory do qual o computador é membro, e *nome\_computador* é o nome do servidor. Uma função SQL chamada rms\_service é criada, e a ela são atribuídas todas as permissões necessárias. O logon para a conta de serviço RMS é adicionado a esse grupo. Não são concedidas permissões de forma explícita à conta de serviço RMS.

Além disso, o SQL Server atribui um proprietário a cada banco de dados. A propriedade dos bancos de dados é atribuída da seguinte forma durante a configuração:

-   A propriedade do banco de dados de configuração é dada à conta do domínio usada para configurar o RMS.
-   A propriedade dos bancos de dados dos serviços de diretório e de log é dada à conta de serviço RMS.

As permissões para todos os recursos criados pelo RMS foram selecionadas com muito cuidado durante o design do RMS, sempre tendo a segurança em mente. Não deve haver nenhuma razão para modificar as permissões atribuídas durante a configuração de qualquer dos recursos. Se você precisar alterar a conta ou senha do usuário da conta de serviço após a configuração, poderá fazê-lo no site Administração Global do RMS. Para obter mais informações, consulte "Alterar a conta de serviço RMS" em "Operando um servidor RMS", nesta coleção de documentos.
