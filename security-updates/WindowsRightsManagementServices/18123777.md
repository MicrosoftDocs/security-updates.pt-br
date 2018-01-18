---
TOCTitle: Publicação online
Title: Publicação online
ms:assetid: '962c4e83-cf34-4c61-9589-31d24b0299fb'
ms:contentKeyID: 18123777
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747694(v=WS.10)'
---

Publicação online
=================

O diagrama a seguir descreve o processo de publicação online.

![](images/Cc747694.897e47b6-fffe-4b11-bc9f-be58539b9f19(WS.10).gif)

O processo de publicação online envolve as seguintes etapas:

1.  O autor do conteúdo cria um documento e usa o aplicativo habilitado para RMS a fim de especificar usuários e aplicar direitos e condições ao conteúdo.
2.  O aplicativo habilitado para RMS gera uma chave simétrica de conteúdo e envia uma solicitação de licença de publicação ao servidor do certificado ou a um servidor de licenciamento. A solicitação inclui a chave de conteúdo e as configurações de uso.
3.  O servidor de licenciamento gera a licença de publicação, criptografa a chave de conteúdo com a chave pública do servidor e, em seguida, retorna a licença de publicação ao aplicativo habilitado para RMS.
4.  O aplicativo criptografa o arquivo com a chave de conteúdo e vincula a licença de publicação ao arquivo.
5.  O aplicativo habilitado para RMS do computador do consumidor do conteúdo envia uma solicitação ao servidor RMS (que emitiu a licença de publicação) com o certificado de conta de direitos do consumidor, a fim de solicitar uma licença de uso para o documento.
6.  O servidor RMS valida as credenciais do usuário. Se a validação do usuário for bem-sucedida, uma licença de uso será gerada e retornada ao aplicativo habilitado para RMS do computador do consumidor do conteúdo.
7.  O aplicativo habilitado para RMS abre o documento e concede direitos ao usuário, de acordo com os parâmetros definidos na licença de uso.
