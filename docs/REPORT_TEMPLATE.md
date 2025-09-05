# Report Template – Guide d’utilisation

## Variables attendues
- `generated_at` : datetime ISO8601
- `subscriptions` : liste d’IDs d’abonnements
- `alerts` : liste d’alertes conformes à `templates/alert.json.schema`
- Comptages : `critical_count`, `high_count`, `medium_count`, `low_count`
- Groupes : `top_alerts` (liste), `alerts_by_category` (dict)

## Sortie
- Format : Markdown
- Emplacement : `reports/`

## Qualité
- Aucune donnée sensible dans le rapport.
- Les recommandations doivent être actionnables (lien doc Azure plus tard).
