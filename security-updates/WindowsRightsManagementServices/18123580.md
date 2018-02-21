---
TOCTitle: Usando o grupo de superusuários
Title: Usando o grupo de superusuários
ms:assetid: '0febcb3e-7124-4e51-971a-1013b928d33b'
ms:contentKeyID: 18123580
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720198(v=WS.10)'
---

Usando o grupo de superusuários
===============================

Durante a configuração, o RMS cria um grupo especial de superusuários que tem controle total sobre todo o conteúdo protegido por direitos. Os membros do grupo de superusuários recebem direitos completos de proprietários em todas as licenças de uso emitidas pelo servidor ou cluster RMS no qual o grupo de superusuários está configurado. Isso significa que membros desse grupo podem descriptografar todos os arquivos de conteúdo protegido e remover sua proteção. Por exemplo, um membro desse grupo pode remover a proteção de arquivos publicados por um funcionário que saiu da empresa, para que um novo proprietário possa publicar e gerenciar os arquivos.

Por padrão, o grupo de superusuários não possui membros, nem mesmo administradores. Quando você usa o site de Administração, pode especificar um grupo de segurança do Active Directory para ser usado como o grupo de superusuários do RMS. É possível usar um grupo existente do Active Directory ou criar um novo grupo para este fim. O grupo deve ficar na mesma floresta do Active Directory que a instalação do RMS. Qualquer conta de usuário que seja membro do grupo especificado como o grupo de superusuários do RMS recebe automaticamente as permissões do grupo de superusuários.

Para obter informações sobre como especificar um grupo de superusuários para o RMS, consulte [Configurar um grupo de superusuários](https://technet.microsoft.com/f2ef847e-2824-471f-9079-5c343094aba8), mais adiante neste tema.


> [!NOTE]  
> Para designar um grupo como o grupo de superusuários do RMS, o grupo precisa existir na mesma floresta do Active Directory que a instalação do RMS. As propriedades desse grupo devem incluir um endereço de email, incluindo um nome de domínio totalmente qualificado que seja igual ao nome da conta. O endereço de email deve estar no formato *nome\_grupo*@*nome\_domínio*.
