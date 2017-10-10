---
TOCTitle: 'Perguntas freqüentes sobre o RMS: Administração'
Title: 'Perguntas freqüentes sobre o RMS: Administração'
ms:assetid: '43f77336-5e62-4405-9efb-55417a402d62'
ms:contentKeyID: 18123645
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747547(v=WS.10)'
---

Perguntas freqüentes sobre o RMS: Administração
===============================================

Perguntas freqüentes sobre a administração do RMS
-------------------------------------------------

-   [Qual é a melhor maneira de revogar as permissões em documentos para um usuário que deixa a organização?](#bkmk_1)
-   [Ao estabelecer relacionamentos de confiança entre duas organizações para trocar conteúdo do RMS, o certificado de licença XrML passado para a empresa confiante precisa de algum tratamento especial?](#bkmk_2)
-   [Como o RMS funciona com perfis de usuários móveis?](#bkmk_3)
-   [Por que uma organização desejaria descomissionar o RMS?](#bkmk_4)
-   [Qual é o processo geral de descomissionamento?](#bkmk_5)
-   [É possível descomissionar um servidor RMS de modo que somente alguns usuários possam recuperar documentos?](#bkmk_6)
-   [O que significa a mensagem "Servidor não pode acessar o diretório de aplicativos"?](#bkmk_7)
-   [Posso usar rastreamento com o servidor RMS?](#bkmk_8)
-   [O que é defasagem horária e como eu devo administrá-la?](#bkmk_9)

<span id="BKMK_1"></span>
#### Qual é a melhor maneira de revogar as permissões em documentos para um usuário que deixa a organização?

De modo geral, é melhor ter documentos licenciados para grupos de usuários definidos no Active Directory em vez de contas de usuários individuais. Isso é recomendado com o intuito de que, quando o usuário deixar a organização, você possa removê-lo do grupo do Active Directory e o usuário não possa ler os documentos enviados para aquele grupo. No entanto, o usuário ainda poderá ler os documentos que possuírem licenças de uso, a menos que os direitos dos documentos estejam configurados para exigir que o usuário obtenha uma licença de uso sempre que o documento for aberto. Se esse direito não estiver definido, a única maneira de evitar que o usuário abra os documentos que possuem licenças de uso é apagar a licença de usuário armazenada no computador do usuário.

<span id="BKMK_2"></span>
#### Ao estabelecer relacionamentos de confiança entre duas organizações para trocar conteúdo do RMS, o certificado de licença XrML passado para a empresa confiante precisa de algum tratamento especial?

Ao estabelecer um domínio de usuário confiável ou um domínio de publicação confiável, você está optando por confiar em uma organização parceira para participar do RMS. Como tal, você está assumindo um risco calculado de que confiar em outra organização não comprometerá as suas informações. A prática recomendada é solicitar que a organização parceira envie o seu certificado de licenciante para servidor RMS usando um canal autenticado, como o email S/MIME, para ajudar a reduzir o risco de que o certificado de licenciante para servidor seja violado antes de ser importado para o servidor RMS.

<span id="BKMK_3"></span>
#### Como o RMS funciona com perfis de usuários móveis?

Os certificados de conta de direitos usados para identificar usuários são específicos de cada computador. Ao usar perfis móveis, o primeiro uso de RMS em um determinado computador criará um novo certificado de conta de direitos para o usuário naquele computador.

<span id="BKMK_4"></span>
#### Por que uma organização desejaria descomissionar o RMS?

O descomissionamento do RMS remove o servidor RMS da infra-estrutura e fornece uma maneira de os usuários salvarem, sem proteção, um conteúdo protegido por direitos. Existem três principais razões para as organizações optarem por fazer isso:

-   Simplificação do design de arquitetura, como, por exemplo, com a consolidação de servidores em um cluster.
-   Migração de um ambiente piloto de verificação de conceito para um ambiente de produção.
-   Mesclagem de servidores RMS, como ocorre após uma aquisição.

<span id="BKMK_5"></span>
#### Qual é o processo geral de descomissionamento?

O processo de descomissionamento é iniciado pelo cluster raiz do RMS com a habilitação do serviço de descomissionamento. Quando o serviço de descomissionamento é habilitado, todos os outros serviços (por exemplo, licenciamento e certificação) são desabilitados. Em seguida, cada aplicativo habilitado para RMS do usuário precisa ser direcionado para conectar-se ao serviço de descomissionamento quando é usado um recurso do RMS. O Microsoft Office 2003 é um exemplo de aplicativo habilitado para RMS. No Office 2003, o cliente do RMS é direcionado para os serviços RMS por meio de chaves de Registro. Uma chave de Registro específica identifica o serviço de descomissionamento. Uma vez configurada a chave para direcionar o cliente para o serviço de descomissionamento, o cluster do RMS concederá licenças de uso que fornecerão permissões completas (leitura, gravação, cópia, impressão, edição etc.) ao usuário do conteúdo, independentemente de o usuário ter essas permissões originalmente. Em seguida, os usuários devem ser direcionados a remover todas as proteções de direitos dos documentos que desejarem manter depois que o cluster do RMS for descomissionado completamente. Depois que isso for feito, o cluster do RMS poderá ser completamente removido de serviço.

Como prática recomendada, faça backup do banco de dados de configuração do cluster do RMS, para o caso de você precisar recuperar um documento protegido por direitos depois que o cluster tiver sido removido. Sem a chave particular do cluster raiz do RMS, somente o autor do documento poderá abrir o conteúdo protegido por direitos depois que o servidor for removido.

<span id="BKMK_6"></span>
#### É possível descomissionar um servidor RMS de modo que somente alguns usuários possam recuperar documentos?

Você pode utilizar uma ACL (lista de controle de acesso) para o serviço Web de descomissionamento (decommission.asmx) para controlar o acesso ao serviço de descomissionamento, de modo que somente determinados usuários possam obter a chave de descriptografia para o conteúdo protegido por direitos.

<span id="BKMK_7"></span>
#### O que significa a mensagem "Servidor não pode acessar o diretório de aplicativos"?

Essa mensagem de erro muitas vezes é exibida quando você tenta abrir o site de administração do RMS pela primeira vez após a instalação. Após recebê-la, você não poderá configurar ou administrar o RMS.

Esse erro geralmente ocorre quando os Serviços de Informações da Internet (IIS) estão sendo executados em modo de isolamento do IIS 5.0. Use o procedimento a seguir para desabilitar essa configuração no servidor e reiniciar o IIS para resolver esse problema.

**Desativar o modo de isolamento do IIS 5.0**
1.  Faça logon no servidor RMS como membro do grupo local Administradores.

2.  Clique em **Iniciar**, aponte para **Ferramentas Administrativas** e clique em **Gerenciador dos Serviços de Informações da Internet (IIS)**.

3.  No **Gerenciador do IIS**, expanda o computador local, clique com o botão direito do mouse em **Sites** e, em seguida, clique em **Propriedades**.

4.  Clique na guia **Serviço**, desmarque a caixa de seleção **Executar o serviço da WWW no modo de isolamento do IIS 5.0** e depois clique em **OK**.

5.  Essa alteração exige que o serviço IIS seja reiniciado. Quando for solicitado que você reinicie o serviço IIS, clique em **Sim**.

<span id="BKMK_8"></span>
#### Posso usar rastreamento com o servidor RMS?

Como o RMS foi criado usando-se o Microsoft® .NET Framework, você pode ativar o rastreamento para ajudar a controlar eventos do sistema e resolver problemas.

Você pode implementar o rastreamento se modificar o arquivo Web.config ou Machine.config. Quando você implementa o rastreamento no arquivo Machine.config, o rastreamento é executado em cada componente de software que está no computador; no entanto, se você implementar o rastreamento no arquivo Web.config, somente os eventos que ocorrerem nos serviços Web serão rastreados.

**Habilitar o rastreamento**
1.  Abra o arquivo Machine.config ou Web.config e adicione as seguintes linhas à seção &lt;system.diagnostics&gt; do arquivo:

    
        ```
2.  Reinicie o IIS executando IISRESET de um prompt de comando.

3.  Após coletar os dados necessários, remova as linhas do arquivo .config adicionadas na etapa 1.

4.  Reinicie o IIS executando IISRESET de um prompt de comando.

| ![](images/Cc747547.Important(WS.10).gif)Importante                                                                                                                                                                                                                                       |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Quando você usa rastreamento em um servidor RMS, podem ocorrer problemas de desempenho, como atrasos maiores nas aquisições de licenças de uso e na emissão de certificados de conta de direitos. Use o rastreamento somente em circunstâncias limitadas para ajudá-lo a diagnosticar e resolver problemas existentes. |

<span id="BKMK_9"></span>
#### O que é defasagem horária e como eu devo administrá-la?

A defasagem horária ocorre quando a hora do relógio em um computador é diferente da hora do relógio em outro computador. É tão comum quanto relógios de pulso de duas pessoas quaisquer em uma sala mostrarem horários ligeiramente diferentes. A defasagem horária pode causar problemas sempre que se especifica um horário de validade em uma licença.

O horário de validade de uma licença é definido de acordo com o relógio do editor. A defasagem desses horários pode causar problemas em dois locais no ciclo de publicação e consumo:

-   Quando um aplicativo tenta adquirir uma licença de uso utilizando uma licença de publicação com horário de validade que termina no passado ou inicia no futuro, de acordo com o horário do servidor RMS. Neste caso, a solicitação não terá êxito. Isso pode ocorrer quando um usuário final solicita uma licença de uso, ou quando um aplicativo está tentando obter uma licença prévia de um documento (para adquirir uma licença de uso em nome de um usuário).
-   Se o horário de validade da licença expirou (ou nem começou), a tentativa de usar a licença não terá êxito. Caso contrário, somente os direitos que já expiraram (ou que ainda não estão válidos) estarão indisponíveis.

Por exemplo, se o relógio do computador de publicação estiver 15 minutos atrasado em relação ao relógio do computador de consumo e o editor criar uma licença de publicação especificando que o conteúdo expirará em 15 minutos, o consumidor receberá do servidor uma licença de uso sem condição de uso, porque os direitos para visualizar o conteúdo, concedidos pela licença de uso, já terão expirado.

Não existe uma solução perfeita para problemas de defasagem horária. Uma boa solução é definir o início do horário de validade de um direito como anterior ao horário atual para consumidores com relógios atrasados em relação ao seu e, se possível, estender o horário de validade da licença para usuários com relógios adiantados. É recomendado que você esteja ciente do impacto de problemas referentes à defasagem horária, especialmente ao criar licenças com horários de validade curtos.
