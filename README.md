# kubernetes-manifests
| NAME    |                PROMPT                  |           DESCRIPTION        | EXAMPLE  |
|---------|----------------------------------------|------------------------------|----------|
|APP Deployment         |kubectl apply -f app.yaml               |This is the main YAML manifest for deploying application in Kubernetes. It typically includes specifications for pods, deployments, services, or other resources necessary for application to run.               |[app.yaml](https://github.com/serhii-cherkez/kubernetes-manifests/blob/main/yaml/app.yaml)  |
|Liveness probe         |kubectl apply -f app-livenessProbe.yaml |This YAML file contains the configuration for the liveness probe of application. A liveness probe is used to determine if the application is running properly. If the probe fails, Kubernetes will restart the container.|[app-livenessProbe.yaml](https://github.com/serhii-cherkez/kubernetes-manifests/blob/main/yaml/app-livenessProbe.yaml) |
|Readiness probe         |kubectl apply -f app-readinessProbe.yaml|This YAML file contains the configuration for the readiness probe of application. A readiness probe is used to determine if the application is ready to serve traffic. If the probe fails, the container will be removed from service until it passes.              |[app-readinessProbe.yaml](https://github.com/serhii-cherkez/kubernetes-manifests/blob/main/yaml/app-readinessProbe.yaml)|
|Volume mounts         |kubectl apply -f app-volumeMounts.yaml  |This YAML file defines any volume mounts that application needs. Volume mounts are used to make external storage or configuration files available to application containers.              |[app-volumeMounts.yaml](https://github.com/serhii-cherkez/kubernetes-manifests/blob/main/yaml/app-volumeMounts.yaml)  |
|Cron job         |kubectl apply -f app-cronjob.yaml       |This YAML file defines a cron job, which is a scheduled task that runs at specified intervals. It typically includes specifications for the job itself, such as the image to run and the schedule for execution.              |[app-cronjob.yaml](https://github.com/serhii-cherkez/kubernetes-manifests/blob/main/yaml/app-cronjob.yaml)       |
|One-time job         |kubectl apply -f app-job.yaml           |Similar to a cron job, this YAML file defines a one-time job to be run in Kubernetes. It specifies the image to use and any other necessary configuration for the job.              |[app-job.yaml](https://github.com/serhii-cherkez/kubernetes-manifests/blob/main/yaml/app-job.yaml)           |
|Multiple containers pod         |kubectl apply -f app-multicontainer.yaml|This YAML file defines a pod with multiple containers. Each container typically performs a different task, but they share the same network and storage resources within the pod.              |[app-multicontainer.yaml](https://github.com/serhii-cherkez/kubernetes-manifests/blob/main/yaml/app-multicontainer.yaml)|
|Resource requirements          |kubectl apply -f app-resources.yaml     |This YAML file specifies the resource requirements and limits for your application pods, such as CPU and memory constraints. It ensures that your application has the necessary resources to run efficiently without consuming too much of the cluster's resources.|[app-resources.yaml](https://github.com/serhii-cherkez/kubernetes-manifests/blob/main/yaml/app-resources.yaml)     |
|Environment variables         |kubectl apply -f app-secret-env.yaml    |This YAML file defines environment variables sourced from Kubernetes secrets that your application needs. Secrets are used to store sensitive information like passwords or API keys and make them available to your application securely.              |[app-secret-env.yaml](https://github.com/serhii-cherkez/kubernetes-manifests/blob/main/yaml/app-secret-env.yaml)    |

