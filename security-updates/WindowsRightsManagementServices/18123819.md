---
TOCTitle: Guia rápido de implantação
Title: Guia rápido de implantação
ms:assetid: 'b8fb69b6-3e0b-4836-8c05-8bd93f522a7c'
ms:contentKeyID: 18123819
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747735(v=WS.10)'
---

Guia rápido de implantação
==========================

Este guia tem o objetivo de ajudá-lo a configurar rapidamente um servidor RMS com Service Pack 1, o que lhe permitirá decidir se deseja realizar uma implantação em escala mais ampla em sua organização.

**Etapa 1 - Preparando para o RMS**

O RMS depende de outros componentes a serem instalados e configurados antes de usar o serviço. Sua infra-estrutura terá que suprir os requisitos básicos do RMS depois de cumpridas as seguintes etapas:

1.  Configure um computador que execute o Windows Server 2003 e inscreva-o em um domínio do Active Directory. (No caso de pequenas organizações que tenham somente um servidor, esse computador também pode ser o controlador do domínio do Active Directory. Entretanto, neste caso o computador precisa estar executando o Windows Server 2003, Standard Edition, o Windows Server 2003, Enterprise Edition ou o Windows Server 2003, Datacenter Edition. Um computador que execute o Windows Server 2003, Web Edition, não pode ser um controlador de domínio.)
2.  Configure o servidor para a função de **Servidor de Aplicativos**. Para isso, clique em **Iniciar**, clique duas vezes em **Painel de Controle** e clique duas vezes em **Adicionar ou Remover Programas**. Em **Adicionar ou Remover Programas**, clique em **Adicionar/Remover Componentes do Windows** e verifique se os seguintes serviços estão habilitados em **Servidor de Aplicativos**:
    -   **ASP.NET**
    -   **IIS (Serviços de Informações da Internet)**
    -   **Enfileiramento de Mensagens**

    Aceite as opções padrão para cada serviço. Não são necessárias configurações adicionais.
