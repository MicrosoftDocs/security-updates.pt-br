---
TOCTitle: 'Perguntas freqüentes sobre o RMS: Considerações de segurança'
Title: 'Perguntas freqüentes sobre o RMS: Considerações de segurança'
ms:assetid: 'ff433834-79aa-481f-bd39-3393be12a26f'
ms:contentKeyID: 18123844
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747757(v=WS.10)'
---

Perguntas freqüentes sobre o RMS: Considerações de segurança
============================================================

Perguntas freqüentes sobre considerações de segurança do RMS
------------------------------------------------------------

-   [O que é a conta do superusuário?](#bkmk_43)
-   [O RMS é uma solução de segurança?](#bkmk_44)
-   [Que mecanismos estão sendo usados para evitar que os destinatários atrasem os relógios dos computadores cliente com a finalidade de estender o acesso a documentos protegidos por direitos depois que as licenças de uso expirarem?](#bkmk_45)
-   [É possível que membros do grupo Admins. do Domínio leiam documentos destinados a alguém de seus domínios?](#bkmk_46)
-   [Sei que todos os cofres podem autenticar todos os certificados ou licenças gerados dentro do sistema, como se tivessem vindo de um serviço registrado com a Microsoft. Contra que ameaça essa proteção funciona?](#bkmk_47)
-   [Se alguém conseguir abrir um documento utilizando ataque de força bruta, isso permitirá que outros documentos sejam abertos com essa chave?](#bkmk_48)
-   [Devido às restrições do governo sobre tecnologias de criptografia, alguma parte das chaves está exposta fora da organização que as implantou?](#bkmk_49)
-   [Como se impede que invasores ativem o recurso de descomissionamento remotamente?](#bkmk_50)
-   [Um usuário pode realizar capturas de tela de conteúdo protegido por direitos?](#bkmk_51)
-   [Os administradores que fazem o backup dos arquivos relacionados ao RMS podem obter acesso a conteúdo protegido por direitos?](#bkmk_52)
-   [O arquivo de permuta que o Windows usa contém conteúdo não criptografado em algum ponto, podendo deixar o conteúdo "aberto"?](#bkmk_53)
-   [É possível limitar que administradores podem acessar os diferentes recursos administrativos do RMS?](#bkmk_54)
-   [O RMS pode proteger documentos individuais assim que eles são criados no disco rígido do usuário ou em uma pasta compartilhada?](#bkmk_55)
-   [Na abertura de um arquivo, os arquivos de salvamento automático e os arquivos temporários estão criptografados?](#bkmk_56)
-   [Quando recebo um email protegido por direitos, parece que existe um anexo incluído no email. Posso salvar o anexo, embora o email supostamente não possa ser salvo. Meu RMS está com problemas?](#bkmk_562)

<span id="BKMK_43"></span>
#### O que é a conta do superusuário?

O RMS oferece suporte a um grupo especial de superusuários que tem controle total sobre todo o conteúdo protegido por direitos. Os membros do grupo de superusuários recebem direitos completos de proprietário em todas as licenças de uso emitidas para eles pelo cluster do RMS no qual o grupo de superusuários está configurado. Isso significa que os membros desse grupo podem descriptografar todos os arquivos protegidos e remover sua proteção. Por exemplo, um membro desse grupo pode remover a proteção de arquivos publicados por um funcionário que saiu da empresa, para que um novo proprietário possa publicar e gerenciar os arquivos.

<span id="BKMK_44"></span>
#### O RMS é uma solução de segurança?

Não, o RMS não é uma solução de segurança. Quando usado com um aplicativo habilitado para RMS, como o Office 2007, ele pode ser considerado uma "solução de imposição de diretivas". Se o usuário não estiver autorizado a exibir os dados, ele poderá usar um ataque de força bruta para tentar quebrar a criptografia. Apesar de a criptografia ser robusta, como todos os esquemas de criptografia de software, ela pode ser quebrada. No entanto, se o usuário tiver o direito de exibir os dados, poderá copiá-los manualmente ou fazer uma fotografia digital e fornecer as informações a usuários não autorizados.

<span id="BKMK_45"></span>
#### Que mecanismos estão sendo usados para evitar que os destinatários atrasem os relógios dos computadores cliente com a finalidade de estender o acesso a documentos protegidos por direitos depois que as licenças de uso expirarem?

O RMS detectará se o relógio de um sistema cliente foi atrasado ou adiantado e evitará que o usuário consuma o conteúdo. Além disso, o RMS detectará se existe uma diferença horária mensurável entre o servidor e o cliente do RMS.

<span id="BKMK_46"></span>
#### É possível que membros do grupo Admins. do Domínio leiam documentos destinados a alguém de seus domínios?

Membros do grupo de Admins. do Domínio podem ler o conteúdo protegido de uma conta de usuário se forem membros do grupo de superusuários do RMS ou se estiverem representando a conta do usuário. Como os membros do grupo de Admins. do Domínio têm controle sobre as contas de usuários no domínio, não há como atenuar o impacto causado por um membro não confiável desse grupo.

A prática recomendada é adicionar membros do grupo de Admins. do Domínio ao grupo de superusuários se eles precisarem ter acesso a conteúdo protegido por direitos. Quando uma licença é concedida a um membro do grupo de superusuários, uma identificação de evento 49 é registrada no log de eventos Aplicativo do servidor RMS. A identificação de evento 49 indica que **"Uma licença foi concedida a um usuário pertencente ao grupo de superusuários. O usuário tem o seguinte endereço de email: &lt;Alias do Usuário&gt;”** em que **Alias do usuário** é substituído pela conta de email do usuário.

Da mesma forma que outros grupos possuem limite de acesso aos recursos, você deve definir alertas e realizar verificações de segurança para evitar que alguém se associe ao grupo de superusuários sem autorização.

<span id="BKMK_47"></span>
#### Sei que todos os cofres podem autenticar todos os certificados ou licenças gerados dentro do sistema, como se tivessem vindo de um serviço registrado com a Microsoft. Contra que ameaça essa proteção funciona?

Se você não puder verificar a integridade dos certificados, um usuário poderá falsificar um certificado de conta de direitos emitido para outro usuário e obter uma licença de uso para conteúdo ou criar um aplicativo que remova a proteção de um documento.

<span id="BKMK_48"></span>
#### Se alguém conseguir abrir um documento utilizando ataque de força bruta, isso permitirá que outros documentos sejam abertos com essa chave?

Cada conteúdo protegido por direitos é criptografado com uma chave simétrica diferente, gerada aleatoriamente. Portanto, a chave de cada documento é exclusiva e não serve para descriptografar outros documentos.

<span id="BKMK_49"></span>
#### Devido às restrições do governo sobre tecnologias de criptografia, alguma parte das chaves está exposta fora da organização que as implantou?

Os aplicativos assinados na raiz da Microsoft estão sujeitos à raiz de assinatura de chave da Microsoft, mas, desse ponto em diante, nenhuma outra chave será divulgada pela Microsoft nem pela implantação do cliente.

<span id="BKMK_50"></span>
#### Como se impede que invasores ativem o recurso de descomissionamento remotamente?

O invasor precisaria ter credenciais de uma conta de usuário com direitos administrativos ao cluster do RMS. Por padrão, a interface de administração do RMS está disponível somente localmente no servidor RMS. Se essa situação perdurar, se o protocolo RDP estiver desativado e se o servidor estiver fisicamente seguro, o risco será reduzido.

<span id="BKMK_51"></span>
#### Um usuário pode realizar capturas de tela de conteúdo protegido por direitos?

Se os direitos do RMS estiverem definidos para não permitir a funcionalidade de cópia, o recurso Alt+PrtSc do Windows será desativado pelo RMS. No entanto, em um ambiente com áreas de trabalho não gerenciadas, um usuário poderá usar produtos que não sejam da Microsoft para capturar conteúdo.

<span id="BKMK_52"></span>
#### Os administradores que fazem o backup dos arquivos relacionados ao RMS podem obter acesso a conteúdo protegido por direitos?

Não, eles podem realizar o backup, mas não têm acesso ao conteúdo.

<span id="BKMK_53"></span>
#### O arquivo de permuta que o Windows usa contém conteúdo não criptografado em algum ponto, podendo deixar o conteúdo "aberto"?

Depois que o cliente do RMS devolver o conteúdo descriptografado ao aplicativo, ele poderá ser exibido no arquivo de permuta. Parte das recomendações de desenvolvimento do aplicativo do RMS presentes no SDK (Software Development Kit) do Rights Management Services (RMS) inclui etapas para evitar essa ocorrência, mas a responsabilidade principal recai sobre o aplicativo habilitado para RMS.

<span id="BKMK_54"></span>
#### É possível limitar que administradores podem acessar os diferentes recursos administrativos do RMS?

Sim, você pode criar grupos diferentes de administradores do RMS no Active Directory, adicionar usuários e, em seguida, criar as listas de controle de acesso (ACLs) apropriadas para as páginas de administração. Por exemplo, a configuração padrão das ACLs da página da Web de administração do RMS especifica que a página de configuração de segurança só pode ser acessada pelo usuário que provisionou o servidor.

<span id="BKMK_55"></span>
#### O RMS pode proteger documentos individuais assim que eles são criados no disco rígido do usuário ou em uma pasta compartilhada?

Embora o RMS possa ser usado para proteger documentos armazenados em um computador local do usuário, o sistema de arquivos com criptografia (EFS) seria a melhor opção. O EFS protege os documentos de modo transparente, enquanto o RMS exige intervenção manual (alguns cliques do mouse) para proteger um documento.

<span id="BKMK_56"></span>
#### Na abertura de um arquivo, os arquivos de salvamento automático e os arquivos temporários estão criptografados?

Sim, todos os arquivos temporários estão criptografados.

<span id="BKMK_562"></span>
#### Quando recebo um email protegido por direitos, parece que existe um anexo incluído no email. Posso salvar o anexo, embora o email supostamente não possa ser salvo. Meu RMS está com problemas?

Não. Este é o comportamento esperado. O anexo que você vê é a mensagem criptografada antes que o cliente do RMS a tenha descriptografado. Ela ainda é uma mensagem protegida por direitos e não pode ser salva após ser descriptografada.
