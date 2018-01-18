---
TOCTitle: Movendo contas de usuários entre domínios
Title: Movendo contas de usuários entre domínios
ms:assetid: '0010b0ea-07c0-41c9-81f7-5881343d1d55'
ms:contentKeyID: 18123569
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720179(v=WS.10)'
---

Movendo contas de usuários entre domínios
=========================================

Quando você instala e configura um servidor raiz de certificação em uma organização, ele é registrado no Active Directory em uma configuração por floresta como um provedor de serviços RMS. Pode haver somente um cluster raiz de certificação para cada floresta do Active Directory.

Em geral, quando você move uma conta de usuário de um domínio para outro domínio que está na mesma floresta, uma nova identificação de segurança é criada para a conta do usuário que está no novo domínio. Em seguida, quando um usuário tenta adquirir um novo certificado de conta de direitos do servidor, ele aparece como um novo usuário para o servidor, porque tem uma nova identificação de segurança. O servidor gera novas chaves para o usuário e emite o novo certificado de conta de direitos usando o endereço de email original do usuário. Quando o usuário tentar usar o novo certificado de conta de direitos com uma licença existente, a identificação de segurança e as chaves não corresponderão e será necessário que o usuário adquira uma nova licença. Isso também é verdadeiro ao mover-se uma conta de usuário para um domínio que está em uma floresta diferente.
