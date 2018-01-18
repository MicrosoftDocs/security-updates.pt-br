---
TOCTitle: Modelos de diretiva de direitos
Title: Modelos de diretiva de direitos
ms:assetid: 'eee931c8-7c98-48e9-9e2c-d0b7bd4f2b96'
ms:contentKeyID: 18123825
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747732(v=WS.10)'
---

Modelos de diretiva de direitos
===============================

Os modelos de diretiva de direitos descrevem um conjunto padrão de usuários, direitos e condições que pode ser aplicado ao conteúdo protegido pelo RMS. Quando um usuário aplica um modelo de diretiva de direitos a uma parte do conteúdo, os direitos que ele descreve tornam-se parte da licença de publicação.

No site de Administração do RMS, você pode criar modelos de diretiva de direitos, bem como excluir ou modificar os modelos existentes. Os modelos de diretiva de direitos podem incluir várias condições, como grupos do Active Directory ou destinatários específicos, o período de validade de uma licença de uso para o conteúdo, durante quanto tempo o conteúdo pode ser consumido após a publicação e até mesmo valores personalizados que sejam significativos para um determinado aplicativo habilitado para RMS. Um modelo pode requerer uma lista de revogação. O modelo especifica a URL para o arquivo de lista e o número de dias de validade da lista. Quando um destinatário solicita uma licença de uso com base no modelo, o sistema verifica a lista de revogação antes que o usuário possa consumir o conteúdo protegido pelo RMS. Para obter mais informações, consulte "[Revogação no RMS](https://technet.microsoft.com/72689f90-f3c5-4b61-94ea-d825f3199b3b)", mais adiante neste tema.

Exemplos de direitos que são estabelecidos em modelos de diretiva de direitos podem incluir:

-   Qualquer pessoa pode exibir o conteúdo, mas somente o autor pode modificá-lo.
-   Qualquer pessoa da empresa pode exibir o conteúdo, mas somente por um mês depois da publicação.
-   Qualquer pessoa da empresa pode exibir o conteúdo, mas nenhum parceiro ou cliente externo pode exibi-lo.
-   Somente recipientes especificados podem exibir o conteúdo.
-   Somente um recipiente especificado pode exibir ou modificar o conteúdo.

Os modelos podem incluir várias condições, como:

-   Recipientes ou grupos do Active Directory específicos que possuem direitos para o conteúdo.
-   O período de validade da licença de uso do conteúdo.
-   O período depois da publicação em que o conteúdo pode ser consumido.
-   Se a licença de uso requer uma lista de revogação e a freqüência de atualização da lista.
-   Valores personalizados que são significativos para um determinado aplicativo habilitado para RMS.

Os modelos de diretivas de direitos são armazenados no banco de dados de configuração e em uma pasta compartilhada. O administrador do RMS é responsável pela distribuição dos modelos de diretiva de direitos, da pasta compartilhada até os computadores clientes, a fim de que os autores possam usá-los. Para obter mais informações, consulte "Distribuindo modelos de diretiva de direitos" em "Operando um servidor RMS", nesta coleção de documentos.

Em um aplicativo habilitado para RMS, os autores podem selecionar o modelo de diretiva de direitos a ser aplicado, o que geralmente especifica um grupo cujos membros podem consumir o conteúdo. Quando um recipiente solicita uma licença de uso, o servidor aplica o modelo de diretiva de direitos do banco de dados. Isso garante que os termos de uma licença de uso sempre reflitam a versão mais atual do modelo.
