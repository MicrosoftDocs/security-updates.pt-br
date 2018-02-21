---
TOCTitle: Descomissionando o RMS
Title: Descomissionando o RMS
ms:assetid: 'dbcacce7-434d-48a7-a11d-ef9690d78b44'
ms:contentKeyID: 18123858
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747767(v=WS.10)'
---

Descomissionando o RMS
======================

O descomissionamento é o processo inteiro de remoção do servidor RMS e de seus bancos de dados associados de uma organização. Esse processo permite remover o RMS da infra-estrutura sem perder o acesso às informações protegidas pelo RMS. A seguir, são apresentadas algumas razões possíveis para que uma organização venha a precisar remover um servidor RMS da infra-estrutura:

-   Migração de um servidor RMS de verificação de conceito de um ambiente piloto para o ambiente de produção.
-   Simplificação do design de arquitetura, removendo e consolidando servidores de licenciamento no cluster raiz do RMS.
-   Mesclagem de servidores RMS (por exemplo, como resultado de uma fusão ou aquisição de empresas), integrando duas infra-estruturas de RMS em uma.
-   Decisão de parar de usar o RMS para proteger conteúdo.

Como um servidor RMS ativo é integrado a um servidor de banco de dados e ao Active Directory e, obviamente, protege um conjunto inteiro de conteúdo com uma chave contida no servidor RMS, a remoção do RMS de uma organização requer mais etapas do que simplesmente remover o programa do servidor. Esta seção lista essas etapas, de modo que você possa descomissionar o servidor RMS, se necessário.

Esta seção inclui:

-   [Compreendendo o processo de descomissionamento](https://technet.microsoft.com/57bd9949-9433-437b-93ed-ffb2dff9992e)
-   [Habilitando o serviço de descomissionamento](https://technet.microsoft.com/45226e85-b50d-41cc-aca7-0f603f8509d5)
-   [Configurando permissões de diretórios virtuais](https://technet.microsoft.com/45112111-9608-45b1-9a86-7b313d0a1579)
-   [Removendo a proteção por RMS do conteúdo](https://technet.microsoft.com/c30361e3-50d2-4474-a87d-d38de502cf9e)
-   [Removendo o serviço da Web (Desconfigurando o RMS)](https://technet.microsoft.com/68b4e2b0-b1b7-4b0a-8c1a-82ac27c1f12e)
-   [Removendo arquivos de programas do RMS](https://technet.microsoft.com/d1dc8a8b-f8de-487f-87b4-2174d449f0bc)
-   [Alternativas para o descomissionamento do RMS](https://technet.microsoft.com/4d32f35e-997d-4d10-ab66-efe217e853f7)
