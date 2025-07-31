<div align="center">

# 🚀 golive-mini

*One-file Go HTTP service + single Terraform plan + GitHub Actions pipeline → live on AWS ECS Fargate in 90 seconds.*

<br/>

[![Live Demo](https://img.shields.io/badge/🚀_LIVE-Open_Demo-00d4aa?style=for-the-badge&logo=aws)](https://golive-mini-17241l0e4-eatherys-projects.vercel.app)
[![GitHub Repo](https://img.shields.io/badge/📦_REPO-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/zerotrace-dev/golive-mini)

<br/>

### 📊 Quick Stats

| Metric | Value |
|---|---|
| **Lines of Go Code** | `18` |
| **Lines of Terraform** | `60` |
| **Image Size** | `15 MB` |
| **Deploy Time** | `~90 s` |
| **Idle Cost** | `≈ $0.01 / hour` |

</div>

---

## 🧰 Tech Stack
![Go](https://img.shields.io/badge/Go-1.22-00ADD8?style=flat-square&logo=go)
![Terraform](https://img.shields.io/badge/Terraform-1.6-5C4EE5?style=flat-square&logo=terraform)
![Docker](https://img.shields.io/badge/Docker-Multi--stage-2496ED?style=flat-square&logo=docker)
![AWS](https://img.shields.io/badge/AWS-ECS_Fargate-FF9900?style=flat-square&logo=amazon-aws)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions)

---

## ⚡ One-command Deploy
```bash
# Fork repo → AWS prerequisites → push to main
aws ecr create-repository --repository-name golive-mini
# Done! GitHub Actions & Vercel auto-deploy.
