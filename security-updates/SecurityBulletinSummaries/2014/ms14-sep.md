---
TOCTitle: 'MS14-SEP'
Title: Resumo de boletins de segurança da Microsoft de setembro de 2014
ms:assetid: 'ms14-sep'
ms:contentKeyID: 62841291
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms14-sep(v=Security.10)'
---

 

Resumo de boletins de segurança da Microsoft de setembro de 2014
================================================================

Publicado em: 9 de setembro de 2014

**Versão:** 1.0

Este resumo de boletins lista os boletins de segurança lançados em setembro de 2014.

Com o lançamento dos boletins de segurança de setembro de 2014, este resumo de boletins substitui a notificação antecipada do boletim emitida originalmente em 4 de setembro de 2014. Para obter mais informações sobre o serviço de notificação antecipada de boletim, consulte [Notificação antecipada dos boletins de segurança da Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [Notificações de segurança técnica da Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins em 10 de setembro de 2014, às 11:00hrs - Hora do Pacífico (EUA e Canadá). Para exibir o webcast mensal e acessar os links de webcasts de boletins de segurança adicionais, consulte [Webcast do Boletim de segurança da Microsoft](http://technet.microsoft.com/security/dn756352).

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

Sinopses
--------

 
A tabela a seguir traz um resumo dos boletins de segurança deste mês em ordem de gravidade.

Para obter detalhes sobre os softwares afetados, consulte a próxima seção, **Softwares afetados**.

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID do Boletim</th>
<th style="border:1px solid black;" >Título do boletim e Sinopse</th>
<th style="border:1px solid black;" >Classificação máxima de gravidade e impacto da vulnerabilidade</th>
<th style="border:1px solid black;" >Requisitos de reinicialização</th>
<th style="border:1px solid black;" >Softwares afetados</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;"><strong>Atualização de segurança cumulativa para Internet Explorer (2977629)<br />
<br />
</strong>Esta atualização de segurança elimina uma vulnerabilidade divulgada publicamente e trinta e seis vulnerabilidades relatadas de forma privada no Internet Explorer. A vulnerabilidade mais grave pode permitir a execução remota de código se um usuário visualizar uma página da Web criada especialmente usando o Internet Explorer. O invasor que explorar com êxito as vulnerabilidades poderá obter os mesmos direitos que o usuário ativo. Os clientes cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.msp">Crítica</a> <br />
Execução remota de código</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-053">MS14-053</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no .NET Framework pode permitir elevação de privilégio (2990931)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada de forma privada no Microsoft .NET Framework. A vulnerabilidade pode permitir a negação de serviço se um invasor enviar um pequeno número de solicitações especialmente criadas para um site .NET habilitado afetado. Por padrão, o ASP.NET não está instalado quando o Microsoft .NET Framework estiver instalado em qualquer edição com suporte do Microsoft Windows. Para serem afetados pela vulnerabilidade, os clientes precisam instalar manualmente e permitir o ASP.NET, registrando-o com o IIS.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.msp">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Pode exigir reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-054">MS14-054</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidade no Agendador de Tarefas do Windows pode permitir a elevação de privilégio (2988948)</strong><br />
<br />
Esta atualização de segurança elimina uma vulnerabilidade relatada de forma privada no Microsoft Windows. A mais severa destas vulnerabilidades poderá permitir a elevação de privilégio se um invasor se conectar a um sistema afetado e executar um aplicativo especialmente criado. O invasor precisa ter credenciais de logon válidas e poder fazer logon localmente para explorar essa vulnerabilidade. Essa vulnerabilidade não pode ser explorada remotamente por usuários anônimos.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.msp">Importante</a> <br />
Elevação de privilégio</td>
<td style="border:1px solid black;">Exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-055">MS14-055</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilidades no Microsoft Lync Server Could podem permitir a negação de serviço (2990928)</strong><br />
<br />
Esta atualização de segurança elimina três vulnerabilidades relatadas de forma privada no Microsoft Lync Server. A mais severa dessas vulnerabilidades pode permitir a negação de serviço se um invasor enviar uma solicitação especialmente criada ao Lync server.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/brasil/security/boletins/rating.msp">Importante</a> <br />
Negação de Serviço</td>
<td style="border:1px solid black;">Não exige reinicialização</td>
<td style="border:1px solid black;">Microsoft Lync Server</td>
</tr>
</tbody>
</table>

<p></p>

  
 
  
Índice de exploração  
--------------------
  
 
A tabela a seguir fornece uma avaliação de exploração de cada uma das vulnerabilidades abordadas este mês. As vulnerabilidades estão listadas por ordem de ID do boletim e de ID da CVE. Só são incluídas as vulnerabilidades com uma classificação de gravidade Crítica ou Importante nos boletins.
  
Como devo usar a tabela?
  
Use esta tabela para conhecer a probabilidade de execução do código e as explorações de negação de serviço dentro de 30 dias a partir do lançamento do boletim de segurança, para cada uma das atualizações de segurança que você possa precisar instalar. Revise cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade à implantação das atualizações deste mês. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Índice de exploração da Microsoft](http://technet.microsoft.com/security/cc998259).
  
Nas colunas a seguir, "Versão mais Recente de Software" se refere ao software, e "Versões mais Antigas de Software se refere a todas as versões mais antigas e suportadas do software, como listado nas tabelas "Softwares afetados" e "Softwares não afetados" do boletim.
  
<p></p>

<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID do Boletim</th>
<th style="border:1px solid black;" >Título da vulnerabilidade</th>
<th style="border:1px solid black;" >ID do CVE</th>
<th style="border:1px solid black;" >Avaliação da capacidade de exploração da última versão de software</th>
<th style="border:1px solid black;" >Avaliação da capacidade de exploração de versão mais antiga de software</th>
<th style="border:1px solid black;" >Avaliação do risco de exploração para negação de serviço</th>
<th style="border:1px solid black;" >Principais observações</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de informações confidenciais do recurso do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-7331">CVE-2013-7331</a></td>
<td style="border:1px solid black;">0- Exploração detectada</td>
<td style="border:1px solid black;">0- Exploração detectada</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa vulnerabilidade foi divulgada publicamente. A Microsoft está ciente dos ataques ativos limitados que tentam explorar essa vulnerabilidade.<br />
Essa é uma vulnerabilidade de divulgação não autorizada de informações: O invasor pode inferir a presença de arquivos em unidades locais.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2799">CVE-2014-2799</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4059">CVE-2014-4059</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4065">CVE-2014-4065</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4079">CVE-2014-4079</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4080">CVE-2014-4080</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4081">CVE-2014-4081</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4082">CVE-2014-4082</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4083">CVE-2014-4083</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4084">CVE-2014-4084</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4085">CVE-2014-4085</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4086">CVE-2014-4086</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4087">CVE-2014-4087</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4088">CVE-2014-4088</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4089">CVE-2014-4089</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4090">CVE-2014-4090</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4091">CVE-2014-4091</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4092">CVE-2014-4092</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4093">CVE-2014-4093</a></td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4094">CVE-2014-4094</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4095">CVE-2014-4095</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4096">CVE-2014-4096</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4097">CVE-2014-4097</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4098">CVE-2014-4098</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4099">CVE-2014-4099</a></td>
<td style="border:1px solid black;">3- Exploração improvável</td>
<td style="border:1px solid black;">3- Exploração improvável</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">Esta vulnerabilidade de corrupção de memória pode a uma negação de serviço.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4100">CVE-2014-4100</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4101">CVE-2014-4101</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4102">CVE-2014-4102</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4103">CVE-2014-4103</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4104">CVE-2014-4104</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4105">CVE-2014-4105</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4106">CVE-2014-4106</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4107">CVE-2014-4107</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4108">CVE-2014-4108</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4109">CVE-2014-4109</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4110">CVE-2014-4110</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-052</a></td>
<td style="border:1px solid black;">Vulnerabilidade de corrupção de memória do Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4111">CVE-2014-4111</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-053</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço do. NET Framework</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4072">CVE-2014-4072</a></td>
<td style="border:1px solid black;">3- Exploração improvável</td>
<td style="border:1px solid black;">3- Exploração improvável</td>
<td style="border:1px solid black;">Permanente</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-054</a></td>
<td style="border:1px solid black;">Vulnerabilidade no Agendador de tarefas</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4074">CVE-2014-4074</a></td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">1 - Probabilidade maior de exploração</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">(Nenhum)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-055</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço do Lync</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4068">CVE-2014-4068</a></td>
<td style="border:1px solid black;">3- Exploração improvável</td>
<td style="border:1px solid black;">3- Exploração improvável</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-055</a></td>
<td style="border:1px solid black;">Vulnerabilidade de divulgação de informações confidenciais do Lync XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4070">CVE-2014-4070</a></td>
<td style="border:1px solid black;">3- Exploração improvável</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Não Aplicável</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de divulgação não autorizada de informações.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/pt-br/library/security/ms14-052">MS14-055</a></td>
<td style="border:1px solid black;">Vulnerabilidade de negação de serviço do Lync</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4071">CVE-2014-4071</a></td>
<td style="border:1px solid black;">3- Exploração improvável</td>
<td style="border:1px solid black;">Não afetado</td>
<td style="border:1px solid black;">Temporário</td>
<td style="border:1px solid black;">Essa é uma vulnerabilidade de negação de serviço (site em inglês).</td>
</tr>
</tbody>
</table>

<p></p>

  
 
  
Softwares afetados  
------------------
  
 
As tabelas a seguir listam os boletins em ordem de categoria de software e gravidade.
  
**Como uso estas tabelas?**  
  
Use as tabelas para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança se aplica à sua instalação. Se um programa de software ou componente estiver listado, a classificação de gravidade da atualização do software também estará listada.
  
**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.
  
**Componentes e sistema operacional Windows**

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://technet.microsoft.com/pt-br/library/security/ms14-052)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://technet.microsoft.com/pt-br/library/security/ms14-053)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://technet.microsoft.com/pt-br/library/security/ms14-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2977629)  
(Moderada)  
Internet Explorer 7  
(2977629)  
(Moderada)  
Internet Explorer 8  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2972207)  
(Importante)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972214)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2973115)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2977629)  
(Moderada)  
Internet Explorer 7  
(2977629)  
(Moderada)  
Internet Explorer 8  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972214)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2973115)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 com SP2 para sistemas baseados no Itanium

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2977629)  
(Moderada)  
Internet Explorer 7  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972214)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://technet.microsoft.com/pt-br/library/security/ms14-052)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://technet.microsoft.com/pt-br/library/security/ms14-053)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://technet.microsoft.com/pt-br/library/security/ms14-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2977629)  
(Crítica)  
Internet Explorer 8  
(2977629)  
(Crítica)  
Internet Explorer 9  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2977629)  
(Crítica)  
Internet Explorer 8  
(2977629)  
(Crítica)  
Internet Explorer 9  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://technet.microsoft.com/pt-br/library/security/ms14-052)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://technet.microsoft.com/pt-br/library/security/ms14-053)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://technet.microsoft.com/pt-br/library/security/ms14-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2977629)  
(Moderada)  
Internet Explorer 8  
(2977629)  
(Moderada)  
Internet Explorer 9  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2977629)  
(Moderada)  
Internet Explorer 8  
(2977629)  
(Moderada)  
Internet Explorer 9  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2974268)  
(Importante)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2974269)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://technet.microsoft.com/pt-br/library/security/ms14-052)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://technet.microsoft.com/pt-br/library/security/ms14-053)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://technet.microsoft.com/pt-br/library/security/ms14-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para sistemas de 32 bits Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
(Crítica)  
Internet Explorer 9  
(2977629)  
(Crítica)  
Internet Explorer 10  
(2977629)  
(Crítica)  
Internet Explorer 11  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 para Sistemas Service Pack 1 baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
(Crítica)  
Internet Explorer 9  
(2977629)  
(Crítica)  
Internet Explorer 10  
(2977629)  
(Crítica)  
Internet Explorer 11  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://technet.microsoft.com/pt-br/library/security/ms14-052)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://technet.microsoft.com/pt-br/library/security/ms14-053)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://technet.microsoft.com/pt-br/library/security/ms14-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para Sistemas Service Pack 1 baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
(Moderada)  
Internet Explorer 9  
(2977629)  
(Moderada)  
Internet Explorer 10  
(2977629)  
(Moderada)  
Internet Explorer 11  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados no Itanium Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 e Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://technet.microsoft.com/pt-br/library/security/ms14-052)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://technet.microsoft.com/pt-br/library/security/ms14-053)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://technet.microsoft.com/pt-br/library/security/ms14-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(Importante)  
Microsoft .NET Framework 3.5  
(2973113)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas de 32 bits  
(2988948)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(Importante)  
Microsoft .NET Framework 3.5  
(2973113)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8 para sistemas baseados em x64  
(2988948)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(Importante)  
Microsoft .NET Framework 3.5  
(2973114)  
(Importante)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas de 32 bits  
(2988948)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(Importante)  
Microsoft .NET Framework 3.5  
(2973114)  
(Importante)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows 8.1 para sistemas baseados em x64  
(2988948)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 e Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://technet.microsoft.com/pt-br/library/security/ms14-052)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://technet.microsoft.com/pt-br/library/security/ms14-053)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://technet.microsoft.com/pt-br/library/security/ms14-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(Importante)  
Microsoft .NET Framework 3.5  
(2973113)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2988948)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(Moderada)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(Importante)  
Microsoft .NET Framework 3.5  
(2973114)  
(Importante)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2988948)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT e Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://technet.microsoft.com/pt-br/library/security/ms14-052)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://technet.microsoft.com/pt-br/library/security/ms14-053)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://technet.microsoft.com/pt-br/library/security/ms14-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT  
(2988948)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(Crítica)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2988948)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Opção de instalação Server Core**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://technet.microsoft.com/pt-br/library/security/ms14-052)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://technet.microsoft.com/pt-br/library/security/ms14-053)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://technet.microsoft.com/pt-br/library/security/ms14-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
**Nenhuma**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits Service Pack 2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados em x64 Service Pack 2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 para sistemas baseados em x64 Service Pack 1 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(Importante)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(Importante)  
Microsoft .NET Framework 4  
(2972215)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(Importante)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(Importante)  
Microsoft .NET Framework 3.5  
(2973113)  
(Importante)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (instalação Server Core)  
(2988948)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)

