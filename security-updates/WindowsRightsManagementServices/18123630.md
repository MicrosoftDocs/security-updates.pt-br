---
TOCTitle: Protegendo a implantação do RMS
Title: Protegendo a implantação do RMS
ms:assetid: '6de8b636-a824-4844-aefc-f26347abfc14'
ms:contentKeyID: 18123630
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720291(v=WS.10)'
---

Protegendo a implantação do RMS
===============================

Uma implantação do RMS é um ativo para qualquer organização e requer as mesmas medidas de segurança física e de rede que outros servidores críticos da infra-estrutura. Como parte da implantação, você deve identificar as ameaças e as medidas preventivas aplicáveis ao servidor do RMS.

O RMS é implementado como um serviço na Web, de modo que você pode controlar o acesso ao RMS como faria com outros serviços na Web, usando ACLs (listas de controle de acesso) e SSL (Secure Sockets Layer).

**Restringindo o acesso aos serviços do RMS na Web usando ACLs**

Você pode restringir o acesso aos serviços do RMS usando ACLs. Cada uma das raízes virtuais criadas quando o RMS é configurado em um site possui uma estrutura de pastas relacionada que pode ser protegida. Por padrão, a estrutura de pastas é encontrada em &lt;unidade do sistema&gt;:\\&lt;*pasta\_raiz\_web*&gt;\\\_wmcs, onde *pasta\_raiz\_web* é o nome da pasta atribuída ao site em que o RMS foi configurado. Alguns dos serviços na Web, como o serviço de sub-registro, o serviço de certificação de dispositivo móvel e o serviço de certificação de serviços do servidor, são restritos por padrão, e os usuários ou grupos que você deseja habilitar para usar o serviço devem ser explicitamente adicionados à lista de controle de acesso.

O serviço de certificação de serviços do servidor fornece certificados de conta de direitos que podem ser usados para acessar serviços protegidos pelo RMS, como serviços de colaboração na Web, servidores de email e servidores de gerenciamento de documentos para oferecer suporte à extensão de um sistema RMS, como:

-   Um servidor de colaboração de documentos no qual os usuários podem carregar documentos desprotegidos, mas os documentos baixados receberão proteção automática do RMS, de acordo com a diretiva de direitos para o tipo de conteúdo. Um exemplo seria o Microsoft Office SharePoint Server 2007.
-   Um sistema de gerenciamento de documentos que serve como um repositório geral e de arquivo de documentos, protegidos e desprotegidos. O sistema poderá indexar para pesquisa os documentos protegidos por direitos, preservando a diretiva de direitos definida pelo criador do conteúdo.
-   Habilite o servidor de emails para abrir rapidamente o conteúdo protegido por direitos a fim de verificar se ele contém vírus ou spam, ou como parte de uma exigência legal ou diretiva de email da empresa.

Como esses cenários exigem licenças em nome de seus usuários, você deve exigir que a capacidade de os servidores obterem RACs seja restrita aos servidores da organização que foram aprovados para tal função e que estejam devidamente protegidos.

**Restringindo o acesso aos serviços do RMS na Web usando SSL**

É recomendável que você habilite o SSL e exija a criptografia de 128 bits em cada arquivo de serviços Web do RMS. Esses arquivos possuem a extensão de nome de arquivo .asmx e estão localizados nos diretórios virtuais Licenciamento, Certificação e Admin. O SSL exige que o seu servidor tenha um certificado SSL válido instalado para o site. Se você aplicar o SSL à pasta \_wmcs da instalação do RMS, as subpastas e os arquivos herdarão a configuração. Para obter mais informações sobre os arquivos dos serviços Web e os diretórios virtuais, consulte "IIS (Serviços de Informações da Internet)" na seção "RMS: referência técnica" desta coleção de documentos.

> [!Note]  
> Se você quiser abrir as páginas da Web de Administração do Windows RMS no navegador de um computador remoto, deverá habilitar o SSL. Entretanto, mesmo com o SSL habilitado, você não poderá abrir a página **Administração Global** em um computador remoto. Para obter mais informações sobre a administração remota do RMS, consulte "Usando a home page de Administração" na seção "RMS: operações" desta coleção de documentos. 

**Definindo uma senha forte para a chave particular**

A senha da chave particular é usada para gerar e armazenar a chave particular com segurança no banco de dados de configuração do RMS. É recomendável uma senha de alta segurança para garantir o máximo de segurança. Se precisar anotar a senha, guarde-a em um local fisicamente protegido.

> [!Caution]  
> Se a senha da chave particular for perdida ou esquecida e o servidor do RMS ficar offline repentinamente, você terá de descriptografar todos os documentos do RMS, recriar o ambiente do RMS e criptografar tudo novamente com a nova chave particular. 
