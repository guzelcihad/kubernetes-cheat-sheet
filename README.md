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

or 

```
kubectl get pod <pod-name> -o yaml > pod-definition.yaml
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
## Create Replication Controller
```
kubectl create -f <file.yaml>
```
## List Replication Controller
```
kubectl get replicationcontroller
```
## Create ReplicaSet
```
kubectl create -f <file.yaml>
```
## List ReplicaSet
```
kubectl get replicaset
```

## Update ReplicaSet From File
```
kubectl replace -f <file.yaml>
```

## Scale ReplicaSet
```
kubectl scale --replicas=6 -f <file.yaml>
```

## Delete ReplicaSet
```
kubectl delete replicaset <file.yaml>
```

----

## Create Deployment
```
kubectl create -f deployment <file.yaml>
```
## List Deployment
```
kubectl get deployment
```

## Update Deployment From File
```
kubectl replace -f <file.yaml>
```

## Delete Deployment
```
kubectl delete replicaset <file.yaml>
```

## List All Objects at Once
```
kubectl get all
```
## Look status of the Rollout
```
kubectl rollout status deployment/<deployment-name>
```

## Look history of the Rollout
```
kubectl rollout history deployment/<deployment-name>
```
## Deployment Rollback
```
kubectl rollout undo deployment/<deployment-name>
```

## Create Service
```
kubectl create -f <file.yaml>
```
## List Services
```
kubectl get service
```
## Update Service From File
```
kubectl replace -f <file.yaml>
```

## Delete Service
```
kubectl delete service <file.yaml>
```