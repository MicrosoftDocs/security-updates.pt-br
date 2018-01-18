---
TOCTitle: Criando listas de revogação
Title: Criando listas de revogação
ms:assetid: '1ef75199-3344-4225-84de-a863a777696a'
ms:contentKeyID: 18123549
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720208(v=WS.10)'
---

Criando listas de revogação
===========================

Para implementar a revogação, você precisa implantar uma lista de revogação, que é um documento XML que usa a linguagem XrML e lista as entidades de segurança que não devem mais ter acesso a conteúdo protegido por direitos. Você deve criar listas de revogação com carimbo de data/hora e assinadas apropriadamente usando a ferramenta Assinatura de Lista de Revogação (RLsigner.exe) fornecida com o RMS.

> [!Important]  
> Para assinar a lista de revogação usando RLsigner.exe, salve o arquivo de lista de revogação como um arquivo Unicode.

Exemplo de lista de revogação
-----------------------------

Este tópico apresenta um exemplo completo de lista de revogação que mostra cada um dos mecanismos de revogação possíveis. É possível usar este exemplo como um modelo para criar suas próprias listas de revogação.

Uma lista de revogação é um arquivo XML que usa a linguagem XrML.

O elemento BODY contém quatro elementos filhos:

-   **ISSUEDTIME**. Contém a data e a hora de emissão da lista de revogação. RLsigner.exe insere esse elemento no arquivo; o elemento é fornecido no exemplo apenas para demonstrar a estrutura geral do arquivo de lista de revogação.
-   **DESCRIPTOR**. Contém dados que identificam o arquivo como uma lista de revogação.
-   **ISSUER**. Contém dados que identificam a entidade que emite a lista de revogação.
-   **REVOCATIONLIST**. Contém os elementos filhos REVOKE que especificam entidades que são revogadas pela lista.

Um exemplo de arquivo de lista de revogação é mostrado a seguir.

> [!Note]  
> Os elementos ISSUEDTIME, PUBLICKEY e SIGNATURE podem ser omitidos, porque são inseridos ou substituídos por RLsigner.exe.

```
<?xml version="1.0" ?> 
<XrML xml:space=”preserve” version=”1.2”>
<BODY type="LICENSE" version="3.0">
<ISSUEDTIME>...</ISSUEDTIME> 
<DESCRIPTOR>
<OBJECT type="Revocation-List">
        <ID type="MS-GUID">{d6373cba-01f1-4f32-ac58-260f580af0f8}</ID>
</OBJECT>
</DESCRIPTOR>
<ISSUER>
<OBJECT type="Revocation-List">
        <ID type="acsii-tag">External revocation authority</ID>
        <NAME>Revocation list name</NAME>
        <ADDRESS type="URL">https://somedomain.com/revocation_list_file</ADDRESS>
</OBJECT>
<PUBLICKEY>...</PUBLICKEY>
</ISSUER>
<REVOCATIONLIST>
<REVOKE>...<\REVOKE>
<REVOKE>...<\REVOKE>
</REVOCATIONLIST>
<SIGNATURE>...</SIGNATURE>
</XrML>
```

> [!Caution]  
> Quando você especifica a URL na lista de revogação, não há mais suporte para um caminho UNC no RMS com SP1 ou no RMS com SP2. Você deve usar uma URL.

Depois de você ter definido os elementos REVOKE, a lista de revogação estará pronta para ser assinada.

Usando o elemento REVOKE
------------------------

Na lista de revogação de exemplo da seção Exemplo de lista de revogação, cada elemento REVOKE especifica uma entidade de segurança que deve ser revogada. A marca de abertura tem atributos de categoria e de tipo que definem o que está sendo revogado e por quais critérios de identificação. Elementos REVOKE diferentes possuem elementos filhos diferentes, de acordo com a ação especificada pelos atributos de categoria e de tipo.

Para obter mais informações sobre a especificação de elementos REVOKE, consulte as seguintes amostras:

