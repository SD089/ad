# AD Bau GmbH – Website

Karriere-Website der AD Bau GmbH, München. Reines HTML, kein Build nötig.

## Dateien

| Datei | Inhalt |
| --- | --- |
| `index.html` | Die Website (Deutsch, Englisch, Bosnisch, Serbisch, Polnisch) |
| `impressum.html` | Impressum, rot markierte Stellen noch ausfüllen |
| `datenschutz.html` | Datenschutzerklärung, Anschrift noch ausfüllen |
| `assets/` | Logo und Symbol |
| `favicon.png` | Symbol im Browser-Tab |

## Bei GitHub hochladen

1. Auf github.com einloggen, oben rechts **+** → **New repository**.
2. Name eingeben, z. B. `adbau`, **Public** wählen, **Create repository**.
3. Auf **uploading an existing file** klicken.
4. Den **Inhalt** dieses Ordners hineinziehen (nicht den Ordner selbst), sodass `index.html` ganz oben liegt.
5. **Commit changes** klicken.

## Website einschalten (GitHub Pages)

1. Im Repository auf **Settings** → **Pages**.
2. Bei **Branch** `main` und `/ (root)` wählen, **Save**.
3. Nach ein bis zwei Minuten ist die Seite unter `https://DEINNAME.github.io/adbau/` erreichbar.

## Eigene Domain (z. B. adbaugmbh.de)

1. Unter **Settings** → **Pages** → **Custom domain** die Domain eintragen und speichern.
2. Beim Domain-Anbieter vier A-Einträge auf `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` setzen und für `www` einen CNAME auf `DEINNAME.github.io`.
3. Wenn GitHub die Domain geprüft hat, **Enforce HTTPS** anhaken.

## Vor dem Start erledigen

- `impressum.html`: Anschrift, Telefon, HRB-Nummer, USt-IdNr. eintragen.
- `datenschutz.html`: Anschrift eintragen und den Text rechtlich prüfen lassen.
- Texte zu Vorteilen (fester Vertrag, pünktlicher Lohn, Probetag) prüfen.
- Übersetzungen von einem Muttersprachler gegenlesen lassen.
