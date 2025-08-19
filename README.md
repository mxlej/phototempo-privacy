
# PhotoTempo – Privacy Policy Site (GitHub Pages)

Ce dépôt contient un mini-site statique pour héberger la politique de confidentialité de l’application PhotoTempo.

## Déploiement rapide (GitHub Pages)
1. Créez un **dépôt public** sur GitHub et uploadez ces fichiers à la racine.
2. Allez dans **Settings → Pages** et sélectionnez :
   - **Source** : `Deploy from a branch`
   - **Branch** : `main` (ou `master`) — dossier `/ (root)`
3. Patientez quelques secondes. L’URL publique sera affichée dans la section **Pages**.
4. Copiez-collez l’URL complète (par ex. `https://votrecompte.github.io/nom-du-repo/privacy-policy.html`) dans la Play Console.

## Fichier à fournir à Google
- Utilisez le lien **public** vers `privacy-policy.html` (pas de PDF, pas de login).

## Personnalisation
- Modifiez l’adresse e-mail de contact si besoin dans `privacy-policy.html`.
- Vous pouvez renommer le dépôt et le projet librement.
- Si vous avez un domaine personnalisé, ajoutez un fichier `CNAME` à la racine.

## Arborescence
- `index.html` : page d’accueil minimale
- `privacy-policy.html` : page de la politique de confidentialité
- `404.html` : page d’erreur
- `robots.txt`, `sitemap.xml` : SEO de base
- `.nojekyll` : désactive le traitement Jekyll
