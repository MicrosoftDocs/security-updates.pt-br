---
TOCTitle: Planejando uma topologia distribuída do RMS
Title: Planejando uma topologia distribuída do RMS
ms:assetid: '8773a1e0-6ac3-41f5-9866-5890cef08d04'
ms:contentKeyID: 18123747
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747657(v=WS.10)'
---

Planejando uma topologia distribuída do RMS
===========================================

Em alguns casos, pode ser necessário implantar um ou mais servidores de licenciamento que não sejam membros do cluster raiz de certificação. Em geral, isso é feito para fornecer suporte a departamentos que requerem controle direto sobre a emissão de licenças de publicação e de uso, como um departamento legal com requisitos de segurança que exigem controle em nível de departamento. O cluster raiz de certificação oferece o serviço de certificação de conta para os servidores de licenciamento. A combinação de um cluster raiz de certificação com uma ou mais instalações de servidores de licenciamento é chamada de topologia distribuída.

Observe que, assim como o servidor raiz de certificação, os servidores de licenciamento também podem ser implantados em um cluster. Além disso, assim como ocorre com o cluster raiz de certificação, o cluster de licenciamento usa seu próprio serviço de balanceamento de carga. Cada servidor de licenciamento ou cluster de licenciamento usa uma instância independente do SQL Server para fornecer os bancos de dados de configuração e log ao servidor ou cluster específico.

Apesar de ser possível configurar a instalação do RMS para executar somente os serviços de certificação na instalação raiz, bem como executar o serviço de licenciamento inteiro de um ou mais servidores ou clusters de licenciamento, essa não é a configuração típica. Geralmente, aumenta-se a quantidade de servidores físicos no cluster raiz de certificação para suprir as necessidades de desempenho e redundância, em vez de implantar servidores de licenciamento independentes (a menos que haja necessidade de suporte departamental para licenciamento). O diagrama a seguir ilustra essa implantação.

![](images/Cc747657.01fa5a85-5711-41aa-932a-124049d34186(WS.10).gif)

A criação de uma topologia distribuída pode aumentar os custos administrativos devido ao fato de ser, por natureza, mais complexa. Se a organização tiver vários clusters de licenciamento e várias florestas, talvez você precise fazer substituições do Registro nos computadores clientes do RMS para assegurar que eles farão as solicitações de licenciamento usando o servidor RMS correto. Além disso, podem ocorrer problemas de confiança nos domínios. Se isso acontecer, você terá de fazer configurações adicionais nos seus domínios para habilitar o consumo do conteúdo protegido por RMS.

Pontos de conexão de serviço em uma topologia distribuída
---------------------------------------------------------

Quando você configurar um servidor RMS, a URL do cluster será adicionada à floresta do Active Directory em um SCP (ponto de conexão de serviço). Há um SCP para o cluster raiz de certificação e para cada cluster de licenciamento configurado na floresta. É necessário que o SCP seja registrado para o cluster raiz de certificação antes de você configurar um cluster de licenciamento. Quando você configura o cluster de licenciamento, o processo de sub-registro usa essa URL para localizar o cluster raiz de certificação na rede e obtém um certificado de licenciante para servidor.

Se um cluster raiz de certificação for implantado em vez de um único servidor raiz de certificação, cada servidor que estiver no cluster deverá poder ser endereçado virtualmente atrás de uma URL compartilhada.

Há diversas implementações de endereçamento virtual como, por exemplo, o DNS de repetição alternada, o serviço Balanceamento de Carga de Rede, soluções de hardware etc. O endereçamento virtual oferece balanceamento de carga nos servidores e também elimina a dependência de um único servidor para licenciamento e publicação.

O RMS usa a URL compartilhada para sua URL de aquisição de licença, bem como para o valor publicado usado pelos computadores de usuários finais quando consultam o cluster RMS no Active Directory ou no Registro. Nenhum computador de usuário final requer acesso direto a um único servidor que se encontra em um cluster.
