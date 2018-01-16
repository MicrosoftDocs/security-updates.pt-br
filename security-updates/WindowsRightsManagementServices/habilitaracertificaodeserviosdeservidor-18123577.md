---
TOCTitle: Habilitar a certificação de serviços de servidor
Title: Habilitar a certificação de serviços de servidor
ms:assetid: '0ed78c85-7acb-4e3b-a594-613f8ccb5b14'
ms:contentKeyID: 18123577
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720196(v=WS.10)'
---

Habilitar a certificação de serviços de servidor
================================================

Para executar este procedimento, você deve estar conectado localmente ao site de administração com uma conta de usuário do domínio que seja membro do grupo Administradores. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Este procedimento só pode ser aplicado no cluster raiz.

Este procedimento pressupõe que você criou um grupo de usuários que contém as contas de usuário que os serviços do servidor representarão ao consumir conteúdo protegido por direitos.

Habilitando a certificação de serviços de servidor
--------------------------------------------------

#### Habilitar a certificação de serviços de servidor

1.  Faça logon no computador como membro do grupo Administradores local.

2.  Abra um navegador do sistema de arquivos e vá para a pasta &lt;unidade do sistema&gt;:\\Inetpub\\wwwroot\\\_wmcs\\Certificação.

3.  Para habilitar serviços do servidor a receberem certificados de conta de direitos, clique com o botão direito do mouse no arquivo ServerCertification.asmx e, em seguida, clique em **Propriedades**.

4.  Na guia **Segurança**, clique em **Adicionar** e adicione o grupo que você criou para essa categoria de usuários e o **Grupo de Serviço RMS**.

5.  Nas listas **Permissões** dos grupos, marque a caixa de seleção **Permitir** para as permissões **Ler e Executar** e clique em **OK**.

6.  As etapas de 1 a 4 devem ser repetidas para cada servidor do cluster.

> [!Note]  
> No caso do Microsoft Exchange Server 2007, você deve adicionar o objeto de computador do Active Directory de cada servidor bridgehead à DACL (lista de controle de acesso discricionário) de ServerCertification.asmx. Da mesma forma, no Microsoft Office SharePoint Server 2007 você deve adicionar o objeto de computador do Active Directory do servidor do Office SharePoint Server 2007 a essa DACL. É recomendável adicionar um grupo de segurança a essa DACL e também os objetos de computador apropriados a ela. 
