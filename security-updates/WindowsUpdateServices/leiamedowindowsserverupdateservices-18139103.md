---
TOCTitle: Leiame do Windows Server Update Services
Title: Leiame do Windows Server Update Services
ms:assetid: '4244109a-395a-4ff8-9989-ea55ab0964a3'
ms:contentKeyID: 18139103
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720505(v=WS.10)'
---

Leiame do Windows Server Update Services
========================================

Este documento descreve problemas conhecidos que afetam o WSUS. Inclui recomendações e requisitos de instalação do WSUS.

> [!NOTE]  
> Uma cópia deste documento está disponível para download no Centro de Download da Microsoft [(http://go.microsoft.com/fwlink/?LinkId=48126](http://go.microsoft.com/fwlink/?linkid=48126)).

Antes de iniciar
----------------

#### Problema 1: o IIS deve estar instalado

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

#### Problema 2: para servidores que executam o Windows 2000 Server, deve haver pelo menos um site no IIS antes de você instalar o WSUS

A instalação do Windows Server Update Services poderá não criar um site se não houver sites no IIS quando a instalação for executada. Isso pode acontecer, por exemplo, se você tiver um site do Software Update Services (SUS) 1.0 como o único site do IIS e excluí-lo antes de instalar o WSUS.

Nesse caso, você precisará criar um novo site usando o snap-in Gerenciador dos Serviços de Informações da Internet (IIS). Depois que fizer isso, poderá selecionar o site ou especificar um novo site durante a instalação do WSUS.

Se você já tentou instalar o WSUS e a instalação não foi bem-sucedida porque não havia sites, abra o snap-in Gerenciador do IIS e exclua o site "Site Nº 1". Depois, siga as etapas descritas anteriormente e reexecute a instalação.

#### Problema 3: instalação de componentes de pré-requisito

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
Consulte o Problema 1: o IIS deve estar instalado.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Todos os sistemas operacionais</td>
<td style="border:1px solid black;">Serviço de Transferência Inteligente em Segundo Plano (BITS) 2.0</td>
<td style="border:1px solid black;">Para os sistemas operacionais Windows Server 2003, consulte <a href="http://go.microsoft.com/fwlink/?linkid=47251">Atualização para o BITS (Serviço de Transferência Inteligente em Segundo Plano) 2.0 e o WinHTTP 5.1 Windows Server 2003</a> (KB842773) no Centro de Download (http://go.microsoft.com/fwlink/?LinkId=47251).
Para os sistemas operacionais Windows Server 2000, consulte <a href="http://go.microsoft.com/fwlink/?linkid=46794">Atualização para o BITS (Serviço de Transferência Inteligente em Segundo Plano) 2.0 e o WinHTTP 5.1 Windows 2000</a> (KB842773) no Centro de Download (http://go.microsoft.com/fwlink/?LinkId=46794).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2003</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47358">Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2003</a>
Se preferir, acesse o site do <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a> e verifique se existem Atualizações Críticas e Service Packs; instale o Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2003.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47359">Internet Explorer 6 Service Pack 1</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Pacote Redistribuível do Microsoft .NET Framework Versão 1.1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47369">Pacote Redistribuível do Microsoft .NET Framework Versão 1.1</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47368">Microsoft .NET Framework 1.1 Service Pack 1</a>
Se preferir, acesse o site do <a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a> e verifique se existem Atualizações Críticas e Service Packs; instale o Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2000.</td>
</tr>
</tbody>
</table>
 

Além desses requisitos, o WSUS poderá instalar ou configurar o ASP.NET versão 1.1 no servidor, caso seja necessário. (A instalação do WSUS configura o ASP.NET.)

#### Instalando o MSDE 2000 no Windows 2000

Se você estiver usando o Windows 2000 para WSUS e não tiver acesso ao Microsoft SQL Server 2000, deverá instalar o Microsoft SQL Server 2000 Desktop Engine (MSDE) antes de executar a instalação do WSUS. Se o MSDE já estiver instalado no servidor do WSUS, não será necessário configurar uma instância especial dele para o WSUS. Você pode simplesmente indicar o nome da instância existente durante o processo de instalação do WSUS.

O processo de instalação do MSDE no Windows 2000 Server tem quatro etapas. Primeiro, você deve baixar e expandir o arquivo morto do MSDE em uma pasta do servidor do WSUS. Em seguida, use um prompt de comando e opções de linha de comando para executar a instalação do MSDE, definir a senha SA e designar WSUS como o nome da instância. Quando a instalação do MSDE for concluída, você deverá verificar se a instância do WSUS está sendo executada como um serviço do NT. Por último, adicione uma atualização de segurança ao MSDE para proteger o servidor do WSUS.

#### Etapa 1: baixar e expandir o arquivo morto do MSDE

Você deve baixar e expandir o arquivo morto do MSDE em uma pasta do servidor do WSUS. Consulte [Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Versão A](http://go.microsoft.com/fwlink/?linkid=47366).

#### Etapa 2: instalar o MSDE

Use um prompt de comando e opções de linha de comando para executar a instalação do MSDE, definir a senha SA e designar WSUS como o nome da instância. Quando a instalação do MSDE for concluída, você deverá verificar se a instância do WSUS está sendo executada como um serviço do NT.

Para instalar o MSDE, defina a senha SA e designe um nome de instância:

1.  No prompt de comando, navegue até a pasta de instalação do MSDE especificada na “Etapa 1: Baixar e expandir o arquivo morto do MSDE”.
2.  Digite o seguinte: **setup sapwd="***senha***" instancename=WSUS**
    em que *senha* é uma senha de alta segurança para a conta SA nesta instância do MSDE e **instancename** corresponde ao nome da instância do banco de dados. Como alternativa, você pode usar o nome de instância padrão (em vez de "WSUS") para o banco de dados do WSUS. Nesse caso, você não precisará digitar **instancename=WSUS** no parâmetro de linha de comando. Esse comando inicia o programa de instalação do MSDE, define a senha SA e nomeia a instância do MSDE com qualquer valor especificado por você.

#### Etapa 3: verificar se a instância do WSUS do MSDE está instalada

Verifique se pode ver a instância do WSUS do MSDE.

1.  Clique em **Iniciar** e em **Executar**.
2.  Na caixa **Abrir**, digite **services.msc** e clique em **OK**.

Role a lista de serviços e verifique se há um serviço chamado MSSQL$WSUS (se você usou "WSUS" para instancename) ou MSSQLSERVER (se usou o nome de instância padrão).

#### Etapa 4: Iniciar a instância do MSDE.

Ao final da instalação do MSDE, será necessário iniciar a instância. Se você usou "WSUS" para instancename, inicie "MSSQL$WSUS". Se usou o nome de instância padrão, inicie MSSQLSERVER. A menos que você inicie esse serviço, o WSUS não poderá usar a instância do banco de dados.

#### Etapa 5: atualizar o MSDE

Você deve baixar e instalar a atualização de segurança descrita no boletim [MS03-031: Patch cumulativo de segurança para SQL Server](http://go.microsoft.com/fwlink/?linkid=47364).

Para baixar a atualização de segurança, consulte o tópico sobre [patch de segurança MS03-031 do SQL Server 2000 (32 bits)](http://go.microsoft.com/fwlink/?linkid=47363).

#### Problema 4: requisitos mínimos de espaço em disco

Estes são os requisitos mínimos de espaço em disco para instalar o Windows Server Update Services:

-   1 GB na partição do sistema
-   2 GB para o volume em que serão armazenados os arquivos de banco de dados
-   6 GB, baseado em números de projeção de conteúdo

#### Problema 5: é preciso desinstalar as versões anteriores do WSUS usando Adicionar ou Remover Programas antes de instalar a versão mais recente

Se você pretende instalar o Windows Server Update Services em um servidor que tenha o Windows Update Services Beta 1 ou Beta 2 instalado, primeiro desinstale a versão anterior usando Adicionar ou Remover Programas no Painel de Controle.

#### Problema 6: o WSUS requer que a opção de disparadores aninhados esteja ativada no SQL Server

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

#### Problema 7: parâmetros de linha de comando da instalação do WSUS

Você pode executar instalações autônomas do WSUS. Para obter mais informações e parâmetros de linha de comando, consulte o apêndice A sobre instalação autônoma no tópico sobre [implantação do Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777).

Problemas conhecidos
--------------------

#### Problema 1: assistente de Bloqueio do IIS

Se você estiver executando os Serviços de Informações da Internet (IIS) em um computador com o Windows 2000 Server, instale a versão mais recente do Assistente de Bloqueio do IIS (que inclui o URLScan) disponível na página da Ferramenta de Bloqueio do IIS, no Microsoft TechNet. A Microsoft recomenda enfaticamente que você instale essa ferramenta para ajudar a manter os servidores do IIS protegidos. O Assistente de Bloqueio do IIS funciona desativando os recursos desnecessários do IIS, reduzindo assim a exposição a riscos de segurança.

> [!NOTE]  
> A instalação do WSUS não instala esses componentes. É necessário instalá-los manualmente. Você não precisa instalar o Bloqueio do IIS em computadores com o Windows Server 2003 em execução, porque a funcionalidade já está presente nele. 

#### Problema 2: não é permitido alterar a configuração do WSUS diretamente no banco de dados

O Windows Server Update Services armazena os dados de configuração em um banco de dados (MSDE ou SQL Server). No entanto, não é permitido alterar os dados da configuração acessando o banco de dados diretamente. Os administradores não devem tentar modificar a configuração do WSUS dessa maneira. A maneira permitida de alterar a configuração do WSUS é usar o console do WSUS ou chamar APIs do WSUS.

#### Problema 3: é necessário habilitar os scripts ativos para acessar o site de administração do WSUS

Na estação de trabalho do administrador, configure o Internet Explorer para permitir scripts ativos, para que você possa usar o Internet Explorer a fim de acessar o site de administração do WSUS.

#### Problema 4: o IIS será reiniciado durante a instalação do WSUS

A instalação do Windows Server Update Services reiniciará o IIS sem avisá-lo. Isso poderia afetar sites existentes na sua organização.

#### Problema 5: alterando o acesso ao diretório virtual dos pontos de gerenciamento (MPs) do WSUS ou SMS

Por padrão, o diretório virtual de conteúdo do Windows Server Update Services é definido com acesso anônimo. Se você alterar essa configuração para exigir autenticação, os clientes receberão erros de autenticação e será negado o acesso para baixar atualizações. Esse é um problema conhecido em que Winhttp.dll usa o contexto de autenticação errado quando é necessária a autenticação implícita, por isso o pedido de autenticação falhará. Para que isso não aconteça, verifique se os MPs do servidor do WSUS e do SMS estão configurados com acesso anônimo aos diretórios virtuais do IIS.

#### Problema 6: ao instalar o WSUS no Windows Small Business Server 2003, as configurações de acesso dos vroots do WSUS do site padrão devem ser modificadas para permitir a auto-atualização dos clientes do WSUS a partir do servidor

O servidor do WSUS instala dois vroots, SelfUpdate e ClientWebService, e alguns arquivos no diretório base do site padrão (na porta 80). Isso permite que os clientes façam a auto-atualização através do site padrão. Por padrão, no Windows Small Business Server 2003, o site padrão é configurado para negar acesso a qualquer IP ou host local que não sejam os do servidor. Isso significa que é negado acesso para os vroots SelfUpdate e ClientWebService e que os clientes não poderão fazer a auto-atualização. Para conceder acesso aos clientes para auto-atualização, execute as seguintes etapas nos vroots SelfUpdate e ClientWebService do site padrão:

1.  Clique no vroot **Propriedades**, clique em **Segurança de Diretório**, clique em **Restrições de endereço IP e nome de domínio** e em **Editar**.
2.  Selecione **Acesso Concedido** e clique em **OK**. Feche todas as páginas de propriedades.

#### Problema 7: instalando o WSUS no Small Business Server - problemas de integração

-   Se o Windows Small Business Server 2003 usar um servidor proxy ISA para acessar a Internet, você deverá digitar o seguinte na interface de usuário **Configurações**: configurações do servidor proxy, nome do servidor proxy e porta.
-   Se o ISA estiver usando a Autenticação do Windows, as credenciais do servidor proxy deverão ser digitadas no formato "DOMÍNIO\\usuário" (o usuário que pertence ao grupo "Usuários da Internet").

#### Problema 8: quando um computador é movido de um grupo de computadores para outro, pode levar até uma hora para que ele apareça no novo grupo conforme exibido no console de administração

Quando um computador é atribuído a um grupo de destino pela primeira vez, os dados existentes no computador são modificados com as informações do grupo. Esses dados são atualizados periodicamente ou a cada hora. Portanto, ao mover um computador de um grupo de computadores para outro, pode levar até uma hora para que as informações sejam atualizadas no cliente e exibidas conforme as alterações feitas no console de administração do WSUS.

#### Problema 9: se você instalar o WSUS em um servidor membro e, depois, quiser promover o servidor membro a um controlador de domínio, primeiro deverá desinstalar o WSUS

Se você instalar o WSUS em um servidor membro e, depois, quiser promover o servidor membro a um controlador de domínio, deverá executar as seguintes etapas:

1.  Desinstale o WSUS.
2.  Promova o servidor a um controlador de domínio.
3.  Reinstale o WSUS.

#### Problema 10: se você quiser rebaixar um servidor do WSUS de um controlador de domínio a um servidor membro, primeiro deverá desinstalar o WSUS

Se você estiver executando o servidor do WSUS em um controlador de domínio e quiser rebaixar o controlador de domínio a um servidor membro, deverá executar as seguintes etapas:

1.  Desinstale o WSUS e mantenha o banco de dados.
2.  Crie uma conta de usuário chamada ASPNET.
3.  No prompt de comando, digite **aspnet\_regiis -i**.
4.  Reinstale o WSUS e use o banco de dados mantido.

#### Problema 11: se o .NET Framework 1.0 ou 2.0 for instalado após a instalação do WSUS, o console administrativo do WSUS não aparecerá

Isso acontece porque o .NET Framework 1.0 é registrado no IIS e o servidor do WSUS requer o .NET Framework 1.1. Para resolver esse problema, abra aspnet\_regiis.exe e execute os seguintes comandos, em que *id do site* é o valor contido na seguinte chave do Registro:

HKLM\\Software\\Microsoft\\WindowsUpdateServices\\Server\\Setup\\IISTargetWebsiteIndex

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\ReportingWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\ClientWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\SimpleAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\WSUSAdmin
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\AdministrationWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\ServrSyncWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\DssAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*id do site*&gt;\\ROOT\\Content

#### Problema 12: limitações do SQL remoto

O WSUS oferece suporte limitado para a execução de software de banco de dados em um computador separado do computador com o restante do aplicativo WSUS.

-   Não é possível usar o Windows 2000 Server como o computador front-end em um par de SQL remoto.
-   Não é possível usar um servidor configurado como controlador de domínio para o front-end ou o back-end do par de SQL remoto.
-   Não é possível usar o WMSDE nem o MSDE para software de banco de dados no computador back-end.
-   A configuração de um servidor SQL remoto (a ser usado como banco de dados do WSUS) falha se os Serviços de Terminal estiverem instalados no servidor remoto e executando no modo de aplicativo. Ao instalar o SQL Server em um servidor dos Serviços de Terminal, você deverá executar o seguinte procedimento:
    1.  Antes de executar a instalação, abra um prompt de comando e digite: **change user /install**
    2.  Execute a instalação do SQL Server.
    3.  Após executar a instalação, digite o seguinte no prompt de comando: **change user /execute**
-   Você deve ser membro do grupo de segurança de administradores locais nos computadores front-end e back-end para poder configurar o banco de dados WSUS do SQL Server remoto.
-   Para obter mais informações sobre problemas relacionados ao SQL remoto, consulte o apêndice C sobre o SQL remoto no tópico sobre [implantação do Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=41777).

#### Problema 13: um servidor downstream de réplica pode ter menos aprovações do que o servidor upstream pai

Um servidor downstream de réplica pode ter menos aprovações do que o servidor upstream pai. Isso acontece porque as aprovações de instalação só fluem para um servidor downstream depois que termina o download do conteúdo no servidor upstream.

#### Problema 14: se a sincronização falhar, tente novamente

Se houver falha na sincronização, você poderá obter uma mensagem de erro. Se isso ocorrer, tente primeiro a sincronização.

#### Problema 15: quando você tenta acessar o console de administração do WSUS, é exibida uma mensagem de erro System.IO.FileNotFoundException

Se você receber a seguinte mensagem de erro, talvez precise ajustar as permissões nas contas Serviço de Rede ou ASP.NET:

System.IO.FileNotFoundException: O arquivo ou assembly chamado *xxxxxx*.dll, ou uma de suas dependências, não foi encontrado

Em que *xxxx* é um nome aleatório.

Para resolver esse problema em sistemas operacionais Windows Server 2003, conceda acesso de leitura/gravação em %systemroot%\\Temp para a conta Serviço de Rede. No Windows 2000 Server, conceda acesso de leitura/gravação em %systemroot%\\Temp para a conta ASP.NET.

#### Problema 16: atualização de segurança MS03-031 do SQL (KB815495)

Esta atualização pode constar como instalada no servidor do WSUS ainda que, na verdade, ela tenha falhado no cliente. Isso pode fazer com que o pacote seja oferecido novamente para o cliente. Você pode contornar esse problema não aprovando a atualização no servidor.

#### Problema 17: configurações do IIS são perdidas durante a atualização da versão RTM.

Se você instalar a versão RTM do WSUS em um servidor com uma versão anterior do WSUS (a RC, por exemplo), a versão RTM desinstalará a versão anterior e, em seguida, instalará a nova. Isso significa que os vroots e arquivos associados ao WSUS no IIS serão excluídos.

Se tiver instalado o WSUS no site padrão, você perderá todas as configurações relacionadas ao WSUS definidas nos vroots do WSUS. Por exemplo, se você tiver configurado os vroots do WSUS para SSL com a intenção de proteger o WSUS, terá que reconfigurá-los depois de instalar a versão RTM do WSUS. Observação: você receberá uma notificação no console do WSUS informando que o SSL não está habilitado.

Se você tiver instalado o WSUS em um site diferente do padrão, todas as configurações adicionais no nível do site do WSUS serão perdidas.

#### Problema 18: usando cabeçalhos de host

Se quiser atribuir valores de cabeçalho de host ao site padrão (site do WSUS) no IIS, você precisará adicionar ao site padrão “Todos os Não Atribuídos” ou um endereço IP atribuído à lista de endereços IP sem definir um valor de cabeçalho de host. Essa informação também deve ser adicionada ao site que não é o padrão.

**Aviso**: isso pode causar falhas na funcionalidade do Windows® SharePoint® Services and Exchange.

#### Problema 19: a URL do console do WSUS precisa ser adicionada à lista de zonas de conteúdo de Sites confiáveis e Intranet local nos computadores em que o sistema de proteção do Internet Explorer está habilitado

Se o sistema de proteção do Internet Explorer (também conhecido como o componente Configuração de Segurança Reforçada do Internet Explorer no Microsoft Windows Server 2003) estiver habilitado em um computador e você não adicionar o console do WSUS às zonas de conteúdo de Sites confiáveis e Intranet local, deverá informar as credenciais de usuário sempre que abrir uma página do console do WSUS.

Para adicionar o console do WSUS às zonas de conteúdo da Web **Intranet local** e **Sites confiáveis**:

1.  Abra **Opções da Internet** (por exemplo, clique em **Iniciar**, aponte para **Painel de Controle** e clique em **Opções da Internet**).
2.  Na guia **Segurança**, clique em **Intranet local**, em **Sites**, em **Avançado**, adicione a URL (http://*nome\_do\_servidor\_WSUS*/WSUSAdmin) e clique em **OK**.
3.  Clique em **Sites confiáveis**, em **Sites**, adicione a URL do console do WSUS e clique em **OK** e em **OK** novamente para sair de **Opções da Internet**.

#### Problema 20: ocorre uma falha na atualização da versão RC do WSUS

A atualização da versão RC do WSUS pode falhar devido a um problema na árvore de auto-atualização. Isso pode ocorrer se vários clientes fizerem a auto-atualização ao mesmo tempo que você tenta a atualização.

Para resolver o problema:

1.  Desconecte o servidor do WSUS da rede, verificando se os clientes não podem se conectar a ela.
2.  Em um prompt de comando, digite: **iisrestart /reset** e pressione ENTER.
3.  Execute a atualização.

#### Problema 21: algumas aprovações do SUS 1.0 falham ao migrar para WSUS.

Quando você migra do SUS 1.0 para WSUS, algumas aprovações no servidor SUS 1.0 falharão ao migrar para o servidor do WSUS. Isso ocorre porque várias atualizações disponíveis para o SUS 1.0 não estão mais disponíveis para o WSUS. Além disso, como o WSUS oferece suporte a mais atualizações que o SUS, pode haver atualizações importantes no servidor do WSUS não aprovadas depois da conclusão do processo de migração.

A Microsoft considera altamente recomendável que você examine o conjunto de atualizações não aprovadas no servidor do WSUS após a migração do SUS 1.0.

Para obter mais informações sobre a migração do SUS 1.0 para o WSUS, consulte o guia sobre [migração do Software Update Services para o Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=48042) em http://go.microsoft.com/fwlink/?LinkId=48042.

#### Problema 22: corrija essa entrada do Registro antes de atualizar para o WSUS 2.0 Service Pack 1, caso você tenha migrado o WMSDE para o SQL Server

Se estiver planejando atualizar o WSUS 2.0 para Service Pack 1 e tiver migrado a instalação do WMSDE para SQL Server (seja remoto ou local), altere a seguinte entrada do Registro:

HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled

O valor deve ser alterado de 1 para 0.

#### Problema 23: migrando uma instalação do SQL remoto para o WSUS 2.0 Service Pack 1

Execute as etapas a seguir ao migrar para o WSUS 2.0 Service Pack 1 com uma configuração do SQL remoto:

1) Execute o pacote de instalação no front-end sem opções e opte por atualizar.

2) Execute o pacote de instalação no back-end sem opções e opte por atualizar.

#### Direitos autorais

As informações contidas neste documento representam a visão que a Microsoft Corporation tem atualmente sobre as questões discutidas até a data da publicação. Como a Microsoft deve responder a condições de mercado em constante mudança, essas informações não devem ser interpretadas como um compromisso da parte da Microsoft, nem a Microsoft pode garantir a exatidão de qualquer informação apresentada após a data da publicação.

Este documento se destina apenas a fins informativos. A MICROSOFT NÃO OFERECE NENHUMA GARANTIA EXPRESSA, IMPLÍCITA OU LEGAL REFERENTE ÀS INFORMAÇÕES DESTE DOCUMENTO.

O cumprimento de todas as leis de direitos autorais aplicáveis é responsabilidade do usuário. Sem limitar os direitos protegidos pela lei de direitos autorais, nenhuma parte deste documento pode ser reproduzida, armazenada ou introduzida em sistemas de recuperação e nem transmitida de qualquer forma ou por qualquer meio (eletrônico, mecânico, por fotocópia, gravação ou de outra forma), nem para qualquer propósito, sem a permissão expressa, por escrito, da Microsoft Corporation.

A Microsoft pode ter patentes, solicitações de patentes, marcas comerciais, direitos autorais ou outros direitos de propriedade intelectual que tratam do assunto deste documento. Exceto quando expressamente declarado em um contrato de licença por escrito da Microsoft, o fornecimento deste documento não confere ao usuário nenhuma licença sobre essas patentes, marcas comerciais, direitos autorais ou outras propriedades intelectuais.

Salvo indicação em contrário, os exemplos de empresas, organizações, produtos, nomes de domínio, endereços de email, logotipos, pessoas, lugares e acontecimentos aqui mencionados são fictícios e de nenhuma forma pretendem representar qualquer empresa, organização, produto, nome de domínio, endereço de email, logotipo, pessoa, lugar ou acontecimento real.

© 2005 Microsoft Corporation. Todos os direitos reservados.

Microsoft, SQL Server, Windows e Windows Server são marcas registradas ou marcas comerciais da Microsoft Corporation nos Estados Unidos e/ou em outros países.

Os nomes reais das empresas e dos produtos aqui mencionados podem ser marcas comerciais de seus respectivos proprietários.
