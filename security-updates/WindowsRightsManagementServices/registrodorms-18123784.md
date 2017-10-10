---
TOCTitle: Registro do RMS
Title: Registro do RMS
ms:assetid: '999db3e1-e3ab-4513-87d9-d584ee334c00'
ms:contentKeyID: 18123784
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747698(v=WS.10)'
---

Registro do RMS
===============

O processo de registro do servidor cria e fornece um certificado de licenciante para servidor. Os certificados de licenciante para servidor validam a identidade dos servidores que estão na implantação e fornecem validação das credenciais durante o consumo do conteúdo protegido pelo RMS. O primeiro servidor de cada cluster de licenciamento é registrado com o cluster raiz de certificação, como parte do processo de configuração. Servidores subseqüentes que estão no cluster não são registrados separadamente.

O servidor inicial de um cluster raiz de certificação (servidor raiz de certificação) deve ser registrado com o Microsoft Enrollment Service. Esse processo poderá ser feito automaticamente como parte da configuração, se o servidor raiz de certificação estiver conectado à Internet, ou processo de registro poderá ser concluído offline com a exportação de uma solicitação para um arquivo, seguida do envio do arquivo ao Microsoft Enrollment Service a partir de outro computador que esteja conectado à Internet. A solicitação de registro retornará um certificado de licenciante para servidor para o servidor raiz de certificação que pode ser importado usando-se as páginas da Web de administração do RMS.

A solicitação de inscrição inclui as seguintes informações:

-   Informações sobre revogação. Se a instalação do RMS for usar revogação padrão ou personalizada (terceiros). Se estiver sendo usada a revogação de terceiros, será incluída a chave pública da autoridade de revogação.
-   Chave pública do certificado. A chave pública do certificado de licenciante servidor. Essa chave pública é gerada no servidor RMS e enviada ao Serviço de Inscrição de Servidores da Microsoft para obtenção do certificado de licenciante para servidor.
-   SKU. O título oficial do SKU no RMS.
-   Versão. O número da versão de montagem do RMS.
-   URL. A URL da base do cluster do servidor RMS.

Quando o Serviço de Inscrição de Servidores da Microsoft fornece uma resposta à solicitação de registro, ele retorna as seguintes informações ao servidor RMS no formato XML:

-   Certificado de licenciante servidor.
-   Cadeia de certificados das autoridades signatárias.

Não importa se o servidor raiz de certificação RMS é registrado com o método online ou offline: as mesmas informações são transferidas. Nenhuma informação adicional é reunida em nenhum dos dois métodos.

Para obter informações sobre as etapas usadas para fazer o registro offline de um servidor, consulte "Para usar o registro offline para registrar um servidor raiz de certificação" em "Operando um servidor RMS", nesta coleção de documentos.

O processo de registro de cliente cria e fornece um certificado de licenciante para cliente que permite que um autor publique conteúdo protegido pelo RMS a partir de um computador não conectado à rede corporativa. Um autor pode solicitar um certificado de licenciante para cliente a qualquer hora. O registro do cliente não é necessário.

Todas as solicitações de registro são registradas.

Esta seção inclui:

-   [Registro do servidor raiz de certificação](https://technet.microsoft.com/f08bc919-f090-4843-b2ce-b40d558012ce)
-   [Sub-registro do servidor de licenciamento](https://technet.microsoft.com/7bc63397-9186-464c-8824-867038adce9b)
-   [Registro do cliente do RMS](https://technet.microsoft.com/9c1d07bf-7235-4694-8291-ac2e5b221f4a)
-   [Ativação de máquina do RMS](https://technet.microsoft.com/09a0d631-9860-477f-9d10-df61b3bfe125)
-   [Certificação de conta do RMS](https://technet.microsoft.com/c9a385c5-6dbb-47f5-a80f-69718e6f9deb)
