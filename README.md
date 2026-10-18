# CI/CD Tools and Practices Final Project Template

## Project Name
ci-cd-final-project

## Project Overview

This project implements a RESTful Customer Accounts microservice and demonstrates Continuous Integration and Continuous Delivery (CI/CD) practices through automated code quality checks, unit testing, and cloud-native deployment workflows.

## Technologies Used

- **Python:** Microservice implementation and unit testing.
- **Flake8:** Python code linting.
- **Nose:** Automated unit testing.
- **GitHub Actions:** Automates linting and unit tests whenever changes are pushed to the repository.
- **Tekton:** Defines tasks for CI/CD automation.
- **OpenShift Pipelines:** Supports pipeline execution and application deployment.

## CI Workflow

The GitHub Actions workflow checks out the repository, installs dependencies, runs Flake8 linting, and executes unit tests using Nose.

## Tekton Tasks

The Tekton configuration in `.tekton/tasks.yml` defines cleanup and unit-testing tasks.

## Setup

Run the setup script in the lab environment:

```bash
bash bin/setup.sh
```

Then exit the shell and start a new terminal to activate the Python virtual environment.

## License

Licensed under the Apache License. See [LICENSE](LICENSE).

## Author

Skills Network
