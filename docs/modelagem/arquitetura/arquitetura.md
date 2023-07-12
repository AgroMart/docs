---
title: Arquitetura
sidebar_position: 1
---

## Descrição

A arquitetura planeja por Rodrigues e Macêdo (2021) e evoluída por Corrêa e Veludo (2022) e Freitas e Cella (2023) segue o modelo cliente-servidor com aplicação distribuída. É representada por um diagrama de componentes que apresenta a estrutura decomposta em componentes arquitetonicamente significativos. A estrutura de implementação apresenta a organização das dependências e dos pacotes ilustrativamente.

![Aplicativo](../../static/img/arquitetura.png)

Apresenta uma aplicação mobile que se comunicará com um dicionário que armazena o localizador uniforme de recursos (URL) de cada CMS Strapi individualizado. Com esse URL, a comunicação cliente-servidor entre App e a API ocorre com o Protocolo de Transferência de Hipertexto (HTTP). Cada API Strapi tem seu banco de dados PostgreSQL e interface providenciado pelo CMS.

Os serviços possuem JavaScript como a linguagem de programação dominante no sistema Agromart. JavaScript é uma linguagem de programação de alto nível, interpretada de forma estruturada com tipagem dinâmica fraca.
