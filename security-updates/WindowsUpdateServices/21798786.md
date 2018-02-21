---
TOCTitle: 'Etapa 3: Configurar as conexões de rede'
Title: 'Etapa 3: Configurar as conexões de rede'
ms:assetid: '42a144c5-f08e-4a6e-b360-47ddea77bd24'
ms:contentKeyID: 21798786
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Dd939815(v=WS.10)'
---

Etapa 3: Configurar as conexões de rede
=======================================

Após instalar o Windows Server Update Services 3.0 Service Pack 2 (WSUS 3.0 SP2), o assistente de configuração será iniciado automaticamente. Você também pode executar o assistente posteriormente por meio da página **Opções** do Console de Administração WSUS.

Antes de iniciar o processo de configuração, assegure-se de que você saiba as respostas para as seguintes perguntas:

1. O firewall do servidor está configurado para permitir que os clientes acessem o servidor?

2. Esse computador pode se conectar ao servidor upstream (como o Microsoft Update)?

3. Você tem o nome do servidor proxy e as credenciais do usuário para o servidor proxy, se necessário?

Por padrão, o WSUS 3.0 SP2 está configurado para usar o Microsoft Update como local do qual obter as atualizações. Se você tiver um servidor proxy na rede, você poderá configurar o WSUS 3.0 SP2 para usar o servidor proxy. Se houver um firewall corporativo entre o WSUS e a Internet, pode ser necessário configurar o firewall para assegurar que o WSUS possa obter as atualizações.

> [!NOTE]
> Embora seja preciso ter conexão com a Internet para baixar as atualizações do Microsoft Update, o WSUS oferece um recurso para importar as atualizações para redes que não estejam conectadas à Internet.
 

A Etapa 3 é composta pelos seguintes procedimentos:

-   Configurar o firewall.
-   Especificar a maneira como o servidor obterá atualizações (a partir do Microsoft Update ou de outro servidor do WSUS).
-   Configure o servidor proxy para que o WSUS possa obter as atualizações.

**Para configurar o firewall**
-   Se houver um firewall corporativo entre o WSUS e a Internet, talvez seja necessário configurar o firewall para garantir que o WSUS possa obter as atualizações.Para obter as atualizações do Microsoft Update, o servidor do WSUS usa a porta 80 para o protocolo HTTP e a porta 443 para o protocolo HTTPS. Essas opções não são configuráveis.

-   Se a sua organização não permitir habilitar a porta 80 ou a porta 443 para ficar aberta a todos os endereços, você pode restringir o acesso apenas aos seguintes domínios para que o WSUS e as Atualizações Automáticas possam se comunicar com o Microsoft Update:

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
> As instruções para configurar o firewall destinam-se a um firewall corporativo posicionado entre o WSUS e a Internet. Como o WSUS inicia todo o seu tráfego de rede, não é necessário configurar o Firewall do Windows no servidor do WSUS.
 

Embora a conexão entre o Microsoft Update e o WSUS exija que as portas 80 e 443 estejam abertas, você pode configurar vários servidores do WSUS para sincronização com uma porta personalizada.

Os dois procedimentos seguintes supõem que você esteja usando o assistente de configuração. Em uma seção posterior desta etapa, você aprenderá como iniciar o snap-in de Administração do WSUS e configurar o servidor pela página Opções.

**Para especificar a maneira como o servidor obterá atualizações**
1.  No assistente de configuração, após inscrever-se no Programa de Aperfeiçoamento da Microsoft, clique em **Avançar** para selecionar o servidor upstream.

2.  Se você escolher sincronizar com o Microsoft Update, a conclusão será na página Opções. Clique em **Avançar** ou selecione **Especificar Servidor Proxy** no painel de navegação.

3.  Se você optar pela sincronização a partir de outro servidor do WSUS, especifique o nome do servidor e a porta na qual esse servidor se comunicará com o servidor upstream.

4.  Para usar SSL, marque a caixa de seleção **Usar SSL ao sincronizar informações de atualização**. Nesse caso, os servidores usarão a porta 443 para sincronização. (Certifique-se de que tanto esse servidor como o servidor upstream oferecem suporte a SSL.)

5.  Se esse for um servidor de réplica, marque a caixa de seleção **Esta é uma réplica do servidor upstream**.

