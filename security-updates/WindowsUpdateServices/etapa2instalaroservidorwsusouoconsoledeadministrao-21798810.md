---
TOCTitle: 'Etapa 2: Instalar o Servidor WSUS ou o Console de Administração'
Title: 'Etapa 2: Instalar o Servidor WSUS ou o Console de Administração'
ms:assetid: '6db6fcb0-c55d-43b9-9b07-4040c6267759'
ms:contentKeyID: 21798810
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Dd939859(v=WS.10)'
---

Etapa 2: Instalar o Servidor WSUS ou o Console de Administração
===============================================================

Após assegurar que o servidor atenda aos requisitos mínimos do sistema e que as permissões de conta necessárias foram concedidas, você estará pronto para instalar o Windows Server Upgrade Services 3.0 Service Pack 2 (WSUS 3.0 SP2). Inicie a instalação do WSUS 3.0 SP2 usando o procedimento aplicável a seu sistema operacional e o tipo de instalação (usando o Gerenciador de Servidores ou o arquivo WUSSetup.exe).

Se você estiver usando o Gerenciador de Servidores
--------------------------------------------------

**Para iniciar a instalação do WSUS 3.0 SP2 Server usando o Gerenciador de Servidores**
1.  Você deve fazer logon no servidor em que pretende instalar o WSUS 3.0 SP2 usando uma conta que seja membro do grupo Administradores Locais.

2.  Clique em **Iniciar**, aponte para **Ferramentas Administrativas** e clique em **Gerenciador de Servidores**.

3.  No painel do lado direto da janela do Gerenciador de Servidores, na seção Resumo de Funções, clique em **Adicionar Funções**.

4.  Se a página Antes de Começar aparecer, clique **Avançar**.

5.  Na página Selecioner Funções de Servidor, selecione **Windows Server Update Services**.

6.  Na página Windows Server Update Services, clique em **Avançar**.

7.  Na página Confirme as Seleções de Instalação, clique em **Instalar**.

8.  Quando o Assistente de Configuração do WSUS 3.0 SP2 for iniciado, ignore a próxima seção e consulte o procedimento "Para continuar a instalação do WSUS 3.0 SP2".

Se você estiver usando o arquivo WUSSetup.exe
---------------------------------------------

**Para iniciar a instalação do Servidor WSUS 3.0 SP2 ou do Console de Administração WSUS 3.0 Sp2 usando o WUSSetup.exe file**
1.  Você deve fazer logon no servidor em que pretende instalar o WSUS 3.0 SP2 usando uma conta que seja membro do grupo Administradores Locais.

2.  Clique duas vezes no arquivo de instalação **WSUSSetup.exe**.

3.  Quando o Assistente de Configuração do Windows Server Update Services 3.0 SP2 for iniciado, consulte o procedimento “Para continuar a instalar o WSUS 3.0 SP2”

Usando o Assistente de Configuração do WSUS 3.0 SP2
---------------------------------------------------

O Assistente de Configuração do WSUS é iniciado do Gerenciador de Servidores ou do arquivo WUSSetup.exe.

**Para continuar a instalar o WSUS 3.0 SP2**
1.  Na página de boas-vindas do Assistente de Configuração do Windows Server Update Services 3.0, clique em **Avançar**.

2.  Na página Seleção do Modo de Instalação, selecione **Instalação completa do servidor incluindo o Console de Administração**, se desejar instalar o servidor WSUS nesse computador ou **Apenas Console de Administração**, se quiser instalar apenas o console de administração.

3.  Na página do Contrato de Licença, leia atenciosamente os termos, clique em **Aceito os termos do Contrato de Licença** e, em seguida, clique em **Avançar**.

4.  Você pode especificar onde os clientes obterão as atualizações na página Selecionar Origem da Atualização do assistente de instalação. Por padrão, a caixa de seleção **Armazenar atualizações localmente** estará marcada e as atualizações serão armazenadas no servidor WSUS no local especificado. Se você desmarcar a caixa de seleção **Armazenar atualizações automaticamente**, os computadores clientes obterão atualizações aprovadas por meio da conexão ao Microsoft Update. Faça sua seleção e, então, clique em **Avançar**.

5.  Na página Opções de Banco de Dados, selecione o software usado para gerenciar o banco de dados WSUS 3.0. Por padrão, o assistente de instalação oferece a instalação do Banco de Dados Interno do Windows.

    Se você não quiser usar o Banco de Dados Interno do Windows, forneça uma instância do SQL Server for WSUS selecionando **Usar um servidor de banco de dados existente neste computador** ou **Usar servidor de banco de dados existente em um computador remoto**. Digite o nome da instância na caixa aplicável.O nome da instância deve ser exibido como &lt;*nome\_do\_servidor*&gt;\\&lt;*nome\_da\_instância*&gt;, onde *nome\_do\_servidor* é o nome do servidor e *nome\_da\_instância* é o nome da instância SQL. Faça sua seleção e clique em **Avançar**.

6.  Se você tiver optado por se conectar a um SQL Server, na página **Conectar a uma Instância do SQL Server**, o WSUS tentará se conectar à instância especificada do SQL Server. Quando tiver se conectado com êxito, clique em **Avançar** para continuar.

7.  Na página Seleção de Site Web, especifique o site Web que o WSUS usará. Se você quiser usar o site Web padrão na porta 80, selecione **Usar o site Web IIS padrão**. Se você já tiver um site Web na porta 80, você poderá criar um site alternativo na porta 8520 selecionando **Criar um site da Web do Windows Server Update Services 3.0 SP2**. Clique em **Avançar**.

8.  Na página **Pronto para Instalar o Microsoft Windows Server Update Services 3.0**, revise as seleções e clique em **Avançar**.

9.  A página final do assistente de instalação permitirá que você saiba que a instalação do WSUS foi bem-sucedida. Após que você clicar em **Concluir** o assistente de configuração será iniciado.

Próxima etapa
-------------

[Etapa 3: Configurar as conexões de rede](https://technet.microsoft.com/42a144c5-f08e-4a6e-b360-47ddea77bd24).

Recursos adicionais
-------------------

[Guia passo a passo para o Windows Server Update Services 3.0 SP2](https://technet.microsoft.com/4b504edc-93b3-45b0-a7e8-d0107f1a4442)
