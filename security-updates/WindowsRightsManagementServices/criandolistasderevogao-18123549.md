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

| ![](images/Cc720208.Important(WS.10).gif)Importante                                      |
|-----------------------------------------------------------------------------------------------------------------------|
| Para assinar a lista de revogação usando RLsigner.exe, salve o arquivo de lista de revogação como um arquivo Unicode. |

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

| ![](images/Cc720208.note(WS.10).gif)Observação                                               |
|---------------------------------------------------------------------------------------------------------------------------|
        ```
| ![](images/Cc720208.Caution(WS.10).gif)Cuidado                                                                           |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| Quando você especifica a URL na lista de revogação, não há mais suporte para um caminho UNC no RMS com SP1 ou no RMS com SP2. Você deve usar uma URL. |

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

<span id="BKMK_1"></span>
#### Revogando entidades de segurança com base em uma chave pública

        ```

<span id="BKMK_2"></span>
#### Revogando certificados e licenças com base na GUID

        ```
#### Revogando por manifesto de aplicativo

Para revogar por manifesto de aplicativo, é necessário extrair do manifesto do aplicativo um dos seguintes itens: a identificação do emissor, a chave pública do emissor, a identificação da licença ou o hash da licença. No entanto, os manifestos de aplicativo têm codificação base 64 e, assim, essas informações não estão disponíveis em texto simples. Com o SDK (Software Development Kit) do Microsoft Windows RMS (Rights Management Services), é possível desenvolver um programa usando os métodos DRMConstructCertificateChain, DRMDeconstructCertificateChain e DRMDecode para decodificar o manifesto de aplicativo e obter as informações necessárias.

Caso queira evitar que um determinado aplicativo possa consumir conteúdo protegido por direitos, considere o uso da exclusão do aplicativo para proibir o cluster do RMS de conceder licenças de uso a esses aplicativos. A limitação da exclusão é que ela não impede que alguém com uma licença de uso válida descriptografe conteúdo protegido por direitos. Para obter mais informações sobre a exclusão de aplicativos, consulte [Excluindo aplicativos](https://technet.microsoft.com/b68ae4b2-b9ba-44ae-90cb-c88df600ec86), já mencionado neste tema.

<span id="BKMK_3"></span>
#### Revogando certificados e licenças com base no valor hash

        ```
#### Revogando por manifesto de aplicativo

Para revogar por manifesto de aplicativo, é necessário extrair do manifesto do aplicativo um dos seguintes itens: a identificação do emissor, a chave pública do emissor, a identificação da licença ou o hash da licença. No entanto, os manifestos de aplicativo têm codificação base 64, assim, essas informações não estão disponíveis em texto sem formatação. Com o SDK do RMS, é possível desenvolver um programa usando os métodos DRMConstructCertificateChain, DRMDeconstructCertificateChain e DRMDecode para decodificar o manifesto de aplicativo e obter as informações necessárias.

