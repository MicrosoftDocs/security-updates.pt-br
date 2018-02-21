---
TOCTitle: Especificar o contato administrativo
Title: Especificar o contato administrativo
ms:assetid: '31777458-5530-4ae0-ac1f-131b3d98dd35'
ms:contentKeyID: 18123621
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720237(v=WS.10)'
---

Especificar o contato administrativo
====================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

O administrador especificado nesse procedimento deve ser um administrador local no servidor raiz de certificação porque o usuário conectado deve ter permissões no arquivo SubEnrollService.asmx do servidor raiz de certificação para configurar um servidor de licenciamento. Caso o usuário que estiver tentando configurar um servidor de licenciamento não tenha permissões nesse arquivo, ele poderá enviar uma solicitação ao administrador designado para essa operação para conceder à conta de usuário as permissões necessárias. Para obter mais informações, consulte [Configurando permissões no arquivo de serviço de sub-registro](https://technet.microsoft.com/737bb69b-fe26-4057-9569-e632f7bbf295), já mencionado neste tema.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Especificando o contato administrativo
--------------------------------------

#### Especificar o contato administrativo

1.  Abra a página **Administração Global** e, próximo ao site em que deseja especificar um contato administrativo, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Configurações de certificação**.

3.  Na área **Contato administrativo**, digite o endereço de email do administrador a contatar em caso de problemas de sub-registro durante a configuração de um servidor de licenciamento, na forma *nome\_usuário*@*nome\_domínio*.com.

4.  Na parte inferior da página, clique em **Enviar**.
