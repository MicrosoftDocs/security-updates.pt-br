---
TOCTitle: Estimando o crescimento do banco de dados
Title: Estimando o crescimento do banco de dados
ms:assetid: '87652cc2-b886-4797-8d40-356669768089'
ms:contentKeyID: 18123670
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747585(v=WS.10)'
---

Estimando o crescimento do banco de dados
=========================================

Para fazer a estimativa da quantidade de armazenamento necessária para os bancos de dados do RMS, planeje uma capacidade mínima de 10 MB e adicione 1 MB para cada grupo de 500 usuários do banco de dados de configuração do RMS. O banco de dados de log pode existir em um servidor de banco de dados diferente do banco de dados de configuração.

Se você estiver usando o recurso de log do RMS, o banco de dados de log precisará oferecer suporte a um crescimento de aproximadamente 1 MB para cada usuário durante a fase inicial de certificação de usuário, quando uma grande quantidade de logs ocorre. Por exemplo, se a implantação oferecer suporte a mil usuários, o banco de dados de log poderá aumentar para 1 GB, pois cada um desses usuários é ativado e certificado pelo servidor de certificação do RMS. Em operações de rotina, o banco de dados de log pode aumentar a uma taxa de 200 KB para cada usuário por dia (se você estiver fazendo uma implementação em fases, estime 1 MB adicional para cada novo usuário incluído no sistema).
