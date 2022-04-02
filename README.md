# bearer-auth

HTTP server built to test basic and bearer.

## Deployed Links

- [Heroku Link](https://bearer-auth-bc.herokuapp.com/)

## UML

- ![UML](/bearer-auth.png)

## Installation

- Clone from this repo `git clone https://github.com/bradyjcamp/auth-api.git`
- cd into api-server
- `npm install`
  - base-64
  - bcrypt
  - cors
  - dotenv
  - express
  - nodemon
  - jest
  - jsonwebtoken
  - morgan
  - pg
  - supertest
  - sequelize
  - sqlite3

## Usage

Once installed, run `npm start`

## Contributors / Authors

- Brady Camp
- JS 401 d46 class.

## Features / Routes

- POST `(/signup)`
- POST `(/signin)`
- GET `(/users)`
- GET `(/secret)`

[routes](./src/auth/routes.js)

- Response
  - status 200
  - status 404, if incorrect route.
  - status 500, if request denied or failed.

- Response
  - status 200
  - status 404, if incorrect route.
  - status 500, if request denied or failed.
  