---
TOCTitle: Adicionando servidores para oferecer suporte a certificação e licenciamento
Title: Adicionando servidores para oferecer suporte a certificação e licenciamento
ms:assetid: '089ceb62-2a96-444f-ab42-1d5deaabd0c3'
ms:contentKeyID: 18123619
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720189(v=WS.10)'
---

Adicionando servidores para oferecer suporte a certificação e licenciamento
===========================================================================

Depois de instalar e configurar o primeiro servidor para estabelecer a instalação do servidor raiz para o RMS, você poderá configurar servidores adicionais para fornecer suporte estendido para serviços de certificação e licenciamento, tais como:

-   É possível adicionar um servidor como um membro do cluster raiz de certificação para oferecer suporte adicional de certificação e licenciamento. Os servidores adicionados a esse cluster usam a mesma configuração e os mesmos bancos de dados do servidor raiz de certificação.
-   Você pode configurar um servidor de licenciamento separado por si mesmo ou como membro de um cluster de servidor de licenciamento. Ele é criado com sub-registro no cluster raiz de certificação e recebe o seu SLC (certificado de licenciante para servidor) através dos serviços de certificação do servidor raiz de certificação. Qualquer solicitação do cliente de serviços de certificação feita ao servidor de licenciamento é encaminhada para o servidor de certificação. O servidor de licenciamento pode emitir licenças de uso e de publicação sem enviar a solicitação ao servidor raiz de certificação.

A opção que você decide implantar depende do tamanho da organização e de como deseja implementar redundância, escala, suporte ao balanceamento de carga e segurança. Se estiver implantando servidores RMS adicionais para suprir demandas crescentes de certificação, licenciamento e publicação, é preciso implantar os servidores RMS como parte do cluster raiz de certificação, de forma que se possa configurar redundância e balanceamento de carga em todos os servidores. Você pode agrupar servidores de certificação e descarregar o processamento para serviços de licenciamento e publicação criando sub-registros de servidores de licenciamento (que também podem ser agrupados para balanceamento de carga), mas não é possível fazer o balanceamento da carga de um cluster de licenciamento com sub-registro com um cluster raiz de certificação.

Os seguintes tópicos fornecem orientação para essa tarefa:

