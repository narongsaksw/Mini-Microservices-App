# Mini-Microservices-App
Microservices with Node JS and React

##Common kubectl commands

Print out information about all of the running pods:
```
kubectl get pods
```

Execute the given command in a running pod:
```
kubectl exec -it [pod_name] [cmd]
```

Print out logs from the given pod:
```
kubectl logs [pod_name]
```

Deletes the given pod:
```
kubectl delete pod [pod_name]
```

Tells kubernates to process the config:
```
kubectl apply -f [config file name]
```

Print out some information about the running pod:
```
kubectl describe pod [pod_name]
```