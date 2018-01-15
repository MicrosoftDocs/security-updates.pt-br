---
TOCTitle: Aplicativos habilitados para RMS
Title: Aplicativos habilitados para RMS
ms:assetid: '30bb5565-81d3-43d9-a64d-cf0c5b990712'
ms:contentKeyID: 18123551
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720231(v=WS.10)'
---

Aplicativos habilitados para RMS
================================

Para criar ou consumir conteúdo protegido pelo RMS, os usuários devem ter instalado um aplicativo habilitado para RMS, conforme descrito neste tópico. Além disso, o cliente do RMS deve ser instalado, e os computadores que estão sendo usados devem ser ativados. Para obter mais informações, consulte "[Cliente do RMS](https://technet.microsoft.com/03294fa2-8350-430d-b4b0-03d5169937c2)" e "[Ativação de máquina do RMS](https://technet.microsoft.com/09a0d631-9860-477f-9d10-df61b3bfe125)", mais adiante neste tema.

Os aplicativos habilitados para RMS permitem que os autores de conteúdo acrescentem direitos de uso, sob a forma de licenças de publicação, aos arquivos que eles criam, a fim de controlar o modo como o conteúdo é consumido. Os aplicativos habilitados para RMS também processam as informações de arquivos criptografados e permitem que os usuários consumam o conteúdo de acordo com as permissões definidas na licença de publicação.

Ao usar o SDK do cliente do RMS, os desenvolvedores podem criar aplicativos habilitados para RMS que licenciam, publicam e consomem conteúdo protegido pelo RMS. Os aplicativos habilitados para RMS podem ser desenvolvidos para computadores que estão executando o Microsoft® Windows® 98 Second Edition ou posterior.

Os desenvolvedores também podem criar aplicativos de servidor habilitados para RMS, usando o SDK do cliente do RMS. Esses aplicativos podem publicar, mas não consumir, conteúdo.

Os usuários que não possuírem outro aplicativo habilitado para RMS disponível para o consumo de conteúdo protegido pelo RMS em emails e páginas da Web poderão obter e usar o complemento do Rights Management para Microsoft® Internet Explorer. Por exemplo, os clientes do Outlook Web Access (OWA) podem usar o complemento do Rights Management para Internet Explorer, a fim de consumir mensagens de email protegidas pelo RMS.

O complemento do RMS para o Internet Explorer está disponível para download no [site da Microsoft](http://go.microsoft.com/fwlink/?linkid=14450) (http://go.microsoft.com/fwlink/?LinkId=14450).

| ![](images/Cc720231.note(WS.10).gif)Observação                                                                                                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Se você estiver usando o complemento do Rights Management para Internet Explorer com o Windows XP Service Pack 2, a configuração avançada de segurança poderá causar alguns problemas de compatibilidade nos aplicativos. |

Se a URL de conexão da extranet de cada domínio da organização não for adicionada aos sites de Intranet local no Internet Explorer, os usuários que estiverem usando o complemento do RMS para Internet Explorer receberão mensagens repetidamente, perguntando se realmente desejam se conectar aos sites. Uma resposta incorreta a essas mensagens poderia fazer com que o cliente do RMS obtivesse um novo certificado de conta de direitos para a conta do usuário.

Com o intuito de definir esses sites corretamente em toda a organização, utilize um script para gravar as URLs necessárias no Registro como parte da zona da Intranet local. Por padrão, a zona da Intranet local fornece um nível de segurança suficientemente alto para eliminar as mensagens.
