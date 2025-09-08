
# Starter site — Morgane Bonsu

## Contenu
- `index.html` : accueil (hero + projets + notes)
- `projets.html` : liste de projets
- `notes.html` : blog/notes
- `a-propos.html` : bio + lien CV
- `contact.html` : contact
- `styles.css` : style minimal (Playfair Display + Inter)
- `assets/` : images, CV, favicon

## Personnalisation rapide
1. Ouvrez `index.html`, `projets.html`, `notes.html`, etc. et remplacez les textes et images (`assets/images/placeholder-*.jpg`).
2. Mettez votre vrai email dans `contact.html` et le footer.
3. Remplacez `assets/Morgane_Bonsu_CV.pdf` par votre vrai CV (même nom de fichier).
4. Couleurs : modifiez les variables CSS en haut de `styles.css` (accent = rouge sobre).

## Mise en ligne en 3 minutes (Netlify)
- Créez un compte sur Netlify.
- Glissez-déposez tout le dossier dans **Add new site > Deploy manually**.
- Assignez un nom de domaine (ex. `morganebonsu.netlify.app`).

## Alternative GitHub Pages
- Créez un repo, uploadez les fichiers à la racine.
- Dans Settings > Pages > Branch: `main` / root.
- Votre site sera en ligne à `https://votrecompte.github.io/nomdusite/`.

## SEO de base
- Mettez un vrai `og-image.jpg` (1200x630) et `favicon.png`.
- Éditez les balises `<title>` et `meta description` par page.
- Ajoutez vos réseaux (Instagram, LinkedIn, Substack) dans le footer.

## Évolutions possibles
- Convertir `notes.html` en blog dynamique (Substack/WordPress) et lier.
- Ajouter un formulaire (Netlify Forms) : <form name="contact" netlify>…</form>.
- Ajouter une page “Expos vues” en liste chronologique avec filtres.
