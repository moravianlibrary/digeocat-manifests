Tento repozitář slouží k specifikaci Docker image pro aplikaci Digeocat, která běží v Kubernetes clusteru od Moravské zemské knihovny.

### Status produkční aplikace Digeocat:
![production_status](https://argocd.osdd.mzk.cz/api/badge?name=digeocat-prod&showAppName=true&width=500)

### Jak změnit image
API: V souboru `patch-image-api.yml` změnit hodnotu `spec.template.spec.containers.image`.

Frontend: Stejně jako pro API, ale v souboru `patch-image-frontend.yml`.