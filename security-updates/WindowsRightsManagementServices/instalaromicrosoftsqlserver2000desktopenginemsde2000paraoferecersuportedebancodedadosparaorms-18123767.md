---
TOCTitle: 'Instalar o Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) para oferecer suporte de banco de dados para o RMS'
Title: 'Instalar o Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) para oferecer suporte de banco de dados para o RMS'
ms:assetid: 'c9b9cd08-98c4-424f-b3fc-d685f57c002e'
ms:contentKeyID: 18123767
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747667(v=WS.10)'
---

Instalar o Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) para oferecer suporte de banco de dados para o RMS
==================================================================================================================

Instalando o Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) para oferecer suporte de banco de dados para o RMS
--------------------------------------------------------------------------------------------------------------------

#### Instalar o Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) para oferecer suporte de banco de dados para o RMS

1.  Faça logon utilizando uma conta de domínio que seja membro do grupo local de Administradores no servidor em que você deseja instalar o Microsoft SQL Server 2000 Desktop Engine (MSDE 2000).

2.  Baixe o MSDE 2000 do [site da Microsoft](http://www.microsoft.com/) (http://www.microsoft.com/) e salve-o em um local no seu computador.

3.  Execute o arquivo MSDE2000A.exe para extrair o pacote de configuração do MSDE 2000 para uma pasta. Por padrão, essa pasta terá o nome MSDERelA, mas você pode especificar um nome diferente.

4.  Abra um prompt de comando e navegue para o local no qual você salvou a instalação do MSDE 2000.

5.  Digite o seguinte comando para configurar o aplicativo Microsoft SQL Server 2000 Desktop Engine com a configuração correta para trabalhar com o RMS e substitua a *senha* por uma senha segura de sua escolha:

    **Setup.exe /i setup\\sqlrun10.msi INSTANCENAME=RMS DISABLEAGENTSTARTUP=1 SAPWD=***senha*

    | ![](images/Cc747667.Important(WS.10).gif)Importante                                                                                                                                                                                                                                    |
    |---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | O serviço do MSDE deve ser iniciado após a sua instalação. Você pode iniciá-lo em **Serviços**, no **Painel de Controle**. É recomendável que o serviço seja configurado para ter início automático, a fim de assegurar que o banco de dados do MSDE esteja sempre disponível quando o RMS estiver sendo executado. |

Não configure o RMS em um servidor até ter um banco de dados instalado para dar suporte ao banco de dados de configuração do RMS.

É recomendável que o Microsoft SQL Server Desktop Engine seja usado para oferecer suporte aos bancos de dados RMS somente em ambientes de teste, porque ele não inclui as ferramentas necessárias para ser totalmente funcional e oferecer suporte a um banco de dados de toda a empresa. Além disso, como o MSDE não oferece suporte a redes remotas, você deverá instalá-lo no mesmo servidor do RMS e não poderá adicionar servidores RMS extras ao cluster do RMS. Os termos de uso do Microsoft SQL Server Desktop Engine especificam que você não pode usar as ferramentas de cliente do SQL Server para manipular um banco de dados Microsoft SQL Server Desktop Engine. Com essa restrição, não será possível fazer backup e recuperar o banco de dados de configuração do RMS, exibir informações de log ou modificar os dados armazenados diretamente no banco de dados de configuração.
