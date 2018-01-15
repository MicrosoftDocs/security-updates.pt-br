---
TOCTitle: Instalar o RMS com Service Pack 1
Title: Instalar o RMS com Service Pack 1
ms:assetid: 'dab20175-a690-43f8-b943-768d289daa0d'
ms:contentKeyID: 18123785
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747689(v=WS.10)'
---

Instalar o RMS com Service Pack 1
=================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

O computador em que você está instalando o RMS deve ser um servidor membro em um domínio ou deve ser um controlador de domínio. Não é possível implantar o RMS em um servidor autônomo em um grupo de trabalho.

| ![](images/Cc747689.Important(WS.10).gif)Importante                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Não configure o RMS em outro servidor sem antes ter concluído a instalação e a configuração do primeiro servidor raiz de certificação. Para obter instruções, consulte "[Configurar o primeiro servidor raiz de certificação](https://technet.microsoft.com/debc42f3-74ff-4c99-b7a4-4921fccdabc2)", "[Configurar um servidor de licenciamento](https://technet.microsoft.com/4d67b898-0ba9-4eef-ab7d-ee0ca55a688e)" ou "[Adicionar um servidor a um cluster](https://technet.microsoft.com/db635238-5528-4bec-9cc6-8244e2b3d733)", mais adiante neste tema. |

| ![](images/Cc747689.Important(WS.10).gif)Importante                                                                                                                                                                        |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| O RMS SP1 pode ser instalado em um servidor que está executando no momento a versão anterior do RMS. No entanto, se você encerrar o RMS, ele deverá ser totalmente removido, usando Adicionar ou Remover Programas, antes de tentar instalar o RMS SP1. |

Instalando o RMS com Service Pack 1
-----------------------------------

#### Instalar o RMS com Service Pack 1

1.  No servidor em que você deseja instalar o RMS SP1, faça logon com uma conta de domínio que seja membro do grupo local de Administradores.

2.  Quando a caixa de diálogo **Bem-vindo** aparecer, verifique a lista de software a ser instalado e clique em **Avançar**.

3.  Na caixa de diálogo **Contrato de Licença**, verifique o contrato, selecione **Aceito** e clique em **Avançar**.

4.  Em **Pasta**, aceite a pasta padrão ou especifique uma pasta nova e clique em **Avançar**.

5.  Na caixa de diálogo **Confirmar Instalação**, clique em **Instalar** para iniciar a instalação.

6.  Quando a caixa de diálogo **Instalação Concluída** aparecer, clique em **Fechar**.

    | ![](images/Cc747689.note(WS.10).gif)Observação                                                         |
    |-------------------------------------------------------------------------------------------------------------------------------------|
    | Se a mensagem de erro "Reiniciando aplicativo" aparecer, atualize a página **Administração Global** no Microsoft Internet Explorer. |

Você também pode instalar o RMS a partir de um prompt de comando. Para obter instruções, consulte "[Instalação a partir do prompt de comando do servidor do RMS](https://technet.microsoft.com/b55b1e2a-dd14-4168-a37f-9cdedbec660b)", mais adiante neste tema.
