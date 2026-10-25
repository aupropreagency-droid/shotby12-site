# SHOTBY12 — site officiel

Site vitrine de SHOTBY12, vidéaste et créateur de contenu sportif, en ligne sur https://shotby12.fr (indexable par les moteurs de recherche).

- `index.html` : page d’accueil en version claire
- `clair.html` : accès direct à la version claire
- `sombre.html` : version noire (bouton en bas à gauche pour changer de thème)
- `media/` : stories, reels 12's POV, icônes et photo (vidéos compressées en 540p / 720p)
- `support.js` : moteur d'affichage des pages

## Déploiement Cloudflare Pages
Projet relié à ce dépôt, sans commande de build, dossier de sortie : `/` (racine). Chaque push sur `main` republie le site.

Indexation : `robots.txt` autorise les moteurs et pointe vers `sitemap.xml` ; chaque page déclare https://shotby12.fr/ comme adresse canonique.
