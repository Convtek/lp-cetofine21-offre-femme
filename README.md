# Cétofine 21 — LP offre femme (preview Convtek)

Preview de partage de la landing page Cétofine 21 "Programmes minceur femme", en cours de validation.
Page en `noindex`, robots.txt bloquant, aucun tracking envoyé.

URL : https://convtek.github.io/lp-cetofine21-offre-femme/

## Republier après une modification

Depuis `05-Exports/cetofine21-offre-femme` :

```
npm run build
```

puis copier le contenu de `dist/` ici (sans écraser `README.md`, `.nojekyll` ni `robots.txt`),
et dans `index.html` : remettre la balise `<meta name="robots" content="noindex, nofollow" />`
et remplacer `https://lp.cetofine.com/` par l'URL ci-dessus (canonique, og:image, og:url).
Ensuite commit et push sur `main`.
