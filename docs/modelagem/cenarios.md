---
title: Cenários
sidebar_position: 2
---

# Cenários

## Introdução

Um cenário é um ambiente criado pela equipe de projeto para representar situações que ajude a compreender as interações entre os sistemas e também elicitar a parte comportamental do software. Essa técnica tem se provado muito eficiente para levantamento de requisitos apesar de informal.

## Metodologia 

A técnica funciona com a criação de narrativas que descrevem um episódio específico que necessitam do uso da tecnologia do nosso projeto. Assim criamos uma breve história de uma cena bem detalhada com atores para simular a situação.<br/><br/>
**Na criação dos nossos cenários utilizamos o seguinte modelo base:**  
<br/>

<br/>

Tópico | Descrição 
:----: | :--------
**Título**   | Nome breve para o cenário
**Objetivo** | Finalidade da história 
**Contexto** | Local, tempo e pré-condição da história
**Atores**   | Personagens que participarão da história
**Recurso**  | Recursos envolvidos
**Restrição** | Critérios favoráveis, caso tenha
**Exceção**  | Critérios desfavoráveis, caso tenha
**Episódio** | Descrição da narrativa 
<br/>

## Nossos cenários

### C1 - Administrador cria a CSA usando o Agromart

|      | Descrição 
:----- | :--------
**Objetivo** | Criação da CSA no Agromart
**Contexto** | Local: em casa<br/>Tempo: pela manhã<br/> Pré-condição: viu uma necessidade de organizar melhor a CSA
**Ator(es)** | Novo usuário
**Recurso**  | Computador com acesso a internet<br/> Telefone com internet
**Restrição** | Conhece um pouco de tecnologia <br/>
**Exceção**  | Falta de sinal de internet<br/>
**Episódio** | Usuário baixou o Agromart para organizar melhor sua CSA <br/>  Usuário seguiu o tutorial de instalação e foi bem sucedido <br/> O usuário agora Administrador possui um código específico para sua CSA <br/> O então Administrador convida os co-agricultores a baixar o Agromart e compartilha seu código com eles.
<br/>

### C2 - Um co-agricultor quer fazer parte de uma CSA

|      | Descrição 
:----- | :--------
**Objetivo** | Participar de uma CSA
**Contexto** | Local: em uma unidade da CSA<br/>Tempo: pela manhã<br/> Pré-condição: se interessou pela CSA a qual está visitando
**Ator(es)** | Novo co-agricultor
**Recurso**  | Telefone com internet
**Restrição** | Tem amigos que já fazem parte da CSA e já tem o aplicativo
**Exceção**  | Falta de sinal de internet <br/> Agromart não pode ser baixado pelo tipo do celular <br/>
**Episódio** | Co-agricultor baixou o Agromart <br/>  Co-agricultor pediu o código para o responsável pela CSA <br/> Co-agricultor está agora participando da CSA
<br/>

### C3 - Co-agricultor comprou uma cesta

|      | Descrição 
:----- | :--------
**Objetivo** | Comprar uma cesta
**Contexto** | Local: em casa<br/>Tempo: pela noite<br/> Pré-condição: Alimentos acabando em casa e precisa reabastecer
**Ator(es)** | Co-agricultor já participando da CSA
**Recurso**  | Telefone com internet
**Restrição** | Já conhece como a CSA funciona <br/>
**Exceção**  | Falta de sinal de internet<br/>
**Episódio** | Co-agricultor logou em sua CSA <br/> Acessou a página da loja  <br/> Olhou as cestas <br/> Escolheu a quantidade <br/> Foi direcionado para o carrinho <br/> Finalizou a compra <br/> Estabeleceu o método de pagamento com o responsável pela CSA <br/> Realizou o pagamento
<br/>

### C4 - Co-agricultor comprou um plano

|      | Descrição 
:----- | :--------
**Objetivo** | Comprar uma plano
**Contexto** | Local: em casa<br/>Tempo: pela noite<br/> Pré-condição: Acabou de se cadastrar e deseja assinar um plano
**Ator(es)** | Co-agricultor inicio sua participação na CSA recentemente
**Recurso**  | Telefone com internet
**Restrição** | Já conhece como a CSA funciona <br/>
**Exceção**  | Falta de sinal de internet<br/>
**Episódio** | Co-agricultor logou em sua CSA <br/> Acessou a página da loja  <br/> Olhou os planos <br/> Escolheu o plano que deseja assinar <br/> Foi direcionado para o carrinho <br/> Finalizou a compra <br/> Estabeleceu o método de pagamento com o responsável pela CSA <br/> Realizou o pagamento
<br/>

### C5 - Co-agricultor comprou produtos

|      | Descrição 
:----- | :--------
**Objetivo** | Comprar produtos
**Contexto** | Local: em casa<br/>Tempo: pela noite<br/> Pré-condição: Frutas, verduras e legumes estão acabando em casa e precisam serem repostos
**Ator(es)** | Co-agricultor já participando da CSA
**Recurso**  | Telefone com internet
**Restrição** | Já conhece como a CSA funciona <br/>
**Exceção**  | Falta de sinal de internet<br/>
**Episódio** | Co-agricultor logou em sua CSA <br/> Acessou a página da loja  <br/> Olhou os produtos <br/> Escolheu a quantidade <br/> Foi direcionado para o carrinho <br/> Finalizou a compra <br/> Estabeleceu o método de pagamento com o responsável pela CSA <br/> Realizou o pagamento
<br/>

### C6 - Co-agricultor deseja alterar seu endereço

|      | Descrição 
:----- | :--------
**Objetivo** | Mudar endereço
**Contexto** | Local: em casa<br/>Tempo: pela manhã<br/> Pré-condição: Já fazer parte da CSA
**Ator(es)** | Co-agricultor já participando da CSA
**Recurso**  | Telefone com internet
**Restrição** | Já conhece como a CSA funcion <br/>
**Exceção**  | Falta de sinal de internet<br/> Se mudou <br/>
**Episódio** | Co-agricultor logou em sua CSA <br/> Acessou a página Meus Endereços  <br/> Realizou a edição do endereço
<br/>

### C7 - Administrador adiciona co-agricultor na assinatura

|      | Descrição 
:----- | :--------
**Objetivo** | Adicionar co-agricultor ao plano de assinatura
**Contexto** | Local: em casa<br/>Tempo: pela manhã<br/> Pré-condição: Ser Administrador
**Ator(es)** | Responsável pela CSA
**Recurso**  | Computador com internet <br/> Telefone com internet
**Restrição** | Já conhece como a CSA funciona <br/>
**Exceção**  | Falta de sinal de internet <br/>
**Episódio** | Agricultor logou na conta do Strapi <br/> Acessou a página Assinaturas  <br/> Adicionou o co-agricultor ao plano de assinatura
<br/>