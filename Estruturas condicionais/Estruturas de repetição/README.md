# Estruturas de repetição
Estruturas de repetição, também conhecidas como *loops*, são fundamentais em programação, pois permitem que um bloco de código seja executado múltiplas vezes até que uma condição específica seja atendida. Essas estruturas simplificam tarefas repetivas e tornam o código mais eficiente e organizado.

## Tipos de estruturas de repetição
### While (enquanto)
O loop *while* continua executando o bloco de código enquanto a condição for verdadeira. Se a condição nunca for verdadeira, o código dentro do ``while`` nunca será executado.

* Exemplo em pseudocódigo:
```pseudo
while (condição) faça
    // código a ser repetido enquanto a condição for verdadeira
fim-enquanto 
```
* **Exemplo**: Mostrar números de 1 a 5.
```pseudo
contador = 1
while (contador <= 5) faça
    print(contador)
    contador = contador + 1
fim-enquanto
```
### Do-while (faça-enquanto)
O ``do-while`` é semelhante ao ``while``, mas garante que o bloco de código seja executado ao menos uma vez, independentemente da condição. Ele executa o código, depois verifica a condição.
* Exemplo:
```pseudo
faça
    // código a ser repetido
enquanto (condição)
```
* **Exemplo**: Ler número do usuário até que ele digite um número positivo
```pseudo
faça
    número = ler()
enquanto (número <0)
```
### For (para)
O ``for`` é uma estrutura de repetição usada quando se sabe o número exato de vezes que o código deve ser executado. Ele contém uma inicialização, uma condição e uma atualização de variável, tudo na mesma linha.
* Exemplo:
```pseudo
for (inicialização; condição; atualização) faça
    // código a ser repetido
fim-para
```
* **Exemplo**: Imprimir os números de 1 a 5.
```pseudo
for (i = 1; i <= 5; i = i + 1) faça
    print(i)
fim-para
```

## Estruturas de controle de repetição
* **BREAK**: Interrompe o loop, encerrando-o imediamente, mesmo que a condição ainda seja verdadeira.
* **CONTINUE**: Interrompe a iteração atual do loop e passa para a próxima.

## Exemplos práticos de uso em python

1. **Contagem**: Você quer contar de 1 a 10.
Usando um loop ``for`` para contar de 1 a 10:
```python
for i in range(1, 11):
    print(i)
```

*Resultado*: Esse código imprime os números de 1 a 10.

2. **Processar dados em uma lista**: Repetir ações para cada item de uma lista.
```python
lista = ["maçã", "banana", "laranja"]
for fruta in lista:
    print(f"Processando a fruta: {fruta}")
```
*Resultado*: Esse código exibe uma mensagem para cada fruta na lista:
```less
Processando a fruta: maçã
Processando a fruta: banana
Processando a fruta: laranja
```

3. Validação de entrada
Neste exemplo, usaremos um loop ``while`` para pedir ao usuário um número positivo. O loop continua até que o usuário forneça um número maior que zero.

```python
numero = -1
while numero <= 0:
    numero = int(input("Digite um número positivo: "))
```
*Explicação*: O código pede repetidamente um número até que o usuário insira um valor positivo.