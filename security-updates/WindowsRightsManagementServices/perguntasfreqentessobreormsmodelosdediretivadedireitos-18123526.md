---
TOCTitle: 'Perguntas freqüentes sobre o RMS: Modelos de diretiva de direitos'
Title: 'Perguntas freqüentes sobre o RMS: Modelos de diretiva de direitos'
ms:assetid: '01515f08-9844-4c1a-9ab5-a5a60a901b50'
ms:contentKeyID: 18123526
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720175(v=WS.10)'
---

Perguntas freqüentes sobre o RMS: Modelos de diretiva de direitos
=================================================================

Perguntas freqüentes sobre modelos do RMS
-----------------------------------------

-   [Eu posso impor um modelo padrão de RMS em todo o conteúdo criado dentro de uma organização, de modo que a empresa possa garantir um conjunto mínimo de direitos?](#bkmk_57)
-   [Onde estão localizados os modelos de diretivas de RMS?](#bkmk_58)
-   [Quando os modelos são criados, os alias dos usuários e as listas de distribuição estão vinculados a eles. Como uma organização com diversos departamentos pode fornecer modelos com os mesmos direitos básicos, mas conceder esses direitos a grupos diferentes dependendo do conteúdo?](#bkmk_59)
-   [Os direitos são aplicados a um documento estático? Se um arquivo for enviado e os direitos precisarem ser alterados posteriormente, isso poderá ser feito se a licença de publicação estiver incorporada ao arquivo e não ao servidor de "diretivas" do RMS?](#bkmk_60)

<span id="BKMK_57"></span>
#### Eu posso impor um modelo padrão de RMS em todo o conteúdo criado dentro de uma organização, de modo que a empresa possa garantir um conjunto mínimo de direitos?

Sim. Usando-se o SDK do RMS, poderia ser desenvolvido um aplicativo personalizado para impor os modelos necessários. No entanto, a implementação do Gerenciamento de Direitos de Informação (IRM) no Office 2003 ou posterior não oferece suporte à imposição de modelos ao conteúdo.

<span id="BKMK_58"></span>
#### Onde estão localizados os modelos de diretivas de RMS?

A localização dos modelos é determinada pelo aplicativo habilitado para RMS. No caso do Office 2003 ou posterior, eles são armazenados como uma configuração do usuário no Registro, no seguinte local:

**HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\11.0\\Common\\DRM\\AdminTemplatePath**

-ou-

**HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\12,0\\Common\\DRM\\AdminTemplatePath** para Microsoft Office 2007.

> [!Note]  
> Se essa entrada apontar para uma pasta local no cliente, os arquivos de modelo deverão ser copiados para o cliente. Se a entrada apontar para uma pasta compartilhada da rede, os modelos estarão indisponíveis quando o usuário estiver offline. 

<span id="BKMK_59"></span>
#### Quando os modelos são criados, os alias dos usuários e as listas de distribuição estão vinculados a eles. Como uma organização com diversos departamentos pode fornecer modelos com os mesmos direitos básicos, mas conceder esses direitos a grupos diferentes dependendo do conteúdo?

Existem duas soluções para esse cenário:

-   Crie um modelo único chamado de "Confidencial da empresa" que seja licenciado para todos os funcionários na sua unidade de negócios e, em seguida, use esse modelo no email e encaminhe-o a um grupo específico de pessoas. A vantagem é que isso exige um modelo único para cada unidade de negócios para envio de email e pode ser restrito a usuários com base nos destinatários. A desvantagem é que qualquer um de fora do grupo para o qual o modelo foi enviado originalmente ainda terá acesso de leitura a ele.
-   Como alternativa, crie diversos modelos, incluindo um para cada lista de distribuição. Embora essa medida proporcione um controle muito mais preciso, também significa que o departamento de TI deve oferecer suporte a diversos modelos.

<span id="BKMK_60"></span>
#### Os direitos são aplicados a um documento estático? Se um arquivo for enviado e os direitos precisarem ser alterados posteriormente, isso poderá ser feito se a licença de publicação estiver incorporada ao arquivo e não ao servidor de "diretivas" do RMS?

Sim, isso é possível quando um modelo de diretiva de RMS é usado: Quando o conteúdo é publicado usando um modelo de diretiva de RMS, a definição de diretiva permanece no servidor e pode ser alterada pelo administrador após a publicação do conteúdo. Quando o usuário solicita uma licença para o conteúdo, a licença concederá direitos de acordo com a diretiva atual, conforme estiver definido no servidor. Se os direitos forem alterados depois que uma licença de uso tiver sido emitida para um usuário, ele continuará usufruindo dos direitos válidos no momento em que a licença de uso foi emitida. Para permitir que você aplique um novo modelo de diretiva de direitos após a publicação do conteúdo, habilite uma diretiva de vencimento para o seu modelo e, em seguida, especifique a opção **As licenças de uso de conteúdo devem ser renovadas a cada: n dias**. Para "n", especifique o número de dias após o qual o usuário deverá solicitar uma nova licença de uso.
