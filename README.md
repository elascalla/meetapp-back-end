<h1 align="center">
    <img alt="Go Stack logo" src="https://github.com/elascalla/meetapp-back-end/blob/master/assets/logo-gostack.png" />
    <br>
    Desafio MeetApp
</h1>

<h4 align="center">
  A challenge for [RocketSeat GoStack Bootcamp](https://rocketseat.com.br/bootcamp) Certificate
</h4>
<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/elascalla/meetapp-back-end.svg">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/elascalla/meetapp-back-end.svg">

  <a href="https://www.codacy.com/app/elascalla/meetapp-back-end?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=elascalla/meetapp-back-end&amp;utm_campaign=Badge_Grade">
  <img src="https://api.codacy.com/project/badge/Grade/b87b27f130cf4af98e52082d21e70426"/></a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/elascalla/meetapp-back-end.svg">
  <a href="https://github.com/elascalla/meetapp-back-end/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/elascalla/meetapp-back-end.svg">
  </a>

  <a href="https://github.com/elascalla/meetapp-back-end/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/elascalla/meetapp-back-end.svg">
  </a>

  <img alt="GitHub" src="https://img.shields.io/github/license/elascalla/meetapp-back-end.svg">
</p>

<p align="center">
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-use">How To Use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## :rocket: Technologies

This project was developed to get the [RocketSeat GoStack Bootcamp](https://rocketseat.com.br/bootcamp) certificate with the following technologies:

### BACK-END
-   [Node.js][nodejs]
-   [Express](https://expressjs.com/)
-   [nodemon](https://nodemon.io/)
-   [Sucrase](https://github.com/alangpierce/sucrase)
-   [Docker](https://www.docker.com/docker-community)
-   [Sequelize](http://docs.sequelizejs.com/)
-   [PostgreSQL](https://www.postgresql.org/)
-   [node-postgres](https://www.npmjs.com/package/pg)
-   [Redis](https://redis.io/)
-   [MongoDB](https://www.mongodb.com/)
-   [Mongoose](https://mongoosejs.com/)
-   [JWT](https://jwt.io/)
-   [Multer](https://github.com/expressjs/multer)
-   [Bcrypt](https://www.npmjs.com/package/bcrypt)
-   [Youch](https://www.npmjs.com/package/youch)
-   [Yup](https://www.npmjs.com/package/yup)
-   [Bee Queue](https://www.npmjs.com/package/bcrypt)
-   [Nodemailer](https://nodemailer.com/about/)
-   [date-fns](https://date-fns.org/)
-   [Sentry](https://sentry.io/)
-   [DotEnv](https://www.npmjs.com/package/dotenv)
-   [VS Code][vc] with [ESLint][vceslint]

## :information_source: How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js v10.15][nodejs] or higher + [Yarn v1.16][yarn] or higher installed on your computer and the [First React Project](https://github.com/elascalla/meetapp-back-end). From your command line:

### Install API

```bash
# Clone this repository
$ git clone https://github.com/elascalla/meetapp-back-end

# Go into the repository
$ cd meetapp-back-end

# Install dependencies
$ yarn

# Created Postgree Docker container
$ docker run --name postgremeetapp -e POSTGRES_PASSWORD=docker -e POSTGRES_DB=database_meetapp -p 5433:5432 -d postgres

# Created Mongo Docker container
$ docker run --name mongomeetapp -p 27017:27017 -d -t mongo

# Created Redis Docker container
$ docker run --name redismeetapp -p 6379:6379 -d -t redis:alpine

# Create Database in Postgres

# Run Migrates
$ yarn migrate

# Run the API
$ yarn dev
```

## :memo: License

This project is under the MIT license. See the [LICENSE](https://github.com/elascalla/meetapp-back-end/blob/master/LICENSE) for more information.

---

Made with ♥ by Erick Lascalla :wave: [Get in touch!](https://www.linkedin.com/in/erick-gomes/)

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
