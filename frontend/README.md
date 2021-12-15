# Static site

This sample creates the infrastructure for a static site, which uses an S3 bucket for storing the content.  The site contents (located in the 'app/build' sub-directory) are deployed to the bucket.

## Local Development
```shell
$ cd app
$ npm run start
```

## Production Build
```shell
$ npm run build
```

## Prep
Change 'bucketName' to unique name in index.ts

## Deploy

```shell
$ npm install -g aws-cdk
$ npm install
$ npm run build
$ cdk deploy
```
