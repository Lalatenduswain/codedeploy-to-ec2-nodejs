# Code Deploy To AWS EC2 (Nodejs Project)

Deploy the Nodejs application to EC2 Instance using CodeDeploy.

This repository contains scripts and configuration files for deploying a Node.js application to an Amazon EC2 instance using AWS CodeDeploy. The project includes various scripts like `afterinstall.sh`, `applicationstart.sh`, and AWS-specific files like `appspec.yml` and `buildspec.yml`.

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
