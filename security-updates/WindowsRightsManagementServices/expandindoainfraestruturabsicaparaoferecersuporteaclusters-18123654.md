---
TOCTitle: 'Expandindo a infra-estrutura básica para oferecer suporte a clusters'
Title: 'Expandindo a infra-estrutura básica para oferecer suporte a clusters'
ms:assetid: '78f0f2f0-a075-409c-9f46-26eb62d1d05b'
ms:contentKeyID: 18123654
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747567(v=WS.10)'
---

Expandindo a infra-estrutura básica para oferecer suporte a clusters
====================================================================

Se estiver implementando clusters para implantações maiores, verifique se sua infra-estrutura está configurada para oferecer suporte aos requisitos do cluster. Os itens a seguir devem ser incluídos nos seus planos de implantação.

Registro do DNS
---------------

Certifique-se de que qualquer registro do DNS feito para expor o endereço IP virtual à extranet também expõe o endereço à intranet.

Se o registro do DNS não for feito para a intranet, as solicitações de licença dos clientes internos falharão. Se você não puder modificar as configurações do DNS, a tabela de hosts de cada servidor que está no cluster poderá ser modificada para mapear a URL do cluster para o endereço IP virtual do cluster. O registro do DNS precisa ser feito antes da configuração do serviço; se você já configurou o serviço, deverá remover o RMS do servidor e depois repetir o processo de configuração.

Balanceamento de carga
----------------------

Configure o hardware e o software necessários para habilitar a implantação de servidores de balanceamento de carga, o serviço de Balanceamento de Carga de Rede ou o balanceamento de carga de hardware, conforme apropriado, para distribuir as solicitações no cluster.
