# KUBERNETES
COMANDOS KUBERNETES

## Ver lista de nodos
```
kubectl get node
```
o

```
kubectl get nodes -o wide
```
o

```
kubectl get nodes -o jason
```
## Con manifest
```
kubectl apply -f ejemplo.yaml
```
o

```
kubectl get all
```
o

```
kubectl delete -f ejemplo.yaml
```
## Sin manifest
```
kubectl create nginx --image=nginx:latest --port 80 --replicas=1
```
o

```
kubectl get all
```
o

```
kubectl delete deployment nginx
```
