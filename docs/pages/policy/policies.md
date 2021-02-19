# Políticas de contribuição

Esse documento possui os métodos e regras para padronização das contribuíções feitas ao projeto, contendo as normas e exigências para melhor organização do repositório. Caso houver alguma dúvida, entrar em contato com os integrantes.

## Issues

- Nome (Breve descrição da tarefa que será realizada.)

- Descrição (Deve ser clara e direta, o objetivo é informar somente o necessário para a realização da tarefa)

- Critérios de aceitação (Os critérios de aceitação da *issue* são o guia para que a issue seja finalizada.)
    - [ ] Critério A
    - [ ] Critério B
    - [ ] Critério C

A *Issue* só estará completa depois de todos os critérios de aceitação terem sido cumpridos.

### Observação

- Toda *Issue* deve ter, pelo menos, um membro como responsável pela mesma.

- As *Issues* devem possuir *labels* que as identifiquem com a prioridade e também o tipo de trabalho que será realizado.

- A *Issue* deve ser relacionada no *milestone* com a sua *Sprint* ao decorrer do desenvolvimento.  

## Commits

- Os *Commits* devem manter o padrão escrito em inglês e no passado, de preferência iniciados com um verbo, curtos e diretos, além de serem relacionados com o número da *Issue*.

**Exemplo:**

```
    git commit -m "[#2] Added personas definitions"
```

## Pull Request

- Nome (O *Pull request* deve indicar o número e nome da issue, ao qual se refere)

- Descrição (A descrição do *Pull request* deve ser escrito de forma clara e objetiva. O que foi resolvido, quais issues foram resolvidas e quais eram os critérios de aceitação.)

**Exemplo**

```
    Este Pull request resolveu a issue#<NumeroDaIssue> de tal forma e os critérios de aceitação eram:
    * Task A;
    * Task B;
    * ...
```

### Observação

- O *Pull request* só pode ser aceito depois que houver a revisão do mesmo.
- Indivíduos que participaram ativamente do desenvolvimento da *branch* não poderão revisar o *Pull request*.

## Branches

- O nome da *branch* deve ser escrito em inglês, sem caracteres especiais e relacionado com o número da *Issue*.

**Exemplo:**

```
    2_define_points
```

- Se houver a necessidade de uma branch de correção, o seu nome não terá o um número, mas a *tag* de *HotFix* seguida do erro que foi corrigido.

**Exemplo:**

```
    HotFix_grammar_error_archive_x
```

### Atenção

- Para adicionar múltiplos contribuidores em um *commit* deve apertar "Enter" duas vezes antes de finalizar as aspas:

```
    git commit -m "[#9] Added topics definitions

    Co-authored-By: Nome do ajudante1 <Email do ajudante1>
    Co-authored-By: Nome do ajudante2 <Email do ajudante2>"
```

## Arquivos

- Nomes e Endereços: toda vez que for necessário criar um novo arquivo, crie uma pasta em:

```
    docs/pages/nomeDaPasta/nomeDoArquivo.md
```

- Todo arquivo e pasta novos seguirão o padrão *camelCase* e serão escritos em inglês.

### Imagens

- Se houver a necessidade de utilizar imagens, crie uma pasta *images* dentro da pasta que deseja utilizá-las.


```
    docs/pages/pastaDoMeuArquivoAtual/images
```

### Wikipage

- Para adicionar um novo documento na *Wiki* do projeto, deve-se adicionar o endereço do mesmo no arquivo:

```
    ./_sidebar.md
```

---

## Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|15/02/2021| 0.1 | Criação do documento de políticas de contribuição | Ailamar Alves


