# DevOps & Kubernetes Deployment Showcase

Welcome to my DevOps portfolio repository! This repo demonstrates my expertise in Kubernetes deployments, GitOps workflows, and the App of Apps pattern using ArgoCD.

## Structure

- **BASE/**: Contains individual application manifests or Helm charts (Hazelcast, NATS, Kong, etc.)
- **app-of-apps/**: ArgoCD Application manifests using the App of Apps pattern (for dev, prod, etc.)
- **.github/workflows/ArgoCD-Pipeline/**: Bootstrap and installation manifest for ArgoCD.

## Why This Repo?

- **All-in-one Portfolio**: Showcases everything I’ve learned in DevOps and Kubernetes.
- **Continuous Learning**: I’ll add new applications and deployment patterns as I learn them.

## How to Use

1. Clone the repo.
2. Install ArgoCD in your cluster using the Pipeline.
3. Apply the App of Apps manifest to deploy all apps.
4. Explore individual deployments in `BASE/`.

## Applications Included

- ArgoCD
- NATS
- Kong
- PostgresDB
- *(Add more as you learn them!)*

## Patterns Covered

- App of Apps (ArgoCD)
- GitOps
- Helm Charts & Raw Manifests

## Contributing

If you want to contribute or suggest improvements, feel free to open issues or PRs!

---

**Maintained by Yvon Ndjamen**
