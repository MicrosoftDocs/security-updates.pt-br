---
TOCTitle: Monitorando o Enfileiramento de mensagens
Title: Monitorando o Enfileiramento de mensagens
ms:assetid: 'a7109399-3a84-4681-874b-f6ea1646b0a0'
ms:contentKeyID: 18123802
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747716(v=WS.10)'
---

Monitorando o Enfileiramento de mensagens
=========================================

O registro do RMS usa o Enfileiramento de mensagens (conhecido também como MSMQ) para enviar eventos para o banco de dados de registro. Cada servidor front-end do RMS envia mensagens para o serviço Enfileiramento de mensagens, e o serviço ouvinte de registro em cada servidor front-end recupera mensagens de registro da fila de Enfileiramento de mensagens e grava-as no banco de dados de registro. Se o banco de dados de registro ou o servidor do banco de dados se tornar indisponível ou se o serviço ouvinte de registro for interrompido, o Enfileiramento de mensagens armazenará as mensagens na fila. Se você estiver planejando desligar o banco de dados de registro ou o servidor do banco de dados, é recomendável primeiro desligar o serviço ouvinte de registro em cada servidor front-end e, em seguida, reiniciar o serviço ouvinte de registro em cada servidor front-end, depois de reiniciar o banco de dados ou o servidor de banco de dados.

Se o banco de dados falhar e o serviço ouvinte de registro ainda estiver em execução, o serviço ouvinte de registro não poderá gravar mensagens de registro no banco de dados. O serviço ouvinte de log moverá as mensagens para uma fila de Enfileiramento de mensagens de "cartas devolvidas" até que o banco de dados esteja disponível, quando novas mensagens de log serão gravadas no banco de dados. As mensagens na fila de cartas devolvidas não serão gravadas automaticamente no banco de dados de registro. Para exibir e excluir as mensagens na fila de cartas devolvidas, use as seguintes etapas:

1.  Abra o snap-in Console de Gerenciamento Microsoft. Para abri-lo, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Ferramentas Administrativas** e clique em **Gerenciamento do Computador**.
2.  Em Serviços e Aplicativos na árvore do console, clique em Enfileiramento de Mensagens e, em seguida, em Filas Particulares.
3.  Duas filas estarão visíveis. As duas terão um nome iniciado com "**drms\_logging**" seguido pelo nome do cluster. Uma das filas terá o nome de "**drms\_logging\_***&lt;nome do cluster&gt;***\_deadletter**". Essa é a fila de cartas devolvidas. Clique no nome da fila e clique na fila Mensagens da fila.
4.  Clique duas vezes em cada mensagem para exibir suas propriedades.
5.  Para excluir a fila, clique com o botão direito do mouse na fila **Mensagens da fila**, selecione **Todas as Tarefas** e clique em **Limpar**.

Na configuração padrão, o Enfileiramento de mensagens armazenará todas as mensagens enfileiradas até o limite do espaço livre de armazenamento disponível no servidor. Se o Enfileiramento de mensagens usar todo o espaço disponível no disco rígido, o servidor RMS não poderá atender a solicitações de serviço dos clientes. Para evitar isso, use as seguintes etapas para limitar a quantidade de espaço em disco que o Enfileiramento de mensagens pode usar para enfileiramento:

1.  Abra o snap-in Console de Gerenciamento Microsoft. Para abri-lo, clique em Iniciar, aponte para Todos os Programas, aponte para Ferramentas Administrativas e clique em Gerenciamento do Computador.
2.  Em Serviços e Aplicativos na árvore do console, clique em Enfileiramento de Mensagens e, em seguida, em Filas Particulares.
3.  Duas filas estarão visíveis. As duas terão um nome iniciado com "drms\_logging." Execute as seguintes etapas em cada fila:
    -   Clique em Propriedades.
    -   Marque a caixa de seleção Limitar o armazenamento de mensagens a (KB) e digite o tamanho total, em quilobytes, de todas as mensagens que podem ser armazenadas na fila.

Se a fila ficar cheia, as mensagens do RMS serão descartadas quando chegarem e a seguinte mensagem de evento associada à Identificação do evento 48 será enviada para o log de Eventos do Sistema:

"Falha no envio do Conjunto de Propriedades para o Enfileiramento de Mensagens."

É recomendável configurar as ferramentas de monitoração do sistema para alertá-lo da ocorrência desse evento porque ele indica que há um problema no banco de dados de registro.
