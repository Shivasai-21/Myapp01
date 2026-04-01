# 🚀 Myapp01 CI/CD Project

This repository demonstrates **Continuous Integration & Delivery (CI/CD)** using **Jenkins** and **Nginx**.

## ✅ Deployment Status
Every commit triggers a Jenkins pipeline that:
1. Clones the repository
2. Builds the project with Maven
3. Deploys the latest build artifacts into Nginx’s document root

### Latest Deployment
- **Build Number:** ${BUILD_NUMBER}
- **Deployed At:** ${BUILD_TIMESTAMP}

*(These values are injected automatically by Jenkins during each pipeline run.)*

## 🌐 Live Demo
Visit the deployed project here:  
`http://<your-server-ip>/`

You’ll see a success page confirming the deployment.

## 🛠️ Tools & Technologies
- Jenkins (Pipeline automation)
- Maven (Build tool)
- Nginx (Web server)
- GitHub (Source control)

---

✨ Proudly showcasing DevOps automation and CI/CD integration.
