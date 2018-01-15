---
TOCTitle: 'Etapa 4: Configurar atualizações e a sincronização'
Title: 'Etapa 4: Configurar atualizações e a sincronização'
ms:assetid: '734cc2ed-98be-4772-a42c-8fd38b39d864'
ms:contentKeyID: 18139256
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708447(v=WS.10)'
---

Etapa 4: Configurar atualizações e a sincronização
==================================================

Antes de baixar as atualizações, será necessário especificar quais atualizações você deseja baixar. Esta seção descreve como configurar o conjunto de atualizações que você deseja baixar.

Os procedimentos desta etapa descrevem como:

-   Salvar e baixar informações sobre o servidor upstream e o servidor proxy.
-   Escolher os idiomas das atualizações desejadas.
-   Escolher os produtos para os quais deseja obter atualizações.
-   Escolher as classificações das atualizações desejadas.
-   Especificar a agenda de sincronização para o servidor.

Os cinco procedimentos a seguir descrevem como configurar as atualizações usando o assistente de configuração. Procedimentos posteriores descrevem como executar essa configuração a partir do console de administração do WSUS escolhendo opções específicas.

**Salvar e baixar informações sobre o servidor upstream e o proxy**
1.  Você deve ter concluído a configuração do servidor upstream e do servidor proxy no assistente de configuração e deve ver a página **Conectar ao Servidor Upstream**.

2.  Clique no botão **Iniciar Conexão**, que salvará e carregará suas configurações e obterá informações sobre as atualizações disponíveis.

3.  Enquanto a conexão estiver sendo feita, o botão **Parar Conexão** estará disponível. Se houver problemas com a conexão, clique em **Parar Conexão**, corrija os problemas e reinicie a conexão.

4.  Após a conclusão bem-sucedida do download, clique em **Avançar** para prosseguir para a página **Escolher Idiomas** ou selecione uma página diferente no painel esquerdo.

**Escolher idiomas de atualização**
1.  A página **Escolher Idiomas** permite obter atualizações de todos os idiomas ou de um subconjunto de idiomas. A seleção de um subconjunto de idiomas economizará espaço em disco, mas é importante escolher todos os idiomas que serão necessários para todos os clientes do servidor do WSUS.

2.  Se você optar por obter atualizações somente para alguns idiomas, selecione **Baixar atualizações somente nestes idiomas** e selecione os idiomas para os quais deseja atualizações. Clique em **Avançar** para prosseguir para a página **Escolher Produtos** ou selecione uma página diferente no painel esquerdo.

**Escolher produtos de atualização**
1.  A página **Escolher Produtos** permite especificar os produtos para os quais deseja atualizações.

2.  Você pode selecionar categorias de produtos, como o Windows, ou produtos específicos, como o Windows Server 2003. A seleção de uma categoria de produtos fará com que todos os produtos sob ela sejam selecionados. Clique em **Avançar** para prosseguir para a página **Escolher Classificações** ou selecione uma página diferente no painel esquerdo.

**Escolher as classificações de atualização**
1.  A página **Escolher Classificações** permite escolher as classificações de atualizações que você deseja obter. Pode-se escolher todas as classificações ou um subconjunto delas.

2.  Clique em **Avançar** para prosseguir para a página **Configurar Agenda de Sincronização** ou selecione uma página diferente no painel esquerdo.

**Configurar a agenda de sincronização**
1.  Você verá a página **Definir Agenda de Sincronização**, que permite escolher se você deseja executar a sincronização manual ou automaticamente.

2.  Se você optar por sincronizar manualmente no servidor, será necessário iniciar o processo de sincronização a partir do console de administração do WSUS.

3.  Se optar por sincronizar automaticamente, o servidor do WSUS sincronizará em intervalos especificados. Defina a hora da primeira sincronização e especifique o número de sincronizações por dia que deseja que o servidor execute. Por exemplo, se você especificar que devem ocorrer quatro sincronizações por dia, a partir das 3:00, as sincronizações ocorrerão às 3:00, às 9:00, às 15:00 e às 21:00.

