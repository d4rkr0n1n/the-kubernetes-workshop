# The Kubernetes Workshop

## Deployment

``kubectl create deployment nginx --image=nginx:latest``
create pod: ``kubectl run nginx --image=nginx:latest``

## Rollout to previous version

```kubectl rollout undo deployment/nginx-deploymnet```
