---
TOCTitle: Desinstalar o RMS
Title: Desinstalar o RMS
ms:assetid: '885e3b4f-ea32-466f-9f7f-d8440b0f7c28'
ms:contentKeyID: 18123675
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747587(v=WS.10)'
---

Desinstalar o RMS
=================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Desinstalando o RMS
-------------------

#### Desinstalar o RMS

1.  Faça logon no servidor no qual você deseja desinstalar o Windows RMS.

    > [!Important]  
    > Se estiver removendo o RMS de um servidor no cluster raiz de certificação, primeiro é preciso desconfigurá-lo indo até a página **Administração Global** e clicando em **Remover o RMS deste site**. Não é preciso desconfigurar um servidor de licenciamento antes de desinstalar o RMS dele.

2.  Abra **Adicionar ou Remover Programas** no **Painel de Controle**.

3.  Na caixa de diálogo **Adicionar ou Remover Programas**, clique em **Windows Rights Management Services** e depois clique em **Remover** para remover o RMS SP1.
