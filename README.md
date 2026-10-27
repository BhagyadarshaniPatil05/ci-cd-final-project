# CI/CD Final Project

## Project Name

CI/CD Final Project – Counter Microservice

## Description

This project demonstrates the implementation of a complete Continuous Integration and Continuous Delivery (CI/CD) pipeline for a RESTful counter microservice.

The project uses GitHub Actions for continuous integration and Red Hat OpenShift Pipelines with Tekton for continuous delivery.

## Technologies Used

- Python
- Flask
- GitHub
- GitHub Actions
- Tekton
- OpenShift Pipelines
- Docker
- Kubernetes/OpenShift

## CI/CD Workflow

The GitHub Actions workflow performs code linting and unit testing automatically whenever changes are pushed to the repository.

The OpenShift Pipeline performs the required CI/CD tasks, including cleanup, linting, unit testing, building the application image, and deploying the application to OpenShift.