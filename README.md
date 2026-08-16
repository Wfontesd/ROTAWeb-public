# Rules of the Abyss — Web Build

Dépôt public du build jouable web de **Rules of the Abyss**.

## Jouer

Adresse prévue : **https://wfontesd.github.io/ROTAWeb-public/**

Le build de production est stocké à la racine de la branche [`gh-pages`](https://github.com/Wfontesd/ROTAWeb-public/tree/gh-pages). Il contient l'application Babylon.js/React compilée, ses assets, le manifeste PWA, le service worker, `.nojekyll` et une page `404.html` compatible avec GitHub Pages.

## Activation initiale de GitHub Pages

GitHub demande une activation administrative unique pour chaque nouveau site :

1. ouvrir **Settings → Pages** ;
2. sélectionner **Deploy from a branch** ;
3. choisir la branche **gh-pages** et le dossier **/(root)** ;
4. enregistrer.

Lien direct : https://github.com/Wfontesd/ROTAWeb-public/settings/pages

Une fois cette activation faite, le site est servi directement depuis `gh-pages`. Le workflow **Publish playable build** reste aussi disponible manuellement dans l'onglet Actions pour redéployer l'artefact.

## Contenu publié

- menu, choix de classe et carte de progression ;
- combats automatiques déterministes ;
- Codex ordonné et réécriture à l'Encre du Néant ;
- Brûlure, Poison, Gel et réactions en chaîne ;
- ennemis, élite, boss, récompenses, boutique, événements et sanctuaire ;
- VFX, audio procédural, interface, sauvegarde locale et options d'accessibilité.
