---
TOCTitle: 'Etapa 1: Revisar os Requisitos de Instalação do WSUS 3.0'
Title: 'Etapa 1: Revisar os Requisitos de Instalação do WSUS 3.0'
ms:assetid: '912b37d7-021e-4c95-b317-49dd15b4611c'
ms:contentKeyID: 18139293
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708484(v=WS.10)'
---

Etapa 1: Revisar os Requisitos de Instalação do WSUS 3.0
========================================================

Este guia explica como instalar o WSUS 3.0. Para requisitos de software e plataformas compatíveis do WSUS 3.0, consulte as Notas de Versão ([http://go.microsoft.com/fwlink/?LinkId=71220](http://go.microsoft.com/fwlink/?linkid=71220)), em sistemas operacionais Windows Server 2003 Service Pack 1 e Windows Server® 2008.

Requisitos de software para instalar o WSUS 3.0 no Windows Server 2003 Service Pack 1
-------------------------------------------------------------------------------------

É necessário ter os seguintes itens no computador para instalar o WSUS 3.0 no Windows Server 2003 Service Pack 1. Se nenhuma destas atualizações exigir a reinicialização do servidor quando a instalação estiver concluída, será necessário reiniciar o servidor antes de instalar o WSUS 3.0.

-   Serviços de Informações da Internet (IIS) 6.0 da Microsoft.
-   Atualização para o BITS (Serviço de Transferência Inteligente em Segundo Plano) 2.0 e o WinHTTP 5.1 Windows Server 2003. Para baixar este software, acesse o Centro de Download ([http://go.microsoft.com/fwlink/?LinkID=47251](http://go.microsoft.com/fwlink/?linkid=47251)).
-   Pacote Redistribuível (x86) do Microsoft .NET Framework Versão 2.0. Para baixar este software, acesse o Centro de Download ([http://go.microsoft.com/fwlink/?LinkID=68935](http://go.microsoft.com/fwlink/?linkid=68935)). (Para plataformas de 64 bits, acesse também o Centro de Download \[[http://go.microsoft.com/fwlink/?LinkID=70637](http://go.microsoft.com/fwlink/?linkid=70637)\].)
-   Microsoft Report Viewer Redistributable 2005. Para obter este software, acesse o Centro de Download ([http://go.microsoft.com/fwlink/?LinkID=70410](http://go.microsoft.com/fwlink/?linkid=70410)).
-   Console de Gerenciamento Microsoft 3.0 para Windows Server 2003 (KB907265). Para baixar este software, acesse o Centro de Download ([http://go.microsoft.com/fwlink/?LinkID=70412](http://go.microsoft.com/fwlink/?linkid=70412)). (Para plataformas de 64 bits, acesse também o Centro de Download \[[http://go.microsoft.com/fwlink/?LinkID=70638](http://go.microsoft.com/fwlink/?linkid=70638)\].)

Requisitos de software para instalar o WSUS 3.0 no Windows Server 2008
----------------------------------------------------------------------

É necessário ter os seguintes itens no computador para instalar o WSUS 3.0 no Windows Server 2008. Se nenhuma destas atualizações exigir a reinicialização do servidor quando a instalação estiver concluída, será necessário reiniciar o servidor antes de instalar o WSUS 3.0.

-   Serviços de Informações da Internet (IIS) 7.0 da Microsoft. Verifique se os seguintes componentes estão habilitados:
    -   Autenticação do Windows
    -   ASP.NET
    -   Compatibilidade de Gerenciamento do IIS 6.0
    -   Compatibilidade da Metabase do IIS
-   Microsoft Report Viewer Redistributable 2005. Para baixar este software, acesse o Centro de Download ([http://go.microsoft.com/fwlink/?LinkID=70410](http://go.microsoft.com/fwlink/?linkid=70410)).
-   Microsoft SQL Server™ 2005 Service Pack 1. Para baixar este software, acesse o Centro de Download ([http://go.microsoft.com/fwlink/?LinkID=66143](http://go.microsoft.com/fwlink/?linkid=66143)).

As atualizações do .NET Framework 2.0 e do BITS 2.0 estão disponíveis no Windows Server 2008 como parte do sistema operacional.

Requisitos e recomendações de disco
-----------------------------------

Para instalar o WSUS 3.0, o sistema de arquivos do servidor deve atender aos seguintes requisitos:

-   Tanto a partição do sistema quanto a partição em que você instala o WSUS 3.0 devem ser formatadas com o sistema de arquivos NTFS.
-   É recomendável ter no mínimo 1 GB de espaço livre para a partição do sistema.
-   É necessário ter no mínimo 20 GB de espaço livre para o volume em que o WSUS armazena o conteúdo; o recomendável é 30 GB de espaço livre.
-   É recomendável ter no mínimo 2 GB de espaço livre no volume no qual a Instalação do WSUS instala o Windows® Internal Database.

Requisitos de instalação somente para console
---------------------------------------------

O WSUS 3.0 permite a instalação do console da Administração do WSUS em sistemas remotos separados do servidor do WSUS. As instalações somente para console devem ser executadas nos seguintes sistemas operacionais:

-   Windows Server® 2008
-   Windows Vista®
-   Windows Server 2003 Service Pack 1
-   Windows XP Service Pack 2

Os pré-requisitos do software para a instalação somente para console estão listados a seguir

-   Pacote Redistribuível (x86) do Microsoft .NET Framework Versão 2.0, disponível no Centro de Download da Microsoft ([http://go.microsoft.com/fwlink/?LinkId=68935](http://go.microsoft.com/fwlink/?linkid=68935)). Para as plataformas de 64 bits, acesse o Pacote Redistribuível (x64) do Microsoft .NET Framework Versão 2.0 ([http://go.microsoft.com/fwlink/?LinkId=70637](http://go.microsoft.com/fwlink/?linkid=70637)).
-   Console de Gerenciamento Microsoft 3.0 para Windows Server 2003 (KB907265), disponível no Centro de Download da Microsoft ([http://go.microsoft.com/fwlink/?LinkId=70412](http://go.microsoft.com/fwlink/?linkid=70412)). Para plataformas de 64 bits, acesse o Console de Gerenciamento Microsoft 3.0 para Windows Server 2003 x64 Edition (KB907265) ([http://go.microsoft.com/fwlink/?LinkId=70638](http://go.microsoft.com/fwlink/?linkid=70638)).
-   Microsoft Report Viewer Redistributable 2005, disponível no Centro de Download da Microsoft ([http://go.microsoft.com/fwlink/?LinkId=70410](http://go.microsoft.com/fwlink/?linkid=70410)).

Requisitos das Atualizações Automáticas
---------------------------------------

As Atualizações Automáticas são o componente cliente do WSUS 3.0. O único requisito de hardware para as Atualizações Automáticas é que haja conexão com a rede. Você pode usar as Atualizações Automáticas com o WSUS 3.0 em computadores que executam qualquer um destes sistemas operacionais:

-   Windows Vista.
-   Windows Server® 2008.
-   Microsoft Windows® Server 2003, todas as versões e service packs.
-   Microsoft Windows XP Professional, Service Pack 1 ou Service Pack 2.
-   Microsoft Windows 2000 Professional Service Pack 4, Windows 2000 Server Service Pack 4 ou Windows 2000 Advanced Server Service Pack 4.

Permissões
----------

As permissões de disco a seguir devem ser concedidas a usuários específicos para os diretórios especificados:

1.  O grupo interno Usuários ou a conta Autoridade NT\\Serviço de Rede (no Windows Server 2003) deve ter permissões de leitura para a pasta raiz na unidade em que o diretório de conteúdo do WSUS reside. Se esta permissão estiver ausente, os downloads do BITS falharão. Se esta permissão estiver ausente, os downloads do BITS falharão.
2.  A conta Autoridade NT\\Serviço de Rede deve ter a permissão "Controle Total" para o diretório de conteúdo do WSUS, geralmente &lt;SystemDriver&gt;:WSUS\\WsusContent. Essa permissão é definida pela instalação do servidor do WSUS, quando o diretório é criado, porém ela será redefinida por alguns softwares de segurança. Se esta permissão estiver ausente, os downloads do BITS falharão.
3.  A conta Autoridade NT\\Serviço de Rede deve ter a permissão “Controle Total” para as seguintes pastas para que o snap-in da Administração do WSUS seja exibido corretamente:
    -   %windir%\\Microsoft .NET\\Framework\\v2.0.50727\\Arquivos ASP.NET Temporários
    -   %WinDir%\\Temp

Para obter mais informações sobre configurações de permissões, consulte O DCPROMO não retém permissões em algumas pastas IIS em [http://go.microsoft.com/fwlink/?LinkID=76332](http://go.microsoft.com/fwlink/?linkid=76332).
