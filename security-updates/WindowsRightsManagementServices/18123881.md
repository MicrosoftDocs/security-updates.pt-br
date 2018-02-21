---
TOCTitle: Definindo requisitos de gerenciamento de chaves
Title: Definindo requisitos de gerenciamento de chaves
ms:assetid: 'f0e08fb8-bf5e-4278-a09f-daa57696e786'
ms:contentKeyID: 18123881
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747797(v=WS.10)'
---

Definindo requisitos de gerenciamento de chaves
===============================================

O RMS usa chaves criptográficas para fornecer proteção de conteúdo e aplicação de direitos. As chaves criptografadas são informações fundamentais que permitem que o sistema opere com perfeição e segurança. Os administradores devem tomar cuidado para gerenciar adequadamente essas chaves e se protegerem contra perda de dados, falhas no sistema e roubo.

Na configuração padrão, o RMS armazena o par de chaves do servidor e sua GUID associada em uma tabela do banco de dados de configuração. O par de chaves do servidor é criptografado por uma senha selecionada no processo de configuração.

Para ajudar a proteger o par de chaves do servidor e sua GUID associada, faça o backup do banco de dados de configuração em uma mídia de armazenamento (como em um CD) e guarde essa mídia em local seguro (como um cofre externo à organização). A programação de backups depende da freqüência das alterações administrativas e do nível de risco aceitável para a perda de dados devido à degradação da mídia ou a outros riscos da mídia. Certifique-se de que dispõe de meios de saber que senha de chave particular foi usada no backup do banco de dados de configuração. Sem a senha apropriada, você não conseguirá restaurar o backup para o servidor RMS.

Se estiver usando o SQL Server como servidor de banco de dados, use o SQL Server Enterprise Manager para copiar diretamente o valor dos dados da chave particular criptografada e da GUID para um disquete protegido ou para outra mídia. Como a chave particular é protegida, a instalação do RMS deverá ser executada sob a mesma conta de serviço RMS do backup, no caso de você restaurá-la da mídia segura para uma instalação RMS.

Se usar um CSP de software ou hardware para proteger a chave particular do servidor, você deverá fazer manualmente o backup da chave e de seu recipiente. Quando você utiliza um módulo de segurança de hardware, a segurança das chaves particulares é aperfeiçoada mantendo-se as chaves particulares em hardware e nunca as expondo ao software. Os dados que precisam ser descriptografados ou assinados são transmitidos ao módulo de segurança de hardware, descriptografados e assinados e, em seguida, retransmitidos.

Cada CSP, seja de hardware ou de software, tem procedimentos específicos para o backup da chave com segurança. Se não estiver familiarizado com esse procedimento, consulte a documentação do CSP.
