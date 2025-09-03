# Install EKS using eksctl

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name demo-cluster --region us-east-1 --fargate
```

## Delete the cluster after use

```
eksctl delete cluster --name demo-cluster --region us-east-1
```
