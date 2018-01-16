---
TOCTitle: Configurar o primeiro servidor raiz de certificação
Title: Configurar o primeiro servidor raiz de certificação
ms:assetid: 'debc42f3-74ff-4c99-b7a4-4921fccdabc2'
ms:contentKeyID: 18123860
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747768(v=WS.10)'
---

Configurar o primeiro servidor raiz de certificação
===================================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Se estiver utilizando um banco de dados remoto do SQL Server, essa conta também deverá ter a função dos Criadores do banco de dados no SQL Server. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Em cada servidor, é possível configurar o RMS em apenas um único site. Se desejar configurar o RMS em um site diferente do site padrão, utilize o Gerente dos Serviços de Informações da Internet para adicioná-lo antes de começar esse processo de configuração. Se o site que você deseja configurar não aparecer na lista de sites, feche a página **Administração Global**, adicione o site e inicie o processo de configuração novamente.

Se estiver implantando o RMS em um ambiente em que o nível funcional de domínio do Active Directory está definido com o modo nativo do Microsoft Windows 2000, o RMS poderá não ser capaz de ler o atributo **memberOf** nos objetos do Active Directory ao tentar expandir as participações nos grupos. Para que o RMS possa ler o atributo **memberOf**, a conta do serviço RMS deve usar uma conta de domínio que seja membro do grupo anterior ao Windows 2000-Acesso compatível (Builtin) em sua floresta.

Se você digitar uma URL personalizada para o cluster, certifique-se de registrá-la em seu DNS (sistema de nome de domínio) e verificar se ela funciona. Se for uma implantação pela Internet, verifique se a URL está disponível em ambas, na Internet e na sua organização. É preciso especificar HTTPS para a URL do cluster se você tiver ativado SSL para os arquivos dos serviços da Web.

Configurando o primeiro servidor raiz de certificação
-----------------------------------------------------

#### Configurar o primeiro servidor raiz de certificação

1.  Depois de instalar o RMS em um servidor que será o primeiro servidor raiz de certificação em uma floresta do Active Directory, abra a página **Administração Global**.

2.  Próximo ao site em que deseja configurar o RMS, clique em **Configurar o RMS neste site**. É possível selecionar o site padrão ou outro site que você tenha criado no IIS (Serviços de Informações da Internet) para esse fim.

    > [!Warning]  
    > Não há suporte para executar qualquer site ou serviço adicionais no mesmo servidor como RMS. Isso poderia resultar na execução de vários aplicativos e serviços sob a mesma conta como o RMS, o que poderia expor as chaves particulares a operações sem garantia.

3.  Na área **Banco de dados de configuração**, a opção padrão é criar o banco de dados de configuração no servidor local. Você pode usar um servidor de banco de dados como SQL Server™ 2000 com SP3 ou Microsoft SQL Server 2000 Desktop Engine (MSDE) para um banco de dados local. Se você estiver usando um banco de dados remoto, ou se estiver executando o servidor do banco de dados no servidor local, mas a instância do servidor do banco de dados tiver um nome diferente do nome deste servidor, selecione **Banco de dados remoto** e depois digite o nome do servidor do banco de dados.

    > [!Important]  
    > É recomendável que o Microsoft SQL Server Desktop Engine seja usado para oferecer suporte aos bancos de dados RMS somente em ambientes de teste porque o Microsoft SQL Server Desktop Engine não oferece suporte a nenhuma interface de rede. Além disso, os termos de uso do Microsoft SQL Server Desktop Engine especificam que você não pode usar as ferramentas de cliente do SQL Server para manipular um banco de dados Microsoft SQL Server Desktop Engine. Com essa restrição não será possível exibir informações de registro ou alterar dados armazenados no banco de dados de configuração.

