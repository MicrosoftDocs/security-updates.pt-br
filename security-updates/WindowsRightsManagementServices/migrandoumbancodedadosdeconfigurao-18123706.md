---
TOCTitle: Migrando um banco de dados de configuração
Title: Migrando um banco de dados de configuração
ms:assetid: '980e3e94-7d28-40dd-ad01-d34eb3c8d8e6'
ms:contentKeyID: 18123706
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747607(v=WS.10)'
---

Migrando um banco de dados de configuração
==========================================

Há casos em que um banco de dados precisa deixar de ser usado. Uma atualização de hardware de servidor de banco de dados do RMS é um exemplo. Antes que o servidor de banco de dados deixe de ser usado, o banco de dados de configuração deve ser movido para outro servidor de banco de dados. Para proteger os dados do banco de dados de configuração, inclusive os pares de chaves que ele contém, planeje e implemente cuidadosamente a migração.

É recomendável criar um alias CNAME para o servidor de banco de dados do RMS e, em seguida, configurar o RMS para usar esse alias. Assim, não é necessário alterar manualmente o nome do servidor de banco de dados no banco de dados de configuração do RMS caso o nome do servidor seja alterado. Ao usar um alias CNAME, você precisa apenas atualizar o registro do alias.

Antes de começar a migração do banco de dados de configuração, verifique se tem as seguintes informações:

-   O nome e a senha da conta usada originalmente para provisionar os servidores do cluster do RMS que usam esse banco de dados.
-   Se um provedor de serviços de criptografia (CSP) baseado em software for usado para armazenar a chave particular do RMS, a senha dessa chave, especificada originalmente durante o provisionamento. Se um módulo de segurança de hardware (HSM) for usado para armazenar a senha da chave particular do RMS, essa etapa não será necessária.

> [!Note]  
> A migração do banco de dados de configuração não requer um novo certificado de licenciante para servidor nem uma nova chave particular de servidor, pois o RMS mantém as configurações do banco de dados de configuração original. 

