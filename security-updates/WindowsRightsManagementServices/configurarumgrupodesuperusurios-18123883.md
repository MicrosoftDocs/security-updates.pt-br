---
TOCTitle: Configurar um grupo de superusuários
Title: Configurar um grupo de superusuários
ms:assetid: 'f2ef847e-2824-471f-9079-5c343094aba8'
ms:contentKeyID: 18123883
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747798(v=WS.10)'
---

Configurar um grupo de superusuários
====================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Antes de ser designado como o grupo de superusuários do RMS, o grupo deve existir no Active Directory e suas propriedades devem incluir um endereço de email (especificado como um nome de domínio totalmente qualificado), que é o mesmo que o nome da conta.

Configurando um grupo de superusuários
--------------------------------------

#### Configurar um grupo de superusuários

1.  Abra a página **Administração Global** e, próximo ao site em que deseja configurar um grupo de superusuários, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Configurações de segurança**.

3.  Na área **Superusuários**, clique em **Habilitar** para adicionar um grupo de superusuários.

4.  Em **Nome do grupo de superusuários**, digite o nome do domínio totalmente qualificado, na forma *nome\_grupo*@*nome\_domínio*.com, de um grupo existente nessa floresta do Active Directory, a cujos membros serão concedidos direitos de proprietário para todos os documentos protegidos pelo RMS e, em seguida, clique em **Salvar**.

    Para desabilitar os direitos do grupo de superusuários, clique em **Desabilitar**.

Para obter mais informações sobre como desempenhar esse procedimento, consulte "[Usando o grupo de superusuários](https://technet.microsoft.com/0febcb3e-7124-4e51-971a-1013b928d33b)", já mencionado neste tema.
