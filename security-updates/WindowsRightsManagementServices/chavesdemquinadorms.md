---
TOCTitle: Chaves de máquina do RMS
Title: Chaves de máquina do RMS
ms:assetid: '56e59ec2-f681-4ca2-98c7-72218ab9e9d9'
ms:contentKeyID: 18123676
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747572(v=WS.10)'
---

Chaves de máquina do RMS
========================

Um computador cliente com RMS SP1 possui um par de chaves com chaves RSA de 1024 bits, as quais são chamadas chaves de máquina.

A chave pública de máquina é usada para criptografar a chave particular de um certificado de conta de direitos. O certificado de máquina do RMS contém a chave pública da máquina. O cofre contém a chave particular da máquina, a qual é usada para descriptografar o certificado de conta de direitos, a fim de permitir o uso da chave particular do usuário.
