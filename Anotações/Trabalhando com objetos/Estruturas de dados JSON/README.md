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

## JSON em lógica de programação
Na programação, JSON é amplamente suportado, e a maioria das linguagens oferece métodos nativos para serializar (converter um objeto para JSON) e desserializar (converter JSON para um objeto).

* **Serialização**: Transformação de um objeto em uma string JSON.
* **Desserialização**: Conversão de uma string JSON em um objeto ou estrutura de dados na linguagem.

Em JavaScript, por exemplo:
```javascript
// Objeto JavaScript
const usuario = {
    nome: "Carlos",
    idade: 25,
    casado: false
};

// Serialização para JSON
const jsonString = JSON.stringify(usuario);

// Desserialização de JSON para objeto
const usuarioObjeto = JSON.parse(jsonString);
```

## Benefícios do JSON em Programação
* **Leve e Eficiente**: JSON é leve, o que o torna ideal para transmissão de dados pela internet.
* **Compatível**: JSON é agnóstico de linguagem, funcionando bem em sistemas escritos em diferentes linguagens.
* **Estrutura Flexível**: Com objetos e arrays aninhados, JSON representa dados hierárquicos com facilidade.
* **Leitura e Escrita Simples**: Sua estrutura é intuitiva para desenvolvedores.

## Uso comum
JSON é muito usado para:
* **APIs REST**: JSON é o formato padrão para APIs, pois é leve e fácil de parsear em qualquer linguagem.
* **Armazenamento de dados**: Usado para salvar configurações e dados estruturados que podem ser lidos facilmente.
* **Transmissão de Dados entre Cliente e Servidor**: É o formato mais comum para comunicação entre frontend e backend em aplicações web.

## Desvantagens
Embora JSON seja muito útil, ele tem algumas limitações:
* **Sem suporte para comentários**: Diferente de outros formatos, JSON não permite comentários.

* **Sem suporte a tipos complexos**: JSON não suporta tipos de dados complexos, como datas, o que requer manipulação para lidar com esses dados de forma consistente.
O JSON é uma ferramenta essencial em lógica de programação e construção de sistemas distribuídos, principalmente por sua simplicidade e ampla compatibilidade com diversas linguagens de programação.