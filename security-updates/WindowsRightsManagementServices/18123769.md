---
TOCTitle: Visão geral do sistema RMS
Title: Visão geral do sistema RMS
ms:assetid: 'cbd14635-e17e-42b8-9fd8-6fdce42ffe07'
ms:contentKeyID: 18123769
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747671(v=WS.10)'
---

Visão geral do sistema RMS
==========================

Este tópico fornece informações sobre como os serviços do RMS na Web e as tecnologias do cliente do RMS trabalham em conjunto em um sistema RMS.

A tabela apresentada a seguir lista os tipos de servidores envolvidos em uma implantação do RMS e descreve suas funções. Para obter informações detalhadas sobre a implantação, consulte "Implantando um sistema RMS", nesta coleção de documentos.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Servidor ou cluster</th>
<th style="border:1px solid black;" >Função</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Certificação raiz</td>
<td style="border:1px solid black;">Executa os seguintes serviços RMS:
<ul>
<li><strong>Sub-registro</strong>. Cria o sub-registro de servidores de licenciamento.<br />
<br />
</li>
<li><strong>Proxy de ativação</strong>. Atua como um proxy da Internet para solicitações, feitas pelo cliente, de cofres e certificados de máquina do RMS.<br />
<br />
</li>
<li><strong>Certificação</strong>. Emite certificados de conta de direitos.<br />
<br />
</li>
<li><strong>Publicação</strong>. Emite licenças de publicação.<br />
<br />
</li>
<li><strong>Licenciamento</strong>. Emite licenças de uso.<br />
<br />
</li>
</ul>
Cada implantação deve incluir no mínimo um servidor ou cluster raiz de certificação. Pode haver somente um cluster raiz de certificação por floresta do Active Directory.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Licenciamento (opcional)</td>
<td style="border:1px solid black;">Executa os seguintes serviços RMS:
<ul>
<li><strong>Publicação</strong>. Emite licenças de publicação.<br />
<br />
</li>
<li><strong>Licenciamento</strong>. Emite licenças de uso.<br />
<br />
</li>
</ul>
Servidores licenciados normalmente são implantados para suportar departamentos individuais ou para descarregar solicitações de licença do cluster raiz de certificação. Servidores de licença são opcionais.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Servidor de banco de dados, como o SQL Server</td>
<td style="border:1px solid black;"><ul>
<li>Executa os bancos de dados de configuração, log e serviços de diretório do RMS.<br />
<br />
</li>
<li>Armazena certificados de conta de direitos no banco de dados de configuração do cluster raiz de certificação.<br />
<br />
</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Controlador de domínio e catálogo global</td>
<td style="border:1px solid black;"><ul>
<li>Fornece serviços de autenticação de usuários e de diretório.<br />
<br />
</li>
<li>Armazena o local de descoberta de serviço do cluster raiz de certificação.<br />
<br />
</li>
</ul></td>
</tr>
</tbody>
</table>
 

O RMS usa os serviços Registro e Ativação hospedados pela Microsoft para fornecer uma raiz de confiança comum para o sistema. Para obter mais informações, consulte "[Hierarquia de confiança do RMS](https://technet.microsoft.com/2d44182f-a653-4383-aba1-dade53f7cf9a)", mais adiante neste tema.

O diagrama apresentado a seguir cita os diferentes componentes de um sistema RMS e suas funções no sistema. As setas representam solicitações e respostas que estão sendo passadas entre os diferentes componentes.

![](images/Cc747671.29138741-d45c-459b-8ead-b9bc3f708dd5(WS.10).gif)

Para obter mais informações sobre cada componente, consulte "[Componentes de software do RMS](https://technet.microsoft.com/e38a840e-f390-48fd-8354-50108a64f5ca)", mais adiante neste tema.
