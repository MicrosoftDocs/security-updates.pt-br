---
TOCTitle: Certificados de conta de direitos
Title: Certificados de conta de direitos
ms:assetid: '2ff315cc-211d-4e6e-85e8-56867c2abd94'
ms:contentKeyID: 18123538
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720230(v=WS.10)'
---

Certificados de conta de direitos
=================================

As organizações devem identificar os usuários que são entidades confiáveis no sistema RMS. Para fazer isto, o RMS emite certificados de conta de direitos que associam contas de usuários a computadores específicos. O certificado de conta de direitos do usuário deve ser incluído na solicitação de certificados de licenciante para cliente e licenças de uso. Um certificado de licenciante para cliente permite que um autor publique conteúdo protegido pelo RMS, como arquivos e emails, enquanto está offline. Uma licença de uso permite que um usuário consuma o conteúdo protegido pelo RMS. Cada certificado de conta de direitos contém a chave pública do usuário, que é usada para criptografar os dados destinados a esse usuário.

Há dois tipos de certificados de conta de direitos: padrão e temporário. É possível especificar o período de validade dos dois tipos. Certificados padrão têm uma duração que é especificada em dias (365 dias, por padrão). Certificados de conta temporários têm uma duração que é especificada em minutos (15 minutos, por padrão). Certificados de conta temporários permitem que usuários consumam conteúdo temporariamente, por exemplo em um quiosque, quando eles não podem obter acesso ao computador que usam normalmente. Isso evita que outro usuário consuma o conteúdo desse computador em um momento posterior.
