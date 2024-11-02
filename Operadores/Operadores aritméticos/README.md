# Operadores aritméticos

## Operadores aritméticos

|Operador|Descrição|Exemplo|
|:---:|:---:|:---:|
|``+``|Adição|``let result = 5 + 3;``|
|``-``|Subtração|``let result = 8 - 2;``|
|``*``|Multiplicação|``let result = 4 * 6;``|
|``/``|Divisão|``let result = 10 / 2;``|
|``%``|Módulo (resto da divisão)|``let result = 10 % 3;``|

```javascript
// sinal de + usado para concatenar string
let idade = 30;
console.log("valor da minha variável " + idade);

// '+' realizando somas
idade = 30 + 6;
console.log("operação de adição " + idade);

// '-' realizando subtrações
let primeiroNumero = 1023;
let = segundoNumero = 23;
console.log(primeiroNumero - segundoNumero);

// '*' realizando multiplicações
let multiplicador = 4;
let multiplicando = 12;
let produto = multiplicador * multiplicando;
console.log("resultado da multiplicação é " + produto);

multiplicador = 8;
produto = multiplicador * multiplicando;
console.log("resultado da multiplicação é " + produto);

// '/' realizando divisões
let notaDoMercado = 50;
let pessoasParaDividir = 2;
console.log("operação de divisão: " + notaDoMercado / pessoasParaDividir);

// '%' pegando o resto de uma divisão
let calculo = 10 % 3;
console.log("operação de módulo " + calculo);
```

## Operadores de incremento e decremento
|Operador|Descrição|Exemplo|
|:---:|:---:|:---|
|``=``|Atribuição|``let x = 5;``|
|``++``|Incremento|``let counter = 0;``<br>``counter++;``|
|``-=``|Subtração e atribuição|``let num = 10;``<br>``num -= 3;``|
|``*=``|Multiplicação e atribuição|``let num = 5;``<br>``num *= 4;``|
|``/=``|Divisão e atribuição|``let num = 10;``<br>``num /= 2;``|
|``%=``|Módulo e atribuição|``let num = 10;``<br> ``let num = 10;num %=3;``|

```javascript
let preco = 10;
preco += 5; // preco = preco + 5
preco -= 5  // preco = preco - 5
console.log(preco) 
```