---
TOCTitle: Certificação de conta do RMS
Title: Certificação de conta do RMS
ms:assetid: 'c9a385c5-6dbb-47f5-a80f-69718e6f9deb'
ms:contentKeyID: 18123840
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747750(v=WS.10)'
---

Certificação de conta do RMS
============================

O processo de certificação de conta cria um certificado de conta de direitos, o qual associa uma conta de usuário a um computador específico e permite que o usuário consuma o conteúdo protegido pelo RMS nesse computador. Na primeira vez que um usuário publicar conteúdo protegido pelo RMS ou tentar consumir conteúdo protegido pelo RMS a partir de um computador cliente, o aplicativo habilitado para RMS enviará uma solicitação de certificado de conta de direitos ao serviço de certificação de conta do RMS.

O serviço de certificação pode autenticar o usuário usando a autenticação do Windows ou um certificado x.509 armazenado em um dispositivo de criptografia de hardware, como um cartão inteligente. Uma vez autenticado o usuário, o servidor RMS cria um certificado de conta de direitos para o usuário com base em suas credenciais autenticadas. Ele criptografa a chave particular do usuário com a chave pública do certificado de máquina do RMS do computador cliente e inclui a chave criptografada no certificado de conta de direitos. Depois, ele emite o certificado de conta de direitos para o aplicativo solicitante, o qual armazena o certificado de conta de direitos no computador ou dispositivo, de modo que esteja disponível para futuras solicitações de licença de publicação e de uso. O certificado de conta de direitos também é armazenado no banco de dados de configuração.

A certificação de conta segue o processo de ativação de máquina porque o certificado de máquina do RMS do computador cliente é exigido ao solicitar o certificado de conta de direitos.

Os usuários devem adquirir um certificado de conta de direitos para cada computador que utilizam. Se um usuário trabalhar em mais de um computador, será emitido um certificado de conta de direitos exclusivo para cada um deles, mas todos os computadores conterão o mesmo par de chaves destinado a esse usuário.

Quando um aplicativo habilitado para RMS solicita uma licença de uso, ele inclui o certificado de conta de direitos na solicitação. O serviço de licenciamento usa a chave pública do certificado de conta de direitos para criptografar a chave de conteúdo; isso garante que apenas o usuário autenticado poderá usar a licença de uso.

O processo de certificação da conta envolve as seguintes etapas:

1.  Na primeira vez que um usuário publicar conteúdo protegido pelo RMS ou tentar consumir conteúdo protegido pelo RMS em um determinado computador, o aplicativo habilitado para RMS enviará uma solicitação de certificado de conta de direitos ao serviço de certificação de conta que estiver em execução no servidor raiz de certificação.
2.  O serviço de autenticação de conta autentica o usuário usando a autenticação do Windows.
3.  O serviço de certificação de conta cria um certificado de conta de direitos para o usuário com base em suas credenciais autenticadas. Ele criptografa a chave particular do usuário com a chave pública do certificado de máquina do RMS e inclui a chave criptografada no certificado. Depois, ele emite o certificado de conta de direitos para o aplicativo solicitante.
4.  O aplicativo armazena o certificado de conta de direitos no computador ou dispositivo, de modo que esteja disponível para futuras solicitações de licença de publicação e de uso.

O serviço de certificação de conta utilizado pelo cliente para solicitar o certificado de conta de direitos depende do tipo de computador em que o cliente do RMS está instalado. Os computadores desktop padrão conectam-se ao serviço de certificação de conta (certification.asmx). Os serviços do servidor que foram habilitados para uso com o RMS SP1 recebem certificados de conta de direitos do serviço de certificação do servidor (ServeCertfication.asmx). Os dispositivos móveis que foram habilitados para uso com o RMS SP1 recebem certificados de conta de direitos do serviço de certificação de dispositivo móvel (MobileDeviceCertfication.asmx). Apenas o serviço de certificação de conta é habilitado em uma instalação padrão do RMS SP1.

Para obter mais informações sobre como usar o RMS SP1 com dispositivos móveis e serviços de servidor, consulte "Habilitando o suporte ao servidor RMS para dispositivos móveis e serviços de servidor" em "Operando um servidor RMS", nesta coleção de documentos.
