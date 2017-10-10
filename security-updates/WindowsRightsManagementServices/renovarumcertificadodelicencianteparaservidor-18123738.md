---
TOCTitle: Renovar um certificado de licenciante para servidor
Title: Renovar um certificado de licenciante para servidor
ms:assetid: 'affce9cf-8b46-4293-8e1c-ee06f2ca6537'
ms:contentKeyID: 18123738
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747636(v=WS.10)'
---

Renovar um certificado de licenciante para servidor
===================================================

Para executar esse procedimento, é preciso estar conectado localmente ao site de Administração com uma conta de usuário do domínio que seja membro do grupo Administradores no computador que você estiver acessando. Membros do grupo Admins. do Domínio também podem executar esse procedimento. Como prática recomendada de segurança, considere utilizar **Executar como** para executar esse procedimento.

Para abrir a página **Administração Global**, clique em **Iniciar**, aponte para **Todos os Programas**, aponte para **Windows RMS** e clique em **Administração do Windows RMS**.

Se você optou pelo uso da renovação Offline e está usando um computador que possui uma configuração avançada de segurança de navegador, como um computador executando o Windows Server 2003 ou o Windows XP com Service Pack 2, para conectar-se à Internet e solicitar um certificado de licenciante para servidor, certifique-se de adicionar a URL do site de Serviço de Inscrição à zona de Sites Confiáveis para permitir que seja baixado o certificado de licenciante para servidor. A URL é https://activation.drm.microsoft.com.

Se você estiver usando o processo de inscrição Offline, certifique-se de que o computador que está usando para enviar a solicitação de inscrição ao Serviço de Inscrição da Microsoft possui a autoridade de certificação GTE Cyber Trust Root instalada no armazenamento de certificados. Por padrão, essa autoridade de certificação é confiável em máquinas que executam o Windows Server 2003. Se o computador estiver executando uma outra versão do Windows, você pode confiar nessa autoridade de certificação instalando as últimas atualizações de certificado do Windows Update.

Renovando certificados de licenciante para servidor
---------------------------------------------------

#### Renovar um certificado de licenciante para servidor

1.  Abra a página **Administração Global** e, próximo ao site em que deseja renovar um certificado, clique em **Administrar o RMS neste site**.

2.  Na página **Administração**, na área **Recursos do cluster**, clique no botão **Renovar**. A caixa de diálogo Renovar é aberta.

3.  Se o servidor estiver conectado à Internet, selecione a opção **Online** e clique em **Renovar** para renovar automaticamente o certificado de licenciante servidor.

4.  Se o servidor não estiver conectado à Internet, selecione a opção **Offline** e depois clique no botão **Exportar**. A caixa de diálogo **Download de Arquivo** aparece.

5.  Clique em **Salvar**. A caixa de diálogo **Salvar como** aparece.

    | ![](images/Cc747636.note(WS.10).gif)Observação                                                                                                                   |
    |-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | Na caixa de diálogo **Download de Arquivo**, não clique em **Abrir**. Se você clicar em **Abrir**, será exibida uma mensagem de erro, e o arquivo de solicitação de inscrição não será salvo. |

6.  Clique em **Salvar** para exportar a solicitação de renovação para um arquivo. Por padrão, o arquivo será salvo na área de trabalho e nomeado *nome\_servidor*RenewalRequest.xml, onde *nome\_servidor* será substituído pelo nome do seu servidor RMS. Você pode salvar o arquivo em um local diferente, escolhendo o local desejado no menu suspenso Salvar em. Também é possível alterar o nome do arquivo, digitando um novo nome em **Nome do arquivo**.

7.  Depois que você salvar o arquivo de solicitação de renovação, a caixa de diálogo **Download concluído** aparecerá. Você pode clicar em **Abrir** para exibir o código XML no arquivo, mas não altere o arquivo. Para abrir a pasta na qual o arquivo está armazenado, clique em **Abrir pasta**. Clique em **Fechar** se tiver terminado de ver o arquivo e de verificar o local.

8.  Transporte o arquivo de solicitação de renovação do servidor para um computador que possa ser conectado à Internet e navegue até o site do [Serviço de Inscrição]() (https://go.microsoft.com/fwlink/?LinkId=25828).

9.  Siga as instruções do site para obter um certificado de licenciante servidor.

10. Transporte o certificado de licenciante servidor de volta para o servidor raiz de certificação.

11. Na área **Recursos do cluster**, clique em **Renovar**. A caixa de diálogo **Renovar** é aberta.

12. Na caixa de diálogo **Renovar**, clique no botão **Procurar**, localize o certificado de licenciante servidor que você baixou e depois clique no botão **Importar**.

13. Clique em **Sim** para confirmar que você deseja importar esse certificado.

14. Depois que o certificado de licenciante servidor tiver sido renovado com êxito, a área **Recursos do cluster** será atualizada para exibir a nova data de vencimento do certificado de licenciante servidor.

Para obter mais informações sobre como renovar certificados do licenciante para servidor, consulte a seção "[Gerenciando certificados de licenciante para servidor](https://technet.microsoft.com/549979ad-13ee-4abc-8281-3e002a5a9561)".
