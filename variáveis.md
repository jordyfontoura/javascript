# Variáveis

## Definição
Em javascript temos 2 formar de criar uma variável. São elas:
- const
- let

## Usos
Usamos variáveis para armazenar e modificar valores.


## Let
Declara uma variável mutável. Exemplo:
```js
let x = 4;

x = 3; 
```

## Const
Declara uma variável com referência imutável.
Significa que ao declarar uma variável `const` ela não pode ser reeatribuida. Exemplo:
```js
const x = 4;

x = 3; 
Uncaught TypeError: Assignment to constant variable.
```
Um bom exemplo de uso:
```js
const segundosPorDia = 86400
const pi = 3.14159265359
```

Nota:

A referência é imutável, mas quaisquer dados dentro da referência podem ser alterados. Exemplo:
```js
const pessoa = {
  idade: 3
}

pessoa.idade = 17
```


## Observações

Variáveis não podem ser atribuidas duas vezes no mesmo escopo. Exemplo:
```js
let x = 17;
let x = 23; 
// Erro: identificador 'x' já foi declarado
```

