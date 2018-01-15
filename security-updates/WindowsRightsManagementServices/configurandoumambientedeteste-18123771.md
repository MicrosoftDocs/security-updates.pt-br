---
TOCTitle: Configurando um ambiente de teste
Title: Configurando um ambiente de teste
ms:assetid: 'cdd96b05-49e2-4b6f-bfae-40b5c028ec66'
ms:contentKeyID: 18123771
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747673(v=WS.10)'
---

Configurando um ambiente de teste
=================================

O RMS integra-se à infra-estrutura do Active Directory e aos servidores de bancos de dados existentes, como aqueles que executam o Microsoft SQL Server™ 2000. Devido à natureza crítica desses componentes de suporte, você deve fazer um teste completo no RMS em um ambiente de teste isolado antes de implantá-lo na organização. Isso exige que você configure instalações de Active Directory e de servidores de bancos de dados separadas no ambiente de teste.

Inicie pela configuração mais básica de um servidor RMS em uma floresta com um servidor de banco de dados e um cliente. Quando você se familiarizar com o RMS, a configuração poderá crescer até corresponder aproximadamente à topologia que você implantará no ambiente de produção da sua organização, adicionando várias florestas e acesso externo, se necessário. Mesmo que o ambiente de teste não inclua todas as configurações de redundância e de sites múltiplos do plano de implantação da organização, ele deve incluir pelo menos um servidor em execução de cada um dos componentes de suporte que você precisa implantar.

A lista a seguir descreve uma configuração mínima possível para um ambiente de teste que você pode usar para testar uma configuração básica para o RMS:

-   Um controlador de domínio que esteja executando o Windows 2000 Server com Service Pack 3 (SP3) ou posterior, bem como o SQL Server 2000 com SP3a instalado. O SQL Server hospeda os bancos de dados de log, configuração e de serviços de diretório do RMS. O RMS poderá ser usado com o Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Versão A ou com o SQL Server se o banco de dados estiver no mesmo servidor que o RMS. Se você for utilizar um servidor remoto para suporte ao banco de dados, o SQL Server será necessário. Você pode baixar o MSDE 2000 do site da Microsoft.

| ![](images/Cc747673.note(WS.10).gif)Observação                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| O Windows 2000 Server com Service Pack 3 (SP3) é o requisito mínimo para o controlador de domínio, mas recomenda-se o Windows Server 2003 devido a melhorias no desempenho da expansão de grupo do Active Directory. É recomendável que o MSDE 2000 seja usado para oferecer suporte aos bancos de dados RMS somente em ambientes de teste porque o MSDE 2000 não oferece suporte a nenhuma interface de rede. Além disso, os termos de uso do MSDE 2000 especificam que você não pode usar ferramentas de cliente do SQL Server para manipular o MSDE 2000. Com essa restrição, não será possível exibir informações de log ou alterar dados armazenados no banco de dados de configuração. |

-   Um servidor raiz de certificação que esteja executando o Windows Server 2003, no qual o RMS esteja instalado e configurado. Você poderá adicionar mais servidores para criar um cluster raiz de certificação, durante a execução do teste, se desejar.
-   Um computador cliente que esteja executando Windows XP Professional, um cliente do RMS e um aplicativo habilitado para RMS.
-   Contas de usuário que possuam atributos de endereço de email no Active Directory.

Para obter mais informações sobre a instalação e a configuração de uma infra-estrutura básica do RMS e também sobre como aplicar os requisitos de infra-estrutura a um ambiente de produção, consulte "[Configurando uma infra-estrutura básica](https://technet.microsoft.com/3a0a3a47-e755-4455-bb22-0e05053723e4)" mais adiante neste tema.
