---
TOCTitle: Importar e utilizar o RMS Management Pack
Title: Importar e utilizar o RMS Management Pack
ms:assetid: 'd9a73ef0-2f81-48c2-97cc-deb7bf477389'
ms:contentKeyID: 18123780
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747688(v=WS.10)'
---

Importar e utilizar o RMS Management Pack
=========================================

Importando e utilizando o RMS Management Pack
---------------------------------------------

#### Importar e utilizar o RMS Management Pack

1.  Copie o RMS Management Pack (RMS\_MOMPack.akm) da pasta %Arquivos de programas%\\Windows Rights Management Services\\Ferramentas para o servidor MOM (Microsoft Operations Manager).

2.  Abra o console do Administrador do MOM e importe o RMS Management Pack utilizando as seguintes etapas:

    1.  Na árvore do console do Administrador do MOM, expanda o item **Regras** e clique com o botão direito do mouse no item **Processando grupos de regras**.
    2.  No menu de atalho, clique em **Importar Pacote de Gerenciamento**. A caixa de diálogo **Importar Pacote de Gerenciamento** é exibida.
    3.  Clique em **Procurar** e selecione o RMS\_MOMPack.akm.

3.  Especifique as opções de mesclagem ou substituição. Para obter mais informações sobre opções de mesclagem e substituição, consulte "Exporting and Importing Management Packs" no site da Microsoft (http://www.microsoft.com/).

    Clique em **Substituir**. A opção de substituição faz com que o pacote de gerenciamento importado substitua grupos de regra de processamento existentes; nenhum comentário do usuário é preservado. Se desejar mesclar esse pacote de gerenciamento com outro existente, você deve fazê-lo em um ambiente de teste e utilizar a opção **Substituir** quando implantar o pacote de gerenciamento no ambiente de produção.

4.  Clique em **Importar** para importar o pacote de gerenciamento.

5.  No console do **Administrador do MOM**, selecione o item **Configuração** e clique na pasta **Gerentes de Agentes**.

6.  Clique com o botão direito do mouse no nome do servidor para o qual você importou o RMS Management Pack e clique em **Verificar Computadores Gerenciados Agora**.
