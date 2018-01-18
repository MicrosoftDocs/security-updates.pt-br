---
TOCTitle: Questões de configuração do RMS
Title: Questões de configuração do RMS
ms:assetid: 'b0e6ef48-ab38-4426-be5b-811cf64c45c0'
ms:contentKeyID: 18123740
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747638(v=WS.10)'
---

Questões de configuração do RMS
===============================

Quando você configura o RMS, os arquivos dos recursos e as conexões entre os vários componentes nos quais o RMS se baseia são configurados e estabelecidos. Se for encontrado um erro quando o RMS estiver tentando configurar um recurso, a configuração falhará e apresentará uma mensagem de erro. Esta seção aborda as causas mais comuns desses erros com o intuito de ajudá-lo a solucionar situações inesperadas que impedem a conclusão da configuração do RMS.

Impossível configurar o servidor raiz de certificação
-----------------------------------------------------

É possível que você não esteja conseguindo configurar um servidor raiz de certificação porque as páginas de configuração corretas não estão sendo exibidas. Esse comportamento ocorre quando você clica em Configurar o RMS neste site para configurar o primeiro servidor raiz de certificação na página Administração Global. No entanto, no lugar das páginas de configuração para um servidor raiz de certificação, são mostradas as páginas para configurar um servidor de licenciamento.

Esse problema ocorre quando você não desconfigura o último servidor raiz de certificação dessa floresta do Active Directory antes de desinstalar o RMS dele e depois tenta configurar um servidor raiz de certificação. Quando você desconfigura o único servidor raiz de certificação de uma floresta do Active Directory, está removendo o ponto de conexão do serviço do Active Directory. Se você não desconfigurar o último servidor raiz de certificação da floresta antes de desinstalar o RMS, não poderá reconfigurar um servidor raiz de certificação que está nessa floresta sem antes remover manualmente o ponto de conexão de serviço do Active Directory.

Se as páginas de configuração para um servidor de licenciamento aparecerem quando você tentar configurar o primeiro servidor raiz de certificação de uma floresta do Active Directory, remova o ponto de conexão de serviço do Active Directory, da seguinte forma:

**Remover o ponto de conexão de serviço para o RMS**
1.  Se necessário, instale as Ferramentas de suporte do Windows Server:

    No Windows Server 2003, execute Suptools.msi, que se encontra na pasta \\Support\\Tools do CD de instalação.

    No Windows 2000 Server, na pasta \\Ferramentas de Suporte que está no CD de instalação, execute Setup.exe.

2.  Faça logon no controlador do domínio do qual o servidor raiz de certificação é membro, usando uma conta que seja membro do grupo Admins. do domínio.

3.  Digite o comando a seguir na linha de comando e pressione ENTER:

    **ldp**

4.  Clique em **Conexão** e, em seguida, em **Conectar**.

5.  Pressione ENTER. Não digite nenhuma informação.

6.  Clique em **Conexão** e, em seguida, clique em **Vincular**.

7.  Pressione ENTER. Não digite nenhuma informação.

8.  Clique em **Exibir** e, em seguida, em **Árvore**.

9.  Pressione ENTER. Não digite nenhuma informação.

    **dc=SeuDomínio,dc=com** é exibido no painel esquerdo.

10. Expanda **dc=SeuDomínio,dc=com**.

11. Expanda **Configuração**.

12. Expanda **Serviços**.

13. Exclua **RightsManagementServices**.

-ou-

1.  Baixe e instale o RMS Administration Toolkit. O kit de ferramentas pode ser baixado do [site da Microsoft](http://go.microsoft.com/fwlink/?linkid=33841).
2.  Abra o prompt de comando, clicando em **Iniciar**, **Executar**. Na caixa de diálogo **Executar**, digite **cmd** e depois clique em **OK**.
3.  Em um prompt de comando, digite o seguinte comando:
    **ADSCPRegister.exeunregisterscp** &lt;*URLtoUnRegister*&gt;
4.  Para &lt;*URLtoUnRegister*&gt;, digite a URL do ponto de conexão de serviço do RMS, por exemplo https://meu\_domínio/\_wmcs/Certificação.

Concluídas essas etapas, você está pronto para configurar o servidor raiz de certificação.

Não é possível gerar contexto SSPI
----------------------------------

É possível que você receba a mensagem de erro "Não é possível gerar contexto SSPI" durante a configuração, se a conta de serviço RMS não estiver autenticada ao registrar o servidor raiz de certificação com o Microsoft Enrollment Service.

Se receber essa mensagem de erro, verifique se a conta do serviço RMS é uma conta válida do domínio. Se a conta for uma conta de grupo, verifique se a participação de grupo é a atual, se você pode resolver todas as contas de usuário do grupo do domínio e se as contas possuem permissões para os bancos de dados do SQL.
