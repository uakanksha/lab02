# CI/CD Pipeline with GitHub Actions and AWS

## Overview
This project sets up a CI/CD pipeline using GitHub Actions to deploy a web application on AWS EC2. It leverages AWS services like CodeDeploy, Auto Scaling, and CloudFormation.

## Prerequisites
- AWS account with necessary permissions
- GitHub account
- Git installed
- Docker installed

## Setup Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/aws-samples/aws-codedeploy-github-actions-deployment.git
   ```
2. **Create a GitHub Repository** and push the cloned project.
3. **Deploy CloudFormation Template** to provision AWS resources.
4. **Configure GitHub Secrets** for authentication.
5. **Trigger GitHub Actions Workflow** to build and deploy the application.

## Deployment Workflow
1. Developer pushes changes to GitHub.
2. GitHub Actions builds the application.
3. Artifacts are uploaded to Amazon S3.
4. CodeDeploy deploys the application to EC2 instances.
5. Auto Scaling ensures availability.

## Cleanup
- Delete the CloudFormation stack.
- Remove GitHub secrets.
- Empty the S3 bucket.

For detailed steps, refer to the uploaded document.

