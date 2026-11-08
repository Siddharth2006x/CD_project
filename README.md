
# CI/CD Pipeline Final Project

## Project Name
CI/CD Pipeline for Python Application using GitHub Actions, Tekton and OpenShift

## Project Description
This project demonstrates the implementation of a complete Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Python application.

GitHub Actions is used to automate code validation, linting and unit testing. Tekton is used to manage pipeline tasks, while OpenShift is used to deploy and run the application.

## Technologies Used
- Python
- GitHub Actions
- Git
- GitHub
- flake8
- nose
- Tekton Pipelines
- Red Hat OpenShift
- YAML

## Project Features
1. Automated GitHub Actions workflow.
2. Python code linting using flake8.
3. Automated unit testing using nose.
4. Tekton cleanup task.
5. Tekton unit testing task.
6. OpenShift application deployment.
7. Persistent Volume Claim configuration.
8. Application monitoring through OpenShift logs.

## Project Structure

```text
.
├── README.md
├── requirements.txt
├── .github/
│   └── workflows/
│       └── workflow.yml
└── .tekton/
    └── tasks.yml
```

## GitHub Actions
The GitHub Actions workflow automatically checks the source code, installs dependencies, runs flake8 linting and executes unit tests using nose.

## Tekton Tasks
The Tekton configuration contains:
- Cleanup Task
- Nose Unit Testing Task

## OpenShift Deployment
The application is deployed using OpenShift Pipelines. The deployment process includes resource cleanup, testing and application deployment.

## Testing
The project uses:
- flake8 for Python code linting.
- nose for automated unit testing.

## Expected Result
The CI/CD pipeline should execute all configured stages successfully and deploy the Python application to OpenShift.

The application should display the message:

`SERVICERUNNING`

The application runs on port `8000`.

## Author
Siddharth P
