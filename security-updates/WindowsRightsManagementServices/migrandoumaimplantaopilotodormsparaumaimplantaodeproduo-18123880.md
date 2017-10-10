---
TOCTitle: Migrando uma implantação piloto do RMS para uma implantação de produção
Title: Migrando uma implantação piloto do RMS para uma implantação de produção
ms:assetid: 'ea151946-22fb-4cba-a3ef-fd7a4bf0d292'
ms:contentKeyID: 18123880
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747789(v=WS.10)'
---

Migrando uma implantação piloto do RMS para uma implantação de produção
=======================================================================

Várias organizações optam por uma implantação piloto do RMS antes de implementar essa tecnologia em toda a organização. Geralmente, o programa piloto possui um número limitado de usuários, e a manutenção do servidor pode ser feita localmente por um administrador dedicado em vez de fazer parte de um centro de dados mantido por um grupo de TI. Quando a organização implementa o RMS no centro de dados para todos os clientes após a conclusão do piloto, os novos servidores do RMS são implantados para oferecer suporte para um número maior de possíveis usuários.

Entretanto, o conteúdo protegido pelo RMS fica ligado ao servidor RMS usado para criá-lo; portanto, se um servidor for removido ou substituído, devem ser executadas algumas etapas para que o conteúdo criptografado com o servidores RMS pilotos possa ser descriptografado e licenciado usando os servidores RMS de produção.

Se você implantou o RMS como um programa piloto e deseja mover o servidor RMS para o ambiente de produção da sua organização, mas também deseja manter a integridade do conteúdo que foi protegido usando o servidor RMS piloto, deve criar um plano de migração que assegure uma transição tranqüila e que possibilite retornar ao programa piloto, se necessário, para recuperar dados.

As etapas a seguir são fornecidas como exemplo de alguns itens que devem constar do plano de migração; a sua implantação pode ter requisitos adicionais.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Servidor</th>
<th style="border:1px solid black;" >Etapa</th>
<th style="border:1px solid black;" >Observações</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Piloto</td>
<td style="border:1px solid black;">Faça o backup do banco de dados de configuração do RMS.</td>
<td style="border:1px solid black;">Isto permitirá que você restaure o servidor piloto, se necessário.
O banco de dados de configuração inclui a chave particular do RMS.
Certifique-se de que você conhece a senha da chave particular.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Piloto</td>
<td style="border:1px solid black;">Se você usou um HSM (Módulo de segurança de hardware) para proteger a chave particular do RMS, faça um backup da configuração do HSM, conforme indicado pelo fabricante.</td>
<td style="border:1px solid black;">Você vai restaurar o HSM no novo servidor.
Certifique-se de que você dispõe de todos os componentes necessários para instalar e configurar o HSM.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Piloto</td>
<td style="border:1px solid black;">Exporte o arquivo de domínio de publicação confiável.</td>
<td style="border:1px solid black;">Isto permitirá que um outro servidor RMS descriptografe as licenças de publicação criadas por esse servidor e emita licenças de uso para o conteúdo protegido.
O domínio de publicação confiável inclui o certificado de licenciante para servidor, a chave particular do RMS e quaisquer modelos de diretiva de direitos estabelecidos por este servidor.
O arquivo de domínio de publicação confiável é um arquivo XML criptografado por uma senha segura que você especifica na criação do arquivo. Você também deve ter essa senha para importar o arquivo de domínio de publicação confiável.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Piloto</td>
<td style="border:1px solid black;">Exportar domínio de usuário confiável.</td>
<td style="border:1px solid black;">Isto permite que um outro servidor RMS conceda licenças de uso a usuários cujos certificados de conta de direitos tenham sido concedidos pelo servidor RMS piloto.
O domínio de usuário confiável é estabelecido através da importação do certificado de licenciante para servidor para o outro servidor RMS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Produção</td>
<td style="border:1px solid black;">Prepare o novo servidor para ser o servidor raiz de certificação.</td>
<td style="border:1px solid black;">Certifique-se de que ele pode acessar o servidor do banco de dados e de que o Enfileiramento de Mensagens e o IIS estão instalados.
Se possível, use o mesmo nome de servidor para este servidor.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Produção</td>
<td style="border:1px solid black;">Se você usar um HSM, instale o HSM e restaure a sua configuração a partir do backup criado no servidor piloto.</td>
<td style="border:1px solid black;">Estabelece as credenciais necessárias para descriptografar a chave particular do RMS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Produção</td>
<td style="border:1px solid black;">Instale o RMS.</td>
<td style="border:1px solid black;">O RMS verificará se todos os pré-requisitos de serviços foram instalados e configurados corretamente.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Produção</td>
<td style="border:1px solid black;">Configure o RMS usando uma nova chave particular. Se você estiver usando o registro online, o seu servidor será registrado durante o processo de configuração, usando a Internet para estabelecer conexão com o Microsoft Enrollment Service. Se você não dispuser de conexão com a Internet neste servidor, será necessário usar o registro offline.</td>
<td style="border:1px solid black;">Se o nome desse servidor for diferente do nome do servidor piloto, você poderá modificar a configuração da URL do cluster para ter a mesma URL do servidor piloto.
Caso contrário, será necessário configurar um redirecionamento da URL anterior do cluster para a nova URL do cluster, a fim de permitir que os usuários com conteúdo anterior obtenham licenças de uso.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Produção</td>
<td style="border:1px solid black;">Se você estiver usando o registro offline, faça o processo de registro manual para o novo servidor RMS. Para obter mais informações, consulte &quot;Registrar manualmente um servidor raiz de certificação&quot; em &quot;Operando um servidor RMS&quot;, nesta coleção de documentos.</td>
<td style="border:1px solid black;">O servidor RMS só pode ser usado depois de ter sido registrado.
Além disso, as páginas de administração do RMS só podem ser acessadas após o registro do servidor.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Produção</td>
<td style="border:1px solid black;">Importe o arquivo de domínio de publicação confiável exportado na etapa 3.</td>
<td style="border:1px solid black;">A conta de serviço RMS deve ter permissão de leitura para o local onde o arquivo está armazenado para que ele seja importado com sucesso.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Produção</td>
<td style="border:1px solid black;">Reassine cada modelo que foi importado com o domínio de publicação confiável.</td>
<td style="border:1px solid black;">Os modelos são assinados com a chave particular do servidor. Como este servidor tem uma nova chave particular, os modelos deverão ser reassinados para se tornarem válidos. Para obter mais informações, consulte &quot;Reassinar um modelo de diretiva de direitos&quot; em &quot;Operando um servidor RMS&quot;, nesta coleção de documentos.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Produção</td>
<td style="border:1px solid black;">Redistribua os modelos aos computadores clientes que participaram do piloto.</td>
<td style="border:1px solid black;">Os modelos antigos precisam ser removidos e substituídos pelos modelos assinados por este servidor.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Produção</td>
<td style="border:1px solid black;">Importe o arquivo de domínio de usuário confiável exportado na etapa 4.</td>
<td style="border:1px solid black;">Permite o uso de RACs e certificados de licenciante para cliente antigos.
Se as contas de usuário estiverem sendo movidas entre florestas como parte desta migração, observe que as contas devem ter proxies SMTP correspondentes.</td>
</tr>
</tbody>
</table>
 

Ao concluir a configuração do servidor de produção, verifique se os usuários do piloto ainda conseguem criar e ler emails anteriormente protegidos. Em seguida, você poderá adicionar tantos servidores RMS ao cluster quantos forem necessários para oferecer suporte ao número de usuários da sua organização.
