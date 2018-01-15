---
TOCTitle: Editar um modelo de diretiva de direitos
Title: Editar um modelo de diretiva de direitos
ms:assetid: '9580b934-bd6f-4097-9d3c-4fc14a3147fa'
ms:contentKeyID: 18123773
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747684(v=WS.10)'
---

Editar um modelo de diretiva de direitos
========================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Editando um modelo de diretiva de direitos
------------------------------------------

#### Editar um modelo de diretiva de direitos

1.  Abra a página **Administração Global** e, próximo ao site em que deseja editar o modelo de diretiva de direitos, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Modelos de diretiva de direitos**.

3.  Em **Nome do modelo**, clique no nome do modelo a editar.

4.  Na área **Identificação do modelo**, modifique as informações nas áreas **Nome do modelo**, **Descrição do modelo** e **URL de solicitação de direitos**, conforme apropriado.

5.  Na área **Usuários e grupos**, efetue uma ou mais entre as seguintes opções:

    -   Para adicionar um usuário ou grupo, em **Adicionar usuários ou grupos**, digite o endereço de email válido de um usuário ou grupo específico a adicionar, clique em **Adicionar** e selecione o nome em **Usuários ou grupos atuais**. Na área **Direitos**, selecione todos os direitos a serem concedidos ao usuário ou grupo selecionado.
    -   Para modificar os direitos de um usuário ou grupo existente, selecione o nome em **Usuários ou grupos atuais** e selecione ou desmarque as caixas de seleção de direitos, conforme apropriado.
    -   Para remover um usuário ou grupo, selecione o nome em **Usuários ou grupos atuais** e clique em **Remover**.

6.  Na área **Diretiva de vencimento**, edite as informações a serem alteradas quando as licenças do conteúdo vencerem e quando elas devem ser renovadas, conforme apropriado.

7.  Na área **Diretiva estendida**, edite as informações para alterar como as licenças de conteúdo devem ser implementadas, incluindo a persistência dos direitos autorais, se navegadores confiáveis são suportados, a persistência da licença no conteúdo e a aplicação de qualquer dado específico do aplicativo, conforme apropriado.

8.  Na área **Diretiva de revogação**, selecione se a lista de revogação deve ser solicitada para o conteúdo que é criado utilizando esse modelo. Se você selecionar **Solicitar revogação**, especifique as seguintes configurações, conforme apropriado:

    -   Em **URL**, digite a URL para onde o arquivo da lista de revogação é postado. Se precisar suportar usuários desconectados ou externos, essa URL deve ser acessível da rede corporativa e da Internet. Para obter mais informações, consulte "[Implementando a revogação](https://technet.microsoft.com/4735f060-7197-4ae2-830a-f91bcc4de30a)", já mencionado neste tema.
    -   Em **Intervalo de atualização da lista de revogação**, digite o número de dias em que a lista de revogação se mantém válida. Se um usuário possui uma cópia da lista de revogação mais antiga do que esse valor, ele deve obter uma lista de revogação atualizada para consumir o conteúdo.
    -   Em **Arquivo de chave pública**, digite o caminho e o nome do arquivo da chave pública para a lista de revogação. Para obter mais informações sobre esse arquivo, consulte "Inserindo uma assinatura em uma lista de revogação", já mencionado neste tema.

    | ![](images/Cc747684.Caution(WS.10).gif)Cuidado                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
    |----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | Cuidado ao implementar a revogação. Baseado no intervalo de atualização especificado, é preciso renovar uma lista de revogação periodicamente ou ela irá expirar, impedindo que os usuários consumam o conteúdo que requer essa lista. Para se assegurar de não impedir inadvertidamente os usuários de consumirem o conteúdo, avalie cuidadosamente o intervalo que você requer para atualizar a lista de revogação. Para obter mais informações, consulte "[Gerenciando a revogação](https://technet.microsoft.com/df732a7d-1fb0-4845-87ca-fab4bc5f98a0)", já mencionado neste tema. |

9.  Clique em **Enviar**.

Para obter mais informações sobre como desempenhar esse procedimento, consulte "[Criando e modificando modelos de diretiva de direitos](https://technet.microsoft.com/6014176f-ef71-4d29-b3e3-da129c18563d)", já mencionado neste tema.
