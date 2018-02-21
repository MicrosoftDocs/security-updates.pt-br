---
TOCTitle: 'Etapa 4: Configurar atualizações e sincronização'
Title: 'Etapa 4: Configurar atualizações e sincronização'
ms:assetid: 'deeaa7e1-9b50-45cb-9537-d75f70de3405'
ms:contentKeyID: 21798886
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Dd939924(v=WS.10)'
---

Etapa 4: Configurar atualizações e sincronização
================================================

Esta seção descreve como configurar um conjunto de atualizações que você deseja baixar usando o Windows Server Update Services 3.0 Service Pack 2 (WSUS 3.0 SP2).

Procedimentos da etapa 4
------------------------

Você pode realizar estes procedimentos usando o Assistente de Configuração WSUS ou o Console de Administração WSUS.

1.  Salvar e baixar informações sobre o servidor upstream e o servidor proxy.
2.  Escolha o idioma das atualizações.
3.  Selecione os produtos sobre os quais deseja receber atualizações.
4.  Escolha a classificação das atualizações.
5.  Especificar a agenda de sincronização para o servidor.

Após configurar a conexão de rede, é possível baixar atualizações sincronizando o servidor do WSUS. A sincronização começa quando o servidor WSUS em contato com o Microsoft Update. Após WSUS fazer o contato, este determinará se há alguma nova atualização disponibilizada desde a última vez em que você esteve sincronizado. Ao sincronizar o WSUS pela primeira vez, todas as atualizações estarão disponíveis e prontas para sua aprovação de instalação. A sincronização inicial pode levar um longo tempo.

Os procedimentos neste seção descrevem a sincronização com as configurações padrão. O WSUS 3.0 SP2 também inclui opções que permitem minimizar o uso de largura de banda durante a sincronização.

Se você estiver usando o Assistente de Configuração do WSUS
-----------------------------------------------------------

Nos procedimentos da etapa 3, você concluiu a configuração do servidor upstream e do servidor proxy. Este próximo conjunto de procedimentos começa na página **Conectar ao Servidor Upstream** do assistente de configuração.

**Para salvar e baixar seu servidor upstream e informações de proxy**
1.  Na página Conectar ao Upstream no assistente de configuração, clique no botão **Iniciar Conexão**. Este botão salva e carrega suas configurações e coleta informações sobre as atualizações disponíveis.

2.  Enquanto a conexão estiver sendo feita, o botão **Parar Conexão** estará disponível. Se houver problemas com a conexão, clique em **Parar Conexão**, corrija os problemas e reinicie a conexão.

3.  Após o download ter sido concluído com êxito, clique em **Avançar**.

**Para escolher o idioma da atualização**
1.  A página Escolher Idioma permite que você receba as atualizações em todos os idiomas ou em um subconjunto de idiomas. Selecionar um subconjunto de idiomas economizará espaço em disco, mas é importante escolher todos os idiomas necessários aos clientes desse servidor WSUS.

    Se você escolher obter as atualizações apenas para idiomas específicos, selecione **Baixar atualizações apenas nesses idiomas** e selecione os idiomas nos quais você deseja atualizações.

2.  Clique em **Avançar**.

**Para escolher produtos de atualização**
1.  A página Escolher Produtos permite que você especifique os produtos para os quais deseja atualizações. Selecione as categorias de produtos, como Windows, ou produtos específicos, como o Windows Server 2008. Selecionar uma categoria de produto fará com que todos os produtos nessa categoria sejam selecionados.

2.  Clique em **Avançar**.

**Para escolher classificações de atualização**
1.  A página Escolher Classificações permite especificar as classificações de atualizações que você deseja obter. Escolha todas as classificações ou um subconjunto delas.

2.  Clique em **Avançar**.

**Para configurar a agenda de sincronização**
1.  Na página Configurar Agenda de Sincronização, escolha se você deseja executar a sincronização manual ou automaticamente.

    Se você escolher **Sincronizar manualmente**, você terá que iniciar o processo de sincronização a partir do Console de Administração WSUS.

    Se você escolher **Sincronizar automaticamente**, o servidor WSUS será sincronizado em intervalos definidos. Defina a hora da **Primeira sincronização** e especifique o número de **Sincronizações diárias** que você deseja que o servidor execute. Por exemplo, se você especificar que deve haver quatro sincronizações por dia, começando em 3:00 A.M., as sincronizações ocorrerão em 3:00 A.M., 9:00 A.M., 3:00 P.M. e 9:00 P.M.

