---
TOCTitle: Descoberta do serviço de ativação
Title: Descoberta do serviço de ativação
ms:assetid: 'e178d81b-b35c-4958-87ef-e077e2204b32'
ms:contentKeyID: 18123800
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747697(v=WS.10)'
---

Descoberta do serviço de ativação
=================================

O serviço de ativação emite cofres e certificados de máquina do RMS para clientes do RMS versão 1.0. Ele conta com o suporte de compatibilidade com versões anteriores ao RMS versão 1.0. O cluster raiz de certificação do RMS fornece o serviço de proxy de ativação que encaminha solicitações de ativação de máquina do RMS ao serviço de ativação a partir de computadores clientes em execução na rede corporativa.

Para fazer uma solicitação de ativação de máquina do RMS, um cliente do RMS versão 1.0 primeiro recupera, a partir do Active Directory, a URL para o diretório virtual de certificação do servidor raiz de certificação, onde o serviço de proxy de ativação está localizado. Em seguida, ele anexa o caminho para o serviço de proxy de ativação.

Por exemplo, a URL do diretório virtual de certificação que está no servidor raiz de certificação é armazenada no Active Directory na seguinte forma:

http://*nome\_do\_servidor*/\_wmcs/Certification

Quando um cliente solicita ativação de máquina do RMS, ele acrescenta à URL o nome de arquivo do serviço de proxy de ativação, da seguinte maneira:

http://*nome\_do\_servidor*/\_wmcs/Certification/Activation.asmx

Os clientes que estão em execução fora da rede corporativa usam UDDI para a descoberta de serviços, a fim de localizar o serviço de ativação. Para obter mais informações, consulte "[Publicação dos serviços hospedados pela Microsoft](https://technet.microsoft.com/7ee8cb4d-1b46-48be-8a4c-5ff6a458231a)", já mencionado neste tema.

> [!Note]  
> Se você habilitou a SSL no servidor RMS, essas URLs usarão o protocolo de conexão https://.
