---
TOCTitle: Registrando o servidor raiz de certificação
Title: Registrando o servidor raiz de certificação
ms:assetid: '3f69d25e-ecae-447f-b741-a819c8cf6227'
ms:contentKeyID: 18123560
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720250(v=WS.10)'
---

Registrando o servidor raiz de certificação
===========================================

Cada instalação do RMS deve incluir no mínimo um servidor raiz de certificação e, opcionalmente, pode incluir servidores raiz de certificação adicionais em um cluster. O primeiro servidor raiz de certificação deve ser registrado com o Microsoft Enrollment Service para obter-se um certificado de licenciante para servidor raiz. Esse certificado serve como a base para a hierarquia de confiança em uma implementação do RMS.

É possível obter um certificado de licenciante para servidor raiz usando um dos métodos a seguir. Você poderá selecionar qual deseja usar ao completar as informações de configuração do seu servidor RMS:

-   **Inscrição online**. Se o servidor raiz de certificação tiver a capacidade de se conectar à Internet, você poderá obter um certificado de licenciante servidor automaticamente durante a configuração. Esse é o método padrão.
-   **Inscrição offline**. Se o servidor raiz de certificação não estiver na Internet, você poderá inscrevê-lo manualmente após a conclusão do processo de configuração. Para isso, exporte uma solicitação de inscrição desse servidor para um arquivo que possa ser levado para outro computador com conexão à Internet e utilize o Serviço de Inscrição da Microsoft para obter um certificado de licenciante servidor. Se a inscrição offline for escolhida no momento da configuração, o RMS completará o processo de configuração, mas não poderá ser usado até que o certificado de licenciante servidor obtido pelo outro computador tenha sido importado. Para obter mais informações, consulte "[Registrar manualmente um servidor raiz de certificação](https://technet.microsoft.com/aecdebb5-b28b-4b58-937a-392bb6ce9643)", mais adiante neste tema.

A solicitação de inscrição inclui as seguintes informações:

-   Informações sobre revogação. Se a instalação do RMS for usar revogação padrão ou personalizada (terceiros). Se estiver sendo usada a revogação de terceiros da Microsoft, será incluída a chave pública da autoridade de revogação.
-   Chave pública do certificado. A chave pública do certificado de licenciante servidor. Essa chave pública é gerada no servidor RMS e enviada ao Serviço de Inscrição da Microsoft para obtenção do certificado de licenciante servidor.
-   SKU. O título oficial do SKU no RMS.
-   Versão. O número da versão de montagem do RMS.
-   URL. A URL da base do cluster do servidor RMS.

Quando o Serviço de Inscrição da Microsoft fornece uma resposta à solicitação de inscrição, ele retorna as seguintes informações ao servidor RMS no formato XML:

-   Certificado de licenciante servidor.
-   Cadeia de certificados das autoridades signatárias.

As mesmas informações são transferidas se o servidor raiz de certificação RMS for registrado usando o método online ou offline. Nenhuma informação adicional é reunida quando um dos dois métodos é empregado.

> [!Note]  
> Se você optou pelo uso da inscrição Offline e está usando um computador que possui uma configuração avançada de segurança de navegador, como um computador executando o Windows Server 2003 ou o Windows XP Service Pack 2, para conectar-se à Internet e solicitar um certificado de licenciante servidor, certifique-se de adicionar a URL do site do Serviço de Inscrição à zona de Sites Confiáveis para permitir que seja baixado o certificado de licenciante servidor. A URL é https://activation.drm.microsoft.com. Se estiver usando o processo de inscrição offline, verifique se o computador usado para enviar a solicitação de inscrição ao Serviço de Inscrição da Microsoft tem todas as atualizações de certificado mais recentes instaladas. O certificado SSL do Serviço de Inscrição da Microsoft é o GTE Cyber Trust Root CA, que é confiável por padrão para todos os computadores que executam o Windows Server 2003. Se você estiver usando o processo de inscrição Offline, deve se certificar de que os clientes do RMS não tentem se conectar ao servidor RMS para obter licenças até que a inscrição tenha ocorrido. Se os clientes tentarem se conectar a um servidor RMS que não esteja inscrito, os serviços da Web apresentarão um erro que os deixará inutilizáveis. Se você não pode assegurar que os clientes não tentarão se conectar ao servidor RMS, a prática recomendada é redefinir o IIS (Internet Information Services) após concluir a inscrição, a fim de desfazer qualquer condição de erro que possa ter sido criada. 
