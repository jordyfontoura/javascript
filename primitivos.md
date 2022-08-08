# Tipos de dados primitivos

## Definição
Existem 7 tipos primitivos em javascript. São eles:

- null
- undefined
- boolean
- number
- bigint
- string
- object
- function
- symbol

---

## Null (Vazio)

Representa um valor vazio

## Undefined (Indefinido)

Representa um valor não atribuido

```js
let x;

console.log(typeof x); // undefined
```

## Boolean (Verdadeiro / Falso)

Representa um valor Verdadeiro ou Falso

## Number (Númerico)

Representa um número inteiro, racional ou irracional (0.213, 1, 3.1415)

## BigInt (Número inteiro possivelmente grande)

Representa um número inteiro

## String (Texto / Mensagem)

Representa um Texto

## Symbol (Valor único)

Representa um simbolo unico

## Object (Objeto)

Qualquer coisa que não seja um dos anteriores
Ex:
```js
const pessoa = {
  nome: "exemplo",
  idade: 17
};

console.log(typeof pessoa); // object
```

```js
const list = [1, 2, 3];

console.log(typeof list); // object
```
