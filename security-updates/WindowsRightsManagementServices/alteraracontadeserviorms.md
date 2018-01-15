---
TOCTitle: Alterar a conta de serviço RMS
Title: Alterar a conta de serviço RMS
ms:assetid: 'a3e522b0-e23d-49f2-b00a-cff90ac2c36a'
ms:contentKeyID: 18123798
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747713(v=WS.10)'
---

Alterar a conta de serviço RMS
==============================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

A conta de serviço RMS não pode ser a mesma conta do domínio utilizada para instalar o RMS com Service Pack 1.

Alterando a conta de serviço RMS
--------------------------------

#### Alterar a conta de serviço RMS

1.  Abra a página **Administração Global** e, em seguida, próximo ao site em que o RMS é configurado, clique em **Alterar conta de serviço RMS**.

2.  Especifique o nome da conta sob a qual o RMS será executado na maioria das operações. Nas contas de domínio, utilize o formato *nome\_domínio*\\*nome\_usuário*.

3.  Digite a senha e clique em **Enviar**.
