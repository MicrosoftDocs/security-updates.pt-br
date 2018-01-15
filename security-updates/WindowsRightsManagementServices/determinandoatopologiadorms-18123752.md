---
TOCTitle: Determinando a topologia do RMS
Title: Determinando a topologia do RMS
ms:assetid: 'bf516f7d-b3a1-4e7f-971f-bfab1db41812'
ms:contentKeyID: 18123752
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747651(v=WS.10)'
---

Determinando a topologia do RMS
===============================

Na topologia básica do RMS, o servidor ou cluster raiz de certificação do RMS em cada floresta do Active Directory fornece todos os serviços RMS de uma organização. A topologia do RMS funciona bem tanto nas grandes como nas pequenas organizações. Em uma topologia distribuída do RMS, um ou mais servidores de licenciamento (algumas vezes chamados de servidores de licenciamento em departamentos) podem fornecer alguns ou todos os serviços de licenciamento a usuários e grupos específicos da organização. Mesmo que o servidor raiz de certificação (ou cluster) continue a fornecer os serviços de certificação de conta e de proxy de ativação para toda a organização, a topologia distribuída do RMS é projetada para organizações que têm necessidades muito específicas de licenciamento e que desejam manter o controle do RMS em um segmento de sua organização.

Embora existam somente duas topologias básicas para RMS, os componentes das topologias podem ser muito diferentes. Para definir os componentes apropriados para a sua organização e criar a topologia certa para a implantação do RMS, você deve:

-   Avaliar as necessidades e os objetivos da organização;
-   Definir como o gerenciamento de direitos será usado;
-   Analisar os padrões e as cargas do tráfego projetado, de forma a implementar um nível adequado de serviço.

A definição da topologia e a tomada das decisões necessárias para implementar o seu projeto constituem um processo repetitivo que continuará até o final do planejamento do RMS.

Este tópico inclui:

-   [Identificando os componentes essenciais](https://technet.microsoft.com/c9ec225b-0e51-42f5-aff6-0aecb62e3b27)
-   [Estabelecendo os objetivos da topologia](https://technet.microsoft.com/8275a04d-3e5b-40b0-be9d-2f31b7aeca6b)
-   [Definindo o escopo da implementação do RMS](https://technet.microsoft.com/4b5fe1be-643e-47c4-bf9b-50d1e97108fb)
-   [Avaliando os requisitos de dimensionamento](https://technet.microsoft.com/89f0138c-946d-47d7-a286-041d4d9606a8)
-   [Fornecendo redundância e balanceamento de carga](https://technet.microsoft.com/162d547c-78a7-4848-b43e-58e481832af2)
-   [Avaliando os requisitos de migração](https://technet.microsoft.com/cec07f45-dc52-4004-860b-5cc33e5fc209)
-   [Planejando a infra-estrutura do servidor de banco de dados](https://technet.microsoft.com/b12354bd-3143-4d1f-b5aa-450c4550653c)
-   [Planejando a implantação entre florestas](https://technet.microsoft.com/2dfb40b7-95b1-4362-b32e-72867544b705)
-   [Planejando para usuários externos do RMS](https://technet.microsoft.com/107e1338-4dcf-4ed5-a49d-e875cc883db1)
-   [Planejando uma topologia básica do RMS](https://technet.microsoft.com/fec3201e-201f-4faf-910e-fa44132af83d)
-   [Planejando uma topologia distribuída do RMS](https://technet.microsoft.com/8773a1e0-6ac3-41f5-9866-5890cef08d04)
