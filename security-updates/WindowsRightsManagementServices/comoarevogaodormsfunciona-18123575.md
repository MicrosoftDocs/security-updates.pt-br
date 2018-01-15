---
TOCTitle: Como a revogação do RMS funciona
Title: Como a revogação do RMS funciona
ms:assetid: '469e3938-a59b-4c92-9779-ead64e724d00'
ms:contentKeyID: 18123575
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720263(v=WS.10)'
---

Como a revogação do RMS funciona
================================

A revogação funciona evitando vinculação, o processo que permite que um usuário consuma conteúdo, quando uma entidade revogada está envolvida na solicitação de vinculação. A revogação é implementada por meio de listas de revogação que são distribuídas aos computadores clientes. Essas listas são arquivos XrML assinados que especificam o conteúdo, os aplicativos, os usuários ou outras entidades que foram revogadas pela entidade que emite a lista.

Sempre que um usuário tenta consumir conteúdo protegido, o aplicativo associado e habilitado para RMS envia uma solicitação para o direito apropriado, em uma solicitação vinculada, ao cliente do RMS. Por exemplo, se o usuário tentar abrir um arquivo, o aplicativo solicitará um direito de exibição que permitirá que o arquivo seja aberto. Se o usuário tentar editar o arquivo, o aplicativo solicitará um direito de edição.

Enquanto processa a solicitação vinculada, o cliente do RMS percorre as seguintes etapas:

1.  Avalia a licença de uso de qualquer requisito da lista de revogação.
2.  Se a licença de uso requerer revogação, o componente cliente verificará se a lista de revogação especificada está presente, registrada e atual, de acordo com o intervalo de atualização especificado na licença de uso.
3.  Ele verifica se a entidade que assinou a lista de revogação está especificada na licença de uso como uma entidade que tem permissão para revogar a licença.
4.  Se essas verificações forem bem-sucedidas, o componente cliente determinará se qualquer entidade envolvida na solicitação de vinculação original foi revogada. Em caso positivo, ele recusa a solicitação de vinculação.

O administrador pode distribuir as listas de revogação aos computadores clientes, ou um aplicativo habilitado para RMS pode baixá-las para o computador, quando isso for exigido por uma licença de uso. Quando uma lista de revogação é usada para vincular uma parte de conteúdo, ela é registrada e pode ser usada para solicitações de vinculação com outras licenças de uso, desde que o aplicativo permaneça aberto. Quando o aplicativo é fechado, o registro da lista de revogação é cancelado.

O diagrama a seguir exibe o processo de vinculação e mostra como a revogação funciona nele.

![](images/Cc720263.81aa2d70-d261-49ad-b446-96a2eddba1a5(WS.10).gif)

A revogação é opcional. O administrador do RMS pode exigir a revogação, especificando-a em um ou mais modelos de diretiva de direitos da organização. Quando a revogação é requerida, uma licença não pode ser vinculada a não ser que a lista de revogação requerida esteja presente, registrada no computador do usuário e não seja mais antiga que o intervalo de atualização especificado na licença de uso.

É importante observar, no entanto, que a revogação ainda pode ter efeito para uma determinada licença de uso, mesmo quando a licença de uso não a requer. A revogação entra em efeito sempre que qualquer emissor de qualquer certificado que esteja na cadeia de confiança que está envolvida em uma solicitação de vinculação tenha emitido uma lista de revogação que está registrada em um computador cliente. Nesse cenário, a lista de revogação é usada para processar solicitações de vinculação, mesmo que as licenças de uso que estavam envolvidas não requeiram revogação. Isso será verdadeiro até o fechamento do aplicativo habilitado para RMS, o que cancelará o registro da lista de revogação.

Por exemplo, se um usuário tentar consumir uma parte do conteúdo, cuja licença de uso, emitida pela entidade A, exige uma lista de revogação emitida pela entidade A, o aplicativo habilitado para RMS obterá a lista de revogação na URL especificada na licença de uso e depois a registrará. Ao processar a solicitação vinculada, o cliente do RMS verifica possíveis revogações na lista de revogação.

Depois, deixando aberto o aplicativo habilitado para RMS, o usuário tenta consumir uma segunda parte de conteúdo, cuja licença de uso também foi emitida pela entidade A. Embora essa licença de uso não inclua uma condição de revogação, a lista de revogação da entidade A encontra-se registrada no computador do usuário. Nessa situação, o componente cliente examinará a lista de revogação antes de processar a solicitação de vinculação.

O usuário então tenta consumir uma parte de conteúdo cuja licença de uso foi emitida pela entidade C. A licença de uso não inclui uma condição de revogação. Como somente a lista de revogação registrada no computador cliente é a lista emitida pela entidade A, e a entidade A não está na cadeia de confiança da licença de uso, nenhuma revogação estará em vigor para a vinculação.

Finalmente, o usuário fecha o aplicativo habilitado para RMS e, mais tarde, reabre a segunda parte de conteúdo que não incluía uma condição de revogação. Como a lista de revogação emitida pela entidade A teve o seu registro cancelado quando o aplicativo foi fechado, o cliente do RMS não a examina para processar a solicitação vinculada.
