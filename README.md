# minikube-guide

install minikube on macOS
```bash
brew install minikube
```
---

Start a cluster using the virtualbox driver:
```bash
minikube start --vm-driver=virtualbox
```

To make virtualbox the default driver:
```bash
minikube config set vm-driver virtualbox
```
