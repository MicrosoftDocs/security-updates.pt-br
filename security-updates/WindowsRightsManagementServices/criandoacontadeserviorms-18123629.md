---
TOCTitle: Criando a conta de serviço RMS
Title: Criando a conta de serviço RMS
ms:assetid: '6eb38729-f0f0-431a-bc8c-17102cf175d8'
ms:contentKeyID: 18123629
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747546(v=WS.10)'
---

Criando a conta de serviço RMS
==============================

Durante a instalação, o RMS cria um grupo de segurança chamado **Grupo de Serviço RMS** no computador local e lhe concede as permissões apropriadas em todos os recursos necessários para a operação do RMS.

Quando você configura o RMS em um servidor, especifica uma conta de usuário como a conta de serviço RMS. A conta que você especifica é configurada como um membro do Grupo de Serviço RMS e, assim, recebe as permissões associadas a esse grupo. Durante a operação normal, o RMS é executado sob a conta de serviço RMS, na maioria dos casos.

| ![](images/Cc747546.note(WS.10).gif)Observação                 |
|---------------------------------------------------------------------------------------------|
| A conta de serviço RMS não pode ser a mesma conta do domínio utilizada para instalar o RMS. |

Por razões de segurança, recomenda-se a criação de uma conta de usuário especial para usar como conta de serviço do Windows RMS e a utilização dessa conta apenas para tal finalidade. Além disso, não conceda permissões adicionais a essa conta.

| ![](images/Cc747546.Important(WS.10).gif)Importante     |
|--------------------------------------------------------------------------------------|
| Você deve criar essa conta de usuário especial antes de instalar e configurar o RMS. |

Para obter mais informações sobre as permissões concedidas ao Grupo de Serviço RMS e as contas sob as quais o RMS é executado, consulte "Modelo de segurança do RMS" em "Referência técnica do RMS", nesta coleção de documentos.
