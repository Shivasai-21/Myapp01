# 🚀 Myapp01 CI/CD Project

This repository demonstrates **Continuous Integration & Delivery (CI/CD)** using **Jenkins** and **Nginx** on an **Ubuntu server**.

## ✅ Deployment Workflow
- Code changes are pushed to GitHub
- Jenkins pipeline automatically:
  1. Clones the repository
  2. Builds the project with Maven
  3. Deploys the latest build artifacts

## 📊 Build Information
- **Build Number:** ${BUILD_NUMBER}
- **Deployed At:** ${BUILD_TIMESTAMP}

*(These values are injected automatically by Jenkins during each pipeline run.)*

## 🛠️ Tools & Technologies
- Ubuntu (server environment)
- Jenkins (pipeline automation)
- Maven (build tool)
- Nginx (web server)
- GitHub (source control)

## 🎯 Learning Outcomes
- Hands‑on experience with CI/CD pipelines
- Automated builds and deployments on Linux
- Integration of Jenkins with GitHub for source control
- Serving applications via Nginx

---

✨ Proudly showcasing DevOps automation and CI/CD integration.
