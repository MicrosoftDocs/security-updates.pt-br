---
TOCTitle: 'Etapa 1: revisar os requisitos de instalação do WSUS'
Title: 'Etapa 1: revisar os requisitos de instalação do WSUS'
ms:assetid: '57d7f8ec-1523-4485-9967-604be9ba2aac'
ms:contentKeyID: 18139150
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720547(v=WS.10)'
---

Etapa 1: revisar os requisitos de instalação do WSUS
====================================================

Este guia oferece instruções sobre a instalação do Microsoft Windows Server Update Services (WSUS) nos sistemas operacionais Microsoft Windows Server 2003 (exceto para Web Edition e todas as versões de 64 bits). Se você tem um servidor que executa o Microsoft Windows 2000 Server e precisa de mais informações, consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês).

A seguir estão os requisitos básicos para as instalações que usam opções padrão. Você pode encontrar requisitos de hardware e software para outras instalações no informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês).

As recomendações de hardware para um servidor com até 500 clientes são:

-   Processador de 1 gigahertz (GHz)
-   1 gigabyte (GB) de RAM

Requisitos de software
----------------------

Para instalar o WSUS com as opções padrão, o computador deve ter os itens a seguir instalados. Para obter mais informações sobre os requisitos de software do WSUS, consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês). Se alguma dessas atualizações exigir que o computador seja reiniciado após a conclusão da instalação, reinicie o servidor antes de instalar o WSUS.

-   Serviços de Informações da Internet (IIS) 6.0 Para obter instruções sobre como instalar o IIS, consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês) ou o Centro de Ajuda e Suporte no Windows Server 2003.
-   Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2003. Para obter esse software, acesse a [Central de Download](http://go.microsoft.com/fwlink/?linkid=47358) em http://go.microsoft.com/fwlink/?LinkId=47358 (o documento pode estar em inglês).
    Opcionalmente, consulte http://www.windowsupdate.com e procure por Atualizações Críticas e Service Packs – instale o Microsoft .NET Framework 1.1 Service Pack 1 para Windows Server 2003.
-   Background Intelligent Transfer Service (BITS) 2.0. No momento, o BITS 2.0 para o Windows Server 2003 não está disponível no Centro de Download. Para obter esse software, acesse o [site da Microsoft](http://go.microsoft.com/fwlink/?linkid=47357) e consulte Windows Server Update Services Open Evaluation (o documento pode estar em inglês) em http://go.microsoft.com/fwlink/?LinkId=47357.

> [!NOTE]  
> Embora seja necessário um software de banco de dados para instalar o WSUS, ele não está listado aqui porque a instalação padrão do WSUS no Windows Server 2003 inclui o software de banco de dados Windows SQL Server™ 2000 Desktop Engine (WMSDE). 

Requisitos e recomendações de disco
-----------------------------------

Para instalar o WSUS, o sistema de arquivos do servidor deve atender aos seguintes requisitos:

-   Tanto a partição do sistema quanto a partição em que você instala o WSUS devem ser formatas com o sistema de arquivos NTFS.
-   É necessário haver, no mínimo, 1 GB de espaço livre para a partição do sistema.
-   É necessário haver, no mínimo, 6 GB de espaço livre para o volume em que o WSUS armazena o conteúdo; o recomendável é 30 GB.
-   É necessário haver, no mínimo, 2 GB de espaço livre para o volume em que o WSUS instala o Windows SQL Server 2000 Desktop Engine (WMSDE).

Requisitos das Atualizações Automáticas
---------------------------------------

As Atualizações Automáticas são o componente cliente do WSUS. O único requisito de hardware para as Atualizações Automáticas é que haja conexão com a rede. Você pode usar as Atualizações Automáticas com o WSUS em computadores que executem qualquer um destes sistemas operacionais:

-   Microsoft Windows 2000 Professional com Service Pack 3 (SP3) ou Service Pack 4 (SP4), Windows 2000 Server com SP3 ou SP4 ou Windows 2000 Advanced Server com SP3 ou SP4.
-   Microsoft Windows XP Professional, com ou sem Service Pack 1 ou Service Pack 2.
-   Microsoft Windows Server 2003, Standard Edition; Windows Server 2003, Enterprise Edition; Windows Server 2003, Datacenter Edition ou Windows Server 2003, Web Edition.
