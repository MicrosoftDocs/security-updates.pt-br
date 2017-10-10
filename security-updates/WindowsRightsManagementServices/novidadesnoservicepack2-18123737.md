---
TOCTitle: Novidades no Service Pack 2
Title: Novidades no Service Pack 2
ms:assetid: 'a944cb73-d900-42bb-b7aa-92916dead408'
ms:contentKeyID: 18123737
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747629(v=WS.10)'
---

Novidades no Service Pack 2
===========================

O RMS com Service Pack 2 (SP2) fornece suporte para os seguintes recursos:

-   **Suporte nativo para Microsoft® SQL Server™ 2005**. Em versões anteriores do RMS, uma solução alternativa era necessária para usar o RMS com o SQL Server 2005. Para obter informações sobre a solução alternativa, consulte o artigo 913372 da Base de Dados de Conhecimento Microsoft ([http://go.microsoft.com/fwlink/?LinkId=68638](http://go.microsoft.com/fwlink/?linkid=68638)). No RMS com SP2, esse problema foi corrigido.
-   **Microsoft Office SharePoint® Server 2007**. Nesta versão, há suporte para o Office SharePoint Server 2007. A biblioteca de documentos do Office SharePoint Server 2007 aplica automaticamente permissões do RMS a documentos com base em direitos do Office SharePoint Server 2007 à medida que são baixados. Isso é obtido com a instalação do cliente do RMS com SP2 no servidor Office SharePoint Server 2007. Não é recomendável instalar o servidor RMS com SP2 e o Office SharePoint Server 2007 no mesmo computador.
-   **Maior segurança em mensagens ao banco de dados de log**. Nesta versão, todas as mensagens do Enfileiramento de Mensagens dos servidores RMS ao banco de dados de log são assinadas digitalmente.
-   **Lotes de servidor maiores**. Nesta versão, agora é possível que um aplicativo habilitado para RMS recupere várias licenças de uso para diferentes contas de usuário por meio de uma única solicitação de licença ao servidor RMS. Isso aumenta o desempenho reduzindo a sobrecarga de várias solicitações de licença para o mesmo conteúdo protegido por direitos.
-   **Expansão de grupo avançada entre florestas**. Nesta versão, a expansão de grupo do RMS entre florestas é feita por meio de uma solicitação SOAP para um novo serviço Web ASP.NET executado no servidor RMS.
