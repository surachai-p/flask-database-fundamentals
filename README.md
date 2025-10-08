# Flask Database Fundamentals - Lab 02

Modern Flask 3.x application with PostgreSQL integration, demonstrating best practices for database management and CI/CD readiness.

## 🚀 Features

- ✅ Flask 3.x with modern Python features
- ✅ Type hints and type safety throughout
- ✅ PostgreSQL with SQLAlchemy 3.x ORM
- ✅ Docker Compose for database management
- ✅ Database migrations with Alembic
- ✅ RESTful API endpoints
- ✅ Modern HTML templates with Bootstrap 5
- ✅ Comprehensive testing suite
- ✅ CI/CD ready structure

## 📦 Tech Stack

- **Flask 3.1.2** - Web framework
- **SQLAlchemy 3.1.1** - ORM
- **PostgreSQL 16** - Database (via Docker)
- **Pydantic 2.9** - Settings validation
- **Bootstrap 5.3** - Frontend framework
- **Pytest 8.3** - Testing framework
- **Docker Compose** - Container orchestration

## 📋 Prerequisites

- Python 3.9+
- Docker Desktop
- Git

## 🏗 Project Structure
flask-database-fundamentals/
├── app/
│   ├── init.py           # Application factory
│   ├── models/               # Database models
│   │   ├── init.py
│   │   ├── base.py          # Base model with common fields
│   │   ├── user.py          # User model
│   │   ├── category.py      # Category model
│   │   └── post.py          # Post model
│   ├── views/               # Route handlers
│   │   ├── init.py
│   │   ├── main.py         # Web views
│   │   └── api.py          # API endpoints
│   ├── templates/          # Jinja2 templates
│   │   ├── base.html
│   │   ├── main/
│   │   └── errors/
│   └── static/            # Static files
│       ├── css/
│       └── js/
├── config/
│   └── settings.py        # Pydantic settings
├── tests/
│   ├── init.py
│   ├── unit/             # Unit tests
│   └── integration/      # Integration tests
├── migrations/           # Alembic migrations
├── docker/
│   └── docker-compose.yml
├── .env.example         # Environment template
├── .env                 # Environment variables (not in git)
├── .gitignore
├── requirements.txt     # Python dependencies
├── requirements-dev.txt # Development dependencies
├── run.py              # Application entry point
└── README.md