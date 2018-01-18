---
TOCTitle: Novidades desta versão
Title: Novidades desta versão
ms:assetid: 'c68ec6fd-0ff5-467e-85a8-a53b9f089de3'
ms:contentKeyID: 18123842
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747748(v=WS.10)'
---

Novidades desta versão
======================

O RMS (Rights Management Services) com Service Pack 1 (SP1) fornece suporte para os seguintes recursos:

-   **Registrar o servidor RMS sem conectividade do servidor à Internet**. Na versão anterior, o servidor RMS precisava ser capaz de se conectar à Internet para se inscrever no Microsoft Enrollment Service e receber o certificado de licenciante para servidor raiz. Com o RMS SP1, o certificado de licenciante para servidor raiz ainda deve ser solicitado com o Microsoft Enrollment Service, mas também pode ser solicitado com outro computador com conectividade à Internet e depois importado para o servidor RMS após a configuração.
-   **Os clientes são ativados automaticamente**. Na versão anterior, os cofres e os certificados de máquina para os computadores clientes precisavam ser baixados do Serviço de Ativação da Microsoft. Com o RMS SP1, não é necessário ter uma conexão com o Serviço de Ativação da Microsoft.
-   **Suporte para mais tipos de clientes**. Nesta versão, o servidor RMS pode ser usado para oferecer suporte a clientes em dispositivos móveis e serviços do servidor. Como administrador de um servidor RMS, você poderá controlar se o servidor fornecerá certificação a esses clientes quando tentarem usar os serviços.
-   **Suporte para modelos em vários idiomas**. Na versão anterior, os modelos baseavam-se na configuração de idioma do Internet Explorer. Nesta versão, você pode especificar na página de administração do RMS na Web qual idioma deve ser usado para criar um modelo.
-   **Suporte para autenticação de clientes com cartões inteligentes**. Nesta versão, o cliente do RMS pode usar credenciais armazenadas como certificados x.509 em cartões inteligentes para autenticar com o servidor RMS com a finalidade de certificados de conta de direitos e licenças de uso.
