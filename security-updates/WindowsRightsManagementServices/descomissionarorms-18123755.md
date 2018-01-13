---
TOCTitle: Descomissionar o RMS
Title: Descomissionar o RMS
ms:assetid: '8b563c25-17cd-4b9b-ae42-695497ab6439'
ms:contentKeyID: 18123755
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747665(v=WS.10)'
---

Descomissionar o RMS
====================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

| ![](images/Cc747665.Warning(WS.10).gif)Aviso                                                        |
|----------------------------------------------------------------------------------------------------------------------------------|
| Quando você encerra um servidor, ele não pode ser restaurado para uma configuração RMS padrão. Esse procedimento é irreversível. |

| ![](images/Cc747665.Warning(WS.10).gif)Aviso                                                                                                 |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Depois de você descomissionar o RMS, ele deve ser totalmente removido usando-se Adicionar ou Remover Programas, antes que você tente instalar uma outra instância do RMS. |

Descomissionando o RMS
----------------------

#### Descomissionar o RMS

1.  Faça logon no servidor no qual você deseja encerrar o RMS.

2.  Abra a página **Administração Global** e clique no link **Administrar o RMS neste site**.

3.  Na **Home Page de Administração**, clique no link **Configurações de segurança**.

4.  Na área **Encerramento do RMS**, marque a caixa de seleção **Habilite o encerramento da instalação do RMS** e clique em **Encerrar**.

5.  Quando solicitado, clique em **OK** para confirmar que deseja encerrar permanentemente a instalação do RMS.
