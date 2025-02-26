Claro! Vou reescrever o `README.md` utilizando português de Portugal, evitando termos específicos do português brasileiro e adotando convenções mais comum em Portugal. Aqui está a versão ajustada:

---

# JobFinder_Laravel_2025

Uma aplicação de listagem de vagas de emprego desenvolvida com Laravel em 2025. Este projecto é baseado no curso "Laravel From Scratch 2022" de Brad Traversy e foi adaptado para as minhas necessidades de aprendizagem e desenvolvimento.

![Imagem do projecto (opcional)](URL_DA_IMAGEM_AQUI)
_Imagem da interface do JobFinder (adicione uma captura de ecrã, se desejar)._

## Sobre o Projecto

O **JobFinder_Laravel_2025** é uma aplicação web que permite aos utilizadores listar, visualizar, criar, editar e eliminar vagas de emprego. Utiliza o framework Laravel para oferecer uma experiência robusta e escalável, com integração de base de dados MySQL e funcionalidades CRUD completas.

## Funcionalidades

-   Listagem de vagas de emprego com filtros.
-   Criação, edição e eliminação de vagas (CRUD).
-   Carregamento de ficheiros relacionados com as vagas.
-   Autenticação e autorização de utilizadores.
-   Interface simples e responsiva.

## Requisitos

-   PHP 8.1 ou superior
-   Composer
-   Node.js e npm
-   MySQL
-   Laravel 9.x

## Instalação

### 1. Clonar o repositório

```bash
git clone https://github.com/smpsandro1239/JobFinder_Laravel_2025.git
cd JobFinder_Laravel_2025
```

### 2. Instalar dependências

Instale as dependências PHP e JavaScript:

```bash
composer install
npm install
```

### 3. Configurar o ambiente

Copie o ficheiro `.env.example` para `.env` e configure as credenciais da sua base de dados:

```bash
cp .env.example .env
```

Edite o ficheiro `.env` com as suas informações da base de dados, como:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=jobfinder_db
DB_USERNAME=root
DB_PASSWORD=
```

Gere a chave da aplicação:

```bash
php artisan key:generate
```

### 4. Configurar a base de dados

Crie a base de dados no MySQL (ex.: `jobfinder_db`) e execute as migrações:

```bash
php artisan migrate
```

Opcionalmente, preencha a base de dados com dados fictícios:

```bash
php artisan db:seed
```

### 5. Configurar armazenamento

Crie uma ligação simbólica para tornar os ficheiros carregados acessíveis:

```bash
php artisan storage:link
```

### 6. Compilar os assets

Compile os ficheiros JavaScript e CSS:

```bash
npm run dev
```

### 7. Executar o projecto

Inicie o servidor local:

```bash
php artisan serve
```

Aceda em `http://localhost:8000`.

Ou, se estiver a usar Laragon, aceda simplesmente a `http://jobfinder_laravel_2025.test`.

## Utilização

-   Registe-se ou inicie sessão para gerir vagas.
-   Crie novas vagas com título, descrição e ficheiros adicionais.
-   Explore a listagem de vagas disponíveis.

## Licença

Este projecto é de código aberto e licenciado sob a [MIT License](https://opensource.org/licenses/MIT).

## Créditos

-   Baseado no projecto [laragigs](https://github.com/bradtraversy/laragigs) de Brad Traversy.
-   Desenvolvido por [smpsandro1239](https://github.com/smpsandro1239).

---
