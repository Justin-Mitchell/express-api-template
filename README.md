# Express API template
[![Build Status](https://travis-ci.com/Justin-Mitchell/express-api-template.svg?branch=development)](https://travis-ci.com/Justin-Mitchell/express-api-template)
[![Coverage Status](https://coveralls.io/repos/github/Justin-Mitchell/express-api-template/badge.svg?branch=development&t=89ECjd)](https://coveralls.io/github/Justin-Mitchell/express-api-template?branch=development)
[![Maintainability](https://api.codeclimate.com/v1/badges/1b6759ab22cdafc43f37/maintainability)](https://codeclimate.com/github/Justin-Mitchell/express-api-template/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/1b6759ab22cdafc43f37/test_coverage)](https://codeclimate.com/github/Justin-Mitchell/express-api-template/test_coverage)
[![Build status](https://ci.appveyor.com/api/projects/status/18n1nj1n219i293l/branch/development?svg=true)](https://ci.appveyor.com/project/Justin-Mitchell/express-api-template/branch/development)
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