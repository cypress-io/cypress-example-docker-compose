# cypress-example-docker-compose

> Example running Cypress tests against Apache server via docker-compose

[![CircleCI](https://circleci.com/gh/cypress-io/cypress-example-docker-compose.svg?style=svg)](https://circleci.com/gh/cypress-io/cypress-example-docker-compose) [![renovate-app badge][renovate-badge]][renovate-app]

See [docker-compose.yml](docker-compose.yml) and [circle.yml](circle.yml) files.
First [container runs Apache](webapp/Dockerfile), second container has [Cypress tests](e2e/Dockerfile).

**note:** for performance on CircleCI, I have turned [docker layer caching](https://circleci.com/docs/2.0/docker-layer-caching/) to avoid rebuilding Docker images unless they have changed.

## Use

1. build the containers with `npm run build`
2. start the web application and run Cypress tests with `npm run up`

## More info

- [Cypress Docker docs](https://on.cypress.io/docker)
- [Cypress continuous integration docs](https://on.cypress.io/ci)
- [docker-compose networking](https://docs.docker.com/compose/networking/)
- Read the excellent [End-to-End Testing Web Apps: The Painless Way](https://mtlynch.io/painless-web-app-testing/)

[renovate-badge]: https://img.shields.io/badge/renovate-app-blue.svg
[renovate-app]: https://renovateapp.com/
