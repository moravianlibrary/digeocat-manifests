Tento repozitář slouží k specifikaci Docker image pro aplikaci Digeocat, která běží v Kubernetes clusteru od Moravské zemské knihovny.

### Status produkční aplikace Digeocat:
![production_status](https://argocd.osdd.mzk.cz/api/badge?name=digeocat-prod&showAppName=true&width=500)

### Jak změnit image
V souboru `production/kustomization.yml` změnit hodnoty `newName` a `newTag`. Commitnout v `main` větvi a synchronizovat stav souborů v Githubu s ArgoCD.
