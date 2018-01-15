---
TOCTitle: Adicionar um domínio de publicação confiável
Title: Adicionar um domínio de publicação confiável
ms:assetid: '731416d8-ddf4-4d4a-9f1a-bbd1ea48fe3c'
ms:contentKeyID: 18123714
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747624(v=WS.10)'
---

Adicionar um domínio de publicação confiável
============================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Se você estiver usando um módulo de segurança de hardware para proteger a chave particular do RMS e estiver importando um certificado de licenciante para servidor de uma instalação do RMS que usa proteção de chave particular baseado no software, deve especificar uma senha de chave particular na página **Configurações de segurança** de cada servidor RMS do cluster, antes de tentar importar o certificado.

Adicionando um domínio de publicação confiável
----------------------------------------------

#### Adicionar um domínio de publicação confiável

1.  Abra a página **Administração Global** e, próximo ao site em que deseja adicionar um domínio de publicação confiável, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Diretivas de confiança**.

3.  Na área **Domínios de publicação confiáveis**, clique em **Procurar**. Encontre o certificado do domínio de publicação que você deseja adicionar e clique nele duas vezes. Em **Senha para descriptografar o arquivo que está sendo importado**, digite a senha necessária para descriptografar esse arquivo e clique em **Importar**.

    O arquivo criptografado pela senha contém o certificado do licenciante, chave particular (se a chave estiver armazenada no software) e modelos de diretiva de direitos.

4.  O nome do domínio é exibido na lista **Domínios de publicação confiáveis**.

Para obter mais informações sobre como desempenhar esse procedimento, consulte [Adicionando e removendo domínios de usuário confiáveis](https://technet.microsoft.com/d87b502d-5497-4ccd-badf-f6807d587cee), já mencionado neste tema.
