---
TOCTitle: 'Etapa 2: Instalar o WSUS 3.0 no servidor'
Title: 'Etapa 2: Instalar o WSUS 3.0 no servidor'
ms:assetid: '191e62a0-7671-41eb-9841-17c64313fa68'
ms:contentKeyID: 18139065
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720469(v=WS.10)'
---

Etapa 2: Instalar o WSUS 3.0 no servidor
========================================

Após verificar se o servidor atende aos requisitos da instalação, você estará pronto para instalar o WSUS 3.0. Você deve fazer logon no servidor no qual pretende instalar o WSUS 3.0 usando uma conta que seja membro do grupo Administradores local. Somente membros do grupo Administradores local podem instalar o WSUS 3.0.

O procedimento a seguir usa as opções de instalação padrão do WSUS, que incluem a instalação do Windows Internal Database para o software de banco de dados do WSUS 3.0, o armazenamento de atualizações localmente e a utilização do site padrão do IIS na porta 80.

**Para instalar o WSUS 3.0**
1.  Clique duas vezes no arquivo instalador, **WSUSSetup.exe**.

2.  Na página **Bem-vindo** do assistente de instalação, clique em **Avançar**.

3.  Na página **Seleção do Modo de Instalação**, clique em **Instalação completa do servidor incluindo o Console de Administração** se quiser instalar o servidor no computador ou em **Somente Console de Administração** se quiser instalar somente o console de administração.

4.  Na página **Contrato de Licença**, leia os termos do contrato de licença cuidadosamente, clique em **Aceito os termos do Contrato de licença** e clique em **Avançar**.

    ![](images/Cc720469.fa6ac6a6-6814-4b7e-96e8-e08af5e534b8(WS.10).gif)

5.  Na página **Selecionar a Origem de Atualização** do assistente de instalação, você pode especificar de onde os clientes obtêm as atualizações. Se você marcar a caixa de seleção **Armazenar atualizações localmente**, as atualizações serão armazenadas no servidor do WSUS 3.0 e você selecionará um local no sistema de arquivos para armazenar as atualizações. Se você não armazenar as atualizações localmente, os computadores cliente se conectarão ao Microsoft Update para obter atualizações aprovadas. Mantenha as opções padrão e clique em **Avançar**.

    ![](images/Cc720469.c8bac396-ca39-4491-8b0c-742a0e470535(WS.10).gif)

6.  Na página **Opções de Banco de Dados**, selecione o software usado para gerenciar o banco de dados do WSUS 3.0. Por padrão, a Instalação do WSUS se oferece para instalar o Windows Internal Database se o computador no qual você está instalando executar o Windows Server 2003.

7.  Se não quiser usar o Windows Internal Database, forneça uma instância do SQL Server para o WSUS usar clicando em **Usar** **um servidor de banco de dados existente neste computador** e digitando o nome da instância na caixa. O nome da instância deve ser exibido como &lt;*nome\_do\_servidor*&gt;\\&lt;*nome\_da\_instância*&gt;, onde *nome\_do\_servidor* é o nome do servidor e *nome\_da\_instância* é o nome da instância SQL. Faça sua seleção e clique em **Avançar**.

8.  Na página **Conectando à Instância do SQL Server**, o WSUS tentará se conectar à instância especificada do SQL Server. Quando tiver se conectado com êxito, clique em **Avançar** para continuar.

    ![](images/Cc720469.36c6af0c-a61e-4151-ae50-c754a106cb1b(WS.10).gif)

9.  Na página **Seleção do Site**, especifique o site a ser usado pelo WSUS 3.0. Se quiser usar o site padrão do IIS na porta 80, selecione a primeira opção. Se você já tiver um site na porta 80, poderá criar um site alternativo na porta 8530 selecionando a segunda opção. Mantenha a opção padrão e clique em **Avançar**.

10. Na página **Pronto para Instalar o Microsoft Windows Server Update Services 3.0**, revise as seleções e clique em **Avançar**.

11. A página final do assistente de instalação informará se a instalação do WSUS 3.0 foi concluída com êxito ou não. Depois de clicar em **Concluir**, o assistente de configuração será inicializado.
