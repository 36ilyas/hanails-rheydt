# HA's Nails Rheydt — Website

Statische Website für das Nagelstudio **HA's Nails** in Mönchengladbach-Rheydt
(Stresemannstraße 83, 41236 Mönchengladbach).

**Live:** https://36ilyas.github.io/hanails-rheydt/

## Aufbau

```
index.html          Startseite (Hero, Studio, Leistungen, Galerie, Preise, Anfahrt)
impressum.html      Impressum  — enthält noch auszufüllende Felder
datenschutz.html    Datenschutzerklärung
404.html            Fehlerseite
assets/css/         Stylesheet
assets/fonts/       Cormorant Garamond + Jost, lokal gehostet (kein Google-Request)
assets/img/         Bilder
assets/favicon.svg  Favicon
```

Kein Build-Schritt, kein Framework, keine Abhängigkeiten — reines HTML/CSS und ein
paar Zeilen JavaScript für das Mobilmenü und die Hervorhebung des heutigen Öffnungstages.

Lokal ansehen: die `index.html` einfach im Browser öffnen, oder

```bash
python -m http.server 8000
```

## Noch zu erledigen

- [ ] **Impressum vervollständigen:** Name der Inhaberin/des Inhabers, E-Mail-Adresse,
      ggf. USt-IdNr. Die betroffenen Stellen sind auf der Seite gelb markiert.
- [ ] **E-Mail-Adresse** in `datenschutz.html` ergänzen.
- [ ] **Echte Fotos** aus dem Studio statt der Stockfotos einsetzen (siehe unten).
- [ ] Preise und Öffnungszeiten gegenprüfen.

## Bilder

Alle Fotos sind **Symbolfotos von [Unsplash](https://unsplash.com/license)** und zeigen
weder Arbeiten noch Räume des Studios. Darauf wird im Footer und im Impressum hingewiesen.
Zum Austauschen genügt es, die Dateien in `assets/img/` unter gleichem Namen zu ersetzen —
und danach die `alt`-Texte und den Hinweis im Footer anzupassen.

| Datei | Verwendung | Quelle |
| --- | --- | --- |
| `hero-nagellack.jpg` | Hero | unsplash.com/photos/…5a05296c8f9a |
| `studio-modellage.jpg` | Abschnitt „Studio“ | unsplash.com/photos/…df63bc536371 |
| `galerie-babyboomer.jpg` | Galerie | unsplash.com/photos/…45dca7fa3a85 |
| `galerie-french.jpg` | Galerie | unsplash.com/photos/…fb02affea7a6 |
| `galerie-nailart.jpg` | Galerie | unsplash.com/photos/…6a2eaa771e5f |
| `galerie-pedikuere.jpg` | Galerie | unsplash.com/photos/…718bdfcd89c8 |
| `galerie-arbeitsplatz.jpg` | Galerie | unsplash.com/photos/…8727f6897d53 |

Die Karte im Abschnitt „Anfahrt“ nutzt Daten von
[OpenStreetMap](https://www.openstreetmap.org/copyright) (ODbL).

## Herkunft

Die Gestaltung stammt aus dem Claude-Design-Entwurf `HAs Nails Rheydt.dc.html`
(liegt lokal im Projektordner, ist nicht Teil dieses Repos) und wurde hier in
statisches HTML/CSS überführt.
