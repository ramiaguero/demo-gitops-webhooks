# demo-gitops-webhooks

Manifiestos de ejemplo para la demo de webhooks de GitHub (meetup DDC-410).

ArgoCD sigue este repo: lo que esté acá es lo que tiene que estar corriendo en el
cluster. Un cambio en `k8s/` y un push alcanzan para que ArgoCD lo aplique.

Durante la charla se cambia `replicas` en `k8s/deployment.yaml` para mostrar el
recorrido OutOfSync → Syncing → Synced.
