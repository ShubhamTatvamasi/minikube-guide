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

unset config
```bash
minikube config unset disk-size
```

stop minikube
```bash
minikube stop
```
