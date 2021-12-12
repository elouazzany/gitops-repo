# GitOps Repo Exapmle using argoCD

the only manuel action is to bootstrap the **app of apps**
```bash
#!/bin/bash
kubectl apply -f app-of-apps.yml
```