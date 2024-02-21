
# Angular CI/CD Project
_Deployed files are on firebase's web server:  https://deploy-17f14.web.app/_
## Overview

This project is a simple Angular application with a CI/CD pipeline set up using Drone. The purpose of this application is to demonstrate a streamlined development and deployment process.

## Project Features

- Angular application with basic features.
- CI/CD pipeline using Drone for automated builds and deployments.
- Easy setup and integration with common development tools.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/theend7/drone_deploy_test.git`
2. Navigate to the project directory: `cd drone_deploy`
3. Install dependencies: `npm install`
4. Start the development server: `npm run app`

## Install Dependencies

Make sure you have Node.js and npm installed on your machine. You can download them from [https://nodejs.org/](https://nodejs.org/).

## Project Description

This is a simple Angular application showcasing the integration of a CI/CD pipeline using Drone. The application provides a foundation for further development and customization. The CI/CD pipeline is configured to build the Angular application and deploy the build artifacts.

## CI/CD Pipeline

The CI/CD pipeline is configured in the `.drone.yml` file. It includes the following stages:

1. **Build Stage:** Triggered on every commit, it builds the Angular application.
2. **Deploy Stage:** Deploys the built artifacts to the specified environment.

## Notes

- This project uses Angular for the front-end.
- CI/CD pipeline is set up using Drone, make sure to configure the necessary environment variables in your Drone settings.
- Customize the application as per your requirements.

