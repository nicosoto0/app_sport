# Project App Sport

This is the project of the frontend Apps Sport develop by Nicolás Soto, for the team of him self and Gonzalo Valdivia and Javier Concha

The Template that was use to start the development was built with [koa](http://koajs.com/) for IIC2513 - Tecnologías y Aplicaciones Web, Pontificia Universidad Católica de Chile.

## Prerequisites:
* [PostgreSQL](https://github.com/IIC2513-2017-2/syllabus/wiki/Getting-Started#postgresql)
  * you will need a database with name and user/password as configured in `src/config/database.js`
* [Node.js v10.8.0](https://github.com/IIC2513-2017-2/syllabus/wiki/Node.js) or above
* [Yarn](https://yarnpkg.com)

## Project Setup

* Clone repository
* Install dependencies:
  * `yarn install`

## Database Setup (development)

* To be completed

### Install postgresql
* On Mac OS X using Homebrew: `brew install postgresql`
  * Start service: check [LaunchRocket](https://github.com/jimbojsb/launchrocket) or [lunchy](https://www.moncefbelyamani.com/how-to-install-postgresql-on-a-mac-with-homebrew-and-lunchy/) for postgresql service management
* [Other platforms](https://www.postgresql.org/download/)
* [More details](https://github.com/IIC2513-2017-2/syllabus/wiki/Getting-Started#postgresql)

### Create development database

```sh
createdb best_dev
```

### Run migrations
```sh
./node_modules/.bin/sequelize db:migrate
```

## Run the app!

```sh
yarn start
```

or directly

```sh
node index.js
```

or, if you want automatic restart after any change in your files

```sh
./node_modules/.bin/nodemon
```

Now go to http://localhost:3000 and start browsing :)
