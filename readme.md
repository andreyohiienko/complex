# Fibonacci sequence app
Multi container\
Calculate fibonacci number by redis based on input index.\
Store inputs in posgreSQL database.

## Technologies stack
- CRA
- Express
- Redis
- Postgres
- Docker
- Docker-compose
- Travis CI
- Elastic Beanstalk
- Elastic Container Service
- Virtual Private Cloud

### Managed data service providers (Recomended)
- AWS Elastic Cache (Redis)
- AWS Relational Database service (Postgres)

## Commands
- docker-compose up --build
- docker-compose down

## Tips
- At least one container should be marked as "essential": "true" 

## Issues
- Hide environment variables in 'docker-compose.yml'