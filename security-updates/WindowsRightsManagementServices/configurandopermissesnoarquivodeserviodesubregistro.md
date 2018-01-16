---
TOCTitle: 'Configurando permissões no arquivo de serviço de sub-registro'
Title: 'Configurando permissões no arquivo de serviço de sub-registro'
ms:assetid: '737bb69b-fe26-4057-9569-e632f7bbf295'
ms:contentKeyID: 18123712
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747627(v=WS.10)'
---

Configurando permissões no arquivo de serviço de sub-registro
=============================================================

O serviço de sub-registro é executado no servidor raiz de certificação e registra um servidor de licenciamento durante a configuração. Por padrão, o serviço de sub-registro permite acesso somente à conta do sistema local que se encontra no servidor raiz de certificação. Para configurar um servidor de licenciamento, é necessário fazer logon no servidor de licenciamento com tal conta. Como alternativa, um administrador local no servidor raiz de certificação precisa alterar a lista de controle de acesso condicional no arquivo de serviço de subscrição, SubEnrollService.asmx, para conceder acesso à conta do usuário que executará a configuração no servidor de licenciamento. SubEnrollService.asmx está localizado no diretório virtual Certificação no servidor raiz de certificação.
