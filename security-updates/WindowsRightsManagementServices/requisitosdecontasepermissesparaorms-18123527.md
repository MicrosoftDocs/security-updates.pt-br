---
TOCTitle: Requisitos de contas e permissões para o RMS
Title: Requisitos de contas e permissões para o RMS
ms:assetid: '07a51daa-6823-41e6-b453-92f1a0592361'
ms:contentKeyID: 18123527
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720178(v=WS.10)'
---

Requisitos de contas e permissões para o RMS
============================================

A tabela a seguir especifica os direitos e permissões do usuário, necessários para implantar e administrar o RMS.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Atividade</th>
<th style="border:1px solid black;" >Conta e permissões do usuário</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Instalando o RMS</td>
<td style="border:1px solid black;">Fazer logon usando uma conta de domínio que seja membro do grupo local de administradores.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Configurando o RMS</td>
<td style="border:1px solid black;">Fazer logon usando uma conta de domínio que seja membro do grupo local de administradores. Além disso, a conta usada deve ter um logon SQL com função de Administrador do Sistema concedida no banco de dados do Servidor SQL para que o RMS possa instalar os bancos de dados.
Durante a configuração, você deve especificar a conta de serviço RMS, que precisa já ter sido criada. A conta deve ser uma conta de usuário do domínio padrão sem permissões adicionais. Essa conta torna-se membro do Grupo de Serviço RMS e é a conta sob a qual o RMS será executado durante as operações de rotina.
Em implantações de um único servidor em que o banco de dados fica no mesmo computador que o servidor raiz de certificação, você pode especificar a conta do Sistema Local. No entanto, por razões de segurança, é recomendável especificar sempre a conta de serviço RMS, em vez da conta do Sistema Local. Quando o banco de dados está em um servidor independente, você deve especificar a conta de serviço RMS.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Administrando o RMS</td>
<td style="border:1px solid black;">Fazer logon usando uma conta de domínio que seja membro do grupo local de administradores. Você pode personalizar as configurações de segurança para gerenciar o acesso às páginas de administração da Web.</td>
</tr>
</tbody>
</table>
  
> [!NOTE]  
> A conta usada para fazer logon no servidor RMS não requer participação adicional em nenhum grupo de domínio, como Admins. do Domínio. Entretanto, algumas tarefas administrativas específicas, como registrar o ponto de conexão do serviço e modificar as diretivas de segurança, exigem uma conta com privilégios adicionais.
