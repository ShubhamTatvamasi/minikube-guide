# multipass

Launch minikube:
```bash
multipass launch minikube \
  --cpus 4 \
  --memory 4G \
  --disk 40G \
  --network en0 \
  --bridged
```

Get access to minikube instance:
```bash
multipass shell minikube
```

Delete Instance:
```bash
multipass delete --purge minikube
```
