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
