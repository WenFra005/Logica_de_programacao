# Vetores e Matrizes
**Vetores** e **matrizes** são estruturas de dados fundamentais em programação. Um vetor (ou **array**) é uma lista unidimensional que armazena uma coleção de elementos do mesmo tipo. Uma **matriz** (ou **array multidimensional**) é uma estrutura de dados que armazena dados em mais de uma dimensão, como uma tabela (2D) ou cubo (3D).

* **Vetores** são ideais para armazenar uma lista ordenada de elementos.
* **Matrizes** são úteis para representar dados em formato de tabela (como em uma planilha) ou mais de dimensões.

## Exemplos em outras linguagens

Aqui estão exemplos de declaração e uso de vetores e matrizes em outras linguaguens de programação.

### Python

#### Vetor

```python
# Declaração e inicialização de um vetor
vetor = [1, 2, 3, 4, 5]

# Acesso a elementos
print(vetor[0])     # Saída: 1
print(vetor[2])     # Saída: 3

# Modificando um elemento
vetor[1] = 10
print(vetor)        # Saída: [1, 10, 3, 4, 5]
```

#### Matriz

```python
# Declaração e inicialização de uma matriz 2D
matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]

# Acesso a elementos
print(matriz[0][1])     # Saída: 2
print(matriz[2][2])     # Saída: 9

# Modificando um elemento
matriz[1][1] = 50
print(matriz)           # Saída: [[1, 2, 3], [4, 50, 6], [7, 8, 9]]
```

### JavaScript
#### Vetor
```javascript
// Declaração e inicialização de um vetor
let vetor = [1, 2, 3, 4, 5];

// Acesso a elementos
console.log(vetor[0]);  // Saída: 1
console.log(vetor[2]);  // Saída: 3

// Modificando um elemento
vetor[1] = 10;
console.log(vetor);     // Saída: [1, 10, 3, 4, 5]
```

#### Matriz
```javascript
// Declaração e inicialização de uma matriz 2D
let matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
];

// Acesso a elementos
console.log(matriz[0][1]);  // Saída: 2
console.log(matriz[2][2]);  // Saída: 9

// Modificando um elemento
matriz[1][1] = 50;
console.log(matriz);        // Saída: [[1, 2, 3], [4, 50, 6], [7, 8, 9]]
```

### Java
#### Vetor
```java
// Declaração e inicialização de um vetor
int[] vetor = {1, 2, 3, 4, 5};

// Acesso a elementos
System.out.println(vetor[0]);   // Saída: 1
System.out.println(vetor[2]);   // Saída: 3

// Modificando um elemento
vetor[1] = 50;
System.out.println(Arrays.toString(vetor));     // Saída: [1, 10, 3, 4, 5]
```

#### Matriz
```java
// Declaração e inicialização de uma matriz 2D
int[][] matriz = {
    {1, 2, 3},
    {4, 5, 6},
    {7, 8, 9}
};

// Acesso a elementos
System.out.println(matriz[0][1]);   // Saída: 2
System.out.println(matriz[2][2]);   // Saída: 9

// Modificando um elemento
matriz[1][1] = 50;
System.out.println(Arrays.deepToString(matriz));    // Saída: [[1, 2, 3], [4, 50, 6], [7, 8, 9]]
```

### C++
#### Vetor
```cpp
#include <iostream>
#include <vector>

int main() {
    // Declaração e inicialização de um vetor
    std::vector<int> vetor = {1, 2, 3, 4, 5};

    // Acesso a elementos
    std::cout << vector[0] << std::endl;    // Saída: 1
    std::cout << vector[2] << std::endl;    // Saída: 3

    // Modificando um elemento
    vetor[1] = 10;
    for (int i : vetor) std::cout << i << " ";  // Saída: 1 10 3 4 5
}
```

#### Matriz
```cpp
#include <iostream>
#include <vector>

int main() {
    // Declaração e inicialização de uma matriz 2D
    std::vector<std::vector<int>> matriz = {
        {1, 2, 3},
        {4, 5, 6},
        {7, 8, 9}
    };

    // Acesso a elementos
    std::cout << matriz[0][1] << std::endl; // Saída: 2
    std::cout << matriz[2][2] << std::endl; // Saída: 9

    // Modificando um elemento
    matriz[1][1] = 50;
    for (const auto& row) {
        for(int val : row) std::cout << val << " ";
    std::cout << std::endl;
    }    
}
```
### Kotlin
#### Vetor
```kotlin
val vetor = arrayOf(1, 2, 3, 4, 5)
println(vetor[0]) // Saída: 1
vetor[1] = 10
println(vetor.joinToString()) // Saída: 1, 10, 3, 4, 5

```

#### Matriz
```kotlin
val matriz = arrayOf(
    arrayOf(1, 2, 3),
    arrayOf(4, 5, 6),
    arrayOf(7, 8, 9)
)
println(matriz[0][1]) // Saída: 2
matriz[1][1] = 50
println(matriz.contentDeepToString()) // Saída: [[1, 2, 3], [4, 50, 6], [7, 8, 9]]
```