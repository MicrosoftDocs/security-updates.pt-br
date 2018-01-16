---
TOCTitle: Configurando uma URL de extranet
Title: Configurando uma URL de extranet
ms:assetid: '88fec9ff-c96c-4d20-8856-0485e7507572'
ms:contentKeyID: 18123750
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747661(v=WS.10)'
---

Configurando uma URL de extranet
================================

Se quiser oferecer suporte a usuários da extranet na instalação do RMS, você pode adicionar um servidor de licenciamento ou cluster que seja dedicado ao uso da extranet.

Ao configurar um servidor de licenciamento para extranet, você especifica para ele uma URL de cluster, da mesma forma como o faz para qualquer servidor RMS. Normalmente, a URL que você especifica é uma URL interna que não é acessível a usuários da extranet. Essa é a URL que o RMS usa para descoberta de serviço. Ela deve ser uma URL válida em sua organização.

Se você estiver adicionando uma URL do cluster da extranet a um servidor RMS que já esteja em serviço, os clientes atuais do RMS deverão obter novos certificados de licenciante cliente para acessarem o cluster da extranet para licenciamento.

Para obter mais informações, consulte "[Adicionar uma URL de cluster de extranet](https://technet.microsoft.com/12c83186-ce9e-4100-bbd1-d87a885331c7)", mais adiante neste tema.
