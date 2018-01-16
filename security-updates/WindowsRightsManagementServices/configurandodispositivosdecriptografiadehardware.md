---
TOCTitle: Configurando dispositivos de criptografia de hardware
Title: Configurando dispositivos de criptografia de hardware
ms:assetid: '3a35a8ea-696c-4005-9892-cac6e773497a'
ms:contentKeyID: 18123631
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720248(v=WS.10)'
---

Configurando dispositivos de criptografia de hardware
=====================================================

O RMS pode usar os CSPs (provedores de serviços de criptografia) padrão do Windows, como os CSPs básicos e os avançados, para gerar as chaves públicas e particulares que serão armazenadas no banco de dados de configuração e usadas para proteger o conteúdo. Recomenda-se que essas chaves recebam proteção adicional, pois são armazenadas no software. Para fornecer proteção de nível mais alto, pode-se utilizar um CSP com base em hardware fornecido por um HSM (módulo de segurança de hardware).

Se você estiver usando um HSM para fornecer segurança adicional às chaves do servidor, instale e configure o hardware nos servidores antes de iniciar a instalação do RMS.
