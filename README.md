# Avaliação N3 Metodologias Ageis

## Papeis Scrum

Alunos: 
- Otavio M. Rau (Todas as Roles)

---
## Estrutura do Projeto
|Serviço|Technologia - Framework| Link Repositório
|---|---|---|
|Frontend|TypeScript - NextJS|[Labs Manager Frontend](https://github.com/Labs-Manager-Corp/Labs-Manager-Front-End)|
|Backend|Java 21 - Spring Boot|[Labs Manager Backend](https://github.com/Labs-Manager-Corp/Labs-Manager-Backend)|
|Database|MongoDB - Mongo Atlas Cloud|[Mongo Atlas](https://www.mongodb.com/pt-br/atlas)|
|Relatórios / Administrativo|Markdow|[Relatórios](https://github.com/Labs-Manager-Corp/Notes)|

Todos os repositórios aqui listados estão públicos

---
## Backlog

### Frontend
- Criação do repositório Frontend - OK
- Criação da rota da tela Inicial
- Criação da rota da tela do usuário
- Criação da rota de tela de cadastros
  - Criação da tela de cadastro de usuário
  - Criação da tela de cadastro de laboratório
  - Criação da tela de cadastro de status de alocação

- Criação de componentes em tela
  - Criação do componente cadastro de notificação
  - Criação do componente visualização de notificação
  - Criação de componente validação de role de usuário
  - Criação de componente modelo de campo de texto
  - Criação de componente DataPicker
  - Criação de componente Select
  - Criação de componente Root Bar
  - Criação de componente List (Para lista de itens internos)
  - Criação de componente Commun Fucntions
  - Criação de componente Modal Genérico (Incluindo Context)
    - Modal de Info sobre Laboratório (Validar Ideia)
    - Modal de formulário de reserva (Validar Ideia)
  - Criação de componente Dialog Genérico (Incluindo Context)

  - Criação de componente comunicação com Backend
    - Grupo laboratórios
    - Grupo Users
    - Grupo Solicitações

### Backend
- Criação do repositório Backend
- Criação de classe genérica para paginação de respostas

- Criação do grupo de controllers de laboratório
  - Criação do controller de cadastro de laboratório
  - Criação do controller de atualização de cadasto de laboratório
  - Criação do controller de remoção de cadastro de laboratório
  - Criação do controller de listagem específica de cadastro de laboratório
  - Criação do controller de listagem geral de cadastro de laboratório

- Criação de grupo de controller de cadastro de usuários
  - Criação do controller de cadastro de usuário
  - Criação do controller de atualização de cadasto de usuário
  - Criação do controller de remoção de cadastro de usuário
  - Criação do controller de listagem específica de cadastro de usuário
  - Criação do controller de listagem geral de cadastro de usuário

- Criação de grupo de controller de solicitações do sistema
  - Criação do controller de cadastro de solicitações do sistema (Abertura)
  - Criação do controller de atualização de cadasto de solicitações do sistema
  - Criação do controller de listagem específica de cadastro de solicitações do sistema
  - Criação do controller de listagem geral de cadastro de solicitações do sistema

- Criação de entidade (entity) de tipo de usuário
- Criação da entidade (entity) para modelo de usuário
- Criação de entidade (entity) para modelo de laboratório
- Criação de entidade (entity) para modelo de histórico de aluguel
- Criação de entidade (entity) para modelo de softwares instalados
- Criação de entidade (entity) para modelo de solicitações

- Validações
  - Validar tipo de modelo para uso de tipo de variavel Time nos processos de cadastro de reserva
  -

### Database
- Criação da conta de MongoDB - OK
- Configuração de conexão com backend

---
## Relatórios de Sprints

### Sprint 1
Data: 30/10/24 ~ 06/11/24

#### Relatório de Status:
Resumo:
- Realizado primeira análise do projeto e objetivos. Criado primeira versão local do backlog, juntamente com arquiteturação do sistema e dos processos do mesmo.

### Sprint 1
Data: 30/10/24 ~ 06/11/24

#### Relatório de Status:

### Sprint 2

Data: 06/11/24 ~ 12/11/24
#### Relatório de Status:

### Sprint 3

Data: 13/11/24 ~ 19/11/24
#### Relatório de Status:


### Sprint 3

Data: 20/11/24 ~ 26/11/24
#### Relatório de Status:

### Sprint 4

Data: 27/11/24 ~ 03/12/24
#### Relatório de Status:

### Sprint 5

Data: 04/12/24 ~ 10/12/24
#### Relatório de Status:


## Relatório Final

### Principais Desafios
- Definição de Sprints e Backlogs:
Foi realizado uma pesquisa de modelos e com base nas referências de modelos e imagens de modelos de metodologias, juntamente com a experiência própria foi criado um template próprio para seguimento de atividades com base nos objetivos criados no backlog

- Configuração de Ambiente:
O projeto havia sido inicializado utilizando banco de dados relacional Postgre rodando na máquina local, mais especificamente em um contêiner docker. E devido a isso precisou-se alterar para MongoDB Atlas, e devido a complexidade de realização da comunicação do servidor backend java spring boot e o MongoDB acabou que não foi possível realizar tal conexão em tempo hábil do projeto

### Pontos Fortes e Melhorias


### Impactos do Scrum

---
# Templates de Referências
```
Modelo para relatório de Sprints:
Objetivos:
        [Objetivo 1]
        [Objetivo 2]
        ...
    Tarefas Concluídas:
        [Tarefa 1]
        [Tarefa 2]
        ...
    Tarefas em Andamento:
        [Tarefa 1]
        [Tarefa 2]
        ...
    Impedimentos:
        [Impedimento 1]
        [Impedimento 2]
        ...
```
