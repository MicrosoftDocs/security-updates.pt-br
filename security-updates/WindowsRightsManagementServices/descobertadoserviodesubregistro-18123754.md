---
TOCTitle: 'Descoberta do serviço de sub-registro'
Title: 'Descoberta do serviço de sub-registro'
ms:assetid: 'b159953a-af38-4a9e-8c87-1aff5fb4e366'
ms:contentKeyID: 18123754
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747641(v=WS.10)'
---

Descoberta do serviço de sub-registro
=====================================

Um servidor de licenciamento individual, ou o primeiro servidor de licenciamento do cluster, deve submeter uma solicitação de sub-registro ao servidor raiz de certificação do RMS e obter um certificado de licenciante para servidor. Para fazer isso, o servidor de licenciamento obtém a URL do serviço de sub-registro raiz de certificação, conforme indicado a seguir.

Durante a configuração de um servidor de licenciamento, a instalação do RMS consulta o Active Directory e depois detecta o ponto de conexão de serviço do cluster raiz de certificação. O RMS usa a URL que está armazenada nesse ponto de conexão de serviço para localizar o cluster raiz de certificação e depois envia uma solicitação de certificado de licenciante para servidor a partir do serviço de sub-registro do servidor raiz de certificação.

Para fazer uma solicitação de serviço de sub-registro, primeiro o servidor de licenciamento recupera, a partir do Active Directory, a URL para o diretório virtual de certificação do servidor raiz de certificação, onde o serviço de sub-registro está localizado. Em seguida, ele acrescenta o caminho ao serviço de sub-registro.

Por exemplo, a URL do diretório virtual de certificação no servidor raiz de certificação é armazenada no Active Directory na seguinte forma:

http://*nome\_do\_servidor*/\_wmcs/Certification

Quando um servidor de licenciamento solicita o serviço de sub-registro, ele acrescenta o nome do arquivo de serviço à URL, da seguinte forma:

http://nome\_do\_servidor/\_wmcs/Certification/SubEnrollService.asmx

> [!Note]  
> Se você habilitou a SSL no servidor RMS, essas URLs usarão o protocolo de conexão https://.
