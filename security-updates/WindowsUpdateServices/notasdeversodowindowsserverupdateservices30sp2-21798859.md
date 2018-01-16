---
TOCTitle: 'Notas de Versão do Windows Server Update Services 3.0 SP2'
Title: 'Notas de Versão do Windows Server Update Services 3.0 SP2'
ms:assetid: 'b3723422-489d-47b7-abfa-663353647da0'
ms:contentKeyID: 21798859
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Dd939886(v=WS.10)'
---

Notas de Versão do Windows Server Update Services 3.0 SP2
=========================================================

Estas notas de versão descrevem a versão Windows Server Update Services 3.0 Service Pack 2 (WSUS 3.0 SP2). Este documento contém as seguintes seções:

1.  Novidades Nesta Versão
2.  Requisitos de Sistema da Instalação do Servidor do WSUS 3.0 SP2
3.  Pré-requisitos de Configuração e Práticas Recomendadas para o Servidor do WSUS
4.  Pré-requisitos do Windows Small Business Server
5.  Requisitos de Sistema da Instalação do Console Remoto do WSUS 3.0 SP2
6.  Requisitos de Sistema para a Instalação do Cliente
7.  Requisitos e Recomendações de Atualização
8.  Como Instalar o WSUS 3.0 SP2
9.  Parâmetros de Linha de Comando de Instalação para Instalações Autônomas do WSUS 3.0 SP2
10. Problemas Conhecidos

Novidades Nesta Versão
----------------------

