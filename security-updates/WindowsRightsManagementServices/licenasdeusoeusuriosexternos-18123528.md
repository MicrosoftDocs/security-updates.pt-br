---
TOCTitle: Licenças de uso e usuários externos
Title: Licenças de uso e usuários externos
ms:assetid: '02db9bda-180e-438f-863d-26252083a471'
ms:contentKeyID: 18123528
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720176(v=WS.10)'
---

Licenças de uso e usuários externos
===================================

O RMS permite que os autores compartilhem conteúdo protegido com usuários externos autorizados via Internet. O RMS oferece igual proteção à publicação de conteúdo para usuários internos e externos, porque os direitos relacionados ao conteúdo devem ser licenciados por um servidor RMS. Isso permite que as organizações compartilhem e trabalhem em conjunto em documentos confidenciais, como contratos, pela Internet.

Um usuário externo normalmente ganha acesso ao RMS via Internet. Se um usuário externo obtiver acesso à rede interna diretamente, como por meio de uma conexão de rede virtual privada, ele será funcionalmente equivalente a um usuário interno. Não importa se o usuário pertence à organização que faz a publicação ou é externo a ela, o processo de aquisição de uma licença de uso é essencialmente aquele já descrito em "[Aquisição de licenças de uso](https://technet.microsoft.com/0b6cde34-418a-4dee-9d27-b65b93b535ac)", já mencionado neste tema. O usuário não precisa estar dentro da rede do autor ou possuir uma conta de usuário nela para solicitar uma licença de uso.

Tudo o que é necessário é que:

-   O usuário tem um certificado de conta de direitos válido.
-   O usuário tem acesso ao servidor de licenciamento do RMS que emitiu a licença de publicação, o qual pode estar na intranet ou em uma extranet.
-   A instalação do RMS que emitiu o certificado de conta do usuário está na lista de domínios de usuários confiáveis da instalação do RMS que emite a licença de uso.

Os seguintes tipos de usuários externos podem obter licenças de uso:

-   Usuários cujas contas fazem parte de uma floresta diferente do Active Directory que também tem uma instalação do RMS. A instalação do RMS na outra floresta deve ser definida como domínios de usuário confiáveis para essa instalação.
-   Usuários de outra organização que também está executando uma instalação do RMS que foi adicionada à lista de domínios de usuário confiáveis para essa instalação.
-   Usuários que têm certificados de conta de direitos baseados no .NET Passport quando o Serviço de Certificação do Microsoft RMS está na lista de domínios de usuário confiáveis para essa instalação.

Você pode adicionar uma organização separada ou outra instalação do RMS na sua organização à lista de domínios de usuário confiáveis. Depois de adicionar um domínio, é possível definir em quais domínios de email confiar naquele domínio, bem como selecionar se os identificadores de segurança (SIDs) que estão nesse domínio são confiáveis ou não.

Outra organização ou uma instalação do RMS que esteja em sua organização podem adicionar a sua instalação do RMS à própria lista de domínios de usuário confiáveis, para que os servidores RMS delas possam processar solicitações de licença de uso dos seus usuários.

Para obter mais informações sobre como criar domínios de usuário confiáveis entre o RMS e outras organizações, consulte "[Domínios de usuário confiáveis](https://technet.microsoft.com/a09b883f-f455-4c46-a4fd-d37b689e1d24)" mais adiante neste tema e "Adicionando e removendo domínios de usuário confiáveis" em "Operando um servidor RMS" nesta coleção de documentos.
