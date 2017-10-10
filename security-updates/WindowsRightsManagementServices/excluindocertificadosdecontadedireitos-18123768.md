---
TOCTitle: Excluindo certificados de conta de direitos
Title: Excluindo certificados de conta de direitos
ms:assetid: 'cba5e901-942c-4d06-9865-e6c4648c95e6'
ms:contentKeyID: 18123768
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747670(v=WS.10)'
---

Excluindo certificados de conta de direitos
===========================================

Se um usuário for confiável mas suas credenciais de RMS estiverem comprometidas, você poderá excluir o certificado de conta de direitos do usuário excluindo sua chave pública. Quando isso é feito, o RMS nega novas solicitações de licença de uso que envolvam esse certificado de conta de direitos. Depois de excluir um certificado de conta de direitos, a solicitação será negada na próxima vez que o usuário tentar adquirir uma licença de uso para novo conteúdo. Para adquirir uma licença de uso, o usuário precisará recuperar um novo certificado de conta de direitos com um novo par de chaves.

Os certificados de conta de direitos podem ser excluídos usando-se a página **Diretivas de exclusão** do site de administração. Quando o certificado de conta de direitos de um usuário é excluído, o RMS adiciona a chave excluída, o nome da conta do usuário, a data e a hora da exclusão à tabela DRMS\_GicExclusionList do banco de dados de configuração do cluster raiz de certificação. Essas informações também são exibidas na página **Diretivas de exclusão** do site de administração. Além disso, o RMS exclui as chaves públicas e particulares que estão associadas ao certificado de conta excluído da tabela UD\_Users do banco de dados de configuração.

Para excluir um certificado de conta de direitos que está no servidor ou cluster raiz de certificação, especifique a conta de domínio do usuário na página **Diretivas de exclusão** do servidor raiz de certificação. Você deve excluir um certificado de conta de direitos entre servidores com sub-registro no site de administração de cada servidor. Para excluir um usuário em um servidor ou cluster de licenciamento com sub-registro, digite o valor da chave pública do certificado de conta de direitos na página **Diretivas de exclusão** do site de administração do servidor de licenciamento. Esse valor pode ser obtido na página de **diretivas de exclusão** do site de administração do cluster raiz de certificação.

Para simplificar a exclusão do certificado de conta de direitos em toda a implantação de vários clusters do RMS, você pode replicar a tabela DRMS\_GicExclusionList do banco de dados de configuração do cluster raiz de certificação para o banco de dados de configuração de cada cluster de licenciamento. Se você fizer isso, não será necessário digitar manualmente o valor da chave pública em cada servidor.
