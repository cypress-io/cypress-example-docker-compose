# circle-multi-image

> Apache + Cypress tests on CircleCI using docker-compose

[![CircleCI](https://circleci.com/gh/bahmutov/circle-multi-image.svg?style=svg)](https://circleci.com/gh/bahmutov/circle-multi-image)

See [docker-compose.yml](docker-compose.yml) and [circle.yml](circle.yml) files.
First [container runs Apache](webapp/Dockerfile), second container has [Cypress tests](e2e/Dockerfile).
