---
TOCTitle: Questões de administração do RMS
Title: Questões de administração do RMS
ms:assetid: '97013c08-d3fa-4ea0-8914-995b6c97f900'
ms:contentKeyID: 18123705
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747605(v=WS.10)'
---

Questões de administração do RMS
================================

Após a configuração bem-sucedida do RMS no servidor, poderão surgir questões na sua administração cotidiana. Você pode usar as informações que se encontram nas seções a seguir para resolver algumas dessas questões.

Mensagem "SQL Server não existe ou acesso negado" recebida ao tentar abrir o site Administração do RMS
------------------------------------------------------------------------------------------------------

Se você instalou o RMS usando uma nova instalação do SQL Server 2005 como servidor de banco de dados, é possível que o serviço SQL Server não tenha sido iniciado. No SQL Server 2005, o serviço MSSQLSERVER não está configurado para ser iniciado automaticamente junto com o servidor. Se você reiniciou o SQL Server após a instalação do RMS mas não configurou esse serviço para ser reiniciado automaticamente, o RMS não funcionará, e apenas a página Administração Global do RMS poderá ser acessada.

Após iniciar o serviço MSSQLSERVER, você deve reiniciar o IIS no servidor RMS para restaurar a funcionalidade do RMS.

Não foi possível concluir o processo de registro offline
--------------------------------------------------------

Se o arquivo de solicitação de registro estiver incompleto ou for modificado antes de ser enviado ao site do serviço de registro, você não poderá completar o registro offline. O arquivo de solicitação de registro pode ter sido corrompido por um programa malicioso ou por um erro do usuário ou do sistema.

Dependendo do tipo de informação que estiver faltando, o site do serviço de registro ainda poderia aceitar o arquivo e retornar um certificado de licenciante para servidor ou poderia recusar a aceitação do arquivo de solicitação e apresentar um erro.

Se for retornado um certificado de licenciante para servidor, ele refletirá as omissões e a corrupção presentes no arquivo de solicitação de registro, e o RMS apresentará um erro quando você tentar importar o certificado.

Se você não conseguir concluir o processo de registro, verifique se o computador conectado à Internet está livre de vírus, exporte novamente o arquivo de solicitação de registro do seu servidor RMS e depois use mídias diferentes para transportá-lo para o computador conectado à Internet. Se o erro se repetir, você deve contatar o Atendimento Microsoft.

Os arquivos de log não são criados
----------------------------------

O serviço de log do RMS exige o serviço de Enfileiramento de Mensagens (também conhecido como MSMQ) e o acesso ao banco de dados de log. Se os arquivos de log não estão sendo criados, isso poderia significar que os componentes não foram configurados corretamente ou que a comunicação entre os componentes está sendo interrompida.

Faça um teste para assegurar que o servidor RMS e o servidor do banco de dados possuem conectividade com a rede. Caso possuam, use os procedimentos a seguir para verificar os pré-requisitos do serviço de log do RMS e assegure que todas as dependências do software foram configuradas corretamente.

Primeiro, verifique se a configuração do Enfileiramento de Mensagens está correta. O Enfileiramento de Mensagens deve ser instalado com a opção Integração com o Active Directory habilitada.

**Para verificar se o Enfileiramento de Mensagens foi instalado e configurado corretamente**
1.  No **Painel de Controle**, clique em **Adicionar ou Remover Programas** e depois clique em **Adicionar/Remover Componentes do Windows** para abrir o **Assistente de Componentes do Windows**.

2.  No **Assistente de Componentes do Windows**, marque a caixa de seleção **Servidor de Aplicativos** e depois clique em **Detalhes**.

3.  Marque a caixa de seleção **Enfileiramento de Mensagens** e depois clique em **Detalhes**.

4.  Se a caixa de seleção **Integração com o Active Directory** estiver marcada, passe para o próximo teste e verifique se o Enfileiramento de Mensagens está em execução. Se a caixa de seleção não estiver marcada, continue executando as etapas 5 a 9.

5.  Clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS** para abrir a página Administração Global.

