# Project Deployment & Pipeline Results

This file contains the links to the active pipelines and verification of the running application on the deployed EC2 instance.

## 🔗 Pipeline Links

*   **Infrastructure Deployment (Terraform Pipeline):** 
    [Link to GitHub Actions Workflow](https://github.com/<YOUR_USERNAME>/<YOUR_REPO_NAME>/actions/workflows/create-infra.yml)
*   **Application CI/CD Pipeline:** 
    [Link to GitHub Actions Application Workflow](https://github.com/<YOUR_USERNAME>/<YOUR_REPO_NAME>/actions/workflows/<YOUR_APP_PIPELINE>.yml)

---

## 🖥️ Live Application

Once the infrastructure is ready and the application is deployed, the application can be accessed via:
*   **Public IP/DNS:** `http://<EC2_PUBLIC_IP>:<PORT>`
*   *(Note for NetFree users: Please request to open this IP/domain if it is currently filtered).*

---

## 📸 Screenshots & Verification

### 1. Terraform Deployment Pipeline Status
*Add a screenshot showing the successful run (green status) of your infrastructure pipeline here.*

![Terraform Pipeline Success](path/to/your/terraform-success-screenshot.png)

### 2. Application Deployment Pipeline Status
*Add a screenshot showing the successful run (green status) of your CI/CD pipeline here.*

![App Pipeline Success](path/to/your/app-success-screenshot.png)

### 3. Application Running Live
*Add a screenshot of your browser displaying the running application on your newly created EC2 instance.*

![App Running Live](path/to/your/app-live-screenshot.png)
