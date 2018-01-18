---
TOCTitle: Alterar as configurações de proxy RMS
Title: Alterar as configurações de proxy RMS
ms:assetid: '8f50bd4d-26b1-4996-b361-722ee21607f3'
ms:contentKeyID: 18123689
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747594(v=WS.10)'
---

Alterar as configurações de proxy RMS
=====================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para obter mais informações sobre os métodos de autenticação do servidor proxy e sobre como eles funcionam no Windows Server 2003, consulte a Ajuda do IIS (Internet Information Services).

Alterando as configurações de proxy RMS
---------------------------------------

#### Alterar as configurações de proxy RMS

1.  Abra a página **Administração Global** e clique em **Administrar o RMS neste site**.

2.  Em **Administração de Cluster**, clique em **Configurações de segurança**.

3.  Se você não usou anteriormente um servidor proxy com RMS, marque a caixa de seleção **Este computador usa um servidor proxy para conectar-se à Internet**. As configurações adicionais aparecerão na página para você completar.

4.  Na caixa **Endereço**, digite o endereço IP ou nome DNS do servidor proxy que você deseja usar.

5.  Na caixa **Porta**, digite o número da porta que o servidor proxy usa para se conectar à Internet.

6.  Se você não usar o servidor proxy para se conectar aos recursos locais, marque a caixa de seleção **Não usar proxy para endereços locais**.

7.  Se for necessário, marque a caixa de seleção **O servidor proxy requer autenticação**.

    -   Escolha o tipo de autenticação na lista, **Básica**, **Digest** ou **Integrada do Windows**.
    -   Em **Nome de usuário**, insira o nome de usuário que deve ser fornecido em resposta ao desafio do servidor proxy.
    -   Em **Senha**, insira a senha que deve ser fornecida em resposta ao desafio do servidor proxy.
    -   Em **Confirmar senha**, reinsira a senha fornecida anteriormente a fim de verificar se você a inseriu corretamente.
    -   Se o seu servidor usa a autenticação Integrada do Windows, em **Domínio**, insira o domínio ao qual o usuário pertence.

8.  Clique em **Enviar**.
