# Static site

This sample creates the infrastructure for API, which uses ECS on Fargate.
cd 

## Prep
```shell
$ npm install -g aws-cdk
$ npm install
```

## Local Development
Start docker (Docker Desktop for Mac/Win) on your local computer, and launch container with the following commands:

```shell
$ docker-compose up --build
```

Test it.
```shell
$ curl http://localhost:8080
```

## Deploy
```shell
$ npm run build
$ cdk deploy
```
