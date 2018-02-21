---
TOCTitle: 'Etapa 5: atualizar e configurar as Atualizações Automáticas'
Title: 'Etapa 5: atualizar e configurar as Atualizações Automáticas'
ms:assetid: '4ac8d574-f48e-4d9d-86c9-9aeb0f57e750'
ms:contentKeyID: 18139115
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720533(v=WS.10)'
---

Etapa 5: atualizar e configurar as Atualizações Automáticas
===========================================================

Os computadores cliente do WSUS exigem uma versão compatível das Atualizações Automáticas. A instalação do WSUS configura automaticamente o IIS para distribuir a versão mais recente das Atualizações Automáticas para cada computador cliente que contata o servidor do WSUS.

> [!NOTE]  
> Embora a maioria das versões de Atualizações Automáticas possa ser direcionada ao servidor do WSUS e ser atualizada automaticamente com a versão compatível do WSUS, a versão de Atualizações Automáticas incluída no Windows XP sem service packs não é capaz de se atualizar automaticamente. Se o Windows XP estiver instalado sem service packs no ambiente e se você nunca tiver usado o Software Update Services (SUS), consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês) para obter instruções. 

A melhor maneira de configurar as Atualizações Automáticas depende do seu ambiente de rede. Em um ambiente do Active Directory, você pode usar um objeto de Diretiva de Grupo (GPO) baseado no Active Directory. Em um ambiente que não seja do Active Directory, use o GPO local. Se você usar o GPO local ou um GPO armazenado em um controlador de domínio, será preciso direcionar os computadores cliente para o servidor do WSUS e configurar as Atualizações Automáticas.

As instruções a seguir presumem que sua rede execute o Active Directory. Esses procedimentos também presumem que você já configurou e está familiarizado com a Diretiva de Grupo e a utiliza para gerenciar sua rede. Você precisa criar um novo GPO para as configurações do WSUS e vincular o GPO no nível do domínio.

Para obter mais informações sobre a Diretiva de Grupo, consulte a página [Diretiva de Grupo](http://go.microsoft.com/fwlink/?linkid=47375) em http://go.microsoft.com/fwlink/?LinkID=14232 (o documento pode estar em inglês).

A Etapa 5 é composta pelos seguintes procedimentos:

-   Carregar o Modelo Administrativo do WSUS.
-   Configurar as Atualizações Automáticas.
-   Direcionar os computadores cliente ao servidor do WSUS.
-   Iniciar manualmente a detecção no computador cliente.

Realize os três procedimentos a seguir em um objeto de Diretiva de Grupo baseado no Active Directory.

**Para adicionar o Modelo Administrativo do WSUS**
1.  No Editor do Objeto de Diretiva de Grupo, clique em um dos nós **Modelos Administrativos**.

2.  No menu **Ação**, clique em **Adicionar ou Remover Modelos**.

3.  Clique em **Adicionar**.

4.  Na caixa de diálogo **Modelos de Diretivas**, clique em **wuau.adm** e em **Abrir**.

5.  Na caixa de diálogo **Adicionar ou Remover Modelos**, clique em **Fechar**.

**Para configurar o comportamento das Atualizações Automáticas**
1.  No Editor do Objeto de Diretiva de Grupo, expanda **Configuração do Computador**, expanda **Modelos Administrativos**, expanda **Componentes do Windows** e clique em **Windows Update**.

2.  No painel de detalhes, clique duas vezes em **Configurar Atualizações Automáticas**.

3.  Clique em **Ativada** e clique em uma destas opções:

    -   **Avisar antes de fazer o download e de instalar qualquer atualização.** Esta opção avisa um usuário com logon administrativo antes do download e da instalação de atualizações.
    -   **Fazer o download automático das atualizações e avisar quando elas estiverem prontas para serem instaladas.** Esta opção começa o download das atualizações automaticamente e depois avisa um usuário com logon administrativo antes de instalar as atualizações.
    -   **Fazer o download automático das atualizações e instalá-las no agendamento especificado abaixo.** Se as Atualizações Automáticas estiverem configuradas para realizar uma instalação agendada, você também deverá definir o dia e o horário da instalação agendada recorrente.
    -   **Permitir que o administrador local escolha a configuração.** Com esta opção, os administradores locais podem usar as Atualizações Automáticas no Painel de Controle para selecionar a opção de configuração desejada. Por exemplo, eles podem escolher seu próprio horário de instalação agendada. Os administradores locais não têm permissão para desabilitar as Atualizações Automáticas.

4.  Clique em **OK**.

> [!NOTE]  
> A opção **Permitir que o administrador local escolha a configuração** somente será exibida se as Atualizações Automáticas tiverem se atualizado para a versão compatível com o WSUS. 

**Para direcionar o computador cliente ao servidor do WSUS**
1.  No Editor do Objeto de Diretiva de Grupo, expanda **Configuração do Computador**, expanda **Modelos Administrativos**, expanda **Componentes do Windows** e clique em **Windows Update**.

2.  No painel de detalhes, clique duas vezes em **Especifique o local do serviço de atualização da Microsoft para a intranet**.

3.  Clique em **Ativado** e digite a URL do HTTP do mesmo servidor do WSUS nas caixas **Configurar o serviço de atualização da intranet para detectar atualizações** e **Configure as estatísticas do servidor intranet**. Por exemplo, digite **http://***nome\_do\_servidor* nas duas caixas.

4.  Clique em **OK**.

> [!NOTE]  
> Se você estiver usando o GPO local para direcionar esse computador ao WSUS, essa configuração entrará em vigor imediatamente e esse computador será exibido no console administrativo do WSUS em aproximadamente 20 minutos. Você pode agilizar esse processo iniciando manualmente um ciclo de detecção. 

Depois de definir um computador cliente, serão necessários alguns minutos até que ele apareça na página **Computadores** no console do WSUS. Nos computadores cliente configurados com um GPO baseado no Active Directory, esse tempo será de aproximadamente 20 minutos depois que a Diretiva de Grupo for atualizada (ou seja, aplicar todas as configurações novas ao computador cliente). Por padrão, a Diretiva de Grupo é atualizada em segundo plano a cada 90 minutos, com uma diferença aleatória entre 0 e 30 minutos. Se você desejar atualizar a Diretiva de Grupo antes, vá para o prompt de comando no computador cliente e digite: **gpupdate /force**.

Para os computadores cliente configurados com o GPO local, a Diretiva de Grupo é imediatamente aplicada e levará aproximadamente 20 minutos.

Depois que a Diretiva de Grupo for aplicada, você poderá iniciar a detecção manualmente. Se você realizar essa etapa, não será preciso aguardar 20 minutos para que o computador cliente contate o WSUS.

**Para iniciar manualmente a detecção pelo servidor do WSUS**
1.  No computador cliente, clique em **Iniciar** e, em seguida, clique em **Executar**.

2.  Digite **cmd** e clique em **OK**.

3.  No prompt de comando, digite **wuauclt.exe /detectnow**. Essa opção de linha de comando instrui as Atualizações Automáticas a contatar o servidor do WSUS imediatamente.
