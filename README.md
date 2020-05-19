# Financial platform
#### Description
Platform for execution of basic financial operations
## Technologies
* OpenJDK 12
* Gradle 6.4.1
* Spring Boot 2.2.5.RELEASE
* Logback & SLF4J
* Docker & DockerCompose
* Travis CI

## Structure
* finplat-ui - front end up
* finplat-api - backend REST API
## Prequisites
* Account in the github and travis CI
* Docker
* Docker compose
## How to start
### Start locally
Execute in the root of the project:
```
docker-compose -f docker-compose-dev.yml up -d --build
```
