---
TOCTitle: Adicionar um domínio de usuário confiável
Title: Adicionar um domínio de usuário confiável
ms:assetid: 'ed672e58-6272-4ac0-a434-d1d938037e93'
ms:contentKeyID: 18123876
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747793(v=WS.10)'
---

Adicionar um domínio de usuário confiável
=========================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Adicionando um domínio de usuário confiável
-------------------------------------------

#### Adicionar um domínio de usuário confiável

1.  Abra a página **Administração Global** e, próximo ao site em que deseja adicionar um domínio de usuário confiável, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Diretivas de confiança**.

3.  Na área **Domínios de usuário confiáveis**, clique em **Procurar**, encontre e clique duas vezes no certificado do domínio de usuário que deseja importar para estabelecer a relação de confiança e clique em **Adicionar**.

    O nome do domínio é exibido na lista **Domínios de usuário confiáveis**.

4.  Para especificar quais domínios de email dentro do domínio confiável do usuário são confiáveis, clique em **Domínios confiáveis** ao lado do nome do certificado na lista para abrir a janela **Domínios de email confiáveis**.

5.  Escolha uma das seguintes opções de confiança:

    -   Selecione a opção **Confiar em todos os domínios de email** para confiar em todas as contas de usuários que são membros daquele domínio.
        OU
    -   Selecione **Confiar apenas nos domínios de email especificados** e digite o nome do domínio no qual confiar, como exemplo.com e, em seguida, clique em **Adicionar.** Isso adiciona o domínio à lista Domínios de email confiáveis. Para remover um nome da lista, selecione o nome e clique em **Remover**. A listagem de um domínio inclui todos os seus subdomínios.

6.  Se estiver usando o RMS em um ambiente em que seja necessário expandir associação de grupo entre florestas, marque a caixa de seleção **Confiar no licenciamento RM de Identificadores de Segurança (SIDs) deste domínio de usuário**.

7.  Ao concluir, clique em **Fechar a janela e retornar para as Diretivas de confiança**.

Para obter mais informações sobre como executar esse procedimento, consulte [Adicionando e removendo domínios de usuário confiáveis](https://technet.microsoft.com/7c440b15-01c4-49f1-b43c-00f67f3388c1), já mencionado neste tema.
