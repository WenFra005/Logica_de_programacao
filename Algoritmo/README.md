# Algoritmo
Algoritmo é uma sequência de ações com o objetivo de resolver um problema. É como uma receita de um bolo na qual é especificado quais ingredientes usar, quais materiais utilizar e quais ações deve-se fazer com esses ingredientes para fazer o bolo.

## Exemplo: Receita de Bolo
### Ingredientes
* 2 xícaras (chá) de açúcar
* 4 colheres (sopa) de margarina
* 1 e 1/2 xícara (chá) de leite
* 3 xícaras (chá) de farinha de trigo
* 3 ovos
* 1 colher (sopa) bem cheia de fermento em pó

### Materias

* Batedeira
* Tijela
* Espátula para bolo
* Forma de Bolo

### Modo de preparo

1. Bata as claras em neve e reserve.

2. Misture as gemas, a margarina e o açúcar até obter uma massa homogênea.

3. Acrescente o leite e a farinha de trigo aos poucos, sem parar de bater.

4. Por último, adicione as claras em neve e o fermento.

5. Despeje a massa em uma forma grande de furo central untada e enfarinhada.

6. Asse em forno médio 180 °C, preaquecido, por aproximadamente 40 minutos ou ao furar o bolo com um garfo, este saia limpo.

### Fluxograma da receita de bolo
Um **Fluxograma** é uma representação visual dos processos ou do algoritmo para realizar um determinado objetivo, nesse caso a preparação de um bolo. Veja abaixo o fluxograma:

~~~mermaid
flowchart TD
    A[Início] --> B[Bater as claras em neve]
    B --> C[Reservar as claras em neve]
    C --> D[Misturar gemas, margarina e açúcar]
    D --> E[Obter massa homogênea]
    E --> F[Acrescentar leite e farinha de trigo aos poucos]
    F --> G[Continuar batendo a massa]
    G --> H[Adicionar claras em neve e fermento]
    H --> I[Despejar a massa na forma untada e enfarinhada]
    I --> J[Assar em forno a 180°C por 40 minutos]
    J --> K{Bolo Assado?}
    K -- Sim --> L[Furar com garfo para verificar]
    L -- Garfo limpo --> M[Fim: Bolo Pronto]
    L -- Garfo sujo --> J
    K -- Não --> J

~~~