6.  Próximo ao site em que o RMS está configurado, clique em **Remover o RMS deste site** e clique em **OK**.

7.  Em **Adicionar ou Remover Programas** no **Painel de Controle**, clique em **Adicionar/Remover Componentes do Windows**, clique em **Servidor de Aplicativos** e, em seguida, clique em **Serviço de Enfileiramento de Mensagens**.

8.  Para habilitar a **Integração com o Active Directory**, clique em **Detalhes**, marque a caixa de seleção **Integração com o Active Directory** e depois clique em **OK**.

9.  Abra a **página Administração Globa**l. Próximo ao nome do site em que deseja configurar o RMS, clique em **Configurar o RMS neste site**.

Depois, verifique se o Enfileiramento de Mensagens está em execução no seu servidor.

**Para verificar se o Enfileiramento de Mensagens está em execução no seu servidor**
1.  No **Painel de Controle**, clique em **Ferramentas Administrativas** e depois clique em **Serviços**.

2.  Role a lista de serviços para baixo até encontrar o serviço **Enfileiramento de Mensagens**.

3.  Na coluna **Status**, o serviço deve estar indicado como **Iniciado**; caso não esteja, clique com o botão direito do mouse no serviço e depois clique em **Iniciar**.

A seguir, verifique se o serviço de log possui permissão para gravar eventos no banco de dados de log. O serviço de log do RMS é executado com o uso da conta de serviço RMS. Verifique se a conta de serviço RMS possui um logon válido no servidor do banco de dados e se lhe foram concedidas as permissões necessárias para que possa criar bancos de dados e gravar informações em arquivos.

Uma vez atendidos todos esses pré-requisitos, pare e reinicie o serviço de log do RMS, usando o snap-in Serviços. Após o reinício do serviço de log do RMS, os arquivos de log devem ser criados no servidor do banco de dados. Se você estiver usando o SQL Server como servidor do banco de dados, o procedimento a seguir mostra como verificar se os arquivos de log estão sendo criados.

**Para verificar se os arquivos de log estão sendo criados no SQL Server**
1.  No SQL Server Enterprise Manager, vá ao banco de dados de log, expanda **Bancos de Dados** e, em seguida, expanda o banco de dados que contém o banco de dados de log do RMS.

2.  Clique no banco de dados de log, clique em **Tabelas**, clique com o botão direito em **DRMS\_log\_master** e, em seguida, clique em **Abrir tabela - retornar todas as linhas**. Se os arquivos de log estiverem sendo criados, você verá um ou mais arquivos de log.

Restaurando o banco de dados de configuração
--------------------------------------------

O RMS não pode operar sem ter um banco de dados de configuração em funcionamento. Se você tiver problemas com o banco de dados de configuração, como corrupção do banco de dados ou falha no disco rígido do servidor do banco de dados, será possível restaurar a funcionalidade do RMS ao restaurar um backup do banco de dados de configuração. Para restaurar o banco de dados de configuração do RMS a partir de um backup, você precisa ter as seguintes informações:

-   O nome do backup mais recente do banco de dados.
-   O nome do computador no qual o banco de dados de backup será restaurado.
-   O nome da conta e a senha usados originalmente para configurar o RMS.
-   A senha especificada originalmente para proteção da chave particular do software (se tiver sido usada).

A restauração a partir de um banco de dados de backup não requer um novo certificado de licenciante para servidor nem uma nova chave particular porque o RMS retém todas as configurações (que obtém do banco de dados de configuração de backup).

Você pode restaurar um banco de dados de backup usando o procedimento apresentado a seguir.

**Para restaurar um banco de dados de backup**
1.  Clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS** para abrir a página **Administração Global**.

2.  Próximo ao site em que o RMS está configurado, clique em **Remover o RMS deste site** e clique em **OK**.

