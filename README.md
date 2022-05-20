# Projeto que facilita o entendimento de um CRUD (CREATE , UPDATE e DELETE) usando o class based view no Django:

### Deploy local
Instale as seguinte bibliotecas com o comando pip:

`pip install django==3.2.13 django-bootstrap-v5`

Instale as dependências no requirements.txt:

`pip freeze > requirements.txt`

No terminal de seu ambiente de desenvolvimento, crie o projeto com:

`django-admin startproject <nome_do_seu_projeto> .`

Crie as migrações para o banco de dados

`python manage.py makemigrations`

E depois migrar os models para o banco de dados:

`python manage.py migrate`

Crie um superusuário para o gerenciamento do banco de dados:

`python manage.py createsuperuser`

Execute sua aplicação:

`python manage.py runserver`

Para acessar vá no seu navegador e digite http://localhost:8000
