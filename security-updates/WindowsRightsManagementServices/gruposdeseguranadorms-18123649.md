---
TOCTitle: Grupos de segurança do RMS
Title: Grupos de segurança do RMS
ms:assetid: '25749a83-8c12-48ec-96ad-296d31fd55d4'
ms:contentKeyID: 18123649
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720215(v=WS.10)'
---

Grupos de segurança do RMS
==========================

A instalação do RMS cria dois grupos: o Grupo de Serviço RMS e o grupo de superusuários.

O Grupo de Serviço RMS é um grupo de segurança local que recebe permissões suficientes para ter acesso a todos os recursos necessários às operações do RMS. Durante a instalação, o administrador especifica uma conta de usuário para ser usada como conta de serviço RMS. Essa conta de usuário é automaticamente configurada como um membro do grupo de serviço do RMS e portanto recebe suas permissões. Na maioria de suas operações normais, o RMS é executado como se fosse essa conta de usuário.

Um outro grupo importante no RMS é o de superusuários. Esse grupo tem controle total sobre todo o conteúdo, o que significa que um membro desse grupo pode descriptografar todos os arquivos de conteúdo protegidos pelo RMS e remover todas as proteções do RMS que eles contêm. O grupo de superusuários não possui membros, por padrão, nem inclui administradores do RMS automaticamente. O gerenciamento da participação desse grupo é crucial para a segurança do conteúdo protegido pelo RMS. Para obter mais informações, consulte "Usando o grupo de superusuários" em "Operando um servidor RMS", nesta coleção de documentos.
