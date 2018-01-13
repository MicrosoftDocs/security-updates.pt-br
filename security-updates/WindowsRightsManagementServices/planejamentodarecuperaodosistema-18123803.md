---
TOCTitle: Planejamento da recuperação do sistema
Title: Planejamento da recuperação do sistema
ms:assetid: 'a7779ffd-7a94-4e13-b846-0ffd00608e02'
ms:contentKeyID: 18123803
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747718(v=WS.10)'
---

Planejamento da recuperação do sistema
======================================

Ocorrem falhas no sistema por numerosos e diferentes motivos não-planejados: falhas de hardware, inundações, picos na tensão, erros de software, etc. Uma implantação bem-sucedida inclui planos para recuperar rapidamente o sistema em caso de falha. Em um sistema RMS, o requisito básico para proteção dos recursos do RMS é atendido com o backup regular da chave particular e dos bancos de dados do RMS, em especial do banco de dados de configuração. Essa prática preserva os modelos de diretiva de direitos, chaves e outros dados necessários para fornecer acesso a licenças anteriores e conteúdo publicado. Se a sua instalação do RMS ficar indisponível, instale o RMS em outros servidores e, em seguida, configure o RMS especificando o banco de dados de configuração de backup como o banco de dados a ser usado. A nova instalação do backup será idêntica à instalação anterior no momento em que o backup foi feito pela última vez.

Esta seção inclui:

-   [Preparação da recuperação do sistema](https://technet.microsoft.com/885c047f-1e3b-4bf5-8248-3a4505759cbb)
-   [Backups de sistema para RMS](https://technet.microsoft.com/c29894da-ee00-428c-8d48-80d8e5a83678)
-   [Fazendo backup e restaurando o sistema para o RMS](https://technet.microsoft.com/c11f3ac1-e512-402b-bf13-9ff21f5fe745)
-   [Fazendo backup e restaurando modelos de diretiva de direitos](https://technet.microsoft.com/a6ed3328-4128-45e8-9236-3de484b460de)
