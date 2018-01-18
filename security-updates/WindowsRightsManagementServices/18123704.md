---
TOCTitle: Habilitar a certificação de dispositivos móveis
Title: Habilitar a certificação de dispositivos móveis
ms:assetid: '93ec088e-9056-4c3c-bd97-1173fb194578'
ms:contentKeyID: 18123704
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747603(v=WS.10)'
---

Habilitar a certificação de dispositivos móveis
===============================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Esse procedimento pode ser aplicado somente no cluster raiz de certificação.

Esse procedimento pressupõe que você criou um grupo de usuários que contém as contas de usuários de dispositivo móvel que consomem conteúdo protegido pelo RMS.

Habilitando a certificação de dispositivos móveis
-------------------------------------------------

#### Habilitar a certificação de dispositivos móveis

1.  No servidor raiz de certificação, abra um navegador do sistema de arquivos e vá para a pasta &lt;unidade de sistema&gt;:\\Inetpub\\wwwroot\\\_wmcs\\Certificação.

2.  Para habilitar dispositivos móveis a receberem certificados de conta de direitos, clique com o botão direito do mouse no arquivo **MobileDeviceCertification.asmx** e, em seguida, clique em Propriedades.

3.  Na guia **Segurança**, clique em **Adicionar** e adicione o grupo que você criou para essa categoria de usuários e o **Grupo de Serviço RMS**.

4.  Na lista **Permissões** dos grupos, marque a caixa de seleção **Permitir** para as permissões **Leitura** e **Leitura & Execução** e clique em **OK**.
