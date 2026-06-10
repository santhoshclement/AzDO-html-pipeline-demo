# 🚀 Azure DevOps CI/CD Pipeline Demo

A complete end-to-end Azure DevOps CI/CD demonstration project created by **Santhosh Clement**.

This project automatically provisions Azure resources and deploys a static website using Azure DevOps Pipelines and Infrastructure as Code (Terraform).

---

## 🌐 Live Website

**Application URL**

https://YOUR-APP-NAME.azurewebsites.net

Example:

http://santhosh-demo-webapp.azurewebsites.net

---

## 🏗 Architecture

```text
GitHub
   ↓
Azure DevOps Pipeline
   ↓
Terraform
   ↓
Azure Resource Group
   ↓
Azure App Service Plan
   ↓
Azure App Service
   ↓
Deploy Website
```

---

## 📋 Project Features

* GitHub Source Control
* Azure DevOps CI/CD Pipeline
* Terraform Infrastructure as Code
* Azure Resource Group Creation
* Azure App Service Plan Provisioning
* Azure App Service Deployment
* Production Approval Workflow
* Automated Website Deployment
* DevSecOps Ready Architecture

---

## 📂 Repository Structure

```text
.
├── index.html
├── azure-pipelines.yml
├── terraform
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
└── images
    └── azure-devops-flow.png
```

---

## ⚙️ Azure Resources Created

| Resource         | Example              |
| ---------------- | -------------------- |
| Resource Group   | rg-demo-webapp       |
| App Service Plan | asp-demo-linux       |
| App Service      | santhosh-demo-webapp |
| Region           | UAE North / East US  |
| Runtime          | Linux                |

---

## 🔄 CI/CD Flow

1. Developer commits code to GitHub.
2. Azure DevOps Pipeline is triggered automatically.
3. Terraform provisions Azure infrastructure.
4. Build artifacts are generated.
5. Deployment waits for Production Approval.
6. Azure App Service is updated.
7. Website becomes available to users.

---

## 🔐 Approval Workflow

```text
Build Stage
     ↓
Production Approval
     ↓
Deploy Stage
```

Deployment to Production requires manual approval through Azure DevOps Environments.

---

## 🛠 Technologies Used

* GitHub
* Azure DevOps
* Terraform
* Azure Resource Manager
* Azure App Service
* YAML Pipelines
* HTML/CSS
* DevSecOps Practices

---

## 📈 Future Enhancements

* Terraform Remote State
* Multi-Stage Deployment (DEV → TEST → PROD)
* SonarQube Integration
* Snyk Security Scanning
* Azure Key Vault Integration
* Azure Application Insights
* Blue-Green Deployment Strategy

---

## 👨‍💻 Author

**Santhosh Clement**

Principal Security Architect | Azure | DevSecOps | Entra ID | AI

Abu Dhabi, UAE

GitHub: https://github.com/santhoshclement

LinkedIn: https://www.linkedin.com/in/santhoshclement

---

## 🎯 Purpose

This project demonstrates practical experience with:

* Azure DevOps Pipelines
* Infrastructure as Code
* Cloud Automation
* Continuous Delivery
* Azure App Service Hosting
* Enterprise DevSecOps Practices

Suitable for showcasing Cloud Architecture, DevOps Engineering, Security Architecture, and Azure Platform Engineering skills.
