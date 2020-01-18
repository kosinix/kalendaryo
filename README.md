
# kalendaryo

Returns a calendar month view as a matrix of strings in this format "YYYY-MM-DD" eg. 2020-01-30.

## Install

#### Choose 1 of 2 options:

Install latest from GitHub:

    npm install github:kosinix/kalendaryo

Tied to a specific version/release from GitHub:

    npm install github:kosinix/kalendaryo#1.0.0
    
## Quickstart

    const moment = require('moment')
    const kalendaryo = require('kalendaryo');

    const momentNow = moment()
    const weekStart = 0 // What weekday the calendar starts. 0 - Sunday (default), 1 - Mon, 2 - Tue, 3, 4, 5, 6.

    console.log(kalendaryo.getMatrix(momentNow, 0))


## Tests

Uses `jest`. Install jest globally

    npm install jest --global

    jest ./tests/index.test.js


## Dev Notes

Increment version run npm version x.x.x

    npm version 1.0.0

Publish to NPM (not published at the moment)

    npm publish