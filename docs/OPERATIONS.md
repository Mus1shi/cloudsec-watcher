# Operations

## Environnement
- Python 3.11+
- Pas de secrets en clair (variables d'env uniquement)

## Arbo utile
- Code : `/src`
- Doc : `/docs`
- Gabarits : `/templates`
- Config : `/config`

## Sorties
- Rapports : `/reports` (Markdown d'abord)

## Run local (plus tard)
- `python -m cloudsec_watcher ...` (placeholder)

## Secrets & Variables d'environnement
- Aucun secret en clair dans le dépôt.
- Utiliser des variables d'environnement (ex: `AZURE_TENANT_ID`, `AZURE_CLIENT_ID`, `AZURE_CLIENT_SECRET`) ou Managed Identity.
- Fichiers d'exemple fournis (`config/example.settings.yaml`) — ne jamais commiter un fichier réel de secrets.

