---
TOCTitle: 'Notas de versão do Microsoft Windows Server Update Services 3.0 SP1'
Title: 'Notas de versão do Microsoft Windows Server Update Services 3.0 SP1'
ms:assetid: 'a5aa93bf-842b-4ad4-ab0f-fe867843cb02'
ms:contentKeyID: 18139339
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708525(v=WS.10)'
---

Notas de versão do Microsoft Windows Server Update Services 3.0 SP1
===================================================================

Estas notas de versão descrevem problemas conhecidos que ocorrem no Microsoft® Windows® Server Update Services (WSUS) 3.0 Service Pack 1 e incluem recomendações e requisitos para instalação do aplicativo. As seguintes seções são apresentadas:

-   Requisitos de sistema para instalação do servidor WSUS 3.0 SP1
-   Requisitos de configuração para instalação do servidor WSUS 3.0 SP1
-   Requisitos de sistema para instalação do console remoto do WSUS 3.0 SP1
-   Requisitos de sistema para instalação do cliente
-   Requisitos de software para instalação do servidor WSUS SP1
-   Requisitos mínimos de espaço em disco para instalação do servidor WSUS 3.0 SP1
-   Requisitos de atualização do WSUS 3.0 SP1
-   Parâmetros de linha de comando de configuração
-   Problemas de configuração
-   Problemas de atualização
-   Problemas conhecidos
-   WSUS 3.0 SP1 no Windows Server® 2008
-   WSUS 3.0 SP1 no Windows Small Business Server 2003

Requisitos de sistema para instalação do servidor WSUS 3.0 SP1
--------------------------------------------------------------

#### O Windows Server 2008 e o Windows Server 2003 Service Pack 1 fornecem suporte ao servidor WSUS 3.0 SP1

O Windows Server 2008 e o Windows Server 2003 Service Pack 1 oferecem suporte ao servidor WSUS 3.0 SP1.

#### Os servidores WSUS 3.0 SP1 não fornecem suporte ao Windows 2000 Server

O Microsoft Windows® 2000 não é um sistema operacional suportado para servidores WSUS 3.0 SP1.

#### WSUS 3.0 SP1 não é suportado em servidores executando Serviços de Terminal

Embora o WSUS 3.0 SP1 ainda possa rodar em servidores executando Serviços de Terminal, isso não é suportado nem recomendado. O WSUS 3.0 SP1 não será executado em um servidor com os Serviços de Terminal em configurações que utilizem implementações de SQL Server remoto. Como todas as ações personalizadas remotas (incluindo instalação) em um servidor de licença de Serviços de Terminal serão executadas como a conta do sistema, e a conta do sistema do servidor talvez não tenha permissões no SQL Server remoto, a instalação poderá falhar.

Requisitos de configuração para instalação do servidor WSUS 3.0 SP1
-------------------------------------------------------------------

#### O IIS deve ser instalado

O WSUS 3.0 SP1 exige o IIS (Serviços de Informações da Internet), que não é instalado por padrão no Windows Server 2008 ou no Microsoft Windows Server 2003. Se você tentar instalar o WSUS 3.0 SP1 sem o IIS, a instalação do Windows Server Update Services exibirá uma mensagem de erro informando que o IIS não está instalado.

#### Se o IIS estiver sendo executado no modo de isolamento do IIS 5.0, a instalação falhará

Se você atualizou o servidor do Windows 2000 Server para o Windows Server 2003, o IIS pode estar sendo executado no modo de compatibilidade do IIS 5.0. Também é possível habilitar o modo de isolamento do IIS 5.0 no Gerenciador do IIS. Isso provocará falha da instalação. Será necessário desabilitar o modo de isolamento antes de instalar o WSUS 3.0 SP1.

#### Se qualquer componente do IIS for instalado no modo de compatibilidade de 32 bits em uma plataforma de 64 bits, a instalação do WSUS 3.0 SP1 poderá falhar

Todos os componentes do IIS devem ser instalados no modo nativo em plataformas de 64 bits. A instalação pode falhar se algum componente do IIS estiver no modo de compatibilidade de 32 bits.

#### Servidores proxy fornecem suporte a HTTP somente, ou HTTP e HTTPS

No WSUS 3.0 SP1, o servidor proxy pode fornecer suporte somente a HTTP. Você deve configurar um segundo servidor proxy que execute HTTPS por meio da linha de comando (**wsusutil configuresslproxy**) antes de configurar o servidor WSUS no Assistente de Configuração ou no Console de administração.

#### Se dois ou mais sites da Web já estiverem sendo executados na porta 80, exclua todos menos um antes da instalação do WSUS

Se houver dois ou mais sites da Web sendo executados na porta 80 (por exemplo, Windows® SharePoint® Services), você deverá excluir todos menos um antes da instalação do WSUS. Se você não fizer isso, os clientes do servidor poderão falhar na auto-atualização.

#### Ao instalar o WSUS 3.0 SP1, você pode precisar desabilitar programas antivírus

Ao instalar o WSUS 3.0 SP1, você pode precisar desabilitar programas antivírus para poder executar a instalação com êxito. Após desabilitar o programa antivírus, reinicie o computador antes da instalação do WSUS. Reiniciar o computador evita o bloqueio de arquivos quando o processo de instalação precisar acessá-los. Depois de concluída a instalação, assegure-se de reabilitar o programa antivírus. Visite o site da Web do fornecedor do programa antivírus para obter as etapas exatas para desabilitar e reabilitar sua versão de programa antivírus.

