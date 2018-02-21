---
TOCTitle: Implantando o RMS em florestas
Title: Implantando o RMS em florestas
ms:assetid: 'd531dfdc-efff-4eb0-8d99-f1fd19d7a963'
ms:contentKeyID: 18123781
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747685(v=WS.10)'
---

Implantando o RMS em florestas
==============================

Se a sua organização inclui várias florestas do Active Directory, e você deseja habilitar o uso do RMS em toda ela, certifique-se de ter configurado a sua rede de tal modo que o RMS possa identificar e autenticar contas de usuários e grupos de distribuição que residem em florestas diferentes.

O RMS usa o Active Directory para identificar usuários e grupos de distribuição. Quando a implantação do Active Directory de uma organização inclui várias florestas, o RMS usa objetos de contato para obter as identificações de usuários e de grupos que fazem parte de uma floresta diferente daquela do servidor RMS. São necessárias três condições para que isso seja possível:

1.  Os servidores de certificação do RMS devem existir na outra floresta, e devem ser definidos objetos de contato para cada grupo remoto.
2.  As extensões de esquemas devem existir em florestas que contenham objetos de contato que lhes permitam apontar retroativamente para as florestas que contêm os objetos reais.
3.  Os atributos dos objetos de contato devem ser sincronizados para apontar retroativamente para as florestas que contêm o objeto real.

Por exemplo, suponha que os grupos sejam definidos e gerenciados em uma floresta, e que os usuários sejam definidos e gerenciados em uma outra floresta. Um usuário quer atribuir direitos a um conteúdo que é baseado em um membro de um dado grupo. Nesse cenário, *Servidor\_RMS\_U* é o servidor da floresta que contém as contas de usuário, e *Servidor\_RMS\_G* é o servidor da floresta que contém as contas de grupos. Foi estabelecido um domínio de usuário confiável entre esses dois servidores RMS. Para que o *Servidor\_RMS\_U* expanda com êxito a participação de grupo especificada na licença de publicação além dos limites da floresta, deve existir um objeto de contato na floresta local do Active Directory que represente o grupo que está na floresta remota. O RMS pode consultar os atributos do objeto de contato e descobrir que esse objeto representa um grupo que está em uma floresta diferente; em seguida, ele pode procurar um servidor RMS nessa floresta e determinar se existe um relacionamento de confiança entre ele mesmo e o outro servidor RMS. Quando o *Servidor\_RMS\_U* consultar o Active Directory sobre o grupo especificado na licença de publicação, o objeto de contato identificará que o grupo pertence a uma outra floresta. Quando o *Servidor\_RMS\_U* encaminhar a solicitação ao servidor RMS listado no SCP (ponto de conexão de serviço) desse domínio. O SCP identifica o *Servidor\_RMS\_G* como o servidor de certificação RMS do domínio. O *Servidor\_RMS\_U* consultará o *Servidor\_RMS\_G* para obter a participação para o grupo.

O atributo que o RMS consulta para obter essa informação é **msExchOriginatingForest**. Por padrão, esse atributo se encontra instalado no esquema do Active Directory, se o Exchange Server 2003 estiver instalado na floresta. É preciso ter esse atributo na floresta de cada esquema do Active Directory que participará do RMS. Se você não estiver usando o Exchange Server 2003, será possível adicionar essas extensões de esquema baixando o RMS Administration Toolkit. Esse kit de ferramentas contém um arquivo de esquema e instruções sobre como adicioná-lo ao Active Directory.

Esses atributos devem ser sincronizados de modo que o objeto de contato aponte para o objeto real nas outras florestas. Depois de adicionar o atributo ao esquema do Active Directory, você deve configurar o seu valor para ser o nome de domínio totalmente qualificado da floresta na qual o grupo reside, por exemplo, corp.fabrikam.com.

Você pode conseguir isso usando o MIIS (Microsoft Identity Integration Server) 2003 ou o IIFP (Identity Integration Feature Pack) e o agente de gerenciamento para a GAL (lista de endereços global) do Active Directory.

Você deve habilitar o servidor RMS local a fim de ter privilégios suficientes para pesquisar o Active Directory remoto e chamar as interfaces do .NET Remoting que estão na instalação remota do RMS.

Para oferecer suporte à expansão de grupo entre florestas, a conta usada para a conta de serviço RMS em cada floresta também deve ter permissões de leitura e execução para o Active Directory. O RMS concede automaticamente acesso de leitura no Active Directory a todos os usuários autenticados que possuem credenciais de domínio. Para aumentar a segurança, você pode remover esse acesso da DACL (lista de controle de acesso condicional) e substituí-lo por contas de serviço individuais de florestas diferentes.

