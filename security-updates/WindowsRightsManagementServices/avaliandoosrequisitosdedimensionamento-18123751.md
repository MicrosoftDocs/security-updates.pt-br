---
TOCTitle: Avaliando os requisitos de dimensionamento
Title: Avaliando os requisitos de dimensionamento
ms:assetid: '89f0138c-946d-47d7-a286-041d4d9606a8'
ms:contentKeyID: 18123751
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747663(v=WS.10)'
---

Avaliando os requisitos de dimensionamento
==========================================

Para decidir se você deve implantar um ou vários servidores, determine quantos usuários utilizarão a implantação do RMS e quantos arquivos eles protegerão.

Isso fornece a média dos requisitos da utilização. Planeje os requisitos de pico de utilização, que provavelmente serão até três vezes a média dos requisitos.

Leve também em conta os padrões de tolerância a falhas e de disponibilidade de serviço da empresa.

Para estabelecer uma medição de referência, o RMS foi testado com um servidor de duplo processador Pentium 4 de 2,4 GHz e de 1 GB de RAM. Nessa configuração, o servidor RMS produziu aproximadamente 50 licenças por segundo.

Use os valores a seguir durante o planejamento de capacidade para avaliar os requisitos de utilização de um sistema RMS.

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
<th style="border:1px solid black;" >Transação</th>
<th style="border:1px solid black;" >Ocorrência</th>
<th style="border:1px solid black;" >Utilização de largura de banda cliente-para-servidor (KB)</th>
<th style="border:1px solid black;" >Utilização de largura de banda servidor-para-cliente (KB)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Solicitação de licença</td>
<td style="border:1px solid black;">Repetida para cada usuário e para cada conteúdo</td>
<td style="border:1px solid black;">64</td>
<td style="border:1px solid black;">18</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Certificação de conta de direitos</td>
<td style="border:1px solid black;">Tráfego de inicialização do RMS somente</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">16</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Inscrição de clientes</td>
<td style="border:1px solid black;">Tráfego de inicialização do RMS somente</td>
<td style="border:1px solid black;">17</td>
<td style="border:1px solid black;">16</td>
</tr>
</tbody>
</table>
  
Além disso, o tráfego de consultas do Active Directory pode ter impacto sobre taxa de transferência da rede. Mas esse normalmente não é um fator quando se implantam servidores RMS muito próximos dos servidores do catálogo global. A exceção seria uma falha de todos os servidores do catálogo global em um site provocada por failover para outro site via uma conexão que não aceitasse a mesma capacidade.
  
A tabela a seguir fornece dados de linha de base sobre a utilização da largura de banda de transações do RMS que você pode usar para avaliar o efeito do tráfego de consultas do Active Directory na rede da sua organização.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Transação</th>
<th style="border:1px solid black;" >Utilização da largura de banda do RMS-para-o-catálogo global (bytes)</th>
<th style="border:1px solid black;" >Utilização da largura de banda do catálogo global-para-o-RMS (bytes)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Estabelecimento da conexão do RMS (ldap_bind)</td>
<td style="border:1px solid black;">1600</td>
<td style="border:1px solid black;">200</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Avaliação da participação em grupos do RMS (ldap_search)</td>
<td style="border:1px solid black;">200</td>
<td style="border:1px solid black;">100</td>
</tr>
</tbody>
</table>
  
No uso dessas tabelas de referência, certifique-se de aplicar os números do conteúdo de sua implantação. Por exemplo, se o usuário pertence a 15 grupos, seriam necessários 200 bytes para a solicitação de pesquisa do RMS e 1.500 bytes (100 bytes x 15) para a resposta do catálogo global.
  
O planejamento da capacidade deve basear-se na previsão das cargas de solicitação de licenças de conteúdo, uma vez que essas cargas representam a maioria das operações executadas pelo RMS. A velocidade de entrada/saída e a taxa de transferência da unidade de disco não são fatores críticos para o RMS, porque as solicitações de licença não utilizam muitos dados e podem depender completamente das informações armazenadas em cache.
  
