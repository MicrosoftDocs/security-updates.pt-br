---
TOCTitle: Monitorando com o Microsoft Operations Manager
Title: Monitorando com o Microsoft Operations Manager
ms:assetid: 'ce372598-7421-4f1f-b8eb-f62da26e85d1'
ms:contentKeyID: 18123848
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747758(v=WS.10)'
---

Monitorando com o Microsoft Operations Manager
==============================================

O RMS inclui um pacote de gerenciamento que pode ser usado com o MOM (Microsoft® Operations Manager). O MOM pode ajudá-lo no gerenciamento das operações dos servidores de sua organização desta forma:

-   Monitorando eventos que estejam no log de eventos do aplicativo através do RMS.
-   Destacando eventos que possam indicar possível falta de serviço ou problemas de configuração, de modo que você possa providenciar rapidamente ações corretivas ou preventivas.
-   Alertando para avisos e erros, como a expiração do seu certificado de licenciante para servidor ou a falha de um serviço da Web.

O pacote de gerenciamento do RMS (RMS\_MOMPack.akm) é instalado com o RMS na pasta %Arquivos de programas%\\Windows Rights Management Services\\Ferramentas.

Esse pacote de gerenciamento contém os seguintes conjuntos de regras, que podem ser usados para ajudar o administrador do RMS a gerenciar a implantação do servidor RMS.

**Regras do pacote de gerenciamento MOM do RMS**

1.  Medida do PMC - Total de falhas do proxy de ativação
2.  Medida do PMC - Tempo total do proxy de ativação
3.  Medida do PMC - Tempo de processamento total da ativação
4.  Medida do PMC - Total de solicitações da ativação
5.  Medida do PMC - Total de solicitações do proxy de ativação
6.  Medida do PMC - Acertos no cache AD (cache DB)
7.  Medida do PMC - Erros no cache AD (cache DB)
8.  Medida do PMC - Tempo de processamento médio de licença
9.  Evento - Corrupção de informações de configuração
10. Medida do PMC - Conexões GC inativas
11. Medida do PMC - Falhas na inscrição
12. Evento - Erro geral
13. Evento - Falha na inicialização
14. Evento - Expiração do certificado de licenciante
15. Evento - Falha na solicitação do certificado de licenciante
16. Evento - Falha no serviço de log
17. Medida do PMC - Máximo de conexões GC disponíveis
18. Evento - Plug-in de geração de ponto de aquisição de licença ausente
19. Medida do PMC - Comprimento de fila do MSMQ em todos os servidores RMS
20. Evento - Sem GCs disponíveis
21. Evento - Falha na inicialização do plug-in
22. Evento - Alteração da senha de proteção de chave particular
23. Evento - Desligamento do servidor RMS
24. Evento - Falha no desligamento do servidor RMS
25. Evento - Falha na inicialização do servidor
26. Medida do PMC - Falhas na subscrição
27. Evento - Permissão de substituição privilegiada do SuperUser invocada
28. Limite do PMC - Excesso de falhas de GetLicensorCert
29. Evento - Expiração iminente de certificado de licenciante - 1 mês
30. Evento - Expiração iminente de certificado de licenciante - 1 semana

Para obter mais informações sobre como implantar os pacotes de gerenciamento MOM em sua organização, consulte o [site da Microsoft](http://www.microsoft.com/) (http://www.microsoft.com/).
