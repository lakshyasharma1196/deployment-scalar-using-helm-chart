# deployment-scalar-using-helm-chart
Deploy deployment scalar using helm chart on kubernetes
 
Use the below commands to verify the chart finally install it.

update ```env``` in values.yaml. it will be your namespace where you want to deploy crons.

```
cd deployment-scalar
helm lint .
helm template .
helm install --dry-run scalar .
helm install scalar .
```