A utilização da CPU é a variável mais importante ao determinar a taxa de transferência do servidor, portanto é essencial escolher os processadores adequados. Os requisitos de memória nos servidores RMS aumentam quando a carga colocada no servidor aumenta e ultrapassa a taxa de transferência máxima do servidor. Quando isso ocorre, o IIS (Serviços de Informações da Internet) coloca as solicitações de entrada em uma fila da memória até que o servidor possa processá-las. Com base no limite da fila configurado no IIS, as solicitações de entrada param de ser colocadas na fila e passam a ser rejeitadas quando a fila atinge o comprimento máximo especificado.
  
Os requisitos de memória do RMS (conjunto de trabalho) para um padrão de carga devem encaixar-se completamente dentro dos limites da memória física. O tamanho total da memória depende mais das necessidades de cache da expansão do grupo do que de qualquer outro fator. Recomenda-se pelo menos 1 GB de RAM para cada servidor que executa o RMS.
  
Cada servidor RMS é capaz de lidar com um número definido de solicitações de clientes em um período definido de tempo (de 30 a 50 licenças por segundo). Por isso, a adição linear de servidores ultrapassa a capacidade total de emissão de licenças de um cluster e oferece maior confiabilidade. Em função disso, a escala deve ser adequada não apenas a cada servidor, mas também à quantidade de servidores implantados. Os seguintes exemplos de configuração mostram como usar essas estimativas para calcular os requisitos de dimensionamento para a implantação do RMS.
  
-   Configuração para utilização baixa  
    Algumas organizações apresentam requisitos de uso razoavelmente baixos para o RMS. Por exemplo, uma organização que tenha cerca de 5.000 usuários, 10% dos quais usam regulamente o RMS para proteger conteúdo de email, poderia estimar que um usuário médio protegeria três emails por hora. Com base nesses requisitos, os servidores RMS precisariam produzir 1.500 licenças por hora, o que equivale a 0,42 licença por segundo. Isso fornece o requisito de utilização médio; multiplicando esse valor por 3, temos o cálculo do pico de utilização de 1,25 licenças por segundo.  
    Com base nesse cálculo, a utilização é relativamente leve. Assim, um único servidor RMS seria adequado para essa organização.  
-   Configuração para utilização média  
    Muitas organizações têm grupos de usuários relativamente grandes, com necessidades de utilização moderadas. Por exemplo, uma organização que tenha cerca de 40.000 usuários, 50% dos quais usam regulamente o RMS para proteger conteúdo de email, poderia estimar que um usuário médio protegeria sete emails e um documento ou outro arquivo por hora. Com base nesses requisitos, os servidores RMS precisariam produzir 160.000 licenças por hora, o que equivale a 44,4 licenças por segundo. Isso fornece o requisito de utilização médio; multiplicando esse valor por 3, temos o cálculo do pico de utilização de 133,3 licenças por segundo.  
    Com base nesse cálculo, a utilização seria moderadamente alta e 3 servidores RMS seriam adequados para suprir os requisitos atuais dos usuários, embora com 6 servidores fosse possível suprir os requisitos atuais e ainda deixar uma folga para crescimento.  
-   Configuração para utilização alta  
    Organizações maiores geralmente têm grupos de usuários extremamente grandes, com necessidades de utilização pesadas. Por exemplo, uma organização que tenha cerca de 150.000 usuários, 70% dos quais usam regulamente o RMS para proteger conteúdo, poderia estimar que um usuário médio protegeria 15 emails e três documentos ou outros arquivos por hora. Com base nesses requisitos, os servidores RMS precisariam produzir 1.890.000 licenças por hora, o que equivale a 525 licenças por segundo. Isso fornece o requisito de utilização médio; multiplicando esse valor por 3, temos o cálculo do pico de utilização de 1575 licenças por segundo.  
    Com base nesse cálculo, a utilização seria muito alta e 32 servidores RMS seriam suficientes para suprir os requisitos dos usuários, embora com 51 servidores fosse possível suprir os requisitos atuais e ainda deixar uma folga para crescimento.
  
Quando os cálculos indicam a emissão de 30 a 50 licenças por segundo, geralmente é necessário outro servidor RMS.