</td>
<td style="border:1px solid black;">
Não Aplicável

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(Importante)  
Microsoft .NET Framework 3.5  
(2973114)  
(Importante)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(Importante)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (instalação Server Core)  
(2988948)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
 

**Softwares e Plataformas de Comunicação da Microsoft**

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
**Microsoft Lync Server**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**

</td>
<td style="border:1px solid black;">
[**MS14-055**](http://technet.microsoft.com/pt-br/library/security/ms14-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Avaliação de gravidade agregada**

</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.msp)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2010

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2010  
(Servidor)  
(2982385)  
(Nenhuma classificação de gravidade) <sup>[1]</sup>
Microsoft Lync Server 2010  
(Serviço de Grupo de Resposta)  
(2982388)  
(Importante)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Servidor)  
(2986072)  
(Importante)  
Microsoft Lync Server 2013  
(Serviço de Grupo de Resposta)  
(2982389)  
(Importante)  
Microsoft Lync Server 2013  
(Componentes principais)  
(2992965)  
(Importante)  
Microsoft Lync Server 2013  
(Web Components Server)  
(2982390)  
(Importante)

</td>
</tr>
</table>

<p></p>

 
**Observação para o boletim MS14-055**

\[ 1\]As classificações de severidade não se aplicam a esta atualização para o software especificado. No entanto, como uma medida de defesa abrangente, a Microsoft recomenda que os clientes desse software apliquem essa atualização de segurança para ajudar a proteger contra possíveis novos vetores de ataque identificados no futuro.

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
Vários recursos estão disponíveis para ajudar administradores a implantar atualizações de segurança.

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns.

