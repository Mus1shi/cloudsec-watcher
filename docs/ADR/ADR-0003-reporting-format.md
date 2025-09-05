# ADR-0003 Reporting Format

## Contexte
Les destinataires sont techniques et non-techniques. Il faut un format lisible, diffable, et exportable.

## Décision
- **Markdown** comme format primaire.
- Export **HTML/CSV** envisagé plus tard (post-v0.2).
- Template **Jinja2** `templates/report.md.j2`.

## Conséquences
- Simple à versionner (Git).
- Conversion HTML possible via pandoc ou moteur interne plus tard.
