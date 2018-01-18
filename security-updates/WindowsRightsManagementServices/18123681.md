---
TOCTitle: Excluindo versões do Windows
Title: Excluindo versões do Windows
ms:assetid: '8b8a184d-ac0e-4a43-822c-d2fae2faf484'
ms:contentKeyID: 18123681
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747590(v=WS.10)'
---

Excluindo versões do Windows
============================

O cliente do Microsoft® Windows® RMS (Rights Management Services) 1.0 tem suporte em computadores que estão executando o Microsoft Windows 98 Segunda Edição ou o Windows Millennium Edition; no entanto, esses sistemas operacionais não oferecem suporte à autenticação NTLM. Por esse motivo, você pode desejar evitar que usuários consumam conteúdo protegido por direitos em um computador que esteja executando um desses sistemas operacionais e exigir que eles usem versões posteriores ao Windows Millennium Edition para garantir maior segurança para seu conteúdo.

Quando você define uma diretiva de exclusão para excluir usuários com base na versão do Windows, uma condição é colocada em todas as licenças de uso impedindo que elas sejam usadas em clientes que estão executando o Windows 98 Segunda Edição e o Windows Millennium Edition. Você deve habilitar a exclusão da versão do Windows na página **Diretivas de exclusão** no site de administração de cada cluster no qual deseja que ela tenha efeito.
