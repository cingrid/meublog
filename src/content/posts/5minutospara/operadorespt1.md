---
title: 5 minutos para entender operadores em Python | PT. 1
published: 2024-08-05
description: 'Aprenda mais sobre operadores'
image: 'https://miro.medium.com/v2/resize:fit:1400/format:webp/1*2xN4oG98QYz7glf1BO4l5A.png'
tags: [Python, Womakerscode, Operadores]
category: 'Python'
draft: false 
---

Como vimos anteriormente, variáveis desempenham o papel fundamental de armazenar dados. Nesse contexto, os operadores são essenciais, pois possibilitam a realização de operações sobre esses dados.

Nesse post, vamos falar sobre: _operadores matemáticos_, _ordem de precedência_, _operadores de comparação_ e _operadores lógicos_.

---

# Operadores Matemáticos

Usamos esses operadores para realizar operações matemáticas. Aqui está uma lista com os operadores matemáticos para você salvar e usar a vontade.

![Descrição da imagem](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*5cutjZ6s07maeAylRcsiYQ.png)

Você pode visualizar e executar exemplos de operadores matemáticos no nosso [Google Collab](https://colab.research.google.com/drive/1TIGmscTEPTcKfEGNWjS8JfHKXE6KVURs?usp=sharing) ;)

---

# Ordem de precedência

Antes de avançarmos para operadores lógicos, é importante entender a **ordem de precedência** dos operadores, isto é, a sequência em que as operações são realizadas em uma expressão, indicando ao Python o que deve ser executado primeiro.

[![Descrição da imagem](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*B8yb6tfJSAstwHUz7vgigw.png)](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*B8yb6tfJSAstwHUz7vgigw.png)

Vamos trabalhar outro exemplo: olhando para a equação abaixo, qual é a sequência de execução que o Python realizará?

```
x = 1 + 2 ** 3 / 4 * 5
```

---

# Operadores de Comparação

Esses operadores são autoexplicativos. Basicamente, comparam dois valores.
![Descrição da imagem](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*rf0dHFsNrWb3Njm7OWbfjg.png)
---

# Operadores lógicos

Nós já aprendemos o que são booleanos, mas se você não se lembra ou não leu a postagem anterior, a gente refresca a sua memória. Valores booleanos retornam True ou False.
Quando nós precisamos trabalhar com dois valores lógicos, aplicamos os operadores lógicos. Existem três em Python: and, or e not.

# And

- O operador `and` só retornará `True` caso ambas as proposições sejam verdadeiras.

```
x = 5
y = 10
print(x > 0 and y > 5)
```

- Pergunte-se: 5 é maior que 0? [Sim] E 10 é maior que 5? [Sim]. Então, essa frase retornará True, já que ambas as condições são verdadeiras.

# Or

- O operador `or` retornará `True` caso uma das condições seja verdadeira.

```
x = 5
y = 3
print(x > 0 or y > 5)  
```

- Pergunte-se: 5 é maior que 0? [Sim]. 3 é maior que 5? [Não]. Mas, como uma das condições é verdadeira, retornaremos True.

# Not

- O operador `not` inverte o valor lógico da condição. Isso significa que retorna `True` se a condição for falsa e vice-versa.

```
x = 5
print(not (x > 10))  # Saída: True
```

---
Ufa! Chegamos ao final da nossa postagem. Agora você sabe: o que são operadores e alguns de seus tipos, sendo eles: operadores matemáticos, comparação e lógico. Você também aprendeu sobre ordem de precedência e sua importância.

Nos encontramos na próxima postagem! 🐱🧡

Pergunte-se: 5 não é maior que 10? [Sim]. Portanto, o retorno será True.
