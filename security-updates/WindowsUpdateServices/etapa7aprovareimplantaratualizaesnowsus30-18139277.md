---
TOCTitle: 'Etapa 7: Aprovar e implantar atualizações no WSUS 3.0'
Title: 'Etapa 7: Aprovar e implantar atualizações no WSUS 3.0'
ms:assetid: '88fac442-a9d3-4e74-92f6-3822b7237af1'
ms:contentKeyID: 18139277
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708475(v=WS.10)'
---

Etapa 7: Aprovar e implantar atualizações no WSUS 3.0
=====================================================

Nesta etapa, você aprovará uma atualização para qualquer computador cliente de teste no grupo de teste. Os computadores do grupo contatarão o servidor do WSUS nas próximas 24 horas. Depois desse período, você poderá usar o recurso de relatórios do WSUS para determinar se essas atualizações foram implantadas nos computadores. Se o teste for bem-sucedido, você poderá aprovar as mesmas atualizações para os demais computadores da organização.

**A Etapa 7 contém os seguintes procedimentos**:

-   Aprovar e implantar uma atualização.
-   Verificar o status da atualização.

**Para aprovar e implantar uma atualização**
1.  No console de administração do WSUS, clique em **Atualizações**. Isso exibirá um resumo das atualizações nos modos de exibição padrão (**Todas as Atualizações**, **Atualizações Críticas**, **Atualizações de Segurança** e **Atualizações do WSUS**). Use **Todas as Atualizações** para este procedimento.

2.  Na lista de atualizações, selecione as atualizações que deseja aprovar para instalação. As informações sobre uma atualização selecionada estão disponíveis na parte mais inferior do painel Atualizações. Para selecionar várias atualizações contíguas, pressione e mantenha pressionada a tecla **SHIFT** enquanto clica nas atualizações; para selecionar várias atualizações que não sejam contíguas, pressione e mantenha pressionada a tecla **CTRL** enquanto clica nas atualizações.

3.  Clique com o botão direito do mouse na seleção e clique em **Aprovar**. A caixa de diálogo **Aprovar Atualizações** será exibida.

4.  Selecione um dos grupos (por exemplo, **Teste**) e clique na seta à sua esquerda. Você verá um menu de contexto com as opções **Aprovado para Instalação**, **Aprovado para Remoção**, **Não Aprovada**, **Prazo**, **Igual ao Pai** e **Aplicar aos Filhos**. Clique em **Aprovado para Instalação** e em **OK**.

5.  Você verá uma nova janela, **Progresso da Aprovação**, que mostra o progresso das diferentes tarefas que afetam a aprovação das atualizações. Quando a aprovação for concluída, clique em **Fechar** para fechar a janela.

| ![](images/Cc708475.note(WS.10).gif)Observação                                                |
|----------------------------------------------------------------------------------------------------------------------------|
| Muitas opções são associadas à aprovação de atualizações, como a configuração de prazos e a desinstalação de atualizações. |

Depois de 24 horas, você poderá usar o recurso de relatórios do WSUS para determinar se essas atualizações foram implantadas nos computadores.

**Para verificar o status de uma atualização**
1.  No console de administração do WSUS, clique em **Relatórios** no painel esquerdo.

2.  Na página **Relatórios**, você verá vários relatórios padronizados. Clique no relatório **Resumo do Status da Atualização**. A janela **Relatórios de Atualização** será exibida.

3.  Se desejar filtrar a lista de atualizações, selecione os critérios que deseja usar (por exemplo, **Incluir atualizações nestas classificações**) e clique em **Executar Relatório** na barra de ferramentas da janela.

4.  O painel **Relatórios de Atualização** será exibido. Você pode verificar o status de atualizações individuais selecionando a atualização na seção esquerda do painel. A última seção do painel do relatório mostra o resumo do status da atualização.

5.  O relatório pode ser salvo ou impresso clicando-se no ícone apropriado na barra de ferramentas.

Se a implantação das atualizações tiver sido bem-sucedida para o grupo de teste, as mesmas atualizações podem ser aprovadas para os demais computadores da organização.
