---
TOCTitle: 'Notas de versão do Microsoft Windows Server Update Services 3.0'
Title: 'Notas de versão do Microsoft Windows Server Update Services 3.0'
ms:assetid: '94d1385f-4872-4c29-8822-3a4ec5e45ae4'
ms:contentKeyID: 18139306
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708491(v=WS.10)'
---

Notas de versão do Microsoft Windows Server Update Services 3.0
===============================================================

Estas notas de versão descrevem problemas conhecidos que afetam o Microsoft® Windows® Server Update Services (WSUS) 3.0 e incluem recomendações e requisitos para instalar o aplicativo. Estas notas contêm as seguintes seções:

-   Requisitos do sistema para instalação do servidor WSUS 3.0
-   Requisitos de configuração para instalação do servidor WSUS 3.0
-   Requisitos do sistema para instalação do console remoto do WSUS 3.0
-   Requisitos de configuração para consoles remotos do WSUS
-   Requisitos do sistema para instalação do cliente
-   Requisitos de software para instalação do servidor WSUS 3.0
-   Requisitos mínimos de espaço em disco para a instalação do servidor WSUS 3.0
-   Requisitos de atualização do WSUS 3.0
-   Parâmetros de linha de comando da instalação
-   Problemas de instalação e atualização
-   Problemas conhecidos
-   WSUS 3.0 no Windows Server® 2008
-   WSUS 3.0 no Windows Small Business Server 2003

