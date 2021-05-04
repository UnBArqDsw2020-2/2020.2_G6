# REUTILIZAÇÃO

## 1. Framework

* Um framework é ....
 
 - Estamos usando: 
    * ReactJS;
 
 - **Hotspots**: São partes do framework que são projetados para serem genéricos podendo ser adaptada para a necessidade do usuário. Normalmente são representadas por classes abstratas, ou seja, necessita de um baixo nível de acoplamento e por isso tem grande aproximação com os design patterns.
    * Temos: O arquivo base.js que faz uso design pattern Decorator, sendo ele uma classe genérica de controllers, ou seja, a partir dele podem ser especificados mais controllers.
 
 - **Frozenspots**: Também conhecido como "core" do framework, definem a arquitetura geral de um sistema de software e por isso permanecem fixos como a base do framework.
    * Temos: Os serviços de uso do back-end do diretório routes definidos pelas rotas já especializadas, onde tem uma entrada esperada e uma saída esperada.


## 2. Biblioteca

* Uma biblioteca é...

 (acho que não temos nada que pode se tornar uma)

## 3. Serviços

* Serviços são ...

 - Nosso back-end por obedecer o padrão RESTful pode funciona como um provedor de serviço que é consumido no front-end ...

## 4. Componentes

* Componentes são...

(Procurar no Diagrama de Componentes) 

## 5. Outros

### 5.1 Plug-in

* Um plug-in tem como objetivo adcionar funcionalidades especificas para programas maiores que já tenham camadas de reutilização para poderem ser acoplados, adicionando um nivel de reutilização e extensibilidade para tal framework ou qualquer outro programa maior.

### 5.2 Linha de Produto

* Uma linha ou família de produto faz uso de Engenharia de Domínio para se estabelecer e enriquecer um escopo sólido para o núcleo de artefatos, e planos de produção. Depois de estabelecer um escopo de um núcleo sólido, é feita a Engenharia de Aplicação, que vai aplicar especificações e derivações do nucleo definido em forma de produtos, retorno, novos artefatos e demais aplicaçòes. Porém, o grande problema da linha de produto é a complexidade muito alta, a dificuldade de se estabelecer ideias totalmente coesas entre sí e os gastos.

---

## Versionamento

|Data|Versão|Descrição|Autor|
|:--------:|:---:|:-------------------:|:------------:|
|03/05/2021| 0.1 | Criação do escopo do documento| Matheus Amaral 
  
</br>

### Referências
