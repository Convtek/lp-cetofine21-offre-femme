# Cétofine 21 — LP offre femme (production Convtek)

Landing page Cétofine 21 "Programmes minceur femme", servie sur **https://lp.cetofine.com/**
(GitHub Pages, domaine personnalisé déclaré par le fichier `CNAME`).
L'ancienne adresse de preview https://convtek.github.io/lp-cetofine21-offre-femme/ redirige vers le domaine.

- DNS côté client : `lp.cetofine.com CNAME convtek.github.io`, en DNS only dans Cloudflare
- Page de campagne : `noindex, nofollow` et `robots.txt` en `Disallow: /` (dans la source)
- Canonique, og:url et og:image sur `https://lp.cetofine.com/` (dans la source, rien à réécrire)
- Build du 2026-11-09 : identique au dossier de passation remis au dev (`1-site-a-publier`, `index-DhCM8s08.js`)

## Republier après une modification

Depuis `05-Exports/cetofine21-offre-femme` :

```
npm run build
```

puis copier le contenu de `dist/` ici sans écraser `README.md`, `.nojekyll`, `CNAME` ni `robots.txt`.
Ensuite commit et push sur `main`, puis repasser la recette sur https://lp.cetofine.com/.
Ne jamais supprimer `CNAME` : le domaine sauterait et la page ne répondrait plus.
