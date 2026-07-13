# Pilates-Kettwig-Demonstrator

Unverbindlicher Redesign-Entwurf für [pilates-kettwig.de](https://pilates-kettwig.de/) (Pilates Kettwig, Susanne Kemper, Ringstraße 1, 45219 Essen-Kettwig). Kein offizieller Auftritt; alle Inhalte und Fotos stammen aus dem bestehenden Auftritt. `noindex` auf allen Seiten.

## Stack

Vanilla HTML/CSS/JS nach dem Web-Starter-Kit. Design-System „Bewegungsfluss": Beere `#B42540`, Apricot `#F4C796`, dunkles Beeren-Bordeaux `#3A141F`, Creme `#FBF6EF`; Kreis-Motiv aus dem Logo, geschwungene Flusslinie als Zier. Schriften Bodoni Moda + Outfit (self-hosted, latin-subset).

## Bauen

Header, Footer und Demo-Leiste liegen als eine Quelle in `partials/` und werden per Marker-Kommentar in alle Seiten gesetzt:

```
node build-site.mjs
```

`partials/` und `build-site.mjs` werden nicht deployed. Nach CSS/JS-Änderungen die Cache-Version (`?v=N`) in allen HTML-Dateien hochzählen.

## Seiten

- `index.html`: One-Pager (Hero, Studio, Pilates, Tanz, Prävention, Team, Kontakt)
- `hinweise.html`: Über diesen Entwurf (Skala, Design, Vergleich, Referenzen)
- `impressum.html`, `datenschutz.html`, `404.html`
