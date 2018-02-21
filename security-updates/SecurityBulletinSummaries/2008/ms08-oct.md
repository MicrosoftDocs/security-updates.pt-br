---
TOCTitle: 'MS08-OCT'
Title: Resumo do Boletim de Segurança da Microsoft de outubro 2008
ms:assetid: 'ms08-oct'
ms:contentKeyID: 61233644
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms08-oct(v=Security.10)'
---

 

Resumo do Boletim de Segurança da Microsoft de outubro 2008
===========================================================

Publicado: terça-feira, 14 de outubro de 2008 | Atualizado: quinta-feira, 23 de outubro de 2008

**Versão:** 3.0

Este resumo de boletins lista os boletins de segurança lançados em outubro de 2008.

Com o lançamento dos boletins de outubro de 2008, este resumo de boletins substitui a notificação prévia de boletim lançada originalmente em 9 de outubro de 2008. Para obter mais informações sobre o serviço de notificação prévia de boletim, consulte [Notificação prévia do Boletim de Segurança da Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Para obter informações sobre como receber notificações automáticas sempre que os boletins de segurança da Microsoft são emitidos, consulte as [notificações de segurança técnica da Microsoft](http://www.microsoft.com/brasil/security/alertas.mspx).

A Microsoft realizará um webcast para solucionar dúvidas dos clientes sobre esses boletins no dia 15 de outubro de 2008, às 11 horas - Hora do Pacífico (EUA e Canadá). [Registre-se agora para participar do Webcast do boletim de segurança de outubro](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374639). Depois dessa data, este webcast estará disponível sob demanda. Para obter mais informações, consulte [Webcasts e resumos dos boletins de segurança da Microsoft.](http://technet.microsoft.com/security/bulletin/summary)

A Microsoft também fornece informações para ajudar os clientes a priorizar as atualizações mensais de segurança em relação a quaisquer atualizações de alta prioridade que não são de segurança que estejam sendo lançadas no mesmo dia que as atualizações mensais de segurança. Consulte a seção **Outras informações.**

### Informações do boletim

#### Sinopses

Os boletins de segurança deste mês são como se segue, em ordem de gravidade:

Crítica (5)
-----------

 



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-067                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**Vulnerabilidade no serviço Servidor pode permitir a execução remota de código (958644)**](http://technet.microsoft.com/security/bulletin/ms08-067)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Sinopse**                           | Esta atualização de segurança resolve uma vulnerabilidade reportada em particular no serviço do servidor. A vulnerabilidade pode permitir execução remota de código se um usuário receber uma solicitação de RPC especialmente criada em um sistema afetado. Nos sistemas Microsoft Windows 2000, Windows XP e Windows Server 2003, um invasor pode explorar esta vulnerabilidade sem autenticação para executar código arbitrário. É possível que esta vulnerabilidade seja usada na criação de uma exploração por worm. As práticas recomendadas de firewall e as configurações de firewall padrão podem ajudar a proteger recursos de rede contra ataques com origem externa ao perímetro da empresa. |
| **Classificação máxima de gravidade** | [Crítica](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-060                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**Vulnerabilidade no Active Directory pode permitir a execução remota de código (957280)**](http://technet.microsoft.com/security/bulletin/ms08-060)                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Sinopse**                           | Esta atualização de segurança resolve uma vulnerabilidade reportada em particular em implementações do Active Directory no Microsoft Windows 2000 Server. Esta vulnerabilidade pode permitir a execução remota de código se um invasor obtiver acesso a uma rede afetada. Esta vulnerabilidade afeta somente servidores Microsoft Windows 2000 configurados para serem controladores de domínio. Se um servidor Microsoft Windows 2000 não tiver sido promovido a controlador de domínio, não escutará consultas LDAP (Lightweight Directory Access Protocol) nem LDAP via SSL (LDAPS) e não estará exposto a esta vulnerabilidade. |
| **Classificação máxima de gravidade** | [Crítica](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-058                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**Atualização de segurança cumulativa para Internet Explorer (956390)**](http://technet.microsoft.com/security/bulletin/ms08-058)                                                                                                                                                                                                                                                                                                                                                   |
| **Sinopse**                           | Esta atualização de segurança elimina cinco vulnerabilidades informadas de forma privada e uma vulnerabilidade anunciada publicamente. As vulnerabilidades podem permitir divulgação de informações e execução remota de código se um usuário exibir uma página da Web especialmente criada usando o Internet Explorer. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação máxima de gravidade** | [Crítica](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                                                                                                                                                                                                   |
| **Softwares afetados**                | **Microsoft Windows, Internet Explorer.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                   |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-059                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**A vulnerabilidade no serviço RPC do Host Integration Server pode permitir a execução remota de código (956695)**](http://technet.microsoft.com/security/bulletin/ms08-059)                                                                                                                                                                                                                                                                                                                                                                                         |
| **Sinopse**                           | Esta atualização de segurança resolve uma vulnerabilidade reportada em particular no Microsoft Host Integration Server. A vulnerabilidade pode permitir execução remota de código se um invasor enviar uma solicitação de chamada de procedimento remoto (RPC) especialmente criada a um sistema afetado. Os clientes que seguem práticas recomendadas e configuram a conta do serviço SNA RPC para ter menos direitos de usuário no sistema podem correr menos riscos do que aqueles que configuram a conta de serviço SNA RPC para ter privilégios administrativos. |
| **Classificação máxima de gravidade** | [Crítica](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização pode requerer uma reinicialização.                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Softwares afetados**                | **Microsoft Host Integration Server.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                                                       |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de segurança da Microsoft MS08-057                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**Vulnerabilidades no Microsoft Excel podem permitir a execução remota de código (956416)**](http://technet.microsoft.com/security/bulletin/ms08-057)                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Sinopse**                           | Esta atualização de segurança elimina três vulnerabilidades reportadas em particular no Microsoft Office Excel que podem permitir a execução remota de código se um usuário abrir um arquivo do Excel especialmente criado. O invasor que explorar com êxito as vulnerabilidades poderá assumir o controle total de um sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. Os usuários cujas contas são configuradas com poucos direitos de usuário no sistema correm menos riscos do que aqueles que possuem direitos administrativos. |
| **Classificação máxima de gravidade** | [Crítica](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização não requer reinicialização.                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Softwares afetados**                | **Microsoft Office.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

Importante (6)
--------------

 



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de segurança da Microsoft MS08-066                                                                                                                                                                                                                                                                                                                                |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**A vulnerabilidade no Ancillary Function Driver pode permitir elevação de privilégio (956803)**](http://technet.microsoft.com/security/bulletin/ms08-066)                                                                                                                                                                                                               |
| **Sinopse**                           | Esta atualização de segurança resolve uma vulnerabilidade reportada em particular no Microsoft Ancillary Function Driver. O invasor local que explorar com êxito essa vulnerabilidade poderá assumir o controle total de um sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. |
| **Classificação máxima de gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                               |
| **Impacto da vulnerabilidade**        | Elevação de privilégio                                                                                                                                                                                                                                                                                                                                                    |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                                                                                        |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                           |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-061                                                                                                                                                                                                                                                                                                  |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**Vulnerabilidades do kernel do Windows podem permitir elevação de privilégio (954211)**](http://technet.microsoft.com/security/bulletin/ms08-061)                                                                                                                                                                                         |
| **Sinopse**                           | Esta atualização de segurança resolve uma vulnerabilidade divulgada publicamente e duas reportadas em particular no kernel do Windows. O invasor que explorar com êxito essas vulnerabilidades poderá assumir o controle total de um sistema afetado. Essas vulnerabilidades não podem ser exploradas remotamente ou por usuários anônimos. |
| **Classificação máxima de gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                 |
| **Impacto da vulnerabilidade**        | Elevação de privilégio                                                                                                                                                                                                                                                                                                                      |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                                                          |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                             |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-062                                                                                                                                                                                                                                                                                                                                      |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**A vulnerabilidade no Windows Internet Printing Service pode permitir execução remota de código (953155)**](http://technet.microsoft.com/security/bulletin/ms08-062)                                                                                                                                                                                                          |
| **Sinopse**                           | Esta atualização elimina uma vulnerabilidade no Windows Internet Printing Service, relatada em particular, que pode permitir a execução remota de código. O invasor que explorar com êxito essa vulnerabilidade poderá assumir o controle total de um sistema afetado. Um invasor poderá instalar programas, visualizar, alterar ou excluir dados, ou ainda criar novas contas. |
| **Classificação máxima de gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                     |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                       |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                                                                                              |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                 |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-063                                                                                                                                                                                                                                                                                                                                                                                         |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**Vulnerabilidade no SMB pode permitir a execução remota de código (957095)**](http://technet.microsoft.com/security/bulletin/ms08-063)                                                                                                                                                                                                                                                                                           |
| **Sinopse**                           | Esta atualização de segurança resolve uma vulnerabilidade reportada em particular no protocolo SMB (Server Message Block) da Microsoft. A vulnerabilidade pode permitir a execução remota de código em um servidor que compartilhe arquivos ou pastas. Um invasor que explorar com êxito essas vulnerabilidades poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de usuário. |
| **Classificação máxima de gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                        |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                                                                                                                                                 |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                    |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-064                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**A vulnerabilidade em manipulação no Virtual Address Descriptor pode permitir elevação de privilégio (956841)**](http://technet.microsoft.com/security/bulletin/ms08-064)                                                                                                                                                                                                                                                                                                                     |
| **Sinopse**                           | Esta atualização de segurança resolve uma vulnerabilidade reportada em particular no Virtual Address Descriptor. A vulnerabilidade pode permitir elevação de privilégio se um usuário executar um aplicativo especialmente criado. Um invasor não autenticado que explore essa vulnerabilidade com êxito pode elevar seus privilégios em um sistema afetado. O invasor poderá instalar programas; exibir, alterar ou excluir dados; ou criar novas contas com direitos totais de administração. |
| **Classificação máxima de gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Impacto da vulnerabilidade**        | Elevação de privilégio                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                                                                                                                                                                                                              |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                                 |



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-065                                                                                                                                                                                                                                                           |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**Vulnerabilidade no serviço de enfileiramento de mensagens pode permitir a execução remota de código (951071)**](http://technet.microsoft.com/security/bulletin/ms08-065)                                                                                                                          |
| **Sinopse**                           | Esta atualização de segurança resolve uma vulnerabilidade reportada em particular no Serviço de Enfileiramento de Mensagens (MSMQ) em sistemas Microsoft Windows 2000. A vulnerabilidade pode permitir a execução remota de código em sistemas Microsoft Windows 2000 com o serviço MSMQ habilitado. |
| **Classificação máxima de gravidade** | [Importante](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                          |
| **Impacto da vulnerabilidade**        | Execução Remota de Código                                                                                                                                                                                                                                                                            |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização requer reinicialização.                                                                                                                                                   |
| **Softwares afetados**                | **Microsoft Windows.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                      |

Moderada (1)
------------

 



<p></p>
<p></p>
<p></p>

| Identificador do Boletim              | Boletim de Segurança da Microsoft MS08-056                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título do boletim**                 | [**A vulnerabilidade no Microsoft Office pode permitir divulgação de informações (957699)**](http://technet.microsoft.com/security/bulletin/ms08-056)                                                                                                                                                                                                                                                                                                                          |
| **Sinopse**                           | Esta atualização de segurança elimina uma vulnerabilidade relatada em particular no Microsoft Office. A vulnerabilidade pode permitir divulgação de informações se um usuário clicar no URL de um CDO especialmente criado. Um invasor que explorar com êxito essa vulnerabilidade pode injetar um script do lado do cliente no navegador do usuário que pode falsificar conteúdo, revelar informações ou realizar todas as ações que o usuário possa efetuar no site afetado. |
| **Classificação máxima de gravidade** | [Moderada](http://www.microsoft.com/brasil/security/boletins/rating.mspx)                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Impacto da vulnerabilidade**        | Divulgação não autorizada de informação                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Detecção**                          | O Microsoft Baseline Security Analyzer pode detectar se seu sistema de computador precisa desta atualização. A atualização não requer reinicialização.                                                                                                                                                                                                                                                                                                                         |
| **Softwares afetados**                | **Microsoft Office.** Para obter mais informações, consulte as seções Softwares afetados e Locais de download.                                                                                                                                                                                                                                                                                                                                                                 |

Índice de exploração
--------------------

 
**Como devo usar a tabela?**  

Use esta tabela para saber qual a probabilidade do código de exploração de funcionamento ser lançado para cada uma das atualizações de segurança que você possa precisar instalar. Você deve revisar cada uma das avaliações abaixo, de acordo com sua configuração específica, para dar prioridade a sua implantação. Para obter mais informações sobre o que estas avaliações significam e como são determinadas, consulte o [Microsoft Exploit Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

| ID do Boletim                                                       | Título do Boletim                                                                                                                                                       | ID do CVE     | Avaliação do índice de exploração                                                                                 | Principais observações                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|-------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [MS08-056](http://technet.microsoft.com/security/bulletin/ms08-056) | [Vulnerabilidade no Microsoft Office pode permitir a divulgação de informações (957699](http://technet.microsoft.com/security/bulletin/ms08-056)                        | CVE-2008-4020 | [2 - Possível código de exploração inconsistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)      | O código de exploração de funcionamento pôde ser criado. No entanto, o impacto da gravidade é limitado porque a vulnerabilidade permite a falsificação em uma caixa de diálogo somente em cenários específicos de aplicativos da Web. Conseqüentemente, isto pode atrair pouca atenção dos invasores.                                                                                                                                                                             |
| [MS08-057](http://technet.microsoft.com/security/bulletin/ms08-057) | [Vulnerabilidades no Microsoft Excel podem permitir a execução remota de código (956416)](http://technet.microsoft.com/security/bulletin/ms08-057)                      | CVE-2008-4019 | [1 - Possível código de exploração consistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-057](http://technet.microsoft.com/security/bulletin/ms08-057) | [Vulnerabilidades no Microsoft Excel podem permitir a execução remota de código (956416)](http://technet.microsoft.com/security/bulletin/ms08-057)                      | CVE-2008-3471 | [2 - Possível código de exploração inconsistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-057](http://technet.microsoft.com/security/bulletin/ms08-057) | [Vulnerabilidades no Microsoft Excel podem permitir a execução remota de código (956416)](http://technet.microsoft.com/security/bulletin/ms08-057)                      | CVE-2008-3477 | [2 - Possível código de exploração inconsistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Atualização de segurança cumulativa para Internet Explorer (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                                          | CVE-2008-2947 | (Pública no lançamento do boletim)                                                                                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Atualização de segurança cumulativa para Internet Explorer (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                                          | CVE-2008-3472 | [1 - Possível código de exploração consistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Atualização de segurança cumulativa para Internet Explorer (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                                          | CVE-2008-3473 | [1 - Possível código de exploração consistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Atualização de segurança cumulativa para Internet Explorer (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                                          | CVE-2008-3475 | [2 - Possível código de exploração inconsistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Atualização de segurança cumulativa para Internet Explorer (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                                          | CVE-2008-3474 | [3 - Código de exploração de funcionamento improvável](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-058](http://technet.microsoft.com/security/bulletin/ms08-058) | [Atualização de segurança cumulativa para Internet Explorer (956390)](http://technet.microsoft.com/security/bulletin/ms08-058)                                          | CVE-2008-3476 | [3 - Código de exploração de funcionamento improvável](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-059](http://technet.microsoft.com/security/bulletin/ms08-059) | [Vulnerabilidade no serviço RPC do Host Integration Server pode permitir a execução remota de código (956695)](http://technet.microsoft.com/security/bulletin/ms08-059) | CVE-2008-3466 | [1 - Possível código de exploração consistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)        | Enquanto apenas tipos específicos de clientes corporativos possivelmente instalariam o Host Integration Server, o código de exploração de funcionamento será possivelmente criado.                                                                                                                                                                                                                                                                                                |
| [MS08-060](http://technet.microsoft.com/security/bulletin/ms08-060) | [Vulnerabilidade no Active Directory pode permitir a execução remota de código (957280)](http://technet.microsoft.com/security/bulletin/ms08-060)                       | CVE-2008-4023 | [2 - Possível código de exploração inconsistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)      | É provável que a vulnerabilidade seja desencadeada para causar uma negação de condição de serviço. No entanto, criar um código de exploração de funcionamento para aproveitar a execução remota de código é difícil devido à incapacidade de controlar a necessidade de um endereço de gravação.                                                                                                                                                                                  |
| [MS08-061](http://technet.microsoft.com/security/bulletin/ms08-061) | [Vulnerabilidades do kernel do Windows podem permitir elevação de privilégio (954211)](http://technet.microsoft.com/security/bulletin/ms08-061)                         | CVE-2008-2250 | [1 - Possível código de exploração consistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-061](http://technet.microsoft.com/security/bulletin/ms08-061) | [Vulnerabilidades do kernel do Windows podem permitir elevação de privilégio (954211)](http://technet.microsoft.com/security/bulletin/ms08-061)                         | CVE-2008-2252 | [1 - Possível código de exploração consistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)        | É mais provável que a exploração de funcionamento seja criada para sistemas de multiprocessadores.                                                                                                                                                                                                                                                                                                                                                                                |
| [MS08-061](http://technet.microsoft.com/security/bulletin/ms08-061) | [Vulnerabilidades do kernel do Windows podem permitir elevação de privilégio (954211)](http://technet.microsoft.com/security/bulletin/ms08-061)                         | CVE-2008-2251 | [3 - Código de exploração de funcionamento improvável](http://technet.microsoft.com/en-us/security/cc998259.aspx) | É possível desencadear uma vulnerabilidade, mas é muito difícil criar um código de exploração de funcionamento com sucesso.                                                                                                                                                                                                                                                                                                                                                       |
| [MS08-062](http://technet.microsoft.com/security/bulletin/ms08-062) | [Vulnerabilidade no Windows Internet Printing Service pode permitir a execução remota de código (953155)](http://technet.microsoft.com/security/bulletin/ms08-062)      | CVE-2008-1446 | [1 - Possível código de exploração consistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)        | Código de exploração consistente foi descoberto em ataques direcionados limitados. Enquanto o serviço de Protocolo IPP (Internet Printing Protocol) é habilitado por padrão, o acesso a este serviço usando IIS também requer autenticação por padrão em todas as plataformas.                                                                                                                                                                                                    |
| [MS08-063](http://technet.microsoft.com/security/bulletin/ms08-063) | [Vulnerabilidade no SMB pode permitir a execução remota de código (957095)](http://technet.microsoft.com/security/bulletin/ms08-063)                                    | CVE-2008-4038 | [2 - Possível código de exploração inconsistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-064](http://technet.microsoft.com/security/bulletin/ms08-064) | [A vulnerabilidade em manipulação no Virtual Address Descriptor pode permitir elevação de privilégio (956841)](http://technet.microsoft.com/security/bulletin/ms08-064) | CVE-2008-4036 | [2 - Possível código de exploração inconsistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-065](http://technet.microsoft.com/security/bulletin/ms08-065) | [Vulnerabilidade no serviço de enfileiramento de mensagens pode permitir a execução remota de código (951071)](http://technet.microsoft.com/security/bulletin/ms08-065) | CVE-2008-3479 | [3 - Código de exploração de funcionamento improvável](http://technet.microsoft.com/en-us/security/cc998259.aspx) | A divulgação não autorizada de informações pode ser possível, mas a obtenção de conteúdo útil da memória não é sempre possível. O problema de corrupção de memória pode ser desencadeado, mas a execução remota de código é difícil de se obter.                                                                                                                                                                                                                                  |
| [MS08-066](http://technet.microsoft.com/security/bulletin/ms08-066) | [Vulnerabilidade no Microsoft Ancillary Function Driver pode permitir elevação de privilégios (956803)](http://technet.microsoft.com/security/bulletin/ms08-066)        | CVE-2008-3464 | [1 - Possível código de exploração consistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [MS08-067](http://technet.microsoft.com/security/bulletin/ms08-067) | [Vulnerabilidade no serviço Servidor pode permitir a execução remota de código (958644)](http://technet.microsoft.com/security/bulletin/ms08-067)                       | CVE-2008-4250 | [1 - Possível código de exploração consistente](http://technet.microsoft.com/en-us/security/cc998259.aspx)        | Código de exploração consistente foi descoberto em ataques direcionados e limitados, afetando o Windows XP. Apesar desse serviço ser habilitado por padrão em todas as plataformas afetadas, a exploração é mais possível no Microsoft Windows 2000, Windows XP e Windows Server 2003. Para o Windows Vista, Windows Server 2008, essas plataformas requerem autenticação, e mesmo depois da autenticação, a exploração é mais difícil devido aos aperfeiçoamentos de ASLR e DEP. |

Softwares afetados e Locais de download
---------------------------------------

 
**Como devo usar a tabela?**  

Use esta tabela para aprender sobre as atualizações de segurança que você talvez precise instalar. Você deve examinar cada programa ou componente de software listado para verificar se alguma atualização de segurança é necessária. Se um programa de software ou componente estiver listado, haverá também um hiperlink para a atualização de software disponível e a classificação de gravidade da atualização de software também estará listada.

**Observação** Talvez você tenha que instalar diversas atualizações de segurança para uma única vulnerabilidade. Examine a coluna inteira de cada identificador de boletim listado para verificar as atualizações que você deve instalar com base nos programas ou componentes instalados no sistema.

#### Componentes e sistema operacional Windows

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="10">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Boletim com classificação de gravidade máxima**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=e22eb3ae-1295-4fe2-9775-6f43c5c2aed3)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Active Directory no Microsoft Windows 2000 Server Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ed7bb9a-4b26-49d7-8c14-60226d2bc20d)  
(Crítica)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=257c0478-56dd-42eb-a90e-607d01613db7)  
(Crítica)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=02390258-08e9-4b75-960d-be081b749558)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=3a6165a6-d7e7-4526-9291-290caf0639b4)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=8163d1f6-feb5-4f39-8134-3ed42326b822)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=9ed29c3a-0682-4586-bbc2-a73deaa18e4c)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=899e2728-2433-4ccb-a195-05b5d65e5469)  
(Importante)
</td>
</tr>
<tr>
<th colspan="10">
Windows XP (site em inglês)
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Boletim com classificação de gravidade máxima**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 e Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d5f9b6e-9265-44b9-a376-2067b73d6a03)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=a7f0f47b-b1ee-4516-9fbf-bf8e579963d0)  
(Crítica)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4e73de2b-05e6-4901-9bac-46d8f469e635)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b16d9dac-c430-4dd8-a1e5-9a614801f1d9)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7718bf14-c26c-43f3-be67-4c79ab5b2607)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e7ef571f-c9e8-4e14-95a3-3eeaec55b784)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2f7e5981-6eef-4f08-86c0-c6a7607ea5d0)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 e Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=25997b73-a640-49c1-b19e-768a18bbe22c)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4c16a372-7bf8-4571-b982-dac6b2992b25)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=234c05fb-988b-4e02-aab6-bb23e447df3d)  
(Crítica)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ccf7a3e3-ec30-4b95-9a86-00032301513c)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5b607efc-c6fb-4079-8478-e4f3262386d3)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b06d3a02-b6e4-4d40-913a-3759a31f20f3)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3ae4b913-bff0-4974-b198-828ca10d2a87)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4e1675eb-6b06-48e9-9765-23a2c7737bdc)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition e Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=50fae854-0bde-46f8-9444-b9e0d9bfecad)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Boletim com classificação de gravidade máxima**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f26d395d-2459-4e40-8c92-3de1c52c390d)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=ae8d22d5-20aa-471d-a423-f54c9d75febe)  
(Moderada)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=feaf2adf-7892-4dbf-a147-db4d5dbe52f3)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ee88ff2d-1b12-4f4c-a081-9f27a6fba074)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e696762-d652-4a8f-ab8f-622f9746c320)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=437a9b68-6a0c-48c8-9348-0d6fda48aa21)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dbbebb3f-f1c7-402c-bd16-6f88da0d042c)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 e Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e8ef3d5f-dd8e-4945-92cd-9d3e30b16667)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c04d2afb-f9d0-4e42-9e1f-4b944a2de400)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=07fc88c4-2571-4a4d-b573-ae576798ab4c)  
(Moderada)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=319dba34-07ca-47f9-a1e9-20df2df7966b)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ab4d94d3-458c-4946-ab7f-03a279629d25)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=57ca28ea-e5e1-4191-a3d6-84aa90a3d668)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d3df6508-a568-449d-ac97-fbf3f97b98ef)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=989ac6f1-515c-467d-a200-2aabe66d9319)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition e Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c2e754f9-086a-494c-bc19-5feed7df8b65)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ab590756-f11f-43c9-9dcc-a85a43077acf)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b68937af-f04a-4d1e-9d7f-ec92af5194de)  
(Moderada)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=47381d91-4a14-4a09-96b3-3345155df52d)  
(Baixa)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=63234f85-6e5d-4ef6-b7cf-d1d2c78a5517)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1e6c3f81-85bb-48e6-a5af-635a7e540c93)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=748f54f1-40b9-407c-9819-909061b53743)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=91589cfb-15ba-4dd2-9e3b-107899fbcba6)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 com SP1 para sistemas baseados no Itanium e Windows Server 2003 com SP2 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5a3832ec-3f8f-42c1-a603-b1330d527547)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="10">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Boletim com classificação de gravidade máxima**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista e Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=18fdff67-c723-42bd-ac5c-cac7d8713b21)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4756e04b-6e1c-4d78-a3c0-17f6b4b97975)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3483b400-cedc-441f-ba8e-594e3df89190)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9b5995df-a3b8-4e81-b118-9bb057e19884)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72dd6015-25d1-45f4-a769-88ac43074b44)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista e Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b4212db5-093e-497d-b999-2e3780f9f7c2)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a976999d-264f-4e6a-9bd6-3ad9d214a4bd)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=bd19c72b-4f83-47ab-93be-d2c286e732c4)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=905ab030-14a5-4a3d-aa11-e8f957f6a1ea)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4a0fcf4b-eb8e-456a-b934-400ae18248ee)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f793af16-5464-4db1-a42b-1c5f17c538ed)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition e Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c20808cb-c30a-4b53-91e5-810eb6b4b2e3)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://technet.microsoft.com/security/bulletin/ms08-067)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://technet.microsoft.com/security/bulletin/ms08-060)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://technet.microsoft.com/security/bulletin/ms08-058)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://technet.microsoft.com/security/bulletin/ms08-066)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://technet.microsoft.com/security/bulletin/ms08-061)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://technet.microsoft.com/security/bulletin/ms08-062)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://technet.microsoft.com/security/bulletin/ms08-063)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://technet.microsoft.com/security/bulletin/ms08-064)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://technet.microsoft.com/security/bulletin/ms08-065)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Boletim com classificação de gravidade máxima**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Importante**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas de 32 bits
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=25c17b07-1efe-43d7-9b01-3dfdf1ce0bd7)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ec73f416-2204-42d6-8932-c96578ac819f)\*\*  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=8b97114a-71aa-47a2-b9e7-f4e158c18c80)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=3d6290d8-1745-4bc0-9ca9-eeb1ad0be4a5)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=cf6744e6-b54c-40f6-a78d-7ba9453133c0)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=ec9eeb82-0497-4c55-94bb-9a47cb3521b4)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=7b12018e-0cc1-4136-a68c-be4e1633c8df)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=baacd1c2-9764-4fea-bd4d-c49791974fef)\*\*  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=6e641db2-90c8-458f-9795-3e46b70a5203)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=a33c833c-d5c5-4e37-8f89-7b9079f92e59)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=223236e8-7b19-4b47-8a90-bfc35eb9318a)\*  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=0bc178b8-f8ae-4f41-8f88-fb6a75be1bca)\*  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 para sistemas baseados no Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2bcf89ef-6446-406c-9c53-222e0f0baf7a)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=250a45dd-7eae-4440-bd10-02a703940976)  
(Baixa)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b6546e1c-bf7b-4354-8574-6c16fa707de0)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=31783e88-76e2-4bc6-b4ae-308443c6d223)  
(Nenhuma classificação de gravidade)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=077b697c-04a0-45bd-b08c-331d5c30cb47)  
(Importante)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 para sistemas baseados no Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=0af72663-4945-4916-8c55-090ba4d82793)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
**\*Instalação do núcleo de servidor do Windows Server 2008 afetada.** Essa atualização se aplica às edições do Windows Server 2008 com suporte, com a mesma classificação de gravidade, se o Windows Server 2008 tiver sido instalado usando a opção de instalação de Núcleo de Servidor. Para obter mais informações sobre essa opção de instalação, consulte [Núcleo do Servidor](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008. Consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Instalação do núcleo de servidor do Windows Server 2008 não afetada.** As vulnerabilidades abordadas por estas atualizações não afetam as edições do Windows Server 2008 com suporte se o Windows Server 2008 for instalado usando a opção de instalação Núcleo do Servidor. Para obter mais informações sobre essa opção de instalação, consulte [Núcleo do Servidor](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Observe que a opção de instalação de Núcleo do Servidor não se aplica a certas edições do Windows Server 2008. Consulte [Comparar opções de instalação de Núcleo do Servidor](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office Suites e software

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Office Suites, sistemas e componentes
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-057**](http://technet.microsoft.com/security/bulletin/ms08-057)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://technet.microsoft.com/security/bulletin/ms08-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Boletim com classificação de gravidade máxima**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=1b2740e0-ecdd-48ca-84e0-eb187c31eb16)  
(KB955461)  
(Crítica)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=27cedef1-c47c-472c-a343-cd9b4ebc2bba)  
(KB955464)  
(Importante)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1aee2d5-bfa0-40e3-91b6-98bf65524e8c)  
(KB956464)  
(Moderada)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 e Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368)  
(KB955466)  
(Importante)  
[Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368)  
(KB955466)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Sistema Microsoft Office 2007 e Sistema Microsoft Office 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Excel 2007](http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f)  
(KB955470)  
(Importante)  
[Excel 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f)  
(KB955470)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office para Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-057**](http://technet.microsoft.com/security/bulletin/ms08-057)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://technet.microsoft.com/security/bulletin/ms08-056)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Boletim com classificação de gravidade máxima**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 para Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 para Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ba4fa21a-7e01-4ef8-9b9f-9d51d00ef094)  
(KB958312)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 para Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 para Mac](http://www.microsoft.com/downloads/details.aspx?familyid=e70c5ae0-2858-46de-81f8-dcd1786656b7)  
(KB958267)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=2a8d9a3b-b8a4-43b6-82a6-a2e7d16ae11d)  
(KB958304)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<th colspan="3">
Outros softwares do Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-057**](http://technet.microsoft.com/security/bulletin/ms08-057)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://technet.microsoft.com/security/bulletin/ms08-056)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Boletim com classificação de gravidade máxima**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
<td style="border:1px solid black;">
[**Moderada**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b)  
(KB955468)  
(Importante)  
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b)  
(KB955468)  
(Importante)  
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=83c88444-75b8-44d1-b280-3671394ade45)  
(KB955935)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007
</td>
<td style="border:1px solid black;">
[Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007](http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9)  
(KB955936)  
(Importante)  
[Pacote de compatibilidade do Microsoft Office para formatos de arquivos do Word, Excel e PowerPoint 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9)  
(KB955936)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535)\*  
(KB955937)  
(Importante)  
[Microsoft Office SharePoint Server 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535)\*  
(KB955937)  
(Importante)  
[Microsoft Office SharePoint Server 2007 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f)\*  
(KB955937)  
(Importante)  
[Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f)\*  
(KB955937)  
(Importante)
</td>
<td style="border:1px solid black;">
Não Aplicável
</td>
</tr>
</table>

