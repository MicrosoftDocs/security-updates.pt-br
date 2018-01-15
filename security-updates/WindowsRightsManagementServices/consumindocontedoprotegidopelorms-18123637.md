---
TOCTitle: Consumindo conteúdo protegido pelo RMS
Title: Consumindo conteúdo protegido pelo RMS
ms:assetid: '3cf6d64b-1187-433c-bbb2-c68069bc3c30'
ms:contentKeyID: 18123637
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720251(v=WS.10)'
---

Consumindo conteúdo protegido pelo RMS
======================================

Quando os usuários consumem conteúdo protegido, ocorrem dois processos que são transparentes para o usuário. Primeiro, o aplicativo habilitado para RMS solicita uma licença de uso quando o usuário abre o documento. Em seguida, o aplicativo habilitado para RMS examina a licença de uso, a fim de determinar se ela exige uma lista de revogação, e verifica se foi revogado algum certificado que esteja na sua cadeia de confiança ou na cadeia de confiança do certificado de conta de direitos. Quando ambos os processos tiverem sido concluídos, o aplicativo habilitado para RMS processará o conteúdo protegido pelo RMS, se todos os direitos e revogações assim o permitirem.

Se uma lista de revogação for necessária, o aplicativo procura por uma cópia local da lista de revogação que não expirou. Se necessário, ele recupera uma cópia atual da lista de revogação. Em seguida, o aplicativo aplica qualquer condição de revogação que seja relevante no contexto atual.

Se nenhuma condição de revogação bloquear o acesso ao conteúdo, o aplicativo processará o conteúdo e o usuário poderá exercer os direitos que foram concedidos a ele.

Você configura o RMS para processar solicitações de licença de uso feitas por usuários externos autorizados. Isso permite que os usuários compartilhem conteúdo protegido pela Internet.

Esta seção contém os seguintes tópicos:

-   [Aquisição de licenças de uso](https://technet.microsoft.com/0b6cde34-418a-4dee-9d27-b65b93b535ac)
-   [Licenças de uso e usuários externos](https://technet.microsoft.com/02db9bda-180e-438f-863d-26252083a471)
