# Shop Angular Cloudfront

Angular version: ~12.

## The purpose

The repository was created to have an Angular version of e-shop for EPAM NodeJS AWS course. At the same time we strive to make this repository follows best practices so it may be used as a starter for new projects with all the necessary toolings already set up.

## Get up and running

Prerequisites: NodeJS v14.20.x and higher

commands:

```
npm run build - build code
npm run start - start server locally
npm run setup - setup AWS env (S3 bucket, cloudfront)
npm run deploy - build + upload files + invalidate cloudfront cache
```

S3 Website: http://my-shop-kf.s3-website-us-east-1.amazonaws.com
CloudFront URL: https://d3o4sef1lkpe4n.cloudfront.net
