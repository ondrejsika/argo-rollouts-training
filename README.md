# argo-rollouts-training

## Install Argo Rollouts to Kubernetes

https://argo-rollouts.readthedocs.io/en/stable/installation/#controller-installation

```bash
kubectl create namespace argo-rollouts
kubectl apply -n argo-rollouts -f https://github.com/argoproj/argo-rollouts/releases/latest/download/install.yaml
```

## Install Argo Rollouts CLI

https://argo-rollouts.readthedocs.io/en/stable/installation/#kubectl-plugin-installation

```bash
brew install argoproj/tap/kubectl-argo-rollouts
```

## Dashboard

Run:

```
kubectl argo rollouts dashboard
```

See: http://127.0.0.1:3100
