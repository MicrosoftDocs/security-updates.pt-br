---
TOCTitle: Adicionar uma URL de cluster de extranet
Title: Adicionar uma URL de cluster de extranet
ms:assetid: '12c83186-ce9e-4100-bbd1-d87a885331c7'
ms:contentKeyID: 18123539
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720193(v=WS.10)'
---

Adicionar uma URL de cluster de extranet
========================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Não deixe de registrar a URL em seu DNS (sistema de nome de domínio) e verifique se ela funciona e se está disponível na extranet da Internet. É preciso especificar HTTPS para a URL do cluster se você tiver ativado SSL para os arquivos dos serviços da Web.

Se você estiver adicionando uma URL do cluster da extranet a um servidor RMS que já está funcionando, os novos certificados de licenciante cliente deverão ser obtidos pelos atuais clientes RMS para que eles acessem o cluster da extranet para fins de licenciamento.

Adicionando uma URL de cluster de extranet
------------------------------------------

#### Adicionar uma URL de cluster de extranet

1.  Abra a página **Administração Global** e, próximo ao site em que deseja adicionar uma URL de cluster extranet, clique em **Administrar o RMS neste site**.

2.  Na área **Links de administração**, clique em **Configurações da URL do cluster extranet**.

3.  Na área **URL do cluster da extranet**, especifique a URL de onde você deseja que os usuários externos adquiram licenças. Também é possível selecionar HTTP ou HTTPS.

4.  Clique em **Enviar**.
