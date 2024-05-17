# The Kubernetes Workshop

``kubectl get all``

## Deployment

``kubectl create -f deployment-definition.yml``

``kubectl create deployment nginx --image=nginx:latest``
create pod: ``kubectl run nginx --image=nginx:latest``

## Rollout to previous version

```kubectl rollout undo deployment/nginx-deploymnet```