Faça backup dos bancos de dados do RMS antes de executar qualquer ação no servidor de banco de dados. Se isso não for possível, no mínimo, exporte seu certificado de licenciante para servidor. Para obter mais informações sobre como exportar o certificado de licenciante para servidor, consulte [Exportar seu certificado de licenciante para servidor para um arquivo](https://technet.microsoft.com/d683a629-71b3-4b11-932b-4ab0317334af). Se ocorrer um erro quando os bancos de dados forem migrados, você poderá importar o certificado de licenciante para servidor para uma nova instalação do RMS e consumir conteúdo protegido por direitos na instalação anterior.

Para migrar um banco de dados de configuração, execute as seguintes etapas:

-   Atualize o banco de dados de configuração do RMS para refletir o nome do novo servidor de banco de dados.
-   Atualize os arquivos web.config e do Registro em cada servidor no cluster do RMS para usar o nome do novo servidor de banco de dados

> [!Important]  
> Este tópico pressupõe que os bancos de dados do RMS já tenham sido copiados para o novo servidor de banco de dados que hospeda os bancos de dados do RMS. 

Atualize o banco de dados de configuração do RMS para usar o nome do novo servidor de banco de dados
----------------------------------------------------------------------------------------------------

O nome do servidor de banco de dados que hospeda os bancos de dados do RMS é armazenado no banco de dados de configuração do RMS. Após migrar os arquivos de banco de dados para o novo servidor de banco de dados, atualize o banco de dados de configuração do RMS. Isso pode ser feito com a ferramenta Editor de Configuração do RMS por meio do Kit de Ferramentas de Administração do RMS ou com o SQL Management Studio.

Para atualizar o nome do servidor de banco de dados do RMS usando o Editor de Configuração do RMS, execute as seguintes etapas:

**Para atualizar o banco de dados de configuração do RMS usando o Editor de Configuração do RMS**
1.  Faça logon em um servidor RMS no cluster como membro da função de banco de dados Administradores do Sistema.

2.  Instale o Kit de Ferramentas de Administração do RMS por meio do Centro de Download da Microsoft ([http://go.microsoft.com/fwlink/?LinkId=98961](http://go.microsoft.com/fwlink/?linkid=98961)).

3.  Navegue para %SystemDrive%:\\ Arquivos de Programas\\SP2 RMS Administration Toolkit\\RMSConfigEditor e clique duas vezes em **RMSCONFIGEDITOR.EXE**.

4.  Na caixa **Servidor**, digite o nome do novo servidor que hospeda o banco de dados de configuração do RMS e clique em **Ir**.

5.  Na caixa **Banco de dados**, clique em **DRMS\_Config\_** *&lt;Nome do cluster do RMS&gt;\_&lt;Porta&gt;*, em que *&lt;Nome do cluster do RMS&gt;* é o nome do cluster do RMS e *&lt;Porta&gt;* é a porta TCP em que o RMS se comunica e, em seguida, clique em **Ir**.

6.  Clique em **DRMS\_ClusterPolicies**.

7.  No painel de resultados, altere o valor na coluna **PolicyData** da linha **LoggingDatabaseServer** para o novo nome do servidor de banco de dados do RMS.

8.  Clique em **Persistir**.

9.  Altere o valor na coluna **PolicyData** da linha **CertificationUserKeyStorageConnectionString** para refletir o novo servidor de banco de dados. O valor deve ser **data source=***&lt;nome do novo servidor de banco de dados&gt;***;integrated** em que *&lt;nome do novo servidor de banco de dados&gt;* é o nome do novo servidor de banco de dados.

10. Clique em **Persistir**.

11. Repita as etapas 9-10 para o valor na coluna **PolicyData** da linha **DirectoryServicesCacheDatabase**.

12. No painel esquerdo, clique em **DRMS\_PluginProperties**.

13. Para **PropertyID** 101, nomeada como **PERSISTENT\_STORAGE**, altere a coluna **PropertyValue** para refletir o novo servidor de banco de dados. O valor deve ser **data source=***&lt;nome do novo servidor de banco de dados&gt;***;integrated** em que *&lt;nome do novo servidor de banco de dados&gt;* é o nome do novo servidor de banco de dados.

14. Clique em **Persistir**.

15. Feche o Editor de Configuração do RMS.

Para atualizar o banco de dados de configuração RMS usando o SQL Server Management Studio, execute as seguintes etapas:

**Para atualizar o banco de dados de configuração do RMS usando o SQL Server Management Studio**
1.  Faça logon no servidor de banco de dados de configuração do RMS como Administrador local ou com outra conta de usuário que seja membro do grupo Administradores local.

2.  Clique em **Iniciar**, aponte para **Todos os Programas** e para **Microsoft SQL Server 2005** e clique em **SQL Server Management Studio**.

3.  Na página **Conectar ao Servidor**, verifique se o nome do novo servidor de banco de dados está listado na caixa **Nome do servidor** e clique em **Conectar**.

4.  Expanda **Bancos de dados**, expanda **DRMS\_Config\_***&lt;Nome do cluster do RMS&gt;***\_***&lt;Porta&gt;* e expanda **Tabelas**.

5.  Clique com o botão direito do mouse em **DRMS\_ClusterPolicies** e clique em **Abrir Tabela**.

6.  No painel de resultados, altere o valor na coluna **PolicyData** da linha **LoggingDatabaseServer** para o novo nome do servidor de banco de dados do RMS.

7.  Altere o valor na coluna **PolicyData** da linha **CertificationUserKeyStorageConnectionString** para refletir o novo servidor de banco de dados. O valor deve ser **data source=***&lt;nome do novo servidor de banco de dados&gt;***;integrated** em que *&lt;nome do novo servidor de banco de dados&gt;* é o nome do novo servidor de banco de dados.

8.  Repita as etapas 6-7 para o valor na coluna **PolicyData** da linha **DirectoryServicesCacheDatabase**.

9.  No painel Object Explorer, clique com o botão direito do mouse em **DRMS\_PluginProperties** e clique em **Abrir Tabela**.

10. Para **PropertyID** 101, nomeada como **PERSISTENT\_STORAGE**, altere a coluna **PropertyValue** para refletir o novo servidor de banco de dados. O valor deve ser **data source=***&lt;nome do novo servidor de banco de dados&gt;***;integrated** em que *&lt;nome do novo servidor de banco de dados&gt;* é o nome do novo servidor de banco de dados.

11. Feche o Microsoft SQL Server Management Studio.

Configure cada servidor no cluster do RMS para usar o nome do novo servidor de banco de dados
---------------------------------------------------------------------------------------------

Para configurar cada servidor no cluster do RMS para usar o nome do novo servidor de banco de dados, você deve atualizar os arquivos web.config e três entradas do Registro. Ao terminar, você deverá reiniciar os Serviços de Informações da Internet (IIS) para que as alterações tenham efeito.

Para atualizar os arquivos web.config em cada servidor no cluster do RMS:

**Para atualizar os arquivos web.config em cada servidor no cluster do RMS**
1.  Faça logon em um servidor no cluster do RMS como membro do grupo local Administradores.

2.  Navegue até %Systemdrive%\\inetpub\\wwwroot\\\_wmcs\\admin.

3.  Clique duas vezes em **web.config**, marque a opção **Selecionar o programa em uma lista** e clique em **OK**.

4.  Clique em **Bloco de Notas**, desmarque **Sempre usar o programa selecionado para abrir este tipo de arquivo** e clique em **OK**.

5.  Clique em **Editar** e em **Substituir**.

6.  Na caixa **Localizar**, digite o nome do servidor de banco de dados a ser removido que está hospedando os bancos de dados do RMS.

7.  Na caixa **Substituir por**, digite o nome do novo servidor de banco de dados que está hospedando os bancos de dados do RMS.

8.  Clique em **Substituir Tudo** e em **Cancelar**.

9.  Clique em **Arquivo** e em **Salvar**.

10. Feche o Bloco de Notas.

11. Repita as etapas 2-9 para os arquivos web.config localizados nos diretórios %Systemdrive%\\inetpub\\wwwroot\\\_wmcs\\certification e %Systemdrive%\\inetpub\\wwwroot\\\_wmcs\\licensing.

12. Repita as etapas 1-11 para cada servidor no cluster do RMS.

Finalmente, atualize o Registro em cada servidor no cluster do RMS para o nome do novo servidor de banco de dados:

> [!Caution]  
> A edição incorreta do Registro pode causar danos graves ao sistema. Antes de alterar o Registro, faça backup de todos os dados importantes do computador. 

**Para atualizar o Registro em cada servidor no cluster do RMS**
1.  Faça logon em um servidor no cluster do RMS como membro do grupo local Administradores.

2.  Clique em **Iniciar** e em **Executar**.

3.  Digite **regedit.exe** e clique em **OK**.

4.  Navegue até **HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0\\KeyProtection**.

5.  Altere a entrada do Registro PASSWORDDERIVEDKEY\_*&lt;nome do servidor de banco de dados antigo&gt;*\_DRMS\_CONFIG\_*&lt;Nome do cluster do RMS&gt;*\_*&lt;porta&gt;* to:

    PASSWORDDERIVEDKEY\_*&lt;nome do antigo servidor de banco de dados&gt;*\_DRMS\_CONFIG\_*&lt;Nome do cluster do RMS&gt;*\_*&lt;porta&gt;*

    em que:

    -   *&lt;nome do antigo servidor de banco de dados&gt;* é o nome do antigo servidor de banco de dados.
    -   *&lt;Nome do cluster do RMS&gt;* é o nome do cluster do RMS.
    -   *&lt;porta&gt;* é a porta TCP em que o RMS se comunica.
    -   *&lt;nome do novo servidor de banco de dados&gt;* é o nome do novo servidor de banco de dados.

6.  Navegue até **HKEY\_LOCAL\_MACHINE\\System\\CurrentControlSet001\\Services\\DRMS\_Logging\_&lt;Nome do cluster do RMS&gt;\_&lt;porta&gt;\\Params**.

7.  Altere a entrada do Registro **ConnectionString** de modo que o valor da origem de dados corresponda ao nome do novo servidor de banco de dados.

8.  Repita as etapas 6-7 para **HKEY\_LOCAL\_MACHINE\\System\\CurrentControlSet\\Services\\DRMS\_Logging\_&lt;Nome do cluster do RMS&gt;\_&lt;porta&gt;\\Params**.

9.  Em um prompt de comando, digite **IISRESET** e pressione ENTER.

10. Repita as etapas 1-9 para cada servidor no cluster do RMS.
