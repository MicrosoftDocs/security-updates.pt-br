---
TOCTitle: Requisitos de software para o RMS
Title: Requisitos de software para o RMS
ms:assetid: '17faf2ad-2366-4a92-98a5-766e20a0f741'
ms:contentKeyID: 18123544
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720201(v=WS.10)'
---

Requisitos de software para o RMS
=================================

Os requisitos de software para executar servidores do RMS estão listados na tabela a seguir.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Software</th>
<th style="border:1px solid black;" >Requisitos</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Sistema operacional</td>
<td style="border:1px solid black;">Qualquer edição do Microsoft Windows Server® 2003, exceto a Web Edition.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Sistema de arquivos</td>
<td style="border:1px solid black;">Recomenda-se o sistema de arquivos NTFS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Componentes do sistema operacional</td>
<td style="border:1px solid black;"><ul>
<li>Enfileiramento de Mensagens (também conhecido como MSMQ) com a Integração com o Serviço de Diretório do Active Directory® habilitada.<br />
<br />
</li>
<li>IIS (Serviços de Informações da Internet) com ASP.NET habilitado<br />
<br />
</li>
<li>Microsoft .NET Framework 1.1<br />
<br />
</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Serviço de diretório do Active Directory®</td>
<td style="border:1px solid black;">O RMS deve ser instalado em um domínio do Active Directory no qual os controladores de domínio executem o Windows Server 2000 com Service Pack 3 (SP3) ou posterior. Todos os usuários e grupos que usam o RMS para consumir e publicar conteúdo devem ter um endereço de email configurado no Active Directory.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Servidor de banco de dados</td>
<td style="border:1px solid black;">O RMS exige um banco de dados e procedimentos armazenados para executar as operações. Você pode usar o Microsoft SQL Server 2000 com SP3a ou posterior ou o Microsoft SQL Server 2005. Para testes ou outras implantações em um único computador, pode ser usado o Microsoft SQL Server Desktop Engine (MSDE 2000) com SP3 ou o Microsoft SQL Server 2005 Express Edition.</td>
</tr>
</tbody>
</table>
  
Se você estiver implantando o RMS em um ambiente onde existem várias florestas do Active Directory, deverá usar os Grupos Universais do Active Directory para que a associação de grupo seja replicada para todos os Catálogos Globais. Para criar Grupos Universais, o nível funcional do seu domínio deve ser definido como, pelo menos, Nativo do Windows 2000, e o nível funcional da floresta deve ser elevado para Windows Server 2003.
  
É recomendável usar o MSDE 2000 ou o Microsoft SQL Server 2005 Express Edition para o suporte a bancos de dados do RMS apenas em ambientes de teste, pois o MSDE 2000 e o Microsoft SQL Server 2005 Express Edition não dão suporte a nenhuma interface de rede. Além disso, os termos de uso do MSDE 2000 ou do Microsoft SQL Server 2005 Express Edition especificam que não é possível usar ferramentas de cliente do SQL Server para manipular um banco de dados do MSDE 2000 ou do Microsoft SQL Server 2005 Express Edition. Com essa restrição não será possível exibir informações de log ou alterar dados armazenados no banco de dados de configuração.
  
Se você não possui o ASP.NET versão 1.1 instalado no servidor, o processo de instalação apresentará variações, dependendo se você está executando a versão de 32 ou de 64 bits do Windows Server 2003.
  
Se você estiver executando a versão de 32 bits do Windows Server 2003, siga estas etapas para instalar e habilitar o ASP.NET versão 1.1:
  
1.  Abra **Adicionar ou Remover Programas** no **Painel de Controle** e clique em **Adicionar/Remover Componentes do Windows**.  
2.  Clique em **Servidor de Aplicativos** e depois clique em **Detalhes**.  
3.  No Assistente de Componentes do Windows, selecione **ASP.NET**.  
4.  Se o ASP.NET 1.1 estiver instalado, mas sem permissão como uma extensão do serviço IIS na Web:  
    -   Abra o Gerente dos Serviços de Informações da Internet.  
    -   Clique em **Extensão do serviço IIS na Web**, selecione ASP.NET v1.1.4322 e clique em **Permitir**.
  
Se você estiver executando a versão de 64 bits do Windows Server 2003, siga estas etapas para instalar e habilitar o ASP.NET versão 1.1:
  
1.  Instale o .NET Framework 1.1, que instalará o ASP.NET 1.1. Você pode baixar o Pacote de Componentes Redistribuíveis do Microsoft .NET Framework Versão 1.1 do Centro de Download da Microsoft em [http://go.microsoft.com/fwlink/?LinkID=69985](http://go.microsoft.com/fwlink/?linkid=69985).  
2.  Abra o Gerente dos Serviços de Informações da Internet.  
3.  Clique em Extensão do serviço IIS na Web, selecione ASP.NET v1.1.4322 e clique em Permitir.
  
Se você estiver executando o RMS em uma versão de 64 bits do Windows Server 2003, deve usar as seguintes etapas para habilitar o IIS para funcionar com o RMS:
  
1.  Clique em **Iniciar** e depois clique em **Executar**.  
2.  Em **Abrir**, digite o comando a seguir e pressione ENTER:
  
**"cscript %SystemDrive%\\inetpub\\AdminScripts\\adsutil.vbs set w3svc/AppPools/Enable32bitAppOnWin64 1"**
  
O RMS não foi projetado para o .NET Framework versão 2.0. Embora seja permitida uma instalação lado a lado, você precisa se certificar de que o ASP.NET está configurado para usar o ASP.NET v1.1.4322. Você tem duas opções para assegurar que a instalação lado a lado seja bem-sucedida:
  
-   Instale o .NET Framework versão 2.0 antes de instalar o servidor do RMS.  
-   Restaure o ASP.NET para a versão 1.1.4322 no Site Padrão do IIS executando o seguinte comando:
  
**"%SystemRoot%\\Microsoft.NET\\Framework\\v1.1.4322\\aspnet\_regiis -s w3svc/1/root"**
  
Para obter mais informações sobre o Active Directory, o Enfileiramento de Mensagens e o IIS, consulte o Centro de Ajuda e Suporte do Windows Server 2003.
  
| ![](images/Cc720201.Caution(WS.10).gif)Cuidado                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |  
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Você pode configurar o servidor do RMS no site padrão ou em qualquer site previamente definido no IIS. Por razões de segurança, não utilize esse servidor para executar outros sites ou serviços. Se você fizer isso, vários aplicativos e serviços poderão ser executados na mesma conta que o RMS (sobretudo a conta local do sistema), o que pode expor as chaves particulares a operações sem garantia. Você não deve configurar o servidor do RMS no mesmo site que o Microsoft Office SharePoint Server 2007. Não é possível usar o RMS com autenticação Kerberos. Configurar o servidor do RMS em um site desabilita a autenticação Kerberos no servidor. Se o RMS não estiver configurado para usar o ASP.NET v1.1.4322, nenhuma informação será registrada no banco de dados de log, o que resultará em perda de dados. |
  
Consulte também  
---------------
  
####  
  
[Planejando a infra-estrutura do servidor de banco de dados](https://technet.microsoft.com/b12354bd-3143-4d1f-b5aa-450c4550653c)
