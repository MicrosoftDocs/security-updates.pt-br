---
TOCTitle: Usando cartões inteligentes para autenticar clientes
Title: Usando cartões inteligentes para autenticar clientes
ms:assetid: '5caacd67-fb16-46f1-b1ad-4aef0a632bf0'
ms:contentKeyID: 18123682
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747579(v=WS.10)'
---

Usando cartões inteligentes para autenticar clientes
====================================================

Se você estiver usando cartões inteligentes na sua organização para fornecer segurança adicional e controle sobre as credenciais do usuário, poderá então usá-los ao obter certificados de conta de direitos e licenças de uso do servidor RMS. Para configurar o servidor RMS a fim de exigir autenticação do cliente, você precisa habilitar a SSL para o site no qual configurou o RMS e configurar o método de autenticação no IIS (Internet Information Services). Você pode usar as seguintes etapas para executar essa tarefa:

1.  Abra o **Gerente dos Serviços de Informações da Internet**.
2.  Expanda o item do servidor, clique com o botão direito do mouse na pasta do site e depois clique em **Propriedades**.
3.  Clique na guia **Segurança de Diretório** e, na área **Comunicações de Segurança**, marque a caixa de seleção **Habilitar o mapeador do serviço de diretório do Windows**.
4.  Expanda a pasta do site, abra o diretório virtual **\_wmcs** e depois expanda o diretório virtual (**Licenciamento** ou **Certificação**) para o qual deseja configurar a autenticação.
    -   Para configurar a autenticação quando um usuário solicita uma licença de uso, clique com o botão direito do mouse no arquivo license.asmx e depois clique em **Propriedades**.
    -   Para configurar a autenticação quando um usuário solicita um certificado de usuário, clique com o botão direito do mouse no arquivo certification.asmx e depois clique em **Propriedades**.
5.  Clique na guia **Segurança de Arquivo** e, em seguida, na área **Comunicações de Segurança**, clique em **Editar** para abrir a caixa de diálogo **Comunicações de Segurança**.
6.  Selecione **Exigir canal de segurança (SSL)** e depois clique em um dos seguintes itens:
    -   **Exigir certificados de cliente**, se você deseja que apenas os clientes com certificados do lado do cliente, tais como cartões inteligentes, possam se conectar ao serviço.
    -   **Aceitar certificados de cliente**, se você deseja que os clientes tenham a opção de fornecer credenciais de autenticação usando um certificado de cartão inteligente ou um nome de usuário e senha.
7.  Selecione **Ativar mapeamento de certificado de cliente** e clique em **OK**.
8.  Caso você deseje usar a autenticação de cliente para a certificação e o licenciamento, repita esse procedimento, mas selecione o diretório virtual alternativo na segunda vez.

Depois que essas configurações tiverem sido definidas, quando um usuário tentar abrir conteúdo protegido pelo RMS e publicado por esse servidor, será mostrada uma mensagem solicitando que ele forneça suas credenciais de autenticação, a fim de que o servidor lhe conceda um certificado de conta de direitos ou licença de uso.
