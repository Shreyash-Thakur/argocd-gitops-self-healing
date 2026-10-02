# argocd-gitops-self-healing

Source of truth for the DevOps IA demo: **Automated GitOps Continuous Delivery, Drift Detection,
and Infrastructure Self-Healing Using ArgoCD on Kubernetes**.

This repo holds a single Kubernetes manifest, `deployment.yaml`. ArgoCD watches it, keeps the
cluster in sync with it, and recreates the Deployment automatically if it is deleted from the cluster.

Group: Vivin Dube (16010123273), Shreyash Thakur (16010123326), Tanmay Goraksha (16010123136)
