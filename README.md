# Legal Website für eine Kinder-Tier-App

Statische Mini-Website für GitHub Pages mit:

- Startseite
- Deutsche Datenschutzerklärung
- Deutsches Impressum
- Englische Privacy Policy
- Englisches Legal Notice

## Wichtig

Die enthaltenen Rechtstexte sind vorbereitete Platzhalter und keine Rechtsberatung. Ersetze alle Platzhalter und prüfe die finalen Texte mit einem passenden Generator oder juristischer Beratung.

## Struktur

```text
/
├── index.html
├── robots.txt
├── .nojekyll
├── CNAME.example
├── assets/
│   └── style.css
├── de/
│   ├── datenschutz/index.html
│   └── impressum/index.html
└── en/
    ├── privacy/index.html
    └── legal-notice/index.html
```

## Platzhalter ersetzen

Suche in allen Dateien nach `{{` und ersetze mindestens:

```text
{{APP_NAME}}
{{OWNER_NAME}}
{{STREET_AND_NUMBER}}
{{POSTAL_CODE_AND_CITY}}
{{CONTACT_EMAIL}}
{{PHONE_NUMBER}}
{{VAT_ID_OR_NOT_APPLICABLE}}
{{DISPUTE_RESOLUTION_TEXT}}
{{THIRD_PARTY_SERVICES}}
```

## GitHub Pages veröffentlichen

1. Neues GitHub-Repository erstellen, z. B. `tierapp-legal`.
2. Alle Dateien aus diesem Ordner ins Repository hochladen.
3. In GitHub: `Settings` → `Pages` öffnen.
4. Als Source `Deploy from a branch` wählen.
5. Branch `main` und Ordner `/root` auswählen.
6. Speichern.
7. Nach kurzer Zeit ist die Seite unter folgender Struktur erreichbar:

```text
https://DEIN-GITHUB-NAME.github.io/tierapp-legal/
https://DEIN-GITHUB-NAME.github.io/tierapp-legal/de/datenschutz/
https://DEIN-GITHUB-NAME.github.io/tierapp-legal/de/impressum/
https://DEIN-GITHUB-NAME.github.io/tierapp-legal/en/privacy/
https://DEIN-GITHUB-NAME.github.io/tierapp-legal/en/legal-notice/
```

## Später eigene Domain verbinden

Wenn später eine Domain gekauft wird:

1. In GitHub unter `Settings` → `Pages` die Custom Domain eintragen.
2. Beim Domainanbieter die DNS-Einträge auf GitHub Pages setzen.
3. GitHub erzeugt oder nutzt eine Datei `CNAME`.
4. Danach können die URLs z. B. so aussehen:

```text
https://deine-domain.de/de/datenschutz/
https://deine-domain.de/de/impressum/
https://deine-domain.de/en/privacy/
https://deine-domain.de/en/legal-notice/
```

Die internen Links sind bewusst relativ aufgebaut, damit die Website sowohl mit GitHub-Subdomain als auch später mit eigener Domain funktioniert.
