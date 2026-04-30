# Holistik Performance

Site one-page pour Kristof Robert · Coaching PNL · Longueuil, QC.

## Fichiers

- `index.html` — page principale (servi à la racine par GitHub Pages)
- `kristof.jpg` — portrait du hero
- `logo.svg` — logo de marque
- `Kristof Robert.html` — page « À propos » (longue bio)
- `Client Intake Questionnaire.html` — formulaire d'accueil client
- `Holistik Performance-print.html` — version imprimable

## Publier sur GitHub Pages

1. Créer un compte / une organisation GitHub nommée **`holistikperformance`**.
2. Créer un repo public nommé exactement **`holistikperformance.github.io`**.
3. Téléverser tous les fichiers de ce dossier (Add file → Upload files → glisser-déposer → Commit).
4. Aller dans **Settings → Pages** → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save.
5. Attendre 30 secondes. Le site sera à : **https://holistikperformance.github.io**

## Mettre à jour le site

Modifier `index.html` directement sur GitHub (crayon en haut à droite du fichier) ou via Git en local. Chaque commit redéploie automatiquement en ~30 sec.

## Domaine personnalisé (optionnel)

1. Acheter `holistikperformance.com` (ou `.ca`) — ~15 $/an.
2. Settings → Pages → Custom domain → entrer le domaine.
3. Chez le registraire (Cloudflare, Namecheap…), créer un enregistrement **CNAME** pointant vers `holistikperformance.github.io`.
4. Cocher « Enforce HTTPS » dans Settings → Pages.

## Notes

- Le site est entièrement statique — aucun build, aucun serveur requis.
- Bilingue FR / EN avec bascule en haut à droite (préférence sauvegardée en localStorage).
- Le formulaire de contact est actuellement décoratif (alerte en submit). Pour le rendre fonctionnel : brancher Formspree, Netlify Forms ou un service équivalent — ou simplement compter sur le bouton « Réserver sur Calendly » qui est déjà fonctionnel.
- Calendly : `https://calendly.com/kristofholistik` — vérifier que ce slug correspond bien au compte de Kristof.
