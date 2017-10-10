---
TOCTitle: Adicionar um servidor a um cluster
Title: Adicionar um servidor a um cluster
ms:assetid: 'db635238-5528-4bec-9cc6-8244e2b3d733'
ms:contentKeyID: 18123788
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747690(v=WS.10)'
---

Adicionar um servidor a um cluster
==================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Em cada servidor, é possível configurar o RMS em apenas um único site. Se desejar configurar o RMS em um site diferente do site padrão, utilize o Gerente dos Serviços de Informações da Internet para adicioná-lo antes de começar esse processo de configuração. Se o site que você deseja configurar não aparecer na lista de sites, feche a página **Administração Global**, adicione o site e inicie o processo de configuração novamente.

Se estiver implantando o RMS em um ambiente em que o nível funcional de domínio do Active Directory está definido com o modo nativo do Microsoft Windows 2000, o RMS poderá não ser capaz de ler o atributo **memberOf** nos objetos do Active Directory ao tentar expandir as participações nos grupos. Para que o RMS possa ler o atributo **memberOf**, a conta do serviço RMS deve usar uma conta de domínio que seja membro do grupo anterior ao Windows 2000-Acesso compatível (Builtin) em sua floresta.

Adicionando um servidor a um cluster
------------------------------------

#### Adicionar um servidor a um cluster

1.  Depois de instalar o RMS em um servidor que você deseja unir a um cluster raiz de certificação ou de licenciamento, abra a página **Administração Global**.

2.  Próximo ao site em que deseja configurar o RMS, clique em **Adicionar este servidor a um cluster**. É possível selecionar o site padrão ou outro site que você tenha criado no IIS (Serviços de Informações da Internet) para esse fim.

    | ![](images/Cc747690.Warning(WS.10).gif)Aviso                                                                                                                                                                                          |
    |--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | Não há suporte para executar qualquer site ou serviço adicionais no mesmo servidor como RMS. Isso poderia resultar na execução de vários aplicativos e serviços sob a mesma conta como o RMS, o que poderia expor as chaves particulares a operações sem garantia. |

3.  Na área **Conta de serviço RMS**, digite o nome da conta na forma nome\_domínio\\nome\_usuário e a senha da conta de serviço RMS sob as quais o RMS será executado na maioria das operações normais. Ela deve ser uma conta do domínio. Todos os servidores em um cluster devem ser executados sob a mesma conta de serviço RMS.

    | ![](images/Cc747690.Important(WS.10).gif)Importante                                                                                                                                                                                               |
    |--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | Por razões de segurança, recomenda-se a criação de uma conta de usuário especial para usar como conta de serviço RMS e a não concessão de permissões especiais. A conta de serviço RMS não pode ser a mesma conta do domínio utilizada para instalar o RMS com Service Pack 1. |

4.  Na área **Banco de dados de configuração**, especifique o nome do servidor de banco de dados e o nome do banco de dados de configuração para esse cluster. O banco de dados selecionado determina o cluster ao qual esse servidor é adicionado.

5.  Na área **Proteção de chave particular**, selecione o mecanismo utilizado por esse cluster para proteger a chave particular. Para a proteção da chave particular baseada em software padrão, forneça a senha que foi utilizada para criptografar a chave particular quando o primeiro servidor desse cluster foi configurado.

6.  Clique em **Enviar**.

    Se forem exibidas mensagens de erro, não feche a página. Em vez disso, corrija os erros, utilize IISReset da linha de comando para parar e reiniciar o IIS, volte para a página anterior, insira novamente as informações de configuração e clique em **Enviar** novamente. Se receber a mensagem de erro "Esgotado o tempo limite do pedido", feche a janela, verifique se o sistema atinge os requisitos mínimos de hardware e tente configurar o servidor novamente.
