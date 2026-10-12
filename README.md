# Atelier Effets MA2

Simulateur de layout grandMA2 pour s'entraîner aux effets sur téléphone : layout de carrés RGB, sélection dans l'ordre, effets dimmer et couleur (Form, Speed, Phase, Width, Groups, Blocks, Wings), Stomp, valeurs At, plusieurs pages de layout.

L'app tient dans un seul fichier, `index.html`. Pas de build : on modifie, on pousse, c'est en ligne.

## Mise en ligne (une seule fois)

1. Pousse ce dossier dans un dépôt GitHub public, par exemple `atelier-effets-ma2`.
2. Sur GitHub : Settings › Pages › Source « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. Une minute plus tard, l'app est sur `https://<ton-compte>.github.io/atelier-effets-ma2/`.

## Installation sur le téléphone (une seule fois)

Ouvre l'adresse dans Chrome, menu ⋮ › « Ajouter à l'écran d'accueil » (ou « Installer l'application »).

## Mettre à jour

`git push` sur `main`. GitHub Pages republie en une minute environ. Ferme puis rouvre l'app : la nouvelle version s'affiche. Sans réseau, l'app tourne sur la dernière version chargée.

## Fichiers

- `index.html` : toute l'app (interface, moteur d'effets, sauvegarde)
- `manifest.webmanifest` : nom, icône, plein écran
- `sw.js` : fonctionnement hors ligne
- `icons/` : icônes de l'écran d'accueil

## Sauvegarde

Les pages sont stockées sur le téléphone. Onglet Layout › Sauvegarde : « Copier la sauvegarde » ou « Enregistrer un fichier », puis « Importer » de l'autre côté. Importer remplace toutes les pages.
