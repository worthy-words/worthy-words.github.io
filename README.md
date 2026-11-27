# Worthy Words

Kildekoden til nettsiden, bygget med [Hugo](https://gohugo.io/).

- `content/artikler/` – artikler
- `content/brev/` – åpne brev
- `content/om/` – Om-siden
- `static/` – bilder, PDF-er og `speil.txt`
- `layouts/` – sidens egne maler

Forhåndsvisning lokalt: `hugo server`. Bygg: `hugo --gc --minify`.
Ved push til `main` bygges siden og publiseres til GitHub Pages
(`.github/workflows/hugo.yml`).
