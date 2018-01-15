---
TOCTitle: Modos de segurança para o RMS
Title: Modos de segurança para o RMS
ms:assetid: 'd7792293-5bb2-4232-9d48-e81e87ab6219'
ms:contentKeyID: 18123782
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747686(v=WS.10)'
---

Modos de segurança para o RMS
=============================

O RMS usa configurações diferentes de segurança para os três seguintes modos:

-   Instalação: Os arquivos do RMS são instalados e configurados.
-   Configuração: Sites da Web, diretórios virtuais e bancos de dados são criados e configurados.
-   Operações normais: Alguns serviços (como certificação de conta) requerem autenticação e outros (como ativação de máquina) não requerem. Quando alguns serviços (como administração) são restritos, outros (como licenciamento) não são.

Em cada modo, o RMS ganha acesso a recursos diferentes para finalidades diferentes. Ele também usa contas de segurança diferentes, dependendo das operações que desempenha. Os demais tópicos desta seção descrevem a segurança nos três modos, as operações executadas pelo RMS e as contas de segurança que ele utiliza, bem como suas permissões de acesso.
