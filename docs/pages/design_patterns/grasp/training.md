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
	Diagrama menos detalhado que o diagrama de classes
	Pontos importantes que devem ser levados em conta pois nem sempre o raciocínio é válido ao modelar ao usando como base o paradigma de OO: 
		• B “contém” A ou é uma composição de A.
		• B registra A.
		• B usa A de maneira muito próxima.
		• B tem dados iniciais de A, os quais serão passados para A quando este for criado. B é um “especialista” em relação à criação de A.

### GRASP Especialista
	Se preocupa em atribuir responsabilidades para a entidade mais especificas em um dado aspecto e não apenas de criação de instâncias: Quem é a melhor entidade para calcular algo? Quem é a melhor para ordenar algo? Quem é a melhor entidade para cadastrar algo? 

### RASP Controlador
	Atribui a responsabilidade de lidar com os eventos do sistema para uma classe que representa a um cenário de caso de uso do sistema global.

### GRASP Baixo Acoplamento 
	Determina que as classes não devem depender de objetos concretos e sim de abstrações, para permitir que haja mudanças sem impacto.

### GRASP Alta Coesão
	Este princípio determina que as classes devem se focar apenas na sua responsabilidade.

### GRASP  Polimorfismo
	As responsabilidades devem ser atribuídas a abstrações e não a objetos concretos, permitindo que eles possam variar conforme a necessidade.

### GRASP Pura Fabricação
	É uma classe que não representa nenhum conceito no domínio do problema, ela apenas funciona como uma classe prestadora de serviços, e é projetada para que possamos ter um baixo acoplamento e alta coesão no sistema.

### GRASP Indireção
	Este princípio ajuda a manter o baixo acoplamento, através de delegação de responsabilidades através de uma classe mediadora.

### GRASP Proteção contra Variações
	Protege o sistema com a variação de componentes, encapsulando o comportamento que realmente importa.

---

### Versionamento

|Data|Versão|Descrição|Autor|
|:--:|:----:|:-------:|:---:|
|22/03/2021| 0.1 | Criação do documento e resumo inicial | Ailamar Alves

<br>

### Referências 
 - 