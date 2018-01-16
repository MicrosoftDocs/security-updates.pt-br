---
TOCTitle: 'Etapa 3: configurar a conexão de rede'
Title: 'Etapa 3: configurar a conexão de rede'
ms:assetid: 'cd77566d-7780-4ce4-aa56-41183c65c4a7'
ms:contentKeyID: 18139492
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708559(v=WS.10)'
---

Etapa 3: configurar a conexão de rede
=====================================

Após instalar o WSUS, você está pronto para acessar o console do WSUS para configurar o WSUS e começar a usá-lo. Por padrão, o WSUS é configurado para usar o Microsoft Update como o local para obter as atualizações. Se você tiver um servidor proxy na rede, use o console do WSUS para configurar o WSUS para usar o servidor proxy. Se houver um firewall corporativo entre o WSUS e a Internet, talvez seja necessário configurar o firewall para garantir que o WSUS possa obter as atualizações.

> [!NOTE]  
> Embora seja preciso ter conexão com a Internet para baixar as atualizações do Microsoft Update, o WSUS oferece um recurso para importar as atualizações para redes que não estejam conectadas à Internet. Para obter mais informações, consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (documento pode estar em inglês). 

A Etapa 3 é composta pelos seguintes procedimentos:

-   Configure o firewall para que o WSUS possa obter as atualizações.
-   Abra o console do WSUS.
-   Configure o servidor proxy para que o WSUS possa obter as atualizações.

**Para configurar o firewall**
-   Se houver um firewall corporativo entre o WSUS e a Internet, talvez seja necessário configurar o firewall para garantir que o WSUS possa obter as atualizações. Para obter as atualizações do Microsoft Update, o servidor do WSUS usa a porta 80 para o protocolo HTTP e a porta 443 para o protocolo HTTPS. Essas opções não são configuráveis.

-   Se a sua organização não permitir que essas portas e esses protocolos fiquem abertas para todos os endereços, você pode restringir o acesso apenas aos seguintes domínios para que o WSUS e as Atualizações Automáticas possam se comunicar com o Microsoft Update:

    -   http://windowsupdate.microsoft.com
    -   http://\*.windowsupdate.microsoft.com
    -   https://\*.windowsupdate.microsoft.com
    -   http://\*.update.microsoft.com
    -   https://\*.update.microsoft.com
    -   http://\*.windowsupdate.com
    -   http://download.windowsupdate.com
    -   http://download.microsoft.com
    -   http://\*.download.windowsupdate.com
    -   http://wustat.windows.com
    -   http://ntservicepack.microsoft.com

> [!NOTE]  
> As etapas de configuração do firewall acima destinam-se a um firewall corporativo posicionado entre o WSUS e a Internet. Como o WSUS inicia todo o seu tráfego de rede, não é necessário configurar o Firewall do Windows no servidor do WSUS. Embora a conexão entre o Microsoft Update e o WSUS exija que as portas 80 e 443 estejam abertas, você pode configurar vários servidores do WSUS para sincronização com uma porta personalizada. Para obter mais informações sobre a sincronização de servidores do WSUS com uma porta personalizada, consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (documento pode estar em inglês). 

**Para abrir o console do WSUS**
-   No servidor do WSUS, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Ferramentas Administrativas** e, depois, clique em **Microsoft Windows Server Update Services**.

> [!NOTE]  
> Você deve ser membro dos grupos de segurança Administradores do WSUS ou Administradores locais no servidor no qual o WSUS está instalado para usar o console do WSUS.  
Se você não adicionar **http://&lt;***nome do site do WSUS***&gt;** à lista de sites na zona de Intranet Local do Internet Explorer no Windows Server 2003, pode ser que as credenciais sejam solicitadas sempre que você abrir o console do WSUS.  
Se você alterar a atribuição de porta no IIS após a instalação do WSUS, será preciso atualizar manualmente o atalho no menu **Iniciar**.  
Também é possível abrir o console do WSUS no Internet Explorer ou em qualquer servidor ou computador na rede digitando a seguinte URL: **http://***nome do servidor do WSUS***/WSUSAdmin** 

**Para especificar um servidor proxy**
1.  Na barra de ferramentas do console do WSUS, clique em **Opções** e, em seguida, clique em **Opções de Sincronização**.

2.  Na caixa **Servidor proxy**, marque a caixa de seleção **Utilizar um servidor proxy ao sincronizar** e digite o nome e o número da porta (o padrão é a 80) do servidor proxy nas caixas correspondentes.

3.  Se você desejar se conectar ao servidor proxy com credenciais de usuário específicas, marque a caixa de seleção **Utilizar credenciais de usuário para se conectar ao servidor proxy** e depois digite o nome de usuário, domínio e senha do usuário nas caixas correspondentes. Se você desejar habilitar a autenticação básica para o usuário que se conectar ao servidor proxy, marque a caixa de seleção **Permitir a autenticação básica (a senha é enviada como texto não criptografado)**.

4.  Em **Tarefas**, clique em **Salvar configurações** e, em seguida, clique em **OK** na caixa de confirmação.
