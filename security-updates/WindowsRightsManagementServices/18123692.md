---
TOCTitle: Problemas de compatibilidade com o FIPS no RMS
Title: Problemas de compatibilidade com o FIPS no RMS
ms:assetid: '720bdace-dcd8-431e-b0fa-01193782fe0b'
ms:contentKeyID: 18123692
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc747551(v=WS.10)'
---

Problemas de compatibilidade com o FIPS no RMS
==============================================

O RMS (Rights Management Services) versão 1.0 Service Pack 1 (SP1) foi desenvolvido para funcionar de forma eficiente em organizações que exijam o uso da funcionalidade de criptografia avaliada pelo FIPS (padrão norte-americano de processamento de informações).

O padrão FIPS 140-1 e seu sucessor FIPS 140-2 são padrões do governo norte-americano que fornecem avaliação de desempenho para implementar software de criptografia. Esses padrões especificam as práticas recomendadas para a implementação de algoritmos de criptografia, manuseio de material de chaves e buffers de dados e trabalho com o sistema operacional.

O RMS pode ser implementado como parte integrante de um sistema compatível com o FIPS, a fim de fornecer um meio de proteger dados confidenciais.

-   Os provedores de serviços de criptografia avaliados pelo FIPS restringem a funcionalidade a: **TLS\_RSA\_WITH\_3DES\_EDE\_CBC\_SHA**. Essa restrição força o provedor do canal de segurança a negociar apenas o protocolo TLS (segurança da camada de transporte) 1.0 mais seguro. Poderá ser necessário configurar o Internet Explorer para oferecer suporte ao protocolo TLS; entretanto, vários servidores Web de terceiros não oferecem suporte ao protocolo TLS. Para obter mais informações sobre esse problema, consulte o artigo 811834 da Knowledge Base, no [site da Microsoft](http://go.microsoft.com/fwlink/?linkid=43614).

Proteja a chave particular do RMS com um dos dois provedores de serviços de criptografia padrão da Microsoft, se você pretende usar proteção de chave particular baseada em software. Esses provedores de serviços de criptografia concluíram o processo de avaliação do FIPS 140-1 ou FIPS 140-2 (conforme apropriado) do governo norte-americano. Apesar de não ser obrigatório, é aconselhável que os clientes para quem a segurança seja crítica usem HSMs (módulos de segurança de hardware), como aqueles da nCipher ou IBM, para proteger chaves particulares de servidores RMS de alto nível. Se forem usados HSMs, deverá ser selecionado o provedor de serviços de criptografia apropriado para usar o HSM. Pode ser necessário reiniciar o sistema. Para obter mais informações sobre esse problema, consulte o artigo 830690 da Knowledge Base, no [site da Microsoft](http://go.microsoft.com/fwlink/?linkid=44138.)

Quando você estiver implementando o sistema RMS, deverá fazer as seguintes seleções:

-   Siga as diretrizes da NSA (agência de segurança norte-americana) referentes à criptografia compatível com FIPS no Windows.
-   Ative Diretiva de Segurança Local para criptografia compatível com FIPS.
-   Implante os clientes e servidores RMS SP1 no ambiente citado acima.
-   Habilite o protocolo TLS no IIS (Serviços de Informações da Internet) do seu servidor RMS.
-   Habilite o protocolo TLS no Internet Explorer para os seus clientes.
-   Habilite o protocolo TDS (fluxo de dados tabulares) do SQL usado com o provedor de segurança TLS/SSL Windows entre clientes SQL e SQL Server no servidor de banco de dados.
-   Configure o SQL para exigir TSL/SSL.
