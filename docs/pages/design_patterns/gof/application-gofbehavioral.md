# Aplicação Padrões de Projeto: GoF Comportamental

Foram utilizados no projeto dois padrões comportamentais do GoF: [State]() e [Memento]().

## State

O exemplo para aplicação desse padrão foi baseado na tela de veículos do projeto, como podemos observar no nosso [protótipo](https://unbarqdsw2020-2.github.io/2020.2_G6_RocketX/#/pages/base/prototype?id=prot%c3%b3tipo-de-alta-fidelidade).

O comportamento desse componente será baseado em uma variável _loading_ que irá observar a requisição que é feita para a API e uma variável _error_ para monitorar possível erro causado durante a requisição. Enquanto estiver sendo feito a busca dos veículos no backend e não ocorrer erro, irá apresentar ao usuário uma mensagem de carregamento, caso tenha sucesso na requisição, é listado o nome dos veículos e em caso de erro, é apresentada uma mensagem com essa indicação.

[_Link para código no GitHub_](https://github.com/UnBArqDsw2020-2/2020.2_G6_RocketX_FrontEnd/blob/main/src/pages/Rockets/index.jsx)

![](/docs/assets/img/designpattern/gof-behavioral/state.png)

## Memento

A biblioteca de navegação entre componentes [_react-router-dom_](https://reactrouter.com/) utiliza, em sua pilha de navegação, esse padrão comportamental. Sendo possível acessar o valor anterior da rota de navegação.

[_Link para código no GitHub_](https://github.com/UnBArqDsw2020-2/2020.2_G6_RocketX_FrontEnd/blob/main/src/App.js)

![](/docs/assets/img/designpattern/gof-behavioral/memento-1.png)

[_Link para código no GitHub_](https://github.com/UnBArqDsw2020-2/2020.2_G6_RocketX_FrontEnd/blob/main/src/pages/Account/index.jsx)

![](/docs/assets/img/designpattern/gof-behavioral/memento-2.png)

[_Link para código no GitHub_](https://github.com/UnBArqDsw2020-2/2020.2_G6_RocketX_FrontEnd/blob/main/src/pages/Dashboard/index.jsx)

![](/docs/assets/img/designpattern/gof-behavioral/memento-3.png)

---

### Versionamento

|    Data    | Versão |                   Descrição                   |      Autor      |
| :--------: | :----: | :-------------------------------------------: | :-------------: |
| 07/04/2021 |  0.1   | Criação do documento e adição do padrão State | Heron Rodrigues |
| 09/04/2021 |  0.2   |           Adição do padrão Memento            | Heron Rodrigues |
