## Render

This repository contains a simple skeleton application configured to automate the deployment process using GitHub Actions and Render.com. The workflow is set up to build a Docker image, push it to Docker Hub, and automatically deploy it on Render.com.

## Prerequisites
Before getting started, ensure you have:

- Docker installed locally.
- A Docker Hub account for image storage.
- A Render.com account for deployment.

## Getting Started
1. Clone this repository.
1. Configure your Docker Hub and Render.com credentials as GitHub Secrets.
1. Customize the Dockerfile for your application's requirements.
1. Commit your changes and push to trigger the GitHub Actions workflow.
1. Monitor the Actions workflow and check Render.com for the deployed application.

## Workflow
1. Build: GitHub Actions builds a Docker image based on your Dockerfile.
1. Push: The built Docker image is pushed to Docker Hub.
1. Deploy: Render.com automatically detects the new image and deploys it based on your configuration.
