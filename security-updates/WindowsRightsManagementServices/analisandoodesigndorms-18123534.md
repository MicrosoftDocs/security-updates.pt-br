---
TOCTitle: Analisando o design do RMS
Title: Analisando o design do RMS
ms:assetid: '0ed1dd67-8e07-47c9-9e2e-0104438bd19f'
ms:contentKeyID: 18123534
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720185(v=WS.10)'
---

Analisando o design do RMS
==========================

Antes de iniciar a implantação, certifique-se de que o plano do RMS trata das seguintes questões:

-   Foi selecionado um aplicativo cliente habilitado para RMS, e os planos de implementação estão corretos.
-   Foi determinado um método para distribuir o cliente do RMS.
-   Foi instalado um servidor de banco de dados e ele se encontra acessível.
-   Foi selecionada uma topologia do RMS, seja ela básica ou distribuída.
-   O Active Directory encontra-se instalado em controladores de domínio que executam o Windows 2000 com o Service Pack 3 (SP3) ou posterior, e todos os usuários possuem um objeto de contato com um atributo de email configurado. O Windows Server 2003 foi instalado com as atualizações mais recentes. O Enfileiramento de Mensagens, o IIS (Serviços de Informações da Internet) e o ASP.NET versão 1.1 estão habilitados.

| ![](images/Cc720185.note(WS.10).gif)Observação                                                                                                                                                            |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Se você planeja instalar o RMS em um computador de 64 bits, consulte "Requisitos de software para o RMS" em "Planejando uma implantação do RMS", nesta coleção de documentos, a fim de obter instruções sobre configurações especiais. |

-   Foram definidos os métodos de falha do servidor e de balanceamento de carga.
-   O registro do DNS foi configurado para os servidores RMS.
-   Os planos de backup e de recuperação estão corretos.
-   As considerações sobre segurança apropriadas à sua organização foram concluídas.
