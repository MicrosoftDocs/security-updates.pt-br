---
TOCTitle: 'Perguntas freqüentes sobre o RMS: Certificados, chaves e criptografia'
Title: 'Perguntas freqüentes sobre o RMS: Certificados, chaves e criptografia'
ms:assetid: 'ad8cc088-1dea-44c2-be68-9091129f0f12'
ms:contentKeyID: 18123812
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747725(v=WS.10)'
---

Perguntas freqüentes sobre o RMS: Certificados, chaves e criptografia
=====================================================================

Perguntas freqüentes sobre certificados, chaves e criptografia do RMS
---------------------------------------------------------------------

-   [Quais algoritmos de criptografia são usados no RMS?](#bkmk_10)
-   [O RMS usa criptografia certificada pelo FIPS?](#bkmk_11)
-   [Para modelos ou licenças de publicação que concedem permissões para uma lista de distribuição em vez de concedê-las para usuários individuais, as licenças de uso são tratadas de modo diferente, a fim de avaliar os membros de forma dinâmica?](#bkmk_12)
-   [Quando o RMS é usado em um quiosque, é emitido um certificado de conta de direitos temporário. Qual é a diferença entre um certificado de conta de direitos temporário e um certificado de conta de direitos padrão? Como o RMS detecta que está sendo usado em um quiosque?](#bkmk_13)
-   [Quando um certificado de conta de direitos temporário é usado?](#bkmk_14)
-   [O RMS emite certificados X.509v3?](#bkmk_15)
-   [Onde os certificados XrML são armazenados?](#bkmk_16)
-   [Onde o par de chaves particulares/públicas da máquina é armazenado?](#bkmk_17)
-   [Onde o par de chaves particulares/públicas do cliente é armazenado?](#bkmk_18)
-   [AES é um algoritmo simétrico. Como as chaves são passadas com segurança entre o servidor e o usuário?](#bkmk_19)

<span id="BKMK_10"></span>
#### Quais algoritmos de criptografia são usados no RMS?

O RMS usa chaves RSA de 2048 bits para o servidor RMS e chaves RSA de 1024 bits para o par de chaves do usuário e da máquina.

<span id="BKMK_11"></span>
#### O RMS usa criptografia certificada pelo FIPS?

No RMS com Service Pack 1 ou posterior, os cofres gerados pelo aplicativo cliente do RMS usam criptografia AES certificada pelo FIPS quando o cliente é instalado em um computador que executa o Windows XP ou Windows Server 2003. No entanto, se o cliente do RMS estiver instalado em computadores que executam o Windows 2000, uma biblioteca AES certificada pelo FIPS não estará instalada. Assim, os cofres não serão compatíveis com FIPS.

<span id="BKMK_12"></span>
#### Para modelos ou licenças de publicação que concedem permissões para uma lista de distribuição em vez de concedê-las para usuários individuais, as licenças de uso são tratadas de modo diferente, a fim de avaliar os membros de forma dinâmica?

As licenças de uso são sempre emitidas para usuários individuais. Se uma licença de publicação ou modelo der nome a um grupo, o RMS avaliará a participação do grupo no momento da emissão da licença de uso. Se o usuário que está solicitando a licença for membro desse grupo, a licença de uso será emitida para a identidade do usuário.

<span id="BKMK_13"></span>
#### Quando o RMS é usado em um quiosque, é emitido um certificado de conta de direitos temporário. Qual é a diferença entre um certificado de conta de direitos temporário e um certificado de conta de direitos padrão? Como o RMS detecta que está sendo usado em um quiosque?

O aplicativo habilitado para RMS deve determinar se o cliente do RMS deve solicitar um certificado de conta de direitos temporário ou padrão para o usuário. Não há método de detecção para essa situação. O Microsoft Office 2003 é um exemplo de aplicativo habilitado para RMS que permite que o usuário selecione o certificado de conta de direitos apropriado.

A principal diferença entre um certificado de conta de direitos temporário e um certificado de conta de direitos padrão é a presença do identificador de segurança do usuário e a especificação do período de validade. Os certificados de conta de direitos temporários não incluem um identificador de segurança (SID) do usuário e têm um período de validade especificado em minutos. O período de validade padrão para um certificado de conta de direitos temporário é 15 minutos. No entanto, os certificados de conta de direitos padrão incluem um SID do usuário e têm o período de validade especificado em dias. O período de validade padrão para um certificado de conta de direitos padrão é 365 dias.

<span id="BKMK_14"></span>
#### Quando um certificado de conta de direitos temporário é usado?

Um certificado de conta de direitos temporário é criado para habilitar um usuário a consumir conteúdo protegido pelo RMS em computadores que atendam a um dos seguintes critérios:

-   Um computador que não seja membro da mesma floresta que a instalação do RMS a partir da qual o certificado de conta de direitos foi obtido.
-   Um computador que não seja membro da mesma floresta em que a conta de usuário está localizada.
-   O usuário não tem certeza se usará a mesma máquina mais tarde.

Exemplos de computadores que se encaixam nesses critérios são terminais de aeroportos, bibliotecas públicas e Cyber cafés.

<span id="BKMK_15"></span>
#### O RMS emite certificados X.509v3?

Não. O RMS emite certificados XrML destinados a representar usuários e uma expressão de diretivas que esteja além do escopo dos certificados X.509v3.

<span id="BKMK_16"></span>
#### Onde os certificados XrML são armazenados?

Um sistema RMS usa os seguintes certificados e licenças que são salvos em XrML no computador cliente:

-   Certificado de máquina
    Nome do arquivo: arquivo CERT-Machine.drm
    Local: %USERPROFILE%\\Local Settings\\Application Data\\Microsoft\\DRM\\
-   Certificado de conta de direitos
    Prefixo do nome do arquivo: GIC
    Local: %USERPROFILE%\\Local Settings\\Application Data\\Microsoft\\DRM
-   Certificado de licenciante para cliente
    Prefixo do nome do arquivo: CLC
    Local: %USERPROFILE%\\Local Settings\\Application Data\\Microsoft\\DRM
-   Licença de uso
    Prefixo do nome do arquivo: EUL
    Local: %USERPROFILE%\\Local Settings\\Application Data\\Microsoft\\DRM

| ![](images/Cc747725.note(WS.10).gif)Observação                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Uma conta de usuário possui um único certificado de máquina, um único arquivo GIC e um único arquivo CLC, mas diversos arquivos EUL para cada conteúdo acessado. |

| ![](images/Cc747725.note(WS.10).gif)Observação                                 |
|-------------------------------------------------------------------------------------------------------------|
| Para o cliente do RMS integrado ao Windows Vista®, o local é %USERPROFILE%\\AppData\\Local\\Microsoft\\DRM. |

<span id="BKMK_17"></span>
#### Onde o par de chaves particulares/públicas da máquina é armazenado?

A chave particular da máquina é armazenada com segurança e protegida por chaves de criptografia relacionadas às credenciais de logon do usuário e à configuração da máquina.

<span id="BKMK_18"></span>
#### Onde o par de chaves particulares/públicas do cliente é armazenado?

O par de chaves para uma conta de usuário é armazenado no certificado de conta de direitos.

<span id="BKMK_19"></span>
#### AES é um algoritmo simétrico. Como as chaves são passadas com segurança entre o servidor e o usuário?

No sistema, são usadas tanto chaves simétricas como chaves públicas/particulares. O conteúdo é criptografado com uma chave simétrica, mas as outras chaves no sistema (usuário, máquina e servidor) são chaves públicas/particulares RSA. A chave simétrica de conteúdo é sempre criptografada nas diversas licenças: para a chave pública RSA do servidor RMS na licença de publicação ou para a chave pública RSA do usuário na licença de uso.
