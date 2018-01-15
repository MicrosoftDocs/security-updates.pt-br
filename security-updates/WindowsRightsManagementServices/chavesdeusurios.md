---
TOCTitle: Chaves de usuários
Title: Chaves de usuários
ms:assetid: '12dad6e2-64e7-4bab-bde7-b72f90f5cb05'
ms:contentKeyID: 18123585
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720202(v=WS.10)'
---

Chaves de usuários
==================

Um usuário do RMS possui um par de chaves com chaves RSA de 1024 bits. O par de chaves do usuário é armazenado no banco de dados de configuração do RMS, de modo que um determinado usuário tenha sempre o mesmo par de chaves em todo o sistema RMS.

O certificado de conta de direitos contém a chave pública do usuário. Essa chave é usada para criptografar a chave de conteúdo que está em uma licença de uso, de modo que apenas um determinado usuário possa usar essa licença para consumir o conteúdo protegido pelo RMS.

O mesmo certificado de conta de direitos também contém a chave particular do usuário, a qual é criptografada com uma chave pública de máquina cliente. Isso assegura que um certificado de conta de direitos possa ser usado apenas no computador para o qual foi emitido, sendo que todos os certificados de conta de direitos de um determinado usuário conterão o mesmo par de chaves. Essa chave particular do usuário é exigida no momento do consumo de qualquer conteúdo protegido com o RMS.
