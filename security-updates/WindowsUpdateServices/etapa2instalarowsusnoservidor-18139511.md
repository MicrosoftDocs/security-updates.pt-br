---
TOCTitle: 'Etapa 2: instalar o WSUS no servidor'
Title: 'Etapa 2: instalar o WSUS no servidor'
ms:assetid: 'f593532c-e92e-47f3-914a-38a6c2519e94'
ms:contentKeyID: 18139511
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708622(v=WS.10)'
---

Etapa 2: instalar o WSUS no servidor
====================================

Depois de revisar os requisitos de instalação, você estará pronto para instalar o WSUS. Você deve fazer logon no servidor em que pretende instalar o WSUS usando uma conta que seja membro do grupo Administradores local. Somente membros do grupo Administradores local podem instalar o WSUS.

O procedimento a seguir usa as opções de instalação padrão do WSUS para o Windows Server 2003, que incluem a instalação do Windows SQL Server 2000 Desktop Engine (WMSDE) como o software de banco de dados do WSUS, o armazenamento local de atualizações e o uso do site padrão do IIS na porta 80. Você pode encontrar os procedimentos para as opções de instalação personalizada, como o uso de um sistema operacional diferente, o software de banco de dados diferente ou um site que use um número de porta personalizado, no informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês).

**Para instalar o WSUS no Windows Server 2003**
1.  Clique duas vezes no arquivo de instalação **WSUSSetup.exe**.

    | ![](images/Cc708622.note(WS.10).gif)Observação                                                                                                                                                                               |
    |-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | A versão mais recente do arquivo WSUSSetup.exe está disponível no [site da Microsoft](http://go.microsoft.com/fwlink/?linkid=47374) de Windows Server Update Services em http://go.microsoft.com/fwlink/?LinkId=47374 (o documento pode estar em inglês). |

2.  Na página de **Bem-vindo** do assistente, clique em **Avançar**.

3.  Leia atenciosamente os termos do Contrato de Licença, clique em **Aceito os termos do Contrato de Licença** e, em seguida, clique em **Avançar**.

4.  Na página **Selecionar a Origem de Atualização**, você pode especificar onde os cliente obtêm as atualizações. Se você marcar a caixa de seleção **Armazenar Atualizações Localmente**, as atualizações serão armazenadas no servidor do WSUS e você selecionará um local no sistema de arquivos para armazenar as atualizações. Se você não armazenar as atualizações localmente, os computadores cliente se conectarão ao Microsoft Update para obter atualizações aprovadas.

    Mantenha as opções padrão e clique em **Avançar**.

    ![](images/Cc708622.fa6ac6a6-6814-4b7e-96e8-e08af5e534b8(WS.10).gif)

5.  Na página **Opções de Banco de Dados**, selecione o software usado para gerenciar o banco de dados do WSUS. Por padrão, o WSUS se oferece para instalar o WMSDE se o computador no qual você está instalado executar o Windows Server 2003.

    Se você não puder usar o WMSDE, forneça uma instância do SQL Server a ser usada pelo WSUS, clicando em **Usar o servidor de banco de dados existente neste computador** e digitando o nome da instância na caixa **Nome da instância SQL**. Para obter mais informações sobre as opções de software de banco de dados além do WMSDE, consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês).

    Mantenha as opções padrão e clique em **Avançar**.

    ![](images/Cc708622.bc0b73ad-b338-437c-a3c7-0299e819840d(WS.10).gif)

6.  Na página **Seleção do Site**, especifique o site a ser usado pelo WSUS. Essa página também lista duas URLs importantes baseadas nessa seleção: a URL para a qual os computadores cliente serão direcionados para obter as atualizações e a URL para o console do WSUS onde o WSUS será configurado.

    Se você já tiver um site na porta 80, talvez seja necessário criar o site do WSUS em uma porta personalizada. Para obter mais informações sobre a execução do WSUS em uma porta personalizada, consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês).

    Mantenha a opção padrão e clique em **Avançar**.

    ![](images/Cc708622.64ed7643-a050-4f54-bf9f-04cf7931adc0(WS.10).gif)

7.  Na página **Espelhar Configurações de Atualização**, você pode especificar a função de gerenciamento desse servidor do WSUS. Se esse for o primeiro servidor do WSUS na rede ou se você desejar uma topologia de gerenciamento distribuído, pule essa tela.

    Se desejar uma topologia de gerenciamento centralizado e esse não for o primeiro servidor do WSUS na rede, marque a caixa de seleção e digite o nome de outro servidor do WSUS na caixa **Nome do Servidor**. Para obter mais informações sobre as funções de gerenciamento, consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês).

    Mantenha a opção padrão e clique em **Avançar**.

    ![](images/Cc708622.f26e09d5-983c-418d-8511-8960850403ef(WS.10).gif)

8.  Na página **Pronto para Instalar o Windows Server Update Services**, revise as seleções e clique em **Avançar**.

    ![](images/Cc708622.20de7d09-3d30-4867-9253-6f353dd1923d(WS.10).gif)

9.  Se a página final do assistente confirmar que a instalação do WSUS foi concluída com êxito, clique em **Concluir**.