> [!CAUTION]  
> Essa solução temporária pode tornar o computador ou a rede mais vulnerável a ataques de usuários ou softwares mal-intencionados, como vírus. Não recomendamos essa solução temporária, mas fornecemos esta informação para que você possa implementá-la a seu próprio critério. Use essa solução temporária por sua própria conta e risco. 

> [!NOTE]  
> Um programa antivírus é projetado para ajudar a proteger o computador contra vírus. Você não deve baixar nem abrir arquivos de fontes não confiáveis, visitar sites da Web em que você não confie ou abrir anexos de email quando seu programa antivírus estiver desabilitado. 

#### O WSUS 3.0 SP1 requer que a opção de disparadores aninhados esteja ativada no SQL Server

A opção de disparadores aninhados é ativada por padrão; entretanto, ela pode ser desativada por um administrador do SQL Server.

Se você planeja usar um banco de dados do SQL Server como o armazenamento de dados do Windows Server Update Services, o administrador do SQL Server deve verificar se a opção de disparadores aninhados no servidor está ativada antes que o administrador do WSUS 3.0 SP1 instale o WSUS 3.0 SP1 e especifique o banco de dados durante a instalação.

A instalação do WSUS 3.0 SP1 ativa a opção RECURSIVE\_TRIGGERS, que é específica do banco de dados; entretanto, ela não ativa a opção de disparadores aninhados, que é global do servidor.

Para verificar se a opção de disparadores aninhados está ativada, use o seguinte:

**sp\_configure 'nested triggers'**

Para ativar a opção de disparadores aninhados no servidor do SQL, execute o seguinte em um arquivo de lote no computador que executa o SQL Server:

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

