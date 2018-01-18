---
TOCTitle: Preparando a instalação do servidor raiz de certificação
Title: Preparando a instalação do servidor raiz de certificação
ms:assetid: 'ed51605e-8b17-4155-8d83-f6777f499b7b'
ms:contentKeyID: 18123889
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747726(v=WS.10)'
---

Preparando a instalação do servidor raiz de certificação
========================================================

Na instalação teste do exemplo, há somente um servidor raiz de certificação. Caso deseje, você poderá configurar servidores adicionais, como parte de um cluster raiz de certificação ou como um cluster do servidor de licenciamento separado. A configuração da infra-estrutura para todos os servidores é a mesma, portanto você terá que executar o procedimento fornecido nesse tópico em cada um desses servidores.

Depois de instalar o controlador de domínio e configurar os servidores de banco de dados (conforme indicado na seção anterior) e, em seguida, concluir as etapas da tabela a seguir, você estará pronto para instalar o RMS.

###  

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Componente de infra-estrutura</th>
<th style="border:1px solid black;" >Preparar o servidor para a instalação do RMS</th>
<th style="border:1px solid black;" >Observações sobre a implantação em um ambiente de produção</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Sistema operacional</td>
<td style="border:1px solid black;">Em um computador que atenda aos requisitos mínimos de hardware do RMS mas que ainda não esteja conectado a uma rede, instale o sistema operacional Windows Server 2003 e use o sistema de arquivos NTFS para a partição.</td>
<td style="border:1px solid black;">É altamente recomendável que você sempre instale o service pack e os patches mais recentes. Utilize partições com formato NTFS.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Conexão com a Internet
(opcional)</td>
<td style="border:1px solid black;">Faça uma conexão Ethernet com uma rede que ofereça conectividade com a Internet, mas que seja isolada do ambiente de produção. Se você for usar o registro online para registrar o servidor RMS como parte do processo de configuração, o servidor deverá ter conectividade com a Internet.</td>
<td style="border:1px solid black;">Se você estiver usando o registro online, certifique-se de que a conexão com a Internet dispõe de um firewall apropriado.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Endereço IP</td>
<td style="border:1px solid black;">Atribua um endereço IP estático a esse computador.</td>
<td style="border:1px solid black;">Sempre utilize endereços IP estáticos para servidores.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Adicione esse computador ao domínio</td>
<td style="border:1px solid black;">Faça logon no computador como administrador local. Clique em <strong>Iniciar</strong>, clique com o botão direito do mouse em <strong>Meu computador</strong>, clique em <strong>Propriedades</strong>, clique na guia <strong>Nome do Computador</strong> e clique em <strong>Alterar</strong>.</td>
<td style="border:1px solid black;">Utilize o mesmo domínio para todos os servidores.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Deixe o nome do computador como está, clique em <strong>Domínio</strong> e digite o nome do domínio, por exemplo, digite Contoso.com e clique em <strong>OK</strong>. Forneça as credenciais do usuário que lhe permitam adicionar ao domínio, clique em <strong>OK</strong> e reinicie o computador quando for solicitado. Depois que o computador reiniciar e for solicitado que você informe suas credenciais de logon, forneça o domínio, o nome de usuário e a senha apropriados.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Usuário e logon</td>
<td style="border:1px solid black;">Clique com o botão direito do mouse em <strong>Meu computador</strong>, clique em <strong>Gerenciar</strong>, expanda <strong>Usuários e Grupos Locais</strong>, clique em <strong>Grupos</strong> e clique duas vezes em <strong>Administradores</strong>.
Clique em <strong>Adicionar</strong>, especifique o nome da conta do usuário a ser adicionada (como Michael@contoso.com) e, em seguida, clique em <strong>OK</strong>. Forneça privilégios ao Administrador da conta do usuário. Quando lhe solicitarem credenciais, forneça as credenciais apropriadas, por exemplo, Contoso\Administrador.
Faça o logon como usuário do domínio com privilégios de administrador no computador.</td>
<td style="border:1px solid black;">É preciso ter direitos de administrador para adicionar componentes a esse computador. Algumas etapas da instalação não podem ser concluídas utilizando a conta do administrador local. É preciso ter pelo menos um usuário do domínio nesse servidor que seja administrador. Além disso, o SQL Server requer direitos de administrador do sistema para criar novos bancos de dados.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Conexão com a Internet
(opcional)</td>
<td style="border:1px solid black;">Usando um navegador da Internet, vá até http://uddi.microsoft.com/ a fim de verificar o acesso à Internet. Nos computadores que executam o Windows Server 2003, é possível que os arquivos Lmhosts e Hosts precisem ser alterados para incluir o controlador de domínio.</td>
<td style="border:1px solid black;">Vá até http://uddi.microsoft.com para verificar o acesso à Internet.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Ativação do Windows</td>
<td style="border:1px solid black;">Você pode usar o Assistente para Ativação para ativar o Windows junto à Microsoft, usando uma conexão com a Internet, ou pode ativar o Windows por telefone. Para obter mais informações sobre a ativação do produto Windows Server 2003, consulte o Centro de ajuda e suporte do Windows Server 2003.</td>
<td style="border:1px solid black;">O Windows Server 2003 deve ser ativado dentro de 14 dias da instalação.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Atualizações de software</td>
<td style="border:1px solid black;">Certifique-se de instalar as atualizações mais recentes para o software que está instalado nesse computador.</td>
<td style="border:1px solid black;">Instale as atualizações de software mais recentes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Configure o Internet Explorer</td>
<td style="border:1px solid black;">O RMS utiliza uma interface da Web para administração. Algumas das configurações padrão de segurança podem impedir que as páginas sejam processadas corretamente. Algumas páginas do site Administração do RMS usam janelas pop-up para algumas opções de configuração.</td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
Após concluir todas as etapas anteriores nos dois servidores, você estará pronto para instalar e configurar o RMS nos servidores.
