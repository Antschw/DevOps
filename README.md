# DevOps

## Description

This project focuses on deploying and managing services using Kubernetes,
including configuration files and commands for applying these configurations with `kubectl`.

## Files
- [Deployment](deployment.yaml)
- [Service](service.yaml)
- [HTTPRoute](route.yaml)

## Commands

### Deployment
```bash
kubectl apply -f deployment.yaml
```

### Service
```bash
kubectl apply -f service.yaml
```

### Route
```bash
kubectl apply -f route.yaml
```