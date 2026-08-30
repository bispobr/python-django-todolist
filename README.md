# TodoList com Django

Aplicação web simples desenvolvida em Python utilizando Django para gerenciamento de tarefas.

O projeto foi desenvolvido como prática de desenvolvimento web com Django, utilizando um banco de dados baseado em arquivo para persistência das informações.

## Funcionalidades

- Cadastro de tarefas
- Visualização de tarefas
- Gerenciamento de uma lista de tarefas

## Tecnologias

- Python
- Django
- SQLite
- Bootstrap

## Requisitos

- Python 3+
- Django
- Dependências adicionais utilizadas pelo projeto

## Instalação

Clone o repositório:

```bash
git clone https://github.com/bispobr/python-django-todolist.git
cd python-django-todolist
```

Instale as dependências utilizadas pelo projeto conforme a configuração atual da aplicação.

Caso as dependências estejam disponíveis em um arquivo `requirements.txt`, utilize:

```bash
pip install -r requirements.txt
```

## Executando o projeto

Utilize o arquivo `manage.py` para iniciar o servidor de desenvolvimento:

```bash
python manage.py runserver
```

A aplicação estará disponível em:

```text
http://localhost:8000
```

## Banco de dados

A aplicação utiliza um banco de dados baseado em arquivo para armazenar as informações.

O Django utiliza SQLite por padrão quando configurado dessa forma.

Para aplicar as migrações:

```bash
python manage.py migrate
```

## Como utilizar

Após iniciar o servidor, acesse a aplicação pelo navegador:

```text
http://localhost:8000
```

A partir da interface da aplicação, é possível gerenciar a lista de tarefas disponibilizada pelo projeto.

## Estrutura

O arquivo `manage.py` é utilizado como ponto de entrada para os comandos administrativos do Django.

A estrutura das aplicações, templates, modelos e demais componentes pode ser consultada diretamente no código-fonte do projeto.

## Comandos úteis

Iniciar o servidor:

```bash
python manage.py runserver
```

Aplicar migrações:

```bash
python manage.py migrate
```

Criar novas migrações:

```bash
python manage.py makemigrations
```

## Status

Projeto de estudos desenvolvido para praticar a construção de aplicações web utilizando Python e Django, com foco no gerenciamento de uma lista de tarefas.