Caso queira evitar que um determinado aplicativo possa consumir conteúdo protegido por direitos, considere o uso da exclusão do aplicativo para proibir o cluster do RMS de conceder licenças de uso a esses aplicativos. A limitação da exclusão é que ela não pode impedir que alguém com uma licença de uso válida descriptografe o conteúdo protegido pelo RMS. Para obter mais informações sobre a exclusão de aplicativos, consulte [Excluindo aplicativos](https://technet.microsoft.com/b68ae4b2-b9ba-44ae-90cb-c88df600ec86), já mencionado neste tema.

<span id="BKMK_4"></span>
#### Revogando certificados e licenças com base na chave pública do emissor

        ```

<span id="BKMK_5"></span>
#### Revogando certificados e licenças com base na identificação do emissor

        ```
| ![](images/Cc720208.note(WS.10).gif)Observação                                                                                                                                                                                                               |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ao especificar o tipo de identificação, certifique-se de que não existe nenhum retorno de carro entre a GUID (identificação global exclusiva) e a marca de fechamento. Se for adicionado um retorno de carro inadvertidamente, o cliente do RMS não poderá analisar a lista de revogação. |

<span id="BKMK_6"></span>
#### Revogando conteúdo com base na identificação do conteúdo

        ```
| ![](images/Cc720208.note(WS.10).gif)Observação                                                                                                                                                                                                               |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ao especificar o tipo de identificação, certifique-se de que não existe nenhum retorno de carro entre a GUID (identificação global exclusiva) e a marca de fechamento. Se for adicionado um retorno de carro inadvertidamente, o cliente do RMS não poderá analisar a lista de revogação. |

<span id="BKMK_10"></span>
#### Revogando entidades de segurança com base na conta do Windows

        ```
| ![](images/Cc720208.note(WS.10).gif)Observação                                                                                                                                                                               |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ao especificar o tipo de identificação, verifique se não há retornos de carro entre a SID da conta do Windows e a marca de fechamento. Se for adicionado um retorno de carro inadvertidamente, o cliente do RMS não poderá analisar a lista de revogação. |

<span id="BKMK_7"></span>
#### Revogando entidades de segurança com base em Windows Live ID

        ```
| ![](images/Cc720208.note(WS.10).gif)Observação                                                                                                                                                                                                                  |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ao especificar o tipo de identificação, certifique-se de que não existe nenhum retorno de carro entre a PUID (identificação principal exclusiva) e a marca de fechamento. Se for adicionado um retorno de carro inadvertidamente, o cliente do RMS não poderá analisar a lista de revogação. |

<span id="BKMK_8"></span>
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

| ![](images/Cc720208.note(WS.10).gif)Observação |
|-----------------------------------------------------------------------------|
| RLsigner.exe não oferece suporte a nomes de arquivo que incluam espaços.    |

<span id="BKMK_9"></span>
Usando RLsigner.exe
-------------------

Quando você executa RLsigner.exe, ele primeiro cria uma assinatura usando a chave particular fornecida no arquivo de chave. Em seguida, ela cria um arquivo de saída com base no arquivo de lista de revogação fornecido.

| ![](images/Cc720208.Important(WS.10).gif)Importante         |
|------------------------------------------------------------------------------------------|
| O arquivo de lista de revogação deve ter sido salvo como Unicode para usar RLsigner.exe. |

Para usar RLsigner.exe para assinar a lista de revogação, digite o seguinte comando em um prompt de comando:

**rlsigner.exe** *arquivo\_entrada* **{-f** *arquivo\_chave* **| -h** *nome\_recipiente* **CSP}** *arquivo\_saída*

Use as seguintes informações para preencher os parâmetros de entrada do comando:

###  

 
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
  
| ![](images/Cc720208.note(WS.10).gif)Observação |  
|-----------------------------------------------------------------------------|  
| RLsigner.exe não oferece suporte a nomes de arquivo que incluam espaços.    |
  
Os exemplos a seguir descrevem como você pode usar RLsigner.exe em um prompt de comando com provedores de serviço de criptografia diferentes:
  
-   Exemplo de sintaxe da linha de comando que usa um arquivo de chave:  
    **rlsigner.exe rl.xml -f key.dat output.xml**  
-   Exemplo de sintaxe da linha de comando que usa um módulo de segurança de hardware:  
    **rlsigner.exe rl.xml -h Container CSP output.xml**
  
RLsigner.exe fornece informações básicas sobre erros e êxitos em seu código de retorno. A tabela a seguir descreve os possíveis códigos de retorno.
  
###  

 
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
  
<codesnippet asp="http://msdn2.microsoft.com/asp" language displaylanguage="Visual Basic">const EVT\_SUCCESS = 0 const EVT\_ERROR = 1 const EVT\_WARNING = 2 const EVT\_INFORMATION = 4 const EVT\_AUDIT\_SUCCESS = 8 const EVT\_AUDIT\_FAILURE = 16 Dim WshShell, oExec Set WshShell = CreateObject( "WScript.Shell" ) Set oExec = WshShell.Exec("rlsigner.exe input\_file key\_file output\_file") Do While oExec.Status = 0 WScript.Sleep 100 Loop if WshShell.ExitCode &lt;&gt; 0 Then WshShell.LogEvent EVT\_ERROR, "RLsigner failed with error """ + WshShell.ExitCode + """" else WshShell.LogEvent EVT\_SUCCESS, "RLsigner completed successfully" end if  
```
