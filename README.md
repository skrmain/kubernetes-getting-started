# Kubernetes Getting Started

## Notes

> Minikube Installation

- https://minikube.sigs.k8s.io/docs/start/

```sh
minikube start

minikube status

kubectl get node

kubectl apply -f <file-name.yaml>

kubectl get all

kubectl get configmaps

kubectl get secrets

kubectl describe service <service-name>
kubectl describe pod <pod-name>

kubectl logs -f <pod-name>

minikube ip
```

```sh
# To launch bash of a pod container 
kubectl exec --stdin --tty <POD> -- /bin/bash

# to restart a deployment
kubectl rollout restart deployment <deployment name>

# to delete
kubectl delete <Component[pod, deployment,...]t> <component_id>
```

## References

- https://youtu.be/s_o8dwzRlu4
- https://gitlab.com/nanuchi/k8s-in-1-hour
- https://minikube.sigs.k8s.io/docs/start/
- https://kompose.io/ --> Convert Docker-compose --> Kubernetes Configs