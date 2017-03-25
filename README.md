Final Project
===

# Requirements

- Node
- [MongoDB](https://www.mongodb.com/) (Using [Mongoose for ORM](http://mongoosejs.com/))

To install all the dependencies run

    npm install

or (if you have [Yarn](https://yarnpkg.com) installed)

    yarn install


This app uses `create-react-app` and `express` with `mongoose` as a MongoDB ORM.

# Commands

Running the app

    npm run start:all

The server can then be accessed from [http://localhost:3000/](http://localhost:3000/)    

Running the tests

    npm run test    

Tests are run using [Jest](https://facebook.github.io/jest/)

# Structure

The base structure follows create-react-app. The express server can be found in `src/server/server.js`

# Linting

Enabling code style checking in your IDE will help you to prevent errors when running the app.

## Atom
https://atom.io/packages/linter-eslint

## Sublime text
Sublime Linter 3
