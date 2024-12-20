# DevOps

## Description

This project focuses on deploying and managing services using Kubernetes,
including configuration files and commands for applying these configurations with `kubectl`.

## Files

### FrontEnd
- [Deployment FrontEnd](FrontEnd/deployment.yaml)
- [Service FrontEnd](FrontEnd/service.yaml)
- [HTTPRoute FrontEnd](FrontEnd/route.yaml)

### BackEnd 
- [Deployment FrontEnd](BackEnd/deployment.yaml)
- [Service FrontEnd](BackEnd/service.yaml)
- [HTTPRoute FrontEnd](BackEnd/route.yaml)

## Commands

### FrontEnd

#### Deployment
```bash
kubectl apply -f FrontEnd/deployment.yaml
```

#### Service
```bash
kubectl apply -f FrontEnd/service.yaml
```

#### Route
```bash
kubectl apply -f FrontEnd/route.yaml
```

### BackEnd

#### Deployment
```bash
kubectl apply -f BackEnd/deployment.yaml
```

#### Service
```bash
kubectl apply -f BackEnd/service.yaml
```

#### Route
```bash
kubectl apply -f BackEnd/route.yaml
```