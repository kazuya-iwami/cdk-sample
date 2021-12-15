# Static site
This sample creates the infrastructure for a static site, which uses an S3 bucket for storing the content. 

## Prep
Change 'bucketName' to unique name in index.ts
```shell
$ npm install -g aws-cdk
$ npm install
```

## Local Development
```shell
$ cd app
$ npm start
```

## Deploy
React Production Build 
```shell
$ (cd app; npm run build)
```

The site contents (located in the 'app/build' sub-directory) are deployed to the S3 bucket.
```shell
$ npm run build
$ cdk deploy
```
