# CI/CD Pipeline Project - repo1

## Project Name: CI/CD Pipeline with OpenShift and Tekton

## 📌 Project Overview
This project demonstrates a complete CI/CD pipeline implementation using GitHub Actions, Tekton, and OpenShift for deploying containerized applications.

## 🚀 Technologies Used
- **GitHub Actions** - Continuous Integration (Linting & Testing)
- **Tekton** - Task Management and Pipeline Execution
- **OpenShift** - Application Deployment
- **Python/Flask** - Sample Application
- **Docker** - Containerization

## 📁 Repository Structure
.
├── .github/
│ └── workflows/
│ └── workflow.yml # GitHub Actions CI workflow
├── .tekton/
│ └── tasks.yml # Tekton tasks and pipeline
├── src/
│ └── app.py # Sample application
├── tests/
│ └── test_app.py # Unit tests
└── README.md

## 🔄 Pipeline Workflow
1. Code push triggers GitHub Actions
2. Flake8 runs linting checks
3. Nose runs unit tests
4. Tekton builds container image
5. OpenShift deploys the application

## ✅ Status
- CI Pipeline: ✅ Passing
- CD Pipeline: ✅ Passing
- Application: ✅ Running on port 8000
