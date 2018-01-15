---
TOCTitle: 'Etapa 7: Aprovar e implantar atualizações WSUS'
Title: 'Etapa 7: Aprovar e implantar atualizações WSUS'
ms:assetid: 'c4e58e17-d5e3-4194-8f26-b459e0c03b86'
ms:contentKeyID: 21798871
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Dd939909(v=WS.10)'
---

Etapa 7: Aprovar e implantar atualizações WSUS
==============================================

Nesta etapa, você aprovará um atualização para quaisquer computadores no grupo de teste do Windows Server Update Services 3.0 Service Pack 2 (WSUS 3.0 SP2). Os computadores no grupo entrarão em contato automaticamente com o servidor WSUS nas próximas 24 horas para obter a atualização. Você pode usar o recurso de geração de relatórios do WSUS para determinar se essas atualizações foram implantadas nos computadores de teste. Quando os testes forem concluídos com êxito, você poderá aprovar as atualizações ao grupo de computadores apropriado em sua organização.

Procedimentos da etapa 7
------------------------

-   Aprovar e implantar uma atualização.
-   Verificar o status de uma atualização.

**Para aprovar e implantar uma atualização**
1.  No Console de Administração WSUS, clique em **Atualizações**. Um resumo do status da atualização será exibido para **Todas as Atualizações**, **Atualizações Críticas**, **Atualizações de Segurança** e **Atualizações WSUS**.

2.  Na seção **Todas as Atualizações**, clique em **Atualizações necessárias para os computadores**.

3.  Na lista de atualizações, selecione as atualizações que você deseja aprovar para instalação no grupo de computadores de teste. As informações sobre uma atualização selecionada estão disponíveis na parte inferior do painel Atualizações. Para selecionar várias atualizações contíguas, mantenha a tecla **SHIFT** pressionada ao clicar nas atualizações; para selecionar várias atualizações não contíguas, mantenha a tecla **CTRL** pressionada ao clicar nas atualizações.

4.  Clique com o botão direito do mouse na seleção e clique em **Aprovar**.

5.  Nacaixa de diálogo **Aprovar Atualizações**, selecione seu grupo de teste e, então, clique na seta para baixo.

6.  Clique em **Aprovado para Instalação** e em **OK**.

7.  A janela Progresso da Aprovação aparecerá mostrando o progresso das tarefas que afetam a aprovação da atualização. Quando a aprovação estiver concluída, clique em **Fechar**.

Depois de 24 horas, você poderá usar o recurso de geração de relatórios do WSUS para determinar se essas atualizações foram implantadas nos computadores do grupo de teste.

**Para verificar o status de uma atualização**
1.  No painel de navegação do Console de Administração do WSUS, selecione **Relatórios**.

2.  Na página **Relatórios**, clique no relatório **Atualizar Resumo do Status**. A janela **Relatório de Atualizações** aparecerá.

3.  Se você desejar filtrar a lista de atualizações, selecione os critérios desejados, por exemplo **Incluir atualizações nestas classificações** e, então, clique na barra de ferramentas **Executar Relatório**.

4.  O painel **Relatórios de Atualização** será exibido. Você pode verificar o status de atualizações individuais selecionando a atualização na seção esquerda do painel. A última seção do painel do relatório mostra o resumo do status da atualização.

5.  Você pode salvar ou imprimir esse relatório clicando no ícone aplicável na barra de ferramentas.

6.  Após testar as atualizações, você poderá aprová-las para instalação nos grupos de computadores aplicáveis em sua organização.

Recursos adicionais
-------------------

[Guia passo a passo para o Windows Server Update Services 3.0 SP2](https://technet.microsoft.com/4b504edc-93b3-45b0-a7e8-d0107f1a4442)

Para obter mais informações sobre como usar o WSUS 3.0 SP2, consulte:

Guia de Implantação do WSUS [http://go.microsoft.com/fwlink/?LinkId=139832](http://go.microsoft.com/fwlink/?linkid=139832).

Guia de operações do WSUS [http://go.microsoft.com/fwlink/?LinkId=139838](http://go.microsoft.com/fwlink/?linkid=139838).
