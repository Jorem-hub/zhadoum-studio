# Zhadoum Studio

Site public statique du studio. HTML et CSS uniquement : aucune dépendance, aucun JavaScript, aucune police distante, aucun formulaire, cookie, outil de suivi ou script tiers.

## Fichiers

- `index.html` : accueil du studio.
- `la-boule/index.html` : politique de confidentialité, avertissement et mentions légales de La Boule.
- `assets/style.css` : styles partagés, responsive et impression.
- `.nojekyll` : publication directe des fichiers statiques avec GitHub Pages.

## Aperçu local

Ouvrir `index.html` dans un navigateur. Pour reproduire les URL en dossiers de GitHub Pages, servir la racine avec un serveur HTTP local, puis visiter `/` et `/la-boule/`.

## Publication — après validation explicite uniquement

L’adresse professionnelle fournie est intégrée : 15 Rue Henri Cheneaux 13008 MARSEILLE.
Aucun push ni aucune activation de Pages ne doit intervenir avant validation du résultat par la propriétaire.

1. Vérifier et valider les pages, les coordonnées et le contenu juridique.
2. Après autorisation, créer un commit et pousser sur `main`.
3. Sur GitHub, ouvrir **Settings → Pages → Build and deployment**.
4. Sélectionner **Deploy from a branch**, branche **main**, dossier **/(root)**, puis **Save**.
5. Attendre le déploiement et vérifier les deux URL ci-dessous, ainsi que HTTPS.
6. Renseigner l’URL directe de La Boule dans Google AdMob.

Accueil : https://jorem-hub.github.io/zhadoum-studio/

URL stable de confidentialité : https://jorem-hub.github.io/zhadoum-studio/la-boule/

Conserver le dossier `la-boule/` pour ne pas casser cette URL. Les liens internes et les styles sont relatifs pour fonctionner sous le chemin du dépôt. Aucun domaine personnalisé n’est configuré.

Documentation : https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
