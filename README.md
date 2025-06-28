# Static Website on AWS S3 with GitHub Actions

This project demonstrates how to deploy a static website to an S3 bucket using a GitHub Actions CI/CD pipeline.

## Features

- AWS S3 static hosting
- CI/CD via GitHub Actions
- Public website URL

## Setup Instructions

1. Create an S3 bucket with static website hosting enabled.
2. Create an IAM user and store credentials in GitHub Secrets:
   - `AWS_ACCESS_KEY_ID`
   - `AWS_SECRET_ACCESS_KEY`
3. Set your S3 bucket name and region in `.github/workflows/deploy.yml`.

## License

MIT
