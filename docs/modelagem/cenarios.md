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