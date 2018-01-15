---
TOCTitle: Habilitando o suporte do RMS para serviços de servidor
Title: Habilitando o suporte do RMS para serviços de servidor
ms:assetid: '6288323c-0638-41b6-bef8-67a7c9433424'
ms:contentKeyID: 18123693
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747593(v=WS.10)'
---

Habilitando o suporte do RMS para serviços de servidor
======================================================

O RMS também pode fornecer certificados de conta de direitos e usar licenças para aplicativos de servidor habilitados para RMS. Ao configurar os serviços de servidor, você deve estar ciente do seguinte:

-   Por padrão, as DACLs (listas de controle de acesso discricionário) existentes nos pipelines do RMS usam as configurações mais seguras. Você deve modificar a DACL ao usar serviços do servidor do RMS.
-   Se o cliente do RMS estiver instalado em um servidor baseado no Windows Server 2003 e a Configuração de Segurança Reforçada do Internet Explorer estiver habilitada, você deverá adicionar a URL do cluster do RMS à Zona de Sites Confiáveis do Internet Explorer.
-   Muitos serviços de servidor usam a funcionalidade avançada de serviços de diretório do Active Directory, que só fica disponível se todos os controladores de domínio do Active Directory executarem o Windows Server 2003. Caso você esteja usando algum serviço de servidor (como o Microsoft Office SharePoint Server 2007 ou o Microsoft Exchange Server 2007, por exemplo), é recomendável que todos os controladores de domínio estejam executando o Windows Server 2003 e que os níveis funcionais do Active Directory no domínio e na floresta estejam no nível do Windows Server 2003.

DACL padrão no pipeline de certificação do servidor
---------------------------------------------------

Aplicativos como o Microsoft Office SharePoint Server 2007 ou o Microsoft Exchange Server 2007 são habilitados para RMS para solicitar licenças de uso em nome de usuários. Em uma instalação padrão do RMS, a DACL do pipeline de certificação do servidor do RMS é restrita, ou seja, um aplicativo não pode obter certificados e licenças para seus usuários. Entretanto, se você tiver um aplicativo habilitado para RMS nesses computadores, poderá habilitá-los para participar do sistema RMS configurando as DACLs no pipeline de certificação do servidor do RMS.

Os aplicativos de servidor habilitados para RMS se conectarão ao serviço de certificação do RMS utilizando o arquivo ServerCertification.asmx.

Quando o RMS cria esses arquivos, as DACLs deles são definidas para somente permitir acesso de processos do sistema. É recomendável que você crie um grupo de segurança do Active Directory para os serviços de servidor e o preencha com os objetos do Active Directory dos computadores que estão solicitando licenças de uso em nome de seus usuários.

Depois de criar o grupo, você poderá modificar a DACL do arquivo ServerCertification.asmx para conceder ao grupo permissão para Ler e Executar no serviço. Você também deve adicionar o Grupo de Serviço RMS à DACL com a permissão Ler e Executar.

| ![](images/Cc747593.note(WS.10).gif)Observação                                                                      |
|--------------------------------------------------------------------------------------------------------------------------------------------------|
| Se houver mais de um servidor do RMS no cluster, será necessário alterar a DACL do arquivo ServerCertification.asmx em cada servidor do cluster. |

No Microsoft Exchange Server 2007, o objeto de computador do Active Directory de cada servidor bridgehead do Exchange deve ser adicionado ao grupo de serviços do servidor. Se isso não for feito, o servidor bridgehead do Exchange não conseguirá solicitar licenças em nome dos usuários que receberam o email.

No caso do Office SharePoint Server 2007, você deve adicionar o objeto de computador do Active Directory do servidor que executa o Office SharePoint Server 2007 ao grupo de serviços do servidor. Se o servidor do Office SharePoint Server 2007 estiver configurado para usar o servidor padrão no Active Directory, você deverá adicionar o Grupo de Serviço RMS e o grupo criado para serviços de servidor ao arquivo ServiceLocater.asmx e conceder permissão para Ler e Executar.

| ![](images/Cc747593.Important(WS.10).gif)Importante                                                                                                                                                       |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| É necessário reiniciar o IIS (Serviços de Informações da Internet) depois de alterar a DACL nos arquivos ServerCertification.asmx e ServiceLocater.asmx. Para redefinir o IIS, execute o comando **iisreset** em um prompt de comando. |
