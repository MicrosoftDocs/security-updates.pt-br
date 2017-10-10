---
TOCTitle: Aquisição de licenças de uso
Title: Aquisição de licenças de uso
ms:assetid: '0b6cde34-418a-4dee-9d27-b65b93b535ac'
ms:contentKeyID: 18123576
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720194(v=WS.10)'
---

Aquisição de licenças de uso
============================

Para consumir conteúdo protegido pelo RMS, o usuário deve adquirir uma licença de uso no serviço de licenciamento do RMS. A figura a seguir ilustra o processo de solicitação e recebimento de uma licença de uso.

![](images/Cc720194.37b8d28c-9749-4e81-bc6a-22692fefb8b6(WS.10).gif)

O processo de aquisição de uma licença de uso envolve as seguintes etapas:

1.  O usuário recebe um arquivo protegido através de um canal de distribuição típico e depois abre esse arquivo com um aplicativo habilitado para RMS. Se o usuário não possuir um certificado de conta de direitos no computador ou dispositivo atual, ele deverá adquiri-lo.
2.  O aplicativo habilitado para RMS envia uma solicitação de licença de uso ao servidor que emitiu a licença de publicação para o conteúdo protegido. A solicitação inclui o certificado de conta de direitos do usuário (que contém a chave pública do usuário) e a licença de publicação (que contém a chave simétrica do conteúdo).
    Uma licença de publicação que é emitida por um certificado de licenciante para cliente inclui a URL do servidor que emitiu o certificado. Nesse exemplo, a solicitação de uma licença de uso vai para o servidor que emitiu o certificado de licenciante para cliente e não para o computador que emitiu a licença de publicação.
3.  O servidor de licença valida se o usuário está autorizado, verifica se ele está nomeado na licença de publicação e, em seguida, cria uma licença de uso. O servidor valida o certificado da conta do usuário e determina as permissões que o usuário recebeu, diretamente ou como um membro de um grupo para o qual foram concedidas permissões.
    O servidor descriptografa a chave simétrica do conteúdo usando a chave particular do servidor, criptografa-a novamente usando a chave pública do recipiente e adiciona-a à licença de uso. Essa etapa garante que somente o usuário indicado possa descriptografar a chave do conteúdo e o conteúdo protegido.
    O servidor adiciona todas as condições relevantes à licença de uso, como a exclusão de um aplicativo ou versão do Windows. Essas condições são aplicadas pelo cliente no momento em que a licença de uso é vinculada ao conteúdo protegido pelo RMS.
4.  Quando a validação é concluída, o servidor de licença retorna a licença de uso para o computador cliente do usuário.
