Tento repozitář slouží k specifikaci Docker image pro aplikaci Digeocat, která běží v Kubernetes clusteru od Moravské zemské knihovny.

### Status produkční aplikace Digeocat:
![production_status](https://argocd.osdd.mzk.cz/api/badge?name=vdc-digeocat-prod&showAppName=true&keepFullRevision=true&width=600)

### Jak změnit image
- V souboru `production/kustomization.yml` změnit hodnoty `newName` a `newTag`. 
- Commitnout změny v `main` větvi
- Nová verze image se nasadí automaticky (cca pár minut), ale lze také synchronizovat novou specifikaci ručně v [ArgoCD](argocd.osdd.mzk.cz) 
