---
TOCTitle: 'Etapa 5: Configurar as Atualizações Automáticas'
Title: 'Etapa 5: Configurar as Atualizações Automáticas'
ms:assetid: '5da6d10a-6ff1-4de8-b53a-4893bf8bd9fa'
ms:contentKeyID: 18139154
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720532(v=WS.10)'
---

Etapa 5: Configurar as Atualizações Automáticas
===============================================

Os computadores cliente do WSUS exigem uma versão compatível das Atualizações Automáticas. A instalação do WSUS configura automaticamente o IIS para distribuir a versão mais recente das Atualizações Automáticas para cada computador cliente que contata o servidor do WSUS.

A melhor maneira de configurar as Atualizações Automáticas depende do seu ambiente de rede. Em um ambiente com o Active Directory, você pode usar um GPO (objeto de Diretiva de Grupo) baseado no domínio. Em um ambiente sem o Active Directory, use o GPO local. Se você usar o GPO local ou um GPO baseado no domínio, será preciso direcionar os computadores cliente para o servidor do WSUS e configurar as Atualizações Automáticas.

As instruções a seguir presumem que sua rede executa o Active Directory. Esses procedimentos também presumem que você esteja familiarizado com a Diretiva de Grupo e a utilize para gerenciar sua rede. Você precisa criar um novo GPO para as configurações do WSUS e vincular o GPO ao domínio.

Para obter mais informações sobre a Diretiva de Grupo, consulte o site sobre a Diretiva de Grupo ([http://go.microsoft.com/fwlink/?LinkID=47375](http://go.microsoft.com/fwlink/?linkid=47375); a página pode estar em inglês).

**A Etapa 5 contém os seguintes procedimentos**:

-   Adicionar o Modelo Administrativo do WSUS.
-   Configurar as Atualizações Automáticas.
-   Direcionar o computador cliente ao servidor do WSUS.
-   Iniciar manualmente a detecção pelo servidor do WSUS.

Realize os três primeiros procedimentos em um objeto de Diretiva de Grupo baseado no domínio. Será necessário criar um novo GPO ou usar um GPO existente. Se estiver usando o GPMC (Console de Gerenciamento de Diretiva de Grupo) para gerenciar seus GPOs, navegue até o GPO que deseja modificar e clique em **Editar**.

Para exibir as configurações da diretiva para gerenciar o WSUS, verifique se o arquivo de modelo administrativo do WSUS, wuau.adm, foi adicionado ao Editor de Objeto de Diretiva de Grupo. Como o wuau.adm é lançado por padrão no sistema operacional, ele já deve estar presente no Editor de Objeto de Diretiva de Grupo.

**Para adicionar o Modelo Administrativo do WSUS**
1.  No Editor de Objeto de Diretiva de Grupo, clique em um dos nós **Modelos Administrativos**.

2.  No menu **Ação**, clique em **Adicionar ou Remover Modelos** e em **Adicionar**.

3.  Na caixa de diálogo **Modelos de Diretiva**, clique em **wuau.adm** e em **Abrir**.

4.  Na caixa de diálogo **Adicionar ou Remover Modelos**, clique em **Fechar**.

**Para configurar as Atualizações Automáticas**
1.  No Editor de Objeto de Diretiva de Grupo, expanda **Configuração de Computadores**, expanda **Modelos Administrativos**, expanda **Componentes do Windows** e clique em **Windows Update**.

2.  No painel de detalhes, clique duas vezes em **Configurar Atualizações Automáticas**.

3.  Clique em **Habilitado** e clique em uma destas opções:

    -   **Notificar antes de baixar e de instalar**: Essa opção notifica um usuário administrativo conectado antes do início do download e da instalação de atualizações.
    -   **Baixar automaticamente e notificar antes de instalar**: essa opção começa a baixar as atualizações automaticamente e depois notifica um usuário administrativo conectado antes de instalar as atualizações.
    -   **Baixar automaticamente e agendar a instalação**: se as Atualizações Automáticas estiverem configuradas para realizar uma instalação agendada, você deverá definir também o dia e a hora da instalação agendada recorrente.
    -   **Permitir que o administrador local escolha a configuração**: com essa opção, os administradores locais podem usar as Atualizações Automáticas no Painel de Controle para selecionar a opção de configuração desejada. Por exemplo, eles podem escolher sua própria hora de instalação agendada. Os administradores locais não têm permissão para desabilitar as Atualizações Automáticas.

4.  Clique em **OK**.

> [!NOTE]  
> A opção **Permitir que o administrador local escolha a configuração** será exibida somente se as Atualizações Automáticas tiverem se atualizado para a versão compatível com o WSUS. 

**Para direcionar o computador cliente ao servidor do WSUS**
1.  No Editor de Objeto de Diretiva de Grupo, expanda **Configuração de Computadores**, expanda **Modelos Administrativos**, expanda **Componentes do Windows** e clique em **Windows Update**.

2.  No painel de detalhes, clique duas vezes em **Especificar o local do serviço de atualização na intranet da Microsoft**.

3.  Clique em **Habilitado** e digite a URL HTTP do mesmo servidor do WSUS nas caixas **Configurar o serviço de atualização da intranet para detectar atualizações** e **Configure as estatísticas do servidor intranet**. Por exemplo, digite *http://nome\_do\_servidor* em ambas caixas e clique em **OK**.

> [!NOTE]  
> Se você estiver usando o GPO local para direcionar esse computador ao WSUS, essa configuração entrará em vigor imediatamente e esse computador deverá aparecer no console administrativo do WSUS em pouco tempo. Você pode agilizar esse processo iniciando manualmente um ciclo de detecção. 

Depois de definir um computador cliente, serão necessários alguns minutos até que ele seja exibido na página **Computadores** do console do WSUS. Nos computadores cliente configurados com uma Diretiva de Grupo baseada no domínio, esse tempo será de aproximadamente 20 minutos depois que a Diretiva de Grupo for atualizada (ou seja, depois que ela aplicar todas as novas configurações de diretiva ao computador cliente). Por padrão, a Diretiva de Grupo é atualizada em segundo plano a cada 90 minutos, com uma diferença aleatória entre 0 e 30 minutos. Se você desejar atualizar a Diretiva de Grupo antes, vá para o prompt de comando do computador cliente e digite: **gpupdate /force**.

Para os computadores cliente configurados com o GPO local, a Diretiva de Grupo é imediatamente aplicada e a atualização leva aproximadamente 20 minutos.

Depois que a Diretiva de Grupo for aplicada, você poderá iniciar a detecção manualmente. Se a detecção for iniciada manualmente, não será preciso aguardar 20 minutos para que o computador cliente contate o WSUS.

**Para iniciar manualmente a detecção pelo servidor do WSUS**
1.  No computador cliente, clique em **Iniciar** e em **Executar**.

2.  Digite **cmd** na caixa **Abrir** e clique em **OK**.

3.  No prompt de comando, digite **wuauclt.exe /detectnow**. Essa opção de linha de comando instrui as Atualizações Automáticas a contatar o servidor do WSUS imediatamente.
