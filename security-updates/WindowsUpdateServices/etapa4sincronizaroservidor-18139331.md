---
TOCTitle: 'Etapa 4: sincronizar o servidor'
Title: 'Etapa 4: sincronizar o servidor'
ms:assetid: 'a5514e46-a50b-46a6-9e5b-33c87c5b7cef'
ms:contentKeyID: 18139331
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc708523(v=WS.10)'
---

Etapa 4: sincronizar o servidor
===============================

Depois de configurar a conexão de rede, você pode obter as atualizações. Por padrão, o WSUS é configurado para baixar as Atualizações Críticas e de Segurança para todos os produtos Microsoft. Para obter atualizações, é preciso *sincronizar* o servidor do WSUS.

A sincronização envolve o contato do servidor do WSUS com o Microsoft Update. Depois desse contato, o WSUS determina se existe alguma nova atualização disponível desde a última vez em que foi feita a sincronização. Como esta é a primeira vez que você está sincronizando o servidor do WSUS, todas as atualizações estarão disponíveis e prontas para sua aprovação para instalação.

| ![](images/Cc708523.note(WS.10).gif)Observação                                                                                                                                                                                                                                                 |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Este documento descreve a sincronização usando as configurações padrão, mas o WSUS inclui opções que permitem minimizar o uso da largura de banda durante a sincronização. Para obter mais informações, consulte o informe oficial “Deploying Microsoft Windows Server Update Services” (o documento pode estar em inglês). |

**Para sincronizar o servidor do WSUS**
1.  Na barra de ferramentas do console do WSUS, clique em **Opções** e em **Opções de Sincronização**.

2.  Em **Tarefas**, clique em **Sincronizar Agora**.

Depois da conclusão da sincronização, clique em **Atualizações** na barra de ferramentas do console do WSUS para exibir a lista de atualizações.
