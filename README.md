# UK Healthcare Patient Management Platform

## DevOps Tasks

This repository contains the DevOps implementation for the
UK Healthcare Patient Management Platform.

## T-001 – CI/CD Pipeline Setup

### Objective

Set up and validate a CI/CD pipeline using GitHub Actions
for automated build, testing, packaging, deployment, and
deployment verification.

### Technology

- GitHub Actions
- Git
- Java 17
- Maven
- JUnit
- Bash

### Pipeline

Git Push
→ GitHub Actions
→ Checkout
→ Java Setup
→ Build & Test
→ Package
→ Upload Artifact
→ Download Artifact
→ Deploy
→ Verify Deployment

## T-002 – Containerization & Deployment Automation

### Containerization

The application is containerized using Docker with a
multi-stage Dockerfile.

### Deployment Automation

Docker Compose and Terraform configurations are included
for deployment automation.

### Infrastructure Files

- Dockerfile
- docker-compose.yml
- terraform/main.tf

## Project Structure

```text
.
├── .github/
│   └── workflows/
│       └── ci-cd.yml
├── app/
│   ├── pom.xml
│   └── src/
├── docs/
│   ├── evidence/
│   └── pipeline-setup.md
├── scripts/
│   └── deploy.sh
├── terraform/
│   └── main.tf
├── Dockerfile
├── docker-compose.yml
├── .gitignore
└── README.md