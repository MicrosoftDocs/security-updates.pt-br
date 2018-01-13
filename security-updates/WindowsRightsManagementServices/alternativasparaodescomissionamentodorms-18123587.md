---
TOCTitle: Alternativas para o descomissionamento do RMS
Title: Alternativas para o descomissionamento do RMS
ms:assetid: '4d32f35e-997d-4d10-ab66-efe217e853f7'
ms:contentKeyID: 18123587
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720268(v=WS.10)'
---

Alternativas para o descomissionamento do RMS
=============================================

Se você ainda pretende usar o RMS na sua organização, mas precisa interromper o uso de determinados servidores RMS por qualquer motivo, considere utilizar as alternativas a seguir para o descomissionamento.

**Configurar um domínio de publicação confiável**

Todas as informações protegidas pelo RMS são criptografadas pela chave particular do servidor RMS. Um domínio de publicação confiável permite importar a chave particular de um servidor RMS para outro. Isso confere a um servidor RMS a capacidade de emitir licenças de uso em relação a licenças de publicação que foram criadas por um outro servidor RMS. Uma vez exportada a chave, o servidor pode ser desconfigurado e desinstalado.

**Configurar um grupo de superusuários**

Se um conteúdo protegido por RMS não puder ser aberto porque nenhum usuário possui os respectivos direitos, você pode conceder ao grupo de superusuários controle total sobre todo o conteúdo protegido pelo RMS que for publicado por esse servidor. Os membros do grupo de superusuários recebem direitos completos de proprietários em todas as licenças de uso emitidas pelo servidor ou cluster RMS no qual o grupo de superusuários está configurado. Isso significa que membros desse grupo podem descriptografar todos os arquivos de conteúdo protegido e remover sua proteção. Por exemplo, um membro desse grupo pode remover a proteção de arquivos publicados por um funcionário que saiu da empresa, para que um novo proprietário possa publicar e gerenciar os arquivos.

O grupo de superusuários não inclui automaticamente qualquer membro, mesmo administradores. Esse grupo deve existir dentro do Active Directory como um grupo de distribuição com um atributo de endereço de email de valor igual ao nome do grupo, no formato "*nome\_grupo*@*nome\_domínio*.com." O nome do grupo deve corresponder exatamente ao atributo de endereço de email e deve fazer distinção entre maiúsculas e minúsculas.
