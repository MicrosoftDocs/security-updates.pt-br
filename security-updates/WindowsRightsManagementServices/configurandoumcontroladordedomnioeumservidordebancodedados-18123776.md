---
TOCTitle: Configurando um controlador de domínio e um servidor de banco de dados
Title: Configurando um controlador de domínio e um servidor de banco de dados
ms:assetid: 'd20f8305-9f9e-4760-bfbf-82824db60d1f'
ms:contentKeyID: 18123776
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747681(v=WS.10)'
---

Configurando um controlador de domínio e um servidor de banco de dados
======================================================================

Antes de instalar um servidor raiz de certificação ou um servidor de licenciamento, certifique-se de que você implementou o suporte a domínio e a banco de dados apropriado, usando o Active Directory e o servidor de banco de dados, como o SQL Server 2000 com Service Pack 3 (SP3) ou o Microsoft® SQL Server 2000 Desktop Engine (MSDE 2000) Versão A. Mesmo que o seu ambiente de produção já esteja executando os componentes necessários, é recomendável que você não use o ambiente de produção para testes.

Os procedimentos a seguir configuram um controlador de domínio e um servidor de banco de dados em um único computador em uma rede isolada para fins de testes do lado do servidor.

| ![](images/Cc747681.note(WS.10).gif)Observação                                                                                                                                                                                                                                                                                                                                |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Neste exemplo, o servidor do banco de dados é executado no controlador de domínio. Em um ambiente de produção, geralmente não se recomenda hospedar outros componentes em um controlador de domínio. Neste exemplo, o Active Directory e o servidor do banco de dados são instalados no mesmo computador para habilitar a instalação da infra-estrutura completa em uma quantidade mínima de computadores. |

