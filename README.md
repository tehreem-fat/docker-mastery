# Docker-Mastery

A Dockerized static website served with Nginx and hosted in AWS ECR.

## Features
- Static website using Nginx
- Docker image pushed to AWS ECR
- Can be run locally or in cloud

## Run Locally
```bash
docker build -t docker-mastery:latest .
docker run -d -p 8080:80 docker-mastery:latest

## Screenshot

![Website Screenshot](screenshots/screenshot1.png)
