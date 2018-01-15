---
TOCTitle: 'Etapa 6: Configurar grupos de computadores'
Title: 'Etapa 6: Configurar grupos de computadores'
ms:assetid: '70518732-2179-4e41-9609-7f9999867f41'
ms:contentKeyID: 21798809
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Dd939860(v=WS.10)'
---

Etapa 6: Configurar grupos de computadores
==========================================

Os grupos de computadores são uma parte importante das implantações do Windows Server Update Services 3.0 Service Pack 2 (WSUS 3.0 SP2). Os grupos de computadores permitem testar e direcionar atualizações para computadores específicos.Há dois grupos de computadores padrão: Todos os Computadores e Computadores Não Atribuídos. Por padrão, quando cada computador cliente faz um contato inicial com o servidor do WSUS, o servidor adiciona o computador cliente a cada um desses grupos.

Você pode criar quantos grupos de computadores personalizados precisar para gerenciar as atualizações em sua organização. Recomendamos criar pelo menos um grupo de computadores para testar as atualizações antes de implantá-las em outros computadores da organização.

Procedimentos da etapa 6
------------------------

1.  Criar um grupo de computadores de teste.
2.  Mova pela menos um computador para o grupo de teste.

**Para criar um grupo**
1.  No Console de Administração do WSUS, expanda **Computadores** e selecione **Todos os Computadores**.

2.  Clique com o botão direito em **Todos os Computadores** e clique em **Adicionar Grupo de Computadores**.

3.  Na caixa de diálogo **Adicionar Grupo de Computadores**, especifique o **Nome** do novo grupo de testes e clique em **Adicionar**.

No próximo procedimento, você designará um computador cliente ao grupo de teste. Um computador de teste é qualquer computador que tenha software e hardware consistente com a maioria dos computadores clientes na rede, ainda que não designado para uma função crítica. Após testes bem-sucedidos, você poderá aprovar as atualizações para computadores nos grupos de sua escolha.

**Para atribuir um computador ao grupo de teste**
1.  No Console de Administração do WSUS, clique em **Computadores**.

2.  Clique no grupo do computador que você deseja designar ao grupo de teste.

3.  Na lista de computadores, selecione o computador ou computadores que você deseja designar ao grupo de teste.

4.  Clique com o botão direito do mouse em **Alterar Associação**.

5.  Na caixa de diálogo **Definir afiliação ao grupo de computadores**, selecione o grupo de teste criado anteriormente e, então, clique em **OK**.

Repita esses dois procedimentos, ou seja, crie um grupo e, então, designe os computadores ao grupo para criar quantos grupos de computadores adicionais forem necessários para gerenciar as atualizações em seu local.

Próxima etapa
-------------

[Etapa 7: Aprovar e implantar atualizações WSUS](https://technet.microsoft.com/c4e58e17-d5e3-4194-8f26-b459e0c03b86).

Recursos adicionais
-------------------

[Guia passo a passo para o Windows Server Update Services 3.0 SP2](https://technet.microsoft.com/4b504edc-93b3-45b0-a7e8-d0107f1a4442)
