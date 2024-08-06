---
title: 5 minutos para entender variáveis em Python
published: 2024-08-05
description: 'Aprenda mais sobre variáveis'
image: 'https://miro.medium.com/v2/resize:fit:1400/format:webp/1*g10rPF36BhOEN-Ht4bx7Yw.png'
tags: [Python, Womakerscode, Variaveis]
category: 'Python'
draft: false 
---

# Variáveis

A definição mais direta que posso pensar vem da W3Schools. De forma direta e reta, variáveis:

:::note
São **_containers_** para **_armazenar valores de dados_**
:::

Mas o que isso quer dizer na prática?

Imagine a seguinte situação: você está se mudando de casa e precisa organizar suas coisas porque, com todo o respeito a Marie Kondo, você acumulou um pouco de tralha ao longo dos anos. Você pensa: “Ok, preciso de uma caixa para guardar esse caos” e decide, então, organizar suas coisas em categorias:

![Imagem](https://miro.medium.com/v2/resize:fit:720/format:webp/1*SRJlQN_vRTIcB-jFR3nt7Q.png)

---

## Sintaxe básica de uma variável

De forma básica, uma variável é composta por três partes: o **identificador** (nome da variável); o **operador de atribuição (=)** (atenção: ele **não significa igual!**) e o valor que estamos guardando.

![Descrição da imagem](https://miro.medium.com/v2/resize:fit:720/format:webp/1*33CrbcRagLZQc_dp1D29SQ.png)

**Dica**: você pode declarar o nome da sua variável usando camelCase 🐪 e o snake_case 🐍

<pre>
```
gatoFaz = 'miau' #camelCase
cachorro_faz = 'auau' #snakel_case
```
</pre>

---

## Tipos de Dados

Eu poderia fazer uma lista enorme aqui, mas não é esse o objetivo. Você pode ver mais sobre outros tipos de dados [aqui](https://www.w3schools.com/python/python_datatypes.asp). Por essa razão, vou explicar e exemplificar apenas três desses tantos: **int**, **float**, **string** e **boolean**.

---

### Tipos Numéricos

Em Python, existem três tipos numéricos built-in, isto é, naturais da linguagem: **int**, **float** e **complex**. Iremos conversar sobre os dois primeiros:

- O tipo **integer** (**int**) refere-se a números inteiros, positivos e negativos:

```
souUmInt = 10
euTambem = -10
```

- **Float (tipos flutuantes)** são números com decimais.

```
souUmFloat = 1.2
euTambem = -120
```

---

### Tipo String

Uma string nada mais é do que um texto, ou melhor, um conjunto de caracteres. É imprescindível que você use aspas (duplas ou simples) para indicar que está tratando um texto.

```
gato = "Meow"
```

---

### Tipo Booleano

Variáveis booleanas retornam valores **True** or **False**. Observe a imagem abaixo: nas ilustrações, apenas um gatinho está comendo. Por essa razão, retornamos **True** (verdadeiro), na segunda variável e **False** (falso), na primeira.

![Descrição da imagem](https://miro.medium.com/v2/resize:fit:720/format:webp/1*Bf_rWrMAdyG0JNfY9zkWdg.png)

Imagine as possibilidades que podemos fazer com o tipo booleano? Até dar comidinha para o nosso gato é possível. Vamos aprender sobre isso nas próxima postagens.

---

Ufa! Chegamos ao final da nossa postagem. Agora você sabe: o que é uma variável, sua sintaxe básica e três tipos de dados que podemos salvar em uma variável.

Nos encontramos na próxima postagem! 🐱🧡

---

*Tradução descompromissada. Original: Variables are containers for storing data values.
