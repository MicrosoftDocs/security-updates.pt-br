---
TOCTitle: Descomissionando servidores RMS
Title: Descomissionando servidores RMS
ms:assetid: '11badb02-62c1-455c-96b7-935bbcb496bc'
ms:contentKeyID: 18123583
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720200(v=WS.10)'
---

Descomissionando servidores RMS
===============================

Quando o RMS é encerrado, o comportamento do servidor RMS é alterado de modo a fornecer uma chave que descriptografa o conteúdo protegido pelo RMS que ele havia publicado anteriormente. Essa chave permite que o conteúdo seja salvo sem proteção por RMS. Isso pode ser útil se você decidiu parar de usar a proteção por RMS em sua organização.

Execute o servidor em seu estado de encerramento por um tempo suficiente para que os usuários tenham a oportunidade de salvar seu conteúdo sem proteção por RMS e para que os administradores da rede e do sistema desabilitem o uso do serviço por qualquer cliente habilitado para RMS.

Você pode habilitar o descomissionamento na página **Configurações de segurança** do site de Administração. Depois de habilitar o encerramento, você não pode restaurar a configuração padrão do RMS no servidor. Se a instalação incluía qualquer domínio de publicação confiável, esses domínios também serão encerrados.

Depois que você habilitar o descomissionamento, o site de Administração conterá somente a página de **informações sobre o servidor descomissionado**; nenhuma administração adicional terá suporte. É necessário executar as seguintes etapas para concluir o encerramento do servidor:

1.  Forneça permissões de Leitura e Execução ao **Grupo de Serviço RMS** para a raiz virtual de encerramento.
2.  Adicione o grupo **Todos** à lista de controle de acesso condicional do arquivo decommissioning.asmx com permissões de leitura.
3.  Informe os usuários que você está encerrando a instalação do RMS e avise-os para se conectarem ao servidor e salvar seu conteúdo sem proteção pelo RMS.
4.  Configure todos os aplicativos habilitados para RMS em sua empresa para se conectarem à página decommissioning.asmx. Dependendo do aplicativo habilitado para RMS, isso poderá ser controlado por uma chave de registro ou pela configuração de Diretiva de Grupo.
5.  Se sua organização estiver usando aplicativos habilitados para RMS que usam automaticamente a instalação para publicação, você deverá usar Diretiva de Grupo para configurar uma entrada de registro naqueles computadores para que os aplicativos usem o serviço de encerramento.
6.  Depois de confirmar que todo o conteúdo está desprotegido, você deve fazer backup da chave particular do servidor e desinstalar o RMS do servidor.
