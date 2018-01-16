---
TOCTitle: Fazendo alterações no banco de dados de configuração
Title: Fazendo alterações no banco de dados de configuração
ms:assetid: '6a7bec73-09e4-4060-b551-5990836df4bc'
ms:contentKeyID: 18123699
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747606(v=WS.10)'
---

Fazendo alterações no banco de dados de configuração
====================================================

As alterações de configuração feitas usando o site de administração refletem-se no banco de dados de configuração do servidor ou cluster. É altamente recomendável alterar as definições de configuração no site de administração, em vez de alterar os dados manualmente no banco de dados de configuração. No entanto, há duas situações que podem exigir alterações manualmente no banco de dados:

-   **Movendo o banco de dados de log para um servidor diferente.** Por padrão, o banco de dados de log é instalado no mesmo servidor que o banco de dados de configuração. Se você decidir mover o banco de dados de registro para um servidor diferente, deverá modificar o banco de dados de configuração para fazer referência ao novo local. Para obter mais informações sobre como mover um banco de dados de log, incluindo informações sobre como atualizar o banco de dados de configuração com o novo local, consulte "[Realocando o banco de dados de log](https://technet.microsoft.com/34ea8045-dc94-422e-9601-29927cfc1534)", mais adiante neste tema.
-   **Removendo chaves de usuários associadas a certificados de conta de direitos**. Quando uma conta de usuário é removida do Active Directory ou um certificado de conta de direitos é excluído ou revogado usando-se o site de administração, as chaves do usuário associadas ao certificado de conta de direitos do banco de dados de configuração não são removidas. Você deve remover chaves de usuários inativos manualmente do banco de dados de configuração, em parte por motivos de segurança, mas também para ajudar no controle do número de licenças de acesso para cliente. Para obter mais informações sobre como remover chaves de usuários do banco de dados de configuração, consulte "[Excluindo contas de usuários](https://technet.microsoft.com/bf73b141-d4d1-4807-a773-3aaff58b0db6)", já mencionado neste tema. Para obter mais informações sobre como controlar licenças de acesso para cliente, consulte "[Controlando certificados de conta de direitos](https://technet.microsoft.com/5bb0f3cf-fc44-4e60-a93f-c789d6f8a902)", já mencionado neste tema.

Se precisar fazer alterações diretamente em um banco de dados de configuração, consulte o administrador do servidor do banco de dados.
