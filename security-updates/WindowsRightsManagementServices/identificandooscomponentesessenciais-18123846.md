---
TOCTitle: Identificando os componentes essenciais
Title: Identificando os componentes essenciais
ms:assetid: 'c9ec225b-0e51-42f5-aff6-0aecb62e3b27'
ms:contentKeyID: 18123846
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747751(v=WS.10)'
---

Identificando os componentes essenciais
=======================================

Para estabelecer uma topologia apropriada, é importante entender os componentes básicos de uma implantação do RMS e as funções que eles desempenham. A lista a seguir identifica os servidores que farão parte da implantação do RMS:

-   Servidores raiz de certificação. O servidor raiz de certificação é o primeiro componente de uma implantação do RMS; todos os demais componentes dependem dele. O servidor raiz de certificação executa todos os serviços RMS, inclusive o serviço de certificação de conta que fornece certificados de conta de direitos aos clientes do RMS da organização. Pode haver apenas um servidor raiz de certificação em cada floresta do Active Directory. Você pode, porém, adicionar diversos servidores à instalação para criar um cluster raiz de certificação que possa ser usado para fins de redundância e balanceamento de carga. Todos os servidores que fazem parte do cluster raiz de certificação usam o mesmo banco de dados de configuração, definido quando você configurou o primeiro servidor de certificação na instalação.
-   Servidores de licenciamento. O servidor de licenciamento é opcional e não faz parte do cluster raiz de certificação; no entanto, ele é criado com sub-registro sob o servidor raiz de certificação. O servidor de licenciamento depende do servidor raiz de certificação para certificação e outros serviços (ele não pode fornecer serviços de certificação de conta); mas ele executa serviços de licenciamento para fornecer licenças de publicação e licenças de uso. Para configurar redundância e balanceamento de carga, adicione diversos servidores à instalação para criar um cluster de licenciamento. Todos os servidores que fazem parte do cluster de licenciamento usam o mesmo banco de dados de configuração, definido quando você configurou o primeiro servidor de licenciamento desse cluster.
-   Servidores que executam componentes da infra-estrutura. Outros servidores que estejam em sua implantação podem oferecer a infra-estrutura necessária, inclusive componentes como SQL Server 2000 e Active Directory. O local de implantação desses componentes e a quantidade de servidores necessários dependem de suas necessidades.

A topologia do RMS que você projetar para a sua organização deverá atender à implantação de cada um desses componentes.
