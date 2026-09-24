# animal-sounds.de

Statische Website für die App „Tiergeräusche für Kinder“, gehostet über GitHub Pages unter https://animal-sounds.de.

## Struktur

```text
/
├── index.html          Landingpage (CSS inline, kein JavaScript, keine externen Ressourcen)
├── privacy.html        Datenschutzerklärung (#de / #en)
├── imprint.html        Impressum / Legal Notice (#de / #en)
├── 404.html            Fehlerseite
├── preview.jpg         Social-Media-Vorschau (1200 × 630)
├── robots.txt
├── sitemap.xml
├── CNAME               Custom Domain für GitHub Pages
└── assets/
    ├── img/            Von der Website genutzte, optimierte Bilder
    └── images/         Originalgrafiken, nur lokal (in .gitignore)
```

`privacy.html` und `imprint.html` nicht umbenennen, falls diese URLs in der Google Play Console oder in der App verlinkt sind.

Texte und Hinweise zur Landingpage stehen in `LANDINGPAGE-TEXTE.md`.

## Veröffentlichen

Änderungen auf `main` pushen. GitHub Pages (Settings → Pages → Deploy from a branch, `main`, `/root`) veröffentlicht automatisch.
