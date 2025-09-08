MONOREAU — Site éditable (sans code)

1) Mettre en ligne (Netlify)
- Crée un compte sur Netlify.
- "Add new site" > "Import from Git" (recommandé) ou "Deploy manually".
- Si tu importes depuis GitHub, active "Identity" et "Git Gateway" dans Netlify > Identity.
- Ajoute ton email en tant qu'utilisateur (Identity > Invite users).

2) Accès à l'admin (CMS)
- Une fois le site en ligne, va sur /admin (ex: monoreau.netlify.app/admin).
- Connecte-toi via Netlify Identity (email + lien magique).
- Tu pourras éditer les listes depuis "Notes" et "Projets".
- Enregistre > publie : le fichier JSON est mis à jour, les pages lisent ces données en direct (via JS).

3) Nom de domaine & mails
- Achète "studio-monoreau.fr" (OVH, Cloudflare, etc.).
- Dans Netlify > Domain settings > Add custom domain.
- Pour les emails (studio@monoreau.fr / contact@monoreau.fr) : utilise Google Workspace, Zoho Mail ou Infomaniak (MX à configurer).

4) Instagram / lien en bio
- Après déploiement, tu as une URL partageable (ex: https://monoreau.netlify.app).
- Ajoute-la à ta bio Instagram.
- Les mises à jour se font depuis /admin, instantanément après publication.

5) Modifier le design
- Ouvre styles.css pour couleurs/typographies.
- Les textes des pages (Accueil, À propos, Contact) sont dans les .html.
- Les listes de notes/projets se modifient via l'admin (fichiers JSON).

Astuce: pour un blog complet avec pages de détail, on pourra ajouter des "post.html?slug=..." plus tard.

Note: Branding MONOREAU — Paris. Emails placeholders: studio@monoreau.fr, contact@monoreau.fr.

Variant: Signature — overlay title set to 'MONOREAU' only; location removed from footer.

Footer updated with 'Paris — London — New York'. Hero overlay still shows 'MONOREAU' only.
