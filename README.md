# minikube-guide

Start minikube with CNI:
```bash
minikube start --network-plugin=cni --cni=calico
```

---

install minikube on macOS
```bash
brew install minikube
```

install HyperKit
```bash
brew install hyperkit
```
---

list all the configs by minikube
```bash
minikube config list
```

Increasing memory allocation - 4 GB RAM
```bash
minikube config set memory 4096
```

Increasing disk-size allocation - 30 GB
```bash
minikube config set disk-size 30000
```

To make hyperkit the default driver:
```bash
minikube config set vm-driver hyperkit
```

Check current custom configs
```bash
minikube config view
```
---

### unset config

unset disk-size
```bash
minikube config unset disk-size
```

unset dashboard
```bash
minikube config unset dashboard
```

Start a cluster using the hyperkit driver:
```bash
minikube start --vm-driver=hyperkit
```

stop minikube
```bash
minikube stop
```

delete minikube cluster
```bash
minikube delete
```

tunnel makes services of type LoadBalancer accessible on localhost
```bash
minikube tunnel
```
