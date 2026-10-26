# TabaTimer
PWA de minuteur par séries (tabata, step, musculation…) pour l'EPS.

## Déploiement sur GitHub Pages
1. Créer un dépôt et déposer **tous** ces fichiers à la racine (index.html, manifest.webmanifest, sw.js, dossier icons/).
2. Settings → Pages → Source : *Deploy from a branch* → branche `main`, dossier `/ (root)`.
3. Ouvrir `https://<utilisateur>.github.io/<depot>/` puis « Installer » / « Ajouter à l'écran d'accueil ».

Pour publier une mise à jour, changer le numéro de version `V` dans sw.js (actuellement v3).

## Format CSV
`seance;n_serie;nom_serie;repetitions;type;libelle;duree_s;couleur`
Types : prepa, echauf, travail, recup, transition, repos, fc, debrief.
