# 🚀 Multi-Tier Automated Deployment Pipeline

This repository contains a production-ready DevOps workflow that automates the deployment of a multi-container application on **AWS**.

## 🏗️ Project Architecture
- **Infrastructure as Code (IaC):** AWS EC2, S3, and Security Groups provisioned via **Terraform**.
- **Configuration Management:** Automated server setup, Docker installation, and security hardening via **Ansible**.
- **Container Orchestration:** Deployed **React Frontend**, **MongoDB**, and **Mongo-Express UI** using **Docker Compose**.
- **CI/CD:** Fully automated pipeline with build, deploy, and infrastructure teardown stages via **GitLab CI/CD**.

## 🌟 Key Features
- **Remote State Management:** Terraform state is securely managed in an **AWS S3** bucket.
- **Dynamic Provisioning:** Infrastructure is created and updated automatically through the pipeline.
- **Persistent Data:** MongoDB volumes are configured to ensure data persistence across container restarts.
- **Safe Teardown:** Included a manual 'Destroy' stage to optimize cloud costs.

## 🛠️ Tech Stack
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white) 
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=flat&logo=terraform&logoColor=white) 
![Ansible](https://img.shields.io/badge/Ansible-%23EE0000.svg?style=flat&logo=ansible&logoColor=white) 
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=flat&logo=docker&logoColor=white) 
![GitLab](https://img.shields.io/badge/GitLab-%23181717.svg?style=flat&logo=gitlab&logoColor=white)

## 📖 How to Deploy
1. Set up your **AWS Access Keys** and **SSH Private Key** in GitLab CI/CD Variables.
2. Ensure the S3 bucket for Terraform backend exists.
3. Push changes to the `main` branch to trigger the automation.
