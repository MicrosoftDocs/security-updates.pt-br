---
TOCTitle: Leiame do WSUS com Service Pack 1
Title: Leiame do WSUS com Service Pack 1
ms:assetid: '937ecfe9-e8e0-41ac-85f7-4b65956f3d1e'
ms:contentKeyID: 18139299
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708486(v=WS.10)'
---

Leiame do WSUS com Service Pack 1
=================================

Este documento descreve problemas conhecidos que afetam o Windows Server Update Services com Service Pack 1 (WSUS com SP1). Logo após as informações sobre o WSUS com SP1, você encontrará todas as informações anteriormente incluídas nas notas do Leiame original do WSUS. Essas informações incluem recomendações e requisitos de instalação do WSUS. Para baixar o WSUS com SP1, acesse o [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=67516).

Novidades do WSUS com SP1
-------------------------

O WSUS com SP1 é uma versão de service pack que aprimora a segurança, a confiabilidade, a escalabilidade, a compatibilidade e o desempenho do WSUS. Estes são os novos recursos e aprimoramentos:

-   Suporte ao cliente do Windows Vista: Os computadores que executam o Windows Vista podem ser atualizados pelo WSUS com SP1 Server.
-   Suporte para mais idiomas de cliente: Suporte para todos os idiomas do Office e do Windows Vista.
-   Nova versão do WMSDE: A instância do WMSDE será atualizada para WMSDE SP4 pelo WSUS com SP1 (a versão RTM do WSUS usa o WMSDE SP3).
-   Aprimoramentos de desempenho: O WSUS com SP1 inclui diversos aprimoramentos de desempenho que aceleram os tempos de resposta da interface do usuário.
-   Todos os hotfixes: O WSUS com SP1 inclui todos os hotfixes e alterações que foram disponibilizados desde a versão RTM do WSUS.
-   Suporte para SQL Server 2005.

Antes de começar a atualização do WSUS com SP1
----------------------------------------------

Os problemas a seguir são específicos da atualização do WSUS com SP1. Observe que os problemas e requisitos descritos na seção “Antes de começar” da versão original deste tópico não são abordados nesta seção e ainda são válidos. Por exemplo, os requisitos de instalação descritos na seção “Antes de começar” original ainda são relevantes.

**Observação**   Após a aplicação do SP1 ao WSUS 2.0, não é possível desinstalar o service pack. A desinstalação do SP1 desinstalará todo o produto.

**Importante**   Este documento contém informações sobre como modificar o Registro. Faça backup do Registro antes de modificá-lo. Você deve saber como restaurar o Registro caso ocorra um problema. Para obter mais informações sobre como fazer backup, restaurar e modificar o Registro, consulte o seguinte artigo na Base de Dados de Conhecimento Microsoft:

