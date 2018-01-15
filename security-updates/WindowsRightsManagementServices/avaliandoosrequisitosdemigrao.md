---
TOCTitle: Avaliando os requisitos de migração
Title: Avaliando os requisitos de migração
ms:assetid: 'cec07f45-dc52-4004-860b-5cc33e5fc209'
ms:contentKeyID: 18123849
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747759(v=WS.10)'
---

Avaliando os requisitos de migração
===================================

As organizações que implantam o RMS precisam estabelecer um plano de migração que minimize o tempo de inatividade do servidor de modo que os cenários de manutenção e atualização não acarretem interrupção do acesso do usuário ao conteúdo protegido pelo RMS. Como os bancos de dados de configuração e log anteriores podem ser usados pelo RMS, a migração do RMS de um servidor para outro deverá provocar impacto mínimo na organização se forem utilizados os procedimentos corretos. O cenário da migração pressupõe que você deseja usar os bancos de dados existentes; caso contrário, você executaria uma nova instalação do RMS.

Se o servidor RMS que está sendo substituído usar um módulo de segurança de hardware (HSM), como o nCipher, você deverá transferir a configuração do HSM para o novo servidor antes de instalar e configurar o RMS no servidor. Para obter instruções, consulte a documentação do módulo de segurança de hardware.

Antes de migrar:

-   Certificar-se de que os bancos de dados estão disponíveis;
-   Definir que computadores serão usados na nova instalação.

Para fazer a migração da instalação do RMS, execute as seguintes etapas:

1.  Faça o backup de todos os componentes antes de iniciar a migração, o que inclui o backup de bancos de dados, chaves particulares e estado do sistema.
2.  Assegure-se de que os bancos de dados da instalação anterior do RMS estão presentes no servidor de banco de dados que será usado na nova implantação.
3.  Instale e configure o RMS nos servidores adequados e especifique a localização dos bancos de dados.

Um cenário comum de migração do servidor RMS é a mudança de uma implantação piloto do RMS para um ambiente de produção. Para obter mais informações sobre esse cenário de uso, consulte “Migrando uma implantação piloto para uma implantação de produção” em “Implantando o RMS” nesta coleção de documentos.
