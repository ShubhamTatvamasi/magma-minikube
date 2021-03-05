# magma-minikube

Set Minikube:
```bash
export MAGMA_ROOT=/home/shubham/myfiles/git/minikube-magma/magma

minikube start \
  --memory=8192 \
  --cpus=2 \
  --kubernetes-version=v1.18.0 \
  --mount \
  --mount-string "${MAGMA_ROOT}/orc8r/cloud/docker/metrics-configs:/configs"
```

