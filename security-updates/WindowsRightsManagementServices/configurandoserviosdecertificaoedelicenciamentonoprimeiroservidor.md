---
TOCTitle: Configurando serviços de certificação e de licenciamento no primeiro servidor
Title: Configurando serviços de certificação e de licenciamento no primeiro servidor
ms:assetid: 'cce29a2f-984f-48ed-9187-0eb68286ec5b'
ms:contentKeyID: 18123851
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747756(v=WS.10)'
---

Configurando serviços de certificação e de licenciamento no primeiro servidor
=============================================================================

Para configurar o RMS em uma floresta, primeiro instale e configure um servidor. O primeiro servidor que você implanta é o servidor raiz de certificação. Esse servidor fornece suporte a certificação e licenciamento e pode ser usado sozinho em uma configuração de um único servidor ou como servidor inicial de um cluster raiz de certificação.

Funções, permissões e direitos necessários para a instalação e a configuração de servidores RMS adicionais
----------------------------------------------------------------------------------------------------------

Para instalar o RMS, você deve fazer logon usando uma conta com privilégios de administrador local. Além disso, você deve estar conectado a um domínio com uma conta de domínio válida para permitir que o Active Directory autentique o RMS. Se estiver implantando o RMS em um ambiente em que a infra-estrutura do Active Directory utiliza o modo nativo do Microsoft Windows 2000, o RMS poderá não ser capaz de ler o atributo memberOf em objetos do Active Directory quando o Active Directory tentar expandir as participações nos grupos. Para que o RMS possa ler o atributo memberOf, a conta do serviço RMS deve ser uma conta de domínio que seja membro do grupo Acesso Compatível com Versões Anteriores ao Windows 2000 em sua floresta. Se você implantou grupos com participação oculta, também precisará configurar a conta de serviço RMS com permissões que o habilitem a ler a participação oculta.

> [!Note]  
> A conta de serviço RMS não pode ser a mesma conta do domínio utilizada para instalar o RMS.

Processos de instalação e de configuração do servidor inicial
-------------------------------------------------------------

A implantação do servidor RMS envolve duas etapas. Primeiro, o software do servidor RMS deve ser instalado juntamente com o software de suporte, como IIS (Serviços de Informações da Internet), Enfileiramento de Mensagens e ASP.NET. Para obter mais informações sobre a instalação, consulte "Instalar o RMS com Service Pack 1" em "Operando um servidor RMS", nesta coleção de documentos.

> [!Note]  
> O RMS também pode ser instalado em um prompt de comando. Para obter mais informações, consulte "Instalação do RMS a partir do prompt de comando" em "Operando um servidor RMS", nesta coleção de documentos.

Depois de instalar o RMS em um servidor, você deve configurar o RMS para ser usado em um único site que está no servidor. Quando você configura esse site, muitas das configurações do site são modificadas e diretórios virtuais são adicionados. Para obter mais informações sobre essas alterações, consulte "Suporte do Serviços de Informações da Internet (IIS) para RMS" em "Referência técnica do RMS", nesta coleção de documentos.

É possível utilizar o site padrão que está no IIS ou criar um site novo. Para configurar o RMS em um site diferente do site padrão, você deve criar o site antes de iniciar o processo de configuração. Se você estiver usando o site padrão para outros fins, deverá criar um novo site para o RMS, de modo que a configuração padrão seja mantida para o site padrão.

Quando você clicar em **Administração do Windows RMS** no menu **Iniciar**, a página **Administração Global** aparece. Nessa página, você pode iniciar o processo de configuração em um site. Para configurar o primeiro servidor RMS, você deverá fornecer as seguintes informações:

-   Especifique o nome a ser usado para os bancos de dados de configuração, log e serviços de diretório do RMS.
    Se a instância do seu SQL Server tiver um nome que não seja o mesmo que o nome do servidor local, é preciso configurá-la como uma instância remota do SQL Server, mesmo que tudo esteja instalado em um servidor único.
    Durante a configuração, a conta de usuário conectada no momento deve ter permissão para criar bancos de dados no servidor de banco de dados.
