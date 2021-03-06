# Cenários

Um cenário é um ambiente criado pela equipe de projeto para representar situações que ajude a compreender as interações entre os sistemas e também elicitar a parte comportamental do software. Essa técnica tem se provado muito eficiente para levantamento de requisitos apesar de informal.

## Metodologia 

A técnica funciona com a criação de narrativas que descrevem um episódio específico que necessitam do uso da tecnologia do nosso projeto. Para isso, de acordo com o que foi gerado a partir dos [Storyboards](https://unbarqdsw2020-2.github.io/2020.2_G6_RocketX/#/pages/base/elicitation/storyboard) e nos levantamentos de [Requisitos](https://unbarqdsw2020-2.github.io/2020.2_G6_RocketX/#/pages/base/elicitation/introspeccao) e [Rich Picture](https://unbarqdsw2020-2.github.io/2020.2_G6_RocketX/#/pages/base/preTraceability/richPicture) a equipe foi criando situações que serão encontradas na plataforma RocketX. <br/><br/>

**Modelo base:**  
<br/>
Tópico | Descrição 
----: | :--------
**Título**   | Nome breve para o cenário
**Objetivo** | Finalidade da história 
**Contexto** | Local, tempo e pré-condição da história
**Atores**   | Personagens que participarão da história
**Recurso**  | Recursos envolvidos
**Restrição** | Critérios favoráveis, caso tenha
**Exceção**  | Critérios desfavoráveis, caso tenha
**Episódio** | Descrição da narrativa 
<br/>

### C1 - Primeiro acesso ao site

|      | Descrição 
:----- | :--------
**Objetivo** | Primeiro contato com a plataforma acessando o site
**Contexto** | Local: em casa<br/>Tempo: pela manhã<br/> Pré-condição: interesse em eventos espaciais
**Ator(es)** | Novo usuário
**Recurso**  | Computador para acesso ao site
**Restrição** | Aceitar fazer o cadastro
**Exceção**  | Falta de sinal de internet
**Episódio** | Usuário ouve falar sobre o site e fica curioso para conhecer.<br/> Ao acessar o domínio fica interessado com as informações que pode encontrar.<br/> Usuário explora página inicial do site.<br/> Encontra campo para fazer seu cadastro.
<br/>

### C2 - Cadastro no site

|      | Descrição 
:----- | :--------
**Objetivo** | Criar uma conta no RocketX Board
**Contexto** | Local: página inicial do site<br/>Tempo: de manhã<br/>Pré-condição: não possuir cadastro
**Ator(es)** | Usuário não cadastrado
**Recurso**  | Computador ou telefone<br/>Acesso a internet<br/>Possuir e-mail compatível<br/>
**Restrição** | Conta de e-mail ativa
**Exceção**  | E-mail já cadastrado
**Episódio** | Usuário não cadastrado entra no site.<br>Usuário seleciona criar conta.<br> Usuário adiciona informações pessoais (nome, idade)<br> Usuário preenche e-mail, senha e confirmar senha.<br> Usuário espera validação para permitir seu acesso.<br> Usuário fica disponível para receber curiosidades e notificações de novidades além dos dashboards. 
<br/>

### C3 - Primeiro contato com os dashboards

|      | Descrição
:----- | :--------
**Objetivo** | Navegar pelos dashboards da plataforma 
**Contexto** | Local: em casa<br/>Tempo: a noite<br/> Pré-condição: ter tempo livre
**Ator(es)** | Lucas 
**Recurso**  | Computador ou telefone com internet<br/> 
**Restrição** | Analisar gráficos
**Episódio** | Lucas acessa seu perfil para ficar por dentro dos acontecimentos novos da SpaceX.<br/> Lucas encontra um quadro com informações sobre a decolagem da nave SN10.<br/> Ao se interessar pela notícia Lucas resolve explorar um pouco mais o site para encontrar mais novidades.
<br/>

### C4 - Recebendo notificações

|      | Descrição
:----- | :--------
**Objetivo** | Receber notificação sobre algo novo adicionado ao site 
**Contexto** | Local: onde o site for acessado<br/>Tempo: ao longo do dia<br/> Pré-condição: ter cadastro no site
**Ator(es)** | Andreza e Marcos 
**Recurso**  | Computador ou telefone com internet<br/> 
**Exceção**  | Usuário não possuir cadastro no RocketX
**Episódio** | Andreza e seu noivo têm muito interesse em assuntos sobre atividades espaciais, ela possui uma conta na plataforma.<br> Pelo menos uma vez na semana entra em seu perfil para saber das atualizações dos lançamentos.<br/> Em seu último login recebeu uma notificação sobre dois eventos que entraram no calendário da SpaceX.<br> Os casal anotou as datas para assistirem a transmissão dos dois eventos.
<br/>

### C5 - Informação de um futuro lançamento 

|      | Descrição
:----- | :--------
**Objetivo** | Notificar aos usuários sobre novos lançamentos 
**Contexto** | Local: em casa<br/>Tempo: a noite<br/> Pré-condição: acesso ao site
**Ator(es)** | Usuários 
**Recurso**  | Computador ou telefone com internet<br/> 
**Restrição** | Interesse em novos eventos
**Episódio** | Um novo evento de lançamento de uma das espaçonaves é anunciado pela empresa.<br/> Usuários que acessarem o site verão que existe esse novo evento disponível.
<br/>

---

### Versionamento

|Data|Versão|Descrição|Autor|
|:--:|:----:|:-------:|:---:|
|03/03/2021| 0.1| Criação do escopo do documento| Ailamar Alves |
|03/03/2021| 0.2| Adição dos cenários 1 a 3 | Ailamar Alves |
|06/03/2021| 0.3| Adição dos cenários 4 e 5 | Ailamar Alves |

<br>

### Referências 

- Cenários e Casos de uso: Fundamentos e Conceitos. Diponível em: <https://www.devmedia.com.br/artigo-engenharia-de-software-16-cenarios-e-casos-de-uso-fundamentos-e-conceitos/14186>. Acesso em: mar 2021.

- Personas e Cenários. PUC-Rio. Disponível em: <http://www.inf.puc-rio.br/~inf1403/docs/alberto2011_1/07_Personas_Cenarios.pdf> Acesso em: mar 2021.