[Descrição do Registro do Microsoft Windows](http://support.microsoft.com/kb/256986) (http://support.microsoft.com/kb/256986/)

#### Problema 1: Verifique se você tem espaço em disco suficiente para backup do banco de dados

Quando você atualiza da versão RTM do WSUS, a instalação do WSUS com SP1 automaticamente cria um backup do banco de dados do WSUS. É necessário verificar se há espaço em disco suficiente no sistema de arquivos do servidor do WSUS para armazenar o backup do banco de dados do WSUS; caso contrário, a instalação do WSUS com SP1 falhará.

**Para determinar se há espaço em disco suficiente**
1.  Abra o Windows Explorer e navegue até a pasta em que o banco de dados do WSUS está armazenado. Por padrão, o WSUS instala o banco de dados aqui:
    
    ```
        <DriveLetter>:\WSUS\MSSQL$WSUS\Data\
    ```
2.  Pressione e mantenha pressionada a tecla **CTRL**, selecione **SUSDB.MDF** e **SUSDB\_log.LDF** e clique com o botão direito do mouse para selecionar **Propriedades**.

3.  Na caixa de diálogo **Arquivos**, leia o valor de **Tamanho em disco**. O disco deve ter pelo menos essa quantidade de espaço livre para que você possa instalar o WSUS com SP1.

4.  No menu **Iniciar**, clique em **Meu Computador**. Verifique se o disco em que o WSUS está instalado tem a quantidade de espaço livre necessária.

Se, por algum motivo, a instalação do WSUS com SP1 falhar, restaure o banco de dados de backup manualmente. Para obter instruções sobre como restaurar o banco de dados do WSUS, consulte o [Guia de Operações do WSUS](http://technet2.microsoft.com/windowsserver/en/library/05f2e884-ae62-4c90-9681-6c9f2f3c9fd91033.mspx) (a página pode estar em inglês).

#### Problema 2: O WSUS com SP1 atualiza somente a versão RTM do WSUS

Você só pode usar o WSUS com SP1 para atualizar a versão RTM do WSUS. No momento, não é permitido atualizar da versão RC do WSUS. Se a versão RC do WSUS ou quaisquer outras compilações anteriores do WSUS estiverem instaladas, você deverá desinstalá-las e, em seguida, executar o WSUS com SP1.

#### Problema 3: O serviço IIS do seu servidor será interrompido durante a atualização do WSUS com SP1

O instalador da atualização do WSUS com SP1 interrompe os Serviços de Informações da Internet (IIS) no servidor durante o processo de atualização. Isso significa que todos os sites hospedados pela instalação do IIS no servidor não ficarão disponíveis enquanto estiver sendo realizada a atualização. O IIS será iniciado automaticamente ao final da atualização.

#### Problema 4: Durante a atualização, você não deve executar aplicativos que chamem APIs do WSUS

As chamadas da interface de programação de aplicativo (API) do WSUS entrarão em conflito com o instalador do WSUS com SP1, gerando falha na atualização (você receberá uma mensagem solicitando a reinicialização do servidor para concluir a atualização).

#### Problema 5: Ao atualizar para o WSUS com SP1, talvez você precise desabilitar programas antivírus

Quando você atualizar o WSUS aplicando o WSUS com SP1, talvez tenha de desabilitar programas antivírus para poder executar a atualização ou aplicar o service pack com êxito. Após desabilitar os programas antivírus, reinicie o computador com o Windows Server antes de aplicar a atualização ou o service pack. Este procedimento evita o bloqueio dos arquivos necessários para a atualização. Depois que a instalação for concluída, habilite novamente o programa antivírus. Visite o site do fornecedor do antivírus para conhecer as etapas exatas necessárias para desabilitar e reabilitar a versão e o programa antivírus.

> [!CAUTION]  
| Esta solução alternativa pode tornar o computador ou a rede mais vulneráveis a ataques de usuários ou softwares mal-intencionados, como vírus. Não recomendamos esta solução alternativa, mas damos essa informação para que você possa implementar esta alternativa a seu critério. Use esta solução alternativa por sua conta e risco. 

> ![NOTE]  
> Um programa antivírus tem a finalidade de proteger seu computador contra vírus. Você não deve baixar nem abrir arquivos de fontes não confiáveis, visitar sites em que não confia ou abrir anexos de email quando o programa antivírus estiver desabilitado. 

#### Problema 6: Se você estiver usando um servidor proxy, a atualização do SP1 poderá apagar o nome de usuário e a senha da configuração do proxy

Se você estiver usando um servidor proxy, em alguns casos a atualização do SP1 poderá apagar o nome de usuário e a senha da configuração do proxy. Isso poderá fazer com que a sincronização de atualizações de Servidores Microsoft gere um erro de “parâmetro inválido”. Para resolver o problema, redefina o nome de usuário e a senha da configuração do proxy e sincronize o servidor novamente.

#### Problema 7: Como se recuperar de uma atualização mal-sucedida para restaurar o servidor do WSUS a um estado consistente e repetir a atualização

Se a atualização para o WSUS com SP1 não for bem-sucedida, ela poderá deixar a instalação do WSUS em um estado inconsistente ou inutilizável. Para repetir a atualização para o WSUS com SP1, você precisa colocar a instalação do WSUS em um estado consistente. Para isso, você pode usar o banco de dados de backup criado no início do processo de atualização para restaurar o servidor do WSUS a um estado anterior à atualização.

Se a atualização não for bem-sucedida, siga estas etapas para repetir a atualização para o WSUS com SP1:

**Para repetir a atualização para o WSUS com SP1**
1.  Determine a localização do banco de dados de backup verificando o conteúdo do arquivo WSUSSetup\_%timestamp%.log. Esse arquivo está localizado na seguinte pasta:

    -   %programfiles%\\Update Services\\LogFiles

2.  Use o seguinte para restaurar o banco de dados de backup do computador com o WSUS:

    -   osql.exe -S &lt;Instância\_do\_Banco\_de\_Dados&gt; -E -Q "USE master ALTER DATABASE SUSDB SET SINGLE\_USER WITH ROLLBACK IMMEDIATE RESTORE DATABASE SUSDB FROM DISK=N'&lt;Caminho\_do\_Backup\_do\_Banco\_de\_Dados&gt;' WITH REPLACE ALTER DATABASE SUSDB SET MULTI\_USER"
    -   Lembre-se de substituir &lt;Instância\_do\_Banco\_de\_Dados&gt; e &lt;Caminho\_do\_Backup\_do\_Banco\_de\_Dados&gt; com valores da sua instalação.
    -   Para &lt;Instância\_do\_Banco\_de\_Dados&gt;, use o valor da seguinte chave do Registro:
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\SqlServerName
    -   Para &lt;Caminho\_do\_Backup\_do\_Banco\_de\_Dados&gt;, use o valor identificado na etapa 1

3.  Desinstale o WSUS, mas mantenha o banco de dados e os arquivos de log e de atualização do WSUS quando solicitado a removê-los. (Verifique se todas as opções de **Remover o Microsoft Windows Server Update Services** estão desmarcadas.)

4.  Reinstale a versão RTM do WSUS (a versão original, não o WSUS com SP1). Use o banco de dados existente quando solicitado a fazê-lo. Isso retornará o sistema do WSUS a um estado consistente.

5.  Instale o WSUS com SP1.

**Observação**    Não é possível usar o banco de dados de backup da etapa 1 acima diretamente em uma instalação limpa do WSUS com SP1. O esquema do banco de dados mudou; portanto, o banco de dados não será compatível sem a atualização para o WSUS com SP1.

#### Problema 8: A atualização para o WSUS com SP1 poderá falhar em alguns casos quando o banco de dados do WMSDE tiver sido migrado

A solução é diferente, dependendo de você ter migrado para um servidor SQL local ou remoto.

#### Banco de dados do WMSDE migrado para um servidor SQL 2000 local

Um valor de chave do Registro deve ser alterado para que o pacote de instalação do WSUS com SP1 reconheça que não há um banco de dados do WMSDE a ser atualizado.

Se você tiver migrado o WMSDE para um servidor SQL 2000 local, deverá fazer a seguinte alteração no Registro antes de tentar atualizar para o WSUS com SP1:

-   Altere o valor da seguinte chave do Registro de "1" para "0":
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled  

#### Banco de dados do WMSDE migrado para um servidor SQL 2000 remoto

Dois valores de chave do Registro devem ser alterados para que o pacote de instalação do WSUS com SP1 reconheça que não há um banco de dados do WMSDE a ser atualizado. A atualização deve ser iniciada no servidor back-end e, depois, no servidor front-end.  

Se você tiver migrado o WMSDE para um servidor SQL remoto, deverá fazer as seguintes alterações no Registro antes de tentar atualizar para o WSUS com SP1:

1.  Altere o valor da seguinte chave do Registro de "1" para "0":
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled 
2.  Altere o valor da seguinte chave do Registro de "0x80" para "0x20":
    -   HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\InstallType 

Depois de atualizar esses valores de chave do Registro, inicie a atualização nos servidores back-end e, depois, nos servidores front-end.

#### Problema 9: O WSUS com SP1 não atualiza servidores do WSUS instalados usando implantações remotas de SQL

Você deve executar o pacote de instalação do WSUS com SP1 nos servidores front-end e back-end.

**Para atualizar para o WSUS com SP1 quando o SQL remoto é usado**
1.  Execute o pacote de instalação no front-end sem opções e opte por atualizar.

2.  Execute o pacote de instalação no back-end sem opções e opte por atualizar.

#### Problema 10: A alteração do nome do computador antes de atualizar para o WSUS com SP1 pode gerar falha na atualização

Se você alterar o nome do computador depois de instalar a versão RTM do WSUS e antes de atualizar para o WSUS com SP1, a atualização poderá falhar.

Use o seguinte script para remover e adicionar novamente os grupos Administradores do ASP.NET e do WSUS. Em seguida, execute a atualização novamente.

```
    osql.exe -S %computername%\WSUS -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=name from sysusers WHERE name like '%ASPNET' EXEC sp_revokedbaccess @asplogin"
    osql.exe -S %computername%\WSUS -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=name from sysusers WHERE name like '%WSUS Administrators' EXEC sp_revokedbaccess @wsusadminslogin"
 
    osql.exe -S %computername%\WSUS -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=HOST_NAME()+'\ASPNET' EXEC sp_grantlogin @asplogin EXEC sp_grantdbaccess @asplogin EXEC sp_addrolemember webService,@asplogin"
    osql.exe -S %computername%\WSUS -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=HOST_NAME()+'\WSUS Administrators' EXEC sp_grantlogin @wsusadminslogin EXEC sp_grantdbaccess @wsusadminslogin EXEC sp_addrolemember webService,@wsusadminslogin"
 
    osql.exe -S %computername%\WSUS -E -Q "backup database SUSDB to disk=N'<ContentDirectory>\SUSDB.Dat' with init"
```

> [!NOTE]
> Talvez seja necessário substituir &lt;Diretório\_de\_conteúdo&gt; na última linha pelo caminho do armazenamento de conteúdo real.

Conteúdo original do Leiame do WSUS
-----------------------------------

O conteúdo a seguir é o texto original do arquivo Leiame do WSUS. O WSUS com SP1 *não* resolve nenhum dos problemas a seguir. Este conteúdo foi incluído aqui para sua comodidade.

Antes de iniciar
----------------

#### Problema 1: O IIS deve estar instalado

O Microsoft® Windows Server™ Update Services (WSUS) requer que os Serviços de Informações da Internet (IIS) estejam instalados. Entretanto, no Microsoft Windows Server 2003 e no Microsoft Windows® 2000 Server, o IIS não é instalado por padrão; por isso, a instalação do Windows Server Update Services pode não ser capaz de continuar, exibindo uma mensagem de erro que informa que o IIS não está instalado.

Para instalar o IIS:

1.  Abra o Painel de Controle.
2.  Clique duas vezes em **Adicionar ou Remover Programas**.
3.  Clique em **Adicionar ou Remover Componentes do Windows**.
4.  Na lista **Componentes**, clique em **Servidor de Aplicativo**.
5.  Clique em **Detalhes**.
6.  Marque a caixa de seleção **ASP.NET**. Habilite o **acesso ao COM+ de rede**, e o IIS será selecionado automaticamente.
7.  Selecione **Serviços de Informações da Internet (IIS)** e clique em **Detalhes** para exibir a lista de componentes opcionais do IIS.
8.  Selecione todos os componentes opcionais que você deseja instalar. O componente opcional Serviço World Wide Web inclui subcomponentes importantes, como o componente Active Server Pages e a Administração Remota (HTML). Para exibir e selecionar esses subcomponentes, clique em Serviço World Wide Web e em Detalhes. Clique em OK até voltar ao Assistente de Componentes do Windows.
9.  Clique em **Avançar** e conclua o Assistente de Componentes do Windows.
10. Depois de instalar o IIS, execute a instalação do Windows Server Update Services.

#### Problema 2: Para servidores que executam o Windows 2000 Server, deve haver pelo menos um site no IIS antes de você instalar o WSUS

A instalação do Windows Server Update Services poderá não criar um site se não houver sites no IIS quando a instalação for executada. Isso pode acontecer, por exemplo, se você tiver um site do Software Update Services (SUS) 1.0 como o único site do IIS e excluí-lo antes de instalar o WSUS.

Nesse caso, você precisará criar um novo site usando o snap-in Gerenciador dos Serviços de Informações da Internet (IIS). Depois que fizer isso, poderá selecionar o site ou especificar um novo site durante a instalação do WSUS.

Se você já tentou instalar o WSUS e a instalação não foi bem-sucedida porque não havia sites, abra o snap-in Gerenciador do IIS e exclua o site "Site Nº 1". Depois, siga as etapas descritas anteriormente e reexecute a instalação.

#### Problema 3: Instalando componentes de pré-requisito

#### Requisitos de software

A tabela a seguir mostra os requisitos de software de cada sistema operacional com suporte. Verifique se o servidor do WSUS atende a esta lista de requisitos antes de executar a instalação do WSUS. Se alguma dessas atualizações exigir a reinicialização do computador quando a instalação for concluída, você deverá reiniciá-lo antes de instalar o WSUS.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Sistema operacional</th>
<th style="border:1px solid black;" >Requisitos</th>
<th style="border:1px solid black;" >Downloads</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Todos os sistemas operacionais</td>
<td style="border:1px solid black;">Microsoft IIS 5.0</td>
<td style="border:1px solid black;">Instale a partir do sistema operacional.
Consulte o Problema 1: O IIS deve estar instalado.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Todos os sistemas operacionais</td>
<td style="border:1px solid black;">Serviço de Transferência Inteligente em Segundo Plano (BITS) 2.0</td>
<td style="border:1px solid black;">Para os sistemas operacionais Windows Server 2003, consulte Atualização para o BITS (Serviço de Transferência Inteligente em Segundo Plano) 2.0 e o WinHTTP 5.1 Windows Server 2003 (KB842773) no Centro de Download (<a href="http://go.microsoft.com/fwlink/?linkid=47251">http://go.microsoft.com/fwlink/?LinkId=47251</a>).
Para os sistemas operacionais Windows Server 2000, consulte Atualização para o BITS (Serviço de Transferência Inteligente em Segundo Plano) 2.0 e o WinHTTP 5.1 Windows 2000 (KB842773) no Centro de Download (<a href="http://go.microsoft.com/fwlink/?linkid=46794">http://go.microsoft.com/fwlink/?LinkId=46794</a>).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2003</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47358">Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2003</a>
Se preferir, acesse o site do <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a> e verifique se existem Atualizações Críticas e Service Packs; instale o Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2003.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">Software de banco de dados totalmente compatível com o Microsoft SQL</td>
<td style="border:1px solid black;">N/D</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Software de banco de dados totalmente compatível com o Microsoft SQL</td>
<td style="border:1px solid black;">Se você não estiver usando o Microsoft SQL Server 2000, poderá instalar o Microsoft SQL Server 2000 Desktop Engine (MSDE 2000). Isso requer várias etapas. Para obter mais informações, consulte abaixo o tópico Instalando o MSDE no Windows 2000.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft Internet Explorer 6.0 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47359">Internet Explorer 6 Service Pack 1</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Pacote de Componentes Redistribuíveis do Microsoft .NET Framework Versão 1.1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47369">Pacote de Componentes Redistribuíveis do Microsoft .NET Framework Versão 1.1</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47368">Microsoft .NET Framework 1.1 Service Pack 1</a>
Se preferir, acesse o site do <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a> e verifique se existem Atualizações Críticas e Service Packs; instale o Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2000.</td>
</tr>
</tbody>
</table>
 

Além desses requisitos, o WSUS poderá instalar ou configurar o ASP.NET versão 1.1 no servidor, caso seja necessário. (A instalação do WSUS configura o ASP.NET.)

#### Instalando o MSDE 2000 no Windows 2000

Se você estiver usando o Windows 2000 para WSUS e não tiver acesso ao Microsoft SQL Server 2000, deverá instalar o Microsoft SQL Server 2000 Desktop Engine (MSDE) antes de executar a instalação do WSUS. Se o MSDE já estiver instalado no servidor do WSUS, não será necessário configurar uma instância especial dele para o WSUS. Você pode simplesmente indicar o nome da instância existente durante o processo de instalação do WSUS.

O processo de instalação do MSDE no Windows 2000 Server tem quatro etapas. Primeiro, você deve baixar e expandir o arquivo morto do MSDE em uma pasta do servidor do WSUS. Em seguida, use um prompt de comando e opções de linha de comando para executar a instalação do MSDE, definir a senha SA e designar WSUS como o nome da instância. Quando a instalação do MSDE for concluída, você deverá verificar se a instância do WSUS está sendo executada como um serviço do NT. Por último, adicione um patch de segurança ao MSDE para proteger o servidor do WSUS.

#### Etapa 1: Baixar e expandir o arquivo morto do MSDE

Você deve baixar e expandir o arquivo morto do MSDE em uma pasta do servidor do WSUS. Consulte [Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Versão A](http://go.microsoft.com/fwlink/?linkid=47366) (a página pode estar em inglês).

#### Etapa 2: Instalar o MSDE

Use um prompt de comando e opções de linha de comando para executar a instalação do MSDE, definir a senha SA e designar WSUS como o nome da instância. Quando a instalação do MSDE for concluída, você deverá verificar se a instância do WSUS está sendo executada como um serviço do NT.

Para instalar o MSDE, defina a senha SA e designe um nome de instância:

1.  No prompt de comando, navegue até a pasta de instalação do MSDE especificada na “Etapa 1: Baixar e expandir o arquivo morto do MSDE”.
2.  Digite o seguinte: **setup sapwd="***senha***" instancename=WSUS**
    onde *senha* é uma senha de alta segurança para a conta SA nesta instância do MSDE e **instancename** corresponde ao nome da instância do banco de dados. Como alternativa, você pode usar o nome de instância padrão (em vez de "WSUS") para o banco de dados do WSUS. Nesse caso, você não precisará digitar **instancename=WSUS** no parâmetro de linha de comando. Esse comando inicia o programa de instalação do MSDE, define a senha SA e nomeia a instância do MSDE com qualquer valor especificado por você.

#### Etapa 3: Verificar se a instância do WSUS do MSDE está instalada

1.  Clique em **Iniciar** e em **Executar**.
2.  Na caixa **Abrir**, digite **services.msc** e clique em **OK**.

Role a lista de serviços e verifique se há um serviço chamado MSSQL$WSUS (se você usou "WSUS" para instancename) ou MSSQLSERVER (se usou o nome de instância padrão).

#### Etapa 4: Iniciar a instância do MSDE

Ao final da instalação do MSDE, será necessário iniciar a instância. Se você usou "WSUS" para instancename, inicie "MSSQL$WSUS". Se usou o nome de instância padrão, inicie MSSQLSERVER. A menos que você inicie esse serviço, o WSUS não poderá usar a instância do banco de dados.

#### Etapa 5: Atualizar o MSDE

Você deve baixar e instalar o patch de segurança descrito no boletim [MS03-031: Patch cumulativo de segurança para SQL Server](http://go.microsoft.com/fwlink/?linkid=47364) (a página pode estar em inglês).

Para baixar o patch de segurança, consulte [Patch de segurança MS03-031 do SQL Server 2000 (32 bits)](http://go.microsoft.com/fwlink/?linkid=47363) (a página pode estar em inglês).

#### Problema 4: Requisitos mínimos de espaço em disco

Estes são os requisitos mínimos de espaço em disco para instalar o Windows Server Update Services:

-   1 GB na partição do sistema
-   2 GB para o volume em que serão armazenados os arquivos de banco de dados
-   6 GB, baseado em números de projeção de conteúdo

#### Problema 5: É preciso desinstalar as versões anteriores do WSUS usando Adicionar ou Remover Programas antes de instalar a versão mais recente

Se você pretende instalar o Windows Server Update Services em um servidor que tenha o Windows Update Services Beta 1 ou Beta 2 instalado, primeiro desinstale a versão anterior usando Adicionar ou Remover Programas no Painel de Controle.

#### Problema 6: O WSUS requer que a opção de disparadores aninhados esteja ativada no SQL Server

Essa opção é ativada por padrão, mas pode ser desativada por um administrador do SQL Server.

Se você pretende usar um banco de dados do SQL Server como o armazenamento de dados do Windows Server Update Services, o administrador do SQL Server deverá verificar se a opção de disparadores aninhados no servidor está ativada antes que o administrador do WSUS instale o WSUS e especifique o banco de dados durante a instalação.

A instalação do WSUS ativa a opção RECURSIVE\_TRIGGERS, que é uma opção específica do banco de dados; entretanto, ela não ativa a opção de disparadores aninhados, que é uma opção global do servidor.

Para verificar se os disparadores aninhados estão ativados, use o seguinte:

**sp\_configure 'nested triggers'**

Para ativar a opção de disparadores aninhados no SQL Server, execute o seguinte a partir de um arquivo em lotes no computador com o SQL Server em execução:

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

#### Problema 7: Parâmetros de linha de comando da instalação do WSUS

Você pode executar instalações autônomas do WSUS. Para obter mais informações e parâmetros de linha de comando, consulte o apêndice A sobre instalação autônoma no tópico sobre [implantação do Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777) (a página pode estar em inglês).

Problemas conhecidos
--------------------

#### Problema 1: Assistente de Bloqueio do IIS

Se você estiver executando os Serviços de Informações da Internet (IIS) em um computador com o Windows 2000 Server, instale a versão mais recente do Assistente de Bloqueio do IIS (que inclui o URLScan) disponível na página da Ferramenta de Bloqueio do IIS, no Microsoft TechNet (a página pode estar em inglês). A Microsoft recomenda enfaticamente que você instale essa ferramenta para ajudar a manter os servidores do IIS protegidos. O Assistente de Bloqueio do IIS funciona desativando os recursos desnecessários do IIS, reduzindo assim a exposição a riscos de segurança.

> [!NOTE]  
> A instalação do WSUS não instala esses componentes. É necessário instalá-los manualmente. Você não precisa instalar o Bloqueio do IIS em computadores com o Windows Server 2003 em execução, porque a funcionalidade já está presente nele. 

#### Problema 2: Não é permitido alterar a configuração do WSUS diretamente no banco de dados

O Windows Server Update Services armazena os dados de configuração em um banco de dados (MSDE ou SQL Server). No entanto, não é permitido alterar os dados da configuração acessando o banco de dados diretamente. Os administradores não devem tentar modificar a configuração do WSUS dessa maneira. A maneira permitida de alterar a configuração do WSUS é usar o console do WSUS ou chamar APIs do WSUS.

#### Problema 3: É necessário habilitar os scripts ativos para acessar o site de administração do WSUS

Na estação de trabalho do administrador, configure o Internet Explorer para permitir scripts ativos, para que você possa usar o Internet Explorer a fim de acessar o site de administração do WSUS.

#### Problema 4: O IIS será reiniciado durante a instalação do WSUS

A instalação do Windows Server Update Services reiniciará o IIS sem avisá-lo. Isso poderia afetar sites existentes na sua organização.

#### Problema 5: Alterando o acesso ao diretório virtual dos pontos de gerenciamento (MPs) do WSUS ou SMS

Por padrão, o diretório virtual de conteúdo do Windows Server Update Services é definido com acesso anônimo. Se você alterar essa configuração para exigir autenticação, os clientes receberão erros de autenticação e será negado o acesso para baixar atualizações. Esse é um problema conhecido em que Winhttp.dll usa o contexto de autenticação errado quando é necessária a autenticação implícita, por isso o pedido de autenticação falhará. Para que isso não aconteça, verifique se os MPs do servidor do WSUS e do SMS estão configurados com acesso anônimo aos diretórios virtuais do IIS.

#### Problema 6: Ao instalar o WSUS no Windows Small Business Server 2003, as configurações de acesso dos vroots do WSUS do site padrão devem ser modificadas para permitir a auto-atualização dos clientes do WSUS a partir do servidor

O servidor do WSUS instala dois vroots, SelfUpdate e ClientWebService, e alguns arquivos no diretório base do site padrão (na porta 80). Isso permite que os clientes façam a auto-atualização através do site padrão. Por padrão, no Windows Small Business Server 2003, o site padrão é configurado para negar acesso a qualquer IP ou host local que não sejam os do servidor. Isso significa que é negado acesso para os vroots SelfUpdate e ClientWebService e que os clientes não poderão fazer a auto-atualização. Para conceder acesso aos clientes para auto-atualização, execute as seguintes etapas nos vroots SelfUpdate e ClientWebService do site padrão:

1.  Clique no vroot **Propriedades**, clique em **Segurança de Diretório**, clique em **Restrições de endereço IP e nome de domínio** e em **Editar**.
2.  Selecione **Acesso Concedido** e clique em **OK**. Feche todas as páginas de propriedades.

#### Problema 7: Instalando o WSUS no Small Business Server - problemas de integração

-   Se o Windows Small Business Server 2003 usar um servidor proxy ISA para acessar a Internet, você deverá digitar o seguinte na interface de usuário **Configurações**: configurações do servidor proxy, nome do servidor proxy e porta.
-   Se o ISA estiver usando a Autenticação do Windows, as credenciais do servidor proxy deverão ser digitadas no formato "DOMÍNIO\\usuário" (o usuário que pertence ao grupo "Usuários da Internet").

#### Problema 8: Quando um computador é movido de um grupo de computadores para outro, pode levar até uma hora para que ele apareça no novo grupo conforme exibido no console de administração

Quando um computador é atribuído a um grupo de destino pela primeira vez, os dados existentes no computador são modificados com as informações do grupo. Esses dados são atualizados periodicamente ou a cada hora. Portanto, ao mover um computador de um grupo de computadores para outro, pode levar até uma hora para que as informações sejam atualizadas no cliente e exibidas conforme as alterações feitas no console de administração do WSUS.

#### Problema 9: Se você instalar o WSUS em um servidor membro e, depois, quiser promover o servidor membro a um controlador de domínio, primeiro deverá desinstalar o WSUS

Se você instalar o WSUS em um servidor membro e, depois, quiser promover o servidor membro a um controlador de domínio, deverá executar as seguintes etapas:

1.  Desinstale o WSUS.
2.  Promova o servidor a um controlador de domínio.
3.  Reinstale o WSUS.

#### Problema 10: Se você quiser rebaixar um servidor do WSUS de um controlador de domínio a um servidor membro, primeiro deverá desinstalar o WSUS

Se você estiver executando o servidor do WSUS em um controlador de domínio e quiser rebaixar o controlador de domínio a um servidor membro, deverá executar as seguintes etapas:

1.  Desinstale o WSUS e mantenha o banco de dados.
2.  Crie uma conta de usuário chamada ASPNET.
3.  No prompt de comando, digite **aspnet\_regiis -i**.
4.  Reinstale o WSUS e use o banco de dados mantido.

#### Problema 11: Se o .NET Framework 1.0 ou 2.0 for instalado após a instalação do WSUS, o console administrativo do WSUS não aparecerá

Isso acontece porque o .NET Framework 1.0 é registrado no IIS e o servidor do WSUS requer o .NET Framework 1.1. Para resolver esse problema, abra aspnet\_regiis.exe e execute os seguintes comandos, onde *id do site* é o valor contido na seguinte chave do Registro:

HKLM\\Software\\Microsoft\\WindowsUpdateServices\\Server\\Setup\\IISTargetWebsiteIndex

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\ReportingWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\ClientWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\SimpleAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\WSUSAdmin
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\AdministrationWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\ServrSyncWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\DssAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\Content

#### Problema 12: Limitações do SQL remoto

O WSUS oferece suporte limitado para a execução de software de banco de dados em um computador separado do computador com o restante do aplicativo WSUS.

-   Não é possível usar o Windows 2000 Server como o computador front-end em um par de SQL remoto.
-   Não é possível usar um servidor configurado como controlador de domínio para o front-end ou o back-end do par de SQL remoto.
-   Não é possível usar o WMSDE nem o MSDE para software de banco de dados no computador back-end.
-   A configuração de um servidor SQL remoto (a ser usado como banco de dados do WSUS) falha se os Serviços de Terminal estiverem instalados no servidor remoto e executando no modo de aplicativo. Ao instalar o SQL Server em um servidor dos Serviços de Terminal, você deverá executar o seguinte procedimento:
    1.  Antes de executar a instalação, abra um prompt de comando e digite: "change user /install"
    2.  Execute a instalação do SQL Server.
    3.  Após executar a instalação, digite o seguinte no prompt de comando: "change user /execute"
-   Você deve ser membro do grupo de segurança de administradores locais nos computadores front-end e back-end para poder configurar o banco de dados WSUS do SQL Server remoto.
-   Para obter mais informações sobre problemas relacionados ao SQL remoto, consulte o apêndice C sobre o SQL remoto no tópico sobre [implantação do Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777) (a página pode estar em inglês).

#### Problema 13: Um servidor downstream de réplica pode ter menos aprovações do que o servidor upstream pai

Um servidor downstream de réplica pode ter menos aprovações do que o servidor upstream pai. Isso acontece porque as aprovações de instalação só fluem para um servidor downstream depois que termina o download do conteúdo no servidor upstream.

#### Problema 14: Repetir a sincronização se ocorrer uma falha na sincronização inicial

Se a sincronização não for bem-sucedida, sua primeira ação para resolver o problema deverá ser tentar sincronizar o servidor novamente. Se a próxima tentativa de sincronização falhar, use as informações de solução de problemas disponíveis no Guia de Operações do WSUS.

#### Problema 15: Quando você tenta acessar o console de administração do WSUS, é exibida uma mensagem de erro System.IO.FileNotFoundException

Se você receber a seguinte mensagem de erro, talvez precise ajustar as permissões nas contas Serviço de Rede ou ASP.NET:

System.IO.FileNotFoundException: O arquivo ou assembly chamado *xxxxxx*.dll, ou uma de suas dependências, não foi encontrado

Onde *xxxx* é um nome aleatório.

Para resolver esse problema em sistemas operacionais Windows Server 2003, conceda acesso de leitura/gravação em %systemroot%\\Temp para a conta Serviço de Rede. No Windows 2000 Server, conceda acesso de leitura/gravação em %systemroot%\\Temp para a conta ASP.NET.

#### Problema 16: Atualização de segurança MS03-031 do SQL (KB815495)

Esta atualização pode constar como instalada no servidor do WSUS ainda que, na verdade, ela tenha falhado no cliente. Isso pode fazer com que o pacote seja oferecido novamente para o cliente. Você pode contornar esse problema não aprovando a atualização no servidor.

#### Problema 17: Configurações do IIS são perdidas durante a atualização da versão RTM

Se você instalar a versão RTM do WSUS em um servidor com uma versão anterior do WSUS (a RC, por exemplo), a versão RTM desinstalará a versão anterior e, em seguida, instalará a nova. Isso significa que os vroots e arquivos associados ao WSUS no IIS serão excluídos.

Se tiver instalado o WSUS no site padrão, você perderá todas as configurações relacionadas ao WSUS definidas nos vroots do WSUS. Por exemplo, se você tiver configurado os vroots do WSUS para SSL com a intenção de proteger o WSUS, terá que reconfigurá-los depois de instalar a versão RTM do WSUS. Observação: você receberá uma notificação no console do WSUS informando que o SSL não está habilitado.

Se você tiver instalado o WSUS em um site diferente do padrão, todas as configurações adicionais no nível do site do WSUS serão perdidas.

#### Problema 18: Usando cabeçalhos de host

Se quiser atribuir valores de cabeçalho de host ao site padrão (site do WSUS) no IIS, você precisará adicionar ao site padrão “Todos os Não Atribuídos” ou um endereço IP atribuído à lista de endereços IP sem definir um valor de cabeçalho de host. Essa informação também deve ser adicionada ao site que não é o padrão.

**Aviso**: isso pode danificar a funcionalidade do Microsoft SharePoint e do Exchange.

#### Problema 19: A URL do console do WSUS precisa ser adicionada à lista de zonas de conteúdo da Web Sites confiáveis e Intranet local nos computadores em que o sistema de proteção do Internet Explorer está habilitado

Se o sistema de proteção do Internet Explorer (também conhecido como o componente Configuração de Segurança Reforçada do Internet Explorer no Microsoft Windows Server 2003) estiver habilitado em um computador e você não adicionar o console do WSUS às zonas de conteúdo da Web Sites confiáveis e Intranet local, deverá informar as credenciais de usuário sempre que abrir uma página do console do WSUS.

Para adicionar o console do WSUS às zonas de conteúdo da Web **Intranet local** e **Sites confiáveis**:

1.  Abra **Opções da Internet** (por exemplo, clique em **Iniciar**, aponte para **Painel de Controle** e clique em **Opções da Internet**).
2.  Na guia **Segurança**, clique em **Intranet local**, em **Sites**, em **Avançado**, adicione a URL (http://*nome\_do\_servidor\_WSUS*/WSUSAdmin) e clique em **OK**.
3.  Clique em **Sites confiáveis**, em **Sites**, adicione a URL do console do WSUS e clique em **OK** e em **OK** novamente para sair de **Opções da Internet**.

#### Direitos autorais

As informações contidas neste documento representam a visão que a Microsoft Corporation tem atualmente sobre as questões discutidas até a data da publicação. Como a Microsoft deve responder a condições de mercado em constante mudança, essas informações não devem ser interpretadas como um compromisso da parte da Microsoft, nem a Microsoft pode garantir a exatidão de qualquer informação apresentada após a data da publicação.

Este documento se destina apenas a fins informativos. A MICROSOFT NÃO OFERECE NENHUMA GARANTIA EXPRESSA, IMPLÍCITA OU LEGAL REFERENTE ÀS INFORMAÇÕES DESTE DOCUMENTO.

O cumprimento de todas as leis de direitos autorais aplicáveis é de responsabilidade do usuário. Sem limitar os direitos protegidos pela lei de direitos autorais, nenhuma parte deste documento pode ser reproduzida, armazenada ou introduzida em sistemas de recuperação e nem transmitida de qualquer forma ou por qualquer meio (eletrônico, mecânico, por fotocópia, gravação ou de outra forma), nem para qualquer propósito, sem a permissão expressa, por escrito, da Microsoft Corporation.

A Microsoft pode ter patentes, solicitações de patentes, marcas comerciais, direitos autorais ou outros direitos de propriedade intelectual que tratam do assunto deste documento. Exceto quando expressamente declarado em um contrato de licença por escrito da Microsoft, o fornecimento deste documento não confere ao usuário nenhuma licença sobre essas patentes, marcas comerciais, direitos autorais ou outras propriedades intelectuais.

Salvo indicação em contrário, os exemplos de empresas, organizações, produtos, nomes de domínio, endereços de email, logotipos, pessoas, lugares e acontecimentos aqui mencionados são fictícios e de nenhuma forma pretendem representar qualquer empresa, organização, produto, nome de domínio, endereço de email, logotipo, pessoa, lugar ou acontecimento real.

© 2006 Microsoft Corporation. Todos os direitos reservados.

Microsoft, SQL Server, Windows e Windows Server são marcas registradas ou marcas comerciais da Microsoft Corporation nos Estados Unidos e/ou em outros países.

Os nomes reais das empresas e dos produtos aqui mencionados podem ser marcas comerciais de seus respectivos proprietários.
