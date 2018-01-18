---
TOCTitle: Usando contadores de desempenho
Title: Usando contadores de desempenho
ms:assetid: '096c3b17-c082-46c4-939c-4373af0c9dec'
ms:contentKeyID: 18123529
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720180(v=WS.10)'
---

Usando contadores de desempenho
===============================

O RMS inclui vários conjuntos de objetos e contadores de desempenho que podem ser usados no Monitor do Sistema para monitorar a atividade dos serviços do RMS. Os contadores de desempenho são específicos de cada um dos objetos de desempenho do RMS e incluem os seguintes objetos:

-   Contadores de desempenho RMS: ActivationProxy para solicitações de proxy de ativação.
-   Contadores de desempenho RMS: Certification para solicitações de certificação de conta.
-   Contadores de desempenho RMS: DirectoryServices para consultas do Active Directory.
-   Contadores de desempenho RMS: Enrollment para solicitações de sub-registro.
-   Contadores de desempenho RMS: Licensing para solicitações de licença de publicação e de uso.
-   Contadores de desempenho RMS: Logging para atividade de registro.

Esses contadores de desempenho são instalados automaticamente durante a configuração, mas você deve adicionar os contadores ao log para iniciar a monitoração.

Para adicionar um contador de desempenho:

1.  No menu **Iniciar**, aponte para **Ferramentas Administrativas** e clique em **Desempenho**.
2.  Na caixa de diálogo **Desempenho**, clique com o botão direito do mouse no painel de detalhes e clique em **Adicionar Contadores**.
3.  Na caixa de diálogo **Adicionar Contadores**, na lista de objetos **Desempenho**, selecione o contador que deseja adicionar e clique em **Adicionar**.

Você pode usar as opções **Logs e Alertas de Desempenho**, disponíveis na caixa de diálogo **Desempenho**, para monitorar e gerenciar arquivos de log. Para obter mais informações sobre os contadores de desempenho que estão disponíveis no RMS, consulte “[Contadores de desempenho do RMS](https://technet.microsoft.com/a2f4e30d-3c6f-4e74-bd11-8f2103f88b0c)”, mais adiante neste tema. Para obter informações gerais sobre contadores de desempenho, consulte a Ajuda do Monitor do Sistema.
