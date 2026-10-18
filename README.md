# CI/CD Tools and Practices Final Project

## Project Overview

This project implements a RESTful Customer Accounts microservice and demonstrates Continuous Integration and Continuous Delivery (CI/CD) practices using automated testing, code quality checks, containerization, and cloud-native deployment tools.

## Technologies Used

- **Python:** Microservice implementation and unit testing.
- **Flask:** REST API development.
- **Flake8:** Python code linting.
- **Nose:** Automated unit testing.
- **GitHub Actions:** Automated CI workflow for linting and tests.
- **Docker:** Container image building.
- **Tekton:** Cloud-native CI/CD tasks and pipeline automation.
- **OpenShift:** Application deployment and pipeline execution.

## CI Workflow

The GitHub Actions workflow checks out the repository, installs dependencies, runs Flake8 linting, and executes unit tests with Nose.

## Tekton Tasks

The Tekton configuration defines cleanup and unit-testing tasks for the project.

## Setup

Run the setup script in the lab environment:

```bash
bash bin/setup.sh
```

Then exit the shell and open a new terminal to activate the Python virtual environment.

## License

Licensed under the Apache License. See [LICENSE](LICENSE).

## Author

Skills Network