Se não houver SQL Server Management Studio no servidor, você talvez deseje executar os scripts SQL na linha de comando. É possível obter o Microsoft SQL Server 2005 Command Line Query Utility no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=70728) (http://go.microsoft.com/fwlink/?LinkId=70728). Para iniciar, execute **sqlcmd**.

Se desejar executar scripts SQL no Windows Internal Database, também será necessário baixar o SQL Server Native Client na mesma página de download.

#### Limitações e requisitos de SQL remoto

O WSUS 3.0 SP1 oferece suporte para execução de software de banco de dados em um computador separado do que contém o restante do aplicativo WSUS 3.0 SP1. Existem alguns requisitos para a configuração de uma instalação de SQL remoto:

-   Você não pode usar um servidor configurado como um controlador de domínio para o back-end do par de SQL remoto.
-   O Servidor de Terminal não deve estar sendo executado no computador que será o servidor front-end de uma instalação de SQL remoto.
-   Você deve usar no mínimo o Microsoft SQL Server 2005 Service Pack 1 (disponível no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=66143) (http://go.microsoft.com/fwlink/?LinkId=66143) para software de banco de dados no computador back-end, se este estiver executando o Windows Server 2003 e o SQL Server 2005 Service Pack 2, se o computador back-end estiver executando o Windows Server® 2008.
-   Ambos os computadores, front-end e back-end, devem ser acrescentados a um domínio do Active Directory; caso contrário, se estiverem em domínios diferentes, você deverá estabelecer uma confiança entre os domínios antes de executar a configuração do WSUS.
-   Se já tiver o WSUS 2.0 instalado em uma configuração de SQL remoto e desejar atualizar para o WSUS 3.0 SP1, você deverá desinstalar o WSUS 2.0 (utilizando **Adicionar ou remover programas** no Painel de Controle) do computador back-end assegurando-se de que o banco de dados existente permaneça intacto. Em seguida, você deverá instalar o SQL Server 2005 SP1 ou SP2 e atualizar o banco de dados existente. Para concluir, instale o WSUS 3.0 SP1 no computador front-end.

Requisitos de sistema para instalação do console remoto do WSUS 3.0 SP1
-----------------------------------------------------------------------

O console remoto do WSUS 3.0 SP1 pode ser instalado nas seguintes plataformas:

-   Windows Server 2008
-   Windows Vista® ou posterior
-   Windows Server 2003 SP1 ou posterior
-   Windows XP SP2 ou posterior

Requisitos de sistema para instalação do cliente
------------------------------------------------

Atualizações Automáticas é o software cliente do WSUS. Pode ser usado com o WSUS em qualquer um dos seguintes sistemas operacionais:

-   Windows Vista ou posterior
-   Windows Server 2008 ou posterior
-   Microsoft Windows Server 2003, qualquer edição
-   Microsoft Windows XP Professional SP2 ou posterior
-   Microsoft Windows 2000 Professional SP4, Windows 2000 Server SP4 ou Windows 2000 Advanced Server com SP4

Requisitos de software para instalação do servidor WSUS 3.0 SP1
---------------------------------------------------------------

A tabela a seguir mostra o software necessário para plataformas Windows Server 2003 SP1. O software necessário para o Windows Server 2008 será mencionado na seção sobre o WSUS 3.0 SP1 no Windows Server 2008.

Verifique se o servidor WSUS 3.0 SP1 atende a esta lista de requisitos antes de executar a configuração do WSUS 3.0 SP1. Se alguma dessas atualizações exigir a reinicialização do computador na conclusão da instalação, você deverá executar a reinicialização antes de instalar o WSUS 3.0 SP1.

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
<td style="border:1px solid black;">Instala do sistema operacional.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Pacote Redistribuível do Microsoft .NET Framework Versão 2.0</td>
<td style="border:1px solid black;">Veja o Pacote Redistribuível (x86) do Microsoft .NET Framework Versão 2.0 no <a href="http://go.microsoft.com/fwlink/?linkid=68935">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=68935). Para plataformas de 64 bits, veja o Pacote Redistribuível (x64) do Microsoft .NET Framework Versão 2.0 no <a href="http://go.microsoft.com/fwlink/?linkid=70637">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70637).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Management Console 3.0 para Windows Server 2003</td>
<td style="border:1px solid black;">Este é um pré-requisito para utilização da interface do usuário do WSUS 3.0 SP1. Veja o Microsoft Management Console 3.0 para Windows Server 2003 (KB907265) no <a href="http://go.microsoft.com/fwlink/?linkid=70412">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70412). Para plataformas de 64 bits, veja o Microsoft Management Console 3.0 para Windows Server 2003 x64 Edition (KB907265) no <a href="http://go.microsoft.com/fwlink/?linkid=70638">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70638).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">Este é um pré-requisito para utilização da interface do usuário do WSUS 3.0 SP1. Veja o Microsoft Report Viewer Redistributable 2005 no <a href="http://go.microsoft.com/fwlink/?linkid=70410">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70410).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005 (opcional)</td>
<td style="border:1px solid black;">O WSUS 3.0 SP1 instalará o Windows Internal Database para você se uma versão compatível do SQL Server ainda não estiver instalada. Se planeja usar um banco de dados completo do SQL Server, você deve usar (no mínimo) o SQL Server 2005 SP1 (disponível no <a href="http://go.microsoft.com/fwlink/?linkid=66143">Centro de Download da Microsoft</a> em http://go.microsoft.com/fwlink/?LinkId=66143) no Windows Server 2003, ou o SQL Server 2005 SP2 (disponível no <a href="http://go.microsoft.com/fwlink/?linkid=84823">Centro de Download da Microsoft</a> em http://go.microsoft.com/fwlink/?LinkId=84823) no Windows Server 2008.</td>
</tr>
</tbody>
</table>
  
> [!NOTE]  
> Se o WSUS 2.0 tiver sido instalado anteriormente e estiver utilizando o SQL Server 2000, SQL Server Desktop Engine 2000 ou qualquer banco de dados do SQL Server anterior ao SQL Server 2005 SP1 (ou SQL Server 2005 SP2 no Windows Server 2008), o programa de instalação do WSUS 3.0 SP1 instalará o Windows® Internal Database e migrará o banco de dados para ele. 
  
Requisitos mínimos de espaço em disco para instalação do servidor WSUS 3.0 SP1  
------------------------------------------------------------------------------
  
A seguir são apresentados os requisitos mínimos de espaço em disco para instalação do Windows Server Update Services:
  
-   1 GB na partição do sistema  
-   2 GB para o volume no qual os arquivos do banco de dados serão armazenados  
-   20 GB para o volume no qual o conteúdo será armazenado
  
> [!Important] 
> O WSUS 3.0 SP1 não pode ser instalado em unidades compactadas. Verifique se a unidade escolhida não está compactada. 
  
Requisitos de atualização do WSUS 3.0 SP1  
-----------------------------------------
  
#### Verifique se sua instalação do WSUS está executando corretamente e faça o backup do banco de dados do WSUS antes da atualização
  
Se estiver atualizando de uma versão anterior para o WSUS 3.0 SP1, verifique se sua instalação atual está executando corretamente e faça o backup do banco de dados do WSUS antes da atualização.
  
1.  Verifique se há erros recentes nos logs de evento, problemas de sincronização entre servidores downstream e upstream ou problemas de clientes sem comunicação. Verifique se esses problemas foram resolvidos antes de continuar.  
2.  Você pode querer executar o DBCC CHECKDB para garantir que o banco de dados do WSUS seja corretamente indexado. Para obter mais informações sobre o DBCC CHECKDB, consulte [DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948) (http://go.microsoft.com/fwlink/?LinkId=86948).  
3.  Faça backup do banco de dados do WSUS.
  
#### Se tiver modificado manualmente a porta usada pelo WSUS, desinstale antes da atualização
  
Ao modificar a porta do WSUS, use sempre o utilitário wsusutil em vez de tentar modificar a porta manualmente. Se você modificou a porta manualmente e atualizou anteriormente do Software Update Services 1.0 para o WSUS 2.0:
  
1.  Se ainda não instalou o WSUS 3.0, desinstale o WSUS 2.0, mantendo o banco de dados e o conteúdo. (Se já instalou o WSUS 3.0, desinstale-o, mantendo o banco de dados e o conteúdo.)  
2.  Inicie o site da Web padrão, reabilitando temporariamente o SUS 1.0, mas tornando-o acessível ao desinstalador.  
3.  Desinstale o SUS 1.0.  
4.  Instale o WSUS 3.0.
  
#### O Software Update Services 1.0 deve ser desinstalado
  
A instalação do WSUS 3.0 SP1 falhará se o Software Update Services 1.0 estiver instalado na mesma máquina. É necessário desinstalar o Software Update Server 1.0 antes de instalar o WSUS 3.0 SP1.
  
#### Não é possível atualizar do WSUS 2.0 para o WSUS 3.0 SP1 em um sistema operacional de 64 bits
  
Sistemas operacionais de 64 bits não fornecem suporte ao WSUS 2.0. Não é possível atualizar do WSUS 2.0 para o WSUS 3.0 SP1 em sistemas operacionais de 64 bits.
  
Parâmetros de linha de comando de configuração  
----------------------------------------------
  
É possível executar instalações autônomas do WSUS 3.0 SP1 utilizando o programa de configuração de linha de comando do WSUS. Esta tabela apresenta os parâmetros de linha de comando para configuração do WSUS 3.0 SP1.
  
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
<td style="border:1px solid black;">Executa a instalação silenciosa.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/u</strong></td>
<td style="border:1px solid black;">Desinstala o produto. Desinstala também a instância do Windows Internal Database, se estiver instalada.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">Somente verificação de pré-requisito. Não desinstala o produto, mas inspeciona o sistema e relata qualquer pré-requisito que esteja faltando.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">Exibe os parâmetros da linha de comando e suas descrições.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">Atualiza da versão anterior do WSUS. (Não tente atualizar do SUS 1.0.) O único parâmetro válido com esta opção é /q (instalação silenciosa). A única propriedade válida com esta opção é DEFAULT_WEBSITE.</td>
</tr>
</tbody>
</table>
  
Esta tabela apresenta as propriedades de linha de comando para o WSUS 3.0 SP1.
  
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
<td style="border:1px solid black;">0=conteúdo hospedado localmente, 1=hospedado no Microsoft Update</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CONTENT_DIR</td>
<td style="border:1px solid black;">Caminho do diretório de conteúdo. O padrão é <em>UnidadedeinstalaçãodoWSUS</em><strong>\WSUS\WSUSContent</strong>, onde <em>UnidadedeinstalaçãodoWSUS</em> é a unidade local com a maior quantidade de espaço livre.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Caminho do diretório de dados do Windows Internal Database.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQLINSTANCE_NAME</td>
<td style="border:1px solid black;">O nome deve ser exibido no formato <em>NomeDoServidor</em>\<em>NomeDaInstânciaSQL</em>. Se a instância do banco de dados estiver na máquina local, use a variável de ambiente %COMPUTERNAME%. Se uma instância existente não estiver presente, o padrão é %COMPUTERNAME%\WSUS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DEFAULT_WEBSITE</td>
<td style="border:1px solid black;">0=porta 8530, 1=porta 80</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PREREQ_CHECK_LOG</td>
<td style="border:1px solid black;">Caminho e nome de arquivo do arquivo de log</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CONSOLE_INSTALL</td>
<td style="border:1px solid black;">0=instala o servidor WSUS, 1=instala somente o console</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ENABLE_INVENTORY</td>
<td style="border:1px solid black;">0=não instala recursos de inventário, 1=instala recursos de inventário</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_DATABASE</td>
<td style="border:1px solid black;">0=mantém o banco de dados, 1=remove o banco de dados</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DELETE_CONTENT</td>
<td style="border:1px solid black;">0=mantém arquivos de conteúdo, 1=remove arquivos de conteúdo</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_LOGS</td>
<td style="border:1px solid black;">0=mantém arquivos de log, 1=remove arquivos de log (usado com a opção de instalação /u).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=usa o banco de dados atual, 1=cria o banco de dados</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">Manuseio de janela para retornar mensagens de progresso do MSI</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=entra no Programa de Aperfeiçoamento do Microsoft Update, 0=não entra no Programa de Aperfeiçoamento do Microsoft Update</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=não grava o local do conteúdo no banco de dados, 0=grava o local do conteúdo no banco de dados (para NLB)</td>
</tr>
</tbody>
</table>
  
#### Exemplo de uso
  
```  
    WSUSSetup.exe /q DEFAULT\_WEBSITE=0 (install in quiet mode using port 8530) WSUSSetup.exe /q /u (uninstall WSUS)  
```  
> [!IMPORTANT]  
> Se você instalar o WSUS 3.0 SP1 no modo silencioso (/q) e a máquina não tiver todos os pré-requisitos instalados, a instalação irá gerar um arquivo denominado WSUSPreReqCheck.xml e salvá-lo no diretório %TEMP%. |
  
Problemas de configuração  
-------------------------
  
#### Os IIS serão reiniciados durante a configuração do WSUS 3.0 SP1
  
A Configuração do WSUS 3.0 SP1 reiniciará os IIS sem notificação, o que poderia afetar sites da Web existentes em sua organização. Se os IIS não estiverem sendo executados, a configuração do WSUS 3.0 SP1 os iniciará.
  
#### Se forem abertas conexões para um banco de dados existente do WSUS, a instalação poderá falhar
  
Se estiver atualizando para o WSUS 3.0 SP1 de uma instalação existente e ainda estiverem abertas conexões para o banco de dados existente do WSUS (por exemplo, se o SQL Server Management Studio estiver aberto), a instalação poderá falhar. Feche todas as conexões e reinstale o WSUS 3.0 SP1.
  
#### A configuração do WSUS mostra o diretório errado de arquivos do banco de dados
  
Na configuração do WSUS, a tela **Ready to Install** (Pronto para Instalar) informa incorretamente que o local do banco de dados é o diretório pai do local do banco de dados. Por exemplo, o local padrão é %unidadedosistema%\\WSUS\\UpdateServicesDbFiles, mas este local aparece incorretamente como %unidadedosistema%\\WSUS.
  
#### Se o WSUS estiver instalado em uma máquina que possua pacotes de idioma MUI (Interface do Usuário Multilíngüe) com um idioma padrão diferente de inglês, a Ajuda será exibida no idioma padrão em vez de em inglês
  
Se tiver uma máquina que possua pacotes de idioma MUI (Interface do Usuário Multilíngüe) com um idioma padrão diferente de inglês, você ainda será capaz de instalar o WSUS quando a localidade do usuário atual for inglês. A IU será exibida em inglês, mas você deve usar uma solução temporária para que a Ajuda seja exibida em inglês. Copie o arquivo .chm da Ajuda em inglês (*DiretóriodeinstalaçãodoWSUS*\\documentation\\mui\\0409\\WSUS30Help.chm) para o diretório de documentação principal (*DiretóriodeinstalaçãodoWSUS*\\documentation\\WSUS30Help.chm). Neste ponto, a Ajuda deve ser exibida corretamente em todos os idiomas.
  
Problemas de atualização  
------------------------
  
#### Recuperação de uma atualização que falhou
  
Se estiver atualizando de uma versão anterior do WSUS (WSUS 3.0, WSUS 2.0 SP1 ou WSUS 2.0) para o WSUS 3.0 SP e a atualização falhar por qualquer motivo:
  
1.  Reinstale a versão anterior do WSUS.  
2.  Restaure o banco de dados do backup realizado antes da tentativa de atualização. (Na maioria dos casos, o WSUS também cria um backup automaticamente. Consulte o arquivo WSUSSetup.log para obter o local.)  
3.  Analise os logs para determinar a causa da falha e corrija o problema.  
4.  Tente novamente a atualização do WSUS.
  
#### Não é possível atualizar do WSUS 2.0 para o WSUS 3.0 SP1 se houver um banco de dados do WSUS 3.0 SP1 de uma instalação anterior
  
Se tiver instalado o WSUS 3.0 SP1 anteriormente e então reinstalou o WSUS 2.0, você deve excluir o banco de dados do WSUS 3.0 SP1 da máquina antes de tentar reinstalar o WSUS 3.0 SP1.
  
#### Modificar o nome do computador antes de atualizar para o WSUS 3.0 SP1 pode provocar falha da atualização
  
Se você modificar o nome do computador após a instalação do WSUS 2.0 e antes de atualizar para o WSUS 3.0 SP1, a atualização poderá falhar.
  
Use o script a seguir para remover e readicionar os grupos de administradores ASPNET e WSUS. Em seguida execute novamente a atualização.
  
Será necessário substituir *<DBLocation>* pela pasta onde o banco de dados está instalado e *<ContentDirectory>* pela pasta de armazenamento local.
  
```  
    sqlcmd.exe -S *<DBLocation>* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=name from sysusers WHERE name like '%ASPNET' EXEC sp\_revokedbaccess @asplogin" sqlcmd.exe -S *<DBLocation>* -E -Q "USE  SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=name from sysusers WHERE name like '%WSUS Administrators' EXEC sp\_revokedbaccess @wsusadminslogin"   sqlcmd.exe -S *<DBLocation>* -E -Q "USE SUSDB  DECLARE @asplogin varchar(200) SELECT @asplogin=HOST\_NAME()+'\\ASPNET' EXEC sp\_grantlogin @asplogin EXEC sp\_grantdbaccess @asplogin EXEC sp\_addrolemember webService,@asplogin" sqlcmd.exe -S *<DBLocation>* -E -Q "USE  SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=HOST\_NAME()+'\\WSUS Administrators' EXEC sp\_grantlogin @wsusadminslogin EXEC sp\_grantdbaccess @wsusadminslogin EXEC sp\_addrolemember webService,  @wsusadminslogin"   sqlcmd.exe -S *<DBLocation>* -E -Q "backup database SUSDB to disk=N'*<ContentDirectory>*\\SUSDB.Dat' with init"  
```
  
#### A configuração substituirá um backup de banco de dados anterior
  
A configuração do WSUS 3.0 SP1 adicionará o banco de dados ao diretório padrão, que é *unidade*\\WSUS (onde *unidade* é a unidade NTFS local que possua maior quantidade de espaço livre). Se houver um backup de banco de dados neste diretório, ele poderá ser substituído. Os administradores devem salvar um backup de banco de dados da versão atual em um local diferente antes da atualização para o WSUS 3.0 SP1.
  
#### Se tiver migrado do MSDE para o SQL Server 2000 ou SQL Server 2005 no WSUS 2.0, você precisará modificar um valor de registro
  
Se você tiver uma instalação do WSUS 2.0, e tiver migrado para o SQL Server 2000 ou SQL Server 2005, será necessário modificar o valor **HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** de 1 para 0. Se não fizer isso antes da atualização para o WSUS 3.0 SP1, a atualização falhará.
  
#### Se a configuração do WSUS 2.0 for iniciada e cancelada, ela excluirá a chave de registro do WSUS
  
Se você iniciar a configuração do WSUS 2.0 e, em seguida, cancelar, a chave de registro do WSUS será excluída. Isso pode causar problemas se você já tiver o WSUS 3.0 SP1 instalado. O mesmo problema ocorrerá se você iniciar a desinstalação do WSUS 2.0 e, em seguida, cancelar a operação, então tentar atualizar do WSUS 2.0 para o WSUS 3.0 SP1.
  
#### Se desinstalar o WSUS 3.0 SP1 e deixar os arquivos de log, eles podem não ter as permissões corretas após a reinstalação
  
Ao desinstalar o WSUS 3.0 SP1, você tem a opção de manter os arquivos de log da instalação. Ao reinstalar o WSUS 3.0 SP1, os arquivos de log antigos perdem suas permissões (geralmente para administradores do WSUS apenas) Você deve restaurar as permissões desses arquivos de log.
  
#### Se clientes do WSUS 2.0 tiverem atualizações com o status "Not Applicable" (Não aplicável), as atualizações aparecerão como "Unknown" (Desconhecido) por um curto período após a atualização para o WSUS 3.0 SP1
  
Se um servidor WSUS 2.0 tiver clientes com atualizações **Not Applicable** (Não aplicável), essas atualizações parecerão ter o status **Unknown** (Desconhecido) por um curto período após o servidor ser atualizado para o WSUS 3.0 SP1 O status da atualização retornará para **Not Applicable** (Não aplicável) após a próxima vez que o cliente fizer uma verificação.
  
Problemas conhecidos  
--------------------
  
#### Solução de problemas de vários erros de download ou repetidas falhas de sincronização do cliente
  
Se os clientes do WSUS 3.0 SP1 relatarem vários erros de download ou se falharem ao sincronizar com o servidor WSUS 3.0 SP1 por um longo período de tempo, você pode ter um cache de download do cliente corrompido. Para recuperar deste estado, é possível tentar excluir o cache de download do cliente no sistema de arquivos.
  
Para excluir o cache de download do cliente:
  
1.  Apague todos os arquivos e subdiretórios no seguinte local no computador cliente: **%windir%\\SoftwareDistribution\\Download**  
2.  Tente instalar a atualização sincronizando novamente o computador cliente com o WSUS 3.0 SP1. Esta tentativa de instalação deve falhar com o seguinte erro: **WU\_E\_DM\_NOTDOWNLOADED, "The update has not been downloaded." (A atualização não foi descarregada.)**  
3.  Após essa falha, o computador cliente reiniciará o download automaticamente e a instalação poderá prosseguir.
  
#### Se a sincronização falhar, tente novamente
  
Se a sincronização falhar, o primeiro item da ação de solução de problemas deve ser tentar sincronizar o servidor novamente. Se as sincronizações subseqüentes falharem, use as informações de solução de problemas apresentadas no [Windows Server Update Services 3.0 Operations Guide (Guia de Operações do Windows Server Update Services 3.0)](http://go.microsoft.com/fwlink/?linkid=81072) em http://go.microsoft.com/fwlink/?LinkId=81072.
  
#### Não há suporte para a alteração da configuração do WSUS 3.0 SP1 diretamente no banco de dados
  
O Windows Server Update Services armazena seus dados de configuração em um banco de dados do SQL Server. Entretanto, a alteração de dados da configuração acessando o banco de dados diretamente não é suportada. Não tente modificar a configuração do WSUS 3.0 SP1 acessando diretamente o banco de dados. Você deve alterar a configuração do WSUS 3.0 SP1 utilizando o console do WSUS 3.0 SP1 ou chamando APIs do WSUS 3.0 SP1.
  
#### Falhas de download não são rapidamente informadas se cotas de disco estiverem ativadas
  
Se cotas de disco estiverem ativada e a cota for atingida, falhas de download de atualização no servidor WSUS podem não ser informadas no momento oportuno. Para evitar esse problema, desative as cotas de disco ou aumente a cota.
  
#### Se o WSUS 3.0 SP1 for implantado utilizando SSL, computadores clientes podem falhar com um código de erro 0x8024400a
  
Algumas vezes, computadores clientes podem falhar com um código de erro 0x8024400a ao comunicarem-se com um servidor WSUS 3.0 SP1 utilizando SSL. Para obter uma atualização que lide com este problema, consulte [KB 905422](http://go.microsoft.com/fwlink/?linkid=70593) (http://go.microsoft.com/fwlink/?LinkId=70593).
  
#### A conta de domínio de administradores do WSUS não será excluída quando o WSUS for desinstalado
  
O grupo de administradores do WSUS é criado como uma conta de domínio (não uma conta local) em controladores de domínio, assim, todas as instalações utilizando essa conta de domínio podem ser desabilitadas se a conta for excluída quando o WSUS for desinstalado. Portanto, a desinstalação do WSUS não excluirá a conta de domínio de Administradores do WSUS.
  
#### Se um servidor downstream for convertido para um servidor upstream, as atualizações de site de catálogo devem ser reimportadas
  
Quando você promove um servidor downstream para ser um servidor upstream, deve também reimportar todas as atualizações de site de catálogo. Caso contrário, o site falhará na sincronização de novas revisões de atualização de site de catálogo neste servidor.
  
#### Se estiver utilizando IIS com SSL, o acesso não criptografado ainda será possível a menos que a opção "Require Secure Channel" (Requer canal protegido) esteja marcada
  
Se configurar os IIS para usarem SSL instalando um certificado, ainda será possível acessar o site através de HTTP não criptografado a menos que a opção **Require Secure Channel** (Requer canal protegido) esteja marcada. Para obter mais informações, consulte a documentação do [IIS](http://go.microsoft.com/fwlink/?linkid=98084) (http://go.microsoft.com/fwlink/?LinkId=98084).
  
#### A importação de site de catálogo pode falhar sem permissões de leitura/gravação para a pasta %windir%\\TEMP
  
Ao executar uma importação de site de catálogo, se a conta Serviços de Rede não tiver permissão de leitura/gravação para a pasta %windir%\\TEMP, a importação poderá falhar com uma mensagem de erro como a seguinte: O servidor não pôde processar a solicitação. ---> Não foi possível encontrar o arquivo "C:\\WINDOWS\\TEMP\\*tempFileName*.dll".
  
#### O desempenho pode ficar lento na sincronização entre o WSUS 3.0 SP1 e um servidor de réplica downstream executando o WSUS 2.0
  
Se você instalar o WSUS 3.0 SP1 em um servidor upstream e tentar sincronizar com um servidor de réplica downstream executando o WSUS 2.0, pode experimentar problemas de desempenho. Para resolver este problema, consulte [KB 910847](http://go.microsoft.com/fwlink/?linkid=70669) (http://go.microsoft.com/fwlink/?LinkId=70669).
  
#### Se o servidor de email ficar inativo ou inacessível, a notificação de email falhará sem aviso
  
Se o servidor de email da rede ficar off-line, o WSUS 3.0 SP1 falhará silenciosamente em enviar notificações de email. Contudo, ele gravará o evento 10052 (HealthCoreEmailNotificationRed) no log de evento.
  
#### Configurações modificadas em um servidor upstream não são recuperadas imediatamente para o servidor downstream
  
Quando a configuração do servidor upstream é modificada, pode levar algum tempo antes dessas modificações de configuração realmente se tornarem efetivas. Por exemplo, se você alterar uma configuração em um servidor upstream tal como selecionar um novo idioma e, imediatamente, acionar uma sincronização no servidor downstream, a modificação não aparecerá. Em vez disso, ela será recuperada para o servidor downstream na próxima sincronização programada. O tempo de espera aumenta conforme o número de atualizações presentes no servidor upstream.
  
#### A desinstalação do WSUS 3.0 SP1 não desinstala a instância de banco de dados
  
Se o WSUS 3.0 SP1 for desinstalado, a instância de banco de dados não será desinstalada. A instância pode estar compartilhada por mais de um aplicativo, e fará com que outros aplicativos falhem se for removida.
  
Se for necessário desinstalar o Windows Internal Database, os seguintes comandos desinstalarão o aplicativo:
  
(em plataformas de 32 bits)
  
```  
msiexec /x {CEB5780F-1A70-44A9-850F-DE6C4F6AA8FB} callerid=ocsetup.exe  
```  
(em plataformas de 64 bits)
  
```  
msiexec /x {BDD79957-5801-4A2D-B09E-852E7FA64D01} callerid=ocsetup.exe  
```  
Se quiser desinstalar o Windows Internal Database Service Pack 2 do Windows Server 2008, pode fazer isso utilizando o Gerenciador de Servidor.
  
Entretanto, a remoção do aplicativo pode não remover os arquivos .mdf e .ldf padrão, o que causará uma subseqüente falha da instalação do WSUS 3.0 SP1. Esses arquivos podem ser excluídos no diretório %windir%\\SYSMSI\\SSEE.
  
#### Se um servidor downstream mudar seu servidor upstream, as atualizações de status "Unknown" (Desconhecido) serão relatadas como "Not Applicable" (Não aplicável)
  
Se um servidor downstream começar a sincronizar em um servidor upstream diferente, as atualizações que tiverem um status de **Unknown** (Desconhecido) serão relatadas no novo servidor upstream como **Not Applicable** (Não aplicável). Esse estado é temporário e será corrigido na próxima vez que o servidor downstream relatar seu status, após seus clientes terem sincronizado com ele.
  
#### Se o Assistente de Limpeza do Servidor atingir o tempo limite em um servidor ao executar em vários servidores de um console remoto, a conexão a todos os servidores será perdida
  
É possível executar o Assistente de Limpeza do Servidor em vários servidores de um único console remoto. Entretanto, se o processo de limpeza atingir o tempo limite em um dos servidores, o console perderá sua conexão com todos os servidores. Nenhum dado será perdido, mas o administrador precisará redefinir a conexão remota com cada um dos servidores.
  
#### Iniciar e interromper a conexão em uma sucessão rápida causa a mensagem de erro "There was no synchronization failure" (Não houve falha na sincronização) no Assistente de Configuração
  
Ao configurar o WSUS, você é solicitado a conectar ao servidor upstream (Microsoft Update ou o servidor upstream de intranet) para transferir informações básicas sobre o servidor. Se clicar em **Start Connecting** (Iniciar conexão) e, imediatamente, clicar em **Stop Connecting** (Interromper conexão), você receberá a mensagem de erro incorreta “There was no synchronization failure” (Não houve falha na sincronização).
  
WSUS 3.0 SP1 no Windows Server 2008  
-----------------------------------
  
#### Versões aceitas
  
As versões de 32 e 64 bits do Windows Server 2008 oferecem suporte ao WSUS 3.0 SP1.
  
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
<td style="border:1px solid black;">Instala do sistema operacional. Assegure-se de que os seguintes componentes estejam habilitados:
<ul>
<li>Autenticação do Windows<br />
<br />
</li>
<li>Conteúdo Estático<br />
<br />
</li>
<li>ASP.NET<br />
<br />
</li>
<li>Compatibilidade de Gerenciamento do IIS 6.0<br />
<br />
</li>
<li>Compatibilidade da Metabase do IIS 6.0<br />
<br />
</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Pacote Redistribuível (x86) do Microsoft .NET Framework Versão 2.0</td>
<td style="border:1px solid black;">Não é necessário no Windows Server 2008; já instalado como parte do sistema operacional.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Console de Gerenciamento Microsoft 3.0</td>
<td style="border:1px solid black;">Não é necessário no Windows Server 2008; já instalado como parte do sistema operacional.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">Este é um pré-requisito para utilização da interface do usuário do WSUS. Veja o Microsoft Report Viewer Redistributable 2005 no <a href="http://go.microsoft.com/fwlink/?linkid=70410">Centro de Download da Microsoft</a> (http://go.microsoft.com/fwlink/?LinkId=70410).</td>
</tr>
</tbody>
</table>
  
#### Usando o Assistente de Configuração de Segurança
  
No Windows Server 2008, quando o Assistente de Configuração de Segurança for executado (ACS), você poderá selecionar a função WSUS e habilitar suas dependências. Para executar o ACS, clique em **Iniciar**, aponte para **Ferramentas administrativas** e clique em **Assistente de Configuração de Segurança**.
  
Os problemas conhecidos a seguir ocorrem devido à utilização conjunta do ACS e da função WSUS:
  
-   **O serviço Windows Internal Database é habilitado mesmo se não for usado pelo WSUS.** Configure o WSUS para usar um banco de dados — o Windows Internal Database ou o SQL Server. Se WSUS for instalado com o SQL Server e você selecionar a função WSUS no ACS, o serviço Windows Internal Database será habilitado se estiver instalado no computador, mas não será usado pelo WSUS. Você terá que desabilitar o serviço Windows Internal Database se estiver usando um banco de dados SQL Server em vez do Windows Internal Database.  
-   **As regras de firewall para o WSUS em um site personalizado não são selecionadas por padrão.** Se você instalar o WSUS em um site personalizado (porta 8530 ou 8531), as regras de firewall exigidas não serão automaticamente selecionadas, mesmo se você selecionar a função WSUS no ACS. É necessário habilitar as regras de firewall apropriadas para o WSUS, considerando se o Secure Sockets Layer (SSL) está configurado para o servidor WSUS.
  
WSUS 3.0 SP1 no Windows Small Business Server 2003  
--------------------------------------------------
  
#### Se a raiz virtual do IIS for restrita para determinados endereços IP ou nomes de domínio, o servidor WSUS 3.0 SP1 não será capaz de se atualizar sozinho
  
Algumas instalações do Windows Small Business Server podem ter o site da Web dos IIS padrão configurado para **Restrições de endereços IP e nomes de domínio**. Nesse caso, o Windows Update Client no servidor pode não conseguir se atualizar sozinho.
  
#### Instalação do WSUS 3.0 SP1 no Small Business Server—Problemas de integração
  
-   Se o Windows Small Business Server 2003 usar um servidor proxy ISA para acessar a Internet, as seguintes informações devem ser digitadas na interface do usuário em **Configurações**: **configurações do servidor proxy, nome do servidor proxy, porta**.  
-   Se o ISA estiver usando uma Autenticação do Windows, as credenciais de servidor proxy devem ser digitadas na forma *DOMÍNIO*\\*usuário* e o usuário dever ser um membro do grupo de Usuários de Internet.
  
#### Se você tiver adicionado uma sub-rede a sua rede sem utilizar os assistentes do Windows SBS, o seguinte procedimento deve ser executado
  
O processo de configuração de servidor do WSUS instala dois IIS vroots no servidor: SelfUpdate e ClientWebService. A configuração também coloca alguns arquivos no diretório inicial do site da Web padrão (na porta 80), que permite aos computadores clientes se auto-atualizarem através do site da Web padrão. Por padrão, o site da Web padrão é configurado para negar o acesso a qualquer endereço IP diferente do host local ou especificar sub-redes conectadas ao servidor. Como resultado, computadores clientes que não estejam no host local ou nessas sub-redes específicas não podem se auto-atualizar. Se você tiver adicionado uma sub-rede a sua rede sem utilizar os assistentes do Microsoft Windows Small Business Server 2003 (Windows SBS), o seguinte procedimento deve ser executado:
  
1.  Em Server Management (Gerenciamento de servidor), expanda **Advanced Management** (Gerenciamento avançado), expanda **Internet Information Services** (Serviços de Informações da Internet), expanda **Web Sites** (Sites da Web), expanda **Default Web Site** (Site da Web padrão), clique com o botão direito no diretório virtual **Selfupdate** (Auto-atualizar) e, em seguida, clique em **Properties** (Propriedades).  
2.  Clique em **Directory Security** (Segurança de diretório).  
3.  Em **IP address and domain name restrictions** (Restrições de endereços IP e nomes de domínio), clique em **Edit** (Editar) e, em seguida, em **Granted Access** (Acesso concedido).  
4.  Clique em **OK**, clique com o botão direito do mouse no diretório virtual **ClientWebService** e clique em **Properties** (Propriedades).  
5.  Clique em **Directory Security** (Segurança de diretório).  
6.  Em **IP address and domain name restrictions** (Restrições de endereços IP e nomes de domínio), clique em **Edit** (Editar) e, em seguida, em **Granted Access** (Acesso concedido).
  
Copyright  
---------
  
As informações contidas neste documento, incluindo URL e outras referências a sites da Internet, estão sujeitas a alterações sem aviso prévio. A menos que seja mencionado o contrário, empresas, organizações, produtos, nomes de domínio, endereços de email, logotipos, pessoas, lugares e eventos representados nos exemplos aqui contidos são fictícios. Nenhuma associação com qualquer empresa, organização, produto, nome de domínio, endereço de email, logotipo, pessoa, lugar ou evento é intencional nem deve ser pressuposta como real. A obediência a todas as leis de direitos autorais aplicáveis é responsabilidade do usuário. Sem limitar os direitos autorais, nenhuma parte deste documento pode ser reproduzida, armazenada ou introduzida em sistemas de recuperação, nem transmitida em qualquer forma ou por qualquer meio (eletrônico, mecânico, fotocópia, gravação ou qualquer outro), ou para qualquer propósito sem a permissão expressa por escrito da Microsoft Corporation.
  
A Microsoft pode possuir patentes, patentes pendentes, marcas comerciais, direitos autorais ou outros direitos de propriedade intelectual cujo escopo abranja o conteúdo deste documento. Exceto conforme expressamente determinado em qualquer contrato de licença da Microsoft, o fornecimento deste documento não implica a concessão de qualquer licença para tais patentes, marcas comerciais, direitos autorais ou outra propriedade intelectual.
  
© 2007 Microsoft Corporation. Todos os direitos reservados.
  
Microsoft, SQL Server, Windows e Windows Server são marcas registradas ou comerciais da Microsoft Corporation nos Estados Unidos e/ou em outros países.
  
Todas as outras marcas registradas são de propriedade de seus respectivos proprietários.
