# Objetos
**Objetos** são uma estrutura em várias linguagens de programação, principalmente aquelas orientadas a objetos, como JavaScript, Python e Java. Um objeto é uma coleção de dados e funcionalidades relacionadas, combinadas em uma estrutura única. Em termos simples, objetos representam entidades do mundo real, com propriedades (atributos) e comportamentos (métodos).

## Conceito de Objetos
Um objeto é composto por:
 * **Propriedades**: Características ou dados do objeto. No contexto de programação, essas propriedades são geralmente armazenadas como pares "chave: valor".
 * **Métodos**: Funções associadas ao objeto, representando as ações ou comportamentos que ele pode realizar.

 ## Exemplo com JavaScript
 Em JavaScript, objetos podem ser criados de várias formas, sendo a mais comum o uso de chaves ``{}`` para declarar um objeto literal.

 ### Criando um objeto literal
 ```javascript
 // Criando um objeto "carro"
 const carro = {
    marca: "Toyota",
    modelo: "Corolla",
    ano: 2021,
    velocidadeAtual: 0,

    // Método para acelerar o carro
    acelerar: function() {
        this.velocidadeAtual += 10;
        console.log(`Acelerou para ${this.velocidadeAtual} km/h`);
    },

    // Método para frear o carro
    frear: function() {
        this.velocidadeAtual -= 10;
        if (this.velocidadeAtual < 0) this.velocidadeAtual = 0;
        console.log(`Reduziu para ${this.velocidadeAtual} km/h`);
    }
 };

 // Utilizando propriedades e métodos do objeto
 console.log(carro.marca);      // Toyota
 carro.acelerar();              // Acelerou para 10 km/h
 carro.frear();                 // Reduziu para 0 km/h
 ```
 Neste exemplo, o objeto ``carro`` possui propriedades como ``marca``, ``modelo``, ``ano``, e ``velocidadeAtual``, além dos métodos ``acelerar`` e ``frear``, que alteram a ``velociadadeAtual``.

 ### Criando objetos com classes (JavaScript ES6)
 O JavaScript ES6 introduziu classes para facilitar a criação de objetos com construtores e métodos:

 ```javascript
 class Carro {
    constructor(marca, modelo, ano) {
        this.marca = marca;
        this.modelo = modelo;
        this.ano = ano;
        this.velocidadeAtual = 0;
    }

    acelerar() {
        this.velocidadeAtual -= 10;
        if (this.velocidadeAtual < 10) this.velocidadeAtual = 10;
        console.log(`Reduziu para ${this.velocidadeAtual} km/h`);
    }
 }

 // Criando uma instância do objeto
 const meuCarro = new Carro("Honda", "Civic", 2020);
 console.log(meuCarro.modelo);  // Civic
 meuCarro.acelerar();           // Acelerou para 10 km/h
 ```

 ## Exemplo de objetos em outras linguagens

 ### Python
 Em Python, um objeto é geralmente criado a partir de uma classe. Assim como em JavaScript, o objeto contém atributos e métodos.
 ```python
 class Carro:
    def __init__(self, marca, modelo, ano):
        self.marca = marca
        self.modelo = modelo
        self.ano = ano
        self.velocidade_atual = 0
    
    def acelerar(self):
        self.velocidade_atual += 10
        print(f"Acelerou para {self.velocidade_atual} km/h")
    
    def frear(self):
        self.velocidade_atual -= 10
        if self.velocidade_atual < 0:
            self.velocidade_atual = 0
        print(f"Reduziu para {self.velocidade_atual} km/h")
 
 # Criando uma instância do objeto
 meu_carro = Carro("Ford", "Mustang", 2021)
 print(meu_carro.modelo)    # Mustang
 meu_carro.acelerar()       # Acelerou para 10 km/h
 ```

### Java
Em Java, objetos também são criados a partir de classes, e possuem atributos e métodos.

```java
public class Carro {
    private String marca;
    private String modelo;
    private int ano;
    private int velocidadeAtual;
    
    public Carro(String marca, String modelo, int ano, int velocidadeAtual) {
        this.marca = marca;
        this.modelo = modelo;
        this.ano = ano;
        this.velocidadeAtual = 0;    
        }

    public void acelerar() {
        velocidadeAtual += 10;
        System.out.println("Acelerou para " + velocidadeAtual + "km/h")
    }

    public void frear() {
        velocidadeAtual -= 10;
        if (velocidadeAtual < 0) velocidadeAtual = 0;
        System.out.println("Reduziu para " + velocidadeAtual + "km/h")
    }

    public String getModelo() {
        return modelo;
    }

}

// Criando uma instância do objeto
public class Main {
    public static void main(String[] args) {
        Carro meuCarro = new Carro("Chevrolet", "Camaro", 2022);
        System.out.println(meuCarro.getModelo());   // Camaro
        meuCarro.acelerar();                        // Acelerou para 10 km/h
    }
}
```

## Diferenças entre objetos nas linguagens
1. **JavaScript**: Suporta objetos literais e é dinâmico, permitindo adicionar ou modificar propriedades em tempo de execução.
2. **Python**: Utiliza classes para objetos e segue uma obordagem orientada a objetos pura.
3. **Java**: Tipagem forte e requer declaração explícita de atributos e métodos, sendo mais rígido