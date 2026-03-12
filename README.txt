# Suivi pâturage — version simplifiée (offline)

## Démarrage rapide
1. Dézippez.
2. Ouvrez `index.html` dans un navigateur moderne (Chrome/Edge/Firefox).  
   - iOS/Safari fonctionne en général, mais si les exports ne se déclenchent pas, testez Chrome iOS ou un PC.

## Données
- Stockage local dans le navigateur (localStorage).
- Sauvegarde/Restaurer dans **Admin → Export / Sauvegarde**.

## Parcours conseillé
1. Onglet **Lots** : créez un lot + renseignez une composition (date d'effet).
2. Onglet **Saisie** : commencez par la **carte cliquable** (Parcelle → Paddock : sélection automatique), puis choisissez lot, date, entrée/sortie → **Valider**.
4. Admin → Export : CSV (événements, compositions, calendrier journalier).

## Mise à jour de la carte (découpage qui évolue)
- Admin → Référentiels → **Carte — mise à jour (GeoJSON)** : importez `parcelles.geojson` et/ou `paddocks.geojson`.
- Conseil : si possible, exportez les GeoJSON en **Lambert-93 / EPSG:2154** depuis QGIS pour une superposition parfaite avec le fond raster.
