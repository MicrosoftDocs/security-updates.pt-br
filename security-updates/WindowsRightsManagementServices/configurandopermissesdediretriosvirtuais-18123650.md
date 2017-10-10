---
TOCTitle: Configurando permissões de diretórios virtuais
Title: Configurando permissões de diretórios virtuais
ms:assetid: '45112111-9608-45b1-9a86-7b313d0a1579'
ms:contentKeyID: 18123650
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747549(v=WS.10)'
---

Configurando permissões de diretórios virtuais
==============================================

Quando o descomissionamento tiver sido habilitado, ele estará disponível como serviço. Entretanto, o serviço de descomissionamento é um diretório virtual do IIS com permissões de acesso associadas. Para que os usuários utilizem esse serviço, você deve configurar permissões no diretório virtual e no arquivo decommission.asmx propriamente dito.

Por padrão, a Autenticação Integrada do Windows foi habilitada para o diretório virtual, mas apenas as contas de sistema e de administrador têm acesso ao arquivo real. Ao especificar as permissões para a lista de controle de acesso condicional do arquivo decommission.asmx, você poderá conceder acesso um grupo específico de usuários confiáveis para remover a proteção real do RMS ou poderá habilitar todos a acessarem o serviço.

Para que os usuários possam começar a usar o serviço de descomissionamento, o aplicativo do usuário precisa ser modificado, de modo que as solicitações de licença de uso possam ser enviadas para este novo canal de descomissionamento. No caso do Microsoft Office 2003, isto é feito com a adição de uma entrada do Registro no computador do usuário. Se você estiver usando o Office 2003, poderá ser usado o seguinte procedimento para executar essa etapa:

1.  Abra o Editor do Registro.
2.  Navegue até`HKEY_CURRENT_USER\Software\Microsoft\Office\11,0\Common\DRM` e adicione uma nova chave nomeada `Descomissionamento`.
3.  Na chave Descomissionamento, adicione a seguinte nova entrada **Valor de seqüência**, substituindo *seu-servidor-licença* pelo nome do seu servidor RMS:
    `http://`*seu-servidor-licença*`/_wmcs/licensing`
4.  Em seguida, clique com o botão direito do mouse na entrada e selecione **Modificar** para especificar os dados de valores para apontar para o serviço de descomissionamento:
    `http://`*seu-servidor-licença*`/_wmcs/decommission`

| ![](images/Cc747549.note(WS.10).gif)Observação                                                              |
|------------------------------------------------------------------------------------------------------------------------------------------|
| Poderá haver várias entradas para essa chave quando vários servidores RMS estiverem no modo de descomissionamento dentro da organização. |
