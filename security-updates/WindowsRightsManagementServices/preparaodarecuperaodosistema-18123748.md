---
TOCTitle: Preparação da recuperação do sistema
Title: Preparação da recuperação do sistema
ms:assetid: '885c047f-1e3b-4bf5-8248-3a4505759cbb'
ms:contentKeyID: 18123748
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747659(v=WS.10)'
---

Preparação da recuperação do sistema
====================================

A falha de qualquer componente do sistema RMS, o que inclui as conexões com Internet e intranet usadas pelo servidor RMS, o servidor de certificação RMS, qualquer dos servidores de licenciamento com sub-registro do RMS ou os servidores de banco de dados que hospedam os bancos de dados de configuração do RMS, pode ocasionar uma perda inesperada do serviço. Quando se configura um sistema RMS, é importante considerar o impacto potencial que uma perda do serviço RMS teria nos sistemas de TI e nos dados sigilosos e preparar-se para recuperar o componente da maneira mais eficiente possível.

A falha dos servidores de banco de dados que hospedam os bancos de dados de configuração do RMS seria um dos fatores que impediriam a continuação do acesso às informações protegidas do RMS. Esta seção descreve considerações e fatores importantes na preparação da recuperação de um sistema RMS, entre os quais os seguintes:

-   [Conectividade com a Internet](#bkmk_1)
-   [Conectividade com a intranet](#bkmk_2)
-   [Serviços de certificação e licenciamento](#bkmk_3)
-   [Servidores de bancos de dados](#bkmk_4)
-   [Active Directory](#bkmk_5)

<span id="BKMK_1"></span>
Conectividade com a Internet
----------------------------

Se você estiver usando o registro de servidor online, o servidor RMS precisará de conectividade com a Internet durante a configuração para obter um certificado de licenciante para servidor (SLC) e para renová-lo uma vez por ano. Quando o fim do período de um ano estiver próximo, o servidor de certificação avisará sobre a renovação do certificado registrando eventos no log de eventos do sistema. Os eventos são registrados um mês antes da data de vencimento do SLC (Identificação do evento 16), uma semana antes da data de vencimento do SLC (Identificação do evento 17) e no vencimento do SLC (Identificação do evento 18). A página Administração Global do RMS do site Administração do RMS também emitirá um alerta de que a data de vencimento do SLC está se aproximando. Se você estiver usando o RMS Management Pack para o Microsoft Operations Manager (MOM), os eventos de vencimento dispararão um alerta. Se não houver conexão com a Internet disponível no servidor RMS, o certificado de licenciante para servidor não poderá ser renovado com o uso do botão **Renovar** no site Administração do RMS, e o processo de registro offline deverá ser usado para a solicitação de um certificado atualizado.

A prática recomendada é renovar o SLC bem antes da data do seu vencimento para evitar complicações caso a conexão com a Internet esteja indisponível quando o certificado vencer. O servidor RMS não pode fornecer serviços RMS sem um SLC válido, o que significa que os usuários não conseguirão publicar informações protegidas pelo RMS nem obter as licenças de uso e os certificados de conta de direitos de uso (RACs) requeridos para a leitura das informações protegidas pelo RMS. Os usuários que tiverem adquirido previamente licenças de uso e RACs para conteúdo protegido pelo RMS poderão continuar a acessar as informações até suas licenças de uso ou RACs vencerem.

<span id="BKMK_2"></span>
Conectividade com a intranet
----------------------------

O RMS é uma tecnologia de cliente-servidor que depende de uma infra-estrutura conectada. Sem uma rede de intranet em funcionamento, os servidores RMS não podem conectar-se aos serviços requeridos dentro da empresa ou aos usuários para fornecer serviços. Sem conectividade com a intranet, os usuários não podem obter certificados de conta de direitos (RACs), certificados de licenciante para cliente (CLCs) nem licenças de uso dos servidores RMS.

Recomenda-se que as organizações considerem usar arquiteturas de roteamento redundantes e links de failover entre sites remotos e sites do servidor RMS.

Obtido um CLC para esse computador, o usuário poderá publicar informações protegidas pelo RMS offline quando não houver acesso a um servidor RMS. Alguns aplicativos de email habilitados para RMS têm sido configurados para baixar automaticamente, na sincronização de caixas de correio, licenças de uso para emails associados protegidos pelo RMS, de modo que o usuário possa ler os emails protegidos pelo RMS mesmo que a conexão com a intranet não esteja mais presente.

<span id="BKMK_3"></span>
Serviços de certificação e licenciamento
----------------------------------------

O sistema RMS depende em grande medida de dois diretórios virtuais do Serviços de Informações da Internet (IIS) 6.0: os serviços de certificação e de licenciamento. Esses serviços permitem que os usuários e seus computadores se registrem no ambiente do RMS e nos aplicativos habilitados para RMS para publicar e acessar informações protegidas por RMS. Se esses serviços se tornarem indisponíveis, os usuários poderão ter o serviço negado até que eles sejam restaurados.

Para estar preparado para a perda potencial de serviço, considere a criação de clusters de servidores de certificação e de servidores de licenciamento com sub-registro, a fim de que a queda de um nó em um cluster não afete a disponibilidade do serviço.

Recomenda-se a criação de excesso de capacidade nos clusters para que os defeitos de nós individuais não afetem o desempenho global. Ao instalar o primeiro servidor de certificação e cada servidor de licenciamento com sub-registro, ou o primeiro servidor de licenciamento de sub-registro em um cluster, grave cuidadosamente as opções de configuração e os dados digitados na configuração.

<span id="BKMK_4"></span>
Servidores de bancos de dados
-----------------------------

Os componentes mais importantes do sistema RMS são os servidores de banco de dados que armazenam os bancos de dados de configuração. Cada servidor RMS ou cluster de servidores usa bancos de dados para armazenar a configuração e as informações de registro. As informações de configuração são essenciais para a operação do RMS. Esses bancos de dados armazenam o certificado de licenciante para servidor, os modelos de diretiva do RMS produzidos e uma lista dos usuários registrados no sistema RMS; se não for usado um módulo de segurança de hardware com o servidor RMS, eles também conterão as chaves particulares e públicas do servidor RMS. Com backups dos bancos de dados do RMS, você também restaura uma instalação anterior do RMS em um novo servidor e recria um sistema RMS. O impacto da perda de um banco de dados difere, dependendo do banco de dados. A lista a seguir descreve o impacto da falha de um determinado banco de dados:

-   **Banco de dados de configuração**. Se este banco de dados se tornar indisponível durante a operação do servidor RMS, os serviços RMS poderão continuar a operar porque o RMS armazena localmente em cache as informações requeridas. Todavia, na ocorrência de um evento que requeira que o serviço RMS interaja com o banco de dados de configuração, como o registro de um novo usuário, o serviço RMS encontrará um erro e o novo usuário não poderá trabalhar com o conteúdo protegido pelo RMS. Se ocorrer uma operação que faça o servidor RMS descartar as informações armazenadas em cache, como a reinicialização do serviço de IIS ou uma atualização programada do cache local, o serviço RMS parará de funcionar. O servidor RMS não poderá retornar ao serviço normal enquanto o banco de dados de configuração não estiver disponível.
    Se o banco de dados de configuração se corromper ou se tornar permanentemente indisponível, os servidores RMS pararão de funcionar.
-   **Banco de dados de serviços de diretório**. Guarda as informações armazenadas em cache sobre nomes de grupos e os detalhes de suas participações obtidos de um servidor do catálogo global. Não existe diminuição perceptível nos serviços RMS quando essa tabela se torna indisponível por curtos períodos de tempo. Sua finalidade principal é fornecer redundância e reduzir as cargas de serviço para o servidor do catálogo global.
-   **Banco de dados de log**. Se o log tiver sido habilitado no servidor RMS, este será o banco de dados a ser usado para armazená-lo. Quando o banco de dados estiver indisponível, as entradas de log se acumularão no serviço Enfileiramento de Mensagens (também conhecido como MSMQ) no servidor RMS e usarão todo o espaço de disco disponível, a menos que tenham sido configuradas para não fazê-lo.

A prática recomendada é que os servidores de banco de dados sejam colocados em cluster para proteção de failover ativa-em espera. Faça também regularmente backups dos bancos de dados de servidores e dos clusters de certificação RMS, bem como dos servidores e clusters de licenciamento.

Outra prática recomendada é usar o envio de logs de transação como um meio de manter pronto um banco de dados de backup. Embora possa requerer hardware adicional, essa prática permite que as organizações recuperem os bancos de dados com maior rapidez. A TI da Microsoft implementou esse método para a recuperação do banco de dados de configuração do RMS. Para fazê-lo, selecione o nome virtual do SQL durante a configuração do RMS. O nome virtual do SQL permite mapear o nome real do SQL com o uso do DNS (sistema de nome de domínio). Em caso de parada do SQL Server original, você pode alternar facilmente para o SQL Server reserva alterando o mapeamento do nome do DNS do servidor original para o servidor reserva. Para obter mais informações sobre a implementação interna dessa solução na Microsoft, consulte o estudo de caso da Microsoft Corporation no [site da Microsoft](http://go.microsoft.com/fwlink/?linkid=42070)(http://go.microsoft.com/fwlink/?LinkId=42070).

<span id="BKMK_5"></span>
Active Directory
----------------

O RMS depende do Active Directory para dois serviços importantes: a autenticação do usuário e o serviço do catálogo global. Se o Active Directory não estiver disponível, a autenticação do usuário não será possível, e os usuários e seus computadores não poderão registrar-se no sistema RMS. Requer-se um canal de certificação para a obtenção de um RAC; esse canal requer autenticação. Quando tiver um RAC, o usuário poderá obter licenças de uso sem autenticação adicional, posto que o canal de licenciamento é anônimo por padrão.

Como as entidades empresariais podem usar participação de grupo no Active Directory para expressar quem tem acesso às informações protegidas por RMS, a perda do Active Directory impede que os usuários adquiram licenças de uso. Por padrão, as informações da participação no grupo são armazenadas no servidor RMS por 15 minutos, para que uma perda temporária do servidor do catálogo global possa ser tolerada. Você modifica a chave do Registro que controla o tempo de validade para aumentar ou diminuir o tempo entre as atualizações do cache. Para obter mais informações, consulte "Modificando as configurações de cache do Active Directory" em "Operando um servidor RMS", nesta coleção de documentos.
