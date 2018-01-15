---
TOCTitle: Compreendendo o processo de descomissionamento
Title: Compreendendo o processo de descomissionamento
ms:assetid: '57bd9949-9433-437b-93ed-ffb2dff9992e'
ms:contentKeyID: 18123601
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720276(v=WS.10)'
---

Compreendendo o processo de descomissionamento
==============================================

Ao utilizar o ISS (Serviços de Informações da Internet), o RMS expõe vários serviços que ele oferece. Por exemplo, o serviço de certificação registra usuários e seus respectivos computadores, e o serviço de licenciamento publica conteúdo e fornece acesso a informações protegidas pelo RMS. Um serviço adicional, chamado de serviço de descomissionamento, deve ser habilitado no servidor RMS para dar início ao processo de descomissionamento. Quando o serviço de descomissionamento é habilitado, todos os demais serviços RMS fornecidos pelo servidor são desabilitados.

Depois que o servidor RMS tiver sido habilitado para o descomissionamento, os aplicativos poderão obter uma chave de conteúdo junto ao serviço de descomissionamento que habilite o aplicativo a descriptografar permanentemente o conteúdo protegido pelo RMS.

Quando o servidor RMS está operando no modo de descomissionamento, qualquer usuário, tendo tido direitos ou não em relação ao conteúdo original protegido pelo RMS, pode obter uma chave de conteúdo e ganhar direitos completos de acesso ao conteúdo.

Uma vez descriptografado o conteúdo, o usuário deve salvá-lo sem a proteção do RMS. Saiba que para usar o serviço de descomissionamento, o usuário deve ter sido registrado na infra-estrutura do RMS. Um usuário sem um cliente do RMS ativado não pode usar o serviço de descomissionamento para ganhar acesso ao conteúdo protegido pelo RMS.
