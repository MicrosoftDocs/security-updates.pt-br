---
TOCTitle: 'Removendo o serviço da Web (Desconfigurando o RMS)'
Title: 'Removendo o serviço da Web (Desconfigurando o RMS)'
ms:assetid: '68b4e2b0-b1b7-4b0a-8c1a-82ac27c1f12e'
ms:contentKeyID: 18123696
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747602(v=WS.10)'
---

Removendo o serviço da Web (Desconfigurando o RMS)
==================================================

Depois que o servidor RMS tiver sido descomissionado e toda a proteção do RMS tiver sido removida, o serviço da Web poderá ser removido usando-se as seguintes etapas:

-   Na página **Administração Global**, selecione **Remover o RMS deste site**.

A próxima etapa depende do tipo de servidor que está sendo removido, apesar de que, em todos os casos, o RMS será removido do IIS.

-   Se o servidor fizer parte de um cluster (e não for o último servidor do cluster), não serão necessárias etapas adicionais.
-   Se o servidor for apenas um servidor de licenciamento, remova o banco de dados dos serviços de diretório, mas mantenha os bancos de dados de configuração e de log (esses são usados pelo servidor de certificação que ainda está em serviço).
-   Caso se trate do último servidor RMS da organização, mantenha os bancos de dados de configuração e de log, mas remova o SCP (ponto de conexão de serviço) do Active Directory.
