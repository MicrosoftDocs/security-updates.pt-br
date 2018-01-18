---
TOCTitle: Adicionando e removendo domínios de usuário confiáveis
Title: Adicionando e removendo domínios de usuário confiáveis
ms:assetid: 'd87b502d-5497-4ccd-badf-f6807d587cee'
ms:contentKeyID: 18123778
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747687(v=WS.10)'
---

Adicionando e removendo domínios de usuário confiáveis
======================================================

Por padrão, um servidor RMS pode emitir licenças de uso somente em relação a licenças de publicação que ele, ou outro servidor do cluster, tenha emitido. Se houver conteúdo publicado com outro servidor raiz de certificação em sua organização, por exemplo uma organização subsidiária em outra floresta, ou em uma organização separada, o servidor RMS poderá conceder licenças de uso a usuários para esse conteúdo, se você configurar um domínio de publicação confiável no servidor RMS. Ao adicionar um domínio de publicação confiável, você configura um relacionamento de confiança entre o servidor RMS e o outro servidor raiz de certificação importando o certificado de licenciante servidor do outro servidor. Não há limite para o número de domínios de publicação confiáveis que podem ser configurados para o servidor RMS.

Você pode remover um domínio de publicação confiável adicionado a qualquer momento removendo seu certificado da lista de certificados de domínios de publicação confiáveis.

Para adicionar um domínio de publicação confiável, é necessário importar o certificado de licenciante para servidor, a chave particular (se a chave particular for armazenada no software e não em um módulo de segurança de hardware) e todos os modelos de diretiva de direitos do servidor ou cluster RMS que deseja adicionar. O administrador deve primeiro exportar esses itens do servidor ou cluster a confiar em um arquivo protegido por senha e, em seguida, especificar a senha necessária para descriptografá-lo. O administrador deve colocar esse arquivo em uma pasta compartilhada e informar a senha a você. Em seguida, você pode importar o arquivo especificando o seu local e a senha. Para salvar o arquivo, a conta que está em execução no pool de aplicativos **Admin** deve ter permissões para a pasta compartilhada.

Para obter instruções detalhadas sobre como estabelecer um domínio de publicação confiável, consulte a seção "[Adicionar um domínio de publicação confiável](https://technet.microsoft.com/731416d8-ddf4-4d4a-9f1a-bbd1ea48fe3c)", mais adiante neste tema.

Se a chave particular estiver armazenada em um módulo de segurança de hardware, você deve transferi-la para o módulo de segurança de hardware que está no servidor confiável, seguindo as instruções na documentação desse módulo. Dependendo do tipo do módulo e da configuração dos dispositivos do módulo de segurança de hardware que está em cada servidor, talvez não seja possível transferir a chave particular de um módulo de segurança de hardware para outro. Analise a documentação do módulo de segurança de hardware para determinar se é possível transferir a chave particular sem perder dados que estão no módulo de segurança de hardware de destino. Se não for possível transferir a chave particular, não será possível estabelecer um domínio de publicação confiável entre os dois servidores.

| ![](images/Cc747687.note(WS.10).gif)Observação                                                                                                                                                                                                                                                                                                                                   |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Se você estiver usando um módulo de segurança de hardware para proteger a chave particular do RMS e estiver importando um certificado de licenciante servidor de uma instalação do RMS que usa proteção de chave particular baseado no software, deve especificar uma senha de chave particular na página Configurações de segurança de cada servidor RMS do cluster, antes de tentar importar o certificado. |
