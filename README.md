# basic-pern-repo
Express Node Postgres REST Api

## Author
[Srikant Kumar Kalaputapu](https://github.com/KSriki)

## Sources
Tutorial Followed: 
[REST API](https://www.alibabacloud.com/blog/building-a-restful-api-with-express-postgresql-and-node-using-es6_594137)

## Tech/Frameworks used

- [Environment Variables](https://www.npmjs.com/package/dotenv)
- [Express.js](https://expressjs.com/)
- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/en/)
- [REST API](https://restfulapi.net/)
- [PostgreSQL](https://www.postgresql.org/)
- [Sequelize/Sequelize CLI](https://sequelize.org/)

## Dependencies

- [Babel 7](https://babeljs.io/)
    - babel-preset-env, babel-core, babel-cli
    - used to transpile code for ES6 to ES5 to work on any browser
    - .babelrc sets env
- [Express.js](https://expressjs.com/)
    - basic web framework for Node.js
- [body-parser](https://www.npmjs.com/package/body-parser)
    - body-parser
    - Node.js middleware to parse request bodies - useful for HTTP POST
    - used to be packaged with Express, now seperate
    - data in req.body
- [morgan](https://www.npmjs.com/package/morgan)
    - morgan
    - logger middleware
- [nodemon](https://nodemon.io/)
    - nodemon
    - automatic refreshing of server based on real-time changes
- [Sequelize/Sequelize CLI](https://sequelize.org/)
    - sequelize, sequelize-cli: promise-based Node.js ORM (map code objects to database models)
    - pg: making the database connection
    - pg-hstore: for serializing and deserializing JSON into the Postgres hstore key/value pair format
    - .sequelizerc settings file to determine bootstrapped folder locations

## Sequelize-cli

1. Setup .sequelizerc file
2. run sequelize init