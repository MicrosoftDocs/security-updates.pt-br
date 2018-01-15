---
TOCTitle: Alterando a conta de serviço RMS
Title: Alterando a conta de serviço RMS
ms:assetid: 'f257d66d-b823-41e4-bcb7-7c90eb295238'
ms:contentKeyID: 18123828
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747736(v=WS.10)'
---

Alterando a conta de serviço RMS
================================

Durante a instalação, o RMS cria o Grupo de Serviço RMS no computador local e lhe concede as permissões apropriadas em todos os recursos necessários para a operação do RMS. Quando você configura o RMS em um servidor, define a conta de serviço RMS usando uma conta de domínio. A conta de serviço RMS não pode ser a mesma conta do domínio que você usou para instalar o RMS. A conta é configurada como um membro do Grupo de Serviço RMS e recebe as permissões associadas a esse grupo. Durante a operação de rotina, o RMS é executado sob a conta de serviço RMS.

Você pode alterar a conta de serviço RMS a qualquer momento. Quando isso ocorre, a conta especificada anteriormente é automaticamente removida do Grupo de Serviço RMS e a nova conta é configurada como membro do grupo.

> [!Important]  
> Por razões de segurança, recomenda-se a criação de uma conta de usuário especial para usar como conta de serviço do Windows RMS e a utilização dessa conta apenas para tal finalidade. Além disso, não conceda permissões adicionais a essa conta. 

> [!Note]  
> A conta de serviço RMS não pode ser a mesma conta do domínio utilizada para instalar o RMS com o Service Pack 1. 
