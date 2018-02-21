---
TOCTitle: Habilitando o serviço de descomissionamento
Title: Habilitando o serviço de descomissionamento
ms:assetid: '45226e85-b50d-41cc-aca7-0f603f8509d5'
ms:contentKeyID: 18123574
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720261(v=WS.10)'
---

Habilitando o serviço de descomissionamento
===========================================

O descomissionamento do sistema RMS requer a chave particular usada para proteger todas as informações publicadas. Essa chave particular é armazenada no banco de dados de configuração, criptografada pela DPAPI (Data Protection API) e baseia-se na senha digitada durante a configuração. Se a chave particular do RMS estiver armazenada em um módulo de segurança de hardware (HSM), a chave particular estará armazenada no HSM e não no banco de dados de configuração.

> [!Caution]  
> Antes de descomissionar o sistema RMS, verifique se você possui a senha da chave particular. Caso não saiba essa senha, redefina a senha da chave particular antes de descomissionar o servidor do RMS. 

A primeira etapa para remover o sistema RMS é descomissionar os servidores do cluster. Como o descomissionamento é uma função de licenciamento, um servidor existente em um cluster somente de licenciamento do RMS com sub-registro pode ser descomissionado sem afetar o cluster raiz do RMS ou qualquer outro cluster somente de licenciamento RMS com sub-registro. Portanto, você precisa descomissionar separadamente o cluster raiz do RMS e quaisquer outros clusters somente de licenciamento porque cada cluster somente de licenciamento armazena sua própria chave particular usada para criar licenças de publicação.

Use o seguinte procedimento para habilitar o serviço de descomissionamento:

1.  Abra o site de Administração do Windows RMS.
2.  Clique em **Administrar o RMS** e depois clique em **Configurações de Segurança**.
3.  Marque a caixa de seleção **Habilite o descomissionamento da instalação do RMS**.
4.  Quando uma caixa de diálogo solicitar a confirmação do processo de descomissionamento, clique em **OK**.

Quando você descomissiona um servidor, ele não pode ser restaurado para uma configuração RMS padrão. Esse procedimento é irreversível.

Depois de você descomissionar o RMS, ele deve ser totalmente removido, usando-se **Adicionar ou Remover Programas**, antes de tentar instalar uma outra instância do RMS.
