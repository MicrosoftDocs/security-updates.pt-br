---
TOCTitle: Confiar em certificados de conta de direitos baseados no Passport
Title: Confiar em certificados de conta de direitos baseados no Passport
ms:assetid: 'c096fa36-c40d-4b28-843c-e9cbbe8eef70'
ms:contentKeyID: 18123756
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747655(v=WS.10)'
---

Confiar em certificados de conta de direitos baseados no Passport
=================================================================

A Microsoft oferece um serviço de certificação de conta que utiliza credenciais do Microsoft .NET Passport para estabelecer o certificado de conta de direitos para o usuário. Para que os usuários que possuem certificados de conta de direitos desse serviço possam obter licenças de uso do cluster do RMS, você precisa configurar um domínio de usuário confiável que aceite credenciais de usuário do serviço de certificação de conta da Microsoft.

Para usar esse recurso, é necessário configurar o IIS para permitir acesso anônimo ao serviço de licenciamento do RMS. Essa etapa é fundamental para usuários externos, uma vez que, por padrão, o serviço de licenciamento é configurado para usar a autenticação Integrada do Windows. Se o acesso anônimo não for definido, os usuários externos que possuem RACs (certificados de conta de direitos) baseados no Passport não conseguirão obter licenças.

Confiando em certificados de conta de direitos baseados no Passport
-------------------------------------------------------------------

#### Para habilitar o acesso anônimo ao serviço de licenciamento do RMS

1.  Abra o snap-in **Gerenciador dos Serviços de Informações da Internet (IIS)** e expanda o servidor que hospeda o RMS.

2.  Na árvore do console, expanda **Sites** e expanda o site no qual você configurou o RMS. Por padrão, esse é o **Site Padrão**.

3.  Na árvore do console, expanda o site **\_wmcs** e selecione o diretório virtual **licensing**.

4.  Clique com o botão direito do mouse no diretório virtual **licensing** e selecione **Propriedades**.

5.  Na caixa de diálogo **Propriedades de licensing**, clique na guia **Segurança de Diretório**.

6.  Clique em **Editar** na área **Autenticação e controle de acesso**.

7.  Marque a caixa de seleção **Ativar Acesso Anônimo**.

#### Confiar em certificados de conta de direitos baseados no Passport

1.  Abra a página **Administração Global** e, próximo ao site em que deseja confiar certificados de conta de direitos baseados no Passport (RACs), clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Diretivas de confiança**.

3.  Na área **Domínios de usuário confiáveis**, clique em **Confiar em RACs do Passport**. O Serviço de certificação RM da Microsoft aparece na lista **Domínio de usuário confiável**.

4.  Opcionalmente, é possível excluir usuários com base em seu endereço de email. Para isso, clique em **Identidades excluídas** e digite o endereço de email do usuário em quem você não confia.
