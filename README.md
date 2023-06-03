Dockerized Django and Postgres Starterkit

This is a starter kit for a web application that uses Django and django-rest as its backend frameworks and Postgres as its database, Dockerized as different services, and also includes a solution for the database race problem.

Before you can run this application, you must have the following software installed on your system:

    Docker
    Docker Compose

Installation


To install and run the application, follow these steps:

0. Update the requirements versions in requirements.txt, you can find the latest versions from PyPI.org
[requirements.txt](https://raw.githubusercontent.com/MastersMasterM/Django-Postgres-Imp4Docker/main/requirements.txt)

1. Clone the repository:

        git clone https://github.com/MastersMasterM/Django-Postgres-Imp4Docker.git

2. Change into the project directory:

        cd Django-Postgres-Imp4Docker

3. Build the Docker containers:

        docker-compose build
        
4. Start the containers:

        docker-compose up

Access the application in your web browser at http://localhost:8000.

Configuration

The application uses environment variables to configure various settings. You can set these variables in a .env file in the project directory. Here are the available variables:

    POSTGRES_USER: the username for the Postgres user (default: postgres)
    POSTGRES_PASSWORD: the password for the Postgres user (default: postgres)
    POSTGRES_DB: the name of the Postgres database (default: postgres)
    DATABASE_HOST: the hostname for the database (default: db)
    DATABASE_PORT: the port number for the database (default: 5432)
    
 Add DOCKER_USER and PASS as the secrets of your repository to automate testing.

Usage

You can use these file as the base of your projects


License

This project is licensed under the MIT License. See the LICENSE file for details.
