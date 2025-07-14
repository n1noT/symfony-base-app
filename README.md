# Symfony base application

This project is a base application for Symfony 7.2.

It includes the following features:
- Register/Authentication
- Administration dashboard

# Installation

- Install dependencies with composer
```bash
cd ./symfony
composer install
```

- Copy the content of .env.example to .env file for docker and symfony
  
- Start the docker containers with the command:
```bash
docker-compose up -d
```

- Create the database user for database_symfony and update .env file with the credentials.


