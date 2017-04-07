# Kube config for Apache Ignite

*Create the Kubernetes service for Apache Ignite*

```

$ kubectl create -f ignite-svc.yaml

```

*Create the Kubernetes deployments for Apache Ignite*

```

$ kubectl create -f ignite-deployment.yaml

```

*To see the pods*

```

$ kubectl get pods

OUTPUT WILL BE SOMETHING LIKE BELOW:

NAME                                     READY     STATUS    RESTARTS   AGE
apache-ignite-cluster-2708371603-7l3x0   1/1       Running   0          4m
apache-ignite-cluster-2708371603-mbv8j   1/1       Running   0          4m
apache-ignite-cluster-2708371603-q82q6   1/1       Running   0          4m

```