Após concluir todas as etapas de configuração acima, selecione a página **Concluído** no assistente de configuração. O console de administração do WSUS pode ser iniciado deixando-se a caixa de seleção **Iniciar o snap-in de Administração do Windows Server Update Services** marcada e a primeira sincronização pode ser iniciada deixando-se a caixa de seleção **Começar a sincronização inicial** marcada.

| ![](images/Cc708447.note(WS.10).gif)Observação                                                                                    |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Não é possível salvar as alterações de configuração feitas durante a sincronização do servidor. Aguarde a conclusão da sincronização para fazer as alterações. |

![](images/Cc708447.3f774fd1-af87-47d8-8f50-a5d585687d70(WS.10).gif)

Os procedimentos a seguir explicam como executar as etapas de configuração acima através da página **Opções** do console de administração do WSUS:

-   Escolher produtos e classificações
-   Arquivos de atualização e idiomas

**Escolher produtos e classificações**
1.  Inicie o console de administração do WSUS: clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Ferramentas Administrativas** e clique em **Microsoft Windows Server Update Services**.

2.  Selecione **Opções** sob o servidor do WSUS no painel esquerdo.

3.  No painel central, selecione **Produtos e Classificações**.

4.  Será exibida uma caixa de diálogo com duas guias: **Produtos** e **Classificações**.

5.  Na guia **Produtos**, selecione a categoria do produto ou o produto específico para o qual deseja que o servidor obtenha atualizações ou selecione **Todos os Produtos**.

6.  Na guia **Classificações**, selecione as classificações de atualização desejadas ou selecione **Todas as Classificações**.

7.  Clique em **OK** para salvar suas seleções.

**Arquivos de atualização e idiomas**
1.  Na página **Opções**, selecione **Arquivos de Atualização e Idiomas**.

2.  Será exibida uma caixa de diálogo com duas guias: **Arquivos de Atualização** e **Idiomas de Atualização**.

3.  Na guia **Arquivos de Atualização**, você pode optar por armazenar os arquivos de atualização localmente ou fazer com que todos os computadores cliente instalem a partir do Microsoft Update. Se você optar por armazenar arquivos de atualização no servidor, poderá escolher se deseja baixar somente as atualizações aprovadas ou baixar arquivos da instalação expressa.

4.  Na guia **Idiomas de Instalação**, você pode optar por obter atualizações para todos os idiomas (o padrão) ou obter atualizações somente para os idiomas especificados. Se o servidor do WSUS tiver servidores downstream, eles obterão atualizações nos idiomas especificados pelo servidor upstream.

5.  Clique em **OK** para salvar as configurações.

Após configurar a conexão de rede, é possível baixar atualizações sincronizando o servidor do WSUS.

A sincronização envolve o contato do servidor do WSUS com o Microsoft Update. Depois desse contato, o WSUS determina se existe alguma nova atualização disponível desde a última vez em que foi feita a sincronização. Como esta é a primeira vez que você está sincronizando o servidor do WSUS, todas as atualizações estarão disponíveis e prontas para sua aprovação para instalação. A sincronização inicial pode levar um tempo razoavelmente longo.

| ![](images/Cc708447.note(WS.10).gif)Observação                                                                                                |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Este documento descreve a sincronização usando as configurações padrão, mas o WSUS inclui opções que permitem minimizar o uso da largura de banda durante a sincronização. |

**Para sincronizar o servidor do WSUS**
1.  No console de administração do WSUS, selecione **Sincronizações**.

2.  Clique com o botão direito do mouse ou vá para o painel **Ações** à direita e clique em **Sincronizar Agora**.

| ![](images/Cc708447.note(WS.10).gif)Observação                                                                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Se você não vir o painel **Ações** do lado direito do console, na barra de ferramentas do console, clique em **Exibir**, clique em **Personalizar** e verifique se a caixa de seleção **Painel de Ações** está marcada. |

Depois da conclusão da sincronização, clique em **Atualizações** no painel esquerdo para exibir a lista de atualizações.
