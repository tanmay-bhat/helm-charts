## helm charts repo hosted in github

### Add repository :

1. Add the helm repo with command :
  `helm repo add tanmay https://tanmay-bhat.github.io/helm-charts/`

2. Verify chart exists in the repo :
  `helm search repo fluent-operator`

### Install Charts : 

### 1. fluent-operator helm chart: 
   `helm install fluent-operator tanmay/fluent-operator`

### 2. kube-ops-view helm chart: 
   `helm install kubeopsview tanmay/kube-ops-view`
   
### 3. uptime-kuma helm chart: 
   `helm install uptime tanmay/uptime-kuma`
