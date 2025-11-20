# Serverless REST API on AWS

## Table of Contents
- [Project Overview](#project-overview)
- [Architecture Diagram](#architecture-diagram)
- [Deployment Process](#deployment-process)
- [Key Features](#key-features)
- [Troubleshooting](#troubleshooting)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact Information](#contact-information)

## Project Overview
This project demonstrates the deployment of a serverless REST API using AWS Lambda and API Gateway. It includes automated deployments, proper CORS handling, and monitoring solutions.

## Architecture Diagram
![Architecture Diagram](ServerlessRESTAPIonAWS.png)

## Deployment Process
1. **AWS Lambda Functions**: Lambda functions are triggered by API Gateway and handle incoming requests.
2. **API Gateway**: REST endpoints are configured with proper CORS headers and HTTP response handling.
3. **Automated Deployments**: API Gateway stages are used for automated deployments.
4. **Monitoring and Logging**: Solutions for monitoring and logging are implemented to ensure smooth operation.

## Key Features
- Serverless architecture using AWS Lambda and API Gateway.
- Automated deployments with API Gateway stages.
- Proper CORS headers and HTTP response handling.
- Monitoring and logging solutions.

## Troubleshooting
- **Authentication Issues**: Resolved by ensuring correct IAM roles and permissions.
- **Module Syntax Errors**: Fixed by validating and testing code before deployment.
- **Deployment Errors**: Troubleshooting using CloudWatch logs and error messages.

## Usage
To use this API, you can send HTTP requests to the live endpoint. Here’s an example using `curl`:

```bash
curl -X GET https://your-api-endpoint.com/resource