4.  Na área **Conta de serviço RMS**, especifique a conta de serviço RMS sob a qual o RMS será executado para a maioria das operações normais. Para a instalação em um servidor único, é possível especificar a conta do Sistema local ou uma conta de domínio. Para todas as outras instalações, é preciso especificar uma conta de domínio. Para uma conta de domínio, forneça o nome da conta na forma *nome\_domínio*\\*nome\_usuário* e a senha.

    > [!Warning]  
    > A conta do Sistema local tem acesso a quase todos os recursos do sistema operacional, por isso tem sérias implicações de segurança. Sempre que possível, evite utilizar a conta do Sistema local como a conta de serviço do RMS. Em vez disso, crie uma conta de usuário do domínio especial para usar como conta de serviço RMS e não conceda permissões especiais. A conta de serviço RMS não pode ser a mesma conta do domínio utilizada para instalar o RMS.

    > [!Important]  
    > Por razões de segurança, recomenda-se a criação de uma conta de usuário especial para usar como conta de serviço RMS e a não concessão de permissões especiais. A conta de serviço RMS não pode ser a mesma conta do domínio utilizada para instalar o RMS com Service Pack 1.

5.  Na área **URL do Cluster**, digite a URL do servidor ou cluster que será usada para os clientes na rede interna. A entrada padrão utiliza o nome do servidor, por exemplo, Contoso-cert. É possível editá-lo, se necessário; por exemplo, para configurar uma URL para o cluster ou um balanceador de carga que serve ao cluster. Também é possível selecionar HTTP ou HTTPS. Consulte a seção **Observações** no final desta lista de procedimentos para obter mais informações sobre a configuração da URL do cluster. Após a configuração, você poderá configurar uma URL do cluster externo das páginas da Web de Administração para uso pelos clientes que estão fora de sua rede interna.

6.  Na área **Proteção e inscrição de chave particular**, selecione o mecanismo de proteção de chave particular do servidor seguindo um destes procedimentos:

    -   **Utilize a proteção de chave particular padrão baseada em software**. Ao selecionar essa opção, a chave particular será armazenada no banco de dados de configuração do RMS. É preciso fornecer uma senha segura para criptografar a chave no banco de dados.

    > [!Important]  
    > Proteja essa senha em um arquivo de segurança para referência futura. Armazene uma cópia de backup do banco de dados de configuração (também protegido com essa senha) no arquivo de segurança. Isso serve como mecanismo para restaurar o RMS caso o banco de dados do SQL Server seja corrompido. Se você alterar a senha por qualquer razão, faça um novo backup do banco de dados de configuração que está vinculado a essa senha e coloque-os no arquivo de segurança.

    -   **Utilize um CSP (Provedor de serviços de criptografia)**. Para utilizar um CSP ou um HSM (módulo de segurança de hardware), desmarque a caixa de seleção **Utilize a proteção de chave particular padrão baseada em software**. Na lista **Selecione o provedor de serviços de criptografia**, selecione o CSP ou o HSM que você instalou.

    > [!Note]  
    > O RMS requer um provedor completo Rivest-Shamir-Adleman (RSA); somente esses provedores estão incluídos na lista de CSPs.

    > [!Note]  
    > Recomenda-se utilizar a proteção de chave particular padrão baseada em software ou um HSM. Se utilizar um CSP baseado em software diferente, verifique se você possui as práticas de gerenciamento de chaves organizacionais (como procedimentos de backup e restauração) no lugar desse CSP antes de utilizá-lo com o RMS.

7.  Essa etapa só se aplica se você tiver selecionado um CSP. Para especificar o par de chaves do servidor a utilizar, efetue uma das seguintes opções:

    -   Para uma nova instalação, selecione **Criar um novo par de chaves públicas/particulares**.
    -   Se estiver recuperando ou atualizando um servidor Windows RMS existente, selecione **Usar um par de chaves públicas/paeticulares**. Em **Recipiente de chave existente**, clique em **Procurar** e selecione o recipiente de chave para o par de chaves do servidor.

    > [!Note]  
    > Os CSPs Microsoft Base, Enhanced e Strong compartilham o mesmo local de armazenamento de chaves.

    > [!Note]  
    > Se você não usar um par de chaves existente ao recuperar ou atualizar um servidor RMS existente, todos os clientes do RMS existentes precisarão ter seus armazenamentos de licenças limpos (exclusão de certificados de conta de direitos e licenças de uso) e depois terão que obter novas licenças do servidor para consumir o conteúdo.

