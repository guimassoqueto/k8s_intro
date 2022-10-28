1. `kubectl create -f <deployment_name>`

2. Status: 
    * `kubectl rollout status deployment <deployment_name>`
    * `kubectl rollout history deployment <deployment_name>`
3. Rollback: 
    * `kubectl rollout undo deployment <deployment_name>`

See also:
* Deployment strategy