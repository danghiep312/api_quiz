## [QUIZ]

This project was built on tech stacks such as NestJS, Redis, MongoDB, PM2, and Docker,...
### Description

api-quiz repository

### Installation

```bash
$ npm install
```

### Running the app

```bash
# copy env file
cp local.env.example .env

# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Docker

```bash
$ sudo docker-compose -f docker-compose-single.yml down api
$ sudo docker-compose -f docker-compose-single.yml up --build api

$Guide CI/CD: https://docs.google.com/document/d/1JW6g4t2pCQfKQZzChsiJX8DbjDLwnS1_OQHVQb3qvlc/edit?usp=sharing
```
