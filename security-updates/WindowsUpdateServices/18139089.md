---
TOCTitle: 'Etapa 7: aprovar e implantar as atualizações'
Title: 'Etapa 7: aprovar e implantar as atualizações'
ms:assetid: '38db25a9-6702-4e43-b536-764e8814afc6'
ms:contentKeyID: 18139089
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720504(v=WS.10)'
---

Etapa 7: aprovar e implantar as atualizações
============================================

Nesta etapa, você aprovará uma atualização para qualquer computador cliente de teste no grupo Teste. Os computadores do grupo verificarão o servidor do WSUS nas 24 horas seguintes. Depois desse período, você poderá usar o recurso de relatório do WSUS para determinar se essas atualizações foram implantadas nos computadores. Se o teste for bem-sucedido, você poderá aprovar a mesma atualização para os demais computadores da organização.

A Etapa 7 é composta pelos seguintes procedimentos:

-   Aprovar e implantar uma atualização.
-   Verificar o relatório Status das Atualizações.

**Para aprovar e implantar uma atualização**
1.  Na barra de ferramentas do console do WSUS, clique em **Atualizações**. Por padrão, a lista de atualizações é filtrada para mostrar apenas as atualizações críticas e de segurança que foram aprovadas para detecção nos computadores cliente. Use o filtro padrão para esse procedimento.

2.  Na lista de atualizações, selecione as atualizações que deseja aprovar para instalação. As informações sobre a atualização selecionada estão disponíveis na guia **Detalhes**. Para selecionar várias atualizações contíguas, pressione e mantenha pressionada a tecla SHIFT enquanto faz a seleção; para selecionar várias atualizações que não sejam contíguas, pressione e mantenha pressionada a tecla CTRL enquanto faz a seleção.

3.  Em **Atualizar Tarefas**, clique em **Alterar aprovação**. A caixa de diálogo **Aprovar Atualizações** será exibida.

4.  Na lista **Configurações de aprovação de grupo das atualizações selecionadas**, clique em **Instalar** na lista na coluna **Aprovação** para o grupo Teste e, em seguida, clique em **OK**.

> [!NOTE]  
> Há várias opções associadas à aprovação de atualizações, como a configuração de prazos e a desinstalação de atualizações. Esses assuntos são tratados no informe oficial “Microsoft Windows Server Update Services Operations Guide” (o documento pode estar em inglês). 

Depois de 24 horas, você poderá usar o recurso de relatório do WSUS para determinar se essas atualizações foram implantadas nos computadores.

**Para verificar o relatório Status das Atualizações**
1.  Na barra de ferramentas do console do WSUS, clique em **Relatórios**.

2.  Na página **Relatórios**, clique em **Status das Atualizações**.

3.  Se você desejar filtrar a lista de atualizações, em **Exibir**, selecione os critérios a serem utilizados e clique em **Aplicar**.

4.  Se desejar ver o status de uma atualização por grupo de computadores e, em seguida, por computador, expanda a exibição da atualização conforme a necessidade.

5.  Se desejar imprimir o relatório Status das Atualizações, em **Tarefas**, clique em **Imprimir relatório**.

Se a implantação das atualizações no grupo Teste for bem-sucedida, você poderá aprovar as mesmas atualizações para os demais computadores da organização.