-   Especifique a conta a ser usada para a conta de serviço RMS. Para uma configuração local, é possível utilizar a conta do Sistema local, embora isso não seja recomendado devido às questões inerentes à segurança que estão envolvidas com o processamento de um serviço que tem privilégios de sistema local.
    Para uma instalação que inclua uma instância remota do SQL Server ou mais de um servidor RMS, você deve especificar uma conta de domínio. A conta de domínio utilizada deve ter privilégios de pesquisa do Active Directory e será utilizada para criar o Pool de aplicativos do IIS sob o qual o console de Administração é processado. Se você não estiver fazendo uma atualização nem estiver usando um banco de dados existente, a conta de serviço RMS exigirá privilégios de criação de bancos de dados. Se você estiver usando bancos de dados existentes, a conta precisará ter permissões de leitura e gravação para cada um dos bancos de dados do RMS.
-   Especifique a URL a ser usada para acessar esse site. O valor padrão é o nome do site que você está configurando (como site padrão, se você estiver configurando um servidor com uma instalação padrão do IIS). É possível especificar uma URL personalizada para acessar um site diferente, por exemplo, suportar uma URL com balanceamento de carga ou suportar acesso à intranet e à Internet. Você deve verificar se a URL personalizada funciona e deve adicionar o nome do site ao DNS para assegurar que tanto a página **Administração Global** quanto a página **Configuração** encontrem as raízes virtuais. Se essa URL for para uma implantação habilitada pela Internet, verifique se a nova URL está disponível na Internet e na rede corporativa.
-   Selecione o mecanismo a ser usado para proteger a chave particular da instalação raiz usada para o registro. O padrão é usar criptografia baseada em software e armazenar a chave particular criptografada no banco de dados de configuração do RMS. Se você utiliza a configuração padrão, é preciso fornecer uma senha de segurança para criptografar o valor que está no banco de dados.
    Entretanto, se você tiver um HSM (módulo de segurança de hardware) instalado e configurado no computador, também poderá selecionar um CSP (provedor de serviços de criptografia) para usar com o módulo de segurança de hardware e armazenar as chaves particulares no hardware, como um cartão inteligente. O RMS exige um provedor RSA (Rivest-Shamir-Adleman) completo e somente esses provedores estão disponíveis na lista de CSPs. O uso de um HSM para proteger a chave particular do RMS é altamente recomendável.
    Se você usar a opção CSP com base em software para proteger a chave particular do RMS com uma senha, deve guardar essa senha em um arquivo seguro para referência futura. Deve também armazenar uma cópia de backup do banco de dados de configuração com a senha. Ao fazer isso, você poderá restaurar o RMS se o banco de dados do SQL sofrer algum dano. Se você alterar a senha por qualquer razão, faça uma nova cópia de backup do banco de dados de configuração que armazena a chave particular protegida com essa senha e coloque-os no arquivo protegido. Para obter mais informações sobre como fazer backup e restaurar o banco de dados de configuração, consulte "Fazendo backup e restaurando o sistema para o RMS" em "Planejando uma implantação do RMS", nesta coleção de documentos.
-   Especifique o nome a ser usado dentro do certificado de licenciante para servidor. Por padrão, esse é o nome do servidor.
-   Especifique um servidor proxy (incluindo endereço e porta) a ser usado para acessar a Internet, se apropriado.
-   Especifique um endereço de email que outros administradores do RMS possam usar para contatar um administrador, caso surjam questões quando esse administrador tentar criar um sub-registro de um servidor de licenciamento. Depois de configurar a instalação raiz, você pode alterar o endereço.
-   Selecione um método de revogação de certificado de licenciante para servidor para controlar quem, além do Microsoft Enrollment Service, pode revogar o certificado de licenciante para servidor da instalação raiz. Para utilizar a revogação de terceiros, é preciso especificar o caminho e o nome do arquivo que contém a chave pública para essa entidade de terceiros.

