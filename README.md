# Building-a-Serverless-URL-Shortner-with-AWS-Lambda-API-Gateway-DynamoDB-Docker
- No infrastructure overhead - Auto-scalable &amp; fault-tolerant - Cost-efficient - Easy deployment with Docker - Serverless simplifies infrastructure

# AWS Serverless URL Shortener

This is a simple URL shortening service built using AWS Lambda, API Gateway, DynamoDB.

## Features
- Shorten long URLs into shorter, shareable links
- Store shortened URLs in DynamoDB
- Retrieve and redirect using API Gateway and Lambda

## Architecture
- **Lambda**: Handles URL shortening and retrieval.
- **DynamoDB**: Stores mapping between short and long URLs.
- **API Gateway**: Exposes endpoints for shortening and redirecting URLs.

## Prerequisites
- AWS CLI configured with necessary permissions
- Terraform installed
- IAM permissions to manage Lambda, API Gateway, DynamoDB, and S3

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone https://github.com/patilanu/Building-a-Serverless-URL-Shortner-with-AWS-Lambda-API-Gateway-DynamoDB-Docker.git
   ```

2. **Deploy Lambda function:**
   ```sh
   lambda_function1.py
   lambda_function2.py
   aws lambda update-function-code --function-name url_shortener
   ```

4. **Test API Gateway Endpoint:**
   ```sh
   curl -X POST https://your-api-gateway-url -d '{"long_url": "https://example.com"}'
   ```

