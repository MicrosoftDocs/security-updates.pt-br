---
TOCTitle: Exportar um domínio de usuário confiável
Title: Exportar um domínio de usuário confiável
ms:assetid: '40281ba3-2674-43ca-aa6d-1deb9302eb0e'
ms:contentKeyID: 18123643
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720259(v=WS.10)'
---

Exportar um domínio de usuário confiável
========================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Os domínios de usuário confiáveis permitem que um servidor RMS forneça licenças a usuários cujos certificados de conta de direitos tenham sido concedidos por um outro servidor RMS.

Exportando um domínio de usuário confiável
------------------------------------------

#### Exportar um domínio de usuário confiável

1.  Na página **Diretivas de Confiança**, na área **Domínios de usuário confiáveis**, clique em **Exportar**.

2.  A caixa de diálogo **Download de Arquivo** aparece. Clique em **Salvar**.

3.  A caixa de diálogo **Salvar como** aparece. É recomendável que você modifique o nome de arquivo .bin para incluir o nome do servidor, como RMS\_Server1\_LicensorCert.bin.

    Por padrão, o arquivo é salvo na área de trabalho. Você pode especificar um local diferente, se desejar.

4.  Clique em **Salvar** para salvar o arquivo no nome de local especificado.

Para obter mais informações sobre como executar esse procedimento, consulte [Adicionando e removendo domínios de usuário confiáveis](https://technet.microsoft.com/7c440b15-01c4-49f1-b43c-00f67f3388c1), já mencionado neste tema.
