---
TOCTitle: Excluir aplicativos
Title: Excluir aplicativos
ms:assetid: '422f2ddd-bcf4-45f1-905a-b8bad30fd7dd'
ms:contentKeyID: 18123640
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720262(v=WS.10)'
---

Excluir aplicativos
===================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

As diretivas de exclusão são aplicadas pelo cliente no momento em que a licença de uso é vinculada ao conteúdo protegido.

Excluindo aplicativos ou parando de excluir aplicativos
-------------------------------------------------------

#### Excluir aplicativos

1.  Abra a página **Administração Global** e próximo ao site em que deseja controlar quais versões de aplicativos podem ser utilizadas com o conteúdo protegido por direitos, clique em **Administrar o RMS neste site**.

2.  Na área **Links** de **Administração**, clique em **Diretivas de exclusão**.

3.  Na área **Exclusão de aplicativo**, clique em **Habilitar** para excluir um aplicativo ou componente ativado pelo RMS.

    Para desabilitar a exclusão do aplicativo, clique em **Desabilitar**.

4.  Digite o nome do arquivo do aplicativo ou componente a ser excluído, digite as versões mínima e máxima a serem excluídas (no formato *x*.*x*.*x*.*x*) e clique em **Excluir este aplicativo**.

    Para excluir um aplicativo (ou componente) da lista de exclusão, selecione o nome do arquivo e clique em **Excluir aplicativos selecionados da lista de exclusão**.

    > [!Note]  
    > O RMS exige que a versão do aplicativo seja especificada em um formato de 4 dígitos delimitados por pontos (\#.\#.\#.\# ). No entanto, alguns aplicativos especificam sua versão com números de 2 ou 3 dígitos delimitados por pontos. Nesse caso, você deve acrescentar um .0, se necessário, para fazer com que o número da versão corresponda ao formato exigido pelo RMS.

#### Parar de excluir aplicativos

1.  Abra a página **Administração Global** e próximo ao site em que deseja controlar quais versões de aplicativos podem ser utilizadas com o conteúdo protegido por direitos, clique em **Administrar o RMS neste site**.

2.  Na área **Links** de **Administração**, clique em **Diretivas de exclusão**.

3.  Na área **Exclusão de aplicativo**, clique em **Desabilitar**.

Para obter mais informações sobre a execução desse procedimento, consulte "[Excluindo aplicativos](https://technet.microsoft.com/b68ae4b2-b9ba-44ae-90cb-c88df600ec86)", já mencionado neste tema.
