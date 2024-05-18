| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| --- | --- | --- | --- |
| app-readinessProbe | Readiness Probe | A readiness probe for your application | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts | Volume Mounts | Mount a volume to your application | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
| app-cronjob | CronJob | A CronJob that runs your application every minute | [app-cronjob.yaml](./yaml/app-cronjob.yaml) |
| app-job | Job | A Job that syncs a volume with a GCS bucket | [app-job.yaml](./yaml/app-job.yaml) |
| app-multicontainer | Multi-container Pod | A Pod with multiple containers | [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources | Resources | Resource limits, liveness and readiness probes, and exposed ports for your application | [app-resources.yaml](./yaml/app-resources.yaml) |
| app-secret-env | Secret Environment Variables | Set environment variables from a Secret in a Pod | [app-secret-env.yaml](./yaml/app-secret-env.yaml) |
| app | App | A Deployment for your application | [app.yaml](./yaml/app.yaml) |
| app-livenessProbe | Liveness Probe | A liveness probe for your application | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |