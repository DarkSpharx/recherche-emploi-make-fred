# Automatiser sa recherche d'emploi Data Analyst

Ce dépôt rassemble les livrables du projet d'automatisation avec Make et l'API JSearch (OpenWeb Ninja).

## Livrables

- [`presentation.txt`](presentation.txt) — document de présentation et support de démonstration, à compléter avec les résultats réels.
- [`scenario.json`](scenario.json) — emplacement réservé à l'export Blueprint du scénario Make.
- [`captures/`](captures/README.md) — emplacement des captures d'écran du scénario, du tableau, des alertes Discord et de la planification.

## Avant de publier

Remplacez le contenu provisoire de `scenario.json` par l'export Blueprint Make, puis remplacez la clé JSearch (`ak_…`) et l'URL du webhook Discord par `***`. Vérifiez avec une recherche que `ak_` et `discord.com/api/webhooks` ne figurent plus dans le Blueprint. Vérifiez également les captures et le document : aucun mot de passe, clé, webhook ou renseignement personnel ne doit être publié.

Le Google Sheet doit être partagé en lecture seule et son lien ajouté dans `presentation.txt`. Ne placez aucune clé API ni URL de webhook dans ce dépôt. `scenario.json` contient actuellement un texte de remplacement, pas un Blueprint importable.