-   [Revogando entidades com base em uma chave pública](#bkmk_1)
-   [Revogando certificados e licenças com base na GUID](#bkmk_2)
-   [Revogando certificados e licenças com base no valor hash](#bkmk_3)
-   [Revogando certificados e licenças com base na chave pública do emissor](#bkmk_4)
-   [Revogando certificados e licenças com base na identificação do emissor](#bkmk_5)
-   [Revogando conteúdo com base na identificação do conteúdo](#bkmk_6)
-   [Revogando certificados baseados na identificação de entidade de segurança](#bkmk_10)
-   [Revogando entidades de segurança com base em Windows Live ID](#bkmk_7)

#### Revogando entidades de segurança com base em uma chave pública
Este exemplo revoga uma entidade com base em sua chave pública. O conteúdo da marca &lt;PUBLICKEY&gt; aqui é do nó &lt;BODY&gt;&lt;ISSUEDPRINCIPALS&gt;&lt;PRINCIPAL&gt;&lt;PUBLICKEY&gt; do certificado que emitiu a chave.

```
<REVOKE category="principal" type="principal-key">
<PUBLICKEY>
        <ALGORITHM>RSA-1024</ALGORITHM>
        <PARAMETER name="public exponent">
        <VALUE encoding="integer32">65537</VALUE>
        </PARAMETER>
        <PARAMETER name="modulus">
        <VALUE encoding="base64" size="1024">
6Jn0kEAWU+1AFWtuUmBYL8Jza8tLhUv/BCmgcq/Pc08Au3DvXkH65s+0MEyZjM+71j3F1xaXUSst+wH2FjApkY1RxgL8VAKIuEvIy9hRrvY1YhJx/0Ite5fZeg2crUFrmoQgZzaJ50FvoakA2QMgZZgxoQmwiGE0y40cEJtIlE0=
        </VALUE>
        </PARAMETER>
</PUBLICKEY>
</REVOKE>
```

#### Revogando certificados e licenças com base na GUID

Este exemplo revoga um certificado ou licença por sua GUID (identificação global exclusiva). Você não pode usar um certificado ou licença com uma GUID correspondente quando esta lista de revogação é usada. O conteúdo da marca &lt;ID&gt; neste exemplo é do nó &lt;BODY&gt;&lt;DESCRIPTOR&gt;&lt;OBJECT&gt;&lt;ID&gt; do certificado ou licença que está sendo revogado. Também é possível revogar aplicativos por meio desse mecanismo, especificando a identificação do manifesto do aplicativo.

```
<REVOKE category="license" type="license-id">
        <OBJECT>
          <ID type="MS-GUID">{06BCB94D-43E5-419f-B180-AA9FD321ED7A}</ID>
        </OBJECT>
      </REVOKE>
```

#### Revogando por manifesto de aplicativo

Para revogar por manifesto de aplicativo, é necessário extrair do manifesto do aplicativo um dos seguintes itens: a identificação do emissor, a chave pública do emissor, a identificação da licença ou o hash da licença. No entanto, os manifestos de aplicativo têm codificação base 64 e, assim, essas informações não estão disponíveis em texto simples. Com o SDK (Software Development Kit) do Microsoft Windows RMS (Rights Management Services), é possível desenvolver um programa usando os métodos DRMConstructCertificateChain, DRMDeconstructCertificateChain e DRMDecode para decodificar o manifesto de aplicativo e obter as informações necessárias.

Caso queira evitar que um determinado aplicativo possa consumir conteúdo protegido por direitos, considere o uso da exclusão do aplicativo para proibir o cluster do RMS de conceder licenças de uso a esses aplicativos. A limitação da exclusão é que ela não impede que alguém com uma licença de uso válida descriptografe conteúdo protegido por direitos. Para obter mais informações sobre a exclusão de aplicativos, consulte [Excluindo aplicativos](https://technet.microsoft.com/b68ae4b2-b9ba-44ae-90cb-c88df600ec86), já mencionado neste tema.

#### Revogando certificados e licenças com base no valor hash

Este exemplo revoga um certificado ou licença por seu hash. O conteúdo da marca &lt;VALUE&gt; aqui é o hash SHA-1 dos caracteres UNICODE de &lt;BODY&gt; a &lt;/BODY&gt;, inclusive, no certificado ou licença. É possível localizar este valor hash na seção &lt;SIGNATURE&gt; do certificado ou licença. Também é possível revogar aplicativos por meio desse mecanismo, especificando o hash do manifesto do aplicativo.

```
<REVOKE category="license" type="license-hash">
        <DIGEST>
          <ALGORITHM>SHA1</ALGORITHM>
          <VALUE encoding="base64" size="160">
            ABfB4mcEslVCMEZR9reACqXHCoQ=
          </VALUE>
        </DIGEST>
      </REVOKE>
```

#### Revogando por manifesto de aplicativo

Para revogar por manifesto de aplicativo, é necessário extrair do manifesto do aplicativo um dos seguintes itens: a identificação do emissor, a chave pública do emissor, a identificação da licença ou o hash da licença. No entanto, os manifestos de aplicativo têm codificação base 64, assim, essas informações não estão disponíveis em texto sem formatação. Com o SDK do RMS, é possível desenvolver um programa usando os métodos DRMConstructCertificateChain, DRMDeconstructCertificateChain e DRMDecode para decodificar o manifesto de aplicativo e obter as informações necessárias.

Caso queira evitar que um determinado aplicativo possa consumir conteúdo protegido por direitos, considere o uso da exclusão do aplicativo para proibir o cluster do RMS de conceder licenças de uso a esses aplicativos. A limitação da exclusão é que ela não pode impedir que alguém com uma licença de uso válida descriptografe o conteúdo protegido pelo RMS. Para obter mais informações sobre a exclusão de aplicativos, consulte [Excluindo aplicativos](https://technet.microsoft.com/b68ae4b2-b9ba-44ae-90cb-c88df600ec86), já mencionado neste tema.

#### Revogando certificados e licenças com base na chave pública do emissor

Este exemplo revoga todos os certificados e licenças emitidos pelo proprietário da chave pública especificada. O conteúdo da marca &lt;PUBLICKEY&gt; aqui é o nó &lt;BODY&gt;&lt;ISSUER&gt;&lt;PUBLICKEY&gt; dos certificados ou licenças que estão sendo revogados.

```
<REVOKE category="license" type="issuer-key">
        <PUBLICKEY>
          <ALGORITHM>RSA-1024</ALGORITHM>
          <PARAMETER name="public exponent">
            <VALUE encoding="integer32">65537</VALUE>
          </PARAMETER>
          <PARAMETER name="modulus">
            <VALUE encoding="base64" size="1024">
AAn0kEAWU+1AFWtuUmBYL8Jza8tLhUv/BCmgcq/Pc08Au3DvXkH65s+0MEyZjM+71j3F1xaXUSst+wH2FjApkY1RxgL8VAKIuEvIy9hRrvY1YhJx/0Ite5fZeg2crUFrmoQgZzaJ50FvoakA2QMgZZgxoQmwiGE0y40cEJtIlE0=
            </VALUE>
          </PARAMETER>
        </PUBLICKEY>
      </REVOKE>
```
#### Revogando certificados e licenças com base na identificação do emissor

Este exemplo revoga um conjunto de certificados ou licenças pela identificação do emissor. O conteúdo da marca &lt;ID&gt; aqui é o nó &lt;BODY&gt;&lt;ISSUER&gt;&lt;OBJECT&gt;&lt;ID&gt; dos certificados ou licenças que estão sendo revogados.

```
<REVOKE category="license" type="issuer-id">
        <OBJECT type="MS-DRM-Server">
          <ID type="MS-GUID">{2BE9E200-3040-41B9-8832-D4D0445EBBD6}</ID> 
        </OBJECT>
      </REVOKE>
```

> [!Note]  
> Ao especificar o tipo de identificação, certifique-se de que não existe nenhum retorno de carro entre a GUID (identificação global exclusiva) e a marca de fechamento. Se for adicionado um retorno de carro inadvertidamente, o cliente do RMS não poderá analisar a lista de revogação.

#### Revogando conteúdo com base na identificação do conteúdo

Este exemplo revoga conteúdo protegido por sua identificação de conteúdo. Esse é o método preferencial que você deve usar para revogar conteúdo porque a identificação do conteúdo é a mesma em todas as licenças de uso criadas a partir de uma determinada licença de publicação. O valor do nó &lt;OBJECT&gt; aqui pode ser encontrado no nó &lt;BODY&gt;&lt;WORK&gt;&lt;OBJECT&gt; de uma licença de publicação ou de uma licença de uso do conteúdo.

```
<REVOKE category="content" type="content-id">
        <OBJECT type="Microsoft Office Document">
          <ID type="MS-GUID">{8702641D-3512-4AA4-A584-84C703A5B5C0}</ID>
        </OBJECT>
      </REVOKE>
```

> [!Note]  
> Ao especificar o tipo de identificação, certifique-se de que não existe nenhum retorno de carro entre a GUID (identificação global exclusiva) e a marca de fechamento. Se for adicionado um retorno de carro inadvertidamente, o cliente do RMS não poderá analisar a lista de revogação.

#### Revogando entidades de segurança com base na conta do Windows

Este exemplo revoga um usuário ou entidade habilitante por sua conta do Windows. O conteúdo do elemento &lt;OBJECT&gt; aqui é do nó &lt;BODY&gt;&lt;ISSUEDPRINCIPALS&gt;&lt;PRINCIPAL&gt;&lt;OBJECT&gt; de um certificado de conta de direitos ou licença de uso.

```
<REVOKE category="principal" type="principal-id">
        <OBJECT type="Group-Identity">
          <ID type="Windows">{Windows account SID}</ID> 
          <NAME>{E-mail address}</NAME> 
        </OBJECT>
      </REVOKE>
```
> [!Note]  
> Ao especificar o tipo de identificação, certifique-se de que não existe nenhum retorno de carro entre a GUID (identificação global exclusiva) e a marca de fechamento. Se for adicionado um retorno de carro inadvertidamente, o cliente do RMS não poderá analisar a lista de revogação.

#### Revogando entidades de segurança com base em Windows Live ID

Este exemplo revoga um usuário ou entidade habilitante por sua Windows Live ID. O conteúdo do elemento &lt;OBJECT&gt; aqui é do nó &lt;BODY&gt;&lt;ISSUEDPRINCIPALS&gt;&lt;PRINCIPAL&gt;&lt;OBJECT&gt; de um certificado de conta de direitos ou licença de uso.

```
<REVOKE category="principal" type="principal-id">
        <OBJECT type="Group-Identity">
          <ID type="Passport">{PUID}</ID> 
          <NAME>michael@contoso.com</NAME> 
        </OBJECT>
      </REVOKE>
```
> [!Note]  
> Ao especificar o tipo de identificação, certifique-se de que não existe nenhum retorno de carro entre a PUID (identificação principal exclusiva) e a marca de fechamento. Se for adicionado um retorno de carro inadvertidamente, o cliente do RMS não poderá analisar a lista de revogação.

Inserindo uma assinatura em uma lista de revogação
--------------------------------------------------

Quando conclui a criação de uma lista de revogação, você deve inserir uma assinatura na lista de revogação, conforme descrito neste tópico. Em seguida, você pode disponibilizar a lista de revogação a usuários da URL especificada no modelo de diretiva de direitos associado.

A primeira etapa que deve ser usada para inserir uma assinatura é gerar um par de chaves e um arquivo de chave para a lista de revogação usando a ferramenta Nome Forte (Sn.exe). A ferramenta Sn.exe é fornecida com o SDK do Microsoft .NET Framework 1.1, que está disponível no site da Microsoft em [http://go.microsoft.com/fwlink/?LinkId=104796](http://go.microsoft.com/fwlink/?linkid=104796).

O arquivo da lista de revogação deve ter sido salvo como Unicode para que seja possível assiná-la usando a ferramenta RLsigner.exe

**Para usar o Sn.exe para gerar um novo par de chaves e gravá-lo em um arquivo**
1.  Crie a chave particular. No prompt de comando, digite o seguinte comando e pressione ENTER:

    **sn -k** *arquivo\_de\_chave\_particular***.snk**

    em que *arquivo\_de\_chave\_particular* é o nome do arquivo de chave.

2.  Use Sn.exe para extrair a chave pública do arquivo de par de chaves criado na Etapa 1 e exportá-la para um arquivo separado. Digite o comando a seguir e pressione ENTER:

    **sn -p** *arquivo\_de\_chave\_particular arquivo\_de\_chave\_pública*

    em que *arquivo\_de\_chave\_particular* é o nome do arquivo de chave particular criado na Etapa 1 e *arquivo\_de\_chave\_pública* é o nome do arquivo em que a chave pública exportada será armazenada.

3.  Altere a extensão do arquivo de chave particular (criado na Etapa 1) de .snk para .dat para uso com RLsigner.exe.

4.  Use RLsigner.exe para inserir uma assinatura em um arquivo de lista de revogação. Essa ferramenta é fornecida com o RMS. Por padrão, está localizada no diretório %systemdrive%\\Arquivos de Programas\\Windows Rights Management Services\\Ferramentas.

> [!Note]  
> RLsigner.exe não oferece suporte a nomes de arquivo que incluam espaços.

Usando RLsigner.exe
-------------------

Quando você executa RLsigner.exe, ele primeiro cria uma assinatura usando a chave particular fornecida no arquivo de chave. Em seguida, ela cria um arquivo de saída com base no arquivo de lista de revogação fornecido.

> [!Important]  
> O arquivo de lista de revogação deve ter sido salvo como Unicode para usar RLsigner.exe.

Para usar RLsigner.exe para assinar a lista de revogação, digite o seguinte comando em um prompt de comando:

**rlsigner.exe** *arquivo\_entrada* **{-f** *arquivo\_chave* **| -h** *nome\_recipiente* **CSP}** *arquivo\_saída*

Use as seguintes informações para preencher os parâmetros de entrada do comando:

###  

<p></p> 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Parâmetro</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><em>arquivo_entrada</em></td>
<td style="border:1px solid black;">Nome do arquivo de lista de revogação compatível com XrML que você preparou</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>arquivo_chave</em></td>
<td style="border:1px solid black;">Nome do arquivo que contém as chaves pública e particular que você gerou</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>nome_recipiente</em></td>
<td style="border:1px solid black;">Nome do recipiente da chave</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>arquivo_saída</em></td>
<td style="border:1px solid black;">Nome do arquivo de lista de revogação assinada que a ferramenta criará</td>
</tr>
</tbody>
</table>

> [!Note]  
> RLsigner.exe não oferece suporte a nomes de arquivo que incluam espaços.
  
Os exemplos a seguir descrevem como você pode usar RLsigner.exe em um prompt de comando com provedores de serviço de criptografia diferentes:
  
-   Exemplo de sintaxe da linha de comando que usa um arquivo de chave:  
    **rlsigner.exe rl.xml -f key.dat output.xml**  
-   Exemplo de sintaxe da linha de comando que usa um módulo de segurança de hardware:  
    **rlsigner.exe rl.xml -h Container CSP output.xml**
  
RLsigner.exe fornece informações básicas sobre erros e êxitos em seu código de retorno. A tabela a seguir descreve os possíveis códigos de retorno.
  
###  

<p></p> 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Código de retorno</th>
<th style="border:1px solid black;" >Descrição</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">0</td>
<td style="border:1px solid black;">Êxito</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">-1</td>
<td style="border:1px solid black;">Não é possível ler o arquivo de origem</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">-2</td>
<td style="border:1px solid black;">Não é possível ler o arquivo de chave</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">-3</td>
<td style="border:1px solid black;">Arquivo de chave inválido</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">-4</td>
<td style="border:1px solid black;">Arquivo de origem inválido</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">-5</td>
<td style="border:1px solid black;">Não é possível gravar o arquivo de saída</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">-6</td>
<td style="border:1px solid black;">Erro desconhecido</td>
</tr>
</tbody>
</table>
  
Você pode agendar a assinatura de listas de revogação com base na taxa de atualização especificada para o servidor.
  
É possível automatizar o processo de assinatura de lista de revogação usando um script. A amostra de VBScript a seguir chama o RLsigner.exe e grava os resultados no log de eventos do sistema.

```
const EVT_SUCCESS       = 0
const EVT_ERROR         = 1
const EVT_WARNING       = 2
const EVT_INFORMATION   = 4
const EVT_AUDIT_SUCCESS = 8
const EVT_AUDIT_FAILURE = 16

Dim WshShell, oExec

Set WshShell = CreateObject( "WScript.Shell" )
Set oExec = WshShell.Exec("rlsigner.exe input_file key_file output_file")
Do While oExec.Status = 0
     WScript.Sleep 100
Loop

if WshShell.ExitCode <> 0 Then
    WshShell.LogEvent EVT_ERROR, "RLsigner failed with error """ + WshShell.ExitCode + """"
else
    WshShell.LogEvent EVT_SUCCESS, "RLsigner completed successfully"
end if
```