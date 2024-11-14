Tento repozitář slouží k specifikaci Docker image pro aplikaci Digeocat, která běží v Kubernetes clusteru od Moravské zemské knihovny.

### Status produkční aplikace Digeocat:
![production_status](https://argocd.osdd.mzk.cz/api/badge?name=vdc-digeocat-prod&showAppName=true&keepFullRevision=true&width=600)

### Jak změnit image
- V souboru `production/kustomization.yml` změnit hodnoty `newName` a `newTag`. 
- Commitnout změny v `main` větvi
- Sledovat který commit hash je v produkci dle README.md NEBO synchronizovat stav souborů v Githubu s ArgoCD 
