# Treinamento Padrões de Projeto: GRASP

## O que é padrão de projeto ?
- Uma solução boa, testada e aprovada para um problema recorrente

## O que é padrão de projeto em software?
- Padrões de projeto são princípios e soluções usados durante a criação do software, codificados em um formato estruturado, descrevendo o problema e a respectiva solução adotada.

## Padrão GRASP (General Responsability Assignment Software Patterns) 
Padrões de Software para Atribuição de Responsabilidade Geral
Foi criado com o intuito de tornar o código mais flexível, facilitando a manutenção e a extensibilidade.
Auxiliam os desenvolvedores a projetar de uma forma bem estrutura aplicações orientadas a objetos

### GRASP Criador
	Diagrama menos detalhado que o diagrama de classes. Define quais classes possuem a responsabilidade de criar instâncias.
	Pontos importantes que devem ser levados em conta pois nem sempre o raciocínio é válido ao modelar ao usando como base o paradigma de OO: 
		• B “contém” A ou é uma composição de A.
		• B registra A.
		• B usa A de maneira muito próxima.
		• B tem dados iniciais de A, os quais serão passados para A quando este for criado. B é um “especialista” em relação à criação de A.

### GRASP Especialista
	Se preocupa em atribuir responsabilidades para a entidade mais especificas em um dado aspecto e não apenas de criação de instâncias: Quem é a melhor entidade para calcular algo? Quem é a melhor para ordenar algo? Quem é a melhor entidade para cadastrar algo?

    Isso evita que o software tenha um forte acoplamento, a partir do momento em que os controladores teriam lógicas além do necessário, além de sua responsabilidade.

### RASP Controlador
	Atribui a responsabilidade de lidar com os eventos do sistema para uma classe que representa a um cenário de caso de uso do sistema global.

### GRASP Baixo Acoplamento 
	Determina que as classes não devem depender de objetos concretos e sim de abstrações, para permitir que haja mudanças sem impacto. Quanto menor essa dependência, mais manutenível é o nosso software.


### GRASP Alta Coesão
	Este princípio determina que as classes devem se focar apenas na sua responsabilidade. Uma classe coesa é uma entidade dedicada a procedimentos específicos.

### GRASP  Polimorfismo
	As responsabilidades devem ser atribuídas a abstrações e não a objetos concretos, permitindo que eles possam variar conforme a necessidade.

    Conceito muito utilizado na Programação Orientada a Objetos, onde o sistema possui duas ou mais classes com métodos parecidos, então é criado uma classe com um nível de abstração mais alto e generalista para que as classes possam herdar as características dessa classe abstrata.

### GRASP Fabricação ou Invenção Pura
	É uma classe que não representa nenhum conceito no domínio do problema, ela apenas funciona como uma classe prestadora de serviços, e é projetada para que possamos ter um baixo acoplamento e alta coesão no sistema. Por exemplo, um módulo de persistência no banco de dados.

### GRASP Indireção
	Este princípio ajuda a manter o baixo acoplamento, através de delegação de responsabilidades através de uma classe mediadora.

### GRASP Proteção contra Variações
	Protege o sistema com a variação de componentes, encapsulando o comportamento que realmente importa.

    Aplicado juntamente com o polimorfismo, através do uso de interface, e encapsulamento de dados, possibilita um mecanismo de defesa para permitir a flexibilidade e proteção dos elementos contra variações em outras entidades.

---

### Versionamento

|Data|Versão|Descrição|Autor|
|:--:|:----:|:-------:|:---:|
|22/03/2021| 0.1 | Criação do documento e resumo inicial | Ailamar Alves
|29/03/2021| 0.2 | Complementando a explicação dos tópicos | Heron Rodrigues

<br>

### Referências 
 - 