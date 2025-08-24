# Qreator App

## Create Fargate profile

```
eksctl create fargateprofile \
    --cluster my-cluster \    
    --region us-east-1 \    
    --name qreator-app \    
    --namespace qreator-fargate
```

## Deploy the deployment, service and Ingress

```
kubectl apply -f https://raw.githubusercontent.com/Shah1011/QReator/refs/heads/main/qreator-K8.yaml
```

<img width="1014" height="899" alt="image" src="https://github.com/user-attachments/assets/9b78a9c8-61c4-492a-b5c9-895c0093128a" />