2.  Clique em **Avançar**.

3.  Na página Concluído, você pode iniciar o Console de Administração WSUS marcando a caixa de seleção **Iniciar o snap-in de Administração do Windows Server Update Services** e a primeira sincronização pode ser iniciada deixando-se a caixa de seleção **Começar a sincronização inicial** marcada.

4.  Clique em **Concluir**.

   > [!IMPORTANT]  
   > Não é possível salvar as alterações de configuração feitas durante a sincronização do servidor. Aguarde até que a sincronização seja concluida e faça suas alterações.

Se você estiver usando o Console de Administração WSUS
------------------------------------------------------

Os procedimentos a seguir explicam como executar as etapas de configuração usando o Console de Administração WSUS.

**Para escolher os produtos e classificações da atualização**
1.  No painel **Opções**, clique em **Produtos e Classificações**. Uma caixa de diálogo aparecerá com as guias **Produtos** e **Classificações**.

2.  Na guia **Produtos**, selecione a categoria de produtos ou produtos específicos para os quais você desejar que o servidor receba atualizações ou selecione **Todos os Produtos**.

3.  Na guia **Classificações**, selecione as classificações de atualização desejadas ou selecione **Todas as Classificações**.

4.  Clique em **OK** para salvar suas seleções.

**Para escolher arquivos e idiomas da atualização**
1.  No painel **Opções**, clique em **Arquivos e Idiomas da Atualização**. Uma caixa de diálogo aparecerá com as guias **Arquivos da Atualização** e **Idiomas da Atualização**.

2.  Na guia **Arquivos da Atualização**, escolha **Armazenar os arquivos da atualização localmente neste servidor** ou deixar que todos os computadores clientes façam a instalação a partir do Microsoft Update. Se você decidir armazenar os arquivos de atualização no servidor, você também deve decidir se serão baixadas apenas as atualizações aprovadas ou os arquivos de instalação expressa.

3.  Na guia **Idiomas da Atualização**, se você estiver armazenando os arquivos de atualização localmente, escolha **Baixar atualizações para todos os idiomas** (o padrão) ou **Baixar atualizações apenas nos idiomas especificados**. Se esse servidor WSUS tiver servidores downstream, eles receberão atualizações apenas nos idiomas especificados pelo servidor upstream.

4.  Clique em **OK** para salvar as configurações.

**Para sincronizar o servidor WSUS**
1.  No painel **Opções**, clique em **Agenda de Sincronização**.

2.  Na página **Agenda de Sincronização**, escolha se você deseja executar a sicronização manual ou automaticamente.

    Se você escolher **Sincronizar manualmente**, você terá que iniciar o processo de sincronização a partir do Console de Administração WSUS.

    Se você escolher **Sincronizar automaticamente**, o servidor WSUS será sincronizado em intervalos definidos. Defina a hora da **Primeira sincronização** e especifique o número de **Sincronizações diárias** que você deseja que o servidor execute. Por exemplo, se você especificar que deve haver quatro sincronizações por dia, começando em 3:00 A.M., as sincronizações ocorrerão em 3:00 A.M., 9:00 A.M., 3:00 P.M. e 9:00 P.M.

3.  Clique em **OK** para salvar suas seleções.

4.  No painel esquerdo do Console de Administração do WSUS, selecione **Sincronizações**.

5.  Clique com o botão direito ou passe ao painel **Ações** no lado direito e clique em **Sincronizar Agora**.

    Se você não vir o painel **Ações** do lado direito do console, na barra de ferramentas do console, clique em **Exibir**, clique em **Personalizar** e verifique se a caixa de seleção **Painel de Ações** está marcada.

6.  Depois que a sincronização for concluída, clique em **Atualizações** no painel esquerdo para exibir uma lista de atualizações.

Próxima etapa
-------------

[Etapa 5: Configurar as atualizações de clientes](https://technet.microsoft.com/5ae60ead-3e94-456c-a692-c0f193ea5d5a).

Recursos adicionais
-------------------

[Guia passo a passo para o Windows Server Update Services 3.0 SP2](https://technet.microsoft.com/4b504edc-93b3-45b0-a7e8-d0107f1a4442)
