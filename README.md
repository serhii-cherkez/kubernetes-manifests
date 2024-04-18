# kubernetes-manifests
| NAME    |                PROMPT                  |           DESCRIPTION        | EXAMPLE  |
|---------|----------------------------------------|------------------------------|----------|
|         |kubectl apply -f app.yaml               |This is the main YAML manifest for deploying application in Kubernetes. It typically includes specifications for pods, deployments, services, or other resources necessary for your application to run.                              |app.yaml  |
|         |kubectl apply -f app-livenessProbe.yaml |              |app-livenessProbe.yaml |
|         |kubectl apply -f app-readinessProbe.yaml|              |app-readinessProbe.yaml|
|         |kubectl apply -f app-volumeMounts.yaml  |              |app-volumeMounts.yaml  |
|         |kubectl apply -f app-cronjob.yaml       |              |app-cronjob.yaml       |
|         |kubectl apply -f app-job.yaml           |              |app-job.yaml           |
|         |kubectl apply -f app-multicontainer.yaml|              |app-multicontainer.yaml|
|         |kubectl apply -f app-resources.yaml     |              |app-resources.yaml     |
|         |kubectl apply -f app-secret-env.yaml    |              |app-secret-env.yaml    |

