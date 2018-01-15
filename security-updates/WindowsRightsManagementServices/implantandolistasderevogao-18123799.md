---
TOCTitle: Implantando listas de revogação
Title: Implantando listas de revogação
ms:assetid: 'e331338b-66d4-45e4-8d3f-acccf2302ac4'
ms:contentKeyID: 18123799
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747702(v=WS.10)'
---

Implantando listas de revogação
===============================

Para implementar revogação, você deve implantar listas de revogação. Listas de revogação especificam o conteúdo, os aplicativos, os usuários ou outras entidades que foram revogadas. Você pode implantar listas de revogação organizacionais e listas de revogação da Microsoft.

Implantando listas de revogação organizacionais
-----------------------------------------------

Para usar um modelo de diretiva de direitos com uma lista de revogação, é necessário disponibilizar a lista de revogação a computadores clientes que estão na organização. Para obter informações sobre a criação de listas de revogação, consulte "Implementando a revogação", já mencionado neste tema.

Você pode implantar uma lista de revogação organizacional executando as seguintes etapas:

1.  Copie o arquivo de lista de revogação em um servidor Web acessível publicamente. Como os usuários podem consumir o conteúdo protegido fora da organização, o local especificado deve ser acessível por todos os usuários, tanto de dentro como de fora da rede.
    A distribuição do arquivo da lista de revogação a computadores clientes pode demorar algum tempo. Isso cria a possibilidade de um arquivo de lista de revogação não estar disponível no computador dos usuários quando eles tentarem abrir um documento que exija uma lista de revogação. Se a lista de revogação não estiver no computador cliente, o aplicativo habilitado para RMS poderá baixá-la do local especificado na licença de uso.
    Idealmente, você deve criar um script que assine e copie automaticamente a lista de revogação no site diariamente. Isso ajuda a garantir que os usuários não sejam impedidos de consumir conteúdo por possuírem uma lista de revogação desatualizada. Para obter uma amostra de script, consulte a seção "Usando a ferramenta Assinatura de Lista de Revogação", já mencionado neste tema.
2.  No modelo de diretiva de direitos, especifique um intervalo de atualização que seja maior que zero para a lista de revogação organizacional. Isso garante que a lista de revogação não seja opcional. Se a lista de revogação for atualizada com pouca freqüência, como somente no caso de uma violação de segurança, você poderá definir a condição de atualização para um intervalo longo e, dependendo de seu script ou configurações de diretiva, colocar a lista de revogação nos computadores clientes quando necessário. Para obter informações sobre como definir intervalos de atualização, consulte a seção "Definindo diretivas de revogação", já mencionada neste tema. Para obter mais informações sobre como configurar modelos de diretiva de direitos, consulte a seção "Criando e modificando modelos de diretiva de direitos", mais adiante neste tema.
3.  No modelo de diretiva de direitos, especifique a URL na qual a lista de revogação estará disponível.
4.  Opcionalmente, implante a lista de revogação em computadores clientes usando um método automatizado, como Diretiva de Grupo ou o SMS (Systems Management Server).

Implantando listas de revogação da Microsoft
--------------------------------------------

Para que o componente cliente do RMS use uma lista de revogação da Microsoft, você deve implantar a lista nos computadores clientes. Este tópico descreve como implantar uma lista de revogação da Microsoft nos seguintes cenários:

-   Sua organização deseja implantar sua própria lista de revogação e a lista de revogação da Microsoft.
-   Sua organização deseja implantar somente a lista de revogação da Microsoft.

Quando a Microsoft publica uma lista de revogação, pode-se baixá-la de:

-   Servidores RMS poderão baixar a lista de revogação usando o Windows Update.
-   Como alternativa, a lista de revogação da Microsoft também estará disponível para download no Microsoft Download Center, se seu servidor RMS não estiver conectado à Internet.

Se você baixar o pacote de lista de revogação em um servidor RMS, o pacote será salvo na pasta %systemdrive%\\Arquivos de Programas\\Lista de Revogação de Serviços do Windows Rights Management. Se você estiver baixando o pacote de lista de revogação para outro tipo de computador, poderá selecionar o local do download. O pacote contém um arquivo executável, CRL\_Update.exe, que pode ser executado para instalar todas as listas de revogação de cliente no armazenamento de licenças de cliente e também um arquivo de lista de revogação, Msrl.xml, que você pode copiar em um site ou em uma pasta compartilhada pública.

**Para implantar a lista de revogação da sua organização e a lista de revogação da Microsoft**
1.  Para implantar a lista de revogação da sua organização, siga as instruções da seção "[Implantando listas de revogação](https://technet.microsoft.com/e331338b-66d4-45e4-8d3f-acccf2302ac4)", já mencionada neste tema.

2.  Baixe o pacote de lista de revogação da Microsoft e implante-o em todos os computadores clientes da organização, usando um método como Diretiva de Grupo ou SMS (Systems Management Server ). Como alternativa, você pode copiar entradas da lista de revogação Microsoft na lista de revogação organizacional e implantar somente a lista de revogação organizacional.

| ![](images/Cc747702.Caution(WS.10).gif)Cuidado                                                                                                                                                                                                                                                                                                                                                                            |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A Microsoft é uma entidade na cadeia de confiança de todos os certificados e licenças que são emitidos pelo RMS. Portanto, uma lista de revogação emitida pela Microsoft tem efeito para todas as solicitações de vinculação para as quais a licença de uso seja obtida com base em um modelo de diretiva de direitos que exija a lista de revogação organizacional. Além disso, a lista de revogação da Microsoft é registrada no computador cliente. |

**Para implantar somente uma lista de revogação da Microsoft**
1.  Baixe a lista de revogação da Microsoft.

2.  Modifique todos os modelos de diretiva de direitos existentes para que exijam revogação ou, se não existir nenhum modelo de diretiva de direitos, crie um que exija revogação. Use a chave pública da Microsoft quando especificar a condição de revogação.

3.  Defina o intervalo de atualização como um número alto, como 50.000. Esse número alto garante que a lista de revogação publicada pela Microsoft nunca expire. Portanto, as licenças de uso distribuídas não requerem uma nova versão da lista de revogação da Microsoft quando uma não estiver disponível.

4.  Copie o arquivo de lista de revogação em um servidor Web acessível publicamente. Como os usuários podem consumir o conteúdo protegido fora da organização, o local especificado deve ser acessível por todos os usuários, tanto de dentro como de fora da rede.

5.  Você deve disponibilizar a lista de revogação porque distribuí-la para os computadores clientes pode demorar algum tempo. Por isso, é possível que a lista de revogação não esteja disponível localmente no computador dos usuários quando eles tentarem abrir um documento que exija uma lista de revogação. Se a lista de revogação não estiver no computador cliente, o aplicativo habilitado para RMS poderá baixá-la do local especificado.

6.  No modelo de diretiva de direitos, especifique a URL na qual a lista de revogação estará disponível. Para obter mais informações sobre como configurar modelos de diretiva de direitos, consulte a seção "[Criando e modificando modelos de diretiva de direitos](https://technet.microsoft.com/6014176f-ef71-4d29-b3e3-da129c18563d)", mais adiante neste tema.

7.  Opcionalmente, implante o pacote de lista de revogação em computadores clientes usando um método, como Diretiva de Grupo ou o SMS. Em seguida, os usuários podem abrir o conteúdo protegido pelo RMS que exige listas de revogação, mesmo quando não estiverem conectados à rede.
