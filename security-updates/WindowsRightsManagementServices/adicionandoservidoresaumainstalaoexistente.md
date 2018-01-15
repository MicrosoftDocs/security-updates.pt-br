---
TOCTitle: Adicionando servidores a uma instalação existente
Title: Adicionando servidores a uma instalação existente
ms:assetid: '7f3598ff-cd19-4daa-aa65-877f7f95a8ec'
ms:contentKeyID: 18123736
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747648(v=WS.10)'
---

Adicionando servidores a uma instalação existente
=================================================

Você pode adicionar servidores à instalação do RMS conforme for necessário para suprir o aumento da demanda ou substituir servidores que precisam ser retirados. Cada instalação do RMS deve incluir no mínimo um servidor raiz de certificação e, opcionalmente, pode incluir servidores raiz de certificação adicionais em um cluster. Cada instalação do RMS também pode incluir servidores de licenciamento autônomos ou em cluster.

É possível adicionar servidores a uma instalação do RMS usando um dos seguintes métodos:

-   Adicionar um ou mais servidores RMS a um cluster raiz de certificação.
-   Adicionar um novo servidor de licenciamento autônomo.
-   Adicionar um ou mais servidores RMS a um cluster de licenciamento.

**Adicionando servidores raiz de certificação**

Na maioria dos casos, adicionar um ou mais servidores RMS a um cluster raiz de certificação é a melhor maneira de aumentar a disponibilidade e a redundância da implantação. Um cluster raiz de certificação é um ou mais servidores raiz de certificação. Ao contrário de servidores de licenciamento, que fornecem somente serviços de licenciamento e de publicação, os servidores raiz de certificação fornecem todos os serviços do RMS.

Durante a instalação e a configuração, você pode optar por adicionar um servidor a um cluster. Quando o faz, o novo servidor RMS é automaticamente configurado como um membro do cluster. Para obter instruções detalhadas sobre a instalação e configuração de um servidor RMS a ser adicionado ao cluster raiz de certificação, consulte "[Instalar o RMS com Service Pack 1](https://technet.microsoft.com/dab20175-a690-43f8-b943-768d289daa0d)" e "[Adicionar um servidor a um cluster](https://technet.microsoft.com/db635238-5528-4bec-9cc6-8244e2b3d733)", mais adiante neste tema.

Além da etapa de configuração, se você estiver criando um cluster pela primeira vez, deverá instalar também software ou hardware com agrupamento e balanceamento de carga, conforme necessário. Se já tiver implementado um cluster, será necessário configurar o software ou o hardware de balanceamento de carga para funcionar com o novo membro do cluster.

**Adicionando servidores de licenciamento**

Ao contrário do servidor raiz de certificação que fornece todos os serviços do RMS, um servidor de licenciamento fornece somente serviços de licenciamento e de publicação.

Os servidores de licenciamento são opcionais e costumam ser implantados para resolver necessidades específicas de licenciamento, como as seguintes:

-   Para oferecer suporte a necessidades exclusivas de gerenciamento de direitos de um departamento. Por exemplo, um grupo dentro de sua organização pode ter diferentes requisitos de segurança para gerenciamento de direitos do que o restante da organização e pode desejar ter controle total sobre a implementação de licenciamento para o grupo deles. Como somente um servidor raiz de certificação é permitido em uma floresta, a configuração de um servidor raiz separado provavelmente não é apropriada. Nesse caso, você pode instalar um servidor de licenciamento ou cluster de licenciamento que seja dedicado às necessidades desse grupo. Em seguida, é possível instalar diretiva de direitos separadamente para esse servidor ou cluster de licenciamento.
-   Para oferecer suporte a gerenciamento de direitos para parceiros de negócios externos, como parte de uma extranet que exija forte separação e controle de recursos para parceiros de negócios específicos. Para obter mais informações, consulte "[Configurando uma URL de extranet](https://technet.microsoft.com/88fec9ff-c96c-4d20-8856-0485e7507572)", mais adiante neste tema.
-   Para descarregar tarefas de licenciamento do servidor raiz de certificação. Isso pode fornecer benefícios de desempenho em organizações que possuem um único servidor raiz de certificação (ao invés de um cluster raiz de certificação).

Na maioria dos casos, é recomendável adicionar servidores RMS ao cluster raiz de certificação para permitir a instalação de redundância e balanceamento de carga em todos os servidores que estão na implantação. Embora servidores de licenciamento também possam ser usados para descarregar o processamento de solicitações de licenças e de publicação, eles não podem usar o balanceamento de carga com o cluster raiz de certificação. A menos que exista uma necessidade específica de implantar servidores de licenciamento separados, é melhor balancear a carga de todos os servidores RMS, tornando-os membros do cluster raiz de certificação.

Para obter instruções detalhadas sobre a instalação e configuração de um servidor de licenciamento RMS, consulte "[Instalar o RMS com Service Pack 1](https://technet.microsoft.com/dab20175-a690-43f8-b943-768d289daa0d)" e "[Configurar um servidor de licenciamento](https://technet.microsoft.com/4d67b898-0ba9-4eef-ab7d-ee0ca55a688e)", mais adiante neste tema.
