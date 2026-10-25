# SaaS RevPilot — basé sur le gabarit original

## Fichiers
- `index.html` : application avec Overview, Revenue Bridge, Monthly Revenue Close et AI Insights.
- `saas_revpilot_data.json` : données extraites des onglets SAAS CSP, SAAS CSTLO et SAAS SYGED, avec montants mensuels originaux.
- `SAAS GED - GabaritVF(1).xlsx` : copie inchangée du classeur fourni.

## Mise à jour GitHub Pages
1. Téléversez `index.html` et `saas_revpilot_data.json` à la racine du dépôt.
2. Ne supprimez pas le dépôt et ne remplacez pas le classeur Excel original.
3. Cliquez sur Commit changes.
4. Ouvrez le site et faites Ctrl+F5.

## Fonctionnalités ajoutées
- Navigation par modules.
- Revenue Bridge 2026→2027 et 2027→2028, basé sur les écarts annuels client/produit.
- Checklist Monthly Revenue Close et export CSV.
- AI Insights : commentaires déterministes calculés à partir des données sources.

## Limites
- Les catégories Revenue Bridge sont des inférences par client/produit et doivent être validées métier.
- AI Insights n'appelle pas encore un modèle IA externe.
- Les fichiers joints ne sont pas stockés durablement ; pas de backend, OCR ou connexion SharePoint.
- Les chiffres de forecast sont issus du classeur source, sans hypothèses de contrat supplémentaires.
