---
TOCTitle: Criptografia e chaves do RMS
Title: Criptografia e chaves do RMS
ms:assetid: '6ed69817-dab0-4845-b2a4-74203f95f7cf'
ms:contentKeyID: 18123713
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747615(v=WS.10)'
---

Criptografia e chaves do RMS
============================

Conteúdo protegido é sempre criptografado. Os certificados e as licenças usados pelo RMS também podem ter conteúdo criptografado, o qual só poderá ser descriptografado pela entidade apropriada. Um aplicativo habilitado para RMS usa uma chave de conteúdo para criptografar os dados. Todos os servidores, computadores clientes e contas de usuários do RMS SP1 possuem um par de chaves RSA de 1024 bits. O RMS usa essas chaves para criptografar a chave de conteúdo que está nas licenças de publicação e de uso e para assinar certificados e licenças do RMS; esse processo assegura que o servidor permitirá o acesso apenas aos usuários e computadores autorizados.

Esta seção inclui:

-   [Definições de chaves do RMS](https://technet.microsoft.com/b052305c-1db7-434a-bad9-26d704156776)
-   [Chaves do servidor RMS](https://technet.microsoft.com/5f4100a1-9aa5-42af-85c8-4bc691022f06)
-   [Chaves de máquina do RMS](https://technet.microsoft.com/56e59ec2-f681-4ca2-98c7-72218ab9e9d9)
-   [Chaves do certificado de licenciante para cliente](https://technet.microsoft.com/28781125-2692-4ff9-99b1-e09227d72966)
-   [Chaves de usuários](https://technet.microsoft.com/12dad6e2-64e7-4bab-bde7-b72f90f5cb05)
-   [Chaves de conteúdo do RMS](https://technet.microsoft.com/63c814bf-2809-477e-a2db-d90370442075)
