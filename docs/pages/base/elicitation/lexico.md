# Léxico
 
Trata-se de uma técnica que descreve os símbolos de uma linguagem. Esses símbolos são descritos com noções e impactos, além disso são divididos entre estados, objetos e verbos. Tem como objetivo identificar palavras chaves que podem ser desconhecidas. 
 
## Metodologia

Cada termo levantado deve ser descrito com sua noção e impacto, sendo a noção o que realmente significa o termo, ou seja, a definição literal e o impacto representando o efeito e qual o real uso daquele termo na aplicação. Os termos escolhidos são utilizados frequentemente ou funcionalidades presentes no projeto, baseado em levantamentos dos [Requisitos](https://unbarqdsw2020-2.github.io/2020.2_G6_RocketX/#/pages/base/elicitation/introspeccao) e ideias do [Brainstorming](https://unbarqdsw2020-2.github.io/2020.2_G6_RocketX/#/pages/base/elicitation/brainstorming)

## Levantamentos 
### Tipo verbo
 
ID  | Termo | Noção | Impacto | Sinônimos |
:-: | :---: | :---- | :------ | :-------- |
LV-1 | Cadastrar | - Criar uma conta pessoal na plataforma | - Contato inicial do usuário com o a página. <br> - Após o cadastro o usuário terá acesso aos dados da página. | - Registrar-se <br> - *Sign Up* |
LV-2 | Login | - Usuário fornece sua identificação de acesso | - Usuários já cadastrados utilizam *user* e senha. | - *Sign In*<br>- Entrar<br>- Logar
LV-3 | Editar Perfil | - Editar informações cadastradas<br> - Atualizar dados | - Dados de contato e informações básicas do usuário podem ser alterados. | - Alterar dados <br>- Atualizar cadastro
LV-4 | Filtrar informações | - Filtrar pedidos de ajuda no mapa a partir da categoria de cada uma delas | - Separa as ajudas, que serão mostradas no mapa, por categorias | - Separar <br> - Selecionar <br> - Especificar
LV-5 | Acessar lançamentos futuros | - Usuário navega na seção de futuros lançamentos da SpaceX | - Usuário possui acesso a lista de lançamentos que estão em andamento. | -
LV-6 | Acessar lançamentos anteriores | - Usuário navega na seção de lançamentos já ocorridos da SpaceX | - Usuário possui acesso a lista de lançamentos que já ocorreram e dados informativos sobre os acontecimentos. | -
LV-7 | Sair | - Desconectar da conta | - O usuário desconecta da conta em sua máquina. <br> - Usuário finaliza sua navegação no site. | - *Logout* <br> -Desconectar

 
### Tipo objeto
 
ID | Termo | Noção | Impacto | Sinônimos |
:-:| :---: | :----: | :------ | :-------- |
LO-1 | Plataforma | - Relacionado ao sistema projetado<br> - Utilizado através de um navegador<br> - Acessado por um computador ou celular | - Visualizar informações<br> - Acesso ao produto | - *Site*
LO-2 | Dashboard | - Ferramenta de gestão de informaçãoo<br> - Indicador de métricas<br> - Painel gráfico visual | - Facilita no entendimento das métricas<br> - Mais confortavel de ler e visualizar informações | - Gráfico <br> - Painel
LO-3 | Colaboradores | - Pessoas que trabalham no desenvolvimento do projeto | - Trabalho colaborativo<br> - Auxiliar na eficiência da criação do produto<br> - Fornecer ideias | - Equipe<br> - Grupo<br> - Membros <br> - Time
LO-4 | Projeto | - O que será desenvolvido<br> - Resultado do trabalho | - Solução do problema levantado inicialmente | - Produto final
LO-5 | Usuário | - Pessoa que usufrui do serviço<br> - Destinatário final | - Executar as funcionalidades propostas pela plataforma | - Cliente
LO-6 | Issue | - Pode ser traduzido como um problema ou questão | - Se refere à uma atividade a ser resolvida ou finalizada | - Problema<br> - Tarefa<br> - Questão
LO-7 | Programador | - Pessoa que se compromete a desenvolver o software | - Resolver o problema inicial<br> - Planejar processos e etapas de produção<br> - Publicar o Produto | - Engenheiro de Software<br> - Desenvolvedor
LO-8 | Protótipo | - Layout ou esquema inicial de inspiração<br> - Sistema modelo apenas com funcionalidades gráficas  | - Visualizar o produto final esperado<br> - Criado e aprovado pela equipe | - Esquema do software <br> - Esboço 
LO-9 | Requisitos | - Podem ser especificações que descrevem como o software se comporta <br> - Podem ser especificações que influenciam no uso do software | - Resolver o problema inicial<br> - Influencia na aceitação da aplicação pelo usuário<br> - Podem ser classificados em funcionais e não funcionais | -Funcionalidades
LO-10 | Veículos | - Objeto ou transporte que foi lançado para orbita | - Executar sua missão<br> - Obter informações em seu destino final | - Espaçonave<br> - Foguetes<br> - Veículo não tripulado


### Tipo estado
 
ID  | Termo | Noção | Impacto | Sinônimos |
:-: | :---: | :---- | :------ | :-------: |
LE-1 | Lançamento anterior | - Missões já executadas | - Veículos que já fizeram seu pouso<br> | - Evento encerrado
LE-2 | Lançamento futuro | - Missões que vão ser executadas em breve | - Podem resultar em sucesso ou falhas<br> - Trazem à Terra informações de acordo com seu objetivo | - Próximo evento
LE-3 | Missões bem sucedidas | - Missões completas e finalizadas | - Atingiram sua meta com sucesso | - Sucesso
LE-4 | Missões falhas | - Missões que sofreram algum imprevisto durante a execução | - Não atingiram seu objetivo<br> - Problemas com a espaçonave | - Falha 
LE-5 | Em desenvolvimento | - Produto que ainda está passando pelo processo de criação de suas funcionalidades | - Fase de execução do que foi planejado | - Em andamento<br> - Em homologação
LE-6 | Em Produção | - Produto já publicado<br> - Pronto para uso | - Aplicação disponível para os usuários | - Publicado

---

## Versionamento
 
|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|17/02/2021| 0.1 | Introdução do documento | Matheus Amaral
|18/02/2021| 0.2 | Adição dos termos do tipo verbo | Ailamar Alves
|04/03/2021| 0.3 | Adição dos termos do tipo objeto | Ailamar Alves e Ingrid Galvão
|06/03/2021| 0.4 | Adição dos termos do tipo estado | Matheus Amaral 

<br> 

## Referências 

- 02g - VídeoAula - DSW - Base - Glossário & Léxico. Milene Serrano. Disponível em: <https://unbbr-my.sharepoint.com/personal/mileneserrano_unb_br/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fmileneserrano%5Funb%5Fbr%2FDocuments%2FArqDSW%20%2D%20V%C3%ADdeosOriginais%2F02g%20%2D%20VideoAula%20%2D%20DSW%2DBase%20%2D%20Glossario%20Lexico%2Emp4&parent=%2Fpersonal%2Fmileneserrano%5Funb%5Fbr%2FDocuments%2FArqDSW%20%2D%20V%C3%ADdeosOriginais&originalPath=aHR0cHM6Ly91bmJici1teS5zaGFyZXBvaW50LmNvbS86djovZy9wZXJzb25hbC9taWxlbmVzZXJyYW5vX3VuYl9ici9FUzMxS1hITWRtWkVodC1tcDJTSXg5WUJWSUJZUHE1ajZDOERaajdpLWllNV9BP3J0aW1lPVRPYnhLUGZmMkVn>. Acesso em: fev 2021.

- Construção do léxico de aplicações. Miriam Sayão; Gustavo R. de Carvalho. Disponível em: <http://www.nilc.icmc.usp.br/til/til2006/0030.pdf>. Acesso em: mar 2021.


