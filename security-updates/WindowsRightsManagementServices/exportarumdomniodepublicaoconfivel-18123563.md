---
TOCTitle: Exportar um domínio de publicação confiável
Title: Exportar um domínio de publicação confiável
ms:assetid: '3fb138dd-e324-43f8-97e0-da0027a036a3'
ms:contentKeyID: 18123563
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720252(v=WS.10)'
---

Exportar um domínio de publicação confiável
===========================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Exportando um domínio de publicação confiável
---------------------------------------------

#### Exportar um domínio de publicação confiável

1.  Abra a página **Administração Global** e, próximo ao site em que deseja adicionar um domínio de publicação confiável, clique em **Administrar o RMS neste site**.

2.  Na área **Links de Administração**, clique em **Diretivas de confiança**.

3.  Na página **Diretivas de Confiança**, na área **Domínios de publicação confiáveis**, clique em **Exportar**, próximo ao recipiente da chave deste servidor RMS.

4.  A caixa de diálogo **Exportação do domínio de publicação confiável** aparece.

5.  Digite a senha que será usada para criptografar o arquivo de domínio de publicação confiável. Você precisará dessa senha para importar esse arquivo para um outro servidor RMS. Essa senha deve ser uma senha segura.

6.  Digite-a novamente para confirmar que você digitou a senha que deseja usar.

7.  Digite o caminho e o nome do arquivo a serem usados para o arquivo .xml de domínio de publicação confiável. Certifique-se de especificar a extensão de nome de arquivo .xml.

8.  Clique em **Exportar** para criar o arquivo de domínio de publicação confiável.

Para obter mais informações sobre como desempenhar esse procedimento, consulte [Adicionando e removendo domínios de usuário confiáveis](https://technet.microsoft.com/d87b502d-5497-4ccd-badf-f6807d587cee), já mencionado neste tema.
