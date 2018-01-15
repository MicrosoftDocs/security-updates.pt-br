---
TOCTitle: Adicionando e removendo domínios de usuário confiáveis
Title: Adicionando e removendo domínios de usuário confiáveis
ms:assetid: '7c440b15-01c4-49f1-b43c-00f67f3388c1'
ms:contentKeyID: 18123660
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747571(v=WS.10)'
---

Adicionando e removendo domínios de usuário confiáveis
======================================================

Por padrão, o RMS não atende a solicitações de serviço de usuários cujos certificados de conta de direitos tenham sido emitidos por uma outra instalação do RMS. No entanto, é possível adicionar domínios de usuários à lista de domínios de usuários confiáveis, o que permite que o RMS processe essas solicitações.

Para cada domínio confiável, você também pode adicionar e remover usuários ou grupos de usuários específicos. Além disso, você pode remover um domínio de usuário confiável; no entanto, não pode remover o cluster raiz de certificação desta floresta do Active Directory dos domínios de usuários confiáveis. Cada servidor RMS em uma implantação, inclusive o servidor raiz de certificação, confia no cluster raiz de certificação em sua própria floresta.

É possível gerenciar domínios de usuários confiáveis da seguinte maneira:

-   Para oferecer suporte a usuários externos em geral, você pode adicionar o serviço Microsoft® .NET Passport à lista de domínios confiáveis. Isso permite que um servidor RMS que esteja em sua empresa processe solicitações de licença que incluem um certificado de conta de direitos emitido pelo serviço Microsoft .NET Passport.
-   Para confiar em usuários externos de uma instalação do RMS de outra organização, é possível adicionar a organização à lista de domínios de usuário confiáveis. Assim, um servidor RMS pode processar uma solicitação de licença que inclui um certificado de conta de direitos emitido por um servidor RMS que está na outra organização.
-   Da mesma maneira, para processar solicitações de licença de usuários dentro de sua organização que residem em uma floresta diferente do Active Directory, você pode adicionar a instalação do RMS naquela floresta à lista de domínios de usuários confiáveis. Isso permite que um servidor RMS que está na floresta atual processe uma solicitação de licença que inclui um certificado de conta de direitos emitido por um servidor RMS na outra floresta.
-   Para cada domínio de usuário confiável, você pode especificar quais são os domínios de email confiáveis. Para domínios Passport confiáveis, você pode especificar quais domínios ou usuários de email não são confiáveis.

Para adicionar uma instalação do RMS à lista de domínios de usuários confiáveis, você deve importar o certificado de licenciante servidor da instalação do RMS que deseja adicionar. O administrador deve primeiro exportar o certificado de licenciante do servidor ou cluster a confiar e enviar o arquivo de certificado para você. Em seguida, você pode importar o arquivo especificando sua localização. Para salvar o arquivo, o usuário que está conectado deve ter permissões para a pasta compartilhada. As informações sobre chave particular não são transferidas quando você instala um domínio de usuário confiável.

Para obter instruções detalhadas sobre como estabelecer domínios de usuário confiáveis, consulte a seção "[Adicionar um domínio de usuário confiável](https://technet.microsoft.com/ed672e58-6272-4ac0-a434-d1d938037e93)", mais adiante neste tema.
