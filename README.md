# E-commerce Operations API

**English** | [Português (Brasil)](README.pt-BR.md)

A REST API project for managing e-commerce operations,
including products, inventory, orders, returns,
refunds, and operational workflows.

Built with Python, Django REST Framework, and PostgreSQL.

> Project under development. Features listed in the
> roadmap are planned and not yet implemented.

## Technologies

- Python 3.12
- Django 5.2
- Django REST Framework
- PostgreSQL 17
- psycopg 3
- drf-spectacular

## Implemented Features

- Django REST Framework setup
- PostgreSQL database integration
- Health check endpoint

## Getting Started

### 1. Clone the repository

git clone https://github.com/Kauan-Pereira1/ecommerce-operations-api.git

cd ecommerce-operations-api

### 2. Create a virtual environment

py -m venv .venv

.\.venv\Scripts\Activate.ps1

### 3. Install dependencies

python -m pip install -r requirements.txt

### 4. Configure PostgreSQL

Create a PostgreSQL database and an application user.

Copy `.env.example` to `.env` and configure your credentials.

### 5. Run database migrations

python manage.py migrate

### 6. Start the development server

python manage.py runserver

## Available Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/health/ | API health check |

## Roadmap

- Authentication and permissions
- Product management
- Inventory management
- Order processing
- Returns and refunds
- Operational reports
- Automated tests
- Docker support

## Author

[Kauan Pereira](https://github.com/Kauan-Pereira1)