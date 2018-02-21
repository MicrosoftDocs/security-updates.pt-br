---
TOCTitle: 'Perguntas freqüentes sobre o RMS: Acesso interno e externo'
Title: 'Perguntas freqüentes sobre o RMS: Acesso interno e externo'
ms:assetid: '59c2c51f-6c20-450c-a334-0e1486292074'
ms:contentKeyID: 18123687
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747577(v=WS.10)'
---

Perguntas freqüentes sobre o RMS: Acesso interno e externo
==========================================================

Perguntas freqüentes sobre o acesso interno e externo ao RMS
------------------------------------------------------------

-   [Quais alterações devem ser feitas no firewall para permitir que clientes do RMS de fora do firewall acessem os servidores RMS?](#bkmk_37)
-   [Como funciona o cenário da extranet?](#bkmk_38)
-   [Se um usuário criar conteúdo protegido por direitos e fornecê-lo a alguém que não tenha acesso à instalação do RMS, o destinatário poderá usar o conteúdo?](#bkmk_39)
-   [Se eu usar o Outlook 2003 ou o Outlook 2007 para enviar um email protegido por direitos a um cliente, o que será necessário para que ele leia o email?](#bkmk_40)
-   [Se as organizações tiverem seus próprios servidores RMS, como elas poderão trocar conteúdo protegido por direitos?](#bkmk_41)
-   [Ao enviar um email protegido pelo RMS a uma organização externa que não ofereça suporte ao Outlook, o destinatário pode responder a um email lido usando o complemento do Rights Management para Internet Explorer?](#bkmk_42)

<span id="BKMK_37"></span>
#### Quais alterações devem ser feitas no firewall para permitir que clientes do RMS de fora do firewall acessem os servidores RMS?

O firewall deve permitir que computadores externos façam solicitações SOAP (Simple Object Access Protocol) ao servidor RMS usando HTTP (TCP porta 80) ou HTTPS (TCP porta 443).

<span id="BKMK_38"></span>
#### Como funciona o cenário da extranet?

Há duas URLs na licença de publicação vinculadas ao conteúdo. Uma é a URL da intranet, definida quando o cluster do RMS é provisionado. A segunda é uma URL da extranet, que pode ser definida pelo administrador do RMS. Essa URL da extranet permite que o cliente obtenha licenças de uso estando fora do firewall. A URL da extranet não pode ser usada para a criação de novo conteúdo protegido por direitos. Nesse caso, uma substituição do Registro do cliente do RMS é necessária.

<span id="BKMK_39"></span>
#### Se um usuário criar conteúdo protegido por direitos e fornecê-lo a alguém que não tenha acesso à instalação do RMS, o destinatário poderá usar o conteúdo?

Se o usuário não tiver uma conexão com a instalação do RMS quando o conteúdo protegido for aberto pela primeira vez, ele não poderá usar o conteúdo.

Observe que o Office 2003 ou posterior obtém licenças de uso automaticamente para email protegido por direitos quando é feita a sincronização, de modo que o email possa ser lido sem uma conexão de rede. No entanto, embora o Outlook 2003 ou posterior automaticamente armazene em cache as licenças de uso para um email, qualquer documento do Excel 2007, Excel 2003, Word 2007, Word 2003, PowerPoint 2007 e PowerPoint 2003 anexado ao email terá os mesmos direitos do email que o contém. Esses documentos não são automaticamente sincronizados quando o email é baixado e devem ser abertos individualmente quando o computador está conectado à rede para obter uma licença de uso.

<span id="BKMK_40"></span>
#### Se eu usar o Outlook 2003 ou o Outlook 2007 para enviar um email protegido a um cliente, o que será necessário para que ele leia o email?

O destinatário precisa usar o Outlook 2003, o Outlook 2007 ou o complemento do Rights Management para Internet Explorer. Se a organização do destinatário tiver estabelecido uma relação de confiança entre a instalação RMS dela e a sua, o destinatário poderá ler o email sem precisar realizar etapas adicionais. O relacionamento de confiança é estabelecido quando são trocados os certificados de licenciante para servidor RMS, que contêm as respectivas chaves públicas.

Se a organização do destinatário não tiver uma infra-estrutura de RMS ou se nenhum relacionamento de confiança for estabelecido, você poderá pedir que o cliente estabeleça um Windows Live ID e, em seguida, enviar o email a ele, especificando os direitos atribuídos às credenciais do Windows Live ID do cliente. Essa abordagem utiliza o serviço de Gerenciamento de Direitos de Informação (IRM) da Microsoft, disponível na Internet, para obter uma licença de uso. O serviço IRM é fornecido sem custo para permitir que as pessoas o utilizem em caráter de experiência e destina-se apenas a testes do RMS. Se você desejar proteger o conteúdo utilizando esse serviço, esteja ciente de que ele pode ser descontinuado no futuro sem aviso prévio.

<span id="BKMK_41"></span>
#### Se as organizações tiverem seus próprios servidores RMS, como elas poderão trocar conteúdo protegido por direitos?

O RMS utiliza domínios de usuário confiáveis e graças a eles os certificados de usuário gerados por uma instalação do RMS são considerados confiáveis por outra.

<span id="BKMK_42"></span>
#### Ao enviar um email protegido pelo RMS a uma organização externa que não ofereça suporte ao Outlook, o destinatário pode responder a um email lido usando o complemento do Rights Management para Internet Explorer?

O destinatário do email pode responder a um email protegido por direitos como se fosse qualquer outro email, mas o corpo original do email recebido permanecerá protegido por direitos para os destinatários originais. O modo como esse email é empacotado é determinado pelo aplicativo cliente. O email original pode ser anexado à resposta como um anexo criptografado ou pode ser removido completamente, como o Outlook 2003 ou o Outlook 2007 fazem, por exemplo.
