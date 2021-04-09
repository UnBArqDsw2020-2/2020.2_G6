# Treinamento Padrões de Projeto: GoF Comportamental

Esse método de padrão tem como objetivo no projeto, observar a maneira com que classes e objetos podem interagir. São divididos em:

## Strategy

Possibilita ao cliente a utilização de variações de determinado algoritmo, mas todos atingindo o mesmo objetivo na resolução de um dado problema. É implementado através de classes abstratas ou interfaces e permite a troca de algoritmos em tempo de execução da aplicação.

## Template Method

Tem como objetivo definir a ordem lógica na qual determinados passos devem ser realizados na resolução de um problema e permitir que esses passos possam ser realizados de formas diferentes de acordo com a situação. Onde a ordem dos passos é conhecida, mas o comportamento não pois depende da sua instância. <br>
Possui uma classe abstrata no topo, que define os casos mais generalista e abaixo dela se encontram as classes filhas ou chamadas também de classes concretas onde estará o um maior detalhamento dos passos (métodos) apresentados na classe abstrata.

## Command

Padrão que utiliza uma interface conhecida pelo componente para gerenciar suas requisições associando cada ação a diferentes objetos.

## Iterator

Possibilita uma forma de acessarmos sequencialmente os elementos de uma agregação de objetos, não sendo necessário violar seu encapsulamento.

## Mediator

Administra a relação entre entidades, possuindo responsabilidades comportamentais para gerenciar essa colaboração entre as entidades.

## Observer

Um observer monitora um determinado objeto (subject), verificando se esse objeto tem seu estado alterado e a partir do momento que isso acontece, o observer notifica os demais observadores interessados no estado atual daquele subject. Representa uma relação 1:n.

## State

Lida com a mudança de estado interno do objeto. Assim como o padrão strategy, utiliza de um contexto e altera seu comportamento de acordo com o estado atual do objeto.

## Memento

Armazena um estado interno de um objeto em um determinado momento para que depois seja possível você voltar para aquele estado anterior do objeto, não afetando seu encapsulamento.

---

### Versionamento

|    Data    | Versão |               Descrição               |      Autor      |
| :--------: | :----: | :-----------------------------------: | :-------------: |
| 26/03/2021 |  0.1   | Criação do documento e resumo inicial | Heron Rodrigues |
| 02/04/2021 |  0.2   |         Complemento e revisão         |  Ailamar Alves  |
| 02/04/2021 |  0.2   |           Adição de tópico            | Heron Rodrigues |

<br>

### Referências

- Padrões de projeto estruturais. Disponível em: https://refactoring.guru/pt-br/design-patterns/structural-patterns . Acesso em: mar, 2021.
