# golive-mini 🚀

> **One-file Go HTTP service + single Terraform plan + GitHub Actions pipeline**  
> Push to `main` → 90 seconds later your app is live on AWS ECS Fargate.

---

## 30-second tour

| What | Link / Command |
|------|----------------|
| **Live URL** | https://golive-mini-123456789.ap-southeast-1.elb.amazonaws.com |
| **CI/CD** | [Actions](https://github.com/zerotrace-dev/golive-mini/actions/workflows/ci.yml) |
| **Infra as Code** | `infra/main.tf` (≈ 60 lines) |
| **App code** | `app/main.go` (18 lines) |
| **Cost** | ≈ \$0.01/hour when idle (Fargate Spot 256/512) |

---

## Quick start (local)

```bash
# Clone
git clone https://github.com/zerotrace-dev/golive-mini.git && cd golive-mini

# Run locally
cd app && go run .

# Open http://localhost:8080 → "Hello from local"
