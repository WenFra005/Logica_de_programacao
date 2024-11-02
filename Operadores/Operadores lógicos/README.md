# Operadores lógicos

## Operadores lógicos:
|Operador|Descrição|Exemplo|
|:---:|:---:|:---|
|``&&``|AND lógico|``if (condition1 && condition2)``|
|``\|\|``|OR lógico|``if (condition1 || condition2)``
|!|NOT lógico|``if (!condition)``|

```javascript
// AND ( && )
let idade = 18
let vistoVerificado = false
let resultado =  (idade >= 18) && (vistoVerificado === true) 
console.log(resultado)
```

```javascript
// AND ( && ) - 100 moedas coletadas E 1 item estrela
let moedasColetadas = 99
let item = "estrela"
let resultado = (moedasColetadas >= 100) && (item === "estrela")
console.log(resultado)
```

```javascript
// NOT  ( !) - nega uma afirmação
let tempo = "chuva"
let resultado = tempo === "chuva"
console.log(!!resultado)
```

```javascript
// NOT  ( !) - nega uma afirmação
let tempo = "chuva"
let horario = 8
let resultado = !((tempo !== "chuva") && (horario > 6))
console.log(resultado)
```