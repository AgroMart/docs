---
title: Visão de Dados
sidebar_position: 1
---

## Descrição

Ao compreender os casos de uso da extensão de Pagamento na API do Agromart foi desenvolvido o diagrama de entidades. Esse diagrama representa um modelo de entidade-relacionamento de um sistema relacionado a assinaturas de cestas em lojas online. 

![Aplicativo](../../static/img/classe.png)

Entidades:

- Assinante: Representa um assinante do serviço de cestas. Possui atributos como nome, cestas disponíveis, plano, usuário e lojas.
- Cesta: Representa uma cesta de produtos. Possui atributos como valor, quantidade, descrição, loja e imagem.
- Endereço: Representa um endereço. Possui atributos como cidade, número, complemento, CEP, rua, bairro e usuários.
- Extrato: Representa um extrato de transações. Possui atributos como usuário, loja, entregue, tipo de entrega, pagamento realizado e itens.
- Item: Representa um item em uma cesta ou plano. Possui atributos como quantidade, valor, produto avulso e plano.
- Loja: Representa uma loja. Possui atributos como nome, descrição, banner, tipos de entrega, contato, CNPJ, endereço, cestas, planos, assinantes e produtos avulsos.
- Plano: Representa um plano de assinatura. Possui atributos como nome, descrição, valor, quantidade de cestas, quantidade e imagem.
- Produto Avulso: Representa um produto avulso. Possui atributos como nome, imagem, unidade de medida, descrição, valor, quantidade e loja.
- User: Representa um usuário. Possui atributos como nome de usuário, email, provedor, senha, token de redefinição de senha, token de confirmação, status de confirmação, bloqueio, função, token de notificações e loja.
- Relacionamentos:

- Extrato está associado a Pagamento: Um extrato possui uma associação com um pagamento.
- Pagamento está associado a Gateway: Um pagamento está associado a um gateway.
- Produto Avulso está relacionado a Loja: Um produto avulso está associado a uma loja.
- Plano está relacionado a Loja: Um plano está associado a uma loja.
- Cesta está relacionada a Loja: Uma cesta está associada a uma loja.
- Endereço está relacionado a User: Um endereço está associado a um usuário.
- Endereço está relacionado a Loja: Um endereço está associado a uma loja.
- Loja está parcialmente relacionada a User: Uma loja está parcialmente relacionada a um usuário.
- Item está conectado a Plano: Um item está associado a um plano.
- Item está conectado a Produto Avulso: Um item está associado a um produto avulso.
- Item está relacionado a Extrato: Um item está relacionado a um extrato.
- Assinante está conectado a User: Um assinante está associado a um usuário.
- Assinante está conectado a Loja: Um assinante está associado a uma loja.
- Assinante está parcialmente relacionado a Plano: Um assinante está parcialmente relacionado a um plano.
Além disso, há um pacote chamado "Plugin Pagamento" que contém as entidades Gateway e Pagamento, relacionadas entre si.
