---
TOCTitle: Distribuindo o cliente do RMS
Title: Distribuindo o cliente do RMS
ms:assetid: '4b8dd930-4105-4e73-918c-12d2b05d5fb5'
ms:contentKeyID: 18123582
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720266(v=WS.10)'
---

Distribuindo o cliente do RMS
=============================

O cliente do RMS é incorporado ao sistema operacional Windows Vista®, portanto, não é mais uma instalação à parte. Os sistemas operacionais anteriores ao Windows Vista requerem que você instale o software cliente do RMS e depois o ative.

O processo de ativação estabelece um cofre e um certificado de computador para o usuário que está conectado no momento. A ativação é um processo local e não exige uma conexão de rede. Se a ativação for bem-sucedida, a primeira solicitação para uma licença de uso por um aplicativo habilitado para RMS obterá um certificado de usuário para o usuário. O cliente do RMS pode ser instalado em cada computador cliente da organização usando-se a Diretiva de Grupo, o Windows Update ou um script administrativo.

| ![](images/Cc720266.note(WS.10).gif)Observação                                                                                                                                                                                                                                              |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Qualquer que seja o método de distribuição de cliente usado, o cliente do RMS utiliza uma porta (por padrão, a porta 80 ou 443) para se comunicar com o servidor do RMS. Verifique se o computador cliente é capaz de fazer solicitações de saída para os clusters raiz e somente de licenciamento do RMS nessas portas. |

**Usando a Diretiva de Grupo**

Se a sua organização distribui software com a Diretiva de Grupo, este método pode ser utilizado para distribuir o cliente do RMS usando altos privilégios. Se o cliente do RMS for distribuído dessa maneira, o usuário não precisará ter privilégios de administrador e poderá instalar o cliente do RMS usando **Adicionar ou Remover Programas** no **Painel de Controle** ou abrindo o conteúdo protegido por direitos com um aplicativo habilitado para RMS.

**Usando o Windows Update**

O Windows Update fornece o modo mais simples de instalar o cliente do RMS em um computador. Esse método tem a vantagem de usar um mecanismo que é conhecido pelos usuários, mas requer que o usuário que irá instalar o cliente do RMS tenha direitos administrativos locais no computador.

**Usando instalação com script**

A fim de ter o nível mais alto de controle sobre o processo de instalação do cliente, você pode adquirir o software e depois validar sua integridade a cada etapa do processo de instalação, executando um script. Esse script pode ser criado e adicionado a um GPO (Objeto de Diretiva de Grupo) como um script de inicialização. Com esse método, o usuário não precisa ser um administrador local no computador, e o cliente do RMS é instalado automaticamente na reinicialização.

        ```
Para obter informações básicas sobre como distribuir o cliente do RMS usando a Diretiva de Grupo, consulte [Configurando o SMS ou a Diretiva de Grupo para oferecer suporte à implantação do cliente](https://technet.microsoft.com/9e37c27b-8cc1-40c6-adb7-0937aa64c8db), mais adiante neste tópico.

Para obter orientação sobre os procedimentos usados na implantação do cliente do RMS, consulte [Como implantar o cliente do RMS](https://technet.microsoft.com/c84f1724-cf71-4385-9003-ff68bc23c927), mais adiante neste tópico.
