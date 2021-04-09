# Aplicação Padrões de Projeto: GoF Comportamental

Foram utilizados no projeto dois padrões comportamentais do GoF: [State]() e [Memento]().

## State

O exemplo para aplicação desse padrão foi baseado na tela de veículos do projeto, como podemos observar no nosso [protótipo](https://unbarqdsw2020-2.github.io/2020.2_G6_RocketX/#/pages/base/prototype?id=prot%c3%b3tipo-de-alta-fidelidade).

O comportamento desse componente será baseado em uma variável _loading_ que irá observar a requisição que é feita para a API e uma variável _error_ para monitorar possível erro causado durante a requisição. Enquanto estiver sendo feito a busca dos veículos no backend e não ocorrer erro, irá apresentar ao usuário uma mensagem de carregamento, caso tenha sucesso na requisição, é listado o nome dos veículos e em caso de erro, é apresentada uma mensagem com essa indicação.

[_Link para código no GitHub_](https://github.com/UnBArqDsw2020-2/2020.2_G6_RocketX_FrontEnd/blob/main/src/pages/Rockets/index.jsx)

![](/docs/assets/img/designpattern/gof-behavioral/state.png)

---

### Versionamento

|    Data    | Versão |                   Descrição                   |      Autor      |
| :--------: | :----: | :-------------------------------------------: | :-------------: |
| 07/04/2021 |  0.1   | Criação do documento e adição do padrão State | Heron Rodrigues |
