---
TOCTitle: Segurança durante a instalação do RMS
Title: Segurança durante a instalação do RMS
ms:assetid: '0a3d40b2-f27e-4e63-baff-a9c8433f5f91'
ms:contentKeyID: 18123586
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720192(v=WS.10)'
---

Segurança durante a instalação do RMS
=====================================

Para instalar e configurar os arquivos do RMS, a instalação do RMS usa as credenciais do usuário conectado. Por esse motivo, o administrador que executa o procedimento de instalação deve fazer logon com uma conta de usuário que seja membro do grupo de administradores locais. Para todas as instalações, exceto para instalações de um único computador, essa conta também deve ser uma conta de usuário de domínio.

Durante o procedimento de instalação, o serviço Windows Installer (Msiexec.exe) é iniciado. Esse serviço herda seu token de usuário pai. Mais tarde, se existirem ações de personalização de pós-processo, o serviço Msiexec.exe usa a identidade do usuário conectado. Isso ocorre independentemente de se o processo é iniciado em um navegador ou na linha de comando.

A instalação do RMS executa as seguintes tarefas:

-   Copia arquivos na pasta C:\\Arquivos de Programas\\RMS. Essa pasta normalmente permite que os administradores e os usuários com poderes obtenham acesso a ela. Você pode configurar a unidade e o local do arquivo durante a instalação.
-   Cria o site de configuração, o site de Administração do RMS, na porta 5720, por padrão. Este site aponta para arquivos instalados.
-   Cria um pool de aplicativos, WMCSProvisioningAppPool, e o associa ao site de Administração do RMS. A conta de serviço que é usada por esse pool de aplicativos é a conta de serviços de rede.
-   Instala contadores de desempenho.
-   Fornece permissões de Leitura e Execução ao Grupo de Serviço RMS para a seguinte chave do registro.
    Em computadores que executam a versão de 32 bits do Windows Server 2003  
    `HKEY_LOCAL_MACHINE\Software\Microsoft\DRMS\1.0`  
    Em computadores que executam a versão de 64 bits do Windows Server 2003  
    `HKEY_LOCAL_MACHINE\Software\WOW6432Node\Microsoft\DRMS\1.0`