3.  Restaure os arquivos do banco de dados de backup para o banco de dados de configuração. Se você fez o backup do banco de dados de log durante o procedimento de backup e deseja manter a continuidade dos dados, restaure também o banco de dados de log.

    -   Se esse sistema estiver sendo restaurado após uma falha total, restaure o Registro usando o backup do estado do sistema antes de restaurar os arquivos do banco de dados de backup.

4.  Se o banco de dados em fase de restauração for para um único servidor raiz de certificação, modifique a seguinte chave do Registro antes de tentar reconfigurar o serviço:

    -   Em computadores que executam a versão de 32 bits do Windows Server 2003
        ```
        HKEY_LOCAL_MACHINE\Software\Microsoft\DRMS\1.0\
        ```
    -   Em computadores que executam a versão de 64 bits do Windows Server 2003
        ```
        HKEY_LOCAL_MACHINE\Software\WOW6432Node\Microsoft\DRMS\1.0\
        ```

    Adicione a seguinte entrada como um valor de seqüência e deixe o valor em branco:

    ```
    GicURL
    ```

    Isto substitui a descoberta do Active Directory do servidor raiz de certificação e permite que você obtenha acesso às páginas de configuração do servidor raiz de certificação.

5.  Se você usou um módulo de segurança de hardware para proteger a chave particular do RMS, restaure o mundo de segurança de backup, de modo que as chaves possam ser recuperadas.

6.  Siga uma destas etapas:

    -   Para restaurar o banco de dados para um único servidor, e não para um cluster, clique em Configurar o RMS neste site ao lado do site onde deseja configurar o RMS.  
        
        -ou-

    -   Para restaurar o banco de dados para um cluster, clique em Adicionar este servidor a um cluster ao lado do site em que deseja configurar o RMS.

7.  Especifique a conta do serviço RMS que foi usada para configurar o servidor originalmente.

8.  Especifique o banco de dados de configuração de backup (incluindo o nome do banco de dados e o nome do computador onde o banco de dados reside) que deseja usar.

9.  Especifique a mesma senha usada para configurar o servidor originalmente.

10. Clique em **Enviar**.

O processo de configuração terá início, e o RMS será reconfigurado no servidor.

Para obter mais informações, consulte Planejamento da recuperação do sistema e Fazendo backup e restaurando o sistema para o RMS em Planejando uma implantação do RMS desta coleção de documentos.

Senha expirada da conta do serviço RMS
--------------------------------------

Se o RMS parar de funcionar, é possível que a senha da conta do serviço RMS tenha expirado. Verifique no Gerenciador do IIS. Se os pools de aplicativos do RMS não estiverem funcionando e você não conseguir reiniciá-los, é possível que a senha da conta do serviço RMS tenha expirado.

Se a senha da conta de serviço RMS expirar, você deve alterá-la em cada servidor RMS que estiver usando a conta com a senha expirada e depois reiniciar o IIS. Para obter mais informações, consulte "Alterando a senha da conta do serviço RMS" em "Operando um servidor RMS", nesta coleção de documentos.

Restaurando uma instalação anterior do RMS
------------------------------------------

Se ocorrer uma falha no hardware ou no software do servidor RMS, você poderá restaurar um servidor RMS usando um banco de dados de configuração previamente instalado para configurar uma nova instância do servidor.

> [!Note]  
> Esse procedimento só poderá ser utilizado se ocorrer uma falha no servidor que está executando o RMS. Se ocorrer uma falha no servidor que está executando o banco de dados de configuração, consulte "Restaurando o banco de dados de configuração". Se o servidor RMS também for o servidor do banco de dados, será necessário restaurar o servidor inteiro a partir de uma cópia de backup. 

Utilize o procedimento a seguir para apontar para o mesmo banco de dados de configuração usado para a instalação original.

**Para restaurar uma instalação anterior do RMS**
1.  Faça logon no computador que deseja configurar como servidor RMS, usando uma conta com privilégios de administrador. Certifique-se de que esse computador atende aos requisitos do sistema mínimos para o RMS. Para obter mais informações sobre os requisitos do sistema para o RMS, consulte "Requisitos de hardware" para o RMS em "Planejando uma implantação do RMS", nesta coleção de documentos.

