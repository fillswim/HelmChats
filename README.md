# HelmChats

### Create package
```bash
helm package My-Template-HelmChart/
```

### Update index.yaml
```bash
helm repo index --url https://fillswim.github.io/HelmChats/ .
```

### Add helm repository
```bash
helm repo add fillswimrepo https://fillswim.github.io/HelmChats/
```

### Update helm repository
```bash
helm repo update
```

### View repository
```bash
helm search repo fillswimrepo
```

### View repository
```bash
helm search repo fillswimrepo
```

### Install Nginx
```bash
helm install my-nginx fillswimrepo/my-template-helmchart -f HelmChart_values_nginx.yaml
```

### Install Nginx
```bash
helm upgrade my-gifservice fillswimrepo/my-template-helmchart -f /home/fill/K8SManifests/HelmChart_values_gifservice.yaml
```