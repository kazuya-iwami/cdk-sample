# Static site

This example creates the infrastructure for a static site, which uses an S3 bucket for storing the content.  The site contents (located in the 'app/build' sub-directory) are deployed to the bucket.

The site redirects from HTTP to HTTPS, using a CloudFront distribution, Route53 alias record, and ACM certificate.

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
