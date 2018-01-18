---
TOCTitle: Excluir certificados de conta de direitos
Title: Excluir certificados de conta de direitos
ms:assetid: 'e5cd9dec-ac29-437e-8515-dc697ec75edf'
ms:contentKeyID: 18123871
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747785(v=WS.10)'
---

Excluir certificados de conta de direitos
=========================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Essas condições são aplicadas pelo cliente no momento em que a licença de uso é vinculada ao conteúdo protegido.

Excluindo certificados de conta de direitos
-------------------------------------------

#### Excluir certificados de conta de direitos

1.  Abra a página **Administração Global** e próximo ao site em que deseja excluir certificados de conta de direitos, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Diretivas de exclusão**.

3.  Na área de exclusão de certificado de conta de direitos, clique em **Habilitar** para excluir o certificado de conta de direitos de um usuário.

4.  Selecione o método para especificar o certificado de conta a excluir:

    -   Para excluir o certificado de conta por nome de usuário, clique em **Nome de usuário** do certificado de conta de direitos a ser excluído, digite o nome do usuário a ser excluído (na forma *nome\_usuário*@*nome\_domínio*.com) e depois clique em **Adicionar**. Utilize essa opção para excluir os certificados de conta de usuários internos que têm contas de usuário do Active Directory.
    -   Para excluir um certificado de conta por chave pública, clique em **Seqüência de caracteres da chave pública** para o certificado de conta a ser excluída:, digite a série de chave pública do certificado de conta de direitos apropriada e depois clique em **Adicionar**. Utilize essa opção para excluir os certificados de conta de usuários externos que não têm contas de usuário do Active Directory.

    > [!Note]  
    > Para excluir um certificado de conta da lista de exclusão, clique no certificado de conta de direitos excluído na lista e clique em **Excluir as chaves públicas selecionadas da lista de exclusão**. O usuário que tiver esse certificado de conta específico não conseguirá uma licença para o conteúdo protegido pelo RMS desse servidor.

    > [!Note]  
    > Para desabilitar a exclusão dos certificados de conta de direitos, clique em **Desabilitar**.

Para obter mais informações sobre a execução desse procedimento, consulte "[Excluindo certificados de conta de direitos](https://technet.microsoft.com/cba5e901-942c-4d06-9865-e6c4648c95e6)", já mencionado neste tema.
