---
TOCTitle: Removendo a proteção por RMS do conteúdo
Title: Removendo a proteção por RMS do conteúdo
ms:assetid: 'c30361e3-50d2-4474-a87d-d38de502cf9e'
ms:contentKeyID: 18123761
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747658(v=WS.10)'
---

Removendo a proteção por RMS do conteúdo
========================================

Decida com antecedência quais arquivos precisam ser recuperados, por quem e quando, de modo que todas as informações importantes sejam preservadas quando o processo de descomissionamento estiver concluído. Quando a proteção por RMS tiver sido removida de todos os arquivos protegidos por RMS necessários, o servidor poderá ser removido da infra-estrutura.

O processo de remoção da proteção por RMS do conteúdo ocorre da seguinte maneira:

1.  O usuário deve remover do computador todas as licenças de uso existentes. Isso garante que o cliente do RMS acessará o servidor para adquirir uma licença e abrir o conteúdo. As licenças de uso são armazenadas na pasta %USERPROFILE%\\Local Settings\\Application Data\\Microsoft\\DRM do computador cliente e possuem um prefixo de licença de usuário final no nome do arquivo.
2.  Um usuário com acesso ao servidor de descomissionamento tenta abrir um arquivo protegido pelo RMS.
3.  O aplicativo se conecta ao servidor de descomissionamento e recebe a chave de conteúdo.
4.  O conteúdo é descriptografado e pode ser editado, salvo, encaminhado ou impresso.
5.  O usuário salva o conteúdo sem a proteção do RMS. A partir desse momento, todos os usuários podem abrir o conteúdo sem precisarem se conectar ao servidor RMS.
