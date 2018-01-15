---
TOCTitle: Determinando requisitos de acesso
Title: Determinando requisitos de acesso
ms:assetid: 'eb2ce9a5-0430-4811-bd40-4a94a84426a8'
ms:contentKeyID: 18123873
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747790(v=WS.10)'
---

Determinando requisitos de acesso
=================================

Durante esta parte da fase de planejamento, você já deve ter identificado o escopo da sua implementação do RMS. Ao avaliar a segurança do seu sistema RMS, você deve considerar métodos que permitam limitar o escopo a determinados participantes e assegurar que os dados que eles estão protegendo com o RMS também sejam protegidos com o uso das práticas recomendadas tradicionais de segurança de informações. Você também deve se certificar de que o acesso ao servidor RMS para administração e configuração é restrito apenas a administradores confiáveis. Os métodos de segurança de acesso que podem ser usados com o RMS incluem:

-   **ACLs (listas de controle de acesso)**. Cada um dos serviços do RMS na Web e o site Administração do RMS podem ser protegidos por ACLs. Para assegurar que apenas os usuários autorizados consigam usar o serviço RMS, você pode usar listas de controle de acesso para restringir a capacidade de os usuários se conectarem aos serviços de certificação e licenciamento do RMS. Isso pode ser útil se você deseja que apenas determinados grupos possam criar conteúdo protegido ou se deseja habilitar apenas determinados grupos a obter licenças para conteúdo protegido.
-   **Autenticação de clientes**. Você também pode exigir cartões inteligentes ou a ocorrência de uma outra autenticação de cliente quando um usuário tentar adquirir uma licença de uso ou certificado. Isso pode ajudar a reduzir a possibilidade de que um usuário não autorizado abra conteúdo usando uma sessão de usuário autorizado.
-   **SSL (Secure Sockets Layer)**. Para fornecer um nível maior de proteção, você também pode exigir uma conexão SSL entre os clientes do RMS e o servidor RMS. Recomenda-se que você habilite a SSL e exija criptografia de 128 bits em cada arquivo de serviço do RMS na Web. Esses arquivos possuem a extensão de nome de arquivo .asmx e estão localizados nos diretórios virtuais Licenciamento, Certificação e Admin. Se você quiser abrir as páginas da Web de **Administração do RMS** com um navegador que está em um computador remoto, será necessário habilitar a SSL. Entretanto, mesmo com a SSL habilitada, você não poderá abrir a página **Administração Global** em um computador remoto.
    Para obter informações sobre como configurar SSL em servidores, consulte a Ajuda do IIS.

Em algumas organizações, é necessário contar com um sistema de licenciamento por departamento que seja isolado dos demais departamentos e que seja protegido. Nesse cenário, pode-se usar um servidor RMS para fornecer um meio para estabelecer diretivas de gerenciamento de direitos de informação. Caso exista um departamento ou outra filial da sua organização que controle conteúdo altamente confidencial, considere a configuração de um servidor de licenciamento ou de cluster de licenciamento separado para que o gerenciamento do licenciamento e da publicação do conteúdo seja separado do restante da organização. Um servidor de licenciamento é criado com sub-registro com o servidor raiz de certificação (ou cluster), que fornece certificação e outros serviços para cada servidor de licenciamento. No entanto, os servidores de licenciamento oferecem seus próprios serviços de licenciamento e publicação.

Contas de usuário, ACLs e segurança física são elementos importantes na implantação. Antes de implementar o RMS em um ambiente de produção, certifique-se de avaliar e implementar todas as práticas recomendadas de segurança e o modelo de segurança, conforme apropriado.
