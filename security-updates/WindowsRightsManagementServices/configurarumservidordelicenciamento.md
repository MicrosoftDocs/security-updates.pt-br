---
TOCTitle: Configurar um servidor de licenciamento
Title: Configurar um servidor de licenciamento
ms:assetid: '4d67b898-0ba9-4eef-ab7d-ee0ca55a688e'
ms:contentKeyID: 18123667
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747563(v=WS.10)'
---

Configurar um servidor de licenciamento
=======================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Além disso, o processo de sub-registro requer permissões de leitura e execução para a conta de usuário do domínio e para o grupo de serviço RMS. Para obter mais informações, consulte [Configurando permissões no arquivo de serviço de sub-registro](https://technet.microsoft.com/737bb69b-fe26-4057-9569-e632f7bbf295), já mencionado neste tema. Se estiver utilizando um banco de dados remoto do SQL Server, essa conta também deverá ter a função dos Criadores do banco de dados no SQL Server. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Em cada servidor, é possível configurar o RMS em apenas um único site. Se desejar configurar o RMS em um site diferente do site padrão, utilize o Gerente dos Serviços de Informações da Internet para adicioná-lo antes de começar esse processo de configuração. Se o site que você deseja configurar não aparecer na lista de sites, feche a página **Administração Global**, adicione o site e inicie o processo de configuração novamente.

Se estiver implantando o RMS em um ambiente em que o nível funcional de domínio do Active Directory está definido com o modo nativo do Microsoft Windows 2000, o RMS poderá não ser capaz de ler o atributo **memberOf** nos objetos do Active Directory ao tentar expandir as participações nos grupos. Para que o RMS possa ler o atributo **memberOf**, a conta do serviço RMS deve usar uma conta de domínio que seja membro do grupo anterior ao Windows 2000-Acesso compatível (Builtin) em sua floresta.

Se você digitar uma URL personalizada para o cluster, certifique-se de registrá-la em seu DNS (sistema de nome de domínio) e verificar se ela funciona. Se for uma implantação pela Internet, verifique se a URL está disponível em ambas, na Internet e na sua organização. É preciso especificar HTTPS para a URL do cluster se você tiver ativado SSL para os arquivos dos serviços da Web.

Configurando um servidor de licenciamento
-----------------------------------------

#### Configurar um servidor de licenciamento

1.  Abra a página **Administração Global** e próximo ao site em que deseja configurar o RMS, clique em **Configurar o RMS neste site**.

    É possível selecionar o site padrão ou outro site que você tenha criado no IIS (Serviços de Informações da Internet) para esse fim.

    > [!Warning]  
    > Não há suporte para executar qualquer site ou serviço adicionais no mesmo servidor como RMS. Isso poderia resultar na execução de vários aplicativos e serviços sob a mesma conta como o RMS, o que poderia expor as chaves particulares a operações sem garantia.

2.  Na área **Banco de dados de configuração**, a opção padrão é criar o banco de dados de configuração no servidor local. Você pode usar um servidor de banco de dados como SQL Server™ 2000 com SP3 ou Microsoft SQL Server 2000 Desktop Engine (MSDE) para um banco de dados local. Se você estiver usando um banco de dados remoto, ou se estiver executando o servidor do banco de dados no servidor local, mas a instância do servidor do banco de dados tiver um nome diferente do nome deste servidor, selecione **Banco de dados remoto** e depois digite o nome do servidor do banco de dados.

    > [!Important]  
    > É recomendável que o Microsoft SQL Server Desktop Engine seja usado para oferecer suporte aos bancos de dados RMS somente em ambientes de teste porque o Microsoft SQL Server Desktop Engine não oferece suporte a nenhuma interface de rede. Além disso, os termos de uso do Microsoft SQL Server Desktop Engine especificam que você não pode usar as ferramentas de cliente do SQL Server para manipular um banco de dados Microsoft SQL Server Desktop Engine. Com essa restrição não será possível exibir informações de registro ou alterar dados armazenados no banco de dados de configuração.

3.  Na área **Conta de serviço RMS**, especifique a conta de serviço RMS sob a qual o RMS será executado para a maioria das operações normais. Para a instalação em um servidor único, é possível especificar a conta do Sistema local ou uma conta de domínio. Para todas as outras instalações, é preciso especificar uma conta de domínio. Para uma conta de domínio, forneça o nome da conta na forma *nome\_domínio*\\*nome\_usuário* e a senha.

    > [!Warning]  
    > A conta do Sistema local tem acesso a quase todos os recursos do sistema operacional, por isso tem sérias implicações de segurança. Sempre que possível, evite utilizar a conta do Sistema local como a conta de serviço do RMS. Em vez disso, crie uma conta de usuário do domínio especial para usar como conta de serviço RMS e não conceda permissões especiais. A conta de serviço RMS não pode ser a mesma conta do domínio utilizada para instalar o RMS.

4.  Na área **URL do Cluster**, digite a URL do servidor ou cluster que será usada para os clientes na rede interna. A entrada padrão utiliza o nome do servidor, por exemplo, Contoso-cert. É possível editá-lo, se necessário; por exemplo, para configurar uma URL para o cluster ou um balanceador de carga que serve ao cluster. Também é possível selecionar HTTP ou HTTPS. Consulte a seção **Observações** no final desta lista de procedimentos para obter mais informações sobre a configuração da URL do cluster. Após a configuração, você poderá configurar uma URL do cluster externo das páginas da Web de Administração para uso pelos clientes que estão fora de sua rede interna.

5.  Na área **Subscrição e proteção de chave particular**, selecione o mecanismo de proteção da chave particular do servidor seguindo um destes procedimentos:

    -   **Utilize a proteção de chave particular padrão baseada em software**. Ao selecionar essa opção, a chave particular será armazenada no banco de dados de configuração do RMS. É preciso fornecer uma senha segura para criptografar a chave no banco de dados.

    > [!Important]  
    > Proteja essa senha em um arquivo de segurança para referência futura. Armazene uma cópia de backup do banco de dados de configuração (também protegido com essa senha) no arquivo de segurança. Isso serve como mecanismo para restaurar o RMS caso o banco de dados do SQL Server seja corrompido. Se você alterar a senha por qualquer razão, faça um novo backup do banco de dados de configuração que está vinculado a essa senha e coloque-os no arquivo de segurança.

    -   **Utilize um CSP (Provedor de serviços de criptografia)**. Para utilizar um CSP ou um HSM (módulo de segurança de hardware), desmarque a caixa de seleção **Utilize a proteção de chave particular padrão baseada em software**. Na lista **Selecione o provedor de serviços de criptografia**, selecione o CSP ou o HSM que você instalou.

    > [!Note]  
    > O RMS requer um provedor completo Rivest-Shamir-Adleman (RSA); somente esses provedores estão incluídos na lista de CSPs.

    > [!Note]  
    > Recomenda-se utilizar a proteção de chave particular padrão baseada em software ou um HSM. Se utilizar um CSP baseado em software diferente, verifique se você possui as práticas de gerenciamento de chaves organizacionais (como procedimentos de backup e restauração) no lugar desse CSP antes de utilizá-lo com o RMS.

6.  Essa etapa só se aplica se você tiver selecionado um CSP. Para especificar o par de chaves do servidor a utilizar, efetue uma das seguintes opções:

    -   Para uma nova instalação, selecione **Criar um novo par de chaves públicas/particulares**.
    -   Se estiver recuperando ou atualizando um servidor Windows RMS existente, selecione **Usar um par de chaves públicas/paeticulares**. Em Recipiente de chave existente, clique em **Procurar** e selecione o recipiente de chave para o par de chaves do servidor.

    > [!Note]  
    > Os CSPs Microsoft Base, Enhanced e Strong compartilham o mesmo local de armazenamento de chaves.

    > [!Note]  
    > Se você não usar um par de chaves existente ao recuperar ou atualizar um servidor RMS existente, todos os clientes do RMS existentes precisarão ter seus armazenamentos de licenças limpos (exclusão de certificados de conta de direitos e licenças de uso) e depois terão que obter novas licenças do servidor para consumir o conteúdo.

7.  Em **Nome do certificado de licenciante servidor**, insira o nome a ser utilizado dentro do certificado de licenciante servidor. Por padrão, esse é o nome do servidor.

8.  Se sua organização utiliza um servidor proxy para se conectar à Internet, marque a caixa de seleção **Este computador usa um servidor proxy para conectar-se à Internet** e digite o endereço e a porta para esse servidor.

    Se o servidor proxy solicitar autenticação, selecione o tipo de autenticação e forneça um nome de usuário e senha que possam ser autenticados por esse servidor. Se estiver usando a autenticação Integrada do Windows, você deverá também especificar um domínio.

9.  Clique em **Enviar**.

    O serviço de sub-registro do RMS gera um par de chaves públicas/particulares para o servidor de licenciamento e assina a chave pública com a chave particular do servidor raiz de certificação. Ele também cria um certificado de licenciante servidor para o servidor de licenciamento. Ele envia esses itens para o banco de dados de configuração em apenas alguns minutos.

    > [!Important]  
    > Se forem exibidas mensagens de erro, não feche a página. Em vez disso, corrija os erros, utilize IISReset da linha de comando para parar e reiniciar o IIS, volte para a página anterior, insira novamente as informações de configuração e clique em **Enviar** novamente. Se receber a mensagem de erro "Esgotado o tempo limite do pedido", feche a janela, verifique se o sistema atinge os requisitos mínimos de hardware e tente configurar o servidor novamente.

Para obter instruções sobre a configuração de servidores de licenciamento adicionais e a sua adição a um cluster, consulte "[Adicionar um servidor a um cluster](https://technet.microsoft.com/db635238-5528-4bec-9cc6-8244e2b3d733)", mais adiante neste tema.
