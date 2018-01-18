---
TOCTitle: Ativação de máquina do RMS
Title: Ativação de máquina do RMS
ms:assetid: '09a0d631-9860-477f-9d10-df61b3bfe125'
ms:contentKeyID: 18123536
ms:mtpsurl: 'https://technet.microsoft.com/pt-br/library/Cc720182(v=WS.10)'
---

Ativação de máquina do RMS
==========================

A ativação de máquina é um pré-requisito para a publicação ou o uso de conteúdo protegido pelo RMS em um computador cliente. Ativação de máquina é o processo através do qual um computador cliente recebe um cofre exclusivo e um certificado correspondente de máquina do RMS. O cofre contém a chave particular do computador, e o certificado de máquina contém a chave pública do computador. Como o cofre contém a chave particular do computador, é a principal entidade de segurança para criptografia e descriptografia. Cada usuário do computador terá um certificado de máquina exclusivo criado pelo processo de ativação de máquina.

O processo de ativação de máquina usado com o cliente do RMS para o Service Pack 1 é consideravelmente diferente daquele da versão 1. O cliente do RMS do Service Pack 1 tem "auto-ativação". Quando o cliente do RMS é instalado por um usuário conectado, ou um recurso do RMS é usado primeiro por um usuário conectado, o cliente inicia o processo de ativação, o qual gera vários conjuntos de chaves usando a criptografia API incluída no Windows. Essas chaves são usadas para executar um conjunto de criptografias, gerando um certificado de máquina que vincula o usuário, o computador e o cliente do RMS na hierarquia de confiança do RMS.
