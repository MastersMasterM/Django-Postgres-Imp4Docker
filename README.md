Dockerized Django and Postgres Application Base

This is a Dockerized web application that uses Django as its backend framework and Postgres as its database.
Prerequisites

Before you can run this application, you must have the following software installed on your system:

    Docker
    Docker Compose

Installation

To install and run the application, follow these steps:

1. Clone the repository:

        git clone https://github.com/MastersMasterM/Django-Postgres-Imp4Docker.git

2. Change into the project directory:

        cd your-repo

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

Usage

You can use these file as the base of your projects

If you would like to contribute to this project, please follow these steps:

    Fork the repository.
    Create a new branch for your changes.
    Make your changes and commit them.
    Push your changes to your branch on your forked repository.
    Submit a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.
