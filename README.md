# Fraud MLOps – GitOps Repository

This repository is the GitOps source of truth for the Fraud / Anomaly Detection MLOps platform.

## Scope
- ArgoCD Applications
- Helm values for platform components
- Environment-specific Kubernetes manifests

## Principles
- No application code
- No data or models
- Git = desired state
- Rollback via git revert
