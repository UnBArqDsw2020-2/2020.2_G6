# GoF Criacional

Os padrões GoF Criacionais são padrões da programação orientada a objetos que definem a criação de classes, objetos e suas instancias, já pensando em suas interações e complexidades.

## Factory Method
O Factory é um dos padrões mais usados e conhecidos, que consiste em construir uma classe criadora das outras classes em um nível abstrato do objeto, que tem a função unicamente de criar expecificações do concretas (instancias) do objeto abstrato. O principal objetivo do uso desse padrão é permitir delegar a instanciação às subclasses.

![Factory Method](./assets/gofcriacional/factory.png "Por Trashtoy - My own work, generated by Inkscape, GIMP and TweakPNG., Domínio público, https://commons.wikimedia.org/w/index.php?curid=1460863")
    


## Abstract Factory
O Abstract Factory é uma evolução do Factory Method para projetos mais complexos. Diferente do Factory normal, o Abstract Factory tem mais uma camada abstrata de criação, criando os criadores de um objeto concreto. Esse metodo se torna util quando se tem mais de um nível de hierarquia.

![Abstract Factory](./assets/gofcriacional/abstract.png "Por Lucasportella - Obra do próprio, CC BY-SA 4.0, https://commons.wikimedia.org/w/index.php?curid=51993055")

## Builder
O builder é um padrão que procura dividir a complexidade de criação de algum objeto muito denso em sua criação. Ele consiste em ter um Director que possui a função que desencadeia a criação, um Builder que contêm os passos para a construção de maneira abstrata, e por fim temos os ConcreteBuilders que tem as expecificações para a criação de um objeto concreto.

![Builder](./assets/gofcriacional/builder.jpg "By Vanderjoe - Own work, CC BY-SA 4.0, https://commons.wikimedia.org/w/index.php?curid=61495624")

## Prototype
Aqui temos um padrão de projeto muito interessante que é o Prototype. O prototype consiste em adcionar na abstração a possibilidade da classe se clonar, e ser herdado e expecificicado nos objetos concretos. O fato mais interessante, é que por mais que esse seja um padrão feito para a orientação por objetos, o JavaScript é uma linguagem orientada a cadeias de prototypos que, na pratica, são criados os escopos dos objetos (incluindo os reservados: Array, String, Number, ...) e toda nova instância de um desses objetos, por exemplo: 'exemplo', são clones dos escopo do objeto, ou seja, no escopo do objeto String (String.prototype) temos a função toString(), portanto, como 'exemplo' é um objeto do tipo String, nós podemos fazer nele 'exemplo'.toString(). Expandindo esse conceito em todo JavaScript, juntamente com seu princípio de imutabilidade, isso nos possibilita alterar o prototype de qualquer objeto adcionando ou modificando algo.

![Prototype](./assets/gofcriacional/prototype.jpg "By Vanderjoe - Own work, CC BY-SA 4.0, https://commons.wikimedia.org/w/index.php?curid=61592470")

## Singleton
O Singleton é um padrão que é simples por definição, mas trás complexidade na prática. Por definição, o Singleton é uma classe que só permite uma unica instancia e fornece um método statico para recuperar a instancia. O problema da instância única é que o programador tem que lidar com trafego de requisições dessa instância, para que não tente ser usada em dois lugares ao mesmo tempo, ou que seja utilizada fora da ordem esperada.

![Singleton](./assets/gofcriacional/singleton.png "By Trashtoy - My own work, written with text editor., Public Domain, https://commons.wikimedia.org/w/index.php?curid=1484985")

## Multiton
Parecido com o Singleton, o Multition é uma classe que só permite um quantidade limitada de instâncias e um metodo statico para recuperá-los. O Multiton sofre do mesmo problema de implementação, que é o trafego de requisições, para que não sejam requisitados mais do que se tem, e que não seja utilizados fora da ordem esperada.

![Multiton](./assets/gofcriacional/multiton.png "By Trashtoy - Modfied on Paint, Public Domain, https://commons.wikimedia.org/w/index.php?curid=1484985")

## Object Pool
O Object Pool é um padrão que consiste na pré-criação de uma coleção de objetos e suas instancias, que são gerenciados por uma inteface de uso desses objetos, a partir de uma interface abstrata.

![Object Pool](./assets/gofcriacional/pool.png "By Matheus-Amaral - Own work, Created on Draw.io")

## Exemplo Gof Criacional em JavaScript

![Exemplo1](./assets/gofcriacional/exemplo1.png)

![Exemplo2](./assets/gofcriacional/exemplo2.png)


<br>


## Versionamento

| Data | Versão | Descrição | Autor |
|:----:|:-----: |:---------:|:-----:|
| 07/03/2021 | 0.1 | Adicionando padrões criacionais  | Matheus Amaral  
| 08/03/2021 | 0.2 | Adicionando tipos de padrões criacionais  | Matheus Amaral 
| 08/03/2021 | 0.3 | Adicionando imagens dos padrões criacionais | Matheus Amaral 

</br>
 

## Referências

* Slide: Aula - GOFS CRIACIONAIS, Profa. Milene Serrano