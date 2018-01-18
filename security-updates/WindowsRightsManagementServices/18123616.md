---
TOCTitle: Registrar um ponto de conexão de serviço
Title: Registrar um ponto de conexão de serviço
ms:assetid: '630cc3c3-9ed9-4423-8874-cbaceb43b353'
ms:contentKeyID: 18123616
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720283(v=WS.10)'
---

Registrar um ponto de conexão de serviço
========================================

Registrando um ponto de conexão de serviço
------------------------------------------

Se você estiver registrando um ponto de conexão de serviço a partir de um servidor RMS em um subdomínio, é possível que receba uma mensagem de erro informando que o registro do SCP (ponto de conexão de serviço) apresentou uma falha. Em vários casos, o registro foi bem-sucedido, mas ocorre que ele é feito primeiramente no domínio de primeiro nível, e leva tempo para replicar para o subdomínio onde o servidor RMS verifica o objeto de ponto de conexão de serviço. Quando o SCP tiver sido replicado em todos os servidores do catálogo global da floresta, a mensagem não será mais exibida. Se você receber essa mensagem, deve aguardar um período de tempo aceitável antes de tentar solucionar o problema, para ver se ele foi resolvido.

#### Registrar um ponto de conexão de serviço

1.  Faça logon no servidor em que você precisa registrar um ponto de conexão de serviço, utilizando uma conta do domínio que tenha privilégios suficientes para criar um objeto de recipiente abaixo do recipiente de serviços no recipiente de configuração da floresta do Active Directory. O grupo de segurança predefinido, **Administradores de Empresa**, é um exemplo de uma conta com os privilégios necessários.

2.  Abra a página **Administração Global** e clique no link **Administrar o RMS neste site**.

3.  Na Home page de **Administração**, clique no link **Ponto de conexão de serviço do RMS**.

4.  Na página **Ponto de conexão de serviço do RMS**, clique no botão **Registrar URL**.
