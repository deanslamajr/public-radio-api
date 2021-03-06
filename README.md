# public-radio-api

[![Build Status](https://travis-ci.org/csampson/public-radio-api.svg?branch=task%2Ftravis-ci-integration)](https://travis-ci.org/csampson/public-radio-api)
[![Coverage Status](https://coveralls.io/repos/github/csampson/public-radio-api/badge.svg?branch=task%2Fcode-coverage-report)](https://coveralls.io/github/csampson/public-radio-api?branch=task%2Fcode-coverage-report)
[![bitHound Overall Score](https://www.bithound.io/github/csampson/public-radio-api/badges/score.svg)](https://www.bithound.io/github/csampson/public-radio-api)
[![bitHound Dependencies](https://www.bithound.io/github/csampson/public-radio-api/badges/dependencies.svg)](https://www.bithound.io/github/csampson/public-radio-api/master/dependencies/npm)
[![bitHound Dev Dependencies](https://www.bithound.io/github/csampson/public-radio-api/badges/devDependencies.svg)](https://www.bithound.io/github/csampson/public-radio-api/master/dependencies/npm)
[![bitHound Code](https://www.bithound.io/github/csampson/public-radio-api/badges/code.svg)](https://www.bithound.io/github/csampson/public-radio-api)

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/a66c9fc83d5c8395bd22#?env%5Bproduction%5D=W3sidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlLCJrZXkiOiJwYmlfZW5kcG9pbnQiLCJ2YWx1ZSI6Imh0dHA6Ly9wdWJsaWMtcmFkaW8tYXBpLmhlcm9rdWFwcC5jb20ifV0=)

This a REST api for querying information about [NPR](http://npr.org) member stations. It features filtering, geolocation searching, pagination, and sorting.

## Requirements

- RethinkDB
- Node.js 6.x
- npm 3.x

## Installing

Run `npm install` to grab the project dependencies.   
Run `npm run db:migrate` to execute database migrations (this will handle populating your database with station records).

## Running

Start RethinkDB on its default port.   
Run `npm start` to spin up a local development server.

## Testing

Run `npm test` to run the unit tests.
