---
TOCTitle: Publicação dos serviços do RMS
Title: Publicação dos serviços do RMS
ms:assetid: '3cca9325-6bd3-49ad-aa3f-e0693205d3f4'
ms:contentKeyID: 18123559
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720247(v=WS.10)'
---

Publicação dos serviços do RMS
==============================

As URLs de serviços do RMS são publicadas no Active Directory durante a configuração do servidor. Durante a configuração, a instalação do RMS consulta o Active Directory para determinar se algum outro servidor RMS foi instalado nessa floresta. Se nenhum outro servidor RMS tiver sido instalado, a instalação do RMS configurará o servidor como servidor raiz de certificação. Antes de usar o RMS, você deve registrar o ponto de conexão de serviço no Active Directory, a fim de permitir que os clientes descubram a URL do servidor raiz de certificação. Clientes que solicitam conexões com os serviços que estão em execução no servidor raiz de certificação começam a consultar o Active Directory para obter a URL desse servidor raiz de certificação. Para obter mais informações, consulte "Registrando o ponto de conexão de serviço" em "Operando um servidor RMS", nesta coleção de documentos.

| ![](images/Cc720247.note(WS.10).gif)Observação                                                                                                                                                      |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Se sua topologia incluir múltiplos servidores que estão em um cluster de servidores raiz de certificação, a URL apontará para o servidor de equilíbrio de carga do cluster, fornecido pelo administrador durante a configuração. |