-   [Funções, permissões e direitos necessários para a instalação e a configuração](#bkmk_1)
-   [Processos de configuração para servidores de certificação e de licenciamento adicionais](#bkmk_2)
-   [Configurando clusters e balanceamento de carga](#bkmk_3)

<span id="BKMK_1"></span>
Funções, permissões e direitos necessários para a instalação e a configuração
-----------------------------------------------------------------------------

Para instalar e configurar servidores adicionais, são necessárias as mesmas funções, permissões e direitos que para configurar o servidor inicial. Além disso, você também deve ter a permissão do servidor raiz de certificação para configurar um servidor de licenciamento separado, o que é conhecido como sub-registro. O servidor raiz de certificação é controlado através da lista de controle de acesso condicional do arquivo SubEnrollService.asmx. Os membros do Grupo de Serviço RMS, incluindo a conta de serviço RMS que você especifica durante a configuração do servidor raiz de certificação, têm permissão para executar o sub-registro. Para obter mais informações, consulte “[Configurando serviços de certificação e de licenciamento no primeiro servidor](https://technet.microsoft.com/cce29a2f-984f-48ed-9187-0eb68286ec5b)”, já mencionado neste tópico.

<span id="BKMK_2"></span>
Processos de configuração para servidores de certificação e de licenciamento adicionais
---------------------------------------------------------------------------------------

Adicionar servidores a clusters de certificação e licenciamento requer que o servidor conclua o processo de configuração. O processo de configuração varia com base no tipo do servidor que está sendo configurado.

-   Se você estiver configurando um servidor de licenciamento separado, especifique um banco de dados de configuração, uma conta de serviço RMS, uma URL de cluster e informações de proteção de chave particular do mesmo modo que você especificou essas informações para um servidor raiz de certificação. No entanto, você não especifica uma diretiva de revogação de certificado de licenciante para servidor; essa diretiva é controlada pelo servidor raiz de certificação.
-   Se você estiver configurando um servidor como membro do cluster, as únicas informações que você precisa especificar durante a configuração são a conta de serviço RMS, o banco de dados de configuração e a senha para proteção de chave particular (ou usar o mesmo CSP \[provedor de serviços de criptografia\] e chave particular do cluster existente). Todos os servidores que estão em um cluster compartilham o mesmo certificado de licenciante para servidor e par de chaves do servidor.

> [!Important]  
> Só inicie a instalação do RMS em outros servidores quando você tiver concluído a instalação do RMS no primeiro servidor, incluindo a instalação propriamente dita e a configuração desse servidor. 

Depois de você ter instalado e configurado um servidor adicional, ele será automaticamente configurado como um membro do cluster. Entretanto, se você implementou o balanceamento de carga, será necessário configurar o software de balanceamento de carga para trabalhar com o novo servidor.

<span id="BKMK_3"></span>
Configurando clusters e balanceamento de carga
----------------------------------------------

O RMS foi desenvolvido para oferecer suporte a clusters de servidores. A criação de clusters de servidores RMS fornece uma melhor escalabilidade, confiabilidade e balanceamento de carga da implantação do RMS.

**Criando clusters**

Para instalar um cluster, comece com um servidor raiz de certificação ou um servidor de licenciamento. Do segundo servidor em diante que se encontra em cada cluster, instale o RMS no novo servidor, vá para a página **Administração Global** e clique em **Adicionar este servidor a um cluster** para configurar os recursos necessários e associar o servidor ao cluster raiz de certificação ou ao cluster de licenciamento.

Especifique o nome do banco de dados para o cluster que você deseja associar.

**Clusters de balanceamento de carga**

O RMS não implementa o balanceamento de carga automaticamente. Você pode usar o balanceamento de carga de hardware ou de software, incluindo o Balanceamento de Carga de Rede, para balancear a carga em todos os servidores RMS.

Os tópicos a seguir fornecem detalhes adicionais sobre esse assunto:

-   Para obter mais informações sobre as diferenças entre serviços de certificação e de licenciamento, consulte "Visão geral do sistema RMS" em "Referência técnica do RMS", nesta coleção de documentos.
-   Para obter mais informações sobre como mapear as implantações de servidores de acordo com as necessidades de disponibilidade e desempenho da sua organização, consulte "Fornecendo redundância e balanceamento de carga" em "Planejando uma implantação do RMS", nesta coleção de documentos.
-   Para obter mais informações sobre como determinar o número de servidores necessários para oferecer suporte à implantação do RMS na sua organização, consulte "Avaliando os requisitos de dimensionamento" em "Planejando uma implantação do RMS", nesta coleção de documentos.
-   Para obter mais informações sobre como implementar a segurança de TI com a implantação do RMS, consulte "[Protegendo a implantação do RMS](https://technet.microsoft.com/6de8b636-a824-4844-aefc-f26347abfc14)" mais adiante neste tópico.
-   Para obter informações sobre como instalar o RMS, consulte "Instalar o RMS com Service Pack 1" em "Operando um servidor RMS", neste coleção de documentos.
    Você também pode instalar o RMS a partir de um prompt de comando. Para obter mais informações, consulte "Instalação do RMS a partir do prompt de comando" em "Operando um servidor RMS", nesta coleção de documentos.
-   Para obter informações sobre como configurar um servidor de licenciamento, consulte "Configurar um servidor de licenciamento" em "Operando um servidor RMS”, nesta coleção de documentos.
-   Para obter informações sobre como configurar servidores adicionais em um cluster, consulte "Adicionar um servidor a um cluster" em "Operando um servidor RMS”, nesta coleção de documentos.
