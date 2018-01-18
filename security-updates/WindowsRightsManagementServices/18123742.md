---
TOCTitle: Estabelecendo os objetivos da topologia
Title: Estabelecendo os objetivos da topologia
ms:assetid: '8275a04d-3e5b-40b0-be9d-2f31b7aeca6b'
ms:contentKeyID: 18123742
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747652(v=WS.10)'
---

Estabelecendo os objetivos da topologia
=======================================

Uma das etapas mais importantes no design de topologias consiste em estabelecer objetivos adequados. Algumas das principais áreas que devem ser levadas em conta no design de topologia do RMS são:

-   **Custos administrativos**. A topologia do site deve minimizar os custos administrativos. Isso inclui a centralização do gerenciamento do servidor sempre que possível e a redução do número de servidores usados.
-   **Latência da rede**. A latência da rede entre o cliente e o servidor será percebida pelos usuários, pois haverá um atraso adicional quando abrirem emails e documentos. Em geral, verifique se a latência é inferior a dois segundos para cada direção em pelo menos 90% das ocorrências.
-   **Confiabilidade**. É necessário que a rede entre o cliente e o servidor seja confiável o suficiente para que uma única solicitação e resposta HTTP tenha uma taxa de falha, que indica uma transação perdida ou danificada, de menos de 5%.

Essas são apenas diretrizes gerais. Você deve estabelecer seus próprios objetivos com base nos requisitos e recursos de sua organização. O estabelecimento de objetivos é o ponto de partida para determinar se uma topologia supre as suas necessidades. Há muitos fatores que afetam a maneira pela qual os objetivos são alcançados, como o número de usuários, solicitações de licença, consultas, mensagens e outros fatores de tráfego relacionados ao RMS. Além disso, a estratégia de implantação, incluindo os domínios e as florestas nos quais você pretende implantar o RMS, pode ter um impacto significativo na realização dos objetivos de topologia. Durante todo o processo de design de topologia, tenha sempre seus objetivos em mente e determine o impacto que cada processo de design terá em seus objetivos.
