# Mentor do Bem - Backend

This project aims to promote the exchange of knowledge about technologies. This is the backend repository.

## Table of Contents
- [Mentor do Bem - Backend](#mentor-do-bem---backend)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [How it works](#how-it-works)
  - [Clone](#clone)
  - [Deploy](#deploy)
  - [Contributing](#contributing)
  - [License](#license)


## Getting Started
For creating this project, first of all, you need installing node:

```
npm install node
```
Then, use create-react-app, an officially supported way to create single-page React applications. 

```
npm init create-react-app mentor-do-bem-server
cd mentor-do-bem-server
npm start
```
You need also install:

Typescript adds typing and other resources to Javascript.
```
npm install typescript
```

ts-node-dev restarts target node process when any of required files changes
```
npm install ts-node-dev --save-dev
```
Express provides small, robust tooling for HTTP servers, making it a great solution for single-page applications, web sites, hybrids, or public HTTP APIs. 
```
npm install express
npm install @types/express -D
```

Knex is a SQL query builder.
```
npm install knex
npm install @types/knex -D
```

Postgres is an open-source database
```
npm install pg
```

Cors is a node.js package for providing a Connect/Express middleware that can be used to enable CORS with various options.
```
npm install cors
npm install @types/cors -D
```

Axios is promise based HTTP client for the browser and node.js.
```
npm install axios
```
dotenv is a zero-dependency module that loads environment variables from a .env file into process.env.
```
npm install dotenv
```

## How it works

In this application create 5 migrations with knex for creating: a login, users, classes, class schedule, and connections. 
In addition, create the routes of application with express: for login, for a new account, for register of the user, and for the search for a connection.

## Clone
Clone this repository to your local machine using 

https://github.com/GCMoura/mentor-do-bem-server.git.

## Deploy
This application was deployed using [Heroku](https://heroku.com/).

## Contributing
If you would like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.