Dependendo das relações de confiança do Active Directory existentes entre as florestas local e remota, as permissões necessárias para a conta de serviço RMS podem ser diferentes. A lista a seguir identifica os modelos de confiança e as permissões que são necessários:

-   **Existe um relacionamento de confiança bidirecional**. A floresta do RMS local confia na floresta onde o grupo se originou e é de confiança dela. A conta de serviço RMS para o servidor RMS que está em cada floresta pode ser qualquer conta de domínio válida que esteja na floresta. Certifique-se de ter adicionado a conta de serviço RMS local à DACL da pasta \\Inetpub\\wwwroot\\\_wmcs\\drmRemote em todos os servidores RMS da floresta da qual o grupo se originou.
-   **Existe um relacionamento de confiança unidirecional**. A floresta do RMS local confia na floresta onde o grupo se originou, mas não é da confiança dessa floresta. A conta de serviço RMS para todos os servidores RMS que estão na organização deve ser de uma conta de domínio válida que está na floresta confiável. Adicione essa conta à DACL da pasta \\Inetpub\\wwwroot\\\_wmcs\\drmRemote em todos os servidores RMS da floresta da qual o grupo se originou.
-   **Não há nenhum relacionamento de confiança**. As florestas que estão na organização não podem autenticar usuários e grupos de outras florestas. É recomendável que você não use expansão de grupo entre florestas, se as florestas envolvidas não tiverem um relacionamento de confiança. No entanto, caso se trate de um requisito operacional, você poderá habilitar esse cenário configurando a conta de serviço RMS como uma conta de domínio válida nas duas florestas e usar o mesmo nome de usuário e senha para ambas. Além disso, deverá ser criada uma conta de máquina local em cada servidor front-end do RMS, que também possui exatamente os mesmos nomes de usuário e senhas que as contas de domínio usadas para a conta de serviço RMS em ambas as florestas. Assim, serão concedidas permissões suficientes ao serviço local para autenticar no Active Directory remoto e no servidor RMS remoto.

Usando as diretivas de confiança do RMS
---------------------------------------

Quando o RMS é implantado em uma organização com várias florestas, deve-se implantar um servidor de certificação RMS em cada floresta que hospeda contas de usuário que participarão do sistema RMS. Caso deseje que usuários de florestas diferentes compartilhem conteúdo protegido pelo RMS, você precisará configurar as diretivas de confiança do RMS, de modo que os certificados e as licenças gerados pelo outro servidor RMS sejam confiáveis. Há duas diretivas de confiança que podem ser usadas com o RMS: domínios de usuário confiáveis e domínios de publicação confiáveis. Os domínios de usuário confiáveis habilitam um servidor RMS a confiar em RACs (certificados de conta de direitos) gerados por um outro servidor de certificação RMS e emitem licenças de uso para usuários com RACs do outro servidor. Os domínios de publicação confiáveis habilitam um servidor RMS a gerar licenças de uso com base em licenças de publicação que especificam o outro servidor de licenciamento.

Eis algumas sugestões de como você poderia usar as diretivas de confiança para oferecer suporte a várias florestas:

-   Um cluster de certificação RMS em cada floresta com um único cluster de licenciamento compartilhado por todos os usuários. O cluster de licenciamento RMS seria configurado com um domínio de usuário confiável que incluiria todos os clusters de certificação RMS. Os clientes do RMS seriam configurados usando uma chave do Registro para se conectarem ao cluster de licenciamento e obterem licenças de uso.
-   Um cluster de certificação e de licenciamento RMS dentro de cada floresta com um domínio de usuário confiável configurado em cada cluster para confiar em servidores RMS de outras florestas. Cada usuário utilizaria o servidor RMS de sua floresta para obter licenças de uso e poderia descobrir seu servidor de licenciamento por meio do ponto de conexão de serviço no Active Directory.
-   Se os consumidores do conteúdo protegido pelo RMS fizerem parte de uma floresta que não tem acesso à floresta a partir da qual o conteúdo foi publicado, então um domínio de publicação confiável poderá ser estabelecido para permitir que o conteúdo seja licenciado e consumido. Os domínios de publicação confiáveis exigem que a chave particular do servidor RMS usado para publicar o conteúdo seja importada.

Para obter mais informações sobre a configuração de diretivas de confiança, consulte "Gerenciando confiança e diretiva de confiança" na seção "Operando um servidor RMS", nesta coleção de documentos.
