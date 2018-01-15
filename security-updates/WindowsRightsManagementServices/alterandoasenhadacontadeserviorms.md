---
TOCTitle: Alterando a senha da conta de serviço RMS
Title: Alterando a senha da conta de serviço RMS
ms:assetid: '435c9cef-b622-48b3-9d4d-4bf5cac7d52d'
ms:contentKeyID: 18123646
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720273(v=WS.10)'
---

Alterando a senha da conta de serviço RMS
=========================================

Dependendo da diretiva de senha especificada para os servidores RMS, a senha da conta de serviço RMS poderá expirar periodicamente. Se a senha expirar, o RMS pára de funcionar. Portanto, você deve alterar a senha antes que expire.

**Usando uma conta de serviço RMS**

Quando você está usando uma conta de serviço RMS, pode alterar a senha em cada servidor RMS da seguinte maneira:

1.  Se o servidor estiver em um cluster, retire o servidor da rotação.
2.  Faça logon no servidor usando as credenciais da conta de serviço RMS.
3.  Altere a senha da conta de serviço RMS.
    Ocorrerá uma interrupção no serviço dos outros servidores que usam a mesma conta de serviço RMS porque as credenciais armazenadas por eles se tornarão inválidas depois que a senha for alterada.
4.  Faça logoff do servidor.
5.  Faça logon novamente no servidor usando credenciais de administrador do RMS.
6.  Para reconfigurar a identidade do usuário no servidor, na página **Administração Global**, clique em **Alterar a conta de serviço RMS** e, na página **Alterar a conta de serviço RMS**, especifique o domínio, o nome do usuário e a senha.
7.  Reinicie o IIS.
8.  Se for o caso, coloque o servidor novamente na rotação.
9.  Repita as etapas 6 a 8 para cada um dos servidores do cluster.

Essa é a abordagem mais simples para alterar a senha da conta de serviço RMS; entretanto, pode provocar um certo tempo de inatividade do RMS, porque o Active Directory é atualizado com a nova senha quando você altera a senha da conta de serviço RMS em um servidor. O Serviços de Informações da Internet (IIS) reinicia periodicamente os pools de aplicativos, e os pools que estiverem em execução sob credenciais antigas não poderão ser iniciados antes de a senha da conta de serviço RMS ser alterada e o IIS ser reiniciado nesse servidor. O RMS não funciona sem que os pools de aplicativos sejam novamente executados.

**Usando duas contas de serviço RMS**

Com esse método, primeiro crie duas contas de serviço RMS com diretivas ou datas de vencimento diferentes. Durante a operação normal, o RMS é executado sob a primeira conta. Quando você estiver pronto para alterar a senha da conta de serviço para a primeira conta, execute as seguintes etapas em cada servidor RMS:

1.  Se o servidor estiver em um cluster, retire o servidor da rotação.
2.  Especifique a segunda conta de serviço RMS como a conta sob a qual o RMS será executado. Para obter instruções sobre como alterar a conta, consulte [Alterando a conta de serviço RMS](https://technet.microsoft.com/f257d66d-b823-41e4-bcb7-7c90eb295238), mais adiante neste tema.
3.  Reinicie o IIS.
4.  Se for o caso, coloque o servidor novamente na rotação.

Uma vez que todos os servidores RMS estejam usando a segunda conta de serviço RMS, você poderá alterar a senha na primeira conta de serviço RMS sem interferir na operação do sistema RMS. É possível alternar entre as duas contas dessa maneira, evitando o tempo de inatividade do RMS.