-   Integração com o Windows Server 2008 R2
-   Suporte para o recurso BranchCache no Windows Server 2008 R2.
-   Suporte para os clientes do Windows 7.
-   Melhorias para o cliente do Windows Update Agent (WUA). O novo cliente do WUA oferece um conjunto de melhorias de desempenho, aprimoramentos de experiência do usuário e mais uma variedade de correções de erros baseados nos comentários dos clientes.
    -   O tempo de verificação do cliente é mais rápido do que em versões anteriores.
    -   Os computadores gerenciados por servidores WSUS podem executar verificações com escopo naqueles mesmos servidores WSUS em vez de realizar uma verificação completa. Isso resultará em verificações muito mais rápidas dos aplicativos que usam os APIs do Microsoft Update como o Windows Defender.
    -   Os aprimoramentos de experiência do usuário do Windows Update Agent (WUA) ajudam os usuários a organizar melhor as atualizações e oferecem maior claridade no valor e comportamento da atualização.
    -   Máquinas com imagens serão exibidas mais claramente no console WSUS. Para obter mais informações, consulte o artigo com o título [Um computador baseado no Windows 2000, Windows Server 2003 ou Windows XP que foi configurado para uso de uma imagem do Windows 2000, Windows Server 2003 ou Windows XP não aparece no console WSUS](http://go.microsoft.com/fwlink/?linkid=159749).
-   Novos recursos:
    -   As regras de aprovação automática agora incluem a capacidade de especificar a data e a hora do prazo final de aprovação de todos os computadores ou de grupos de computadores específicos.
    -   A manipulação aprimorada da seleção de idioma nos servidores downstream inclui um novo diálogo de aviso que é exibido quando você decide baixar atualizações somente para idiomas especificados.
    -   Os novos relatórios Atualização e Status do Computador permitem que você filtre atualizações aprovadas para instalação. É possível executar esses relatórios do console WSUS ou usar a API (Interface de Programação de Aplicativo) para incorporar essa funcionalidade em seus próprios relatórios.
-   A interface do usuário é compatível entre o Service Pack 1 e o Service Pack 2 do WSUS 3.0 no cliente e no servidor.
-   Atualizações do software.
-   Problemas conhecidos com o Windows Update Agent que foram resolvidos nessa versão:
    1.  O WSUS 3.0 SP2 e o Windows 7 incluem uma nova versão do Windows Update Agent (para Windows XP, Windows Vista, Windows Server 2000, Windows Server 2003 e Windows Server 2008). Essa versão corrige o seguinte problema: APIs chamadas por chamadores de sistema não-local em uma sessão não-interativa falharão.
    2.  O problema foi corrigido pela versão 7.2.6001.788 do Windows Update Agent. Essa atualização corrige o seguinte problema: Ao tentar instalar 80 ou mais atualizações ao mesmo tempo da página da Web do Windows Update ou da página da Web do Microsoft Update, você poderá receber o código de erro 0x80070057.
    3.  Aprimoramentos e problemas que foram corrigidos pela versão 7.2.6001.784 do Windows Update Agent. Essa atualização corrige o seguinte problema: Aprimora o tempo de verificação do Windows Update, aprimora a velocidade na qual as atualizações de assinatura são entregues, habilita o suporte para a funcionalidade de reinstalação do Windows Installer e aprimora as mensagens de erro.

<span id="BKMK_SysReqWSUS30SP2"></span>
Requisitos de Sistema da Instalação do Servidor do WSUS 3.0 SP2
---------------------------------------------------------------

Essa seção descreve os requisitos de software e hardware necessários para a instalação do WSUS 3.0 SP2.

### Pré-requisitos de Software do Servidor do WSUS

-   É necessário ter um dos seguintes sistemas operacionais com suporte instalados:
    -   Windows Server 2008 R2
    -   Windows Server 2008 SP1 ou versões mais recentes
 
        > [!WARNING]
        > Se o WSUS 3.0 SP2 estiver instalado no Windows Server 2008 antes de atualizar para Windows Server 2008 R2, a atualização para Windows Server 2008 R2 falhará. Consulte a seção <a href="#bkmk_knownissues">Problemas conhecidos</a> para obter mais informações.
        
    -   Windows Server 2003 SP1 ou versões mais recentes
    -   Windows Small Business Server 2008
    -   Windows Small Business Server 2003

    Observe que pré-requisitos adicionais se aplicam ao Windows Small Business Server. Consulte a seção "Pré-requisitos do Windows Small Business Server" para obter mais informações.
-   IIS (Serviços de Informações da Internet) 6.0 ou versões mais recentes
-   O Microsoft .NET Framework 2.0 ou versões mais recentes
-   É necessário ter um dos seguintes bancos de dados com suporte instalados:
    -   Microsoft SQL Server 2008 Standard ou Enterprise Edition
    -   Microsoft SQL Server 2005 SP3 ou versões mais recentes
    -   Banco de Dados Interno do Windows

    Se nenhuma das versões com suporte do SQL Server estiver instalada, o Assistente de Instalação do WSUS 3.0 SP2 instalará o Banco de Dados Interno do Windows.
-   Console de Gerenciamento Microsoft 3.0
-   Microsoft Report Viewer Redistributable 2008

> [!IMPORTANT]  
> O Windows Server 2008 R2 exige o WSUS 3.0 SP2. Se você instalar o Windows Server 2008 R2, deverá instalar o WSUS 3.0 SP2. Não instale o WSUS 3.0 SP1 no Windows Server 2008 R2.

### Pré-requisitos de Software do Console de Administração do WSUS

-   Um dos seguintes sistemas operacionais com suporte: Windows Server 2008 R2, Windows Server 2008, Windows Server 2003 SP2 ou versões mais recentes, Windows Small Business Server 2008 ou 2003, Windows Vista ou Windows XP SP2
-   Microsoft .NET Framework 2.0 ou versões mais recentes
-   Console de Gerenciamento Microsoft 3.0
-   Microsoft Report Viewer Redistributable 2008

### Requisitos Mínimos de Hardware do Servidor do WSUS

A seguinte lista contém requisitos mínimos de hardware necessários para uma instalação básica de servidor. Consulte o Guia de Implantação do WSUS 3.0 SP2 no site [http://go.microsoft.com/fwlink/?LinkId=139832](http://go.microsoft.com/fwlink/?linkid=139832) para uma lista abrangente de configurações de hardware com suporte.

-   Tanto a partição do sistema quanto a partição em que você instalar o WSUS 3.0 SP2 devem ser formatadas com o sistema de arquivos NTFS.
-   Mínimo de 1 GB de espaço livre na partição de sistema.
-   Mínimo de 2 GB de espaço livre no volume no qual os arquivos de banco de dados serão armazenados.
-   Mínimo de 20 GB de espaço livre necessários no volume no qual o conteúdo está armazenado, 30 GB são recomendados.

 
Pré-requisitos de Configuração e Práticas Recomendadas para o Servidor do WSUS
------------------------------------------------------------------------------

Certifique-se de ter concluído as tarefas aplicáveis nesta seção antes de instalar o WSUS 3.0 SP2.

### IIS

-   Na página do Gerenciador de Servidores em Serviços de Função do Servidor Web (IIS), instale todos os recursos necessários e os serviços de função do IIS padrão, como também os seguintes serviços de função: **ASP.NET**, **Autenticação do Windows**, **Compactação de Conteúdo Dinâmico**, e **Compatibilidade de Gerenciamento do IIS 6**.
-   Se o IIS estiver sendo executado no modo de isolamento do IIS 5.0, a instalação falhará. Desabilite o modo de isolamento do IIS 5.0 antes de instalar o WSUS 3.0 SP2.
-   Se algum componente do IIS for instalado no modo de compatibilidade de 32 bits em uma plataforma de 64 bits, a instalação do WSUS 3.0 SP2 poderá falhar. Todos os componentes do IIS devem ser instalados no modo nativo em plataformas de 64 bits.

### Servidores Proxy

O WSUS 3.0 SP2 permite que um servidor proxy ofereça suporte somente a HTTP. Como melhor prática, configure um segundo servidor proxy que execute HTTPS usando a linha de comando (**wsusutil configuresslproxy**) antes de configurar o servidor do WSUS do Assistente de Configuração ou do Console de Administração.

### Sites Executados na Porta 80

Se você tiver dois ou mais sites executados na porta 80 (por exemplo, o Windows SharePoint Services), exclua todos, exceto um deles, antes de instalar o WSUS. Se você não fizer isso, os clientes do servidor podem falhar na autoatualização.

### Programas Antivírus

Ao instalar o WSUS 3.0 SP2, talvez seja necessário desabilitar programas antivírus antes de poder executar a instalação com êxito. Depois de desabilitar o software antivírus, reinicie o computador antes de instalar o WSUS. Reiniciar o computador evita que os arquivos sejam bloqueados quando o processo de instalação precisa acessá-los. Depois que a instalação for concluída, certifique-se de reabilitar seu software antivírus. Visite o site do fornecedor de software antivírus para obter as etapas exatas para desabilitar e reabilitar o software e a versão antivírus.

> [!Caution]
> Essa solução alternativa pode tornar o computador ou a rede mais vulnerável a ataques de usuários ou softwares mal-intencionados, como vírus. Não recomendamos essa solução alternativa, mas fornecemos essas informações para que você possa implementá-la se desejar. Use essa solução alternativa por sua conta e risco. O software antivírus ajuda a proteger o computador contra vírus. Não baixe nem abra arquivos de fontes não confiáveis, não visite sites da Web não confiáveis nem abra anexos de email quando seu programa antivírus estiver desabilitado.

### Opção de Gatilhos Aninhados no SQL Server

Se você planeja usar um banco de dados do SQL Server como o armazenamento de dados do Windows Server Update Services, o administrador do SQL Server deverá verificar se a opção de gatilhos aninhados está ativada no servidor antes que o administrador do WSUS instale o WSUS 3.0 SP2. A opção de gatilhos aninhados é ativada por padrão; no entanto, ela pode ser desativada pelo administrador do SQL Server. A instalação do WSUS 3.0 SP2 ativa a opção RECURSIVE\_TRIGGERS, que é específica do banco de dados. No entanto, ela não ativa a opção de gatilhos aninhados, que é global do servidor.

### Limitações e Requisitos de SQL Remoto

O WSUS 3.0 SP2 oferece suporte à execução de uma versão compatível do software SQL Server em um computador separado do computador no qual o aplicativo WSUS 3.0 SP2 esteja em execução. Os requisitos a seguir se aplicam a uma instalação remota do SQL.

-   Não é possível usar um servidor configurado como um controlador de domínio para o back-end do par de SQL remoto.
-   Não é possível executar os serviços de terminal no computador que será o servidor front-end de uma instalação remota de SQL.
-   Os computadores front-end e back-end devem ser unidos a um domínio do Active Directory. Se os computadores front-end e back-end estiverem em domínios diferentes, estabeleça uma confiança entre os domínios antes de executar a Instalação do WSUS.
-   Se o WSUS 2.0 já estiver instalado em uma configuração remota do SQL e você desejar atualizá-lo para o WSUS 3.0 SP2, você deverá executar o seguinte procedimento antes de instalar o WSUS:
    1.  Desinstale o WSUS 2.0 (usando **Adicionar ou Remover Programas** no Painel de Controle) e certifique-se de que o banco de dados existente permaneça intacto.
    2.  Instale o SQL Server 2005 SP2 ou o SQL Server 2008 e atualize o banco de dados existente.

### O IIS será reiniciado durante a Instalação do WSUS 3.0 SP2

A instalação do WSUS 3.0 SP2 reiniciará o IIS sem notificação, o que pode afetar sites existentes em sua organização. Como prática recomendada, notifique antecipadamente as partes envolvidas sobre essa instalação. Certifique-se de que se o IIS não estiver em execução, a instalação do WSUS 3.0 SP2 o iniciará durante a instalação.

Pré-requisitos do Windows Small Business Server
-----------------------------------------------

Se você estiver instalando o WSUS 3.0 SP2 em um Windows Small Business Server, os pré-requisitos a seguir se aplicarão.

### Se a Raiz Virtual do IIS for Restrita a Determinados Endereços IP ou Nomes de Domínio

Algumas instalações do Windows Small Business Server podem ter o site do IIS padrão configurado para **Restrições de endereços IP e nomes de domínio**. Se esse for o caso, o Cliente do Windows Update no servidor poderá não conseguir se atualizar. Remova a restrição antes de instalar o WSUS 3.0 SP2.

### Se Você Estiver Usando Um Servidor Proxy ISA

-   Se o Windows Small Business Server usar um servidor proxy ISA para acessar a Internet, digite **configurações do servidor proxy, nome do servidor proxy, porta** na interface de usuário **Configurações**.
-   Se o ISA estiver usando uma Autenticação do Windows, digite as credenciais de servidor proxy na forma *DOMÍNIO*\\*usuário*. O usuário dever ser um membro do grupo de Usuários da Internet.

### Se Você Tiver Adicionado uma Sub-rede à sua Rede e Não Tiver Usado os Assistentes do Windows Small Business Server

O processo de instalação do servidor do WSUS instala dois vroots do ISS no servidor: SelfUpdate e ClientWebService. A instalação também coloca alguns arquivos no diretório raiz do site padrão (na porta 80), que permite aos computadores cliente se autoatualizarem por meio do site padrão. Por padrão, o site padrão é configurado para negar o acesso a qualquer endereço IP diferente do host local ou a sub-redes específicas conectadas ao servidor. Portanto, computadores cliente que não estiverem no host local ou nessas sub-redes específicas não podem se autoatualizar. Se você tiver adicionado uma sub-rede à rede sem usar os assistentes do Microsoft Windows Small Business Server, execute este procedimento:

1.  Em Gerenciamento de Servidor, expanda **Gerenciamento Avançado**, **Serviços de Informações da Internet**, **Sites**, **Site Padrão**, clique com o botão direito do mouse no diretório virtual **Selfupdate** e clique em **Propriedades**.
2.  Clique em **Segurança de Diretório**.
3.  Em **Restrições de endereço IP e nome de domínio**, clique em **Editar** e em **Acesso Concedido**.
4.  Clique em **OK**, clique com o botão direito do mouse no diretório virtual **ClientWebService** e clique em **Propriedades**.
5.  Clique em **Segurança de Diretório**.
6.  Em **Restrições de endereço IP e nome de domínio**, clique em **Editar** e em **Acesso Concedido**.

Requisitos de Sistema da Instalação do Console Remoto do WSUS 3.0 SP2
---------------------------------------------------------------------

O Console Remoto do WSUS 3.0 SP2 pode ser instalado em qualquer um dos seguintes sistemas operacionais:

-   Windows Server 2008 R2, Windows Server 2008 SP1 ou versões mais recentes, Windows Server 2003 SP2 ou versões mais recentes, Windows Small Business Server 2003, 2005 ou 2008, Windows Vista ou Windows XP Professional SP3 ou versões mais recentes.

Requisitos de Sistema da Instalação do Cliente WSUS
---------------------------------------------------

Atualizações Automáticas, o software cliente do WSUS, pode ser instalado em qualquer um dos seguintes sistemas operacionais:

-   Windows Server 2008 R2, Windows Server 2008 SP1 ou versões mais recentes, Windows Server 2003 SP2 ou versões mais recentes, Windows Small Business Server 2003, 2005 ou 2008, Windows Vista, Windows XP Professional RTM, Windows XP Professional SP1, Windows XP Professional SP2, Windows XP Professional SP3 ou versões mais recentes, Windows 2000 SP4, ou cliente do Windows 7.

Requisitos e Recomendações de Atualização
-----------------------------------------

As seguintes versões do WSUS podem ser atualizadas para o WSUS 3.0 SP2 e não exigem a desinstalação da versão anterior:

-   WSUS 2.0, 2.0 SP1, 3.0 e 3.0 SP1.

Não há suporte para as atualizações da versão WSU 1.0 para a versão WSU 3.0 SP2. Desinstale o SUS (Software Update Services) 1.0 antes de instalar o WSUS 3.0 SP2.

O Windows Server 2008 R2 exige o WSUS 3.0 SP2. Se instalar o Windows Server 2008 R2, você deverá instalar o WSUS 3.0 SP2. Não instale o WSUS 3.0 SP1 no Windows Server 2008 R2.

#### Antes de atualizar para o WSUS 3.0 SP2

1.  Verifique se há erros recentes nos logs de evento, problemas de sincronização entre servidores downstream e upstream ou problemas relatórios de cliente. Resolva esses problemas antes da atualização.

2.  Como opção, é possível executar o DBCC CHECKDB para verificar se o banco de dados do WSUS está corretamente indexado. Para obter mais informações sobre DBCC CHECKDB, consulte [DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948).

3.  Faça backup do banco de dados do WSUS. Observe que a instalação do WSUS 3.0 SP2 não adicionará o novo banco de dados ao diretório padrão, que é *unidade*\\WSUS (*unidade* é a unidade NTFS local que tiver a maior quantidade de espaço livre). Se já houver um backup de banco de dados nesse diretório, ele poderá ser substituído. Como melhor prática, salve um backup de banco de dados da versão atual do WSUS em um local diferente antes de atualizar para o WSUS 3.0 SP2.

4.  Se você tiver alterado manualmente a porta usada pelo WSUS (ou seja, se não tiver usado o utilitário Wsusutil) e estiver executando atualmente o SUS 1.0 ou o WSUS 2.0, inicie o site antes de desinstalar o SUS 1.0 ou o WSUS 2.0 de 64 bits.

5.  Se as conexões estiverem abertas para um banco de dados do WSUS existente (por exemplo, se o SQL Server Management Studio estiver aberto), a instalação poderá falhar. Feche todas as conexões antes de instalar o WSUS 3.0 SP2.

### Como Recuperar de uma Atualização que Falhou

Se você estiver atualizando de uma versão anterior do WSUS para o WSUS 3.0 SP2 e a atualização falhar (por qualquer motivo que não o de tentar uma atualização sem suporte do SUS 1.0), execute as tarefas a seguir.

1.  Reinstale a versão anterior do WSUS.
2.  Restaure o banco de dados do backup feito antes de tentar atualizar. Não é possível concluir com êxito uma atualização se houver um banco de dados do WSUS 3.0 SP2 existente de uma instalação anterior. Na maioria dos casos, o WSUS também cria um backup automaticamente. Consulte o arquivo WSUSSetup.log para obter o local.
3.  Analise os logs para determinar a causa da falha e resolva o problema.
4.  Instale o WSUS 3.0 SP2.

### Modificar o nome do computador antes de atualizar para o WSUS 3.0 SP2 pode provocar falha da atualização

Se você alterar o nome do computador depois da instalação do WSUS 2.0 e antes de atualizar para o WSUS 3.0 SP2, a atualização poderá falhar.

Use o script a seguir para remover e adicionar novamente os grupos Administradores do ASPNET e do WSUS. Em seguida, execute a atualização novamente.

### Se você tiver migrado do MSDE para o SQL Server 2008 ou SQL Server 2005 no WSUS 2.0, será necessário modificar um valor do Registro

Se você tiver uma instalação do WSUS 2.0, e tiver migrado para o SQL Server 2008 ou SQL Server 2005, será necessário modificar o valor **HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** de 1 para 0. Se não fizer isso antes da atualização para o WSUS 3.0 SP2, a atualização falhará.

### Se você desinstalar o WSUS 3.0 SP2 e deixar os arquivos de log, eles podem não ter as permissões adequadas após a reinstalação

Se desinstalar o WSUS 3.0 SP2, você terá a opção de manter os arquivos de log da instalação. Ao reinstalar o WSUS 3.0 SP2, os arquivos de log antigos poderão perder suas permissões (geralmente somente para Administradores do WSUS). Como prática recomendada, confirme as permissões nesses arquivos de log depois da instalação.

### Se clientes do WSUS 2.0 tiverem atualizações com o status "Não aplicável", as atualizações serão exibidas como "Desconhecido" por um curto período após a atualização para o WSUS 3.0 SP2

Se um servidor do WSUS 2.0 existente tiver clientes que têm atualizações do tipo **Não Aplicável**, essas atualizações poderão ser listadas com um status **Desconhecido** por um curto período depois de atualizar para o WSUS 3.0 SP2. O status da atualização retornará para **Não Aplicável** depois da próxima vez que o cliente fizer uma verificação.

Como Instalar o WSUS 3.0 SP2
----------------------------

O Guia de Instalação Passo a Passo do WSUS, em [http://go.microsoft.com/fwlink/?LinkId=139836](http://go.microsoft.com/fwlink/?linkid=139836), oferece instruções para instalar o WSUS 3.0 SP2 usando o Windows Server Manager ou o arquivo WUSSetup.exe.

Para obter informações completas sobre como instalar e usar o WSUS, consulte:

O Guia de Implantação do WSUS, em [http://go.microsoft.com/fwlink/?LinkId=139832](http://go.microsoft.com/fwlink/?linkid=139832).

O Guia de operações do WSUS, em [http://go.microsoft.com/fwlink/?LinkId=139838](http://go.microsoft.com/fwlink/?linkid=139838).

Parâmetros de Linha de Comando da Instalação para Instações Autônomas do WSUS 3.0 SP2
-------------------------------------------------------------------------------------

É possível executar instalações autônomas do WSUS 3.0 SP2 usando o programa de configuração de linha de comando do WSUS. Esta tabela mostra os parâmetros de linha de comando da instalação do WSUS 3.0 SP2.

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
<td style="border:1px solid black;">Desinstala.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">Verificação de pré-requisito. Inspeciona o sistema e relata qualquer pré-requisito ausente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">Exibe os parâmetros da linha de comando e suas descrições.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">Atualiza da versão anterior do WSUS. (Não há suporte para atualizações do SUS 1.0). O único parâmetro válido com essa opção é /q (instalação silenciosa). A única propriedade válida com essa opção é DEFAULT_WEBSITE.</td>
</tr>
</tbody>
</table>
  
Esta tabela mostra as propriedades de linha de comando do WSUS 3.0 SP2.
  
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
<td style="border:1px solid black;">O caminho para o diretório de conteúdo. O padrão é <em>UnidadedeinstalaçãodoWSUS\WSUS\ConteúdodoWSUS</em>, onde <em>UnidadedeinstalaçãodoWSUS</em> é a unidade local com a maior quantidade de espaço livre.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Caminho do diretório de dados do Windows Internal Database.</td>
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
<td style="border:1px solid black;">Caminho e nome de arquivo do arquivo de log</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CONSOLE_INSTALL</td>
<td style="border:1px solid black;">0=instalar o servidor do WSUS, 1=instalar somente o console</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ENABLE_INVENTORY</td>
<td style="border:1px solid black;">0=não instalar os recursos de inventário, 1=instalar os recursos de inventário</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_DATABASE</td>
<td style="border:1px solid black;">0=mantér o banco de dados, 1=remover o banco de dados</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DELETE_CONTENT</td>
<td style="border:1px solid black;">0=mantér os arquivos de conteúdo, 1=remover os arquivos de conteúdo</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_LOGS</td>
<td style="border:1px solid black;">0=mantér os arquivos de log, 1=remover os arquivos de log (usado com a opção de instalação /u).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=usar banco de dados atual, 1=criar banco de dados</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">Identificador da janela para retornar mensagens de progresso do Windows Installer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=entrar no Programa de Aperfeiçoamento do Microsoft Update, 0=não entrar no Programa de Aperfeiçoamento do Microsoft Update</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=não gravar o local do conteúdo no banco de dados, 0=gravar o local do conteúdo no banco de dados (para NLB)</td>
</tr>
</tbody>
</table>
  
### Exemplo de Uso
  
```  
    WSUSSetup.exe /q DEFAULT\_WEBSITE=0 (instala em modo silencioso usando a porta 8530) WSUSSetup.exe /q /u (desinstala o WSUS)  
```

Problemas Conhecidos
--------------------

-   Depois da conclusão com êxito do Assistente de Instalação do WSUS, o usuário é orientado a clicar em **Concluir**.  
Em casos raros, uma caixa de diálogo de erro é exibida contendo a seguinte mensagem: "**Ocorreu um erro de comunicação com o servidor e este assistente deve ser fechado. Você pode reiniciar o Assistente de Configuração do Servidor do WSUS da página Opções no console do WSUS.**" Para certificar-se de que suas seleções de instalação foram salvas, abra a página **Opções** no console de administração do WSUS e confirme as configurações em cada seção.
-   **Versões localizadas de cliente do Windows Update Agent (WUA) serão lançadas após o lançamento do WSUS 3.0 SP2**.  
    Isso é devido a uma dependência da agenda de localização do Windows 7. Durante o período entre o lançamento do WSUS 3.0 SP2 e o lançamento da versão localizada de cliente do WUA, esse último terá suporte para apenas cinco idiomas (inglês, alemão, francês, espanhol e japonês).
-   **Os novos relatórios Atualização e Status do Computador que foram apresentados nessa versão do SP2 não são funcionais um ambiente em que servidores downstream do WSUS 3.0 SP1 são gerenciados de um servidor do WSUS 3.0 SP2**.          Se os novos relatórios forem executados para um servidor do SP1, a seguinte mensagem de erro será exibida: "Erro ao gerar o relatório. Tente executar o relatório novamente ou entre em contato com o administrador da rede se o problema persistir." A execução do relatório novamente não irá resolver o problema e também não há relação com problema de rede. Os novos relatórios dependem da funcionalidade de API que não existe no SP1, entretanto o Console de Administração do SP2 não bloqueia os novos relatórios ao gerenciar um servidor do SP1.
-   **A atualização para o WSUS 3.0 SP2 falha quando o SSL é configurado sem nome de certificado**.  
    É necessário um nome de certificado para configurar o SSL. 
-   **O WSUS 3.0 SP2 que executa Windows Internal Database instalado em Windows Server 2008 impede a atualização para Windows Server 2008 R2**.  
    Antes de você continuar com a atualização para Windows Server 2008 R2, uma mensagem de erro do Relatório de Compatibilidade será exibida com instruções para desativar o Windows Internal Database. É necessário atualizar Windows Internal Database antes da atualização para Windows Server 2008 R2 poder continuar. Consulte o link [Como obter o pacote de serviços mais recente para o Windows Internal Database](http://go.microsoft.com/fwlink/?linkid=162104) (http://go.microsoft.com/fwlink/?LinkId=162104) para obter mais instruções e informações sobre atualização Windows Internal Database.

Aviso de Direitos Autorais
--------------------------

As informações contidas neste documento, incluindo URL e outras referências de site da Internet, estão sujeitas a alterações sem aviso prévio. A menos que indicado em contrário, as empresas, as organizações, os produtos, os nomes de domínios, os endereços de email, os logotipos, as pessoas, os lugares e os eventos descritos nos exemplos aqui contidos são fictícios. Nenhuma associação com qualquer empresa, organização, produto, nome de domínio, endereço de email, logotipo, pessoa, lugar ou acontecimento real é intencional ou deve ser inferida. Obedecer a todas as leis de direitos autorais aplicáveis é responsabilidade do usuário. Sem a limitação dos direitos sob direitos autorais, nenhuma parte deste documento pode ser reproduzida, armazenada ou introduzida em nenhum sistema de recuperação, ou transmitida sob qualquer forma ou por qualquer meio (eletrônico, mecânico, de fotocópia, gravação ou outro), ou para qualquer propósito, sem a permissão expressa por escrito da Microsoft Corporation.

A Microsoft pode ter patentes ou requisições para obtenção de patente, marcas comerciais, direitos autorais ou outros direitos de propriedade intelectual que abranjam o conteúdo deste documento. A posse deste documento não lhe confere nenhum direito sobre as citadas patentes, marcas comerciais, direitos autorais ou outros direitos de propriedade intelectual, salvo aqueles expressamente mencionados em um contrato de licença, por escrito, da Microsoft.

© 2009 Microsoft Corporation. Todos os direitos reservados.

Microsoft, Active Directory, ActiveX, Authenticode, Excel, InfoPath, Internet Explorer, MSDN, Outlook, Visual Studio, Win32, Windows, Windows Server e Windows Vista são marcas comerciais do grupo de empresas Microsoft.

Todas as outras marcas comerciais pertencem a seus respectivos proprietários.
