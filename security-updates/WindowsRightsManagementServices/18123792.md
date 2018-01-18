---
TOCTitle: Desconfigurar o RMS
Title: Desconfigurar o RMS
ms:assetid: '9fa63daa-5fb9-4afd-8371-b38248619857'
ms:contentKeyID: 18123792
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747706(v=WS.10)'
---

Desconfigurar o RMS
===================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Quando você desconfigura um servidor, ele é removido da tabela ClusterServer do banco de dados de configuração. Quando você desconfigura o último servidor em um cluster, o banco de dados de serviços de diretório é excluído do SQL Server. Ao desconfigurar o último servidor raiz de certificação em um cluster, você deve cancelar manualmente o SCP (ponto de conexão de serviço) de certificação. A desconfiguração e a desinstalação não removerão o SCP do Active Directory.

Se você optar por desinstalar um servidor raiz de certificação antes de tê-lo configurado, receberá um aviso informando que o site ainda não foi desconfigurado e que o SCP não será removido do Active Directory. No entanto, se selecionar **Sim** para continuar, o site será desconfigurado para você. A desinstalação não removerá o ponto de conexão de serviço do Active Directory.

Desconfigurando o RMS
---------------------

#### Desconfigurar o RMS

1.  Faça logon no servidor no qual você deseja desconfigurar o RMS.

2.  Abra a página **Administração Global**.

3.  Próximo ao site em que o RMS está configurado, clique em **Remover o RMS deste site** e clique em **OK**.

4.  Clique em **Cancelar registro da URL** na página de ponto de conexão de serviço do RMS para cancelar o registro da conexão do serviço de certificação do Active Directory.
