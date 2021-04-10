# Aplicações Padrão GRASP

Após o [Treinamento](https://unbarqdsw2020-2.github.io/2020.2_G6_RocketX/#/pages/design_patterns/patterns?id=o-que-%c3%a9-padr%c3%a3o-de-projeto-) e definição de cada método, utilizamos os que mais se encaixavam no escopo do nosso projeto para executar essas aplicações.

## Creator

Exemplo da aplicação: 

![Creator](img/creator.jpg)

<p align="center">
  Fig 1: Uso do creator.
</p>

Arquivo completo: [controllerCreator.js](https://github.com/UnBArqDsw2020-2/2020.2_G6_RocketX_BackEnd/blob/main/src/routes/controllerCreator.js)

## Controller

Esse padrão foi utilizado para a implementação do acesso aos dados da aplicação, ou seja, estamos utilizando controllers para receber os dados das requisições feitas. 

Exemplo de uma das aplicações: 

![](img/controller.jpg)

<p align="center">
  Fig 2: Uso da controller.
</p>

Arquivo completo: [RocketController.js](https://github.com/UnBArqDsw2020-2/2020.2_G6_RocketX_BackEnd/blob/main/src/controllers/RocketController.js)

## Polimorfismo

Adaptado para o uso de Java (sem classes e classes abstratas) criamos alguns objetos que sobrescrevem os métodos da cadeia de protótipos.  
Na imagem abaixo a *Base* é um objeto genérico, e os demais objetos a partir dele como o *RocketBase*, são especificações da generalização *Base*, o que categoriza o polimorfismo, utilizando as ferramentas da linguagem, deixando assim o código menos acoplado e mais coeso. 

Exemplo da aplicação:

![polimorfism](img/polimorfism.jpg)

<p align="center">
  Fig 3: Uso de polimorfismo.
</p>

Arquivo completo: [base.js](https://github.com/UnBArqDsw2020-2/2020.2_G6_RocketX_BackEnd/blob/main/src/baseController/base.js)

---

### Versionamento

|Data|Versão|Descrição|Autor|
|:--:|:----:|:-------:|:---:|
|06/04/2021| 0.1 | Criação do documento e adição das figuras | Ailamar Alves

<br>

### Referências 
 - AULA - GRASP – PARTE I. Milene Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/639891/mod_label/intro/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20GRASP%20BASE%20Parte%20I%20-%20Profa.%20Milene.pdf> . Acesso em: abr, 2021.

