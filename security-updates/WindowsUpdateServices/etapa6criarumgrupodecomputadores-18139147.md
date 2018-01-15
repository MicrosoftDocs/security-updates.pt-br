---
TOCTitle: 'Etapa 6: criar um grupo de computadores'
Title: 'Etapa 6: criar um grupo de computadores'
ms:assetid: '6039e5dc-d2ce-4d4b-b737-17ebcadbd4a7'
ms:contentKeyID: 18139147
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720536(v=WS.10)'
---

Etapa 6: criar um grupo de computadores
=======================================

Os grupos de computadores são uma parte importante da implantação do WSUS, mesmo em implantações básicas. Os grupos de computadores permitem direcionar as atualizações para computadores específicos. Há dois grupos de computadores padrão: Todos os Computadores e Computadores Não Atribuídos. Por padrão, quando cada computador cliente faz um contato inicial com o servidor do WSUS, o servidor o adiciona a esses dois grupos.

Você pode criar grupos de computadores personalizados. Um dos benefícios de criar os grupos de computadores é poder testar as atualizações antes de implantá-las de forma abrangente. Se o teste for bem-sucedido, você poderá passar as atualizações para o grupo Todos os Computadores. Não há limite para o número de grupos personalizados que podem ser criados.

A configuração dos grupos de computadores é um processo de três etapas. Primeiro, especifique como você atribuirá os computadores aos grupos de computadores. Há duas opções: *destino do lado do servidor* e *destino do lado do cliente*. O destino do lado do servidor envolve a adição manual de cada computador ao seu grupo usando o WSUS. O destino do lado do cliente envolve a adição automática dos clientes usando a Diretiva de Grupo ou as chaves do Registro. Depois, crie o grupo de computadores no WSUS. Por último, mova os computadores para os grupos usando qualquer método selecionado na primeira etapa.

Este documento explica como usar o destino do lado do servidor e mover manualmente os computadores para seus grupos usando o console do WSUS. Se você tivesse vários computadores cliente a serem atribuídos a grupos de computadores, poderia usar o destino do lado do cliente, que automatizaria a movimentação dos computadores para os grupos de computadores.

Você pode usar a Etapa 6 para configurar um grupo de testes que contém pelo menos um computador de teste.

Essa etapa é composta pelos seguintes procedimentos:

-   Especificar o destino do lado do servidor.
-   Criar um grupo.
-   Mover os computadores para o grupo.

**Para especificar o método para atribuir computadores a grupos**
1.  Na barra de ferramentas do console do WSUS, clique em **Opções** e em **Opções de Computador**.

2.  Na caixa **Opções de Computador**, clique em **Usar a tarefa Mover Computadores no Windows Server Update Services**.

3.  Em **Tarefas**, clique em **Salvar Configurações** e clique em **OK** quando a caixa de confirmação for exibida.

**Para criar um grupo**
1.  Na barra de ferramentas do console do WSUS, clique em **Computadores**.

2.  Em **Tarefas**, clique em **Criar um grupo de computadores**.

3.  Na caixa **Nome do Grupo**, digite **Test** e clique em **OK**.

Use o procedimento a seguir para atribuir um computador cliente apropriado para testar o grupo de teste. Um computador cliente apropriado para teste é qualquer computador com software e hardware que represente a maioria dos computadores na rede, mas não um computador atribuído a uma função crítica. Dessa forma, baseado no computador de teste, você poderá informar como será o comportamento dos computadores com as atualizações que aprovar.

**Para adicionar manualmente um computador ao grupo Teste**
1.  Na barra de ferramentas do console do WSUS, clique em **Computadores**.

2.  Na caixa **Grupos**, clique no grupo do computador a ser movido.

3.  Na lista de computadores, clique no computador a ser movido.

4.  Em **Tarefas**, clique em **Mover o computador selecionado**.

5.  Na lista **Grupo de Computadores**, selecione o grupo para o qual deseja mover o computador e clique em **OK**.
