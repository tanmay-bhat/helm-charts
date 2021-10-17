# helm-chart

### helm charts repo hosted in github

#### Steps to Add repo :

1. Add the helm repo with command :
  `helm repo add myrepo https://tanmay-bhat.github.io/helm-chart/`

2. Verify chart exists in the repo :
  `helm search repo chart_name`

### 1. uptime kuma helm chart: 
   `helm install uptime myrepo/uptime-kuma`

### 2. kube-ops-view helm chart: 
   `helm install kubeopsview myrepo/kube-ops-view`
