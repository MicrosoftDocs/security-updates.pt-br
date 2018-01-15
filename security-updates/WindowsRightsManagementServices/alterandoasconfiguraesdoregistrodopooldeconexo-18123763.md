---
TOCTitle: Alterando as configurações do Registro do pool de conexão
Title: Alterando as configurações do Registro do pool de conexão
ms:assetid: 'c61d91db-a1ad-4ca5-a492-015da629afbc'
ms:contentKeyID: 18123763
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747660(v=WS.10)'
---

Alterando as configurações do Registro do pool de conexão
=========================================================

Para melhorar o desempenho do sistema, é possível usar as entradas da chave do Registro para definir as propriedades do pool de conexão do protocolo LDAP do Active Directory usado pelo RMS.

Em computadores que executam a versão de 32 bits do Windows Server 2003, a seguinte chave do Registro é o caminho completo da subchave para as entradas do Registro do pool de conexão:

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0**

Em computadores que executam a versão de 64 bits do Windows Server 2003, a seguinte chave do Registro é o caminho completo da subchave para as entradas do Registro do pool de conexão:

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0**

A tabela a seguir lista as entradas que podem ser adicionadas para substituir as configurações padrão do pool de conexão do Active Directory. Os valores exibidos são padrão. Para obter mais informações sobre como o RMS constrói uma lista de consulta e usa essas configurações, consulte "Otimizando as configurações do pool de conexão do Active Directory", já mencionado neste tema.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Nome</th>
<th style="border:1px solid black;" >Tipo</th>
<th style="border:1px solid black;" >Valor padrão</th>
<th style="border:1px solid black;" >Descrição</th>
<th style="border:1px solid black;" >Observações</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">GC</td>
<td style="border:1px solid black;">Seqüência de caracteres</td>
<td style="border:1px solid black;">nome-1, ..., nome-n</td>
<td style="border:1px solid black;">Lista de catálogos globais separada por vírgula (usando nomes DNS). Esta chave restringe o RMS a usar somente os catálogos globais especificados.</td>
<td style="border:1px solid black;">Para que o RMS não crie uma lista de consulta, use esta configuração para especificar os catálogos globais a serem usados.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MinGC</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1</td>
<td style="border:1px solid black;">Número mínimo de catálogos globais que devem estar disponíveis para iniciar o RMS.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">MaxGC</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">15</td>
<td style="border:1px solid black;">Número máximo de catálogos globais que o algoritmo de Topology Discovery adicionará à lista de consulta.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ThreshHoldAlive</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1</td>
<td style="border:1px solid black;">Número mínimo de conexões que devem responder para que o DiscoveryServices comece a procurar novos catálogos globais para adicionar à lista de consulta de modo que o RMS possa aceitar as solicitações.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RetryDown</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">5</td>
<td style="border:1px solid black;">Número de vezes para repetir uma conexão inativa antes de considera-la inoperante.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">TimeRetryDown</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">300</td>
<td style="border:1px solid black;">Número de segundos a esperar antes de repetir uma conexão inativa.</td>
<td style="border:1px solid black;">Não se deve alterar a configuração padrão, exceto em circunstâncias incomuns.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">TimeRetrySlow</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">30</td>
<td style="border:1px solid black;">Número de segundos a esperar antes de repetir uma conexão lenta.</td>
<td style="border:1px solid black;">Não se deve alterar a configuração padrão, exceto em circunstâncias incomuns.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">WtRoundRobin</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1</td>
<td style="border:1px solid black;">Peso da repetição alternada durante o balanceamento de carga.</td>
<td style="border:1px solid black;">A importância relativa da repetição alternada no balanceamento de carga. O valor mínimo é 1.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WtThreadCount</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">100</td>
<td style="border:1px solid black;">Peso da contagem de segmentos por conexão durante o balanceamento de carga.</td>
<td style="border:1px solid black;">A importância relativa de uma contagem de segmentos baixa.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">WtSlow</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">Peso de conexão lenta durante o balanceamento de carga.</td>
<td style="border:1px solid black;">A importância relativa da conexão que não é lenta.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">TimeOutForGC</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">5</td>
<td style="border:1px solid black;">Tempo de espera para que uma solicitação atinja o tempo limite para adicionar um catálogo global à lista de consulta.</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">LdapTimeOut</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">5</td>
<td style="border:1px solid black;">Número de segundos a aguardar antes de atingir o tempo limite em APIs de LDAP</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">TopDownExpansionLDAPTimeOut</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">40</td>
<td style="border:1px solid black;">Número de segundos a aguardar antes de atingir o tempo limite em consultas de expansão decrescentes do LDAP</td>
<td style="border:1px solid black;"></td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747660.Caution(WS.10).gif)Cuidado                                                                                   |  
|---------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Editar o Registro incorretamente pode causar sérios danos ao sistema. Antes de alterar o Registro, faça backup dos dados importantes que estão no computador. |
