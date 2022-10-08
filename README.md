# prometheus-installation
This repo will show you how you can install Prometheus in minikube environment

### Following setup im using 
- Minikube
- lens IDE
- Choco for installtion
- windows 10

### first get the helm repo
```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
```

```
helm repo update
```

```
kubectl create namespace monitoring
```

```
helm install prometheus --namespace monitoring prometheus-community/kube-prometheus-stack
```
