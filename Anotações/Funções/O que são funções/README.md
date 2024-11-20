# O que são funções e como cria-las
Funções são blocos de código reutilizáveis na lógica de programação que realizam uma tarefa específica. Elas permitem organizar o código, evitar repetição e torná-lo mais modular e fácil de entender.

## Estrutura de uma função
Uma função geralmente inclui:
1. **Nome**: Identifica a função e permite chamá-la no código.
2. **Parâmetros (ou argumentos)**: Variáveis que recebem valores quando a função é chamada, possibilitando que a função opere sobre esses dados.
3. **Corpo**: Bloco de código que define o que a função faz.
4. **Valor de Retorno (opcional)**: Resultado produzido pela função que pode ser enviado de volta ao ponto onde foi chamada, usado a instrução ``return``.

## Exemplo de uma Função em Python
Aqui está um exemplo básico de função em Python.
```python
def saudacao(nome):
    print(f"Olá, {nome}!")
```
Para chamar a função e ver o resultado, basta fazer:
```python
saudacao("Carlos")
```
*Resultado*: ``Olá, Carlos!``

## Vantagens de usar Funções
* **Reutilização de código**: Funções podem ser chamadas várias vezes em diferentes partes do programa, sem precisar reescrever o código.
* **Organização e Modularidade**: Funções ajudam a dividir um programa em partes menores e mais gerenciáveis.
* **Facilidade de manutenção**: Com funções, é possível atualizar ou corrigir uma parte específica do código sem afetar o restante do programa.
* **Evita repetição**: Evita duplicação de código, tornando-o mais eficiente e limpo.