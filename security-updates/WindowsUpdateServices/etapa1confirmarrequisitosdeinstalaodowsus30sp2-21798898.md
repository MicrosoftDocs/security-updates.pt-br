---
TOCTitle: 'Etapa 1: Confirmar requisitos de instalação do WSUS 3.0 SP2'
Title: 'Etapa 1: Confirmar requisitos de instalação do WSUS 3.0 SP2'
ms:assetid: 'ec01bd75-5def-4899-8cee-ddab827bbd83'
ms:contentKeyID: 21798898
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Dd939916(v=WS.10)'
---

Etapa 1: Confirmar requisitos de instalação do WSUS 3.0 SP2
===========================================================

Antes de instalar ou atualizar para o Windows Server Upgrade Services 3.0 Service Pack 2 (WSUS 3.0 SP2), verifique se os computadores servidor e cliente atendem aos requisitos de sistema WSUS 3.0 SP2 e confirme se você tem as permissões necessárias para concluir a instalação.

Requisitos de hardware e software para instalação do WSUS 3.0 SP2
-----------------------------------------------------------------

1.  Confirme se o servidor atende aos requisitos dos sistema do WSUS 3.0 SP2 quanto a hardware, sistema operacional e outro software necessário. Os requisitos de sistema estão listados nas notas de versão do WSUS 3.0 SP2 em [http://go.microsoft.com/fwlink/?LinkId=139840](http://go.microsoft.com/fwlink/?linkid=139840). Se você estiver usando o Gerenciador de Servidores para instalar o WSUS 3.0 SP2 Server, confirme se você atende aos requisitos de software seguindo as etapas na seção “Preparando-se para instalar o WSUS 3.0 SP2”.
2.  Se você instalar funções ou atualizações de software que necessitem a reinicialização do servidor quando a instalação for concluída, reinicie o servidor antes de instalar o WSUS 3.0 SP2.

Requisitos de software cliente
------------------------------

As Atualizações Automáticas são o cliente do WSUS 3.0.O único requisito de hardware para as Atualizações Automáticas é que haja uma conexão com a rede.

1.  Confirme se o computador no qual você está instalando as Atualizações Automáticas atende aos requisitos de sistema do WSUS 3.0 SP2 para computadores clientes. Os requisitos de sistema são listados nas notas de versão do WSUS 3.0 SP2 em [http://go.microsoft.com/fwlink/?LinkId=139840](http://go.microsoft.com/fwlink/?linkid=139840).
2.  Se você tiver instalado atualizações de software que requerem o reinício do computador, reinicie-o antes de instalar o WSUS 3.0 SP2.

Permissões
----------

As seguintes permissões são necessárias para os usuários e diretórios especificados:

1.  A conta Autoridade NT\\Serviço de Rede deve ter a permissão Controle Total para as seguintes pastas para que o snap-in da Administração do WSUS seja exibido corretamente:
    -   %windir%\\Microsoft .NET\\Framework\\v2.0.50727\\Temporary ASP.NET Files
    -   %windir%\\Temp
2.  Confirme se a conta que você planeja usar para instalar o WSUS 3.0 SP2 é um membro do grupo Administradores Locais.

Preparando para instalar o WSUS 3.0 SP2
---------------------------------------

Se você estiver executando o Windows 7 ou o Windows Server 2008 SP2, você pode instalar o WSUS 3.0 SP2 a partir do Gerenciador de Servidor. Se você estiver usando outro sistema operacional suportado ou instalando apenas o Console de Administração WSUS, vá para a próxima seção deste guia para instalar o WSUS 3.0 SP2 usando o arquivo WUSSetup.exe.

**Para preparar a instalação do WSUS 3.0 SP2 Server usando o Gerenciador de Servidores**
1.  Você deve fazer logon no servidor em que pretende instalar o WSUS 3.0 SP2 usando uma conta que seja membro do grupo Administradores Locais.

2.  Clique em **Iniciar**, aponte para **Ferramentas Administrativas** e clique em **Gerenciador de Servidores**.

3.  No painel do lado direto da janela do Gerenciador de Servidores, na seção Resumo de Funções, clique em **Add Roles**.

4.  Se a página Antes de Começar aparecer, clique **Avançar**.

5.  Na página Selecionar Funções do Servidor, confirme se **Servidor de Aplicativos** e **Servidor Web (IIS)** estão selecionados. Se eles estiverem selecionados, use o restante desta etapa para confirmar se os serviços de função necessários foram selecionados. Caso contrário, instale o Servidor de Aplicativos e e Servidor Web (IIS) como mostrado.

    1.  Na página Selecionar Funções do Servidor, selecione **Servidor de Aplicativos** e **Servidor Web (IIS)** e clique em **Avançar**.
    2.  Se você estiver instalando os Serviços de Função de Aplicativo, na página Servidor de Aplicativos, clique em **Avançar**. Na página Serviços de Função do Servidor de Aplicativos, aceite as configurações padrão e, então, clique em **Avançar**.
    3.  Se você estiver instalando o Servidor Web IIS na página Servidor Web IIS, clique em **Avançar**. Na página Serviços de Função do Servidor Web (IIS), além das configurações padrão, selecione **ASP.NET**, **Autenticação do Windows**, **Compactação de Conteúdo Dinâmico** e **Compatibilidade de Gerenciamento do IIS 6**. Se a janela do Assistente para Adicionar Funções aparecer, clique em **Adicionar Serviços de Função Necessários**. Clique em **Avançar**.
    4.  Na página Confirme as Seleções de Instalação, clique em **Instalar**.
    5.  Na página Resultados da Instalação, confirme se uma mensagem de "Instalação bem-sucedida" aparece para os serviços de função instalados nesta etapa e, então, clique em **Close**.

Próxima etapa
-------------

[Etapa 2: Instalar o Servidor WSUS ou o Console de Administração](https://technet.microsoft.com/6db6fcb0-c55d-43b9-9b07-4040c6267759).

Recursos adicionais
-------------------

[Guia passo a passo para o Windows Server Update Services 3.0 SP2](https://technet.microsoft.com/4b504edc-93b3-45b0-a7e8-d0107f1a4442)
