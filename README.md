Este projeto é um aplicativo de lista de tarefas (todo list) desenvolvido com Node.js, Express, Handlebars, Sequelize e MySQL. O principal objetivo deste projeto foi aprender e implementar o padrão MVC (Model-View-Controller), que organiza a aplicação de maneira modular, separando a lógica de negócio, visualização e controle.

Funcionalidades:
Criar: Adicionar novas tarefas à lista.

Ler: Exibir todas as tarefas cadastradas.

Atualizar: Editar tarefas existentes.

Deletar: Remover tarefas da lista.

Tecnologias Utilizadas:
Node.js: Plataforma para o desenvolvimento do servidor.

Express: Framework para construção das rotas e controle da aplicação.

Sequelize: ORM (Object-Relational Mapping) para interação com o banco de dados MySQL.

MySQL: Banco de dados relacional utilizado para armazenar as tarefas.

Handlebars: Motor de templates utilizado para renderizar as views.

MVC (Model-View-Controller): Padrão de arquitetura utilizado, que separa a lógica da aplicação em três componentes distintos.

Estrutura do Projeto:
A estrutura do projeto segue o padrão MVC, sendo dividida em pastas como controllers, models, views, routes, e outras. Aqui está um resumo da organização do projeto:

controllers/: Contém a lógica para manipulação das rotas e interação com os dados.

db/: Arquivos de configuração para o banco de dados.

models/: Define os modelos que representam as tabelas do banco de dados.

public/: Arquivos estáticos como CSS, JS e imagens.

routes/: Define as rotas da aplicação.

views/: Contém as views renderizadas com Handlebars.

layouts/: Layouts comuns para as views (como cabeçalhos e rodapés).

index.js: Arquivo responsável por inicializar o servidor.

Como Executar o Projeto:
Clonar o Repositório: Clone o repositório e entre na pasta do projeto:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/crud-todo-node.git
cd crud-todo-node
Instalar Dependências: Execute o comando para instalar as dependências do projeto:

bash
Copiar
Editar
npm install
Configurar Banco de Dados: Antes de rodar o projeto, crie o banco de dados MySQL e configure as credenciais no arquivo db/config.js.

Executar a Aplicação: Para rodar a aplicação, utilize o comando:

bash
Copiar
Editar
npm start
A aplicação estará disponível em http://localhost:3000.

Rotas:
GET /tasks: Exibe todas as tarefas.

POST /tasks: Adiciona uma nova tarefa.

GET /tasks/:id/edit: Exibe o formulário de edição de uma tarefa.

PUT /tasks/:id: Atualiza uma tarefa existente.

DELETE /tasks/:id: Deleta uma tarefa.

Este projeto foi uma excelente oportunidade para aprender o padrão MVC na prática, estruturando a aplicação de maneira modular e escalável. Estou empolgado com o aprendizado e como o padrão MVC facilita a manutenção e expansão da aplicação.








