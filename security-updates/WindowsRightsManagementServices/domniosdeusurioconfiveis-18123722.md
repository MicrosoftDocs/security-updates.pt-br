---
TOCTitle: Domínios de usuário confiáveis
Title: Domínios de usuário confiáveis
ms:assetid: 'a09b883f-f455-4c46-a4fd-d37b689e1d24'
ms:contentKeyID: 18123722
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747618(v=WS.10)'
---

Domínios de usuário confiáveis
==============================

Por padrão, o RMS não emite licenças de uso para usuários cujos certificados de conta de direitos tenham sido emitidos por um outro domínio de usuário. Um domínio de usuário é uma instalação do RMS que consiste em um cluster raiz de certificação, servidores ou clusters de licenciamento opcionais e bancos de dados associados.

Você pode configurar o RMS de modo que ele processe esse tipo de solicitação importando o certificado de licenciante para servidor de um outro domínio de usuário e adicionando-o à lista de domínios de usuário confiáveis. Quando isso é feito, os usuários cujos certificados de conta foram emitidos pelo domínio de usuário confiáveis podem enviar solicitações de licenças de uso para sua instalação. Essas licenças de uso serão processadas como se fossem solicitações de usuários internos.

| ![](images/Cc747618.note(WS.10).gif)Observação                                                                                    |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| O cluster raiz de certificação é automaticamente incluído na lista de domínios de usuário confiáveis de todos os servidores RMS que estão na mesma instalação. |

Você pode permitir que usuários de diferentes domínios compartilhem conteúdo protegido. Isso é descrito nos exemplos a seguir:

-   Sua organização está trabalhando intimamente com outra organização em documentos confidenciais que você deseja compartilhar e proteger. A outra organização também está executando o RMS. Cada uma das duas organizações pode adicionar a instalação de RMS da outra organização à sua lista de domínios de usuário confiáveis, de modo que os usuários que estejam em ambas possam trabalhar juntos em conteúdo protegido e trocá-lo através da Internet ou uma extranet.
-   Você só pode ter uma instalação de RMS em cada floresta do Active Directory. A sua organização implantou mais de uma floresta do Active Directory, e elas estão executando o RMS. Os usuários desejam compartilhar conteúdo protegido com outros usuários, independentemente da floresta em que residem. Para permitir isso, você pode adicionar a instalação do RMS das outras florestas à lista de domínios de usuário confiáveis de cada floresta.
-   Os usuários que estão na sua organização estão trabalhando com usuários em outra organização em documentos confidenciais que desejam proteger. A outra organização não está executando o RMS. Os usuários que estão na outra organização podem estabelecer contas do .NET Passport, e você pode adicionar o .NET Passport à lista de domínios de usuário confiáveis da sua instalação do RMS. Os usuários das duas empresas podem agora trabalhar em conteúdo protegido e trocá-lo pela Internet.

Para obter mais informações sobre domínios de usuário confiáveis e instruções detalhadas, consulte "Adicionando e removendo domínios de usuário confiáveis" e "Estabelecer diretivas de confiança" em "Operando um servidor RMS", nesta coleção de documentos.
