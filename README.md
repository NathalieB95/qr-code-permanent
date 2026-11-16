# QR Permanent — Générateur de QR code

Site statique (HTML/CSS/JS) hébergeable sur GitHub Pages.

## Fonctionnalités
- Encode n'importe quelle URL directement dans le QR code (pas de redirection, pas d'expiration).
- Téléchargement en PNG, JPEG, WebP, SVG, PDF, ou copie dans le presse-papiers.
- Options : taille, couleurs, marge, forme des points, nom de fichier.

## Utilisation locale
Ouvrez `index.html` dans un navigateur, ou servez le dossier :

```bash
python3 -m http.server 8080
```

## Déploiement sur GitHub Pages
1. Dans Settings → Pages, choisissez la branche `main` et le dossier racine.
2. Le site est disponible à `https://nathan0720.github.io/qr-code-permanent/`.

Aucune dépendance serveur, aucune clé API.