6.  Neste ponto, você concluiu a configuração do servidor upstream. Clique em **Avançar** ou selecione **Especificar servidor proxy** no painel de navegação esquerdo.

**Para definir configurações do servidor proxy**
1.  Na página **Especificar Servidor Proxy** do assistente de configuração, marque a caixa de seleção **Usar um servidor proxy ao sincronizar** e digite o nome do servidor proxy e o número da porta (porta 80 por padrão) nas caixas correspondentes.

2.  Se você desejar se conectar ao servidor proxy com credenciais de usuário específicas, marque a caixa de seleção **Utilizar credenciais de usuário para se conectar ao servidor proxy** e digite o nome de usuário, o domínio e senha do usuário nas caixas correspondentes. Se quiser habilitar a autenticação básica para o usuário que se conectar ao servidor proxy, marque a caixa de seleção **Permitir autenticação básica (a senha é enviada em texto não criptografado)**.

3.  Neste ponto, você concluiu a configuração do servidor proxy. Clique em **Avançar** para passar à próxima página, onde você poderá iniciar a configuração do processo de sincronização.

Os dois procedimentos seguintes supõem que você esteja usando o snap-in de Administração do WSUS para configuração. Esses dois procedimentos mostram como iniciar o snap-in de Administração do WSUS e configurar o servidor a partir da página **Opções**.

**Para iniciar o Console de Administração do WSUS**
-   No Console de Administração do WSUS, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Ferramentas Administrativas** e, depois, clique em **Microsoft Windows Server Update Services 3.0**.

> [!NOTE]
> Para usar todos os recursos do console, efetue logon como um membro do grupo de segurança Administradores WSUS ou Administradores Locais no servidor no qual o WSUS está instalado. Os membros do grupo de segurança Relatores WSUS têm acesso somente leitura ao console.
 

**Para especificar uma origem da atualização e o servidor proxy**
1.  No console WSUS, clique em **Opções** no painel esquerdo sob o nome do servidor e, então, clique em **Atualizar Origem e Servidor Proxy** no painel central.

    Uma caixa de diálogo será exibida com as guias **Origem da Atualização** e **Servidor Proxy**.

2.  Na guia **Origem da Atualização**, selecione o local a partir do qual esse servidor obterá atualizações. Se você optar por sincronizar a partir do Microsoft Update (o padrão), terá terminado com esta página do assistente.

3.  Se você escolher sincronizar a partir de outro servidor WSUS, será necessário especificar a porta pela qual os servidor se comunicarão (o padrão é a porta 80). Se você selecionar uma porta diferente, você deverá se assegurar de que ambos os servidores possam usar essa porta.

4.  Você também pode especificar se o SSL deve ser usado ao sincronizar a partir do servidor upstream do WSUS. Nesse caso, os servidores usarão a porta 443 para sincronização a partir do servidor upstream.

5.  Se esse servidor for uma réplica do segundo servidor do WSUS, marque a caixa de seleção **Esta é uma réplica do servidor upstream**. Nesse caso, todas as atualizações devem ser aprovadas somente no servidor upstream do WSUS.

6.  Na guia **Servidor proxy**, marque a caixa de seleção **Usar um servidor proxy ao sincronizar** e digite o nome e o número da porta (porta 80 por padrão) do servidor proxy nas caixas correspondentes.

7.  Se você desejar se conectar ao servidor proxy com credenciais de usuário específicas, marque a caixa de seleção **Utilizar credenciais de usuário para se conectar ao servidor proxy** e digite o nome de usuário, o domínio e senha do usuário nas caixas correspondentes. Se quiser habilitar a autenticação básica para o usuário que se conectar ao servidor proxy, marque a caixa de seleção **Permitir autenticação básica (a senha é enviada em texto não criptografado)**.

8.  Clique em **OK** para salvar as configurações.

Próxima etapa
-------------

[Etapa 4: Configurar atualizações e sincronização](https://technet.microsoft.com/deeaa7e1-9b50-45cb-9537-d75f70de3405).

Recursos adicionais
-------------------

[Guia passo a passo para o Windows Server Update Services 3.0 SP2](https://technet.microsoft.com/4b504edc-93b3-45b0-a7e8-d0107f1a4442)