2.  Se você estiver usando um módulo de segurança de hardware para proteger as chaves particulares do RMS, certifique-se de que ele está configurado corretamente, usando a mesma configuração e o mesmo mundo de segurança da instalação anterior do RMS.

3.  Instale o RMS no computador.

4.  Após concluir a instalação do RMS, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e depois clique em **Administração do Windows RMS** para abrir a página **Administração Global**.

5.  Próximo ao site em que deseja configurar o RMS, clique em **Adicionar este servidor a um cluster**.

6.  Na área **Conta de serviço RMS**, digite o nome da conta de serviço RMS, na forma nome\_domínio\\nome\_usuário, e a senha da conta de serviço RMS sob as quais o RMS será executado na maioria das operações de rotina. Ela deve ser uma conta do domínio.

7.  Na área **Banco de dados de configuração**, especifique o nome do servidor de banco de dados e o nome do banco de dados de configuração da instalação original do RMS que você deseja recuperar.

8.  Na área **Proteção de chave particular**, selecione o mecanismo utilizado por esse cluster para proteger a chave particular. Se tiver usado proteção de chave particular baseada em software, será necessário fornecer a senha usada para criptografar a chave particular quando esse cluster foi configurado originalmente.

9.  Clique em **Enviar**.

Os clientes não podem abrir um conteúdo protegido pelo RMS porque as permissões expiraram
-----------------------------------------------------------------------------------------

Se as permissões de um usuário expiraram, ele não poderá consumir o conteúdo protegido pelo RMS. Se o relógio do sistema do servidor RMS estiver adiantado em relação ao relógio do sistema do cliente do RMS, é possível que um usuário não possa consumir o conteúdo protegido pelo RMS, apesar de as permissões ainda não terem expirado. Se os relógios do sistema dos dois computadores não estiverem sincronizados, é possível que ocorra o seguinte erro quando o computador cliente tentar abrir o conteúdo:

**Você não tem permissão para abrir esta mensagem porque a sua permissão expirou. Deseja abri-la usando um outro conjunto de credenciais?**

Tanto a licença de cliente quanto a licença de conteúdo são válidas, mas a diferença no horário faz com que o cliente interprete a licença de conteúdo como inválida e devolve esse erro para o usuário. Isto pode fazer com que o usuário acredite que tem problemas com o certificado de conta do RMS ou com os direitos concedidos ao documento. Quando o relógio do cliente alcançar o prazo de validade da licença de publicação do conteúdo, o usuário conseguirá abrir o conteúdo.

Como prática recomendada, você deve sincronizar os clientes e os servidores do sistema RMS com o mesmo serviço de tempo.

Erro de "Acesso negado" quando o RMS tenta registrar eventos no log de eventos do aplicativo
--------------------------------------------------------------------------------------------

Por padrão, componentes como o RMS, executados em uma página ASP, são criados na conta IUSR\_NOMECOMPUTADOR. Essa conta é membro do grupo Convidados, e os privilégios de segurança necessários para gravar no log de eventos do aplicativo impedem que as contas de convidados gravem dados no log de eventos.

Para contornar esse problema, você pode usar o Editor do Registro para modificar a chave do Registro que controla esse comportamento.

> [!Caution]  
> Editar o Registro incorretamente pode causar sérios danos ao sistema. Antes de alterar o Registro, faça backup dos dados importantes que estão no computador. 

Defina a seguinte chave do Registro com 0 em vez de 1 e depois reinicie o computador para que as alterações entrem em vigor:

```
HKEY_LOCAL_MACHINE\System\CurrentControlSet\Services\EventLog\Application
```

Nome: `RestrictGuestAccess`

Tipo: `REG_DWORD`

> [!Note]  
> Isso permite que todas as contas de convidados gravem no log de eventos do aplicativo. 

Para obter mais informações sobre o motivo desse erro, leia o artigo sobre a permissão de log em páginas ASP, na [Microsoft Knowledge Base](http://go.microsoft.com/fwlink/?linkid=44167).
