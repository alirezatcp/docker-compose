# Django Project with Docker

A Dockerized Django project with PostgreSQL, RabbitMQ, Celery, and Nginx.

## Features

- Django application served with Gunicorn
- PostgreSQL database with persistent storage
- RabbitMQ message broker for Celery tasks
- Celery worker for asynchronous tasks
- Nginx reverse proxy
- Docker Compose orchestration


## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/alirezatcp/docker-compose.git
   cd docker-compose
   ```
2. **Build and start containers**
   ```bash
   docker-compose up -d
   ```
2. **Access the application**
   - Web interface: http://localhost
