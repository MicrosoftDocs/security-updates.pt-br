---
TOCTitle: Redefinindo a senha da chave particular
Title: Redefinindo a senha da chave particular
ms:assetid: 'ceba927e-a7fd-4b06-bb70-5e5d9d6d099c'
ms:contentKeyID: 18123775
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747675(v=WS.10)'
---

Redefinindo a senha da chave particular
=======================================

Quando você configura um servidor, seleciona um método para proteger a chave particular do RMS. Se você escolheu a opção padrão de usar a proteção da chave particular baseada no software, especificou uma senha forte que foi usada para criptografar a chave particular do servidor no banco de dados de configuração. Se você perder ou esquecer a senha, um membro do grupo de superusuários poderá redefini-la, conforme descrito na seção "[Redefinir a senha da chave particular](https://technet.microsoft.com/f71df255-fe19-4e07-810e-87309a5e8e88)", mais adiante neste tema.

Se você estiver executando o RMS em um ambiente em cluster, deve redefinir a chave particular em cada servidor front-end do RMS da sua instalação. Caso contrário, esses servidores não funcionarão, pois não conseguirão descriptografar a chave do servidor no banco de dados de configuração.

Para obter mais informações sobre senhas de segurança, consulte o Centro de ajuda e suporte do Windows Server 2003.
