---
TOCTitle: Protegendo os bancos de dados usados pelo RMS
Title: Protegendo os bancos de dados usados pelo RMS
ms:assetid: '65802f9a-81bc-4398-968a-00c9b1dca2fa'
ms:contentKeyID: 18123617
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720285(v=WS.10)'
---

Protegendo os bancos de dados usados pelo RMS
=============================================

O RMS cria e usa três bancos de dados que possuem requisitos variáveis de segurança, conforme a seguir:

-   **Serviços de diretório**. Este banco de dados armazena em cache os resultados das consultas de associação de grupo do Active Directory. Como contém somente informações do Active Directory, não exige segurança adicional além da que é configurada automaticamente durante a configuração do RMS.
-   **Log**. As informações contidas nesse banco de dados são mais confidenciais do que as que estão no banco de dados de serviços de diretório, pois sua divulgação pode afetar a privacidade dos usuários. A Microsoft esforçou-se para garantir que nenhuma informação de identificação pessoal seja registrada e que todas as informações registradas nesse banco de dados sejam protegidas pelas medidas de segurança apropriadas. Nenhuma modificação adicional na segurança desse banco de dados é necessária, a menos que o banco de dados seja movido para outro computador que esteja executando o SQL Server. Se o banco de dados for movido para outro servidor, será necessário garantir a aplicação dos mesmos mecanismos de proteção ao novo ambiente.
-   **Configuração**. Esse banco de dados é o recurso mais importante e valioso da implantação do RMS, além das chaves particulares do servidor. Ele contém informações confidenciais e cruciais que devem ser cuidadosamente protegidas. Ele contém todos os certificados e chaves, a chave particular criptografada do servidor (a menos que você tenha usado a criptografia de hardware recomendada) e o hash da senha da chave particular, além das informações de configuração.

Quando o RMS cria o banco de dados de configuração, ele configura permissões que restringem o acesso e ajudam a garantir a segurança do banco de dados.

Aumentando a segurança do banco de dados
----------------------------------------

É possível usar as etapas adicionais a seguir para aumentar a segurança global dos bancos de dados que estão dentro de sua rede e do ambiente do servidor:

-   Execute o servidor de banco de dados em um computador que esteja executando o Windows Server 2003. Por padrão, esse sistema operacional é mais seguro do que o Windows 2000 Server. Embora seja possível bloquear um computador baseado no Windows 2000 Server, o processo pode ser demorado e você pode cometer erros que poderiam dar abertura para o acesso de usuários mal-intencionados ao banco de dados.
-   Restrinja o acesso físico ao servidor de banco de dados.
-   Verifique se as permissões e as listas de controle de acesso condicionais do banco de dados que estão nos arquivos do banco de dados restringem o acesso a pessoal autorizado. As permissões e as listas de controle de acesso condicional padrão configuradas pelo RMS são seguras. Tenha cuidado ao alterar qualquer configuração padrão.
-   Não execute serviços desnecessários no servidor do banco de dados, como o Serviços de Informações da Internet (IIS), Enfileiramento de Mensagens ou Serviços de Terminal.
-   Não execute nenhum banco de dados no servidor de banco de dados, exceto os bancos de dados do RMS.

Proteja os bancos de dados do SQL Server configurando o SSL (Secure Sockets Layer) ou o IPSec (Internet Protocol security) para fornecer canais criptografados. A criptografia das comunicações do banco de dados ajuda a impedir que usuários mal-intencionados capturem ou modifiquem dados registrados.

Para obter mais informações sobre como configurar o SSL para o SQL Server 2000, consulte o site do MSDN em [http://go.microsoft.com/fwlink/?LinkID=17060](http://go.microsoft.com/fwlink/?linkid=17060) (a página pode estar em inglês).

Para obter mais informações sobre como configurar o IPsec para o SQL Server 2000, consulte o site do MSDN em [http://go.microsoft.com/fwlink/?LinkID=17061](http://go.microsoft.com/fwlink/?linkid=17061) (a página pode estar em inglês).

Para obter mais informações sobre como proteger a família de sistemas operacionais Microsoft Windows Server 2003, baixe o Guia de Segurança do Windows Server 2003, disponível no Centro de Download da Microsoft em [http://go.microsoft.com/fwlink/?LinkId=36719](http://go.microsoft.com/fwlink/?linkid=36719) (a página pode estar em inglês).
