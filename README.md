# bloppie.nl

Dit is de website van **Anna & Zelda**.

## Lokaal bekijken

1. Open `index.html` in je browser.
2. Als de YouTube videos niet laden via `file:///...`, start een lokale webserver en open `http://localhost:8000/`:

```sh
cd /home/rutger/bloppie.nl
python3 -m http.server 8000
```

## Aanpassen / nieuwe kaartjes

De pagina is een verzameling “kaartjes” in een grid (masonry/staggered). Nieuwe items voeg je toe door in `index.html` binnen `.container` een nieuwe `<section class="card ...">...</section>` toe te voegen.

## Domein

`CNAME` bevat de custom domain configuratie voor GitHub Pages.

