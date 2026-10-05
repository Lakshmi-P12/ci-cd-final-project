# CI/CD Tools and Practices Final Project

This project demonstrates the implementation of a CI/CD workflow using GitHub Actions and OpenShift Pipelines.

## Project Overview

The project covers the following CI/CD practices:

* Created a GitHub Actions CI workflow triggered by pushes and pull requests to the `main` branch.
* Configured the workflow to run in a Python 3.9 environment.
* Added code linting using Flake8.
* Added automated unit testing using Nose with coverage.
* Created Tekton tasks for cleaning the workspace and running Nose tests.
* Configured a cleanup task to remove existing files from the shared workspace.
* Configured a Nose testing task to install dependencies and execute the unit tests.
* Created an OpenShift Pipeline using Tekton tasks for cleanup, cloning the repository, linting, testing, building the container image, and deploying the application.
* Used Buildah for container image building.
* Used the OpenShift Client task to deploy the built image to the OpenShift cluster.


## License

Licensed under the Apache License.

## Author

Skills Network
