---
TOCTitle: 'Pré-requisitos e listas de verificação para o RMS'
Title: 'Pré-requisitos e listas de verificação para o RMS'
ms:assetid: '836d96ef-d0fd-4935-b595-e8dec19cbb2b'
ms:contentKeyID: 18123669
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747582(v=WS.10)'
---

Pré-requisitos e listas de verificação para o RMS
=================================================

Antes de você iniciar a instalação do RMS, verifique os pré-requisitos de tecnologia para usar o RMS; cada uma das tecnologias listadas é parte integrante do RMS, e é importante ter um conhecimento básico sobre elas para implantar o RMS com sucesso. O uso das listas de verificação apresentadas a seguir ajuda a criar listas de tarefas e planos para implantar e administrar o RMS:

-   [Pré-requisitos de tecnologia](#bkmk_9)
-   [Listas de verificação da implantação do RMS](#bkmk_10)
-   [Listas de verificação da administração do RMS](#bkmk_14)

<span id="BKMK_9"></span>
Pré-requisitos de tecnologia
----------------------------

Esta coleção de documentos fornece informações para ajudá-lo a entender como o Windows RMS funciona, como planejar e executar uma implantação para a sua organização e como administrar o dia a dia do sistema. Pressupõe que você possua conhecimentos nas seguintes áreas:

-   Implantação e administração do Windows Server 2003
-   Implantação e administração do Active Directory
-   Implantação e administração dos Serviços de Informações da Internet (IIS) 6.0 da Microsoft®
-   Administração do Microsoft® SQL Server™ 2000
-   Conceitos básicos de PKI (infra-estrutura de chave pública)
-   Rede de servidores e segurança

Para obter mais informações sobre esses tópicos, consulte "Recursos adicionais" em [Operando um servidor RMS](http://go.microsoft.com/fwlink/?linkid=42495), nesta coleção de documentos.

<span id="BKMK_10"></span>
Listas de verificação da implantação do RMS
-------------------------------------------

Esta seção fornece listas de verificação para as seguintes tarefas de implantação:

-   [Implantando uma instalação em um servidor único](#bkmk_11)
-   [Implantando clusters raiz de certificação e clusters de licenciamento](#bkmk_12)
-   [Implantando o RMS em florestas](#bkmk_13)

Para obter mais informações sobre a implantação do RMS, consulte [Implantando um sistema RMS](http://go.microsoft.com/fwlink/?linkid=42494), nesta coleção de documentos.

<span id="BKMK_11"></span>
Implantando uma instalação em um servidor único
-----------------------------------------------

Use a lista de verificação a seguir para implantar um único servidor RMS.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Etapa</th>
<th style="border:1px solid black;" >Referência</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Examinar conceitos e informações de planejamento.</td>
<td style="border:1px solid black;">&quot;Preparativos para uma implantação de RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Examinar os requisitos do sistema e confirmar se o hardware e o software necessários estão disponíveis.</td>
<td style="border:1px solid black;">&quot;Pré-requisitos de infra-estrutura para o RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=37537">Planejando uma implantação do RMS</a>.
&quot;Planejando a infra-estrutura do servidor de banco de dados&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=37537">Planejando uma implantação do RMS</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Configurar a infra-estrutura, inclusive pré-requisitos de hardware e software, contas administrativas e suporte a SMS ou Diretiva de Grupo, conforme apropriado.</td>
<td style="border:1px solid black;">&quot;Preparativos para uma implantação de RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Instalar e configurar o RMS no servidor.</td>
<td style="border:1px solid black;">&quot;Configurando serviços de certificação e de licenciamento no primeiro servidor&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Testar a implantação.</td>
<td style="border:1px solid black;">&quot;Configurando um ambiente de teste&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Implementar o RMS no ambiente de produção.</td>
<td style="border:1px solid black;">&quot;Definindo o escopo da implementação do RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
</tbody>
</table>
  
<span id="BKMK_12"></span>
Implantando clusters raiz de certificação e clusters de licenciamento  
---------------------------------------------------------------------
  
Use a lista de verificação a seguir para implantar os clusters raiz de certificação e clusters de licenciamento.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Etapa</th>
<th style="border:1px solid black;" >Referência</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Examinar conceitos e informações de planejamento.</td>
<td style="border:1px solid black;">&quot;Preparativos para uma implantação de RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Examinar os requisitos do sistema e confirmar se o hardware e o software necessários estão disponíveis.</td>
<td style="border:1px solid black;">&quot;Pré-requisitos de infra-estrutura para o RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=37537">Planejando uma implantação do RMS</a>.
&quot;Planejando a infra-estrutura do servidor de banco de dados&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=37537">Planejando uma implantação do RMS</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Examinar o plano de implantação para compreender a topologia e os componentes a serem instalados.</td>
<td style="border:1px solid black;">&quot;Determinando a topologia do RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=37537">Planejando uma implantação do RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Configurar a infra-estrutura, inclusive pré-requisitos de hardware e software, contas administrativas e suporte a SMS ou Diretiva de Grupo, conforme apropriado.</td>
<td style="border:1px solid black;">&quot;Preparativos para uma implantação de RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Instalar e configurar o RMS nos servidores que estão no cluster raiz de certificação.</td>
<td style="border:1px solid black;">&quot;Configurando serviços de certificação e de licenciamento no primeiro servidor&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.
&quot;Adicionando servidores para oferecer suporte a certificação e licenciamento&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Instalar e configurar o RMS nos servidores que estão em clusters de licenciamento.</td>
<td style="border:1px solid black;">&quot;Configurando serviços de certificação e de licenciamento no primeiro servidor&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.
&quot;Adicionando servidores para oferecer suporte a certificação e licenciamento&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Configurar o balanceamento de carga.</td>
<td style="border:1px solid black;">&quot;Expandindo a infra-estrutura básica para oferecer suporte a clusters&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Testar a implantação.</td>
<td style="border:1px solid black;">&quot;Configurando um ambiente de teste&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Implementar o RMS no ambiente de produção.</td>
<td style="border:1px solid black;">&quot;Definindo o escopo da implementação do RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
</tbody>
</table>
  
<span id="BKMK_13"></span>
Implantando o RMS em florestas  
------------------------------
  
Use a lista de verificação a seguir para implantar o RMS raiz entre florestas.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Etapa</th>
<th style="border:1px solid black;" >Referência</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Examinar conceitos e informações de planejamento.</td>
<td style="border:1px solid black;">&quot;Preparativos para uma implantação de RMS&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Configurar as permissões necessárias com base em um modelo confiável.</td>
<td style="border:1px solid black;">&quot;Implantando o RMS em florestas&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Definir os atributos apropriados do Active Directory para as florestas.</td>
<td style="border:1px solid black;">&quot;Implantando o RMS em florestas&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>.</td>
</tr>
</tbody>
</table>
  
<span id="BKMK_14"></span>
Listas de verificação da administração do RMS  
---------------------------------------------
  
Esta seção fornece listas de verificação para as seguintes tarefas de administração:
  
-   [Implementando um modelo de diretiva de direitos](#bkmk_15)  
-   [Implantando um novo cliente do RMS](#bkmk_16)  
-   [Adicionando um domínio de usuário confiável](#bkmk_17)  
-   [Adicionando um domínio de publicação confiável](#bkmk_18)
  
Para obter mais informações sobre como gerenciar o RMS, consulte [Operando um servidor RMS](http://go.microsoft.com/fwlink/?linkid=42495), nesta coleção de documentos.
  
<span id="BKMK_15"></span>
Implementando um modelo de diretiva de direitos  
-----------------------------------------------
  
Use a lista de verificação a seguir para implementar um modelo de diretiva de direitos.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Etapa</th>
<th style="border:1px solid black;" >Referência</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Examinar os conceitos pertinentes.</td>
<td style="border:1px solid black;">&quot;Modelos de diretivas de direitos&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42496">Referência técnica do RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Especificar a localização do modelo de diretiva de direitos.</td>
<td style="border:1px solid black;">&quot;Especificar o local dos modelos de diretiva de direitos&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Criar o modelo de diretiva de direitos.</td>
<td style="border:1px solid black;">&quot;Criando e modificando modelos de diretiva de direitos&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.
&quot;Adicionar um modelo de diretiva de direitos&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Distribuir o modelo de diretiva de direitos.</td>
<td style="border:1px solid black;">&quot;Distribuindo modelos de diretiva de direitos&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.</td>
</tr>
</tbody>
</table>
  
<span id="BKMK_16"></span>
Implantando um novo cliente do RMS  
----------------------------------
  
Use a lista de verificação a seguir para implantar uma nova versão do cliente do RMS.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Etapa</th>
<th style="border:1px solid black;" >Referência</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Examinar os conceitos pertinentes.</td>
<td style="border:1px solid black;">&quot;Planejamento de distribuição de cliente&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42494">Implantando um sistema RMS</a>
&quot;Excluindo versões do cofre&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Para forçar todos os clientes a atualizarem para a versão de cliente mais recente, exclua a versão desatualizada do cofre.</td>
<td style="border:1px solid black;">&quot;Excluir versões do cofre&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.</td>
</tr>
</tbody>
</table>
  
<span id="BKMK_17"></span>
Adicionando um domínio de usuário confiável  
-------------------------------------------
  
Use a lista de verificação a seguir para adicionar um domínio de usuário confiável.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Etapa</th>
<th style="border:1px solid black;" >Referência</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Examinar os conceitos pertinentes.</td>
<td style="border:1px solid black;">&quot;Domínios de usuário confiáveis&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42496">Referência técnica do RMS</a>.
&quot;Adicionando e removendo domínios de usuário confiáveis&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Obter o certificado de licenciante para servidor do domínio de usuário a ser adicionado. (O administrador da instalação de confiança deve fornecer isso.) Em seguida, adicionar o domínio de usuário à instalação.</td>
<td style="border:1px solid black;">&quot;Adicionar um domínio de usuário confiável&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.</td>
</tr>
</tbody>
</table>
  
<span id="BKMK_18"></span>
Adicionando um domínio de publicação confiável  
----------------------------------------------
  
Use a lista de verificação a seguir para adicionar um domínio de publicação confiável.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Etapa</th>
<th style="border:1px solid black;" >Referência</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Examinar os conceitos pertinentes.</td>
<td style="border:1px solid black;">&quot;Domínios de publicação confiáveis&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42496">Referência técnica do RMS</a>.
&quot;Adicionando e removendo domínios de publicação confiáveis&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Obter o certificado de licenciante para servidor criptografado e a chave particular do domínio de publicação a ser adicionado e, em seguida, adicionar o domínio de publicação à instalação.</td>
<td style="border:1px solid black;">&quot;Adicionar um domínio de publicação confiável&quot; em <a href="http://go.microsoft.com/fwlink/?linkid=42495">Operando um servidor RMS</a>.</td>
</tr>
</tbody>
</table>
