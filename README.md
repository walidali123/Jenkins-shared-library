# Project: Docker Groovy Automation

This project provides Groovy scripts for automating Docker tasks such as building, logging in, and pushing Docker images.

## Prerequisites

- Docker installed on the system where the scripts will be executed.
- Maven installed if using the build script.

## Usage

### 1. `buildDockerImage.groovy`

This script builds a Docker image with the provided image name.

#### Example:

```groovy
./buildDockerImage.groovy "my-docker-image"

### 2. buildApplication.groovy
This script builds the application for a specific branch using Maven.

Example:
groovy
Copy code
./buildApplication.groovy
### 3. dockerLogin.groovy
This script logs into a Docker registry using credentials stored in Jenkins.

Example:
groovy
Copy code
./dockerLogin.groovy
### 4. dockerPush.groovy
This script pushes a Docker image with the provided image name to a Docker registry.

# Example:
groovy
Copy code
./dockerPush.groovy "my-docker-image"
# Scripts
buildDockerImage.groovy: Builds a Docker image.
buildApplication.groovy: Builds the application using Maven.
dockerLogin.groovy: Logs into a Docker registry.
dockerPush.groovy: Pushes a Docker image to a registry.
## Notes
These scripts assume the presence of necessary Docker credentials stored in Jenkins for logging into Docker registries.
css
Copy code
This readme provides an overview of the project, its purpose, usage instructions, and