Se você selecionou a opção de registro online, ao clicar em **Enviar** na página **Configuração** (após configurar todas as opções apropriadas), o RMS gerará um par de chaves e enviará a chave pública ao Microsoft Enrollment Service. (Se você receber mensagens de erro, não feche a página em que os erros estão exibidos. Depois que você solucionar os erros, abra uma janela de prompt de comando e digite `IISReset` para parar e reiniciar o IIS, volte para página anterior, redigite as informações na tela de configuração e depois clique novamente em **Enviar**.) O Microsoft Enrollment Service cria um certificado de licenciante para servidor e o devolve para o banco de dados de configuração em apenas alguns minutos. Como este é o primeiro servidor do domínio onde o RMS está instalado, essa etapa representa o processo de registro do servidor raiz de certificação.

Caso tenha selecionado a opção de registro offline, você registrará o servidor manualmente com o Microsoft Enrollment Service após a conclusão do processo de configuração. O processo de registro deve ser concluído antes para que o servidor possa ser usado. Para obter mais informações, consulte "Registrar manualmente um servidor raiz de certificação" em "Operando um servidor RMS", nesta coleção de documentos.

Quando você concluir a configuração e o registro de um servidor, os links da página **Administração Global** serão alterados. O link **Configurar o RMS neste site** altera o link **Administrar o RMS neste site**, o link **Adicionar este servidor a um cluster** é substituído por um link **Alterar a conta de serviço RMS**, e um link **Remover o RMS deste site**.

Esse servidor inicial estabelece a instalação raiz do RMS. A instalação raiz pode consistir em um único servidor ou em um cluster. Depois de concluir a instalação e a configuração do servidor inicial, você pode configurar servidores adicionais para fornecer redundância e suporte ao balanceamento de carga para serviços de certificação e licenciamento.

Quando a configuração estiver concluída, você deverá registrar o ponto de conexão de serviço do cluster raiz de certificação no Active Directory, a fim de permitir que os clientes habilitados para RMS descubram o serviço. Para obter mais informações, consulte "Registrando o ponto de conexão de serviço" em "Operando um servidor RMS", nesta coleção de documentos. Se o ponto de conexão de serviço não estiver registrado, o seu cliente do RMS não poderá ser usado com o RMS.

> [!Important]  
> Você deve instalar e configurar o RMS totalmente no primeiro servidor antes de iniciar a instalação do RMS em outros servidores. O RMS oferece suporte à proteção de conteúdo para grupos do Active Directory cuja participação se estende por várias florestas. Se a sua organização não possui várias florestas ou grupos que se estendam por várias florestas, você poderá otimizar o desempenho do processo de emissão de licenças de uso no servidor RMS ao modificar a diretiva de clusters **MaxCrossForestCalls** no banco de dados de configuração do RMS. Essa diretiva especifica o número máximo de vezes que a participação de um grupo pode atravessar os limites da floresta. O valor padrão é 10. Para alterar esse valor para 0, use o seguinte comando SQL:`update DRMS_ClusterPolicies set PolicyData=0 where PolicyName='MaxCrossForestCalls'` 

Os tópicos a seguir fornecem as etapas detalhadas necessárias para completar as tarefas disponíveis na página Administração Global do RMS:

-   Para obter informações sobre como usar o assistente de instalação para instalar o servidor inicial, consulte "Instalar o RMS com Service Pack 1" em "Operando um servidor RMS", nesta coleção de documentos.  
-   Para obter informações sobre como configurar o servidor inicial, consulte "Configurar o primeiro servidor raiz de certificação" em "Operando um servidor RMS", nesta coleção de documentos.
-   Para obter informações sobre como adicionar servidores à instalação raiz para criar um cluster, consulte "[Adicionando servidores para oferecer suporte a certificação e licenciamento](https://technet.microsoft.com/089ceb62-2a96-444f-ab42-1d5deaabd0c3)", mais adiante neste tema.
