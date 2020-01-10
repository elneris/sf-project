# Symfony 5 Project

Personal project from scratch in php 7.3 & Symfony 5
This project use SymfonyCloud for the deploiement in prod

## Requirements

  - PHP 7.3
  - Git
  - Composer
  - Docker & Docker-compose
  - Symfony CLI
  
## Init the project

  - Clone the project
  - composer install
  - docker-compose up -d
  
## Access to the local database
  
  - docker exec -it guestbook_database_1 psql -U main -W main
 