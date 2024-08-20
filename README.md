# t02 IOC Instances and Services

This repository holds the definition of Argocd deployed ec services. Each sub folder of the 'services' directory of an ec 'services repository' is mapped to an Argocd App which is managed by a root App.

## Deployment
To deploy the Argocd root App:
```
# Login to argus cluster
kubectl apply -n esq51579 -f apps.yaml
```