8.  Em **Conectividade com a Internet do Servidor**, especifique se esse servidor se conecta à Internet para obter um certificado de licenciante servidor.

    -   Selecione **Online** para conectar-se automaticamente ao Serviço de Inscrição da Microsoft e obter um certificado de licenciante servidor durante o processo de configuração.
    -   Selecione **Offline** se o servidor RMS não possui uma conexão com a Internet ou se você quiser obter manualmente o certificado de licenciante servidor e importá-lo para o servidor RMS após a configuração.

9.  Em **Nome do certificado de licenciante servidor**, insira o nome a ser utilizado dentro do certificado de licenciante servidor. Por padrão, esse é o nome do servidor.

10. Se sua organização utiliza um servidor proxy para se conectar à Internet, marque a caixa de seleção **Este computador usa um servidor proxy para conectar-se à Internet** e digite o endereço e a porta para esse servidor.

    Se o servidor proxy solicitar autenticação, selecione o tipo de autenticação e forneça um nome de usuário e senha que possam ser autenticados por esse servidor. Se estiver usando a autenticação Integrada do Windows, você deverá também especificar um domínio.

    > [!Note]  
    > Essa configuração poderá ser modificada após a configuração, na página **Configurações de segurança** do site Administração do RMS. No entanto, essa página só ficará disponível depois que o servidor tiver sido inscrito junto ao Serviço de Inscrição da Microsoft. Se a sua organização requerer o uso de um servidor proxy para a conexão com a Internet, mas você não configurar um servidor proxy porque selecionou **Offline** para **Conectividade com a Internet do Servidor**, só será possível alterar as suas configurações para o processo de inscrição e para o servidor proxy depois que você tiver concluído o processo de inscrição manual ou tiver reconfigurado o RMS.

11. Em **Contato administrativo**, digite o endereço de email do administrador a ser contatado caso surjam questões a respeito da configuração de outros servidores. Depois da configuração, pode-se alterar esse endereço de email.

12. Na área **Revogação**, selecione se irá ou não permitir que terceiros revoguem o certificado de licenciante servidor desse servidor. Se você selecionar essa opção, digite o caminho e o nome do arquivo de chave pública dessa pessoa.

13. Clique em **Enviar**.

    Ao clicar em **Enviar**, você configura o serviço. Se você selecionou o registro online, também será executado o processo de registro para o servidor raiz de certificação. Nesse processo, o RMS gera um par de chaves pública/particular e envia a chave pública para o Microsoft Enrollment Service. O Serviço de Inscrição da Microsoft cria um certificado de licenciante servidor e o devolve para o banco de dados de configuração em apenas alguns minutos. Se você estiver usando o registro offline, deve concluir a tarefa descrita em "[Registrar manualmente um servidor raiz de certificação](https://technet.microsoft.com/aecdebb5-b28b-4b58-937a-392bb6ce9643)", mais adiante neste tema, antes de configurar o servidor RMS.

    > [!Note]  
    > Esse servidor não estará pronto para uso até que o SCP (ponto de conexão de serviço) do RMS tenha sido registrado no Active Directory. Use as etapas em "[Registrar um ponto de conexão de serviço](https://technet.microsoft.com/630cc3c3-9ed9-4423-8874-cbaceb43b353)", mais adiante neste tema, para executar esse processo.

Para obter instruções sobre a configuração de servidores raiz de certificação adicionais e a sua adição a um cluster, consulte "[Adicionar um servidor a um cluster](https://technet.microsoft.com/db635238-5528-4bec-9cc6-8244e2b3d733)", mais adiante neste tema.