Se você optar por usar o MSDE 2000 como servidor de banco de dados, deve estar ciente de que ele não oferece suporte para qualquer interface de rede e que os termos de uso do MSDE 2000 especificam que não é possível usar as ferramentas de cliente do SQL Server para manipular um banco de dados MSDE. Com essa restrição não será possível exibir informações de log ou alterar dados armazenados no banco de dados de configuração. Portanto, é recomendável usar o MSDE 2000 apenas para oferecer suporte a bancos de dados do RMS em ambientes de teste.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Componente de infra-estrutura</th>
<th style="border:1px solid black;" >Etapas para configurar um controlador de domínio e um servidor de banco de dados</th>
<th style="border:1px solid black;" >Observações sobre a implantação em um ambiente de produção</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Sistema operacional</td>
<td style="border:1px solid black;">Em um computador que atenda aos requisitos mínimos de hardware do RMS mas que ainda não esteja conectado a uma rede, instale o Windows 2000 Server com SP3 ou posterior ou o Windows Server 2003. Use o sistema de arquivos NTFS na partição.</td>
<td style="border:1px solid black;">É altamente recomendável que você sempre instale o service pack e as atualizações mais recentes. Utilize partições com formato NTFS.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Conexão em rede</td>
<td style="border:1px solid black;">Estabeleça uma conexão com uma rede que forneça conectividade com a Internet, mas que esteja isolada do ambiente de produção.</td>
<td style="border:1px solid black;">A conexão com a Internet deve ter uma firewall apropriada.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Endereço IP</td>
<td style="border:1px solid black;">Atribua um endereço IP estático a esse computador.</td>
<td style="border:1px solid black;">Sempre utilize endereços IP estáticos para servidores.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Active Directory</td>
<td style="border:1px solid black;">Faça logon como um administrador local.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Clique em <strong>Iniciar</strong>, clique em <strong>Executar</strong>, digite <code>dcpromo</code> na caixa <strong>Abrir</strong> e depois clique em <strong>OK</strong>.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Quando o assistente de instalação do Active Directory for iniciado, percorra as telas do assistente para criar um domínio novo em uma nova floresta e aceitar as opções padrão, com exceção das seguintes opções:
Especifique o nome do domínio, por exemplo, especifique contoso.com.
Deixe o assistente configurar o DNS no computador.
Selecione <strong>Permissões compatíveis somente com servidores Windows 2000</strong> se todos os controladores de domínio estiverem sendo executados em Windows 2000 ou posterior.
Forneça uma senha segura para o administrador local.</td>
<td style="border:1px solid black;">Se novos domínios forem necessários para implementar o RMS, configure-os no Active Directory.
Sempre utilize senhas de segurança para todas as contas.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Reinicie o computador quando for solicitado.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Verifique o nível funcional abrindo o snap-in <strong>Usuários e Computadores do Active Directory</strong>, clicando com o botão direito do mouse no nome do domínio, clicando em <strong>Propriedades</strong> e verificando a definição que está na caixa <strong>Modo de operação de domínio</strong>. Se não houver controladores de domínio anteriores aos do Windows 2000, clique em <strong>Alterar modo</strong> para que o domínio opere no <strong>Modo nativo</strong>.
Observação: No Windows Server 2003, a configuração <strong>Modo de operação de domínio</strong> foi substituída por <strong>Nível funcional de domínio</strong>.</td>
<td style="border:1px solid black;">Para obter segurança e flexibilidade de gerenciamento máximas, você não deve usar o nível funcional misto do Windows 2000 para suporte a RMS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Contas de usuário</td>
<td style="border:1px solid black;">Crie uma conta de usuário do domínio para usar como conta de serviço RMS para o RMS, como ContosoRMS@contoso.com. Especifique uma senha segura. Lembre-se de especificar um endereço de email para o usuário. Se o endereço de email não for especificado no Active Directory, o usuário não poderá obter licenças e certificados do RMS.
Observação: A conta de serviço RMS não pode ser a mesma conta do domínio utilizada para instalar o RMS.</td>
<td style="border:1px solid black;">Crie uma conta separada no Active Directory para ser utilizada pela conta de serviço RMS. Inclua um endereço de email. Não forneça à conta permissões especiais.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQL Server 2000</td>
<td style="border:1px solid black;">Faça logon no servidor no qual você pretende instalar o banco de dados. Se esse for o mesmo servidor que o controlador de domínio, faça logon como administrador de domínio.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Siga as instruções fornecidas com o software do banco de dados para instalar o software de servidor do banco de dados.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Use as práticas recomendadas do servidor para instalar o servidor do banco de dados, tais como:
<ul>
<li>Fornecer um nome para a conta de administrador do sistema do banco de dados e um nome de organização como, por exemplo, Contoso.<br />
<br />
</li>
<li>Fornecer uma senha de administrador de sistema segura.<br />
<br />
</li>
<li>Usar métodos de autenticação integrada do Windows.<br />
<br />
</li>
</ul></td>
<td style="border:1px solid black;">Você deve usar um Modo de Autenticação do Windows integrado. Se você não puder executar o servidor do banco de dados nesse modo, contate o administrador do domínio e o administrador do servidor do banco de dados para determinar quais alterações poderão ser necessárias na configuração do RMS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Verifique se o serviço do banco de dados foi interrompido.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Instale as atualizações de software existentes para o servidor de banco de dados. Quando for solicitado que você informe uma senha, use a mesma senha que especificou durante a instalação.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Reinicie o computador. Verifique se o serviço do banco de dados foi iniciado.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Verifique se as contas de usuário possuem atributos de endereço de email válidos no Active Directory.</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">Certifique-se de que o usuário do domínio que administrará o RMS (e configurará os servidores raiz de certificação e os servidores de licenciamento) possui as permissões necessárias no servidor do banco de dados. Se você estiver usando o SQL Server como servidor de banco de dados, poderá adicionar uma identificação de logon para o usuário que está usando o snap-in <strong>SQL Server Enterprise Manager</strong>. No snap-in, expanda o servidor e o grupo de servidores e depois expanda o item <strong>Segurança</strong>. Clique no item <strong>Logons</strong>, adicione um novo logon para a conta do domínio do usuário, clique na guia <strong>Funções do Servidor</strong> e depois marque a caixa de seleção <strong>Administradores de servidor</strong>.</td>
<td style="border:1px solid black;">Importante: Todos os usuários e grupos que usam o RMS para adquirir licenças e publicar conteúdo devem ter um endereço de email configurado na conta no snap-in do MMC para Usuários e Grupos do Active Directory, na guia <strong>Geral</strong> do usuário <strong>Propriedades</strong>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Conexão com a Internet
(opcional)</td>
<td style="border:1px solid black;">Verifique se o navegador e o servidor (incluindo as configurações necessárias do servidor proxy), TCP/IP e LMHOSTS/HOSTS estão configurados corretamente para acessar a Internet. Teste isso acessando http://uddi.microsoft.com. Se você conseguir abrir essa página, isto significa que o RMS pode se conectar ao Microsoft Enrollment Service.</td>
<td style="border:1px solid black;">Vá até http://uddi.microsoft.com para verificar o acesso à Internet.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Atualizações de software</td>
<td style="border:1px solid black;">Baixe e instale as atualizações mais recentes para o software que se encontra instalado nesse computador (incluindo as atualizações mais recentes do Windows em www.microsoft.com).</td>
<td style="border:1px solid black;">Sempre baixe e instale as atualizações de serviços mais recentes.</td>
</tr>
</tbody>
</table>
  
Depois de passar por todas essas etapas, você estará pronto para fazer a configuração inicial (inclusive a instalação do software de pré-requisito) em computadores que executarão o RMS.
