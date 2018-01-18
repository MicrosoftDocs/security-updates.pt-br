---
TOCTitle: Modelo de segurança do RMS
Title: Modelo de segurança do RMS
ms:assetid: '665db831-366d-4dca-9bb3-cc2912481fe1'
ms:contentKeyID: 18123697
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747598(v=WS.10)'
---

Modelo de segurança do RMS
==========================

Durante sua operação, o RMS ganha acesso a vários recursos, incluindo o servidor de banco de dados, o Active Directory, a fila de mensagens e o disco rígido local. Além disso, a instalação do RMS cria e expõe determinados recursos necessários às suas operações, como entradas do SOAP, páginas da Web, filas de mensagens de log, etc. A instalação do RMS configura listas de controle de acesso condicionais nos recursos que ela cria e expõe e também configura a autenticação do Serviços de Informações da Internet (IIS) para cada recurso.

Esta seção fornece informações sobre como o RMS configura a segurança nos recursos que utiliza e como ganha acesso aos recursos nas diferentes fases de sua operação: instalação, configuração e normal.

Esta seção inclui:

-   [Grupos de segurança do RMS](https://technet.microsoft.com/25749a83-8c12-48ec-96ad-296d31fd55d4)
-   [Modos de segurança para o RMS](https://technet.microsoft.com/d7792293-5bb2-4232-9d48-e81e87ab6219)
-   [Segurança durante a instalação do RMS](https://technet.microsoft.com/0a3d40b2-f27e-4e63-baff-a9c8433f5f91)
-   [Segurança durante a configuração](https://technet.microsoft.com/9f1282c5-5642-4870-a9a4-c3a485f8ff76)
-   [Segurança durante a operação normal do RMS](https://technet.microsoft.com/98f3d584-6320-4aa1-9959-7133cfdb6df7)
