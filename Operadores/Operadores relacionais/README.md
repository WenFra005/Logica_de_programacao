## Operadores relacionais
|Operador|Descrição|Exemplo|
|:---:|:---:|:---|
|``==``|Igual a (compara valor)|``let isEqual = (x == y);``|
|``===``|Igual a (compara valor e formato)|
|``!==``|Diferente de|``let isNoEqual = (x != y);``|
|``>``|Maior que|``let isGreater = (x > y);``|
|``<``|Menor que|```let isLess = (x < y);``|
|``>=``|Maior ou igual a|``let isGreaterOrEqual = (x >= y);``|
|``<=``|Menor ou igual que|``let isLessOrEqual = (x <= y);``|

```javascript
let marca = "Apple";
console.log(marca !== "Sawsung")

// = é atribuição
// == é para comparar o valor
// === é para comparar o valor e o formato do conteúdo
// !== é diferente?
```

```javascript
// guardar o valor em uma variável de resultado TRUE?FALSE
let marca = "Apple";
let resultado = marca === "Samsung";

console.log(resultado);
```

```javascript
// guardar o valor em uma variável de resultado TRUE?FALSE
let cpfBloqueado = "123.445.222-45";
let cpfUsuario = "222.111.222-09";
let ehCPFBloqueado = cpfUsuario === cpfBloqueado;

console.log("O usuário está barrado? " + ehCPFBloqueado;)
```

```javascript
let idadeMinima = 18;
let idadeUsuario = 18;
let idadePermitida = let idadeUsuario >= idadeMinima;

console.log(idadePermitida);
```

```javascript
let idadeDeCorte = 50;
let idadeUsuario = 50;

let resultadoEhTerceiraIdade = idadeDeCorte <= idadeUsuario;
console.log(resultadoEhTerceiraIdade)
```