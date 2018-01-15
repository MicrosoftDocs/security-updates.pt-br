---
TOCTitle: Ativar ou desativar o log
Title: Ativar ou desativar o log
ms:assetid: '8e672f95-566f-4070-9a2a-2f70f087148f'
ms:contentKeyID: 18123762
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747674(v=WS.10)'
---

Ativar ou desativar o log
=========================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Certifique-se de que o servidor RMS possui uma conexão com o servidor do banco de dados e de que o serviço do banco de dados foi iniciado antes de ativar o registro. Se o Enfileiramento de Mensagens não puder fornecer os registros ao banco de dados de registro, ele manterá os dados enfileirados no disco rígido do servidor RMS. Ele continuará fazendo isso até ocupar todo o espaço de armazenamento no servidor. Nessa condição, o RMS não exibe uma mensagem de erro, visto que esse recurso tem a função de suportar o registro nos períodos em que a conexão com o servidor SQL for interrompida.

Ativando ou desativando o log
-----------------------------

#### Ativar ou desativar o log

1.  Abra a página **Administração Global** e, ao lado do site em que deseja ativar ou desativar o registro, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Configurações de registro**.

3.  Na área **Banco de dados e servidor de registro**, marque a caixa de seleção **Ativar registro** e clique em **Atualizar**.

    Para desativar o registro, desmarque a caixa de seleção e clique em **Atualizar**.

Para obter mais informações sobre como desempenhar esse procedimento, consulte "[Ativando e desativando o log](https://technet.microsoft.com/50ccd827-2d39-41e7-a395-3d5f5836869b)", já mencionado neste tema.
