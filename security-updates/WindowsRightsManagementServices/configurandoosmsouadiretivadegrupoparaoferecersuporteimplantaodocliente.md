---
TOCTitle: Configurando o SMS ou a Diretiva de Grupo para oferecer suporte à implantação do cliente
Title: Configurando o SMS ou a Diretiva de Grupo para oferecer suporte à implantação do cliente
ms:assetid: '9e37c27b-8cc1-40c6-adb7-0937aa64c8db'
ms:contentKeyID: 18123791
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747703(v=WS.10)'
---

Configurando o SMS ou a Diretiva de Grupo para oferecer suporte à implantação do cliente
========================================================================================

Quando você implanta o RMS, um aplicativo habilitado para RMS deve ser instalado no computador de um usuário para proteger o conteúdo e consumir o conteúdo protegido pelo RMS.

A fim de que um aplicativo seja habilitado para RMS, ele deve integrar o cliente do RMS nas suas operações. Antes do Windows Vista®, o cliente do RMS ficava disponível como um componente do Windows que podia ser baixado separadamente do Centro de Download da Microsoft. Entretanto, se você não quiser baixar o cliente individualmente para cada computador cliente da sua empresa, poderá usar o Microsoft SMS (Systems Management Server), a Diretiva de Grupo ou os scripts para automatizar a entrega dos clientes do RMS aos computadores clientes.

> [!Important]  
> O cliente do RMS é integrado ao Windows Vista. Portanto, não é necessário fazer uma instalação à parte.

Ao usar o SMS para distribuir o cliente do RMS, você precisará fazer o seguinte:

-   Criar um novo arquivo de definição de pacote.
-   Extrair os arquivos do Windows Installer do arquivo WindowsRightsManagementServicesSP2-KB917275-Client-ENU.exe. Para fazer isso, primeiro salve o arquivo WindowsRightsManagementServicesSP2-KB917275-Client-ENU.exe. Não o instale. Para este exemplo, considere que o arquivo foi salvo em c:\\nome\_pasta. Abra uma janela de prompt de comando e digite o seguinte comando:  
    `c:\folder_name\WindowsRightsManagementServicesSP2-KB917275-Client-ENU.exe /x/t:c:\folder_name`
    Esse comando extrai os arquivos MSDrmClient.msi e RMClientBackCompat.msi do arquivo .exe e os coloca em *c:\\nome\_da\_pasta*.
-   Use os arquivos do Windows Installer para a origem e a definição de pacote.
-   Anunciar a disponibilidade dos pacotes na sua rede.

> [!note]  
> São exigidos direitos administrativos para instalar o software; a diretiva de segurança da sua organização pode exigir que um administrador do sistema instale o software cliente do RMS.

Para obter mais informações sobre como usar o SMS para distribuir software, consulte o Guia de Conceitos, Planejamento e Implantação do Systems Management Server 2003 em [http://go.microsoft.com/fwlink/?LinkId=17401](http://go.microsoft.com/fwlink/?linkid=17401) (a página pode estar em inglês).

Para obter mais informações sobre como implantar software cliente usando a Diretiva de Grupo, consulte os tópicos sobre implantação de software baseada na Diretiva de Grupo em [http://go.microsoft.com/fwlink/?LinkID=38997](http://go.microsoft.com/fwlink/?linkid=38997) (a página pode estar em inglês).
