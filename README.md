# newwebapp
# Hello-World Web Application

This repository contains a simple hello-world web application. The project is set up with a CI/CD pipeline using GitHub Actions for automatic deployment to AWS. Additionally, monitoring is implemented using Grafana, and email triggers are set up for monitoring alerts.

## CI/CD Pipeline Setup

The CI/CD pipeline is configured using GitHub Actions. Every push to the main branch triggers the pipeline, which performs the following steps:

1. **Build:** Build the hello-world web application.

2. **Test:** Run automated tests to ensure the application's correctness.

3. **Deploy:** Deploy the application to AWS.

## Auto-Deployment to AWS

GitHub Actions is configured to automatically deploy the application to AWS whenever changes are pushed to the main branch. The deployment process includes provisioning resources, deploying the application, and ensuring high availability.

## Monitoring with Grafana

Grafana is used for monitoring the deployed application. Key metrics such as response times, error rates, and resource utilization are tracked. Additionally, Grafana alerts are configured to send email notifications in case of anomalies or issues.

## Quick Start

To run the hello-world web application locally:

```bash
# Clone the repository
git clone https://github.com/your-username/hello-world-webapp.git

# Navigate to the project directory
cd hello-world-webapp

# Run the application
./run.sh
