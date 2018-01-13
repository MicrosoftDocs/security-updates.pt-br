---
TOCTitle: Domínios de publicação confiáveis
Title: Domínios de publicação confiáveis
ms:assetid: 'bca1c33a-d3ef-42b5-adbe-6e104979a71f'
ms:contentKeyID: 18123823
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747738(v=WS.10)'
---

Domínios de publicação confiáveis
=================================

Por padrão, os servidores RMS não emitem licenças de uso em relação a licenças de publicação emitidas por um servidor RMS de um outro cluster. Há situações, no entanto, em que o mesmo servidor ou cluster não pode emitir tanto licenças de publicação como de uso para uma parte de conteúdo protegido. Isso pode ocorrer, por exemplo, quando um determinado cluster do RMS for retirado e um outro entrar em seu lugar, como ocorre na fusão de duas empresas. Nessa situação, um cluster do RMS precisa ter a capacidade de emitir licenças de uso em relação a licenças de publicação que foram criadas por um outro cluster do RMS.

Você pode configurar um cluster do RMS para confiar nas licenças de publicação emitidas por um outro cluster do RMS e emitir licenças de uso em relação a elas, implementando um domínio de publicação confiável. Para fazer isso, importe o certificado de licenciante para servidor e a chave particular do outro servidor e adicione-os à lista de domínios de publicação confiáveis. As chaves particulares que são importadas são usadas somente para descriptografar licenças de publicação assinadas e não para assinar novas licenças.

Para obter mais informações sobre domínios de usuário confiáveis e instruções detalhadas, consulte "Adicionando e removendo domínios de publicação confiáveis" e "Estabelecer diretivas de confiança" em "Operando um servidor RMS", nesta coleção de documentos.
