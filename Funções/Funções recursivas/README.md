# Funções recursivas
Funções podem chamar a si mesmas. Esse conceito é conhecido como *recursão* e é útil para resolver problemas que podem ser divididos em subproblemas menores, como cálculo de fatorial e sequência de Firenacci.

Exemplo de uma função recursiva para calcular o fatorial de um número:
```python
def fatorial(n):
    if n == 1:
        return 1
    else:
        return n * fatorial(n - 1)
```
Chamando a função:
```python
print(fatorial(5))
```
*Resultado*: ``120``