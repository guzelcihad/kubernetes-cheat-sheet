## Create a POD
```
kubectl run <pod-name> --image=<image-name>
```

## Create a POD with Yaml File
```
kubectl create -f <pod.yaml>
```
or 

```
kubectl apply -f <pod.yaml>
```
## List available PODs
```
kubectl get pods
```

## More info about POD
```
kubectl describe pod <pod-name>
```

## Delete a POD
```
kubectl delete pod <pod-name>
```
