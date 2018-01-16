---
TOCTitle: Usando a página Administração Global
Title: Usando a página Administração Global
ms:assetid: '57bbf402-2351-4dee-823c-27f4dd32447c'
ms:contentKeyID: 18123677
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747575(v=WS.10)'
---

Usando a página Administração Global
====================================

Na página **Administração Global** do site de Administração, é possível configurar e desconfigurar um servidor RMS e alterar a conta de serviço RMS.

Para obter acesso a esta página a partir do servidor que deseja administrar, proceda da seguinte maneira:

1.  Faça logon como um administrador local.
2.  Clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Não é possível acessar a página **Administração Global** de um navegador que esteja em um computador remoto.

Se você ainda não tiver configurado o servidor do qual a página **Administração Global** está sendo acessada, as seguintes opções serão exibidas para cada site que estiver em execução no servidor:

-   **Configurar o RMS neste site**. Clique neste link se este for o primeiro servidor que deseja configurar neste cluster. Isso iniciará o processo de configuração durante o qual os recursos do RMS, como diretórios virtuais, são instalados. Além disso, os bancos de dados são instalados no servidor de banco de dados. Para obter mais informações, consulte "[Configurar o primeiro servidor raiz de certificação](https://technet.microsoft.com/debc42f3-74ff-4c99-b7a4-4921fccdabc2)", mais adiante neste tema.
-   **Adicionar o RMS a um cluster**. Clique neste link se desejar configurar o servidor e adicioná-lo a um cluster existente. Você pode unir um servidor ao cluster raiz de certificação ou a um cluster de licenciamento. Os recursos do RMS, como diretórios virtuais, são instalados. No entanto, os bancos de dados não são criados porque este servidor usará os bancos de dados do cluster. Para obter mais informações, consulte a seção "[Adicionar um servidor a um cluster](https://technet.microsoft.com/db635238-5528-4bec-9cc6-8244e2b3d733)", mais adiante neste tema.

Se você acessar a página **Administração Global** de um servidor que já foi configurado, as seguintes opções serão exibidas:

-   **Administrar o RMS neste site.** Clique neste link para exibir a página Administração do Cluster. Para obter mais informações, consulte a seção "[Usando a Home page de Administração](https://technet.microsoft.com/6c155977-bd0e-47d6-ac65-1746cddb505e)", mais adiante neste tema.
-   **Alterar a conta de serviço RMS.** Clique neste link para especificar uma conta de serviço RMS diferente sob a qual o RMS será executado. Para obter mais informações, consulte a seção "[Alterando a conta de serviço RMS](https://technet.microsoft.com/f257d66d-b823-41e4-bcb7-7c90eb295238)", mais adiante neste tema.
-   **Remover o RMS deste site.**Clique neste link para desconfigurar o RMS. Quando você desconfigura o RMS, os diretórios virtuais e os aplicativos dele são removidos deste servidor, mas o RMS não é desinstalado. Para obter mais informações, consulte "[Desinstalar o RMS](https://technet.microsoft.com/885e3b4f-ea32-466f-9f7f-d8440b0f7c28)", mais adiante neste tema.


> [!NOTE]  
> O site Administração do RMS usa janelas pop-up para a configuração de alguns recursos. Se você estiver usando um bloqueador de pop-ups com o navegador da Web, deve definir as configurações do navegador para permitir pop-ups do site Administração do RMS.
