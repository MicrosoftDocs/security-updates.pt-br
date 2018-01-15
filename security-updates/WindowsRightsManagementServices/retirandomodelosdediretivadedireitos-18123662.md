---
TOCTitle: Retirando modelos de diretiva de direitos
Title: Retirando modelos de diretiva de direitos
ms:assetid: '32bf98c7-edda-4507-a4b8-4c11bddd6e60'
ms:contentKeyID: 18123662
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720239(v=WS.10)'
---

Retirando modelos de diretiva de direitos
=========================================

Para retirar um modelo de diretiva de direitos, você o exclui. Esse procedimento é descrito na seção [Excluir um modelo de diretiva de direitos](https://technet.microsoft.com/9c9a1496-cf55-4c65-a4c6-9fe245edce00), mais adiante neste tema. No entanto, em geral, você não deve excluir modelos de diretiva de direitos. Se desejar retirar um modelo de diretiva de direitos, você deve certificar-se de remover as cópias do modelo existentes nos computadores dos usuários. Isso deve ser feito porque uma solicitação é recebida no servidor RMS quando um autor usa um modelo de diretiva de direitos para publicar conteúdo. O RMS usa uma cópia do modelo de diretiva de direitos armazenado no banco de dados para responder à solicitação. Se o modelo de diretiva de direitos não existir no banco de dados, a solicitação falhará.


> [!note]  
> Uma maneira de gerenciar a retirada de um modelo de diretiva de direitos é criar um script que remova o modelo de todos os computadores de usuários.
