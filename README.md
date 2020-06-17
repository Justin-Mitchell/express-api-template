# Express API template
[![Build Status](https://travis-ci.com/Justin-Mitchell/express-api-template.svg?xtoken=ycsC4nJsx3mRkpCkjceX&branch=development)](https://travis-ci.com/Justin-Mitchell/express-api-template)

[![Coverage Status](https://coveralls.io/repos/github/Justin-Mitchell/express-api-template/badge.svg?branch=development&t=89ECjd)](https://coveralls.io/github/Justin-Mitchell/express-api-template?branch=development)
# initialize the project folder as a git repository
git init

# install the express generator globally
yarn global add express-generator

# install express
yarn add express

# generate the express project in the current folder
express -f

# install babel scripts
yarn add @babel/cli @babel/core @babel/plugin-transform-runtime @babel/preset-env @babel/register @babel/runtime @babel/node --dev

# install nodemon
yarn add nodemon --dev

# install elsint and prettier
yarn add eslint eslint-config-airbnb-base eslint-plugin-import prettier --dev

# install dotenv
yarn add dotenv

# install dependencies
yarn add mocha chai nyc sinon-chai supertest coveralls --dev