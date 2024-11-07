# Estruturas de dados JSON
JSON (JavaScript Object Notation) é um formato de texto leve e amplamente para representar dados estruturados de uma forma legível por humanos e facilmente manipulável por máquinas. ELe é muito comum na comunicação entre sistemas, especialmente APIs e transmissão de dados entre cliente e servidor. Em lógica de programação, JSON é especialmente útil com estruturas de dados, pois facilita a troca e armazenamento de informações.

## Principais conceitos e estruturas do JSON
1. **Objetos**: Em JSON, um objeto é representado por chaves ``{}`` e consiste em pares "chave: valor". As chaves são sempre strings, enquanto os valores ser diversos tipos, como strings, números, booleanos, arrays, objetos ou ``null``.

```json
{
"nome": "Carlos",
"idade": 25,
"casado": false
}
```
2. **Arrays**: Arrays são representados por colchetes ``[]`` e contém uma lista ordenada de valores, que podem ser de qualquer tipo permitido no JSON, incluindo objetos e outros arrays.

```json
{
"nomes": ["Carlos", "Ana", "João"]
}
```

3. Tipos de dados permitidos
* **String**: Cadeias de texto entre aspas.
* **Number**: Valores numéricos (inteiros ou de ponto flutuante).
* **Boolean**: Verdadeiro (``true``) ou falso (``false``).
* **Null**: Representa a ausência de valor.
* **Objeto**: Um conjunto de pares "chave: valor" dentro de ``{}``.

4. **Estruturas aninhadas**: JSON permite que objetos e arrays sejam aninhados. Isso possibilita estruturas de dados complexas de maneira hierárquica.

```json
{
    "empresa": {
    "nome": "Tech Solutions",
    "funcionarios": [
            {
            "nome": "Carlos",
            "idade": 28
            },
            {
            "nome": "Ana",
            "idade": 30
            }
        ]
    }
}
```