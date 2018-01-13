---
TOCTitle: Otimizando o desempenho
Title: Otimizando o desempenho
ms:assetid: '24dc9ca4-652b-41a6-9a99-95fdeca9120b'
ms:contentKeyID: 18123606
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720220(v=WS.10)'
---

Otimizando o desempenho
=======================

Os tópicos desta seção fornecem informações sobre a otimização do desempenho da implantação do RMS.

Otimizando o desempenho dos serviços de diretório
-------------------------------------------------

Você pode monitorar os contadores de desempenho dos serviços de diretório que estão incluídos no RMS. Se necessário, você pode otimizar o desempenho modificando as configurações do registro que controlam os atributos do cache do Active Directory.

As configurações do registro controlam os seguintes atributos do cache do Active Directory:

-   Número máximo de entidades a serem armazenadas em cache.
-   Período de validade das informações que são armazenadas em cache para as entidades.
-   Número máximo de grupos a serem armazenados em cache.
-   Período de validade das informações que são armazenadas em cache para grupos.
-   Número máximo de entradas de participação de grupo.
-   Período de validade das informações que são armazenadas em cache para participação de grupo.

Em geral, quanto mais longo o período de validade das informações no cache ou quanto mais entradas estão no cache, mais rapidamente o RMS pode responder a solicitações que requerem a obtenção de serviços de diretório. Se as informações forem armazenadas no cache do Active Directory, uma viagem de ida e volta ao Active Directory para executar uma consulta não será necessária. Isso reduz o tempo de resposta da solicitação.

O dilema de armazenar mais informações no cache do Active Directory é que serão necessários mais recursos de memória do sistema. Outro problema a ser considerado quando você configura definições do registro é que quanto mais longo for o período de validade especificado para um item, haverá mais probabilidade de que os resultados retornados pelo cache do Active Directory sejam inválidos. Isso poderá ocorrer se as informações forem alteradas no Active Directory, mas a alteração ainda não estiver refletida no cache do Active Directory. Se o Active Directory for alterado com freqüência, você poderá especificar um período de validade mais curto para informações armazenadas no cache: um que reflita essa freqüência.

Os contadores de desempenho dos serviços de diretório são descritos na seção "[Contadores de desempenho RMS: Contadores de desempenho para o objeto DirectoryServices](https://technet.microsoft.com/37afea1d-f320-4040-96d8-57c0b45e6d46)", mais adiante neste tema. Para obter instruções sobre como usá-los, consulte a seção "[Usando contadores de desempenho](https://technet.microsoft.com/096c3b17-c082-46c4-939c-4373af0c9dec)", já mencionado neste tema. Os contadores a serem monitorados são os "acertos" versus "perdas". O RMS deve executar uma consulta no Active Directory para cada perda.

Para obter detalhes sobre configurações de Registro e instruções sobre como modificá-las, consulte a seção "[Alterando as configurações de cache do Active Directory](https://technet.microsoft.com/8789a7a5-2065-4fae-9104-e0a70f1f2fb6)", mais adiante neste tema.

Otimizando configurações do pool de conexões do Active Directory
----------------------------------------------------------------

Para melhorar o desempenho do sistema, é possível adicionar e modificar chaves do registro que controlam as configurações do pool de conexões LDAP do Active Directory. A configuração de chaves do Registro é descrita na seção “[Alterando as configurações do Registro do pool de conexão](https://technet.microsoft.com/c61d91db-a1ad-4ca5-a492-015da629afbc)”, mais adiante neste tema.

O RMS foi desenvolvido para otimizar conexões LDAP. Ele estabelece uma conexão para cada catálogo global do Active Directory e cada conexão pode atender a vários segmentos. Para fornecer solidez, ele mantém um pool de conexões para atender a solicitações. Para evitar a colocação de uma grande carga em um único catálogo global, o RMS usa um algoritmo para distribuir solicitações, executando balanceamento de carga entre os catálogos globais que estão na lista de catálogos globais a serem consultados. Ele também trata automaticamente erros de LDAP e faz novo roteamento de solicitações para um catálogo global diferente, conforme necessário.

O RMS cria uma lista de catálogos globais para consulta, usando o algoritmo de Descoberta de Topologia. Você pode especificar os números mínimo e máximo de catálogos globais disponíveis que a Descoberta de Topologia deve localizar ante que os serviços do RMS possam ser iniciados. A Descoberta de Topologia primeiro descobre os catálogos globais que estão no site atual. Se catálogos globais adicionais forem necessários, ele os pesquisará em outros sites. Você também especifica o número máximo de conexões que podem se tornar indisponíveis antes que o RMS pare de aceitar solicitações. Se um ou mais catálogos globais na lista de consulta se tornarem indisponíveis mais tarde, a Descoberta de Topologia começará a pesquisar catálogos globais substitutos para adicionar à lista de consulta.

Como alternativa, você pode listar os catálogos globais que deseja que o RMS use. Nesse caso, a Descoberta de Topologia não pesquisa catálogos globais para adicionar à lista de consulta.

Você também pode configurar definições sobre como o RMS executa balanceamento de carga entre os catálogos globais. Você pode especificar a importância relativa das seguintes considerações ao decidir se deve enviar uma solicitação específica a um catálogo global específico.

-   **Repetição alternada (WtRoundRobin)**. Esse parâmetro especifica a importância relativa do balanceamento de carga que usa a lógica de repetição alternada. A definição de peso padrão é 1, o que significa que essa é a consideração de menor importância para o servidor levar em conta ao selecionar um catálogo global.
-   **Contagem de segmentos durante a conexão (WtThreadCount)**. Esse parâmetro especifica a importância relativa do número de segmentos que são alocados a uma conexão. A configuração de peso padrão é 100, o que significa que é 100 vezes mais importante que a contagem de segmentos de um catálogo global seja baixa para que uma conexão seja selecionada, do que é para o balanceamento de carga, usando a lógica de repetição alternada.
-   **Conexão lenta (WtSlow)**. Esse parâmetro especifica a importância relativa de uma conexão lenta. A configuração do peso padrão é 1.000, o que significa que é 10 vezes mais importante que uma conexão a um catálogo global não seja lenta para que seja selecionada, do que para que a contagem de segmentos seja baixa.
