# Static Website on AWS S3 + CloudFront

A personal portfolio website deployed to AWS using S3 for storage and CloudFront as a CDN for fast, secure global delivery.

## Live Demo

[View Live Website](https://d3uwqyk78lbrx7.cloudfront.net)

## Architecture

## AWS Services Used

- **Amazon S3** — Stores and serves the static website files
- **Amazon CloudFront** — CDN that delivers content globally with low latency and HTTPS
- **IAM** — Manages permissions and access control

## Features

- Served over HTTPS via CloudFront
- Global content delivery via AWS edge locations
- Custom error page (404)
- Bucket policy restricting direct S3 access

## Project Structure## Deployment Steps

1. Created S3 bucket with static website hosting enabled
2. Applied bucket policy for public read access
3. Uploaded website files to S3
4. Created CloudFront distribution pointing to S3 origin
5. Configured HTTPS and HTTP to HTTPS redirect

## Author

**Joe Greenwood**  
AWS Cloud Practitioner  
[GitHub](https://github.com/jgreenwo39)

