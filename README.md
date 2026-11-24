# Containerised Flask Application with Redis

## Project Overview

A Python Flask web application integrated with Redis, 
containerised using Docker and orchestrated using 
Docker Compose.

This project demonstrates containerisation, 
multi-container applications and Docker networking.

## Technologies Used

- Python
- Flask
- Redis
- Docker
- Docker Compose
- Linux
- Git and GitHub

## Architecture

The application consists of two containers:

- Flask: Handles HTTP requests and application logic.
- Redis: Provides a backend data store.

Both containers communicate through a Docker network 
managed by Docker Compose.

## How to Run
git clone https://github.com/Mohammad3650/flask-redis-docker-compose.git
cd flask-redis-docker-compose

### Prerequisites

- Docker
- Docker Compose

### Build and start the application

```bash
docker compose up --build
```

### Stop the application

```bash
docker compose down
```

## Learning Outcomes

- Building Docker images using Dockerfiles.
- Managing multiple containers using Docker Compose.
- Configuring inter-container communication.
- Understanding Docker networking.
- Using Git and GitHub for version control.

## Future Improvements

- Deploy the application to AWS.
- Implement a CI/CD pipeline using GitHub Actions.
- Provision infrastructure using Terraform.
