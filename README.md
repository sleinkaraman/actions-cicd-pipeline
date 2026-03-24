# Actions CI/CD Pipeline 🚀

This repository demonstrates a professional **Continuous Integration (CI)** workflow using **GitHub Actions**, **Docker**, and **Node.js**. It automates the entire process of building, tagging, and pushing a containerized web application to **Docker Hub**.

## 🛠 Project Architecture
1. **Source:** Node.js Express API providing a structured JSON health-check.
2. **Build:** Automated Docker image creation using a multi-stage `Dockerfile`.
3. **Registry:** Secure push to Docker Hub using GitHub Secrets.

## 🚀 Key Features
- **Automated Workflow:** Triggered on every push to the `main` branch.
- **Containerization:** Lightweight images based on `node:18-alpine`.
- **Security:** Managed environment variables and secure credential handling via Secrets.
- **Industry Standards:** Clean code structure and professional API responses.

## 🏗 Tech Stack
- **CI Engine:** GitHub Actions
- **Containerization:** Docker
- **Backend:** Node.js / Express.js
- **Registry:** Docker Hub

## 🚦 How to Run
1. Clone the repository.
2. Ensure you have your `DOCKERHUB_USERNAME` and `DOCKERHUB_TOKEN` set in GitHub Secrets.
3. Push a change to the `main` branch to trigger the pipeline.

## 🧠 Key Learning Outcomes

Through the development of this specific CI/CD infrastructure, I achieved the following technical milestones:

- **Event-Driven Workflows:** Mastered the trigger-mechanism of GitHub Actions, ensuring seamless execution on `push` events to the `main` branch.
- **Workflow Security & Secrets:** Implemented zero-trust authentication using GitHub Secrets to securely communicate with external container registries.
- **Automated Registry Integration:** Managed the automated build-and-push cycle, ensuring immediate image availability in the Docker Hub registry.
- **CI/CD Debugging:** Gained practical experience in troubleshooting pipeline failures.



