---
TOCTitle: Serviço de descomissionamento do RMS
Title: Serviço de descomissionamento do RMS
ms:assetid: '97677e3b-bc83-47ec-b6db-d326cd94566c'
ms:contentKeyID: 18123783
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747695(v=WS.10)'
---

Serviço de descomissionamento do RMS
====================================

O serviço de Descomissionamento é um serviço personalizado da Web que é instalado pelo programa de instalação do RMS. Ele é executado no cluster raiz e nos clusters somente de licenciamento. Quando você habilita esse serviço, todos os outros serviços da Web do RMS no servidor são desabilitados.

O serviço descriptografa a chave de conteúdo que está na licença de publicação do conteúdo protegido por direitos e fornece essa chave ao cliente em resposta a uma solicitação de licenciamento. Isso permite que o conteúdo seja salvo sem proteção por RMS. O serviço de descomissionamento registra todas as solicitações de cliente que são feitas nele e envia-as para o serviço ouvinte do log para serem gravadas no banco de dados de log.

Você pode habilitar o serviço de descomissionamento na página **Configurações de segurança** do site de administração. Depois de habilitar esse serviço, não é possível restaurar o servidor para uma configuração padrão do RMS.

Após a habilitação do serviço, você deve definir que a lista de controle de acesso condicional do arquivo decommission.asmx permita o acesso a usuários da empresa que usaram esse servidor para licenciar conteúdo e para adicionar o Grupo de Serviço RMS à lista de controle de acesso condicional com permissões de leitura e execução, a fim de permitir que o RMS gerencie essa operação. Depois que todo o conteúdo publicado por esse servidor for desprotegido, você deve fazer o backup das informações da chave particular e, em seguida, remover o RMS do servidor.

A lista de controle de acesso padrão desse serviço é mostrada na seguinte tabela:

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Usuário ou grupo</th>
<th style="border:1px solid black;" >Permissão padrão</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SYSTEM</td>
<td style="border:1px solid black;">Controle Total</td>
</tr>
</tbody>
</table>
