---
TOCTitle: Planejamento da segurança do RMS
Title: Planejamento da segurança do RMS
ms:assetid: 'eb0fa784-1246-44aa-be31-2c332db7d09c'
ms:contentKeyID: 18123816
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747719(v=WS.10)'
---

Planejamento da segurança do RMS
================================

Como ocorre com outros servidores da sua organização, a segurança deve ser considerada parte integrante do planejamento da implantação. O RMS é implementado como um serviço na Web, de modo que você pode controlar o acesso ao RMS como faria com outros serviços na Web, usando ACLs (listas de controle de acesso) e SSL (Secure Sockets Layer).

O RMS também pode ser implementado como parte de um domínio de acesso controlado, se parte da sua implantação solicitar que o RMS forneça um nível maior de controle para informações sigilosas.

Como o RMS utiliza um sistema de chaves particulares para criptografar o conteúdo, deve ser feito o backup da chave particular do RMS e ela deve ser gerenciada como parte integrante do plano de segurança.

Este tema inclui os seguintes tópicos:

-   [Determinando requisitos de acesso](https://technet.microsoft.com/eb2ce9a5-0430-4811-bd40-4a94a84426a8)
-   [Definindo requisitos de gerenciamento de chaves](https://technet.microsoft.com/f0e08fb8-bf5e-4278-a09f-daa57696e786)
