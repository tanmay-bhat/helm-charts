# helm-chart

### helm charts repo hosted in github

#### Steps to Add repo :

1. Add the helm repo with command :
  `helm repo add tanmay https://tanmay-bhat.github.io/helm-charts/`

2. Verify chart exists in the repo :
  `helm search repo chart_name`

### 1. uptime kuma helm chart: 
   `helm install uptime tanmay/uptime-kuma`

### 2. kube-ops-view helm chart: 
   `helm install kubeopsview tanmay/kube-ops-view`
