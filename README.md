# SHOTBY12 — site (préproduction)

Site vitrine de SHOTBY12, vidéaste et créateur de contenu sportif. Version de travail, non indexée par les moteurs de recherche.

- `index.html` : version sombre
- `clair.html` : version claire (bouton en bas à gauche pour passer de l'une à l'autre)
- `media/` : stories, reels 12's POV, icônes et photo (vidéos compressées en 540p / 720p)
- `support.js` : moteur d'affichage des pages

## Déploiement Cloudflare Pages
Projet relié à ce dépôt, sans commande de build, dossier de sortie : `/` (racine). Chaque push sur `main` republie le site.

Avant la mise en ligne définitive : retirer `robots.txt`, la balise `noindex` et l'en-tête `X-Robots-Tag` dans `_headers`, remplacer les contenus entre crochets.
