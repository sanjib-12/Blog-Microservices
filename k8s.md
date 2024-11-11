## kubectl get pods 
retuns ==all== the runnung pods

## kubectl get pods -o wide
give the information in details

## kubectl describe pod <PODNAME>
descrive the image in details

## kubectl delete pod <PodName>
deletes the specified pod.

## kubectl create -f redis.yaml
kubectl create: This command is used to create a new resource in Kubernetes.

-f: This flag tells kubectl to use a file for the resource configuration.

-redis.yaml: The name of the YAML file containing the configuration for the resource(s) you want to create. This file should define one or more resources, like Pods, Services, or Deployments.

## kubectl apply -f redis.yaml
kubectl apply: The apply command is used to create or update resources. Unlike kubectl create, which only creates resources if they do not exist, apply will create the resource if it doesn’t exist, or update it if it already does.

-f: This flag specifies a file to read the configuration from.

redis.yaml: The name of the YAML file containing the configuration for the resource(s) you want to manage.
