# Static site

This sample creates the infrastructure for API, which uses ECS on Fargate.
cd 

## Local Development
Start Docker on your local computer, and launch container with the following commands:

```shell
$ docker-compose up --build
```

## Deploy

```shell
$ npm install -g aws-cdk
$ npm install
$ npm run build
$ cdk deploy
```
