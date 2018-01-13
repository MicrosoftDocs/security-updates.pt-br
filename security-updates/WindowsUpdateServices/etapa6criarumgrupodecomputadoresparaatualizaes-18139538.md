---
TOCTitle: 'Etapa 6: Criar um grupo de computadores para atualizações'
Title: 'Etapa 6: Criar um grupo de computadores para atualizações'
ms:assetid: 'fe219654-eae8-45ca-a44b-c1e05c3c3e93'
ms:contentKeyID: 18139538
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708629(v=WS.10)'
---

Etapa 6: Criar um grupo de computadores para atualizações
=========================================================

Os grupos de computadores são uma parte importante da implantação do WSUS, mesmo em implantações básicas. Os grupos de computadores permitem direcionar as atualizações para computadores específicos. Há dois grupos de computadores padrão: Todos os Computadores e Computadores Não Atribuídos. Por padrão, quando cada computador cliente faz um contato inicial com o servidor do WSUS, o servidor adiciona o computador cliente a cada um desses grupos.

Você pode criar grupos de computadores personalizados. Um dos benefícios de criar grupos de computadores é que eles permitem testar as atualizações antes de implantá-las de forma abrangente. Se o teste for bem-sucedido, você poderá distribuir as atualizações para o grupo Todos os Computadores. Não há limite para o número de grupos personalizados que podem ser criados.

**Para configurar grupos de computadores**
1.  Especifique como você atribuirá os computadores aos grupos de computadores. Há duas opções: destino do lado do servidor e destino do lado do cliente. O destino do lado do servidor envolve a adição manual de cada computador ao seu grupo usando o WSUS. O destino do lado do cliente envolve a adição automática dos clientes usando a Diretiva de Grupo ou as chaves do Registro.

2.  Criar um grupo de computadores no WSUS.

3.  Mover os computadores para os grupos usando o método selecionado na etapa 1.

Esta seção explica como usar o destino do lado do servidor e mover manualmente os computadores para seus grupos usando o console de administração do WSUS. Se você tiver vários computadores cliente a serem atribuídos a grupos de computadores, pode usar o destino do lado do cliente, que automatiza a movimentação dos computadores para os grupos de computadores.

Você pode usar a Etapa 6 para configurar um grupo de testes que contém pelo menos um computador de teste.

**A Etapa 6 contém os seguintes procedimentos:**

-   Criar um grupo.
-   Adicionar um computador a um grupo.

**Para criar um grupo**
1.  No console de administração do WSUS, expanda **Computadores** e selecione **Todos os Computadores**.

2.  Clique com o botão direito do mouse em **Todos os Computadores** ou vá para o painel **Ações** e clique em **Adicionar Grupo de Computadores**.

3.  Você verá uma caixa de diálogo **Adicionar Grupo de Computadores**. Especifique o nome do novo grupo.

Use o procedimento a seguir para atribuir um computador cliente ao grupo de teste. Um computador cliente apropriado para teste é qualquer computador com software e hardware que represente a maioria dos computadores na rede, mas não um computador atribuído a uma função crítica. Dessa forma, você poderá informar como será o comportamento dos computadores, como o computador de teste, com as atualizações que aprovar.

**Para adicionar um computador a um grupo**
1.  No console de administração do WSUS, clique em **Computadores**.

2.  Clique no grupo do computador a ser movido.

3.  Na lista de computadores, selecione o computador a ser movido.

4.  Clique com o botão direito do mouse em **Alterar Associação**.

5.  Você verá uma caixa de diálogo **Definir Associação de Grupo de Computadores**, com uma lista de grupos.

6.  Selecione o grupo para o qual deseja mover o computador e clique em **OK**.
