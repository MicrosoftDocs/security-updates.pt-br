---
TOCTitle: Usando a Home page de Administração
Title: Usando a Home page de Administração
ms:assetid: '6c155977-bd0e-47d6-ac65-1746cddb505e'
ms:contentKeyID: 18123625
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720290(v=WS.10)'
---

Usando a Home page de Administração
===================================

Na **Home page de Administração**, é possível exibir informações sobre o servidor ou cluster e obter acesso às opções de administração. Essa página estará disponível somente depois que o servidor estiver configurado.

Para obter acesso a esta página a partir do servidor que deseja administrar, proceda da seguinte maneira:

1.  Faça logon como um administrador local.
2.  Clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e selecione **Administração do Windows RMS**.
3.  Na página **Administração Global**, clique em **Administrar o RMS neste site**.

Se você tiver habilitado a administração remota usando SSL (Secure Sockets Layer), será possível também acessar a **Home page de Administração** de um computador diferente, por meio da execução das seguintes etapas:

1.  Na barra de endereços do navegador da Web, digite a seguinte URL:
    https://*nome\_do\_cluster:número\_da\_porta*/\_wmcs/admin
    Em que *nome\_do\_cluster:número\_da\_porta* é a URL especificada para este cluster durante a configuração. Forneça o número da porta somente se tiver especificado um número de porta diferente da porta padrão 80.
2.  Quando solicitado, digite as credenciais de um administrador local no servidor que você está acessando.

A **Home Page de Administração** exibe informações sobre o cluster, como a URL do cluster, o nome e o local do banco de dados, a data de vencimento do certificado de licenciante para servidor e assim por diante. Ela também fornece links para páginas onde é possível configurar as seguintes opções de administração do cluster:

-   **Diretivas de confiança.** Adicionar e remover domínios confiáveis. Para obter mais informações, consulte "[Gerenciando confiança e diretiva de confiança](https://technet.microsoft.com/1c96ee74-fd28-4511-be21-087e2b04c3ee)", mais adiante neste tema.
-   **Modelos de diretiva de direitos**. Criar e modificar modelos de diretiva de direitos. Para obter mais informações, consulte "[Gerenciando modelos de diretiva de direitos](https://technet.microsoft.com/718286dc-3399-4556-96c9-ec3a33d31877)", mais adiante neste tema.
-   **Configurações de registro**. Ativar e desativar o registro e exibir o nome do servidor e do banco de dados de log. Para obter mais informações, consulte "[Gerenciando o log](https://technet.microsoft.com/8fccfc57-2135-494e-8e44-f6191bf5e4a0)", mais adiante neste tema.
-   **Configurações da URL do cluster da extranet.** Especificar uma URL disponível externamente para solicitações de licenciamento e certificação de conta. Para obter mais informações, consulte "[Configurando uma URL de extranet](https://technet.microsoft.com/88fec9ff-c96c-4d20-8856-0485e7507572)", mais adiante neste tema.
-   **Configurações de proxy RMS.** Especificar o endereço do servidor proxy, o tipo de autenticação e o nome de usuário a serem usados quando o servidor RMS precisar se conectar à Internet usando um servidor proxy. Para obter mais informações, consulte "[Preparando as configurações de proxy RMS](https://technet.microsoft.com/179d2970-62e9-4487-aa5b-f4334234991e)", mais adiante neste tema.
-   **Configurações de segurança.** Redefinir a senha da chave particular do servidor, especificar o grupo de superusuários cujos membros podem descriptografar todo o conteúdo licenciado e descomissionar o RMS. Para obter mais informações, consulte "[Gerenciando a segurança ao operar o RMS](https://technet.microsoft.com/62050812-de4f-4392-8d63-f2f89aa01ed4)", mais adiante neste tema.
-   **Configurações de certificação.** Especificar o período de validade dos certificados de conta de direitos e especificar um contato administrativo. (Esta opção está disponível somente no cluster raiz de certificação, não em servidores de licenciamento.) Para obter mais informações, consulte "[Gerenciando certificados de conta de direitos](https://technet.microsoft.com/49c5c2ba-e197-4e4b-b3b3-b3248f068bcc)", mais adiante neste tema.
-   **Diretivas de exclusão.** Especificar exclusão com base na versão do cofre, no certificado da conta de direitos, na versão do Windows ou no aplicativo habilitado para RMS. Para obter mais informações, consulte "[Gerenciando diretivas de exclusão](https://technet.microsoft.com/ee31e099-e095-4648-95da-0009fbeb48cb)", mais adiante neste tema.
-   **Relatório de certificação de conta RM.** Exibir o número de certificados de conta de direitos que foram emitidos. (Esta opção está disponível somente no cluster raiz de certificação, não em servidores de licenciamento.) Para obter mais informações, consulte "[Controlando certificados de conta de direitos](https://technet.microsoft.com/5bb0f3cf-fc44-4e60-a93f-c789d6f8a902)", mais adiante neste tema.

Os tópicos restantes desta seção descrevem como usar esses recursos. Para obter instruções detalhadas, consulte a seção “[Como ...](https://technet.microsoft.com/82032075-f361-438f-a2c4-93ab29ae6cff)” mais adiante neste tema

| ![](images/Cc720290.note(WS.10).gif)Observação                                                                                                                                                                                   |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| O site Administração do RMS usa janelas pop-up para a configuração de alguns recursos. Se você estiver usando um bloqueador de pop-ups com o navegador da Web, deve definir as configurações do navegador para permitir pop-ups do site Administração do RMS. |
