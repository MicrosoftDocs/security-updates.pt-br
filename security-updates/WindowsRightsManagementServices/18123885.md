---
TOCTitle: Trabalhando com modelos de diretiva de direitos
Title: Trabalhando com modelos de diretiva de direitos
ms:assetid: 'ff4f1143-f6b9-4dd8-aa4c-c2cbbf6fdf06'
ms:contentKeyID: 18123885
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747804(v=WS.10)'
---

Trabalhando com modelos de diretiva de direitos
===============================================

Depois de criar um modelo de diretiva de direitos, você pode gerenciar como ele é aplicado na organização, controlando sua distribuição a autores.

O RMS armazena modelos de diretiva de direitos no banco de dados de configuração. Além disso, ele mantém uma cópia de todos os modelos de diretiva de direitos em uma pasta compartilhada que você especifica, conforme descrito na seção "[Especificar o local dos modelos de diretiva de direitos](https://technet.microsoft.com/e1bee46d-33db-424f-ba45-1dcedcb883ab)", mais adiante neste tema. Certifique-se de que os seus modelos estão armazenados em um local acessível na rede que atende às diretrizes de segurança da organização. Você não deve criar pastas compartilhadas para modelos nas pastas principais usadas pelo RMS, como a pasta Arquivos de Programas ou as pastas IISRoot.

Ao publicar conteúdo protegido, o autor seleciona o modelo de diretiva de direitos a ser aplicado entre os modelos disponíveis no computador local. Para disponibilizar modelos de diretiva de direitos para uso, o administrador deve implantá-los em computadores de usuários a partir de uma pasta compartilhada.

Quando um usuário tenta consumir conteúdo protegido, o aplicativo habilitado para RMS obtém a última versão do modelo de diretiva de direitos usado para publicar o conteúdo do banco de dados de configuração. Em seguida, o aplicativo habilitado para RMS aplica suas configurações ao conteúdo. Quando você modifica um modelo de diretiva de direitos no servidor RMS, o RMS atualiza o modelo de acordo, no banco de dados de configuração e na pasta compartilhada (se o servidor RMS estiver configurado para especificar um local para armazenamento de cópias de modelos de diretiva de direitos). Implante novamente o modelo de diretiva de direitos nos sistemas do cliente quando ele tiver sido modificado, de forma que os usuários tenham a versão mais atualizada disponível em seus computadores.

Se você excluir um modelo de diretiva de direitos, ele será removido do banco de dados de configuração e também da pasta compartilhada (especificada como o local para armazenar cópias de modelos) quando você excluir o modelo. No entanto, ele não será removido dos computadores dos usuários. Você deve removê-lo desse local manualmente. Você deve remover modelos de diretiva de direitos excluídos de todos os computadores de usuários. Se você não o fizer e o modelo de diretiva de direitos excluído for usado para publicar conteúdo, o RMS não poderá emitir licenças de uso para o conteúdo porque não poderá localizar o modelo especificado no banco de dados de configuração.

Ao trabalhar com modelos de diretiva de direitos, execute as seguintes tarefas:

-   **Especificar uma pasta compartilhada**. Antes de criar seu primeiro modelo de diretiva de direitos, é necessário especificar a pasta compartilhada na qual todos os modelos de diretiva de direitos serão armazenados. Para obter mais informações, consulte a seção "[Especificar o local dos modelos de diretiva de direitos](https://technet.microsoft.com/e1bee46d-33db-424f-ba45-1dcedcb883ab)", mais adiante neste tema.
-   **Criar e editar modelos de diretiva de direitos**. É possível criar tantos modelos de diretiva de direitos quantos forem necessários para gerenciar direitos em sua organização. Quando você cria um modelo de diretiva de direitos, você define os usuários e os direitos aplicáveis. Você também define como o modelo de diretiva de direitos deve ser aplicado ao conteúdo. Mais tarde, você pode editar modelos de diretiva de direitos quando precisar atualizá-los. Para obter mais informações, consulte "[Criando e modificando modelos de diretiva de direitos](https://technet.microsoft.com/6014176f-ef71-4d29-b3e3-da129c18563d)", mais adiante neste tema.
-   **Distribuir modelos de diretiva de direitos**. Para que um autor aplique um determinado modelo de diretiva de direitos a um conteúdo, deve existir no computador do autor uma cópia do modelo da diretiva de direitos. É possível controlar quais autores aplicam quais modelos de diretiva de direitos, gerenciando a distribuição do modelo. Para obter mais informações, consulte "[Distribuindo modelos de diretiva de direitos](https://technet.microsoft.com/ae6fa26f-d744-4ac9-9eb1-728ffab87bfe)", mais adiante neste tema.
-   **Retirar modelos de diretiva de direitos**. Quando não for mais apropriado, você pode excluir um modelo de diretiva de direitos. Ao fazer isso, você também deve removê-lo dos computadores de usuários para que eles não tenham problemas ao tentar consumir conteúdo que foi publicado usando o modelo de diretiva de direitos retirado. Para obter mais informações, consulte "[Retirando modelos de diretiva de direitos](https://technet.microsoft.com/32bf98c7-edda-4507-a4b8-4c11bddd6e60)", mais adiante neste tema.
