---
TOCTitle: Habilitar a administração remota do RMS
Title: Habilitar a administração remota do RMS
ms:assetid: '00f17054-5f5d-47e2-89c1-7a593b930bb3'
ms:contentKeyID: 18123565
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720181(v=WS.10)'
---

Habilitar a administração remota do RMS
=======================================

O Internet Explorer 6.0 ou posterior deve ser instalado no computador que está sendo usado para administração remota do RMS.

Habilitando a administração remota do RMS
-----------------------------------------

#### Habilitar a administração remota do RMS

1.  Faça logon no servidor que deseja poder administrar remotamente.

2.  Em **Ferramentas administrativas**, abra o snap-in do **Gerenciador dos Serviços de informações da Internet (IIS)**.

3.  Expanda o item que representa o site em que você configurou o RMS.

4.  Clique com o botão direito do mouse na pasta **\_wmcs** e clique em **Propriedades**. Na guia **Segurança de Diretório** sob **Comunicação segura**, clique em **Editar**, clique em **Exigir canal de segurança** e clique em **OK**. Isso aplica a proteção SSL (Secure Sockets Layer) para os serviços do RMS na Web. Para obter mais informações sobre como gerenciar sites da Web utilizando o IIS, consulte a Ajuda do IIS.

    | ![](images/Cc720181.Important(WS.10).gif)Importante                                                                                                                                                                                                            |
    |---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | Você pode proteger os serviços RMS na Web com SSL para obter segurança adicional e habilitar o acesso HTTP remoto às páginas de Administração do RMS na Web. Se você pretende habilitar SSL para os serviços do RMS na Web, obtenha e instale um certificado válido de servidor SSL da Web. |

5.  Clique com o botão direito do mouse na pasta **Admin** e clique em **Propriedades**. Na guia **Segurança de Diretório**, sob **Restrições de endereço IP e nome de domínio**, clique em **Editar** e, sob **Restrições de acesso de endereço IP**, clique em **Acesso concedido** para permitir que todos os computadores solicitem uma conexão com esse site.
