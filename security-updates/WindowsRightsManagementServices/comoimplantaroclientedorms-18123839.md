---
TOCTitle: Como implantar o cliente do RMS
Title: Como implantar o cliente do RMS
ms:assetid: 'c84f1724-cf71-4385-9003-ff68bc23c927'
ms:contentKeyID: 18123839
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747749(v=WS.10)'
---

Como implantar o cliente do RMS
===============================

Se você estiver usando o Microsoft Windows XP ou o Microsoft Windows 2000, o cliente do RMS (Rights Management Services) deve ser instalado para que você possa usar qualquer recurso do RMS, como o Gerenciamento de Direitos de Informação do Microsoft® Office System 2003 e o Complemento do Rights Management para o Internet Explorer. O cliente do RMS está incorporado ao Windows Vista®.

Várias organizações optam por controlar a implantação do software cliente na própria organização. Tanto o SMS (Systems Management Server) quanto a Diretiva de Grupo podem ser usados para implantar o cliente do RMS com o Service Pack 2 (SP2).

Antes de começar a implantação, consulte [http://go.microsoft.com/fwlink/?LinkId=67736](http://go.microsoft.com/fwlink/?linkid=67736) para baixar o cliente do RMS (a página pode estar em inglês).

| ![](images/Cc747749.Important(WS.10).gif)Importante                          |
|-----------------------------------------------------------------------------------------------------------|
| O cliente do RMS foi integrado ao Windows Vista. Portanto, não é necessário fazer uma instalação à parte. |

Extraindo os arquivos de instalação
-----------------------------------

Depois de baixar o arquivo WindowsRightsManagementServicesSP2-KB917275-Client-ENU.exe, você deve extrair os arquivos do Microsoft® Windows® Installer do pacote executável.

Você pode usar o seguinte comando no prompt de comando para fazer isso:

`WindowsRightsManagementServicesSP2-KB917275-Client-ENU.exe /x <path>`

onde &lt;path&gt; é o diretório de destino no qual você deseja colocar os arquivos extraídos.

Ao executar esse comando, os seguintes arquivos serão extraídos para o diretório de destino especificado:

-   Bootstrap.exe
    Trata-se de um arquivo de invólucro usado pelo arquivo executável para instalar os outros arquivos incluídos. Ele não é usado na instalação do cliente do RMS com SP2 ao usar o SMS ou a Diretiva de Grupo.
-   MSDrmClient.msi
    Esse é o arquivo de instalação do cliente do RMS com SP2. Essa instalação desinstala qualquer versão anterior do cliente do RMS existente no computador. Este programa deve ser instalado primeiramente nos computadores clientes.
-   RMClientBackCompat.msi
    Esse é o arquivo de instalação que identifica o novo cliente do RMS com SP2 para aplicativos habilitados para RMS (como o Microsoft Office Professional 2003 ou o 2007 Microsoft Office System) que dependem da versão anterior do cliente do RMS para que o cliente do RMS com SP2 possa ser usado. Este programa deve ser instalado nos computadores clientes após a instalação bem-sucedida do MSDrmClient.msi.

| ![](images/Cc747749.note(WS.10).gif)Observação                                                                                                                                                                               |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Qualquer que seja o método de instalação que você escolha implementar, os dois arquivos do Windows Installer devem ser instalados com êxito. Se ocorrer um erro que impeça a instalação do MSDrmClient.msi, não instale o arquivo RMClientBackCompat.msi. |

Implantar o cliente do RMS usando uma instalação autônoma
---------------------------------------------------------

A extração dos arquivos para instalar os arquivos do Windows Installer é opcional. Também é possível implantar o cliente do RMS utilizando o método de instalação autônoma. Você pode usar o seguinte comando no prompt de comando para fazer isso:

`WindowsRightsManagementServicesSP2-KB917275-Client-ENU.exe -override 1 /I MsDrmClient.msi REBOOT=ReallySuppress /q -override 2 /I RmClientBackCompat.msi REBOOT=ReallySuppress /q`

Esse comando inicia a instalação autônoma do cliente do RMS.

| ![](images/Cc747749.note(WS.10).gif)Observação                                                                                                               |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Como se trata de uma instalação autônoma, o instalador não informa quando o processo é concluído. Geralmente as instalações autônomas são executadas em um arquivo em lotes ou de script. |

Implantar o cliente do RMS usando o SMS
---------------------------------------

**Para implantar o cliente do RMS usando o SMS**
1.  Abra o console do Administrador do SMS.

2.  Expanda o banco de dados do site que você deseja usar.

3.  No painel esquerdo, clique com o botão direito do mouse em **Pacotes**, escolha **Novo** e clique em **Pacote da Definição**.

4.  Crie pacotes a partir dos arquivos MSDRMClient.msi e RMClientBackCompat.msi. Os pacotes devem ter as seguintes propriedades:

    **Geral**:

    -   Em **Linha de Comando**, digite o seguinte:
        `msiexec.exe /q ALLUSERS=2 /m MSIDGHOG /i "<file_name>.msi"`
        | ![](images/Cc747749.note(WS.10).gif)Observação                                                      |
        |----------------------------------------------------------------------------------------------------------------------------------|
        | MSIDGHOG é um valor aleatório. Substitua &lt;file\_name&gt; pelo nome do arquivo do Windows Installer que o pacote vai instalar. |

    -   Em **Executar**, selecione a opção **Oculto**.
    -   Em **Após executar**, selecione a opção **Nenhuma ação necessária**.
    -   Em **Categoria**, selecione a opção **Software Administrativo**.

    **Requisitos:**

    -   Em **Espaço em disco estimado**, digite **445 KB**.
    -   Em **Tempo de execução máximo permitido**, selecione **Desconhecido**.
    -   Marque a caixa de seleção **Este programa pode ser executado em qualquer plataforma**.

    **Ambiente:**

    -   Em **O programa pode ser executado**, selecione a opção **Se um usuário tiver ou não efetuado logon**.
    -   Em **Modo de execução**, selecione a opção **Executar com direitos administrativos**.
    -   Em **Modo de acionamento**, selecione a opção **Execução com nome UNC**.

    **Avançado:**

    -   Desmarque a caixa de seleção **Executar um outro programa primeiro**.
    -   Desmarque a caixa de seleção **Suprimir notificação de programa** em **Quando o programa estiver atribuído a um computador**.
    -   Desmarque a caixa de seleção **Desabilitar este programa nos computadores quando for anunciado**.

5.  Defina as **Contas de acesso e pontos de distribuição**, conforme apropriado para a sua organização.

6.  Crie um anúncio para a coleção apropriada. Recomenda-se utilizar o programa **Autônomo por sistema** em uma implantação de SMS.

7.  Agende este anúncio de acordo com as necessidades da sua organização.

Implantar o cliente do RMS usando a Diretiva de Grupo
-----------------------------------------------------

Você pode usar o recurso de Instalação e Manutenção de Software da Diretiva de Grupo para implantar o cliente do RMS nos computadores de destino.

A Diretiva de Grupo é o método recomendado para gerenciar ativamente a implantação dos clientes do RMS em organizações de pequeno e médio porte ou que ainda não usam uma solução corporativa de gerenciamento de atualizações, como o Systems Management Server 2003.

Ao usar a Diretiva de Grupo para distribuir um programa, você pode atribuir esse programa a computadores. A instalação do programa ocorre quando o computador é iniciado e está disponível para todos os usuários que fizerem logon no computador. Para obter mais informações sobre a Diretiva de Grupo, consulte a página sobre criação de uma infra-estrutura de Diretiva de Grupo em <http://go.microsoft.com/fwlink/?linkid=24328> (a página pode estar em inglês). Este procedimento pressupõe que você está usando o Console de Gerenciamento de Diretiva de Grupo (GPMC). Para baixar o GPMC, consulte a página sobre o Console de Gerenciamento de Diretiva de Grupo com Service Pack 1 em <http://go.microsoft.com/fwlink/?linkid=21813> (a página pode estar em inglês).

O procedimento a seguir fornece um guia rápido para administradores que não estão familiarizados com a distribuição de software baseada em Diretiva de Grupo. Se necessário, você pode modificar estas etapas para atender às demandas da sua organização.

**Para implantar o cliente do RMS usando a Diretiva de Grupo**
1.  Em um controlador de domínio, abra o snap-in do Console de Gerenciamento Microsoft **Usuários e computadores do Active Directory**.

2.  Crie uma nova unidade organizacional ou selecione uma já existente.

    Se você criou uma nova unidade organizacional, adicione os computadores nos quais deseja instalar o cliente do RMS.

3.  Clique com o botão direito do mouse na unidade organizacional e escolha **Propriedades**.

4.  Selecione a guia **Diretiva de Grupo**.

5.  Clique em **Novo** para criar um novo objeto Diretiva de Grupo (GPO).

6.  Clique em **Editar** para editar o novo GPO.

7.  Na árvore do console, expanda **Configuração do Computador, Configurações de Software** e selecione **Instalação de software**.

8.  Clique com o botão direito do mouse no painel de detalhes, clique em **Novo** e em **Pacote**.

9.  Forneça um caminho ao arquivo MSDRMclient.msi em uma pasta compartilhada da rede que os computadores clientes possam acessar.

10. Clique em **OK** para atribuir o pacote.

11. Repita as etapas 5 a 10 para criar um GPO que instale o arquivo RMClientBackCompat.msi.

| ![](images/Cc747749.note(WS.10).gif)Observação                                                                                                                                                                                                                                                                                                                                                                                                |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Essas etapas são fornecidas apenas como orientação para os usuários que não têm experiência no uso de Diretiva de Grupo. Se você for um administrador experiente de Diretiva de Grupo, poderá adotar os seus próprios procedimentos operacionais para distribuir o pacote MSDrmClient.msi. Além disso, essas etapas são para um controlador de domínio que execute o Windows Server 2003 — o processo e a terminologia podem ser diferentes em um domínio de Windows 2000. |

Atualizando de uma versão anterior
----------------------------------

        ```
| ![](images/Cc747749.note(WS.10).gif)Observação                                   |
|---------------------------------------------------------------------------------------------------------------|
| Esse script não funciona com o Windows Vista porque o cliente do RMS está incorporado ao sistema operacional. |
