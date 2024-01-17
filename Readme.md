# Django MongoDB Dockerized Project

This is a simple Dockerized project using Django as the web framework, MongoDB as the database, and Mongo Express for database management.

## Prerequisites

- Docker: Make sure you have Docker installed on your machine. You can download it [here](https://www.docker.com/get-started).

## Getting Started

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/huseynovfuad/django_mongo
    cd django_mongo
    ```

2. **Build and Run Docker Containers:**

    ```bash
    docker-compose up --build
    ```

    This command will download the necessary images, build the Docker containers, and start the services.

3. **Access the Django App:**

    Open your web browser and go to [http://localhost:8000](http://localhost:8000) to access the Django application.

4. **Access Mongo Express:**

    Open your web browser and go to [http://localhost:8081](http://localhost:8081) to access the Mongo Express interface for managing MongoDB.

## Project Structure

- **app**: Django application folder.
- **db**: MongoDB data folder.
- **docker-compose.yml**: Docker Compose configuration file.
- **Dockerfile**: Dockerfile for the Django app.
- **requirements.txt**: Python dependencies for the Django app.
- **.env**: Environment variables file.
