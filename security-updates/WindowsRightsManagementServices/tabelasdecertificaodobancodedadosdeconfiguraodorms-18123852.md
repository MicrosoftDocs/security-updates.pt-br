---
TOCTitle: Tabelas de certificação do banco de dados de configuração do RMS
Title: Tabelas de certificação do banco de dados de configuração do RMS
ms:assetid: 'd392663a-1a46-42f6-a71d-f0f2c1843566'
ms:contentKeyID: 18123852
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747760(v=WS.10)'
---

Tabelas de certificação do banco de dados de configuração do RMS
================================================================

Este tópico descreve as tabelas de certificação contidas no banco de dados de configuração do RMS. As tabelas contêm informações sobre os certificados de conta de direitos emitidos para os usuários desta instalação.

UD\_Machines
------------

A tabela a seguir lista informações sobre as identificações de hardware de todos os computadores.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Nome</th>
<th style="border:1px solid black;" >Tipo de dados</th>
<th style="border:1px solid black;" >NULLs</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">i_MachineId</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">IDENTITY(1,1) Não NULL</td>
<td style="border:1px solid black;">Índice interno</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">b_PubKeyHash</td>
<td style="border:1px solid black;">binário(20)</td>
<td style="border:1px solid black;">(20) Não NULL</td>
<td style="border:1px solid black;">Hash da identificação do hardware</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">dt_CreateDate</td>
<td style="border:1px solid black;">datetime</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Data e hora em que a entrada foi adicionada à tabela</td>
</tr>
</tbody>
</table>
  
UD\_PassportAuthIdentities  
--------------------------
  
A tabela a seguir lista informações sobre o Microsoft® .NET Passport para os usuários.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Nome</th>
<th style="border:1px solid black;" >Tipo de dados</th>
<th style="border:1px solid black;" >NULLs</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">i_UserId</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Índice interno</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">i64_Puid</td>
<td style="border:1px solid black;">bigint</td>
<td style="border:1px solid black;">(50) NULL</td>
<td style="border:1px solid black;">Identificação de usuário do .NET Passport</td>
</tr>
</tbody>
</table>
  
UD\_UserMachine  
---------------
  
A tabela a seguir vincula usuários certificados às informações correspondentes do computador.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Nome</th>
<th style="border:1px solid black;" >Tipo de dados</th>
<th style="border:1px solid black;" >NULLs</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">i_MachineId</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Índice interno</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">i_UserId</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Índice interno</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">dt_CreateDate</td>
<td style="border:1px solid black;">datetime</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Data e hora em que a entrada foi adicionada à tabela</td>
</tr>
</tbody>
</table>
  
UD\_Users  
---------
  
A tabela a seguir lista informações sobre os dados do usuário.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Nome</th>
<th style="border:1px solid black;" >Tipo de dados</th>
<th style="border:1px solid black;" >NULLs</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">i_UserId</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">IDENTITY(1,1) Não NULL</td>
<td style="border:1px solid black;">Índice interno</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">b_KeyData</td>
<td style="border:1px solid black;">varbinary(2000)</td>
<td style="border:1px solid black;">(2000) Não NULL</td>
<td style="border:1px solid black;">Chave pública/particular do usuário criptografada</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">i_KeyDataLength</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Comprimento da chave pública/particular não criptografada</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">b_PublicKey</td>
<td style="border:1px solid black;">PublicKey</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Chave pública do usuário</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">i_EncryptionDbId</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Índice para o certificado do licenciante usado para criptografar o par de chaves pública/particular</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">s_Certificate</td>
<td style="border:1px solid black;">ntext</td>
<td style="border:1px solid black;">Não especificado</td>
<td style="border:1px solid black;">Não usado</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">dt_Expiration</td>
<td style="border:1px solid black;">datetime</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Data de vencimento da chave do usuário</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">dt_TemporaryExpiration</td>
<td style="border:1px solid black;">datetime</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Data/hora de vencimento para uso temporário da chave</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">f_Modified</td>
<td style="border:1px solid black;">bit</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Não usado</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">i_Quota</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Nível atual de cota para o usuário</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">i_WaitDays</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Número de dias antes que solicitações de cota adicional possam ocorrer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">dt_LastConsumption</td>
<td style="border:1px solid black;">datetime</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Data e hora da última certificação de usuário adicional</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">dt_CreateDate</td>
<td style="border:1px solid black;">datetime</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Data e hora em que a entrada foi adicionada à tabela</td>
</tr>
</tbody>
</table>
  
UD\_Windows AuthIdentities  
--------------------------
  
A tabela a seguir lista as identificações de todos os usuários autenticados e certificados do Windows.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Nome</th>
<th style="border:1px solid black;" >Tipo de dados</th>
<th style="border:1px solid black;" >NULLs</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">i_UserId</td>
<td style="border:1px solid black;">int</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">Índice interno</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">s_Sid</td>
<td style="border:1px solid black;">Sid</td>
<td style="border:1px solid black;">Não NULL</td>
<td style="border:1px solid black;">SID (Security ID) do usuário</td>
</tr>
</tbody>
</table>
