---
TOCTitle: Registrando o ponto de conexão de serviço
Title: Registrando o ponto de conexão de serviço
ms:assetid: '446d83ec-3224-45e2-9697-625e7db338f3'
ms:contentKeyID: 18123572
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720260(v=WS.10)'
---

Registrando o ponto de conexão de serviço
=========================================

O SCP (Ponto de conexão de serviço) do RMS identifica a URL de conexão para o serviço para os clientes habilitados para RMS de sua organização. Os clientes não serão capazes de descobrir o RMS para solicitar licenças de uso, licenças de publicação ou certificados de contas de direitos sem um SCP válido.

Você pode registrar a URL do SCP do cluster raiz de certificação na página **Ponto de Conexão de Serviço** do site de administração. Pode também cancelar o registro da URL do ponto de conexão de serviço na página **Ponto de Conexão de Serviço** se precisar, por qualquer motivo, redefinir a URL. Para registrar ou cancelar o registro da URL do SCP, você deve fazer o logon com uma conta de usuário de domínio válida que possua privilégios suficientes para criar um objeto recipiente sob o recipiente Serviços.

Sob o recipiente de serviços no Active Directory, um novo objeto de recipiente será criado com o nome de "RightsManagementServices". Sob esse recipiente o objeto do SCP será criado com o nome "MSRMRootCluster". Esse objeto de ponto de conexão de serviço possui dois valores para seu atributo de palavras-chave:

-   MSRMRootCluster
-   1.0

Esses são os atributos usados por clientes e outros servidores para localizar a URL do cluster raiz no Active Directory. O serviceBindingInformation no objeto do ponto de conexão de serviço conterá a URL do cluster raiz, no formato http://*nomedocluster*/\_wmcs/Certification.
