# Docker-GettingStarted
Getting familiar with Docker

Tutorial: Create and share a Docker app with Visual Studio Code

https://docs.microsoft.com/en-us/visualstudio/docker/tutorials/docker-tutorial

Create Github repo and clone to Visual Studio Code
- Started docker image docker/getting-started
- Verified locally hosted webpage
- Stopped and removed docker using CLI

Create Dockerfile
- Downloaded source code from https://github.com/docker/getting-started.git
- Extracted to project folder
- Created a Dockerfile, built docker image, and started from CLI
- Verified app running hosted locally
- Stopped and removed docker using CLI

Update and replace container
- Updated app wordage
- Rebuilt docker image and started from CLI
- Verified app running and changes reflected
- Stopped and removed docker using CLI

Upload to AWS
- Installed AWS CLI
- Created IAM user account
- Created an access key ID and secret access key
- Configured AWS CLI profile
- Created private repo
- Authenticated Docker client to the Amazon ECR registry
- Pushed Docker image to repo