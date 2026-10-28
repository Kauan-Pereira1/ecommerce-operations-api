# E-commerce Operations API

[English](README.md) | **Português (Brasil)**

Projeto de API REST para gerenciamento de operações
de e-commerce, incluindo produtos, estoque, pedidos,
devoluções, reembolsos e processos operacionais.

Desenvolvido com Python, Django REST Framework
e PostgreSQL.

> Projeto em desenvolvimento. As funcionalidades
> do roadmap ainda não foram implementadas.

## Tecnologias

- Python 3.12
- Django 5.2
- Django REST Framework
- PostgreSQL 17
- psycopg 3
- drf-spectacular

## Funcionalidades implementadas

- Configuração do Django REST Framework
- Integração com PostgreSQL
- Endpoint de verificação da API

## Como executar o projeto

### 1. Clonar o repositório

git clone https://github.com/Kauan-Pereira1/ecommerce-operations-api.git

cd ecommerce-operations-api

### 2. Criar o ambiente virtual

py -m venv .venv

.\.venv\Scripts\Activate.ps1

### 3. Instalar as dependências

python -m pip install -r requirements.txt

### 4. Configurar o PostgreSQL

Crie um banco PostgreSQL e um usuário para a aplicação.

Copie `.env.example` para `.env` e configure
suas credenciais.

### 5. Executar as migrations

python manage.py migrate

### 6. Iniciar o servidor

python manage.py runserver

## Endpoints disponíveis

| Método | Endpoint | Descrição |
|--------|----------|-----------|
| GET | /api/health/ | Verificação da API |

## Próximas funcionalidades

- Autenticação e permissões
- Gerenciamento de produtos
- Controle de estoque
- Processamento de pedidos
- Devoluções e reembolsos
- Relatórios operacionais
- Testes automatizados
- Suporte a Docker

## Autor

[Kauan Pereira](https://github.com/Kauan-Pereira1)