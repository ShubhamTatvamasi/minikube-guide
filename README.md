# minikube-guide

install minikube on macOS
```bash
brew install minikube
```
---

install HyperKit
```bash
brew install hyperkit
```

Start a cluster using the hyperkit driver:
```bash
minikube start --vm-driver=hyperkit
```

To make hyperkit the default driver:
```bash
minikube config set vm-driver hyperkit
```
