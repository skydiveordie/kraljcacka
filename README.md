# Kralj Čačka — sajt

Naslovna stranica sajta kantautora i slikara Kralja Čačka.

## Struktura

```
index.html        naslovna stranica (HTML + CSS u jednom fajlu)
tekstovi.html     stranica TEKSTOVI (albumi, pesme i tekstovi su u samoj stranici)
img/
  hero.jpg        pozadinska fotografija
  logo.webp       logo
  vesti.jpg       slika za sekciju VESTI (prikazuje se na hover)
  muzika.jpg      slika za sekciju MUZIKA
  tekstovi.jpg    slika za sekciju TEKSTOVI
  slikarstvo.jpg  slika za sekciju SLIKARSTVO
  albumi/         omoti albuma za stranicu TEKSTOVI
```

## Dodavanje pesama

Tekstovi su u `tekstovi.html`, u bloku `<script type="application/json" id="data">`.
Svaki album ima `title`, `year`, `cover` i spisak `songs`; svaka pesma ima `title` i `stanzas` (strofe kao nizovi stihova).

## Objavljivanje preko GitHub Pages

1. Postaviti sve fajlove u koren repozitorijuma.
2. Settings → Pages → Source: *Deploy from a branch*, grana `main`, folder `/ (root)`.
3. Sajt će biti dostupan na `https://<korisnik>.github.io/<repozitorijum>/`.

## Šta treba dopuniti

- Linkove ka profilima (Instagram, Facebook, Patreon, YouTube, Spotify, Apple Music) u `index.html` i `tekstovi.html` — trenutno vode na početne stranice servisa.
- Stranice `vesti.html`, `muzika.html`, `slikarstvo.html` i `bio.html` — linkovi već vode na njih, ali još ne postoje.
