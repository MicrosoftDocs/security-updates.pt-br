---
TOCTitle: Definindo diretivas de revogação
Title: Definindo diretivas de revogação
ms:assetid: 'e2fffe9f-def7-439b-a8aa-43f8a065813d'
ms:contentKeyID: 18123867
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747782(v=WS.10)'
---

Definindo diretivas de revogação
================================

A definição de diretivas de revogação organizacionais requer consideração e planejamento cuidadoso porque, embora a implementação da revogação forneça maior segurança para conteúdo protegido, ela pode afetar a capacidade do usuário de consumir conteúdo. Diretivas de revogação da implantação do RMS podem ser definidas no site de administração.

Revogação de terceiros
----------------------

Como o Microsoft Enrollment Service é o emissor do certificado de licenciante para servidor do servidor raiz de certificação da sua implantação do RMS, a Microsoft pode revogar seu certificado de licenciante para servidor. Contudo, a Microsoft somente revogará um certificado de licenciante servidor quando isso for solicitado por um tribunal.

Além do Serviço de Inscrição da Microsoft, é possível especificar um terceiro que possa revogar o certificado de licenciante servidor do seu servidor RMS. Esse terceiro pode ser uma entidade externa ou um par de chaves públicas ou particulares que o administrador gera em nome da organização. A chave particular do terceiro especificado pode assinar uma lista de revogação que revoga o certificado de licenciante servidor. Esse terceiro é especificado por sua chave pública durante a configuração do RMS. Os modelos de diretiva de direitos de seu servidor também podem ser configurados para permitir que terceiros revoguem o conteúdo, manifestos de aplicativos, licenças e certificados que foram emitidos por sua instalação do RMS. Para obter mais informações, consulte "[Criando e modificando modelos de diretiva de direitos](https://technet.microsoft.com/6014176f-ef71-4d29-b3e3-da129c18563d)", mais adiante neste tema.

> [!Important]  
> Se você decidir gerar seu próprio par de chaves para uso para revogação do certificado de licenciante do servidor raiz de certificação, certifique-se de mantê-lo em um local protegido.

A revogação de um certificado do licenciante servidor é uma decisão importante, porque todos os certificados e licenças emitidos por sua instalação do RMS se tornam inválidos quando esse certificado é revogado. Para obter mais informações sobre como revogar certificados de licenciante para servidor, consulte a seção "[Revogando certificados de licenciante para servidor](https://technet.microsoft.com/8020861d-d196-4431-8282-044675ef5616)".

Considerando como listas de revogação entram em efeito
------------------------------------------------------

Quando a revogação for necessária para uma parte específica de conteúdo protegido, todas as listas de revogação que estiverem registradas em computadores clientes serão usadas e terão efeito se uma condição especificada for atendida. Portanto, implemente a revogação com moderação, porque ela poderá causar o registro de listas de revogação em computadores clientes, e essas listas poderão ser aplicadas mais amplamente do que o pretendido. Para obter mais informações sobre como configurar essa opção, consulte "[Criando e modificando modelos de diretiva de direitos](https://technet.microsoft.com/6014176f-ef71-4d29-b3e3-da129c18563d)", já mencionado neste tema.

Balanceando segurança e utilização
----------------------------------

Quando você especifica diretiva de revogação em um modelo de diretiva de direitos, considere a necessidade de fornecer maior segurança para documentos em relação ao risco de que os usuários poderão encontrar problemas ao consumir conteúdo, conforme descrito no exemplo a seguir.

Como parte da configuração de uma lista de revogação em um modelo de diretiva de direitos, você também pode especificar um intervalo de atualização para a lista de revogação. Para consumir conteúdo publicado usando esse modelo de diretiva de direitos, deve existir uma lista de revogação no computador do usuário, e a lista não deve ser mais antiga do que o intervalo de atualização. Por exemplo, se o intervalo de atualização for 10, a lista de revogação deverá ter sido criada nos últimos 10 dias. Se a lista de revogação não existir no computador cliente ou se a data de criação da lista for mais antiga do que o intervalo de atualização, o aplicativo habilitado para RMS obterá a última lista de revogação do local especificado na licença de uso. No entanto, um usuário que não esteja conectado à rede talvez não possa obter uma lista de revogação atual e talvez não possa consumir o conteúdo.

As seguintes sugestões podem ajudar a aliviar esse problema:

-   Tenha cuidado ao especificar o intervalo de atualização de uma lista de revogação e execute as etapas para ter certeza de que uma lista de revogação atualizada esteja sempre acessível imediatamente para os usuários.
-   Mantenha listas de revogação em URLs que sejam acessíveis interna e externamente à rede corporativa.
-   Use o Microsoft® SMS (Systems Management Server) ou um mecanismo semelhante para distribuir cópias atualizadas de listas de revogação para cada computador cliente em um intervalo definido, como por exemplo, toda noite.
-   Exija revogação somente para os tipos de documentos mais confidenciais.
