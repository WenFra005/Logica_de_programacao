# Tipos de estruturas condicionais

## IF (se)
A estrutura ``if`` verifica se uma condição é verdadeira. Se for, executa um bloco de código; caso contrário, ignora-o.
Exemplo em pseudocódigo:

```pseudo
se (condição) então
    // código a ser executado se a condição for verdadeira
fim-se
```

## IF-ELSE (se-senão)
A estrutura ``if-else`` lida com uma condição que pode ser verdadeira ou falsa. Se a condição no ``if`` for verdadeira, executa um bloco de código; caso contrário, executa o bloco do ``else``.

```pseudo
if (condição) então
    // código a ser executado se a condição for verdadeira
if else
    // código a ser executado se a condição for falsa
fim-se
```

## ELSE
Esse comando é usado como o último bloco de código quando nenhuma das várias condições são verdadeiras e é executado.

```pseudo
if (condição1) então
    // código para condição1
if else (condição2) então
    // código para condição2
else
    // código se nenhuma das condições anteriores for verdadeira
fim-se
```