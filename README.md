# ACR example (build, push image from github to ACR)

## Step-01: Deploy manifests 
```
# Deploy manifests
kubectl apply -f ./kube-manifests
```
## Step-02: Verify created objects
```
# Verify objects
kubectl get pods,svc
```
## Step-03: Clean-Up
```
# Delete all manifests
kubectl delete -f ./kube-manifests
```
