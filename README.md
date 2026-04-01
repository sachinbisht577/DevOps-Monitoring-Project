## 📦 Project Structure

📦 DevOps Monitoring Project
├── 🚀 app/                      # Node.js Application
│   ├── 📄 package.json         # Dependencies
│   └── 📄 index.js             # Entry point
│
├── 🐳 Dockerfile               # Docker build configuration
│
├── ☸️ k8s/                     # Kubernetes manifests
│   ├── 📄 deployment.yaml      # App deployment
│   └── 📄 service.yaml         # Service exposure
│
├── 📊 monitoring/              # Monitoring stack
│   ├── 📄 prometheus.yml       # Prometheus config
│   └── 📄 grafana-dashboard.json  # Grafana dashboard
│
└── ⚙️ .github/workflows/       # CI/CD pipeline
    └── 📄 ci.yml               # GitHub Actions workflow

    📊 Access
App: http://localhost:30007
Grafana: http://localhost:32000
