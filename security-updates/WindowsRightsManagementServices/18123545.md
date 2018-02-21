---
TOCTitle: Fornecendo redundância e balanceamento de carga
Title: Fornecendo redundância e balanceamento de carga
ms:assetid: '162d547c-78a7-4848-b43e-58e481832af2'
ms:contentKeyID: 18123545
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720199(v=WS.10)'
---

Fornecendo redundância e balanceamento de carga
===============================================

Para assegurar que os usuários adquiram licenças e publiquem conteúdo sempre que necessário, é altamente recomendável implantar servidores RMS redundantes usando clusters. Isso significa que será necessário implantar um cluster raiz de certificação que consista em pelo menos dois servidores. Se um servidor de licenciamento separado também for implantado para oferecer suporte às necessidades específicas de licenciamento de um grupo individual que esteja na sua organização, implante o servidor de licenciamento como um cluster com pelo menos dois servidores.

Os vários servidores físicos do cluster raiz de certificação ou de qualquer cluster de licenciamento constituem uma “Web farm” atrás de uma URL compartilhada ou endereço virtual. Se a organização usa um server farm, é possível integrar o RMS a qualquer técnica usada para endereçamento virtual, como DNS de repetição alternada, o serviço Balanceamento de Carga de Rede ou uma solução dedicada de hardware.

Além do balanceamento de carga, o endereçamento virtual é útil quando usado com o RMS, pois remove a dependência de um servidor físico de serviços de certificação ou licenciamento. Nenhum computador de usuário final requer acesso direto a um único servidor que se encontra em um cluster.
