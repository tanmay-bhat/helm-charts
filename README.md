# helm-chart

### helm charts repo hosted in github

### 1. uptime kuma helm chart

Steps to install :

1. Add the helm repo with command :
  `helm repo add myrepo https://tanmay-bhat.github.io/helm-chart/`

2. Verify chart exists in the repo :
  `helm search repo uptime-kuma`

2. Install the chart :
   `helm install uptime myrepo/uptime-kuma`
