# Roadmap

## v0.1 – Préparation (docs & structure)
- Threat model, architecture, ADR
- Schéma d’alerte + template de rapport
- Config d’exemple + policies baseline
- CI minimale (lint docs/yaml)

## v0.2 – Collecte Azure (lecture seule)
- Auth Managed Identity / Device Code
- Collecte ressources minimales (Storage, KeyVault, NSG, SQL)
- Normalisation en alertes (schema v0)
- Génération rapport Markdown

## v0.3 – Détecteurs critiques & intégrations
- 10–15 règles Azure “haute valeur”
- Export HTML/CSV, notification Slack/Teams (webhooks)
- Packaging CLI (pip/pipx)

## v0.4 – Durcissement & QA
- Tests unitaires de règles
- Télémétrie/logs (JSONL)
- Signatures de policies / checksums
