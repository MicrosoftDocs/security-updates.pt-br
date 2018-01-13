---
TOCTitle: 'Etapa 5: Configurar as atualizações de clientes'
Title: 'Etapa 5: Configurar as atualizações de clientes'
ms:assetid: '5ae60ead-3e94-456c-a692-c0f193ea5d5a'
ms:contentKeyID: 21798797
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Dd939830(v=WS.10)'
---

Etapa 5: Configurar as atualizações de clientes
===============================================

No Windows Server Update Services 3.0 (WSUS 3.0 SP2), a instalação do WSUS configura o IIS automaticamente para distribuir a versão mais recente das Atualizações Automátias para cada computador cliente que entre em contato com o servidor WSUS.

A melhor maneira de configurar as Atualizações Automáticas depende do ambiente de rede. Em um ambiente que use o serviço de diretório Active Directory® , você pode usar um objeto Diretiva de Grupo (GPO) baseado em domínio ou criar um novo GPO.Em um ambiente sem o Active Directory, use o GPO local. Nesta etapa, você configurará as Atualizações Automáticas e, então, apontará os computadores clientes para o servidor WSUS.

Os procedimentos a seguir consideram que sua rede está executando o Active Directory. Esses procedimentos também consideram que você está familiarizado com a Diretiva de Grupo e a usa para gerenciar a rede.

Para obter mais informações sobre a Diretiva de Grupo, consulte o site Web Group Policy Tech Center ([http://go.microsoft.com/fwlink/?LinkID=47375](http://go.microsoft.com/fwlink/?linkid=47375)).

 
-

Procedimentos da etapa 5
------------------------

Na etapa 4, você concluiu a configuração das atualizações que deseja baixar. Use este conjunto de procedimentos para configurar as atualizaçoes automáticas para computadores clientes.

1.  Configurar Atualizações Automáticas na diretiva de grupo.
2.  Direcionar um computador cliente ao servidor WSUS.
3.  Iniciar a detecção manual pelo servidor WSUS.

Você executará os primeiros dois procedimentos no GPO baseado em domínio de sua escolha e o terceiro procedimento em um prompt de comando no computador cliente.

**Para configurar as Atualizações Automáticas**
1.  No Group Policy Management Console (GPMC), navegue até o GPO no qual você deseja configurar o WSUS e, então, clique em **Editar**.

2.  No GPMC, expanda **Configuração do Computador**, expanda **Modelos Administrativos**, expanda **Componentes do Windows** e clique em **Windows Update**.

3.  No painel de detalhes, clique duas vezes em **Configurar Atualizações Automáticas**.

4.  Clique em **Habilitado** e clique em uma destas opções:

    -   **Notificar para download e notificar para instalação**. Esta opção notifica um usuário administrativo que tenha efetuado logon antes do download e antes da instalação das atualizações.
    -   **Fazer o download automático das atualizações e avisar quando elas estiverem prontas para serem instaladas**. essa opção começa a baixar as atualizações automaticamente e depois notifica um usuário administrativo conectado antes de instalar as atualizações.
    -   **Baixar automaticamente e agendar a instalação**. Esta opção baixa automaticamente as instalações e, então, instala as atualizaçõs no dia e hora especificados.
    -   **Permitir que o administrador local escolha a configuração**. Esta opção permite que administrador local use as Atualizações Automáticas no Painel de Controle para selecionar uma opção de configuração. Por exemplo, eles podem escolher sua própria hora de instalação agendada. Os administradores locais não podem desativar as Atualizações Automáticas.

5.  Clique em **OK**.

**Para direcionar os computadores clientes ao servidor WSUS**
1.  No painel de detalhes **Windows Update**, clique duas vezes em **Especificar o local do serviço de atualização na intranet da Microsoft**.

2.  Clique em **Habilitado** e digite a URL HTTP do mesmo servidor do WSUS nas caixas **Configurar o serviço de atualização da intranet para detectar atualizações** e **Configure as estatísticas do servidor intranet**. Por exemplo, digite *http://nome\_do\_servidor* em ambas caixas e clique em **OK**.

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939830.note(WS.10).gif" />Observação</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Se você estiver usando o objeto Diretiva de Grupo Local para direcionar o computador ao WSUS, essa configuração entrará em vigor imediatamente e esse computador será exibido no console administrativo do WSUS em pouco tempo.Você pode agilizar esse processo iniciando manualmente um ciclo de detecção.
</td>
</tr>
</tbody>
</table>
 

Após configurar um computador cliente, levará vários minutos antes que o computador apareça na página **Computadores** no Console de Administração WSUS. Para computadores clientes configurados com uma diretiva de grupo baseada em domínio, pode levar até 20 minutos para a atualização da diretiva (ou seja, para aplicação de qualquer nova política ao computador cliente). Por padrão, a diretiva de grupo é atualizada em segundo plano a cada 90 minutos, com um deslocamento aleatório de 0 a 30 minutos. Se você quiser atualizar a diretiva de grupo mais cedo, vá até o prompt de comando no computador cliente e digite **gpupdate /force**.

Para os computadores clientes configurados com o GPO local, a diretiva de grupo é imediatamente aplicada e a atualização levará aproximadamente 20 minutos.

Se você iniciar a detecção manualmente, não será preciso aguardar 20 minutos para que o computador cliente contate o WSUS.

**Para iniciar manualmente a detecção pelo servidor WSUS**
1.  No computador cliente, clique em **Iniciar** e em **Executar**.

2.  Digite **cmd** na caixa **Abrir** e, então, clique em **OK**.

3.  No prompt de comando, digite **wuauclt.exe /detectnow**.Essa opção de linha de comando instrui as Atualizações Automáticas a contatar o servidor do WSUS imediatamente.

Próxima etapa
-------------

[Etapa 6: Configurar grupos de computadores](https://technet.microsoft.com/70518732-2179-4e41-9609-7f9999867f41).

Recursos adicionais
-------------------

[Guia passo a passo para o Windows Server Update Services 3.0 SP2](https://technet.microsoft.com/4b504edc-93b3-45b0-a7e8-d0107f1a4442)
