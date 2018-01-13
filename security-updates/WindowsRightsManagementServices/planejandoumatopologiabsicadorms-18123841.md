---
TOCTitle: Planejando uma topologia básica do RMS
Title: Planejando uma topologia básica do RMS
ms:assetid: 'fec3201e-201f-4faf-910e-fa44132af83d'
ms:contentKeyID: 18123841
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747755(v=WS.10)'
---

Planejando uma topologia básica do RMS
======================================

A topologia básica do RMS consiste em um ou mais servidores físicos que formam o cluster raiz de certificação. Esse cluster é usado para certificação, licenciamento e publicação na organização. Normalmente, para todas as implantações, exceto a menor, vários servidores físicos são configurados como um cluster por trás de uma única URL. Esse cluster é criado pela configuração do primeiro servidor para criar o servidor raiz de certificação e, depois, pela adição de servidores ao cluster até se alcançar o número de servidores raiz de certificação necessários para oferecer suporte à atividade projetada. A figura a seguir ilustra essa topologia.

![](images/Cc747755.a3332719-4d25-4694-a89a-7c31fd97ca3b(WS.10).gif)

Os servidores inscritos em um cluster compartilham os mesmos bancos de dados de configuração e registro, que são os bancos de dados do SQL Server. O SQL Server pode residir tanto no servidor raiz de certificação quanto em um servidor independente.

O balanceamento de carga é instalado ao longo de todos os servidores que estão no cluster raiz de certificação. Todas as solicitações de certificados e licenças serão passadas para o cluster raiz de certificação por meio do URL comum especificado na configuração do primeiro servidor deste cluster.

Se precisar suportar um pequeno número de clientes, você poderá configurar o RMS em um único servidor com um banco de dados local. O servidor é responsável por todas as certificações e licenciamentos na organização. Essa configuração oferece um único ponto de falha, portanto é recomendável fazer backup das suas configurações regularmente.
