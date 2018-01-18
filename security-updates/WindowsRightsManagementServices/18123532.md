---
TOCTitle: Planejando para usuários externos do RMS
Title: Planejando para usuários externos do RMS
ms:assetid: '107e1338-4dcf-4ed5-a49d-e875cc883db1'
ms:contentKeyID: 18123532
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720190(v=WS.10)'
---

Planejando para usuários externos do RMS
========================================

Esta seção descreve as topologias que você pode implementar para permitir que sua organização e seus usuários externos compartilhem conteúdo protegido por RMS pela Internet.

É possível implantar clusters de RMS para uso interno e externo usando uma das seguintes opções:

-   Configure a URL do cluster raiz de certificação com uma URL que possa ser acessada pela Internet. Verifique se essa URL está resolvida na intranet para servidores RMS do mesmo cluster. Quando você faz isso, a URL de licença de publicação usada pelos computadores dos usuários finais para aquisição de licenças passa a funcionar na intranet e na Internet.
-   Configure um cluster de RMS separado especificamente para publicação na Internet. Todos os conteúdos que precisarem ser licenciados a partir da Internet devem ser publicados nesse cluster. Se o conteúdo precisar estar disponível tanto interna quanto externamente, ele deve ser publicado nos dois locais. Outra alternativa seria os usuários poderem contatar o servidor Internet.

Permitindo usuários externos
----------------------------

Você pode incluir usuários externos na instalação do RMS se criar contas internas para esses usuários e permitir que obtenham acesso à rede corporativa por meio de uma VPN. A conta pode ter uma caixa de correio interna ou um endereço de email que aponte para uma caixa de correio externa.

Se você usar uma caixa de correio interna, os autores internos deverão especificar o endereço de email associado a essa caixa de correio (em vez de outro email que o usuário externo tenha fora da organização) quando publicarem o conteúdo protegido por RMS. Caso você use uma caixa de correio externa, os autores internos deverão especificar o endereço de email externo da conta quando publicarem conteúdo protegido por RMS.

Para fornecer segurança de rede sem deixar de oferecer suporte ao acesso à rede por usuários externos, você pode criar uma floresta separada do Active Directory para contas de parceiros. Com essa topologia, é possível criar um cluster raiz de certificação separado para a parte do sistema RMS que faz interface com a Internet. Isso permite que usuários externos recebam os certificados de máquina de RMS e de direitos de conta desse cluster de raiz de identificação que faz interface com a Internet na primeira vez em que obtiverem acesso ao conteúdo protegido por RMS.

Se você decidir implementar uma floresta separada para parceiros externos contendo as contas dos parceiros, é necessário que o RMS seja instalado nessa floresta. Em seguida, use o recurso de domínio de publicação confiável do RMS para estabelecer uma relação de confiança entre os dois servidores RMS. Também é necessário fazer com que os registros de DNS externos identifiquem a URL do cluster externo da instalação do RMS na floresta criada para os parceiros externos. A criação dessa relação de confiança permite que o servidor RMS externo emita licenças de uso para todo o conteúdo emitido pelo sistema RMS e vice-versa.

Como uma alternativa para configurar um servidor RMS na floresta externa, você pode usar um servidor como o ISA para filtrar o tráfego de entrada e reverter as solicitações de licença de proxy RMS para o servidor RMS interno.

Usando certificados externos
----------------------------

Para permitir que usuários externos obtenham acesso ao conteúdo protegido por RMS, configure um servidor RMS separado como um servidor de licenciamento que faça interface com a Internet, publique o conteúdo desse servidor e especifique relações confiáveis para ele.

A parte da interface com a Internet da implantação do RMS é um servidor de licenciamento separado, dedicado à interface com a Internet. Faz parte do mesmo cluster que a instalação de licenciamento interno e usa o mesmo banco de dados e a mesma URL que a instalação de licenciamento interno; é o único servidor que pode aceitar tráfego proveniente da Internet.

Quando usuários externos solicitarem uma licença de uso desse servidor de licenciamento RMS, usarão um certificado de conta de direitos de outro serviço de certificação do RMS no qual esse servidor de licenciamento confie.

#### Confiando em certificados de conta de direitos baseados no Passport

Sua organização pode optar por confiar em certificados de conta de direitos baseados em credenciais do Microsoft .NET Passport. Esses certificados de conta exigem que os usuários obtenham certificados de conta de direitos diretamente do Microsoft Certification Service hospedado na Internet.

Neste modelo, os usuários externos recebem certificados de máquina do RMS e certificados de conta de direitos da Microsoft. Quando o conteúdo é publicado, a conta do Microsoft .NET Passport do usuário externo deve ser nomeada como um destinatário na licença de publicação.

A conta do Microsoft® .NET Passport deverá corresponder à conta do .NET Passport usada no momento em que o usuário baixou o certificado de conta de direitos da Microsoft. É necessário que o autor especifique essa conta quando adicionar destinatários no aplicativo habilitado para RMS. Se as contas não forem iguais, o conteúdo não poderá ser consumido.

#### Confiando em outros certificados externos

Se a empresa do usuário externo também tiver uma implantação de RMS, você poderá optar por configurar um relacionamento de confiança com essa empresa. Para fazer isso, solicite à empresa que exporte o certificado de licenciante para servidor RMS e envie-o para você. Em seguida, você pode importar o certificado para o servidor de licenciamento com interface com a Internet usando o console de administração do RMS.
