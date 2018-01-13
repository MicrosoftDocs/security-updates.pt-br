---
TOCTitle: Planejando a implantação entre florestas
Title: Planejando a implantação entre florestas
ms:assetid: '2dfb40b7-95b1-4362-b32e-72867544b705'
ms:contentKeyID: 18123618
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720233(v=WS.10)'
---

Planejando a implantação entre florestas
========================================

Se você estiver implantando o RMS em um ambiente com várias florestas, será necessário determinar que suporte será exigido para usuários ou grupos fora da floresta na qual o RMS está sendo implantado. O problema é que objetos de usuário ou de grupo de outras florestas geralmente não possuem objetos representativos na floresta em que o RMS reside. Caso pretenda usar o RMS para restringir permissões a usuários ou grupos de outras florestas, será necessário configurar apropriadamente sua floresta para permitir a expansão de grupos entre florestas.

Pode-se implementar o suporte à expansão de grupos entre florestas para o RMS de duas maneiras:

-   Implantar o RMS na floresta em que os grupos estão definidos e no local em que será usado para expandir a participação desses grupos.
-   Sincronizar as definições de grupos entre florestas para permitir que a instalação do RMS local determine a participação de grupo completa para todos os usuários. Se o usuário que está solicitando uma licença de uso tiver uma conta Windows em uma floresta separada, também será necessário que exista um objeto de contato na floresta local para representar a participação de grupo desse usuário. Você pode usar metadiretórios, como o MIIS (Microsoft® Identity Integration Server) 2003 ou o IIFP (Identity Integration Feature Pack) para implementar a sincronização de alta fidelidade de objetos de grupo entre florestas.

Se desejar usar o RMS em uma única floresta, você poderá otimizar o processo de emissão de licenças de uso modificando as diretivas de cluster **MaxCrossForestCalls** no banco de dados de configuração do RMS. Essa diretiva especifica o número máximo de vezes que a participação de um grupo pode atravessar os limites da floresta. O valor padrão é 10. Para alterar esse valor para 0, use o seguinte comando SQL:

`update DRMS_ClusterPolicies set PolicyData=0 where PolicyName='MaxCrossForestCalls'`
