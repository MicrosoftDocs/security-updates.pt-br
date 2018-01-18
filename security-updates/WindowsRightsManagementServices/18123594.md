---
TOCTitle: 'Perguntas freqüentes sobre o RMS: Implantação'
Title: 'Perguntas freqüentes sobre o RMS: Implantação'
ms:assetid: '5559ae65-77ae-4e0b-bfd8-3512409ed29b'
ms:contentKeyID: 18123594
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720274(v=WS.10)'
---

Perguntas freqüentes sobre o RMS: Implantação
=============================================

Perguntas freqüentes sobre a implantação do RMS
-----------------------------------------------

-   [Se as entidades de segurança usadas para o RMS forem membros da lista de endereços global (GAL), existe alguma dependência da versão do Exchange?](#bkmk_20)
-   [Qual é o papel do SQL Server no RMS?](#bkmk_21)
-   [O computador do usuário precisa ter ingressado no mesmo domínio que o cluster raiz do RMS para usar o RMS?](#bkmk_22)
-   [Se um cliente desejar colocar um Servidor RMS em uma rede de perímetro, quais portas devem ser abertas no firewall voltado para a Internet e no firewall voltado para a intranet para se comunicar com o RMS?](#bkmk_23)
-   [Como os servidores subordinados em um cluster somente de licenciamento são inscritos, e preciso fazer algo em relação aos clientes para que eles reconheçam o cluster?](#bkmk_24)
-   [Qual é a vantagem de usar um cluster somente de licenciamento?](#bkmk_25)
-   [O que é preciso fazer para reverter completamente uma instalação de RMS?](#bkmk_26)
-   [Após a desinstalação do cliente do RMS usando Adicionar ou Remover Programas, é preciso remover algum outro arquivo?](#bkmk_27)
-   [O RMS funciona com o sistema de arquivos FAT?](#bkmk_28)
-   [Qual é a configuração de hardware típica recomendada para o servidor de banco de dados usado pelo RMS?](#bkmk_29)
-   [Como o uso do RMS do catálogo global para expansão de grupo afeta o desempenho do servidor de catálogo global?](#bkmk_30)
-   [O RMS exige alguma alteração de esquema no Active Directory?](#bkmk_31)
-   [O ponto de conexão de serviço (SCP) será automaticamente replicado entre os diferentes controladores de domínio no domínio em que o cluster do RMS está instalado?](#bkmk_32)
-   [Se os usuários não tiverem direitos administrativos em suas máquinas, como o cliente do RMS pode ser instalado e configurado?](#bkmk_33)
-   [O que é a escalabilidade do RMS?](#bkmk_35)
-   [O RMS aceita módulos de segurança de hardware (HSMs) para proteger as chaves RMS no hardware?](#bkmk_36)

<span id="BKMK_20"></span>
#### Se as entidades de segurança usadas para o RMS forem membros da lista de endereços global (GAL), existe alguma dependência da versão do Exchange?

O RMS depende do Active Directory, mas não do Exchange. No entanto, o Exchange 5.5 mantém o seu próprio diretório e não usa o Active Directory. Verifique se todos os objetos de usuário e de grupo do Active Directory possuem um atributo de email válido que inclua o nome de domínio totalmente qualificado. Isso é feito automaticamente se você estiver usando o Exchange 2000 ou posterior.

<span id="BKMK_21"></span>
#### Qual é o papel do SQL Server no RMS?

O RMS usa um banco de dados para armazenar todos os dados de configuração de serviços, informações sobre entidades do sistema, todos os dados de log e para armazenar pesquisas no cache durante a expansão do Active Directory e da lista de distribuição. O RMS foi totalmente testado com o SQL Server 2000 e o SQL Server 2005.

<span id="BKMK_22"></span>
#### O computador do usuário precisa estar inscrito no mesmo domínio que o servidor RMS para usar RMS?

O computador do usuário não precisa ser membro do mesmo domínio que o cluster do RMS, mas precisa ser capaz de localizar esse cluster. A maneira mais fácil para os computadores cliente localizarem o cluster RMS é usar uma pesquisa do Active Directory por meio do ponto de conexão de serviço (SCP). No entanto, configurações do Registro no cliente também podem ser definidas para localizar o cluster RMS sem usar a pesquisa do Active Directory. As configurações exatas do Registro dependem do aplicativo habilitado para RMS.

<span id="BKMK_23"></span>
#### Se um cliente desejar colocar o Servidor RMS em uma rede de perímetro, quais portas devem ser abertas no firewall voltado para a Internet e no firewall voltado para a intranet para se comunicar com o RMS?

Os usuários internos precisarão de acesso aos servidores RMS que emitiram certificados de conta de direitos e licenças de uso. Por padrão, o servidor RMS escuta em HTTP (TCP porta 80) ou HTTPS (TCP porta 443), dependendo de o servidor estar configurado para usar SSL; portanto, essas portas precisam estar abertas no firewall da Internet. Você deverá abrir portas adicionais usadas por servidores membros em um domínio no firewall da intranet.

<span id="BKMK_24"></span>
#### Como os servidores subordinados em um cluster somente de licenciamento são inscritos, e preciso fazer algo em relação aos clientes para que eles reconheçam o cluster?

Quando o primeiro servidor RMS no cluster raiz é criado em uma empresa, recebe um certificado de licenciante para servidor do Microsoft Enrollment Service. Quando um outro servidor RMS é instalado e provisionado, você pode fazer com que ele ingresse no cluster raiz ou inscrevê-lo como servidor em um cluster somente de licenciamento subordinado. Se você optar por inscrevê-lo como servidor em um cluster somente de licenciamento subordinado, ele enviará uma solicitação de inscrição ao cluster raiz do RMS. Os aplicativos habilitados para RMS especificam onde o aplicativo cliente deve procurar o cluster somente de licenciamento. O Office 2003 é um exemplo de aplicativo habilitado para RMS que, por padrão, procura o cluster raiz. Esse comportamento pode ser substituído por configurações do Registro, de modo que o aplicativo procure o novo cluster somente de licenciamento subordinado.

<span id="BKMK_25"></span>
#### Qual é a vantagem de usar um cluster somente de licenciamento subordinado?

Uma vantagem é poder isolar departamentos diferentes dentro de uma organização. Se um domínio de publicação confiável entre clusters do RMS não for estabelecido, o conteúdo só poderá ser consumido por usuários que tenham acesso a um determinado servidor de licenciamento. Dessa maneira, um departamento jurídico poderia excluir todos os demais do acesso de leitura de seus emails RMS criptografados. Além disso, diversas opções podem ser definidas no cluster somente de licenciamento, como modelos de direitos, log, associação no grupo de superusuários e diretrizes de exclusão.

<span id="BKMK_26"></span>
#### O que é preciso fazer para reverter completamente uma instalação de RMS?

Para reverter uma instalação de RMS corretamente, realize o procedimento apresentado a seguir.

**Reverter uma instalação de RMS**
1.  Remova o ponto de conexão de serviço (SCP) para o cluster RMS usando o site de administração do RMS.

2.  Na página **Administração Global**, clique em **Remover o RMS deste site** para remover o provisionamento do RMS no servidor. Primeiramente, você deve remover o provisionamento de servidores ou clusters somente de licenciamento com sub-registro e, em seguida, remover o provisionamento dos servidores de cluster raiz.

3.  Em **Painel de Controle**, clique em **Adicionar ou Remover Programas** e remova o **Rights Management Services**.

4.  No servidor de banco de dados, remova os bancos de dados do RMS restantes.

5.  Remova a conta de serviço RMS da lista de logons autorizados nos servidores de bancos de dados e, em seguida, remova a conta do Active Directory propriamente dito.

6.  Se os clientes do RMS estiverem executando o Windows XP e o Windows 2000, remova o cliente do RMS dos computadores cliente.

> [!Important]  
> Após a conclusão desse procedimento, você não poderá mais abrir conteúdo protegido por direitos. Descomissione o RMS antes de reverter uma instalação de RMS, se ele tiver sido usado para proteger dados importantes. 

<span id="BKMK_27"></span>
#### Após a desinstalação do cliente do RMS usando Adicionar ou Remover Programas, é preciso remover algum outro arquivo?

Embora isso não seja necessário, você poderá excluir o cofre de %systemroot%\\system32.

<span id="BKMK_28"></span>
#### O RMS funciona com o sistema de arquivos FAT?

Sim, o RMS funciona em um computador usando FAT, embora o sistema de arquivos NTFS seja recomendado.

<span id="BKMK_29"></span>
#### Qual é a configuração de hardware típica recomendada para o servidor de banco de dados usado pelo RMS?

O banco de dados de log crescerá rapidamente, especialmente em ambientes em que o RMS seja utilizado intensamente. Se estiver considerando o uso do SQL Server para o servidor de banco de dados, considere o uso do SQL Server 2000 Enterprise Edition ou SQL Server 2005 Enterprise Edition no Windows 2000 Advanced Server ou Windows Server 2003, Enterprise Edition, configurado em um cluster em uma configuração ativa-em espera. Nesse caso, as configurações recomendadas são discos de log RAID-1 e discos de dados RAID-5, e pelo menos 512 MB de RAM. A CPU mínima recomendada para essa configuração é um Pentium III com 1,4 GHz. Em servidores de bancos de dados dedicados, não é necessário haver várias CPUs.

<span id="BKMK_30"></span>
#### Como o uso do RMS do catálogo global para expansão de grupo afeta o desempenho do servidor de catálogo global?

O servidor RMS armazenará em cache qualquer lista de expansão de grupo para diminuir a carga no servidor de catálogo global. Atualizações freqüentes na participação de grupos aumentam a confiança no servidor de catálogo global, embora o tempo limite para adquirir novas listagens de grupos possa ser configurado pelo Registro. A expansão freqüente de grandes grupos prejudicará o desempenho. Para obter mais informações, consulte "Mudando as configurações de cache do Active Directory" em "RMS: operações" nesta coleção de documentos.

<span id="BKMK_31"></span>
#### O RMS exige alguma alteração de esquema no Active Directory?

Para que o RMS expanda com êxito a associação de grupo especificada na licença de publicação para além dos limites da floresta, deve existir um objeto de contato na floresta local do Active Directory que represente o grupo que se encontra na floresta remota. O RMS pode consultar os atributos do objeto de contato e descobrir se esse objeto representa um grupo que está em uma floresta diferente.

Para que o RMS faça isso, o Active Directory exige o atributo de esquema msExchOriginatingForest do Exchange Server 2003 ou posterior. Por padrão, esse atributo encontra-se instalado no esquema do Active Directory, se houver um servidor executando o Exchange Server 2003 na floresta. É preciso ter esse atributo na floresta de cada esquema do Active Directory que participará do RMS. Se não estiver usando o Exchange Server 2003, você poderá instalar o esquema separadamente em sua estrutura do Active Directory usando o Kit de Ferramentas de Administração do RMS.

<span id="BKMK_32"></span>
#### O ponto de conexão de serviço será automaticamente replicado entre os diferentes controladores de domínio no domínio no qual o servidor RMS está instalado?

Após o provisionamento do primeiro servidor RMS em uma floresta, ele deve ser registrado no Active Directory utilizando uma conta de domínio que tenha permissões suficientes para criar um objeto de contêiner abaixo do contêiner de serviços, no contêiner de configuração do Active Directory. O grupo de segurança interno Administradores de empresa é um exemplo de uma conta com as permissões necessárias. Isso cria o SCP. Como isso está no contêiner de serviços, o Active Directory replica as informações em todos os controladores de domínio da floresta.

<span id="BKMK_33"></span>
#### Se os usuários não tiverem direitos administrativos em suas máquinas, como o cliente do RMS pode ser instalado e configurado?

O cliente do RMS é um arquivo do Windows Installer e pode ser distribuído usando uma infra-estrutura de distribuição de software, como o Systems Management Server 2003. Também é possível distribuir o cliente do RMS usando um objeto de Diretiva de Grupo (GPO) que usa uma conta de serviço com direitos administrativos. Se o cliente do RMS estiver executando o Windows Vista, uma instalação separada do cliente do RMS não será mais necessária, pois ele é integrado ao sistema operacional.

<span id="BKMK_35"></span>
#### O que é a escalabilidade do RMS?

O RMS é um serviço Web sem estado e pode ser agrupado e ter a carga balanceada como qualquer outro site ou serviço da Web. O desempenho do RMS depende, principalmente, da disponibilidade do processador; portanto, a adição de processadores pode melhorar o desempenho.

<span id="BKMK_36"></span>
#### O RMS aceita módulos de segurança de hardware (HSMs) para proteger as chaves RMS no hardware?

Sim, o RMS funciona com HSMs compatíveis com CAPI, como o HSM nCipher.
