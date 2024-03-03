## Gerenciamento de Biblioteca com Flask

**Atualização**

Este projeto foi atualizado para incluir os campos `ano_publicacao` e `genero` no modelo `Livro`. As rotas `POST`, `GET`, `PUT` e `GET` do livro também foram modificadas para incluir os novos campos.

### Funcionalidades

* CRUD de Livros: Crie, leia, atualize e delete livros usando a API REST.
* Armazenamento com SQLite: Facilita o armazenamento e recuperação de dados de livros.
* Feedback ao Usuário: Fornece respostas claras e informativas para as ações do usuário.

### Novas Funcionalidades

* **Gerenciamento de Ano de Publicação:** Permite adicionar, atualizar e consultar livros por ano de publicação.
* **Gerenciamento de Gênero:** Permite adicionar, atualizar e consultar livros por gênero.

### Tecnologias Utilizadas

* Flask
* Flask-SQLAlchemy
* SQLite

### Como Configurar

#### Pré-Requisitos

* Python 3.6 ou superior
* pip

#### Instalação

1. Clone o repositório para sua máquina local:

```bash
git clone <URL do repositório>
```

2. Navegue até o diretório do projeto:

```bash
cd <nome do diretório do projeto>
```

3. Instale as dependências necessárias:

```
pip install flask flask_sqlalchemy
```

### Como Executar

1. Inicie o servidor Flask executando:

```
python app.py
```

2. A aplicação agora estará rodando em http://localhost:5000/. Você pode acessar os endpoints definidos utilizando um cliente HTTP como Postman ou via curl.

### Endpoints da API

* **POST /livro:** Adiciona um novo livro. Exemplo de corpo da requisição: {"titulo": "Novo Livro", "autor": "Autor", "ano_publicacao": 2023, "genero": "Fantasia"}.
* **GET /livros:** Retorna uma lista de todos os livros.
* **GET /livro/<id>:** Retorna detalhes de um livro específico.
* **PUT /livro/<id>:** Atualiza um livro existente. Exemplo de corpo da requisição: {"titulo": "Livro Atualizado", "autor": "Autor Atualizado", "ano_publicacao": 2024, "genero": "Ficção Científica"}.
* **DELETE /livro/<id>:** Deleta um livro específico.


## Gerenciamento de Biblioteca com Flask

**Atualização**

Este projeto foi atualizado para incluir os campos `ano_publicacao` e `genero` no modelo `Livro`. As rotas `POST`, `GET`, `PUT` e `GET` do livro também foram modificadas para incluir os novos campos.

### Funcionalidades

* CRUD de Livros: Crie, leia, atualize e delete livros usando a API REST.
* Armazenamento com SQLite: Facilita o armazenamento e recuperação de dados de livros.
* Feedback ao Usuário: Fornece respostas claras e informativas para as ações do usuário.

### Novas Funcionalidades

* **Gerenciamento de Ano de Publicação:** Permite adicionar, atualizar e consultar livros por ano de publicação.
* **Gerenciamento de Gênero:** Permite adicionar, atualizar e consultar livros por gênero.

### Tecnologias Utilizadas

* Flask
* Flask-SQLAlchemy
* SQLite

### Como Configurar

#### Pré-Requisitos

* Python 3.6 ou superior
* pip

#### Instalação

1. Clone o repositório para sua máquina local:

```bash
git clone <URL do repositório>
```

2. Navegue até o diretório do projeto:

```bash
cd <nome do diretório do projeto>
```

3. Instale as dependências necessárias:

```
pip install flask flask_sqlalchemy
```

### Como Executar

1. Inicie o servidor Flask executando:

```
python app.py
```

2. A aplicação agora estará rodando em http://localhost:5000/. Você pode acessar os endpoints definidos utilizando um cliente HTTP como Postman ou via curl.

### Endpoints da API

* **POST /livro:** Adiciona um novo livro. Exemplo de corpo da requisição: {"titulo": "Novo Livro", "autor": "Autor", "ano_publicacao": 2023, "genero": "Fantasia"}.
* **GET /livros:** Retorna uma lista de todos os livros.
* **GET /livro/<id>:** Retorna detalhes de um livro específico.
* **PUT /livro/<id>:** Atualiza um livro existente. Exemplo de corpo da requisição: {"titulo": "Livro Atualizado", "autor": "Autor Atualizado", "ano_publicacao": 2024, "genero": "Ficção Científica"}.
* **DELETE /livro/<id>:** Deleta um livro específico.

### Contribuindo

Contribuições são muito bem-vindas! Por favor, leia o CONTRIBUTING.md para mais detalhes sobre nosso código de conduta, e o processo para enviar pedidos de pull.

### Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo LICENSE.md para detalhes.





### Contribuindo

Contribuições são muito bem-vindas! Por favor, leia o CONTRIBUTING.md para mais detalhes sobre nosso código de conduta, e o processo para enviar pedidos de pull.

### Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo LICENSE.md para detalhes.