O WSUS (Windows Server Update Services), SMS (Systems Management Server) e SCCM (System Center Configuration Manager) ajudam os administradores a distribuir as atualizações de segurança.

Os componentes do Avaliador de compatibilidade com atualizações, incluídos no Kit de ferramentas de compatibilidade de aplicativos, auxilia a otimizar os testes e a validação das atualizações do Windows com relação aos aplicativos instalados.

Para informações sobre estas e outras ferramentas que estão disponíveis, consulte [Ferramentas de segurança para profissionais de TI](http://technet.microsoft.com/security/cc297183). 

Agradecimentos
--------------

 
A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) às pessoas mencionadas abaixo por trabalhar conosco para ajudar a proteger os clientes:

**MS14-052**

-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-2799)
-   [Adlab of Venustech](http://www.venustech.com.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4059)
-   AbdulAziz Hariri, da [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4065)
-   56e7aec02099b976120abfda31254b05, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4079)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4080)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4081)
-   [Adlab of Venustech](http://www.venustech.com.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4081)
-   Yuki Chen, da [Qihoo 360](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4082)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4082)
-   [Adlab of Venustech](http://www.venustech.com.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4083)
-   [Adlab of Venustech](http://www.venustech.com.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4084)
-   Sky, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4085)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4086)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4087)
-   Zhibin Hu, da [Qihoo 360](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4087)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4088)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4089)
-   Garage4Hackers, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4090)
-   Yuki Chen, da [Qihoo 360](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4091)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4092)
-   A3F2160DCA1BDE70DA1D99ED267D5DC1EC336192, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4092)
-   Jason Kratzer, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4092)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4093)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4094)
-   Yuki Chen, da [Trend Micro](http://www.trendmicro.com/), que rabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4095)
-   Cloudfuzzer, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4096)
-   AbdulAziz Hariri, da [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4096)
-   Yuki Chen, da [Trend Micro](http://www.trendmicro.com/), que rabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4097)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4097)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4098)
-   SkyLined, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4099)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4100)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4101)
-   Josá A. Vázquez da Yenteasy, que trabalha com a [Zero Day Initiative da](http://www.hpenterprisesecurity.com/products) [HP](http://www.zerodayinitiative.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4101)
-   Liu Long, da [Qihoo 360](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4102)
-   AbdulAziz Hariri, da [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4103)
-   Liu Long, da [Qihoo 360](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4104)
-   Yuki Chen, da [Trend Micro](http://www.trendmicro.com/), que rabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4105)
-   Bo Qu, da [Palo Alto Networks](http://www.paloaltonetworks.com/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4106)
-   AbdulAziz Hariri, da [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4107)
-   Um pesquisador anônimo, que trabalha com a [Zero Day Initiative](http://www.zerodayinitiative.com/) da [HP](http://www.hpenterprisesecurity.com/products), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4108)
-   John Villamil, (@day6reak), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4109)
-   Heige, por relatar a vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4110)
-   Yujie Wen, da [Qihoo 360](http://www.360.cn/), por relatar a Vulnerabilidade de corrupção de memória do Internet Explorer (CVE-2014-4111)
-   Masato Kinugawa e a [Equipe de Segurança do Google](http://www.google.com/), por trabalhar conosco em alterações de defesa abrangentes incluídas neste boletim

**MS14-053**

-   Alexander Klink de [Cynops GmbH](http://www.cynops.de/) por reportar a Vulnerabilidade de Negação de Serviço no .NET Framework (CVE-2014-4072)

**MS14-054**

-   James Forshaw, da [Segurança de Informação de Contexto](http://www.contextis.com/), por relatar a Vulnerabilidade do Agendador de Tarefas (CVE-2014-4074)

**MS14-055**

-   Peter Schraffl, de [Telecommunication Software GmbH](http://www.telecomsoftware.com/) por relatar a Vulnerabilidade de Negação de Serviço do Lync (CVE-2014-4068)
-   Noam Rathaus, que trabalha com a equipe de [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) da Beyond Security, por relatar a Vulnerabilidade de Divulgação de Informações do Lync XSS (CVE-2014-4070)

Outras informações
------------------

 
### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

Em relação ao lançamento de boletins que ocorre na segunda terça-feira do mês, a Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows no Windows Update, Microsoft Update, Windows Server Update Services e Centro de Download. Nenhuma versão atualizada da Ferramenta de Remoção de Software Mal-intencionado do Microsoft Windows está disponível para os lançamentos de boletins de segurança desvinculados.

### Atualizações não relacionadas à segurança no MU, WU e WSUS

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte o site:

-   [Artigo 894199 (em inglês) da Microsoft Knowledge Base](https://support.microsoft.com/kb/894199): Descrição de alterações no conteúdo dos Serviços de Atualização de Software e do Windows Server Update Services. Inclui todo o conteúdo do Windows.
-   [Atualizações dos meses anteriores para o Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965). Exibe todas as atualizações novas, revisadas e lançadas novamente para os produtos Microsoft que não sejam o Microsoft Windows.

### Microsoft Active Protections Program (MAPP)

Para melhorar as proteções de segurança para os clientes, a Microsoft fornece informações sobre vulnerabilidades aos principais fornecedores de software de segurança antes do lançamento de cada atualização de segurança mensal. Assim, os fornecedores de software de segurança podem usar essas informações sobre vulnerabilidades para fornecer proteções atualizadas aos clientes por meio de seus softwares ou dispositivos de segurança, como antivírus, sistemas de detecção de invasões baseados em rede ou sistemas de prevenção de invasões baseados em host. Para determinar se os fornecedores de software de segurança estão disponibilizando proteções ativas, visite os sites de proteções ativas fornecidos pelos parceiros do programa, listados em [Parceiros do Microsoft Active Protections Program (MAPP)](http://go.microsoft.com/fwlink/?linkid=215201).

### Comunidade e estratégias de segurança

**Estratégias de Gerenciamento de Atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [Artigo 913086 (em inglês) da Microsoft Knowledge Base](https://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (em inglês).

### Suporte

O software afetado listado foi testado para determinar quais versões são afetadas. Outras versões passaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).

Soluções de segurança para profissionais de TI: [Solução de problemas e suporte de segurança TechNet](http://technet.microsoft.com/security/bb980617)

Ajuda a proteger seu computador Windows de vírus e malware: [Central de segurança e solução contra vírus](http://support.microsoft.com/contactus/cu_sc_virsec_master)

Suporte local de acordo com seu país: [Suporte internacional](http://support.microsoft.com/common/international.aspx)

### Aviso de isenção de responsabilidade

As informações fornecidas na Microsoft Knowledge Base são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, consequenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos consequenciais ou indiretos, a limitação acima pode não ser aplicável a você.

### Revisões

-   V1.0 (9 de setembro de 2014): Resumo de boletins publicado.

*Página gerada em 05/09/2014 17:30Z-07:00.*
