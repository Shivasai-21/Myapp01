# 🚀 Myapp01 CI/CD Project

This repository demonstrates **Continuous Integration & Delivery (CI/CD)** using **Jenkins** and **Nginx**.

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
- Jenkins (Pipeline automation)
- Maven (Build tool)
- Nginx (Web server)
- GitHub (Source control)

---

✨ Proudly showcasing DevOps automation and CI/CD integration.