> [!NOTE]  
> Uma cópia deste documento está disponível para download no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=71220) ([http://go.microsoft.com/fwlink/?LinkId=71220](http://go.microsoft.com/fwlink/?linkid=71220)). 

Problema importante de configuração: É necessário substituir a senha do servidor proxy no assistente de configuração
--------------------------------------------------------------------------------------------------------------------

Se estiver usando um servidor proxy que exija autenticação de nome de usuário/senha, o servidor WSUS poderá falhar ao sincronizar atualizações caso você não substitua a senha do servidor proxy quando executar o Assistente de Configuração do Servidor WSUS. Como o assistente de configuração é iniciado automaticamente no fim da instalação, esse problema pode causar erros de sincronização depois da atualização do WSUS 3.0 de uma versão mais antiga do WSUS.

Você pode evitar esse problema cancelando o assistente de configuração depois da atualização ou digitando novamente a senha de proxy correta quando executar o assistente de configuração. Para recuperar-se desse problema depois que ele ocorrer, vá para **Origem de Atualização e Servidor Proxy** na página **Opções**, digite novamente a senha do proxy e salve a configuração.

Requisitos do sistema para instalação do servidor WSUS 3.0
----------------------------------------------------------

#### O servidor WSUS 3.0 tem suporte no Windows Server 2003 Service Pack 1 e no Windows Server 2008

O servidor WSUS 3.0 tem suporte no Windows Server 2003 Service Pack 1 e no Windows Server 2008.

#### O Windows 2000 Server não tem suporte nos servidores WSUS 3.0

O Microsoft Windows® 2000 Server não é um sistema operacional com suporte nos servidores WSUS 3.0.

#### o WSUS 3.0 não tem suporte nos servidores que executam os Serviços de Terminal

Embora o WSUS 3.0 ainda possa ser executado em servidores que executem os Serviços de Terminal, essa ação não tem suporte nem é recomendada. O WSUS 3.0 não será executado em um servidor que execute os Serviços de Terminal em configurações que usem as implementações remotas do SQL Server. Como todas as ações remotas personalizadas (incluindo a instalação) em um servidor de licença do Terminal Server serão executadas como a conta do sistema e a conta do sistema do servidor não pode ter permissões no SQL Server remoto, a instalação pode falhar.

Requisitos de configuração para instalação do servidor WSUS 3.0
---------------------------------------------------------------

#### o IIS deve estar instalado

O Microsoft Windows Server Update Services 3.0 requer o ISS (Serviços de Informações da Internet), que não é instalado por padrão no Microsoft Windows Server 2003 ou no Windows Server 2008. Se você tentar instalar o WSUS 3.0 sem o IIS, a instalação do Windows Server Update Services exibirá uma mensagem de erro informando que o IIS não está instalado.

#### Se o IIS 5.0 estiver sendo executado em modo de isolamento, haverá falha na instalação

Se você tiver atualizado o servidor do Windows 2000 Server para Windows Server 2003, o IIS poderá ser executado no modo de compatibilidade do IIS 5.0. Também é possível habilitar o modo de isolamento do IIS 5.0 no Gerenciador do IIS. Isso causará falha na instalação. Será necessário desabilitar o modo de isolamento do IIS 5.0 antes de instalar o WSUS 3.0.

#### Se qualquer componente do IIS estiver instalado no modo de compatibilidade de 32 bits em uma plataforma de 64 bits, a instalação do WSUS 3.0 poderá falhar

Todos os componentes do IIS devem ser instalados no modo nativo em plataformas de 64 bits. A instalação poderá falhar se qualquer componente do IIS estiver no modo de compatibilidade de 32 bits.

#### Os servidores proxy devem dar suporte a HTTP e HTTPS

Quando você configurar o servidor raiz do WSUS (o servidor do WSUS que obtém as atualizações diretamente do Microsoft Update) e houver um servidor proxy entre o servidor do WSUS e a Internet, o servidor proxy deverá dar suporte a HTTP e HTTPS.

#### Se dois ou mais sites já estiverem em execução na porta 80, exclua todos eles, com exceção de um, antes de instalar o WSUS

Se houver dois ou mais sites em execução na porta 80 (por exemplo, o Windows® SharePoint® Services), exclua todos eles, com exceção de um, antes de instalar o WSUS. Se você não fizer isso, os clientes do servidor poderão falhar na auto-atualização.

#### Ao instalar o WSUS 3.0, pode ser necessário desabilitar os programas antivírus

Ao instalar o WSUS 3.0, pode ser necessário desabilitar os programas antivírus antes de poder executar a instalação com êxito. Após desabilitar o programa antivírus, reinicie o computador antes de iniciar a instalação do WSUS. Esse procedimento impede que os arquivos estejam bloqueados quando o processo de instalação precisar acessá-los. Após a conclusão da instalação, habilite o programa antivírus novamente. Visite o site do fornecedor do programa antivírus para obter as etapas exatas para desabilitar e reabilitar o programa antivírus e a versão.

> [!CAUTION]  
> Essa solução alternativa pode tornar seu computador ou a rede mais vulnerável a ataques por usuários ou softwares mal-intencionados, como vírus. Não recomendamos essa solução alternativa, mas fornecemos estas informações para que você possa implementar essa solução alternativa se desejar. Use essa solução alternativa por seu próprio risco. 

> [!NOTE]  
> Um programa antivírus é projetado para ajudar a proteger o computador contra vírus. Você não deve baixar nem abrir arquivos de origens não confiáveis, visitar sites não confiáveis, nem abrir anexos de email quando o programa antivírus estiver desabilitado. 

#### o WSUS 3.0 requer que a opção de disparadores aninhados esteja ativada no SQL Server

A opção de disparadores aninhados é ativada por padrão; entretanto, pode ser desativada pelo administrador do SQL Server.

Se você planeja usar um banco de dados do SQL Server como armazenamento de dados do Windows Server Update Services, o administrador do SQL Server deverá verificar se a opção de disparadores aninhados no servidor está ativada antes que o administrador do WSUS 3.0 instale o WSUS 3.0 e especifique o banco de dados durante a instalação.

A instalação do WSUS 3.0 ativa a opção RECURSIVE\_TRIGGERS, uma opção específica de banco de dados; no entanto, ela não ativa a opção de disparadores aninhados, que é uma opção global do servidor.

Para verificar se os disparadores aninhados estão ativados, use o seguinte:

**sp\_configure 'nested triggers'**

Para ativar a opção de disparadores aninhados no SQL Server, execute o seguinte a partir de um arquivo em lotes no computador que executa o SQL Server:

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

Se você não tiver o SQL Server Management Studio no servidor, poderá executar scripts SQL a partir da linha de comando. Você pode obter o Microsoft SQL Server 2005 Command Line Query Utility no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=70728) (http://go.microsoft.com/fwlink/?LinkId=70728). Para iniciar, execute **sqlcmd**.

Se desejar executar scripts SQL contra o Windows Internal Database, você também deverá baixar o SQL Native Client a partir da mesma página de download.

#### limitações e requisitos do SQL remoto

O WSUS 3.0 oferece suporte limitado para a execução de software de banco de dados em um computador separado do computador em que está o restante do aplicativo WSUS 3.0. Há alguns requisitos para configurar uma instalação do SQL remoto

-   Não é possível usar um servidor configurado como controlador de domínio para o back-end do par de SQL remoto.
-   Você não deve executar o Terminal Server no computador que será o servidor front-end de uma instalação do SLQ remoto.
-   Use pelo menos o Microsoft SQL Server 2005 Service Pack 1 (disponível no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=66143) (http://go.microsoft.com/fwlink/?LinkId=66143) para um software de banco de dados no computador back-end, se esse computador estiver executando o Windows Server 2003, e o SQL Server 2005 Service Pack 2, se estiver executando o Windows Server® 2008.
-   Os computadores front-end e back-end devem estar associados a um domínio do Active Directory, caso contrário, se estiverem em domínios diferentes, será necessário estabelecer uma relação de domínio cruzado entre os domínios antes de executar a instalação do WSUS.
-   Se você já tiver o WSUS 2.0 instalado em uma configuração do SQL remota e quiser atualizar para o WSUS 3.0, deverá desinstalar o WSUS 2.0 (usando **Adicionar ou Remover Programas** no Painel de Controle) no computador back-end e verificar se o banco de dados existente permanece intacto. Em seguida, instale o SQL Server 2005 SP 1 ou SP2 e atualize o banco de dados existente. Finalmente, instale o WSUS 3.0 no computador front-end.

#### o WSUS não pode ser instalado quando determinadas versões de pré-lançamento do Internet Explorer 7 já estiverem instaladas juntamente com os Serviços de Terminal

A instalação do WSUS falhará quando determinadas versões RC do Internet Explorer 7 estiverem presentes juntamente com os Serviços de Terminal.

Requisitos do sistema para instalação do console remoto do WSUS 3.0
-------------------------------------------------------------------

O console remoto do WSUS 3.0 pode ser instalado nestas plataformas:

-   Windows Server 2008
-   Windows Vista®
-   Windows Server 2003 SP1
-   Windows XP SP2

Requisitos de configuração para consoles remotos do WSUS
--------------------------------------------------------

#### Use uma conexão de banda larga entre um console de administração remoto e um servidor WSUS 3.0

Se você se conectar ao servidor WSUS 3.0 com um console de administração remoto usando uma conexão WAN de banda estreita, poderá ter problemas de desempenho. É possível limitar o número de atualizações e computadores vistos filtrando exibições do computador e da atualização, mas é recomendável usar uma conexão de banda larga entre o console de administração remoto e servidores WSUS 3.0. Se você tiver problemas de desempenho com o console remoto, recomendamos conectar-se ao servidor usando o Terminal Server para gerenciamento remoto.

Requisitos do sistema para instalação do cliente
------------------------------------------------

O recurso Atualizações Automáticas é o software cliente do WSUS. Ele pode ser usado com o WSUS em qualquer um destes sistemas operacionais:

-   Windows Vista
-   Windows Server 2008
-   Microsoft Windows Server 2003, qualquer edição
-   Microsoft Windows XP Professional SP2
-   Microsoft Windows 2000 Professional SP4, Windows 2000 Server SP4 ou Windows 2000 Advanced Server com SP4

Requisitos de software para instalação do servidor WSUS 3.0
-----------------------------------------------------------

A tabela a seguir mostra o software necessário para as plataformas Windows Server 2003 SP 1. O software exigido pelo Windows Server 2008 será descrito na seção sobre o WSUS 3.0 no Windows Server 2008.

Verifique se o servidor do WSUS 3.0 atende a esta lista de requisitos antes de executar a instalação do WSUS 3.0. Se alguma destas atualizações exigir que o computador seja reiniciado após a conclusão da instalação, reinicie-o antes de instalar o WSUS 3.0.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Requisito</th>
<th style="border:1px solid black;" >Detalhes</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft IIS (Serviços de Informações da Internet)</td>
<td style="border:1px solid black;">Instalar a partir do sistema operacional.
Consulte o Problema 1: o IIS deve estar instalado.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Pacote Redistribuível do Microsoft .NET Framework Versão 2.0 (x86)</td>
<td style="border:1px solid black;">Consulte Pacote de componentes redistribuíveis Microsoft .NET Framework versão 2.0 (x86) no <a href="http://go.microsoft.com/fwlink/?linkid=68935">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=68935). Para as plataformas de 64 bits, consulte a página sobre o pacote de componentes redistribuíveis Microsoft .NET Framework versão 2.0 (x64) no <a href="http://go.microsoft.com/fwlink/?linkid=70637">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70637)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Console de Gerenciamento Microsoft 3.0 para Windows Server 2003</td>
<td style="border:1px solid black;">Este é um pré-requisito para o uso da interface do usuário do WSUS 3.0. Consulte Console de Gerenciamento Microsoft 3.0 para Windows Server 2003 (KB907265) no <a href="http://go.microsoft.com/fwlink/?linkid=70412">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70412). Para as plataformas de 64 bits, consulte a página sobre o Console de Gerenciamento Microsoft 3.0 para Windows Server 2003 x64 Edition (KB907265) no <a href="http://go.microsoft.com/fwlink/?linkid=70638">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70638).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">Este é um pré-requisito para o uso da interface do usuário do WSUS 3.0. Consulte as informações sobre o Microsoft Report Viewer Redistributable 2005 no <a href="http://go.microsoft.com/fwlink/?linkid=70410">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70410).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005 (opcional)</td>
<td style="border:1px solid black;">O WSUS 3.0 instalará o Windows Internal Database para você, caso ainda não haja uma versão do SQL Server compatível instalada. Se você planeja usar um banco de dados SQL Server completo, deverá usar (no mínimo) o SQL Server 2005 SP1 (disponível no <a href="http://go.microsoft.com/fwlink/?linkid=66143">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=66143) no Windows Server 2003, ou o SQL Server 2005 SP2 (disponível no <a href="http://go.microsoft.com/fwlink/?linkid=84823">Centro de Download da Microsoft</a>, em http://go.microsoft.com/fwlink/?LinkId=84823) para Windows Server 2008.</td>
</tr>
</tbody>
</table>
  
> [!NOTE]  
> Se o WSUS 2.0 tiver sido instalado anteriormente e estiver usando o SQL Server 2000, o SQL Server Desktop Engine 2000 ou qualquer banco de dados do SQL Server anterior ao SQL Server 2005 SP1 (ou SQL Server 2005 SP2 no )Windows Server 2008, o programa de instalação do WSUS 3.0 instalará o Windows® Internal Database e migrará o banco de dados para ele. 
  
Requisitos mínimos de espaço em disco para a instalação do servidor WSUS 3.0  
----------------------------------------------------------------------------
  
Estes são os requisitos mínimos de espaço em disco para instalar o Windows Server Update Services:
  
-   1 GB na partição do sistema  
-   2 GB para o volume no qual os arquivos do banco de dados serão armazenados  
-   20 GB para o volume no qual o conteúdo está armazenado
  
> [!IMPORTANTE]
> O WSUS 3.0 não pode ser instalado em unidades compactadas. Verifique se a unidade escolhida não está compactada.
  
Requisitos de atualização do WSUS 3.0  
-------------------------------------
  
#### Verifique se a instalação do WSUS está sendo executada corretamente e faça backup do banco de dados WSUS antes da atualização
  
Se você estiver atualizando o WSUS 3.0 de uma versão anterior, verifique se a instalação atual está sendo executada corretamente e faça backup do banco de dados WSUS antes da atualização.
  
1.  Verifique os erros recentes nos logs de eventos, problemas com sincronização entre os servidores de downstream e upstream ou problemas com clientes que não tenham sido reportados. Verifique se esses problemas foram resolvidos antes de continuar.  
2.  Execute DBCC CHECKDB para verificar se o banco de dados WSUS está indexado corretamente. Para obter mais informações sobre o CHECKDB, consulte [DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948) (http://go.microsoft.com/fwlink/?LinkId=86948).  
3.  Faça backup no banco de dados WSUS.
  
#### o Software Update Services 1.0 deve ser desinstalado
  
A instalação do WSUS 3.0 falhará se o Software Update Services 1.0 estiver instalado na mesma máquina. Você deve desinstalar o Software Update Services 1.0 antes de instalar o WSUS 3.0.
  
#### a atualização de uma versão beta do WSUS 3.0 para a versão RTM do WSUS 3.0 não tem suporte, mas a atualização da versão RC para a versão RTM é permitida
  
Se você tiver uma versão beta do WSUS 3.0 já instalada, será necessário desinstalá-la e excluir o banco de dados antes de instalar a versão RTM do WSUS 3.0. A atualização pode ser feita apenas da versão RC para a versão RTM.
  
#### não é possível fazer a atualização do WSUS 2.0 para o WSUS 3.0 em um sistema operacional de 64 bits
  
O WSUS 2.0 não tem suporte em sistemas operacionais de 64 bits. Não é possível fazer a atualização do WSUS 2.0 para o WSUS 3.0 em sistemas de 64 bits.
  
Parâmetros de linha de comando da instalação  
--------------------------------------------
  
Você pode executar instalações autônomas do WSUS 3.0 usando os parâmetros de linha de comando do WSUS. Esta tabela mostra os parâmetros de linha de comando para o WSUS 3.0.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Opção</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>/q</strong></td>
<td style="border:1px solid black;">Executa uma instalação silenciosa.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/u</strong></td>
<td style="border:1px solid black;">Desinstala o produto. Também desinstala a instância do Windows Internal Database, se estiver instalado.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">Somente verificação de pré-requisito. Não instala o produto, mas inspeciona o sistema e reporta pré-requisitos ausentes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">Exibe parâmetros da linha de comando e suas descrições.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">Atualiza da versão 2.0 do WSUS. O único parâmetro válido com essa opção é /q (instalação silenciosa). A única propriedade válida com essa opção é DEFAULT_WEBSITE.</td>
</tr>
</tbody>
</table>
  
Esta tabela mostra as propriedades de linha de comando para o WSUS 3.0.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Propriedade</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">CONTENT_LOCAL</td>
<td style="border:1px solid black;">0=conteúdo hospedado localmente, 1=hospedar no Microsoft Update</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CONTENT_DIR</td>
<td style="border:1px solid black;">Caminho para o diretório do conteúdo. O padrão é <em>WSUSInstallationDrive</em><strong>\WSUS\WSUSContent</strong>, em que <em>WSUSInstallationDrive</em> é a unidade local com maior quantidade de espaço em disco.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Caminho para o diretório de dados do Windows Internal Database.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQLINSTANCE_NAME</td>
<td style="border:1px solid black;">O nome deve ser exibido no formato <em>Nome_do_Servidor</em>\<em>Nome_da_Instância_SQL</em>. Se a instância do banco de dados estiver na máquina local, use a variável de ambiente %COMPUTERNAME%. Se uma instância existente estiver ausente, o padrão será %COMPUTERNAME%\WSUS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DEFAULT_WEBSITE</td>
<td style="border:1px solid black;">0=porta 8530, 1=porta 80</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PREREQ_CHECK_LOG</td>
<td style="border:1px solid black;">Caminho e nome do arquivo para arquivo de log</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CONSOLE_INSTALL</td>
<td style="border:1px solid black;">0=instalar o servidor WSUS, 1=instalar console somente</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ENABLE_INVENTORY</td>
<td style="border:1px solid black;">0=não instalar recursos de inventário, 1=instalar recursos de inventário</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_DATABASE</td>
<td style="border:1px solid black;">0=manter banco de dados, 1=remover banco de dados</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DELETE_CONTENT</td>
<td style="border:1px solid black;">0=manter arquivos de conteúdo, 1=remover arquivos de conteúdo</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_LOGS</td>
<td style="border:1px solid black;">0=reter arquivos de log, 1=remover arquivos de log (usados com a opção de instalação /u).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=usar banco de dados atual, 1=criar banco de dados</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">Identificador da janela para retornar mensagens de progresso do MSI</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=ingressar no Programa de Aperfeiçoamento do Microsoft Update, 0=não ingressar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=não gravar o local do conteúdo no banco de dados, 0=gravar o local do conteúdo no banco de dados (para NLB)</td>
</tr>
</tbody>
</table>
  
#### Exemplo de Uso
  
```  
    WSUSSetup.exe /q DEFAULT\_WEBSITE=0 (install in quiet mode using port 8530) WSUSSetup.exe /q /u (uninstall WSUS)  
```

> [!IMPORTANT]
> Se o WSUS 3.0 for instalado em modo silencioso (/q) e a máquina não tiver todos os pré-requisitos instalados, a instalação gerará um arquivo denominado WSUSPreReqCheck.xml que será salvo no diretório %TEMP%. 
  
Problemas de instalação  
-----------------------
  
#### o IIS será reiniciado durante a instalação do WSUS 3.0
  
A instalação do WSUS 3.0 reiniciará o IIS sem notificação, o que pode afetar sites existentes da organização. Se o IIS não estiver em execução, a instalação do WSUS 3.0 o inicializará.
  
#### se houver conexões abertas para um banco de dados existente do WSUS, a instalação poderá falhar
  
Se estiver atualizando o WSUS 3.0 a partir de uma instalação existente e houver conexões ainda abertas para o banco de dados do WSUS (por exemplo, se o SQL Server Management Studio estiver aberto), a instalação poderá falhar. Feche todas as conexões e reinstale o WSUS 3.0.
  
#### a instalação do WSUS exibe o diretório errado para os arquivos de banco de dados
  
Na instalação do WSUS, a tela **Pronto para Instalar** informa incorretamente que o local do banco de dados é o diretório pai do local do banco de dados. Por exemplo, o local padrão é %unidade\_do\_sistema%\\WSUS\\UpdateServicesDbFiles, mas ele é exibido incorretamente como %unidade\_do\_sistema%\\WSUS.
  
#### Se o WSUS estiver instalado em um computador que tenha pacotes de idioma para Interface do Usuário Multilíngüe com um idioma padrão diferente de inglês, a Ajuda será exibida no idioma padrão, e não em inglês.
  
Se você tiver um computador com pacotes de idioma da Interface do Usuário Multilíngüe com idioma padrão diferente do inglês, ainda poderá instalar o WSUS quando o idioma local do usuário atual for inglês. A interface do usuário será exibida em inglês, mas você deverá usar uma solução para que a Ajuda seja exibida em inglês. Copie o arquivo Help.chm do idioma inglês (*WSUSInstallDir*\\documentation\\mui\\0409\\WSUS30Help.chm) no diretório principal de documentação (*WSUSInstallDir*\\documentation\\WSUS30Help.chm). Nesse momento, a Ajuda deverá ser exibida corretamente em todos os idiomas.
  
Problemas de atualização  
------------------------
  
#### A atualização do WSUS 3.0 RC para o WSUS 3.0 RTM fará com que o certificado SSL deixe de ser atribuído ao site do WSUS
  
O site do WSUS será excluído e recriado durante a atualização do WSUS 3.0 RC para o WSUS 3.0 RTM. Como conseqüência, o certificado SSL não será mais atribuído ao site do WSUS. Será necessário reatribuir o certificado após a atualização.
  
#### recuperação de uma falha de atualização
  
Se você estiver atualizando do WSUS 2.0 para o WSUS 3.0 e a atualização falhar por alguma razão, será necessário reinstalar o WSUS 2.0 e restaurar seu banco de dados a partir do backup.
  
#### não é possível atualizar do WSUS 2.0 para o WSUS 3.0 se houver um banco de dados do WSUS 3.0 de uma instalação anterior
  
Se você tiver instalado o WSUS 3.0 anteriormente e reinstalado o WSUS 2,0, deverá excluir o banco de dados do WSUS 3.0 da máquina antes de tentar reinstalar o WSUS 3.0.
  
#### a alteração do nome do computador antes da atualização para o WSUS 3.0 pode causar uma falha na atualização
  
Se você alterar o nome do computador após instalar o WSUS 2.0 e antes de atualizar para o WSUS 3.0, ocorrerá uma falha na atualização.
  
Use o script a seguir para remover e adicionar novamente os grupos Administradores do ASPNET e do WSUS. Em seguida, execute a atualização novamente.
  
Será preciso substituir *<Local\_do\_BD>* pela pasta onde o banco de dados está instalado e *<Diretório\_de\_Conteúdo>* pela pasta do armazenamento local.
  
```
    sqlcmd.exe -S <DBLocation> -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=name from sysusers WHERE name like '%ASPNET' EXEC sp_revokedbaccess @asplogin"
    sqlcmd.exe -S <DBLocation> -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=name from sysusers WHERE name like '%WSUS Administrators' EXEC sp_revokedbaccess @wsusadminslogin"
    
    sqlcmd.exe -S <DBLocation> -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=HOST_NAME()+'\ASPNET' EXEC sp_grantlogin @asplogin EXEC sp_grantdbaccess @asplogin EXEC sp_addrolemember webService,@asplogin"
    sqlcmd.exe -S <DBLocation> -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=HOST_NAME()+'\WSUS Administrators' EXEC sp_grantlogin @wsusadminslogin EXEC sp_grantdbaccess @wsusadminslogin EXEC sp_addrolemember webService,@wsusadminslogin"
    
    sqlcmd.exe -S <DBLocation> -E -Q "backup database SUSDB to disk=N'<ContentDirectory>\SUSDB.Dat' with init"
```

#### a instalação pode substituir um backup de banco de dados anterior
  
A instalação do WSUS 3.0 adicionará o banco de dados ao diretório especificado durante a instalação. Por padrão, esse diretório é *%unidade\_do\_sistema%*\\WSUS\\UpdateServicesDbFiles. Se houver um backup de banco de dados anterior nesse diretório, ele será substituído pelo novo banco de dados. Os administradores devem fazer backup dos arquivos do banco de dados antes de aplicar atualizações no computador em que está o banco de dados.
  
#### Se você tiver migrado do MSDE para o SQL Server 2000 ou o SQL Server 2005 no WSUS 2.0, deverá alterar o valor do Registro
  
Se você tiver uma instalação do WSUS 2.0 e tiver migrado do SQL Server 2000 ou SQL Server 2005, deverá atualizar o valor **HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** de 1 para 0. Se você não fizer isso antes de atualizar o WSUS 3.0, haverá falha na atualização.
  
#### se a instalação do WSUS 2.0 for iniciada e cancelada, ela excluirá a chave do Registro do WSUS
  
Se você iniciar a instalação do WSUS 2.0 e cancelá-la, a chave do Registro do WSUS será excluída. Isso pode causar problemas se o WSUS 3.0 já estiver instalado. O mesmo problema ocorrerá se você iniciar a desinstalação do WSUS 2.0, cancelar a operação e, em seguida, tentar fazer a atualização do WSUS 2.0 para o WSUS 3.0.
  
#### se você desinstalar o WSUS 3.0 e mantiver os arquivos de log, talvez eles não tenham as permissões corretas após a reinstalação
  
Ao desinstalar o WSUS 3.0, você tem a opção de manter os arquivos de log da instalação. Na reinstalação do WSUS 3.0, os arquivos de log antigos perdem suas permissões (geralmente apenas para Administradores do WSUS). É preciso restaurar as permissões desses arquivos de log.
  
#### se o Windows SharePoint Services tiver sido instalado após o WSUS 3.0 RC, a atualização para o WSUS 3.0 RTM será bem-sucedida com uma solução alternativa
  
Se você tiver instalado o WSUS 3.0 RC e, em seguida, o Windows SharePoint Services na mesma máquina, poderá atualizar para o WSUS 3.0 RTM apenas selecionando a instalação na porta personalizada (porta 8530). Para executar essa instalação a partir da linha de comando, abra um shell de comando e, em seguida, digite o comando: **WSUSSetup /q / g/ DEFAULT\_WEBSITE=0**. (Para executar essa instalação usando a interface do usuário, digite **WSUSSetup /g DEFAULT\_WEBSITE=0**.)
  
Se o WSUS estiver instalado em um computador com pacotes de idioma de Interface do Usuário Multilíngüe instalado, a Ajuda será exibida no idioma padrão, e não no idioma do usuário local
  
#### Se os clientes do WSUS 2.0 tiverem atualizações com status Não Aplicável, elas serão exibidas como "Desconhecidas" depois da atualização para o WSUS 3.0
  
Se um servidor WSUS 2.0 tiver clientes com atualizações Não Aplicáveis, elas serão exibidas para ter o status Desconhecido por um período curto após a atualização do servidor para WSUS 3.0. O status de atualização voltará a Não Aplicável depois da próxima verificação do cliente.
  
Problemas conhecidos  
--------------------
  
#### solução de problemas de vários erros de download ou falhas repetidas de sincronização do cliente
  
Se os clientes do WSUS 3.0 relatarem vários erros de download ou se os clientes falharem na sincronização com o servidor do WSUS 3.0 por um longo período, pode haver um cache de download de cliente corrompido. Para se recuperar desse estado, tente excluir o cache de download do cliente do sistema de arquivos.
  
Para excluir o cache de download do cliente:
  
1.  Exclua todos os arquivos e subdiretórios deste local do computador cliente: **%windir%\\SoftwareDistribution\\Download**  
2.  Tente instalar a atualização sincronizando o computador cliente com o WSUS 3.0 novamente. A tentativa de instalação deve falhar com o seguinte erro: **WU\_E\_DM\_NOTDOWNLOADED, "A atualização não foi baixada."**  
3.  Após essa falha, o computador cliente reiniciará automaticamente o download e a instalação poderá prosseguir.
  
#### se a sincronização falhar, tente novamente
  
Se a sincronização falhar, sua primeira ação de solução do problema deve ser tentar sincronizar o servidor novamente. Caso haja falha nas sincronizações subseqüentes, use as informações de solução de problemas do [Windows Server Update Services 3.0 Operations Guide](http://go.microsoft.com/fwlink/?linkid=81072) (http://go.microsoft.com/fwlink/?LinkId=81072; o documento pode estar em inglês.)
  
#### não há suporte para a alteração da configuração do WSUS 3.0 diretamente no banco de dados
  
O Windows Server Update Services armazena seus dados de configuração em um banco de dados SQL Server. No entanto, não há suporte para a alteração dos dados de configuração pelo acesso direto ao banco de dados. Não tente modificar a configuração do WSUS 3.0 acessando o banco de dados diretamente. Você deve alterar a configuração do WSUS 3.0 usando o console do WSUS 3.0 ou chamando as APIs do WSUS 3.0.
  
#### falhas de download não são relatadas rapidamente se as cotas de disco estiverem ativadas
  
Se as cotas de disco estiverem ativadas e a cota for atingida, as falhas de download de atualização no servidor do WSUS podem não ser relatadas rapidamente. Para evitar esse problema, desative as cotas de disco ou aumente a cota.
  
#### Se o WSUS 3.0 for implantado usando SSL, os computadores cliente podem falhar com um código de erro 0x8024400a.
  
Os computadores cliente podem, às vezes, falhar com o código de erro "0x8024400a" ao se comunicarem com um servidor do WSUS 3.0 usando SSL. Para obter uma atualização que resolve esse problema, consulte [KB 905422](http://go.microsoft.com/fwlink/?linkid=70593) (http://go.microsoft.com/fwlink/?LinkId=70593; a página pode estar em inglês).
  
#### a conta de domínio Administradores do WSUS não será excluída quando o WSUS for desinstalado
  
O grupo Administradores do WSUS é criado como uma conta de domínio (não uma conta local) nos controladores do domínio, de forma que todas as instalações usando essa conta de domínio seriam desabilitadas se a conta fosse excluída quando o WSUS for desinstalado. Portanto, a desinstalação do WSUS não excluirá a conta de domínio Administradores do WSUS.
  
#### se um servidor downstream for convertido em um servidor upstream, as atualizações do site de catálogo deverão ser importadas novamente
  
Ao promover um servidor downstream para ser um servidor upstream, você também deve importar novamente todas as atualizações do site de catálogo. Caso contrário, o site não conseguirá sincronizar novas revisões de atualização do site de catálogo com esse servidor.
  
#### se você estiver usando o IIS com o SSL, o acesso não criptografado ainda será possível, a menos que a opção "Exigir Canal de Segurança" esteja selecionada
  
Se você tiver configurado o IIS para usar SSL pela instalação de um certificado, o acesso ao site via HTTP não criptografado ainda será possível, a menos que a opção "Exigir Canal de Segurança" esteja selecionada. Para obter mais informações, consulte as informações sobre [habilitação de criptografia](http://go.microsoft.com/fwlink/?linkid=70601) (http://go.microsoft.com/fwlink/?LinkId=70601; a página pode estar em inglês).
  
#### a importação do site de catálogo pode falhar sem as permissões de leitura/gravação para a pasta %windir%\\TEMP
  
Ao executar uma importação do site de catálogo, se a conta Serviço de Rede não tiver permissão de leitura/gravação para a pasta %windir%\\TEMP, a importação poderá falhar com uma mensagem de erro como a seguinte: "O servidor não pôde processar a solicitação. ---> Não foi possível localizar o arquivo 'C:\\WINDOWS\\TEMP\\*Nome\_do\_Arquivo\_temp*.dll'."
  
#### o desempenho pode estar lento durante a sincronização entre o WSUS 3.0 e o servidor downstream de réplica executando o WSUS 2.0
  
Se você instalar o WSUS 3.0 em um servidor upstream e tentar sincronizar com um servidor downstream de réplica executando o WSUS 2.0, poderá ter problemas de desempenho. Para resolver esse problema, consulte [KB 910847](http://go.microsoft.com/fwlink/?linkid=70669) (http://go.microsoft.com/fwlink/?LinkId=70669; a página pode estar em inglês).
  
#### se o servidor de email estiver inativo ou inacessível, a notificação por email falhará sem aviso
  
Se o servidor de email da rede estiver offline, o WSUS 3.0 falhará de forma silenciosa ao enviar notificações por email. No entanto, o evento 10052 (HealthCoreEmailNotificationRed) será gravado no log de eventos.
  
#### as configurações alteradas em um servidor upstream não são enviadas imediatamente ao servidor downstream
  
Quando a configuração do servidor upstream for alterada, pode levar algum tempo antes de essas alterações de configuração realmente serem efetivadas. Por exemplo, se você alterar uma configuração no servidor upstream, como selecionar um novo idioma, e disparar imediatamente uma sincronização no servidor downstream, a alteração não aparecerá. Em vez disso, ela será enviada ao servidor downstream na próxima sincronização agendada. O tempo de espera aumenta de acordo com o número de atualizações presentes no servidor upstream.
  
#### a desinstalação do WSUS 3.0 não desinstala a instância do banco de dados
  
Se o WSUS 3.0 for desinstalado, a instância do banco de dados não será desinstalada. A instância pode ser compartilhada por mais de um aplicativo e causará falhas em outros aplicativos se for removida.
  
Se for necessário desinstalar o Windows Internal Database, os comandos a seguir desinstalarão o aplicativo:
  
(em plataformas de 32 bits)
  
```  
msiexec /x {CEB5780F-1A70-44A9-850F-DE6C4F6AA8FB} callerid=ocsetup.exe  
```  
(em plataformas de 64 bits)
  
```  
msiexec /x {BDD79957-5801-4A2D-B09E-852E7FA64D01} callerid=ocsetup.exe  
```  
Se desejar desinstalar o Windows Internal Database Service Pack 2 do Windows Server 2008, você deverá fazer isso por meio do Gerenciador de Servidores.
  
No entanto, a remoção do aplicativo pode não remover os arquivos .mdf e .ldf padrão, o que fará com que uma instalação subseqüente do WSUS 3.0 falhe. Esses arquivos podem ser excluídos do diretório %windir%\\SYSMSI\\SSEE.
  
#### se um servidor downstream alterar seu servidor upstream, as atualizações com status "Desconhecido" serão relatadas como "Não Aplicáveis"
  
Se um servidor downstream começar a sincronizar a partir de um servidor upstream diferente, as atualizações com status "Desconhecido" serão relatadas no novo servidor upstream como "Não Aplicáveis". Esse estado é temporário e será corrigido na próxima vez em que o servidor downstream relatar seu status, após seus clientes terem sido sincronizados com ele.
  
#### se um servidor de réplica do WSUS 3.0 estiver gerenciando mais de um computador com o mesmo nome, o agrupamento de relatórios falhará
  
Se um servidor de réplica do WSUS 3.0 estiver gerenciando mais de um computador com o mesmo nome, o agrupamento de relatórios falhará. Como resultado, os relatórios disponíveis para o servidor raiz do WSUS estarão incompletos. Esse problema é resolvido excluindo-se todas as entradas de computador duplicadas, exceto uma, no servidor de réplica.
  
#### se o Assistente de Limpeza do Servidor tiver o tempo limite excedido em um servidor quando executado em vários servidores a partir de um console remoto, a conexão com todos os servidores será perdida
  
É possível executar o Assistente de Limpeza do Servidor em vários servidores a partir de um único console remoto. No entanto, se o processo de limpeza tiver o tempo limite excedido em um dos servidores, o console perderá sua conexão com todos os servidores. Nenhum dado será perdido, mas o administrador precisará redefinir a conexão remota com cada um dos servidores.
  
#### o Assistente de Limpeza do Servidor exclui arquivos após trinta dias, não após três meses
  
Parte do texto do Assistente de Limpeza do Servidor está incorreta. O texto diz: "Excluir atualizações expiradas e que não foram aprovadas por três meses e excluir revisões de atualizações antigas que não foram aprovadas por três meses". A quantidade de tempo correta é trinta dias, não três meses.
  
#### iniciar e parar a conexão em uma sucessão rápida gera uma mensagem de erro de "ausência de falha" no Assistente de Configuração
  
Ao configurar o WSUS, você é solicitado a se conectar ao servidor upstream (o Microsoft Update ou o servidor upstream da intranet) a fim de transferir informações básicas sobre o servidor. Se você clicar em **Iniciar Conexão** e, imediatamente, clicar em **Parar Conexão**, receberá a mensagem de erro incorreta “Não houve falha na sincronização”.
  
#### os clientes do WSUS com o Windows Vista RTM agora podem pesquisar atualizações no Microsoft Update
  
Em versões anteriores do WSUS, os clientes com o Windows Vista RTM podiam obter atualizações apenas a partir do servidor do WSUS. Agora, com o WSUS 3.0 RTM, os clientes do Vista também poderão obter atualizações a partir do Microsoft Update. Os clientes do Vista podem ser direcionados para o Microsoft Update abrindo o Windows Update a partir do Painel de Controle e clicando no hiperlink **Verificar online se há atualizações do Serviço Microsoft Update**. Se a opção de Diretiva de Grupo **Remover acesso ao uso de todos os recursos do Windows Update** estiver habilitada, o Windows Update não exibirá o hiperlink.
  
WSUS 3.0 no Windows Server 2008  
-------------------------------
  
#### Versões com suporte
  
O WSUS 3.0 dá suporte ao Windows Server 2008 nas versões de 32 e 64 bits.
  
#### Pré-requisitos
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Requisito</th>
<th style="border:1px solid black;" >Detalhes</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Serviços de Informações da Internet (IIS) da Microsoft</td>
<td style="border:1px solid black;">Instale a partir do sistema operacional. Verifique se os seguintes componentes estão habilitados:
Autenticação do Windows
Conteúdo estático
ASP.NET
Compatibilidade com Gerenciamento 6.0
Compatibilidade com metabase do IIS</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Pacote Redistribuível do Microsoft .NET Framework Versão 2.0 (x86)</td>
<td style="border:1px solid black;">Não é necessário no Windows Server 2008; já é instalado como parte do sistema operacional.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Console de Gerenciamento Microsoft 3.0</td>
<td style="border:1px solid black;">Não necessário no Windows Server 2008, já instalado como parte do sistema operacional.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">Esse é um pré-requisito para o uso da interface do usuário do WSUS. Consulte as informações sobre o Microsoft Report Viewer Redistributable 2005 no <a href="http://go.microsoft.com/fwlink/?linkid=70410">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70410).</td>
</tr>
</tbody>
</table>
  
#### Problema 1: o arquivo de configuração do IIS 7.0 deve ser atualizado antes da execução do WSUS 3.0
  
Antes de executar o WSUS 3.0 no Windows Server 2008, o arquivo de configuração do IIS deve ser atualizado. Siga estas etapas:
  
1. Abra o arquivo de configuração do IIS: %WINDIR%\\system32\\inetsrv\\applicationhost.config
  
2. Na marca <System.webServer><modules>, remova <add name="CustomErrorMode">, se existir.
  
3. Na marca <System.webServer><modules>, adicione <remove name="CustomErrorMode">.
  
A marca resultante deve se parecer com:
  
```  
    <System.webServer> <modules> <remove name="CustomErrorMode"> </modules> </System.webServer>  
```
  
#### Problema 2: Se você instalar o WSUS 3.0 na porta personalizada no Windows Server 2008 Beta 3, deverá pré-criar o site
  
Se você pretende instalar o WSUS 3.0 no Windows Server 2008 Beta 3 e deseja configurar o WSUS para usar a porta personalizada 8530, deverá criar um site denominado "Administração do WSUS" na porta 8530 antes de iniciar o programa de instalação do WSUS.
  
WSUS 3.0 no Windows Small Business Server 2003  
----------------------------------------------
  
#### Problema 1: se a raiz virtual do IIS estiver restrita a determinados endereços IP ou nomes de domínio, o servidor do WSUS 3.0 não poderá se atualizar
  
Algumas instalações do Windows Small Business Server podem ter o site do IIS padrão configurado para "Restrições de endereço IP e nome de domínio". Nesse caso, o Cliente do Windows Update no servidor talvez não seja capaz de fazer sua própria atualização.
  
#### Problema 2: instalando o WSUS 3.0 no Small Business Server — problemas de integração
  
-   Se o Windows Small Business Server 2003 usar um servidor proxy ISA para acessar a Internet, será preciso digitar o seguinte na interface de usuário **Configurações**: configurações do servidor proxy, nome do servidor proxy e porta.  
-   Se o ISA estiver usando a Autenticação do Windows, as credenciais do servidor proxy deverão ser digitadas na forma "DOMAIN\\user" e o usuário deverá ser um membro do grupo Usuários da Internet.
  
#### Problema 3: caso tenha adicionado uma sub-rede à rede sem usar os assistentes do Windows SBS, você deverá executar este procedimento
  
O processo de instalação do servidor do WSUS instala duas raízes virtuais do ISS no servidor: SelfUpdate e ClientWebService. A instalação também insere alguns arquivos sob o diretório base do site padrão (na porta 80) que habilita os computadores cliente à auto-atualização por meio do site padrão. Por padrão, o site padrão é configurado para recusar acesso a qualquer endereço IP diferente do host local ou de sub-redes específicas conectadas ao servidor. Como resultado, os computadores cliente que não estiverem no host local ou nessas sub-redes específicas não poderão executar a auto-atualização. Caso tenha adicionado uma sub-rede à rede sem usar os assistentes do Microsoft Windows Small Business Server 2003 (Windows SBS), você deverá executar este procedimento.
  
1.  Em Gerenciamento de Servidor, expanda **Gerenciamento Avançado**, **Serviços de Informações da Internet**, **Sites**, **Site Padrão**, clique com o botão direito do mouse no diretório virtual **Selfupdate** e clique em **Propriedades**.  
2.  Clique em **Segurança de Diretório**.  
3.  Em **Restrições de endereço IP e nome de domínio**, clique em **Editar** e em **Acesso Concedido**.  
4.  Clique em **OK**, clique com o botão direito do mouse no diretório virtual **ClientWebService** e clique em **Propriedades**.  
5.  Clique em **Segurança de Diretório**.  
6.  Em **Restrições de endereço IP e nome de domínio**, clique em **Editar** e em **Acesso Concedido**.
  
#### Direitos autorais
  
Este documento dá suporte a uma versão preliminar de um produto de software que pode ser alterado de forma substancial antes do lançamento comercial final e contém informações confidenciais e de propriedade da Microsoft Corporation. Ele é divulgado de acordo com um contrato de não divulgação entre o destinatário e a Microsoft. Este documento é fornecido somente para fins informativos e a Microsoft não faz nenhuma garantia, expressa ou implícita, neste documento. As informações deste documento, inclusive URLs e outras referências a sites da Internet, estão sujeitas a alteração sem aviso prévio. Todo e qualquer risco relacionado ao uso ou aos resultados do uso deste documento são do usuário. A menos que observado de outra forma, as empresas, as organizações, os produtos, os nomes de domínios, os endereços de email, os logotipos, as pessoas, os locais e os eventos apresentados em exemplos neste documento são fictícios. Nenhuma associação a uma empresa, uma organização, um produto, um nome de domínio, um endereço de email, um logotipo, uma pessoa, um local ou um evento real é proposital ou deve ser inferida. Obedecer a todas as leis de direitos autorais aplicáveis é responsabilidade do usuário. Sem limitar os direitos autorais, nenhuma parte deste documento pode ser reproduzida, armazenada ou introduzida em um sistema de recuperação ou transmitida de qualquer forma ou por qualquer meio (eletrônico, mecânico, fotocópia, gravação ou qualquer outro), ou para qualquer propósito, sem a permissão expressa, por escrito, da Microsoft Corporation.
  
A Microsoft pode ter patentes ou requisições para obtenção de patentes, marcas comerciais, direitos autorais ou outros direitos de propriedade intelectual que abrangem o conteúdo deste documento. A posse deste documento não lhe confere nenhum direito sobre as citadas patentes, marcas comerciais, direitos autorais ou outros direitos de propriedade intelectual, salvo aqueles expressamente mencionados em um contrato de licença, por escrito, da Microsoft.
  
© 2007 Microsoft Corporation. Todos os direitos reservados.
  
Microsoft, SQL Server, Windows e Windows Server são marcas registradas ou comerciais da Microsoft Corporation nos Estados Unidos e/ou em outros países.
  
Todas as outras marcas comerciais pertencem a seus respectivos proprietários.
