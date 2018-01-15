---
TOCTitle: Site de Administração do RMS
Title: Site de Administração do RMS
ms:assetid: 'f003c1d9-9a17-4e50-9e1e-5d67677552a0'
ms:contentKeyID: 18123879
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747796(v=WS.10)'
---

Site de Administração do RMS
============================

Cada cluster raiz e somente de licenciamento hospeda um site de Administração que você pode usar para gerenciar o RMS. Esse site está disponível apenas no servidor do RMS que você está administrando ou através de uma conexão de área de trabalho remota.

Este tópico descreve capacidades do site de administração. As instruções sobre como usar o site para administrar o RMS são fornecidas em "RMS: Como ..." e "Gerenciando o RMS" em "RMS: operações" nesta coleção de documentos.

**Observação** A configuração de clusters é global. Você pode gerenciar a configuração de um cluster no site de administração em qualquer servidor que esteja no cluster.

Abra a página **Administração Global** para executar as seguintes tarefas:

-   Configurar o RMS neste site.
-   Configurar um servidor e adicioná-lo a um cluster.
-   Remover o RMS de um site.
-   Vá para as páginas de administração do cluster.

Abra a página **Administração** de um cluster para executar as seguintes tarefas:

-   **Exibir informações do cluster.** Você pode exibir informações sobre o cluster, como a URL de instalação, a URL do servidor, o nome do certificado, o servidor de banco de dados de configuração, o nome do banco de dados de configuração e a data de validade do certificado.
-   **Registrar ou renovar o certificado de licenciante para servidor.** Você pode registrar ou renovar o certificado de licenciante para servidor do cluster.
-   **Estabelecer diretivas de confiança.** Clique no link para abrir a página da Web Diretivas de Confiança, na qual você pode adicionar ou remover domínios de usuário confiáveis e domínios de publicação confiáveis. Adicione ou remova usuários da lista de exclusão que está em um domínio de usuário confiável. Exporte o certificado de licenciante para servidor para um arquivo para ser importado por outra instalação do RMS.
-   **Configurar modelos de diretiva de direitos.** Clique no link para abrir a página da Web Modelos de diretivas de direitos, na qual você pode criar e modificar modelos de diretiva de direitos para a empresa.
-   **Configurar o log.** Clique no link para abrir a página da Web Configurações de log, na qual você pode ativar e desativar o log e depois exibir o servidor e o banco de dados de log.
-   **Especificar a URL do cluster da extranet.** Clique no link para abrir a página da Web de configurações da URL do cluster da extranet, na qual você pode especificar a URL a ser usada para obter acesso aos serviços de certificação do cluster raiz a partir da extranet.
-   **Especificar as configurações de proxy RMS.** Clique no link para abrir a página da Web Configurações de proxy RMS, na qual você pode especificar o endereço do servidor proxy, o tipo de autenticação e o nome do usuário a ser utilizado quando o servidor do RMS precisar se conectar à Internet usando um servidor proxy.
-   **Controlar a quantidade de certificados de conta de direitos distribuídos.** Clique no link para abrir a página da Web de controle dos certificados de conta de direitos, na qual você pode ver quantos certificados de conta de direitos foram distribuídos pelo cluster raiz, o que pode ser usado para estimar o número de licenças de acesso de cliente necessárias.
-   **Gerenciar configurações de segurança.** Clique no link para abrir a página da Web Configurações de segurança, na qual você pode adicionar e remover membros do grupo de superusuários que tenham controle total sobre todo o conteúdo licenciado, bem como redefinir a senha da chave particular.
-   **Exibir e definir configurações de certificados de conta.** Clique no link para abrir a página da Web Configurações de certificação, na qual você pode especificar a validade do certificado e um contato do administrador.
-   **Habilitar diretivas de exclusão.** Clique no link para abrir a página da Web Diretivas de exclusão, na qual você pode habilitar diretivas de exclusão com base na versão do cofre, versão do Windows, certificado de conta e aplicativos.
-   **Registrar o ponto de conexão de serviço.** Clique no link para abrir a página da Web Ponto de conexão de serviço, na qual você pode fazer ou cancelar o registro do ponto de conexão de serviço do cluster.

Os administradores podem executar outras tarefas, incluindo eventos de monitoração e gerenciamento do Active Directory, do IIS (Serviços de Informações da Internet) e do SQL Server, usando o Console de Gerenciamento Microsoft (MMC).
