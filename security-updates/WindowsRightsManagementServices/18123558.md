---
TOCTitle: Adicionar um modelo de diretiva de direitos
Title: Adicionar um modelo de diretiva de direitos
ms:assetid: '1a5555cd-6d39-4078-a879-4106864674be'
ms:contentKeyID: 18123558
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720206(v=WS.10)'
---

Adicionar um modelo de diretiva de direitos
===========================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Adicionando um modelo de diretiva de direitos
---------------------------------------------

#### Adicionar um modelo de diretiva de direitos

1.  Abra a página **Administração Global** e, próximo ao site em que deseja adicionar um modelo de diretiva de direitos, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Modelos de diretiva de direitos**.

3.  Em **Idioma**, clique no idioma que deseja selecionar para utilização no modelo.

4.  Clique em **Adicionar um modelo de diretiva de direitos**.

5.  Na área **Identificação de modelo**, especifique um nome, descrição e URL de solicitação de direitos para o modelo.

6.  Na área **Usuários e grupos**, em **Adicionar usuários ou grupos**, digite o endereço de email válido de um usuário ou grupo a adicionar, depois clique em **Adicionar**. Repita para adicionar usuários ou grupos, se necessário.

7.  Em **Usuários ou grupos atuais**, selecione o endereço de email de um usuário ou grupo ao qual atribuir direitos.

8.  Selecione as caixas de seleção de todos os direitos a serem concedidos ao usuário ou grupo selecionado. Repita para conceder direitos aos usuários e grupos restantes.

9.  Na área **Diretiva de vencimento**, selecione uma entre as três opções de vencimento e especifique uma data ou hora de vencimento, conforme apropriado. Se apropriado, selecione **As licenças de uso de conteúdo devem ser renovadas a cada** e especifique o número de dias entre as renovações.

10. Na área **Diretiva estendida**, selecione uma ou mais entre as quatro opções. Se você selecionar **Aplicar dados específicos do aplicativo**, especifique um nome e valor para os dados a serem aplicados e clique em **Adicionar**.

11. Para implementar a revogação, na área **Diretiva de revogação** marque a caixa de seleção **Solicitar revogação** e siga estas etapas:

    1.  Em **URL ou UNC**, digite a URL para onde o arquivo da lista de revogação é postado. Se precisar suportar usuários desconectados ou externos, essa URL deve ser acessível da rede corporativa e da Internet.
    2.  Em **Intervalo de atualização da lista de revogação**, digite o número de dias em que a lista de revogação se mantém válida. Se um usuário possui uma cópia da lista de revogação mais antiga do que esse valor, ele deve obter uma lista de revogação atualizada para consumir o conteúdo.
    3.  Em **Arquivo de chave pública**, digite o caminho e o nome do arquivo ou clique em **Procurar** para localizar o arquivo de chave pública para a lista de revogação. Para obter mais informações sobre esse arquivo, consulte "Inserindo uma assinatura em uma lista de revogação", já mencionado neste tema.

    > [!Caution]  
    > Cuidado ao implementar a revogação. Baseado no intervalo de atualização especificado, é preciso renovar uma lista de revogação periodicamente ou ela irá expirar, impedindo que os usuários consumam o conteúdo que requer essa lista. Para se assegurar de não impedir inadvertidamente os usuários de consumirem o conteúdo, avalie cuidadosamente o intervalo que você requer para atualizar a lista de revogação. Para obter mais informações, consulte "[Gerenciando a revogação](https://technet.microsoft.com/df732a7d-1fb0-4845-87ca-fab4bc5f98a0)", já mencionado neste tema. 

12. Clique em **Enviar**.

Para obter mais informações sobre revogação, consulte "[Gerenciando a revogação](https://technet.microsoft.com/df732a7d-1fb0-4845-87ca-fab4bc5f98a0)", já mencionado neste tema.

Para obter considerações sobre a especificação das opções de revogação, consulte "[Definindo diretivas de revogação](https://technet.microsoft.com/e2fffe9f-def7-439b-a8aa-43f8a065813d)", já mencionado neste tema.

Para obter mais informações sobre como desempenhar esse procedimento, consulte "[Criando e modificando modelos de diretiva de direitos](https://technet.microsoft.com/6014176f-ef71-4d29-b3e3-da129c18563d)", já mencionado neste tema.
