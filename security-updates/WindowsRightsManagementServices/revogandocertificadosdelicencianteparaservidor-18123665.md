---
TOCTitle: Revogando certificados de licenciante para servidor
Title: Revogando certificados de licenciante para servidor
ms:assetid: '8020861d-d196-4431-8282-044675ef5616'
ms:contentKeyID: 18123665
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747578(v=WS.10)'
---

Revogando certificados de licenciante para servidor
===================================================

Uma organização pode precisar revogar um certificado de licenciante servidor devido a circunstâncias não previstas que resultam no comprometimento do servidor RMS. Uma chave particular que não é mantida em um módulo de segurança de hardware está vulnerável a roubo. Um certificado de licenciante para servidor e chave podem estar comprometidos em uma organização por um hacker que assuma o controle do servidor ou por um funcionário insatisfeito que consiga copiar ou remover o certificado ou a chave. A revogação é uma maneira de conter o dano e limitar o mau uso por um usuário mal-intencionado.

Por padrão, qualquer licença ou certificado pode ser revogado pela entidade que a emitiu. Como os servidores RMS emitem as licenças e certificados associados a seu conteúdo protegido, você pode revogá-los sempre que necessário. Se um servidor de licenciamento estiver comprometido, será possível revogar seu certificado de licenciante servidor. Quando um certificado de licenciante servidor é revogado, todos os certificados e licenças emitidos por ele são invalidados. Instruções sobre revogação de licenças e certificados são fornecidas na seção "[Implementando a revogação](https://technet.microsoft.com/4735f060-7197-4ae2-830a-f91bcc4de30a)", já mencionado neste tema.

O cluster raiz de certificação, no entanto, é um caso especial. O certificado de licenciante para servidor do cluster raiz de certificação é emitido pelo Serviço de Inscrição Microsoft e, por padrão, somente esse serviço pode revogar esse certificado.

A Microsoft pode revogar o certificado de licenciante servidor de um servidor raiz de certificação somente se você obtiver uma ordem judicial e fornecer a chave pública do servidor ao tribunal. Depois que o tribunal notificar a Microsoft de que um pedido de revogação foi enviado, a Microsoft especificará o certificado de licenciante servidor pela chave pública em sua lista de revogação e tornará a lista publicamente disponível. Você pode solicitar um pedido de revogação do tribunal, quando uma das seguintes condições for verdadeira em relação ao servidor cuja licença deve ser revogada:

-   O servidor é de sua propriedade, e sua chave particular foi comprometida.
-   Você é proprietário do conteúdo que está sendo publicado pelo servidor e esse conteúdo está sendo publicado como uma violação a seus direitos autorais.

Siga as etapas descritas em "[Implantando listas de revogação](https://technet.microsoft.com/e331338b-66d4-45e4-8d3f-acccf2302ac4)", já mencionada nesta seção, para obter e distribuir listas de revogação da Microsoft que incluem o certificado de licenciante para servidor de um servidor raiz de certificação.

Ao configurar o servidor raiz de certificação, você pode especificar uma chave pública que tenha autoridade para revogar o certificado de licenciante servidor do cluster raiz de certificação. Essa chave pública pode pertencer à organização ou a um terceiro. Uma lista de revogação assinada pela chave particular correspondente pode revogar o certificado de licenciante servidor.

Para revogar o certificado de licenciante servidor do servidor raiz de certificação, você pode criar uma lista de revogação que especifique esse certificado de licenciante servidor, assiná-la com a chave particular da sua organização ou de terceiros e, em seguida, distribuir a lista de revogação a todos os usuários. Para obter instruções, consulte "Implantando listas de revogação organizacionais" em "[Implantando listas de revogação](https://technet.microsoft.com/e331338b-66d4-45e4-8d3f-acccf2302ac4)", mais adiante neste tema.

É possível revogar um certificado de licenciante servidor em uma lista de revogação usando os seguintes parâmetros:

-   **GUID**. Um certificado de licenciante servidor pode ser revogado por sua GUID (identificação global exclusiva). Para obter informações sobre o uso desse parâmetro em uma lista de revogação, consulte a seção "Revogando certificados e licenças com base na GUID" em "[Criando listas de revogação](https://technet.microsoft.com/1ef75199-3344-4225-84de-a863a777696a)", mais adiante neste tema.
-   **Valor hash**. Um certificado de licenciante servidor pode ser revogado com base em um hash SHA-1 dos caracteres Unicode que estão no corpo do certificado. Para obter informações sobre o uso desse parâmetro em uma lista de revogação, consulte a seção "Revogando certificados e licenças com base no valor hash" em "[Criando listas de revogação](https://technet.microsoft.com/1ef75199-3344-4225-84de-a863a777696a)", mais adiante neste tema.

Para obter o certificado de licenciante servidor de uma instalação do RMS, é necessário consultar o banco de dados de configuração do RMS. As seguintes etapas descrevem como obter essas informações de um banco de dados de configuração SQL e salvá-las em um arquivo que pode ser lido facilmente em um navegador:

1.  Abra o Analisador de Consultas SQL e conecte-se ao banco de dados de configuração do servidor raiz de certificação.
2.  No menu **Consultar**, clique em **Resultados em Texto**.
3.  No menu **Ferramentas**, clique em **Opções** para abrir a caixa de diálogo **Opções**. Clique na guia **Resultados** e defina **Máximo de caracteres por coluna** até **8192**.
        ```
1.  Copie os resultados da janela **Resultados** e cole-os em um editor de texto, como o Bloco de Notas. Salve os resultados em um arquivo com uma extensão de nome de arquivo .xml.

Para obter mais informações sobre como usar essas informações em uma lista de revogação, consulte a seção "[Criando listas de revogação](https://technet.microsoft.com/1ef75199-3344-4225-84de-a863a777696a)", mais adiante neste tema.

Depois de salvar as informações do certificado de licenciante servidor como um arquivo XML, você poderá extrair a chave pública dele, procedendo da seguinte maneira:

1.  Abra o arquivo XML do certificado de licenciante servidor em um editor de arquivo XML ou de texto.
2.  Na seção &lt;ISSUEDPRINCIPALS&gt;, copie o elemento &lt;PUBLICKEY&gt;.
3.  Salve essa informação em um arquivo que possa ser enviado para o tribunal ou coloque-o em uma lista de revogação organizacional.

Depois que o certificado de licenciante servidor do cluster raiz de certificação for revogado, todos os certificados e licenças que foram emitidos por sua instalação do RMS tornam-se inválidos para o conteúdo que requeira uma lista de revogação e o conteúdo será inacessível. Esse processo não é afetado pelo tipo de licença que o usuário possui. Para reter conteúdo que foi publicado pelo servidor cuja licença está sendo revogada, você deve executar uma das seguintes ações antes de implementar a lista de revogação:

-   Salve o conteúdo sem proteção por RMS.
-   Publique o conteúdo novamente sem um requisito de lista de revogação.

Nos dois cenários (revogação pela Microsoft ou revogação por um terceiro), a lista de revogação tem efeito para todas as solicitações de vinculação, porque foi assinada pela chave particular de uma entidade na cadeia de confiança da licença de uso. Portanto, todas as solicitações de vinculação que envolvem licenças emitidas pela instalação do RMS usando o certificado de licenciante servidor revogado falharão.

| ![](images/Cc747578.note(WS.10).gif)Observação                                     |
|-----------------------------------------------------------------------------------------------------------------|
| A Microsoft somente revogará um certificado de licenciante servidor quando isso for solicitado por um tribunal. |
