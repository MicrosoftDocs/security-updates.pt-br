---
TOCTitle: Operando um servidor RMS
Title: Operando um servidor RMS
ms:assetid: '1533426b-89c2-43e0-8068-ca97ddab8606'
ms:contentKeyID: 18123588
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720205(v=WS.10)'
---

Operando um servidor RMS
========================

Este tema trata das tarefas de gerenciamento executadas após a implantação do RMS em uma organização. São fornecidas informações para ajudá-lo a gerenciar o servidor RMS, procedimentos de tarefas administrativas comuns e recursos para informações adicionais, bem como informações sobre práticas recomendadas.

Tópicos relacionados

-   [Gerenciando o RMS](https://technet.microsoft.com/9b573c55-c14c-436c-b3c5-7ba445de1562)
-   [Como ...](https://technet.microsoft.com/82032075-f361-438f-a2c4-93ab29ae6cff)
-   [Recursos do RMS](https://technet.microsoft.com/d91221cf-e38e-4add-b7b9-50e63aad9a28)

Terminologia usada neste guia
-----------------------------

**certificação de conta**  
O processo que associa contas de usuário a pares de chaves no certificado de conta de direitos ou RAC.

<!-- -->

**serviço de certificação de conta**  
Um serviço do RMS na Web que cria e distribui certificados de conta de direitos. Consulte também certificação de conta.

<!-- -->

**serviço de proxy de ativação**  
Um serviço do RMS na Web que oferece suporte à ativação de máquina cliente do RMS versão 1.0. Usado para encaminhar solicitações de ativação ao Serviço de Ativação da Microsoft. O serviço de ativação gera um cofre e um certificado correspondente de máquina do RMS exclusivos para o computador cliente, que o serviço de proxy de ativação no servidor RMS encaminha ao cliente solicitante. Consulte também cofre.

<!-- -->

**serviço de administração**  
Um serviço do RMS na Web que hospeda o site de administração, permite o gerenciamento do RMS e atualiza o banco de dados de configuração do cluster.

<!-- -->

**manifesto de aplicativo**  
Um documento XML que descreve os módulos de um aplicativo associado e habilitado para RMS e o que pode ser executado no ambiente do aplicativo. Qualquer aplicativo que faz gravações nas APIs do cliente do RMS para criar ou consumir informações protegidas pelo RMS deve fornecer um manifesto em tempo de execução.

<!-- -->

**atributo**  
No Active Directory, a propriedade de um objeto. Para cada classe de objeto, o esquema define quais atributos uma instância da classe deve ter e quais atributos adicionais poderia ter.

<!-- -->

**vinculação**  
O mecanismo que exerce direitos em um sistema RMS, no qual o cliente do RMS valida as condições de uma licença de uso em relação aos direitos que estão sendo solicitados. Se essas condições forem atendidas, os direitos serão concedidos.

<!-- -->

**certificado**  
Um documento digital normalmente usado para autenticação e para proteger informações em redes abertas. Um certificado vincula com segurança uma chave pública à entidade que armazena a chave particular correspondente. Certificados são assinados digitalmente pela autoridade de certificação emissora, e podem ser emitidos para um usuário, um computador ou um serviço. Consulte também chave particular; chave pública.

<!-- -->

**inscrição de cliente**  
O processo de criação do certificado de licenciante cliente, o qual permite ao computador ou dispositivo do usuário criar licenças de publicação que serão respeitadas por um servidor de licenciamento.

<!-- -->

**certificado de licenciante cliente**  
O certificado criado por um servidor RMS e colocado em computadores clientes do RMS, o qual permite aos usuários publicar conteúdo protegido offline, sem estarem conectados à rede habilitada para RMS. O certificado de licenciante cliente contém a chave que o cliente do RMS usa para assinar licenças de publicação digitalmente.

<!-- -->

**condição**  
Um conjunto de restrições e parâmetros específicos que fazem parte do grupo de direitos contidos em uma licença de publicação. Eles são aplicados no momento do consumo. Uma condição de tempo é uma condição comum que permite que um usuário defina uma data de expiração para as informações protegidas pelo RMS.

<!-- -->

**banco de dados de configuração**  
O banco de dados que contém informações de configuração do RMS para um servidor ou cluster.

<!-- -->

**consumindo conteúdo**  
Descriptografando e exercendo direitos de uso de um conteúdo protegido.

<!-- -->

**chave de conteúdo**  
A chave usada para criptografar e descriptografar conteúdo protegido durante a publicação e o consumo. Também conhecida como chave simétrica. O RMS utiliza chaves de conteúdo AES de 128 bits.

<!-- -->

**proprietário de conteúdo**  
A pessoa ou organização que estabelece a diretiva de acesso para o conteúdo protegido.

<!-- -->

**descriptografia**  
O processo de tornar dados criptografados novamente legíveis através da conversão de texto cifrado em texto sem formatação.

<!-- -->

**assinatura digital**  
Um meio pelo qual os originadores de uma mensagem, arquivo ou outras informações codificadas digitalmente vinculam suas identidades às informações. O processo de assinatura digital de informações significa transformar as informações, além de algumas informações secretas do remetente, em uma marca chamada assinatura. Assinaturas digitais são usadas em ambientes de chave pública e fornecem serviços de não-repúdio e integridade.

<!-- -->

**serviço DRMRemote**  
Um serviço do RMS na Web que expõe serviços através do .NET Remoting, o qual é usado para comunicação entre diferentes servidores RMS.

<!-- -->

**criptografia**  
O processo de converter informações em um formato que só possa ser lido por um receptor específico. A criptografia é um meio eficaz para ajudar a proteger informações. Para decifrar um arquivo criptografado, o receptor deve ter a chave secreta ou senha que o converterá. Consulte também criptografia de chave pública.

<!-- -->

**inscrição**  
O processo pelo qual o servidor raiz de certificação obtém um certificado de licenciante para servidor assinado pelo Microsoft Enrollment Service.

<!-- -->

**solicitação de inscrição**  
Uma solicitação enviada pelo servidor raiz de certificação RMS ao Serviço de Inscrição da Microsoft para obter um certificado de licenciante servidor.

<!-- -->

**exclusão**  
O processo usado pelo servidor RMS para recusar uma solicitação de licença de uso a um cliente com base na diretiva de exclusão. Consulte também lista de exclusão.

<!-- -->

**lista de exclusão**  
A lista de entidades que terão as licenças recusadas pelo serviço de licenciamento do RMS.

<!-- -->

**diretiva de exclusão**  
Definições do banco de dados de configuração do RMS que controlam a forma como a exclusão é aplicada na organização.

<!-- -->

**eXtensible rights Markup Language**  
O formato baseado em XML usado pelo RMS para todas as licenças que contam com suporte: certificados de máquina, certificados de conta de direitos, certificados de licenciante para cliente, licenças de uso, licenças de publicação e certificados de licenciante para servidor, que são documentos que determinam a diretiva de RMS aplicada ao conteúdo protegido.

<!-- -->

**licença de emissão**  
Dados que especificam a diretiva de RMS aplicada a conteúdo protegido.

<!-- -->

**cluster de licenciamento**  
Um ou mais servidores que executam os serviços de licenciamento e publicação do RMS fora do cluster raiz de certificação. Esses servidores usam um banco de dados e uma URL de conexão em comum e devem ser implantados atrás de um balanceador de carga de software ou de hardware, se for utilizado mais de um servidor. Ao contrário de um cluster raiz ou de certificação, o(s) servidor(es) RMS de um cluster de licenciamento não pode(m) executar a certificação de usuário.

<!-- -->

**servidor de licenciamento**  
Um servidor que executa os serviços de licenciamento e publicação do RMS fora do cluster raiz de certificação.

<!-- -->

**serviço de licenciamento**  
Um serviço do RMS na Web que emite licenças de uso.

<!-- -->

**cofre**  
O módulo do software responsável pela autenticação do uso válido do conteúdo protegido, criptografia e descriptografia das informações e pela proteção do processamento confiável do software contra modificação e visualização. Também conhecido como repositório seguro.

<!-- -->

**serviço de log**  
Um serviço ouvinte do RMS que transfere dados registrados da fila de mensagens para o banco de dados de registro do servidor ou cluster do RMS.

<!-- -->

**ativação de máquina**  
O processo de obtenção de um cofre exclusivo e certificado de máquina para um computador com RMS versão 1.0. No RMS versão 1.0 SP1, ativação de máquina é o processo de obtenção de um certificado de máquina para cada usuário dessa máquina.

<!-- -->

**manifesto**  
O documento XML assinado que identifica as bibliotecas ou os programas que podem ou não ser carregados no espaço de processamento do aplicativo.

<!-- -->

**Serviço de Ativação da Microsoft**  
Um serviço da Web hospedado na Microsoft que emite certificados de máquina de e cofres do RMS em resposta às solicitações do cliente do RMS versão 1.0.

<!-- -->

**Serviço de Inscrição da Microsoft**  
Um serviço da Web hospedado na Microsoft que emite um certificado de licenciante servidor para o servidor raiz de certificação em uma implantação do RMS.

<!-- -->

**pré-certificação**  
Um recurso do serviço de certificação do RMS que permite a um aplicativo solicitar um certificado de conta de direitos ao servidor RMS em nome de um usuário. Certificados de conta de direitos obtidos com a pré-certificação contêm somente a chave pública do usuário.

<!-- -->

**entidade**  
Alguém (usuário, grupo ou gerente de conteúdo protegido) que tenha uma função estabelecida no esquema de segurança do RMS e cujos objetos possam ser protegidos.

<!-- -->

**chave particular**  
A metade secreta de um par de chaves de criptografia que é usada com um algoritmo de chave pública. Geralmente, as chaves particulares são usadas para descriptografar uma chave de sessão simétrica, assinar dados digitalmente ou descriptografar dados que tenham sido criptografados com a chave pública correspondente. Consulte também chave pública; criptografia de chave pública.

<!-- -->

**configurar**  
Preparar um servidor RMS para funcionar em uma organização.

<!-- -->

**chave pública**  
A metade não secreta de um par de chaves de criptografia que é usada com um algoritmo de chave pública. Geralmente, chaves públicas são usadas para criptografar uma chave de sessão, para verificar uma assinatura digital ou para criptografar dados que possam ser descriptografados com a chave particular correspondente. Consulte também chave particular; criptografia de chave pública.

<!-- -->

**criptografia de chave pública**  
Um método de criptografia que usa duas chaves de criptografia relacionadas matematicamente. Uma delas é a chave particular e é confidencial. A outra é a chave pública e é fornecida gratuitamente a todos os correspondentes em potencial. Em um cenário comum, um remetente usa a chave pública do receptor para criptografar uma mensagem. Somente o receptor tem a chave particular relacionada para descriptografar a mensagem. A complexidade da relação entre a chave pública e a chave particular significa que, desde que as chaves sejam longas o suficiente, é impossível determinar uma a partir da outra usando recursos de computação. Esse método também é chamado de criptografia assimétrica. Consulte também chave particular; chave pública.

<!-- -->

**licença de publicação**  
A licença criada ao publicar conteúdo protegido pelo RMS. Especifica, entre outros itens, quem pode acessar o conteúdo, quais são os direitos concedidos e sob quais condições esse conteúdo pode ser acessado. Também conhecida como licença de emissão.

<!-- -->

**serviço de publicação**  
Um serviço do RMS que assina licenças de publicação e emite certificados de licenciante cliente. Consulte também certificado de licenciante para cliente; licença de publicação

<!-- -->

**RAC**  
Consulte definição de certificado de conta de direitos.

<!-- -->

**revogação**  
Um processo pelo qual as entidades são colocadas em uma lista de licenças inválidas.

<!-- -->

**lista de revogação**  
Um documento baseado em XrML que lista os certificados e as licenças que foram revogados pelo emissor. Consulte também revogação.

<!-- -->

**direito**  
Uma ação permitida a usuários específicos para conteúdo protegido pela tecnologia do RMS. Esses direitos podem ter mais restrições ao se usar condições.

<!-- -->

**certificado de conta de direitos**  
O certificado que usa o certificado de máquina da ativação de RMS para vincular uma conta e uma chave de usuário a um computador específico ou a grupos de computadores. Os componentes do certificado são usados para permitir aos consumidores o uso de conteúdo protegido. Também conhecido como GIC (certificado de identificação de grupo) no SDK do RMS.

<!-- -->

**gerenciamento de direitos**  
Uma tecnologia que fornece proteção consistente aos dados digitais, usando criptografia, certificados e autenticação. Os destinatários ou usuários autorizados devem adquirir uma licença para consumir os arquivos protegidos, de acordo com os direitos ou as regras comerciais estabelecidos pelo proprietário do conteúdo.

<!-- -->

**cliente do RMS (Rights Management Services)**  
Um conjunto de APIs de RMS que cada computador cliente de um sistema RMS deve instalar. É um pré-requisito para a ativação de máquina e é obrigatório para o uso de aplicativos habilitados para RMS.

<!-- -->

**modelo de diretiva de direitos**  
Descreve um conjunto padrão de usuários, direitos e condições que pode ser aplicado ao conteúdo protegido pelo RMS. Quando um usuário aplica um modelo de diretiva de direitos a um conteúdo, os direitos e as condições que ele descreve tornam-se parte da licença de publicação.

<!-- -->

**ativação de RMS**  
O processo de colocação de um cofre no computador de um usuário final com RMS versão 1.0. Ela pode ser fornecida apenas pelo serviço de ativação de RMS e é essencial para o uso da tecnologia do RMS. No RMS versão 1.0 SP1, esse é o processo de obtenção de um certificado de máquina para um usuário dessa máquina e não requer uma conexão com o serviço de ativação de RMS. Também conhecida como ativação.

<!-- -->

**Serviço de Certificação do RMS**  
Um serviço da Web hospedado pela Microsoft que emite certificados de conta de direitos para usuários com base nas credenciais que possuem do Microsoft .NET Passport.

<!-- -->

**cliente do RMS**  
Um conjunto de APIs de RMS que cada computador cliente de um sistema RMS deve instalar. É um pré-requisito para a ativação de máquina e é obrigatório para o uso de aplicativos habilitados para RMS.

<!-- -->

**certificado de máquina de RMS**  
O certificado colocado no computador de um usuário final durante a ativação de RMS. A chave pública nesse certificado é usada para criptografar a chave particular do usuário, existente nos certificados de conta de direitos do usuário.

<!-- -->

**aplicativo habilitado para RMS**  
Um aplicativo que foi ampliado pelo SDK do Rights Management Services a fim de permitir que os usuários especifiquem os direitos relacionados ao conteúdo que criarem.

<!-- -->

**computador habilitado para RMS**  
Um computador que possui o componente cliente do RMS instalado e que foi submetido à ativação de máquina de RMS para poder processar conteúdo protegido pelo RMS.

<!-- -->

**conteúdo protegido por RMS**  
Informações digitais protegidas pela tecnologia do RMS.

<!-- -->

**cluster raiz de certificação**  
Um ou mais servidores em uma implantação do RMS que executam serviços de administração, inscrição, certificação de conta, proxy de ativação, licenciamento e publicação. Esses servidores usam um banco de dados e uma URL de conexão em comum e devem ser implantados atrás de um balanceador de carga de software ou de hardware. Pode haver apenas um cluster raiz de certificação por floresta do Active Directory.

<!-- -->

**servidor raiz de certificação**  
O servidor principal em uma implantação do RMS que executa serviços de administração, inscrição, certificação de conta, proxy de ativação, licenciamento e publicação. Pode haver apenas um servidor raiz de certificação por floresta do Active Directory.

<!-- -->

**raiz de confiança**  
Uma entidade confiável que fornece a base para estabelecer a confiança de outros certificados. Todos os fornecedores de certificado e o usuário final devem confiar na raiz.

<!-- -->

**SID (identificação de segurança)**  
Uma estrutura de dados do Windows que identifica todas as contas de usuário, grupo e computador do Windows. Cada conta em uma rede recebe uma SID exclusiva quando é criada. Processos internos no Windows referem-se à SID de uma conta, em vez de um nome de usuário ou grupo da conta.

<!-- -->

**certificado de licenciante servidor**  
O certificado que estabelece as credenciais do servidor RMS, tornando-o um serviço de certificação e licenciamento válido e permitindo sua execução. O certificado de licenciante contém a chave particular usada para criptografar chaves de conteúdo em licenças de publicação.

<!-- -->

**serviço de servidor**  
Um serviço do RMS na Web destinado a ser usado por um outro serviço.

<!-- -->

**SCP (ponto de conexão de serviço)**  
Um objeto do Active Directory que faz referência à URL do cluster raiz de certificação de uma implantação do RMS. O cliente do RMS usa essas informações para localizar serviços do RMS.

<!-- -->

**subscrição**  
Parte do processo de configuração de um servidor de licenciamento através do qual o servidor de licenciamento obtém um certificado de licenciante servidor do cluster raiz de certificação.

<!-- -->

**solicitação de subscrição**  
Uma solicitação enviada por um servidor de licenciamento ao cluster raiz de certificação para obter um certificado de licenciante servidor.

<!-- -->

**serviço de subscrição**  
Um serviço do RMS na Web, no servidor raiz de certificação, que atende às solicitações de certificados de licenciante servidor enviadas pelos servidores de licenciamento durante a configuração.

<!-- -->

**superusuário**  
Um membro do grupo de superusuários.

<!-- -->

**grupo de superusuários**  
Um grupo de usuários opcional definido administrativamente em cada cluster do RMS, o qual terá licenças de proprietário concedidas pelo servidor RMS ao abrir conteúdo publicado por esse servidor.

<!-- -->

**licença de uso**  
A licença que lista os direitos e as condições sob as quais um usuário final pode consumir conteúdo protegido. Também conhecida como licença de usuário final.
