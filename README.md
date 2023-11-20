# Code Deploy To AWS EC2 (Nodejs Project)

Deploy the Nodejs application to EC2 Instance using CodeDeploy.

This repository contains scripts and configuration files essential for deploying a Node.js application to an Amazon EC2 instance using AWS CodeDeploy.

## File Descriptions

- `afterinstall.sh`: A shell script executed after the application's code has been deployed to the EC2 instance. This script typically handles tasks like setting up environment variables, running database migrations, or performing any post-deployment configuration needed for the application to run properly.

- `applicationstart.sh`: This script is responsible for starting the Node.js application on the EC2 instance. It usually includes commands to start the Node.js server, ensuring that the application is up and running after deployment.

- `appspec.yml`: The AppSpec file is a YAML-formatted file used by AWS CodeDeploy to manage a deployment. It specifies the deployment's hooks and the location of application files to copy. This file is crucial for instructing CodeDeploy on how to handle the deployment process, including pre-deployment and post-deployment activities.

- `buildspec.yml`: Used by AWS CodeBuild, this YAML file contains a collection of build commands and related settings, in the form of phases, that CodeBuild uses to run a build. This file is essential for defining the build process, including installation of dependencies, build commands, and post-build tests.

## Getting Started

To use this project, clone the repository and navigate to the project directory. Ensure you have Node.js installed and run `npm install` to install the necessary dependencies.

### Prerequisites

- AWS CLI installed and configured
- An AWS account with necessary permissions for EC2 and CodeDeploy
- Node.js environment

### Deployment

Follow these steps to deploy the application:

1. Run `npm install` to install dependencies.
2. Configure AWS CLI with your AWS account.
3. Use the provided `buildspec.yml` and `appspec.yml` for AWS CodeBuild and CodeDeploy configurations.
4. Deploy the application using the `applicationstart.sh` script.

**Note:** Make sure to have the necessary permissions and dependencies set up before running this script.

## Donations

If you want to show your appreciation, you can donate via [Buy Me a Coffee](https://www.buymeacoffee.com/lalatendu.swain)

## Disclaimer

This script is provided as-is and may require modifications or updates based on your specific environment and requirements. Use it at your own risk. The authors of the script are not liable for any damages or issues caused by its usage.

## Author : Lalatendu Swain | https://github.com/Lalatenduswain
## Website : https://blog.lalatendu.info/
