# cypress-example-docker-compose

> Example running Cypress tests against Apache server via docker-compose

[![CircleCI](https://circleci.com/gh/bahmutov/circle-multi-image.svg?style=svg)](https://circleci.com/gh/bahmutov/circle-multi-image)

See [docker-compose.yml](docker-compose.yml) and [circle.yml](circle.yml) files.
First [container runs Apache](webapp/Dockerfile), second container has [Cypress tests](e2e/Dockerfile).

## More info

- [Cypress Docker docs](https://on.cypress.io/docker)
- [Cypress continuous integration docs](https://on.cypress.io/ci)
- [docker-compose networking](https://docs.docker.com/compose/networking/)
