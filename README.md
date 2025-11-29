# Enterprise Application Migration
Modernize legacy 3 - tier applications with containerization and Kubernetes. Automated CI/CD, monitoring, and infrastructure as code. Reduce costs, improve scalability, and accelerate deployment cycles.

## Project Structure
```bash
enterprise-app-migration/
├── README.md
├── docs/
│   └── migration-guide.md
├── frontend/
│   ├── package.json
│   ├── Dockerfile
│   ├── nginx.conf
│   └── src/
│       └── App.jsx
├── backend/
│   ├── package.json
│   ├── Dockerfile
│   └── app.js
├── k8s/
│   ├── frontend-deployment.yaml
│   └── backend-deployment.yaml
└── scripts/
    └── deploy.sh
```
## Quick Start
```bash
git clone https://github.com/VictorCh50/enterprise-app-migration.git
cd enterprise-app-migration
docker-compose up --build
```

