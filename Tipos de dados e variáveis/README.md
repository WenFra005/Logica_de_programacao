# Tipos de dados e variáveis
Em programação existem dois conceitos que são básicos em qualquer linguagem, **dados** e **variáveis**.

* **Dados** são valores que são armazenados dentro de uma variável.
* **Variáveis** são pedaços da memória de um disposivo nas quais contém algum dado.

## Exemplos de declaraçãp de variáveis em diferentes linguagens

Aqui estão exemplos de declaração de variáveis em cinco linguagens de programação diferentes.

### Python (Tipagem Dinâmica)

Em Python, as variáveis não precisam ter o tipo especificado; o interpretador infere o tipo automaticamente.
```python
idade = 25          # Inteiro
altura = 1.75       # Ponto flutuante
nome = "Maria"      # String
estudante = true    # Booleano
```
**Observação**: Python usa tipagem dinâmica, então o tipo é determinado pelo valor atribuído.

### JavaScript (Tipagem Dinâmica)

JavaScript também usa tipagem dinâmica e permite declarar variáveis usando ``var``, ``let`` ou ``const``.

```javascript
let idade = 25;      // Inteiro
let altura = 1.75;   // Ponto flutuante
let nome = "Maria";  // String
let estudante = true // Booleano
```

**Dica**: Prefira ``let`` e ``const`` em vez de ``var`` devido ao escopo e comportamento previsível de bloco.

### Java (Tipagem Estática)

Java é uma linguagem com tipagem estática, ou seja, você deve declarar o tipo da variável antes de usá-la.
```java
int idade = 25;         // Inteiro
double altura = 1.75;   // Ponto flutuante
String nome = "Maria";  // String
boolean estudadante;    // Booleano
```
**Observação**: Em Java, variáveis devem ser inicializadas ou declaradas antes de serem usadas.
### C++ (Tipagem Estática)

Em C++, como em Java, o tipo da variável deve ser especificado no momento da declaração.
```cpp
int idade = 25;             // Inteiro
float altura = 1.75f;       // Ponto flutuante
std::string nome = "Maria"  // String
bool estudante = true;      // Booleano
```

**Dica**: C++ permite uma ampla gama de tipos primitivos e derivados, como ``int``, ``float``, ``double``, etc.

### TypeScript (JavaScript com Tipagem Estática)

TypeScript adiciona tipagem estática ao JavaScript, permitindo que você defina tipos explicitamente.
```typescript
let idade: number = 25;         // Inteiro
let altura: number = 1.75;      // Ponto flutuante
let nome: string = "Maria";     // String
let estudante: boolean = true;  // Booleano

```
**Dica**: TypeScript verifica os tipos em tempo de compilação, reduzindo erros de tipo em comparação com JavaScript puro.

## Outros tipos de variáveis

Há outros tipos de variáveis também. Abaixo segue uma tabela mostrando quais são e sua descrição.

|Tipo de variável|Descrição|
|:---|:---|
|Variáveis numéricas| São usadas para armazenar valores numéricos.|
|Inteiro| Armazena números inteiros como 1, 10, -5.|
|Ponto flutuante ou decimal| Armazena números com casas decimais como 3.14, -0.5.|
|Número complexos| Armazena números complexos como 2 + 3j.|
|Variáveis de texto| Usadas para armazenar sequências de caracteres.|
|String| Armazena uma sequência de caracteres como "Olá mundo!"|
|Caractere| Armazena um único caractere como 'a', 'X', '@'.|
|Variáveis lógicas| Usadas para armazenar valores de verdadeiro ou falso.|
|Booleano| Armazena os valores True ou False.|
|Variáveis de data e hora| Utilizadas para representar datas e horários.|
|Data| Armazena datas no formato AAAA-MM-DD.|
|Hora| Armazena horários no formato HH:MM:SS.|