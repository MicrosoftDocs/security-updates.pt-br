---
TOCTitle: Práticas recomendadas da administração do RMS
Title: Práticas recomendadas da administração do RMS
ms:assetid: '385f8112-da00-417f-a2b8-42dc1e06b717'
ms:contentKeyID: 18123626
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720245(v=WS.10)'
---

Práticas recomendadas da administração do RMS
=============================================

Considere as práticas recomendadas apresentadas a seguir para administrar o RMS.

-   **Não implantar serviços adicionais em servidores RMS**
    Se você executar serviços que não sejam do RMS em seus servidores, poderão ocorrer conflitos que resultarão em problemas de segurança. Utilize contadores de desempenho para observar degradações ou conflitos nos serviços.
-   **Executar backups freqüentes dos bancos de dados de configuração**
    Os bancos de dados de configuração armazenam informações vitais para o funcionamento do RMS. Além disso, o banco de dados de configuração do cluster raiz de certificação armazena os pares de chaves para toda a instalação. Se você executar backups regulares, poderá fazer com que o RMS volte a funcionar rapidamente se ocorrer uma falha em um servidor de banco dados. Além de fazer backups regulares, você também deve testar a validade desses backups periodicamente, executando restaurações simuladas (em um ambiente de teste separado). Para obter mais informações, consulte "Fazendo backup e restaurando o sistema para o RMS" na seção "Planejando uma implantação do RMS" desta coleção de documentos.
-   **Organizar o banco de dados de log regularmente**
-   **Usar o Microsoft Operations Manager (MOM) para monitorar o servidor RMS**
    Use o MOM e o pacote MOM do RMS para interceptar eventos críticos ou detectar a degradação do desempenho e enviar notificações sobre esses eventos.