<p></p>

 
\*Esta atualização aplica-se a servidores que têm os Serviços do Excel instalados, como a configuração padrão do Microsoft Office SharePoint Server 2007 Enterprise e do Microsoft Office SharePoint Server 2007 para Sites da Internet. O Microsoft Office SharePoint Server 2007 Standard não inclui os Serviços do Excel.

#### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Host Integration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identificador do boletim**
</td>
<td style="border:1px solid black;">
[**MS08-059**](http://technet.microsoft.com/security/bulletin/ms08-059)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Boletim com classificação de gravidade máxima**
</td>
<td style="border:1px solid black;">
[**Crítica**](http://www.microsoft.com/brasil/security/boletins/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2000
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2000 Service Pack 2 (Servidor)](http://www.microsoft.com/downloads/details.aspx?familyid=11cca58b-59a4-4e93-9eb1-19b07c290a10)  
(Crítica)  
[Microsoft Host Integration Server 2000 Administrator Client](http://www.microsoft.com/downloads/details.aspx?familyid=41b49291-1231-4e23-aef7-818207453d56)  
(Crítica)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 (Servidor)](http://www.microsoft.com/downloads/details.aspx?familyid=9ca255ed-9334-4848-af94-49ef3078cdc0)  
(Crítica)  
[Microsoft Host Integration Server 2004 Service Pack 1 (Servidor)](http://www.microsoft.com/downloads/details.aspx?familyid=eca756a1-ca56-4481-b23c-53c159a4e08c)  
(Crítica)  
[Microsoft Host Integration Server 2004 (Cliente)](http://www.microsoft.com/downloads/details.aspx?familyid=92cb54e7-f4ff-40a4-99cb-6257c4d8d4cd)  
(Crítica)  
[Microsoft Host Integration Server 2004 Service Pack 1 (Cliente)](http://www.microsoft.com/downloads/details.aspx?familyid=d776515c-09aa-4a04-876d-606bfc26a006)  
(Crítica)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2006 para sistemas de 32 bits](http://www.microsoft.com/downloads/details.aspx?familyid=1ae79da3-ec17-4d4b-8011-d777a237ac93)  
(Crítica)  
[Microsoft Host Integration Server 2006 para sistemas baseados em x64](http://www.microsoft.com/downloads/details.aspx?familyid=05da4540-4976-458a-a612-7385d78695a2)  
(Crítica)
</td>
</tr>
</table>

<p></p>

 

Orientação e ferramentas de detecção e implantação
--------------------------------------------------

 
**Central de segurança**

Gerencie as atualizações de software e segurança que você precisa instalar em servidores, computadores desktop e notebooks em sua organização. Para obter mais informações, consulte o [Centro de Gerenciamento de Atualização do Technet](http://technet.microsoft.com/pt-br/updatemanagement/default.aspx). O site [TechNet Security Center](http://www.microsoft.com/brasil/security/guidance) fornece informações adicionais sobre segurança em produtos da Microsoft. Os consumidores podem visitar [Segurança em Casa](http://www.microsoft.com/brasil/protect/default.mspx), onde essa informação também está disponível, clicando em “Atualizações de Segurança mais Recentes”.

As atualizações de segurança estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) e [Office Update](http://office.microsoft.com/pt-br/downloads/default.aspx). As atualizações de segurança também estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".

Por fim, as atualizações de segurança podem ser baixadas do [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). O Microsoft Update Catalog fornece um catálogo pesquisável de conteúdo disponibilizado por meio do Windows Update e Microsoft Update, incluindo atualizações de segurança, drivers e service packs. Ao pesquisar usando o número do boletim de segurança (como "MS07-036"), é possível adicionar todas as atualizações aplicáveis em sua cesta (incluindo idiomas diferentes para uma atualização) e baixá-las na pasta de sua escolha. Para obter mais informações sobre o Microsoft Update Catalog, consulte as [Perguntas Freqüentes sobre Microsoft Update Catalog.](http://go.microsoft.com/fwlink/?linkid=97900)

**Orientação para detecção e implantação**

A Microsoft está oferecendo uma orientação de detecção e implantação para as atualizações de segurança deste mês. Essa orientação também ajudará os profissionais de TI a entender como eles podem usar as várias ferramentas para ajudar a implantar a atualização de segurança, tal como o Windows Update, Microsoft Update, Atualização do Office, as ferramentas MBSA (Microsoft Baseline Security Analyzer), Office Detection Tool, Microsoft Systems Management Server (SMS) e a Ferramenta Extended Security Update Inventory (ESUIT). Para obter mais informações, consulte o [Artigo 910723 (em inglês) da Base de Conhecimento Microsoft](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

O MBSA (Microsoft Baseline Security Analyzer) permite aos administradores pesquisar, em sistemas locais e remotos, atualizações de segurança ausentes e problemas de configuração de segurança comuns. Para obter mais informações sobre o MBSA, visite [Microsoft Baseline Security Analyzer](http://www.microsoft.com/brasil/technet/seguranca/mbsa/).

**Windows Server Update Services**

Usando o WSUS (Windows Server Update Services), os administradores podem implantar de forma rápida e confiável as mais recentes atualizações críticas e de segurança dos sistemas operacionais Windows 2000 e posterior, Office XP e superior, Exchange Server 2003, e SQL Server 2000 nos sistemas operacionais Windows 2000 e superior.

Para obter mais informações sobre como implantar esta atualização de segurança usando o Windows Server Update Services, visite [Windows Server Update Services](http://www.microsoft.com/brasil/technet/seguranca/wsus/default.mspx).

**Systems Management Server**

O SMS (Microsoft Systems Management Server) fornece uma solução corporativa altamente configurável para gerenciar atualizações. Ao usar o SMS, os administradores podem identificar os sistemas baseados no Windows que precisam de atualizações de segurança, bem como executar a implantação controlada dessas atualizações em toda a empresa com o mínimo de interrupção para os usuários. O próximo lançamento do SMS, System Center Configuration Manager 2007, já está disponível; consulte também [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Para obter mais informações sobre como os administradores podem usar o SMS 2003 para instalar atualizações de segurança, consulte [Gerenciamento de Patches de Segurança do SMS 2003.](http://www.microsoft.com/brasil/servidores/smserver/evaluation/capabilities/patch.mspx) Os usuários do SMS 2.0 também podem usar o [Software Updates Service Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) (em inglês) para ajudar a implantar atualizações de segurança. Para obter informações sobre o SMS, visite [Microsoft Systems Management Server](http://www.microsoft.com/brasil/sms).

**Observação** O SMS usa o Microsoft Baseline Security Analyzer e a Microsoft Office Detection Tool para fornecer amplo suporte à detecção e implantação de atualizações do boletim de segurança. Algumas atualizações de software podem não ser detectadas por essas ferramentas. Os administradores podem usar os recursos de inventário do SMS nesses casos para apontar as atualizações de sistemas específicos. Para obter mais informações sobre este procedimento, consulte [Implementando atualizações de software usando o Recurso Distribuição de Software do SMS](http://go.microsoft.com/fwlink/?linkid=33341). Algumas atualizações de segurança exigirão direitos administrativos quando o sistema for reiniciado. Os administradores podem usar a Elevated Rights Deployment Tool (disponível no [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) e no [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) (sites em inglês) para instalar essas atualizações.

**Avaliador de compatibilidade com atualizações e Kit de ferramentas de compatibilidade de aplicativos**

As atualizações freqüentemente gravam nos mesmos arquivos e configurações do Registro necessários à execução dos aplicativos. Isto pode gerar incompatibilidades e aumentar o tempo necessário à implantação de atualizações de segurança. É possível usar os componentes do [Avaliador de compatibilidade com atualizações](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) incluídos no [Kit de ferramentas de compatibilidade de aplicativos 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) para agilizar o teste e a validação de atualizações do Windows com relação aos aplicativos instalados.

O Kit de ferramentas de compatibilidade de aplicativos (ACT) contém as ferramentas e a documentação necessárias para avaliar e atenuar problemas de compatibilidade com aplicativos antes da implantação do Microsoft Windows Vista, de uma atualização do Windows, de uma atualização de segurança da Microsoft ou de uma nova versão do Windows Internet Explorer em seu ambiente.

### Outras informações

#### Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows

A Microsoft lançou uma versão atualizada da Ferramenta de Remoção de Software Mal-Intencionado do Microsoft Windows em Windows Update, Microsoft Update, Windows Server Update Services e no Centro de Download.

#### Atualizações de alta prioridade que não são de segurança no MU, WU e WSUS:

Para obter informações sobre versões não seguras no Windows Update e Microsoft Update, consulte:

-   [Artigo 894199 (em inglês) da Base de Conhecimento Microsoft](http://support.microsoft.com/kb/894199): Descrição dos serviços de atualização de software e de alterações nos serviços do Windows Server no conteúdo para 2008. Inclui todo o conteúdo do Windows.
-   [Atualizações novas, revisadas e liberadas para produtos da Microsoft que não sejam o Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Comunidade e estratégias de segurança

**Estratégias de gerenciamento de atualização**

O site [Orientações de segurança para gerenciamento de atualizações](http://go.microsoft.com/fwlink/?linkid=21168) oferece informações adicionais sobre as práticas recomendadas pela Microsoft para a aplicação de atualizações de segurança.

**Obtendo outras atualizações de segurança**

As atualizações para outros problemas de segurança estão disponíveis nos seguintes locais:

-   As atualizações de segurança estão disponíveis no [Centro de Download da Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Você poderá encontrá-las com mais facilidade, executando uma pesquisa com a palavra-chave "atualização de segurança".
-   Atualizações para plataformas do cliente estão disponíveis no [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   É possível obter as atualizações de segurança oferecidas este mês no Windows Update, disponíveis no Centro de Download de arquivos de imagem ISO em CD contendo lançamentos críticos e de segurança. Para obter mais informações, consulte o [Artigo 913086 (em inglês) da Base de Conhecimento Microsoft](http://support.microsoft.com/kb/913086).

**Comunidade de segurança de profissionais de TI**

Aprenda a aumentar a segurança e a otimizar a infra-estrutura de TI e participe de discussões sobre os tópicos de segurança com outros profissionais de TI no site [IT Pro Security Community](http://www.microsoft.com/brasil/technet/seguranca) (em inglês).

#### Agradecimentos

A Microsoft [agradece](http://go.microsoft.com/fwlink/?linkid=21127) à pessoa citada abaixo por trabalhar conosco para ajudar a proteger os clientes:

-   [NetAgent Co., Ltd.](http://www.netagent.co.jp/) por relatar um problema descrito no boletim MS08-056
-   Joshua J. Drake, da [iDefense](http://labs.idefense.com/), por relatar um problema descrito no boletim MS08-057
-   Wushi, que trabalha com a [TippingPoint](http://www.tippingpoint.com/) e a [Zero Day Initiative](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS08-057
-   Lionel d'Hauenens, da [Labo Skopia](http://www.laboskopia.com/), que trabalha com a [iDefense VCP](http://labs.idefense.com/), por relatar um problema descrito no boletim MS08-057
-   David Flor por relatar um problema descrito no boletim MS08-058
-   Gregory Rubin por relatar um problema descrito no boletim MS08-058
-   [Ivan Fratric](http://ifsec.blogspot.com/), que trabalha com a [TippingPoint](http://www.tippingpoint.com/) e a [Zero Day Initiative](http://www.zerodayinitiative.com/), por relatar um problema descrito no boletim MS08-058
-   Thierry Zoller, da [n.runs](http://www.nruns.com/), por relatar um problema descrito no boletim MS08-058
-   Lee Dagon, da [Composica](http://www.composica.com/), por relatar um problema descrito no boletim MS08-058
-   Stephen Fewer, da [Harmony Security](http://www.harmonysecurity.com/), que trabalha com a [iDefense VCP](http://labs.idefense.com/), por relatar um problema descrito no boletim MS08-059
-   Paul Miseiko, da [nCircle](http://www.ncircle.com/), por relatar um problema descrito no boletim MS08-060
-   Paul Caton, da [iShadow](http://www.ishadow.com/), por relatar um problema descrito no boletim MS08-061
-   Thomas Garnier, da [SkyRecon](http://www.skyrecon.com/), por relatar um problema descrito no boletim MS08-061
-   [CERT/CC](http://www.cert.org/) por relatar um problema descrito no boletim MS08-062
-   Joshua Morin, da [Codenomicon](http://www.codenomicon.com/), por relatar um problema descrito no boletim MS08-063
-   Cody Pierce e Aaron Portnoy da [TippingPoint DVLabs](http://dvlabs.tippingpoint.com) por relatarem um problema descrito no boletim MS08-065
-   Fabien Le Mentec, da [SkyRecon](http://www.skyrecon.com/), por relatar um problema descrito no boletim MS08-066

#### Suporte

-   O software afetado listado foi testado a fim de determinar que versões são afetadas. Outras versões pasaram seu ciclo de vida de suporte. Para determinar o ciclo de vida do suporte da sua versão de software, visite o site [Ciclo de Vida do Suporte Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Os clientes nos EUA e Canadá podem receber suporte técnico dos [Serviços de suporte ao produto Microsoft](http://support.microsoft.com/?ln=pt-br&x=18&y=14) pelo telefone 1-866-PCSAFETY. As ligações para obter suporte associado a atualizações de segurança são gratuitas.
-   Os clientes de outros países podem obter suporte nas subsidiárias locais da Microsoft. O suporte associado a atualizações de segurança é gratuito. Para obter mais informações sobre como entrar em contato com a Microsoft a fim de obter suporte a problemas, visite o site de [Ajuda e Suporte Internacional](http://support.microsoft.com/?ln=pt-br&x=18&y=14).

#### Aviso de isenção de responsabilidade

As informações fornecidas na Base de Conhecimento Microsoft são apresentadas "no estado em que se encontram", sem garantia de qualquer tipo. A Microsoft se isenta de todas as garantias, expressas ou implícitas, inclusive as garantias de comercialização e adequação a um propósito específico. Em hipótese alguma a Microsoft Corporation ou seus fornecedores serão responsáveis por quaisquer danos, inclusive danos diretos, indiretos, incidentais, conseqüenciais, danos por lucros cessantes ou danos especiais, mesmo que a Microsoft Corporation ou seus fornecedores tenham sido alertados da possibilidade dos referidos danos. Como alguns estados não permitem a exclusão ou limitação de responsabilidade por danos conseqüenciais ou indiretos, a limitação acima pode não ser aplicável a você.

#### Revisões

-   V1.0 (14 de outubro de 2008): Resumo do boletim publicado.
-   V2.0 (15 de outubro de 2008): Removida a classificação de gravidade para o Windows Server 2008 para sistemas baseados no Itanium (MS08-062).
-   V2.1 (16 de outubro de 2008): A Sinopse do boletim de segurança MS08-062 da Microsoft foi atualizada.
-   V3.0 (23 de outubro de 2008): Adicionado o Boletim de Segurança da Microsoft MS08-067: Vulnerabilidade no serviço Servidor pode permitir a execução remota de código (958644).

*Built at 2014-04-18T01:50:00Z-07:00*
