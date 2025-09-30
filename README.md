# CICD
![CI](https://github.com/LaboneeyDhanure/CICD/actions/workflows/ci.yml/badge.svg)

## 🚀 CI/CD Pipeline Flow
```mermaid
flowchart LR
    A[Developer push code] --> B[GitHub Repo]
    B --> C[CI: Build & Test]
    C --> D[CD: Deploy to Server/Cloud]
    D --> E[Application Running]
