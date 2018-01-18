---
TOCTitle: Serviços da Web do RMS
Title: Serviços da Web do RMS
ms:assetid: 'ed8dbb2e-0590-4502-afc4-54f66b96d515'
ms:contentKeyID: 18123820
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747728(v=WS.10)'
---

Serviços da Web do RMS
======================

O RMS fornece o componente de servidor de um sistema RMS. Suas funções de núcleo são implementadas como um conjunto de serviços Web do Microsoft ® ASP.NET, executados nos Serviços de Informações da Internet da Microsoft® (IIS). Os serviços Web do RMS são expostos por meio da interface SOAP ou do .NET Remoting.

Os serviços Web fornecem:

-   Sub-registro de servidores
-   Certificação de conta de entidades confiáveis
-   Licenciamento de informações protegidas por direitos
-   Funções de administração do RMS

A tabela a seguir descreve os serviços Web do RMS.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Serviço</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Sub-registro</td>
<td style="border:1px solid black;">Fornece certificados de licenciante de servidor subordinado a servidores em clusters somente de licenciamento. Esses certificados permitem que o cluster somente de licenciamento emita licenças de publicação e de uso.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Certificação de conta</td>
<td style="border:1px solid black;">Fornece certificados de conta de direitos aos usuários. Esses certificados são necessários para que os usuários obtenham licenças de publicação e de uso para criar e consumir conteúdo protegido por direitos.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Proxy de ativação</td>
<td style="border:1px solid black;">Esse serviço é mantido para compatibilidade com o cliente do RMS versão 1. Ele passa solicitações de ativação de computador ao Serviço de Ativação da Microsoft e retorna cofres e certificados de computador do RMS a clientes do RMS versão 1 . Esse serviço não é usado por clientes RMS com Service Pack 1 (SP1) ou posterior.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Publicação</td>
<td style="border:1px solid black;">Emite licenças de publicação, que permitem que os autores criem e distribuam conteúdo protegido por direitos. Também emite certificados de licenciante para cliente, que permitem aos usuários publicar conteúdo protegido por direitos sem estarem conectados à rede interna que hospeda o RMS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Licenciamento</td>
<td style="border:1px solid black;">Emite licenças de uso, que permitem que os usuários consumam conteúdo protegido por direitos.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Administração</td>
<td style="border:1px solid black;">Permite que o administrador gerencie o RMS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DrmRemote</td>
<td style="border:1px solid black;">Permite que os serviços Web se comuniquem entre si e com outros componentes do sistema RMS expondo o .NET Remoting.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Descomissionamento</td>
<td style="border:1px solid black;">Remove a proteção de conteúdo anteriormente protegido por direitos e o retorna ao cliente. Esse serviço é instalado pelo Programa de Instalação do RMS, mas não tem uma raiz virtual correspondente no IIS até ser habilitado pelo administrador. A habilitação desse serviço desabilita todos os outros serviços.</td>
</tr>
</tbody>
</table>
  
Além dos serviços Web, o RMS instala um serviço de ouvinte de log. Cada serviço Web envia dados registrados à fila de mensagens de log. O serviço de ouvinte de log transfere então os dados registrados da fila de mensagens para o banco de dados de log.
  
Os aplicativos do serviço Web estão localizados nos diretórios virtuais do IIS. Os diretórios virtuais são instalados em cada servidor RMS, sob o site que você selecionou durante o provisionamento.
  
A autenticação e o acesso são configurados separadamente para cada diretório virtual. Além disso, o acesso é configurado separadamente para cada serviço Web. Para obter informações sobre as configurações de segurança em diretórios virtuais e arquivos de serviços Web, consulte [Suporte do Serviços de Informações da Internet (IIS) para RMS](https://technet.microsoft.com/bd4dc69f-1e4e-4e95-9ae2-c925d8a14d4c), mais adiante neste tópico.
  
Para obter mais informações sobre cada serviço Web, consulte [Componentes de software do RMS](https://technet.microsoft.com/e38a840e-f390-48fd-8354-50108a64f5ca), mais adiante neste tópico.
