Projeto: Django API com React
Visão Geral
Este projeto integra um backend desenvolvido com Django e um frontend construído com React. O objetivo principal é criar uma aplicação web onde o frontend consome os dados de uma API RESTful fornecida pelo backend.

Estrutura do Projeto
backend/: Contém o código do servidor Django que gerencia a API.
frontend/: Inclui o código React para a interface do usuário.
env/: Arquivos de configuração do ambiente.
Funcionalidades
API RESTful: Django fornece endpoints para operações CRUD.
Interface do Usuário: React é utilizado para criar uma UI dinâmica que interage com a API.
Como Rodar o Projeto
Configuração do Backend:

Navegue até o diretório backend/.
Instale as dependências com pip install -r requirements.txt.
Rode as migrações do banco de dados com python manage.py migrate.
Inicie o servidor com python manage.py runserver.
Configuração do Frontend:

Navegue até o diretório frontend/.
Instale as dependências com npm install.
Inicie a aplicação React com npm start.
Tecnologias Utilizadas
Backend: Django, Django REST framework
Frontend: React, JavaScript, CSS
Banco de Dados: SQLite (padrão, pode ser configurado para outro banco)
Contribuição
Contribuições são bem-vindas. Para contribuir, faça um fork do repositório, crie uma branch para suas alterações e envie um pull request.
