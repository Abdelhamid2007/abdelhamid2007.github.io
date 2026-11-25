# abdelhamid2007.github.io

Racine du domaine GitHub Pages de Trésor (https://abdelhamid2007.github.io/tresor/).

- `.well-known/assetlinks.json` : lie l'app Android `io.github.abdelhamid2007.tresor` au site
  (plein écran sans barre d'adresse). Empreintes SHA-256 publiques : clé d'envoi
  (construction GitHub Actions) et, plus tard, clé de signature de Google Play.
- `index.html` : redirige vers `/tresor/`.
- `404.html` : toute adresse inconnue à la racine du domaine redirige aussi vers `/tresor/`.
- `.nojekyll` : désactive Jekyll pour que `.well-known/` soit publié tel quel.
