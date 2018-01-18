---
TOCTitle: Registrar manualmente um servidor raiz de certificação
Title: Registrar manualmente um servidor raiz de certificação
ms:assetid: 'aecdebb5-b28b-4b58-937a-392bb6ce9643'
ms:contentKeyID: 18123811
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747727(v=WS.10)'
---

Registrar manualmente um servidor raiz de certificação
======================================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar Executar como para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Se você estiver usando o processo de inscrição Offline, deve se certificar de que os clientes do RMS não tentem se conectar ao servidor RMS para obter licenças até que a inscrição tenha ocorrido. Se os clientes tentarem se conectar a um servidor RMS que não está inscrito, os serviços da Web apresentarão uma condição de erro que os deixará sem condição de uso. Se você não pode assegurar que os clientes não tentarão se conectar ao servidor RMS, a prática recomendada é redefinir o IIS (Internet Information Services) após concluir a inscrição, a fim de desfazer qualquer condição de erro que possa ter sido criada.

Se você optou pelo uso da inscrição Offline e está usando um computador que possui uma configuração avançada de segurança de navegador, como um computador executando o Windows Server 2003 ou o Windows XP Service Pack 2, para conectar-se à Internet e solicitar um certificado de licenciante servidor, certifique-se de adicionar a URL do site do Serviço de Inscrição à zona de Sites Confiáveis para permitir que seja baixado o certificado de licenciante servidor. A URL é https://activation.drm.microsoft.com.

Se você estiver usando o processo de inscrição Offline, certifique-se de que o computador que está usando para enviar a solicitação de inscrição ao Serviço de Inscrição da Microsoft possui a autoridade de certificação GTE Cyber Trust Root instalada no armazenamento de certificados. Por padrão, essa autoridade de certificação é confiável em máquinas que executam o Windows Server 2003. Se o computador estiver executando uma outra versão do Windows, você pode confiar nessa autoridade de certificação instalando as últimas atualizações de certificado do Windows Update.

Registrando manualmente um servidor raiz de certificação
--------------------------------------------------------

#### Registrar manualmente um servidor raiz de certificação

1.  Após instalar o RMS em um servidor que você deseja que seja o servidor raiz de certificação, abra a página **Administração Global** e depois, ao lado do site para o qual deseja importar um certificado de licenciante servidor raiz, clique em **Administrar o RMS neste site**.

2.  Na área **Recursos do cluster**, clique em **Registrar**. A caixa de diálogo **Registrar** aparece.

3.  Selecione a opção **Offline** e depois clique no botão **Exportar**. A caixa de diálogo **Download de Arquivo** aparece.

4.  Clique em **Salvar**. A caixa de diálogo **Salvar como** aparece.

    > [!Note]  
    > Na caixa de diálogo **Download de Arquivo**, não clique em **Abrir**. Se você clicar em **Abrir**, será exibida uma mensagem de erro, e o arquivo de solicitação de inscrição não será salvo. 

5.  Clique em **Salvar** para exportar a solicitação de inscrição para um arquivo. Por padrão, o arquivo será salvo na área de trabalho e nomeado *nome\_servidor*EnrollRequest.xml, onde *nome\_servidor* será substituído pelo nome do seu servidor RMS. Você pode salvar o arquivo em um local diferente, escolhendo o local desejado no menu suspenso **Salvar em**. Também é possível alterar o nome do arquivo, digitando um novo nome em **Nome do arquivo**.

6.  Depois que você salvar o arquivo de solicitação de inscrição, a caixa de diálogo **Download concluído** aparecerá. Você pode clicar em **Abrir** para exibir o código XML no arquivo, mas não altere o arquivo. Para abrir a pasta na qual o arquivo está armazenado, clique em **Abrir pasta**. Clique em **Fechar** se tiver terminado de ver o arquivo e de verificar o local.

7.  Transporte o arquivo de solicitação de registro do servidor para um computador que possa ser conectado à Internet e navegue até o [site do Serviço de Inscrição]().

8.  Siga as instruções do site para obter um certificado de licenciante servidor.

9.  Transporte o certificado de licenciante servidor de volta para o servidor raiz de certificação.

10. Na área **Recursos do cluster**, clique em **Registrar**. A caixa de diálogo **Registrar** aparece.

11. Na caixa de diálogo **Registrar**,clique no botão **Procurar**, localize o certificado de licenciante para servidor que você baixou e depois clique no botão **Importar**.

12. Clique em **Sim** para confirmar que você deseja importar esse certificado.

13. A área **Recursos do cluster** será atualizada para exibir o certificado de licenciante servidor.
