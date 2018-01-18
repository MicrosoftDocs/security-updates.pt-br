---
TOCTitle: Controlar certificados de conta de direitos
Title: Controlar certificados de conta de direitos
ms:assetid: 'f9efac9f-c725-4bce-a89f-7691b0d8ffc0'
ms:contentKeyID: 18123838
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747752(v=WS.10)'
---

Controlar certificados de conta de direitos
===========================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Este recurso está disponível somente no cluster raiz de certificação; não está disponível nos servidores ou clusters de licenciamento.

Esse procedimento só pode ser utilizado para estimar o número de licenças de uso e só é útil se forem licenças faturáveis. O número exibido na página Relatório de certificação de conta RM é uma aproximação. Se você não tiver atualizado o banco de dados de configuração para excluir os usuários que não estão mais ativos, esse número não estará correto. Além disso, se houver usuários com várias licenças em diversas florestas, as licenças adicionais não estarão incluídas no número exibido.

Controlando certificados de conta de direitos
---------------------------------------------

#### Controlar certificados de conta de direitos

1.  Abra a página **Administração Global** e, próximo ao site em que deseja controlar certificados, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em Relatório de certificação de conta RM.

3.  Sob **Total de usuários certificados**, visualize o número de usuários que recebeu certificados de conta de direitos desse cluster raiz de certificação.

Para obter mais informações, consulte "[Controlando certificados de conta de direitos](https://technet.microsoft.com/5bb0f3cf-fc44-4e60-a93f-c789d6f8a902)", mais adiante neste tema.