3.  Configure um servidor de banco de dados usando um dos seguintes aplicativos de banco de dados:
    -   Microsoft® SQL Server 2000 com SP3a. Pode ser uma instalação local do SQL Server 2000 ou uma instalação remota que esteja no mesmo domínio.
    -   Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Versão A. Deve ser uma instalação local. Você pode baixar o MSDE 2000 no [site da Microsoft](http://go.microsoft.com/fwlink/?linkid=17799) (http://go.microsoft.com/fwlink/?LinkID=17799).

    É recomendável que o Microsoft SQL Server Desktop Engine seja usado para oferecer suporte aos bancos de dados RMS somente em ambientes de teste, porque ele não inclui as ferramentas necessárias para ser totalmente funcional e oferecer suporte a um banco de dados de toda a empresa. Além disso, como o MSDE não oferece suporte a redes remotas, você deverá instalá-lo no mesmo servidor do RMS e não poderá adicionar servidores RMS extras ao cluster do RMS. Os termos de uso do Microsoft SQL Server Desktop Engine especificam que você não pode usar as ferramentas de cliente do SQL Server para manipular um banco de dados Microsoft SQL Server Desktop Engine. Com essa restrição, não será possível fazer backup e recuperar o banco de dados de configuração do RMS, exibir informações de log ou modificar os dados armazenados diretamente no banco de dados de configuração.
4.  Decida o nome pelo qual esse serviço deve ser conhecido quando os usuários tentarem se conectar a ele através da intranet (por exemplo, http://certificacao.contoso.com). Configure o DNS (nome de domínio) para resolver essa URL para o endereço IP do computador RMS. Você deve usar um nome de domínio DNS totalmente qualificado para a URL do cluster, a fim de garantir que os clientes de outras zonas de DNS sejam capazes de resolver o endereço IP do(s) servidor(es) RMS.
5.  Crie uma conta de administrador para ser usada com o RMS.
6.  Agora você está pronto para instalar o RMS SP1. Para obter mais instruções sobre essa etapa, consulte "Instalar o RMS com Service Pack 1" em "Operando um servidor RMS", nesta coleção de documentos.

**Recursos opcionais usados normalmente**

Os recursos apresentados a seguir são opcionais. Caso decida usá-los, certifique-se de fazer os preparativos necessários antes de iniciar o processo de instalação e de configuração do RMS.

-   Você pode configurar o RMS para usar um HSM (Módulo de segurança de hardware) para armazenar as chaves particulares. Se quiser utilizar um módulo de segurança de hardware, certifique-se de que os drivers estejam configurados corretamente e que o mundo de segurança esteja definido.
-   É possível baixar automaticamente um certificado de licenciante para servidor durante o processo de configuração, se seu computador RMS for capaz de se comunicar com a Internet. Se a sua organização usar um servidor proxy para se conectar à Internet, verifique as configurações de proxy no Internet Explorer, incluindo quaisquer requisitos de autenticação, e registre-as para uso futuro.
-   Se você for executar o RMS em um controlador de domínio e pretender usar uma conta de usuário para executar os serviços do RMS, verifique se a Diretiva de Segurança do Controlador de Domínio está configurada para conceder permissão de logon local à conta do usuário. Para obter mais informações sobre como configurar a Diretiva de Segurança do Controlador de Domínio, consulte o Centro de ajuda e suporte do Windows Server 2003.

**Etapa 2 - Configuração do primeiro servidor RMS**

A configuração é o processo de preparação de um site com o RMS para que os usuários possam começar a usar o serviço. Siga as etapas a seguir para configurar o servidor raiz de certificação de sua organização:

1.  Faça logon no computador como um usuário do domínio com privilégios locais de administrador. Se estiver instalando o RMS em um controlador de domínio, faça logon como administrador do domínio.
2.  Clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS** para abrir a página **Administração Global**. Essa página lista os sites disponíveis nesse servidor.
3.  Clique no site que deseja configurar com o RMS e clique em **Configurar o RMS neste site**. Quando a página se abrir, estará escrito **Configurar o Servidor Raiz de Certificação RMS** na parte superior.
4.  Preencha a página com as informações de sua organização.
    -   Na caixa **URL do Cluster**, digite o nome do serviço (tal como certificacao.contoso.com) configurado na etapa 4 do procedimento anterior. Se quiser usar SSL com sua instalação, clique no protocolo HTTPS na lista de protocolos. Ao fazer isso, o SSL é habilitado; entretanto, essa escolha não exigirá SSL para os serviços do RMS na Web. Isso deve ser configurado separadamente por meio do IIS.
    -   Se o servidor estiver conectado à Internet usando um servidor proxy, na área **Configurações de Proxy RMS**, preencha a seção com as informações registradas do Internet Explorer, conforme descrito na parte de recursos opcionais do procedimento anterior
    -   Na área **Conectividade com a Internet do Servidor**, selecione **Online** se desejar que o servidor se conecte ao Microsoft Enrollment Service usando a Internet e obtenha um certificado de licenciante para servidor automaticamente durante o processo de configuração. Selecione **Offline** se desejar se conectar manualmente ao Serviço de Inscrição da Microsoft, baixar o certificado de licenciante servidor e depois importá-lo após configurar o RMS.
5.  Clique em **Enviar**.
    Em aproximadamente 60 a 90 segundos, a configuração estará concluída com êxito, o que permite que você retorne à página **Administração Global**, onde é possível administrar o site recém-configurado.
6.  Na página **Administração Global**, selecione **Administrar o RMS neste site** para abrir a **Home page de Administração** do servidor RMS.
    Se tiver selecionado Offline em Conectividade com a Internet do Servidor na Etapa 4, complete o procedimento "Registrar manualmente um servidor raiz de certificação" antes de continuar.
7.  Na **Home Page de Administração**, clique no link Ponto de conexão de serviço do RMS.

> [!Note]  
> A próxima etapa deste procedimento — o registro de um ponto de conexão de serviço — requer o uso de uma conta de domínio que tenha privilégios suficientes para criar um objeto de recipiente abaixo do recipiente Serviços no recipiente de configuração da floresta do Active Directory. O grupo de segurança predefinido, **Administradores de Empresa**, é um exemplo de uma conta com os privilégios necessários. 

1.  Na página **Ponto de conexão de serviço do RMS**, clique no botão **Registrar URL**. Isso registra o ponto de conexão de serviço do RMS no Active Directory, para que aplicativos habilitados para RMS possam descobrir serviços de licenciamento, proxy de ativação e certificação do RMS. 

**Etapa 3 - Teste do RMS**

Para usar o RMS na sua totalidade, é necessário instalar o cliente do Microsoft Windows Rights Management Services e um aplicativo habilitado para RMS nos computadores clientes. Os usuários devem ser membros do domínio do Active Directory e os computadores clientes devem ser inscritos no domínio. Além disso, todos os usuários do domínio devem ter endereços de email configurados no Active Directory. Para testar o RMS:

1.  Faça logon no computador cliente como um usuário válido do domínio.
2.  Instale o cliente do RMS para Service Pack 1.
3.  Instale um aplicativo habilitado para RMS.
4.  Crie um arquivo protegido por RMS, forneça a todos os usuários direitos somente de leitura para esse arquivo e salve-o em uma pasta compartilhada à qual os usuários tenham acesso total.
5.  Faça logon no computador como outro usuário. Abra o arquivo e tente fazer alterações. Se o RMS estiver instalado corretamente, você não conseguirá fazer alterações no arquivo.
