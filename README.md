# FUGU! — landing

Site vitrine statique pour FUGU! (zéro dépendance, zéro build).

## Aperçu local
```bash
python3 -m http.server 8080   # puis http://localhost:8080
```

## Fichiers
- `index.html` — page d'accueil (hero, features, CTA).
- `privacy.html` — **brouillon** de politique de confidentialité (à finaliser ;
  l'URL servira aussi à remplir le champ « Privacy Policy » des stores et les
  déclarations de données AdMob).
- `style.css` — thème abysse (mêmes couleurs/typos que le jeu).
- `fugu.svg` — le poisson (repris du jeu).

## À faire avant le lancement
- Remplacer `contact@example.com` par le vrai email.
- Finaliser `privacy.html` (relecture) — requis par App Store / Google Play.
- Brancher les vrais liens de téléchargement sur les badges quand l'app est en ligne.
- Déployer (Netlify / Vercel / GitHub Pages — tout hébergeur statique convient)
  pour obtenir une URL publique (nécessaire pour la politique de confidentialité).
