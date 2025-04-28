# Tekton Pipeline: Build and Push Docker Image

This project sets up a **Tekton pipeline** to:

- Clone a **public GitHub repository**.
- Build a Docker image with **Kaniko**.
- Push the image to **Docker Hub**.
- Manually trigger runs via the **Tekton Dashboard**.

---

## Prerequisites

- Kubernetes Cluster
- `kubectl`
- [Tekton Pipelines](https://tekton.dev/docs/getting-started/)
- [Tekton Dashboard](https://github.com/tektoncd/dashboard)

Install Tekton Pipelines:

```bash
kubectl apply -f https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml
```
