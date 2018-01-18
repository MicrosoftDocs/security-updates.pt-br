---
TOCTitle: Especificar o local dos modelos de diretiva de direitos
Title: Especificar o local dos modelos de diretiva de direitos
ms:assetid: 'e1bee46d-33db-424f-ba45-1dcedcb883ab'
ms:contentKeyID: 18123862
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747781(v=WS.10)'
---

Especificar o local dos modelos de diretiva de direitos
=======================================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Se você armazenar modelos de diretiva de direitos em uma pasta compartilhada e depois alterar o local da pasta compartilhada, será preciso copiar manualmente os modelos de diretiva de direitos do local antigo para o novo.

Os modelos de diretiva de direitos também são armazenados no banco de dados de configuração. Para obter mais informações sobre a distribuição de modelos de diretiva de direitos, consulte "[Distribuindo modelos de diretiva de direitos](https://technet.microsoft.com/ae6fa26f-d744-4ac9-9eb1-728ffab87bfe)", já mencionado neste tema.

Se você estiver usando o Microsoft Office 2003 como aplicativo habilitado para RMS, o local dos modelos de diretiva de direitos será controlado pela chave do Registro `AdminTemplatePath`, e o cliente do RMS tentará localizar modelos apenas no local especificado na chave do Registro.

Especificando o local dos modelos de diretiva de direitos
---------------------------------------------------------

#### Especificar o local dos modelos de diretiva de direitos

1.  Abra a página **Administração Global** e, próximo ao site em que deseja especificar o local dos modelos de diretiva de direitos, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Modelos de diretiva de direitos**.

3.  Na área **Local de modelo**, especifique a UNC (Convenção de nomenclatura universal) de uma pasta compartilhada no qual devem ser armazenados os modelos de diretiva de direitos para esse cluster, na forma \\\\*nome\_servidor*\\*nome\_compartilhamento*. A conta que estiver executando o pool de aplicativos de **Admin** deverá ter permissão de gravação na pasta compartilhada. Certifique-se de que os seus modelos estão armazenados em um local acessível na rede que atende às diretrizes de segurança da organização. Pastas compartilhadas para modelos não devem ser criadas nas pastas principais utilizadas pelo RMS, como a pasta Arquivos de programa ou as pastas IISRoot.

4.  Clique em **Salvar**.

5.  Depois que você criar modelos de diretiva de direitos e salvá-los nesse local, eles precisarão ser disponibilizados para os usuários. Por padrão, o cliente do RMS procurará os modelos de diretiva de direitos no seguinte local do computador local:

    %HOMEPATH%\\Local Settings\\Application Data\\Microsoft\\DRM\\templates

    Os modelos de diretiva de direitos devem ser copiados do local que está especificado na etapa 3 para esse local, para todos os usuários em sua organização que utilizarão o RMS.
