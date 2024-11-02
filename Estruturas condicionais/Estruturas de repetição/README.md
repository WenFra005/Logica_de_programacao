# Estruturas de repetição
Estruturas de repetição, também conhecidas como *loops*, são fundamentais em programação, pois permitem que um bloco de código seja executado múltiplas vezes até que uma condição específica seja atendida. Essas estruturas simplificam tarefas repetivas e tornam o código mais eficiente e organizado.

## Tipos de estruturas de repetição
### While (enquanto)
O loop *while* continua executando o bloco de código enquanto a condição for verdadeira. Se a condição nunca for verdadeira, o código dentro do ``while`` nunca será executado.

* Exemplo em python:
```python
contador = 1
while contador <= 5:
    print(contador)
    contador += 1
```
### Do-while (faça-enquanto)
O ``do-while`` é semelhante ao ``while``, mas garante que o bloco de código seja executado ao menos uma vez, independentemente da condição. Ele executa o código, depois verifica a condição.
* Exemplo:

# For (para)
O ``for`` é uma estrutura de repetição u