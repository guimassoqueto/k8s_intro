# k8s_intro


## Basic commands

1. Create: `kubectl create -f <file_name>.yaml`
2. Get: `kubectl get <pods | rs | deployments>`
3. Update:
    * `kubectl apply -f <file_name>.yaml`
    * `kubectl edit <pods | rs | deployments> <resource_name>`