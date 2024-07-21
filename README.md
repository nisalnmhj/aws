# Automated CI/CD Pipeline with AWS
<img src="https://github.com/nisalnmhj/aws/blob/main/environment/high-step8.1.png?raw=true" alt="CI/CD Pipeline Diagram" width="800"/>

## Project Overview

This project demonstrates the creation of an automated CI/CD pipeline for a web application using AWS services. The pipeline integrates AWS CodeCommit, CodeBuild, CodeDeploy, and Cloud9 to streamline the development, build, and deployment processes.

## Technologies Used

- **AWS Cloud9**: Development environment for building the web application.
- **AWS CodeCommit**: Source code repository management.
- **AWS CodeArtifact** : Storing all dependencies
- **AWS CodeBuild**: Automated build process for code quality and security.
- **AWS CodeDeploy**: Deployment of applications to multiple environments.

## Features

- Automated build and deployment pipeline.
- Integrated source code management, build automation, and deployment.
- End-to-end testing to ensure pipeline reliability.
- Reduction in manual intervention and deployment time.

## Setup and Configuration

1. **Develop the Web Application**:
   - Use AWS Cloud9 to develop and test your web application.

2. **Configure AWS CodeCommit**:
   - Create a CodeCommit repository to manage your source code.

3. **Set Up AWS CodeBuild**:
   - Create a build project in CodeBuild.
   - Configure the build specifications and environment settings.

4. **Deploy with AWS CodeDeploy**:
   - Set up CodeDeploy to deploy your application to your desired environments.
   - Define deployment strategies and configurations.

5. **Create AWS CodePipeline**:
   - Configure CodePipeline to integrate CodeCommit, CodeBuild, and CodeDeploy.
   - Define the pipeline stages and actions.

6. **Testing and Validation**:
   - Conduct end-to-end testing to verify the pipeline's functionality and efficiency.

## Usage

- Commit your source code to AWS CodeCommit.
- CodePipeline will automatically trigger the build and deployment processes.
- Monitor the pipeline and deployment status through the AWS Management Console.

## Outcome

The project resulted in a more efficient development workflow with reduced manual intervention and a significant decrease in deployment time.



