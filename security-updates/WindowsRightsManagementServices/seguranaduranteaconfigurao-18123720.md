---
TOCTitle: Segurança durante a configuração
Title: Segurança durante a configuração
ms:assetid: '9f1282c5-5642-4870-a9a4-c3a485f8ff76'
ms:contentKeyID: 18123720
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747616(v=WS.10)'
---

Segurança durante a configuração
================================

Você pode usar o site de Administração do RMS para configurar os recursos do RMS em um site já existente. Durante a configuração, são criados diretórios virtuais e pools de aplicativos nesse site, e os bancos de dados do RMS são criados e configurados em um servidor de banco de dados. Opcionalmente, se o servidor estiver conectado à Internet, ele poderá ser registrado com o Microsoft Enrollment Service durante o processo de configuração.

Durante a configuração, o RMS usa as contas descritas na tabela apresentada a seguir.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Conta</th>
<th style="border:1px solid black;" >Objetivo</th>
<th style="border:1px solid black;" >Permissões</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Conta do usuário conectado</td>
<td style="border:1px solid black;">Cria diretórios virtuais e pools de aplicativos. O Serviços de Informações da Internet (IIS) requer a autenticação do Windows, e o RMS representa o usuário conectado, que deve estar conectado localmente.</td>
<td style="border:1px solid black;">Controle total (o usuário conectado deve ser um administrador local).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Conta do sistema</td>
<td style="border:1px solid black;">Constrói a montagem temporária para serialização.</td>
<td style="border:1px solid black;">Permissões de leitura e gravação para a pasta temporária do Windows, C:\Windows\Temp.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Conta ASPNET</td>
<td style="border:1px solid black;">Cria a montagem temporária dos arquivos *.aspx.</td>
<td style="border:1px solid black;">Acesso ao diretório temporário de cache de montagem, C:\Windows\Microsoft.NET\Framework\v1.1.4322\Arquivos ASP.NET temporários, por padrão.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Conta dos serviços de rede</td>
<td style="border:1px solid black;">Registra o ponto de conexão do serviço no Active Directory.</td>
<td style="border:1px solid black;"><ul>
<li>Permissões somente leitura para o site de configuração (normalmente C:\Inetpub\Wwwroot\Provisioning).<br />
<br />
</li>
<li>Permissões de leitura e gravação para a chave do Registro <strong>DRMS</strong>. As permissões são concedidas pela instalação do RMS, que também cria a chave de Registro apresentada a seguir.<br />
<br />
Em computadores que executam a versão de 32 bits do Windows Server 2003<br />
<br />
<code>HKEY_LOCAL_MACHINE\Software\Microsoft\DRMS\1.0</code><br />
<br />
Em computadores que executam a versão de 64 bits do Windows Server 2003<br />
<br />
<code>HKEY_LOCAL_MACHINE\Software\WOW6432Node\Microsoft\DRMS\1.0</code><br />
<br />
</li>
</ul></td>
</tr>
</tbody>
</table>
 

Durante a configuração, o RMS executa as seguintes tarefas:

-   No servidor de banco de dados:
    -   Cria configuração, serviços de diretório e bancos de dados de log.
    -   Concede permissões de logon para o grupo de serviço do RMS.
    -   Instala procedimentos armazenados nos bancos de dados e concede permissões de execução ao grupo de serviço do RMS.
    -   Executa consultas no banco de dados mestre.
-   Adiciona o grupo de serviço do RMS ao grupo IIS\_WPG.
-   No diretório C:\\Inetpub\\Wwwroot\\\_wmcs, cria uma hierarquia de diretórios virtuais, arquivos e pools de aplicativos para os serviços na Web e o site de Administração do RMS.
-   Define listas de controle de acesso condicionais nos diretórios virtuais, arquivos e pools de aplicativos.
-   Para o grupo de serviço do RMS, concede acesso à pasta temporária.
-   Quando você especifica proteção de chave de software, criptografa a chave particular de licenciante para servidor antes de armazená-la no banco de dados. O RMS solicita uma senha durante a configuração e ganha acesso à DPAPI (Data Protection API) do nível da máquina.
-   Instala o serviço ouvinte do registro.
-   Cria uma fila de mensagens de registro.
-   Ao configurar o servidor raiz de certificação, configura o ponto de conexão de serviço no Active Directory.
