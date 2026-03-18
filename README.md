# CCS-Netzwerk One-Pager (Jekyll / GitHub Pages)

Diese Datei enthält einen statischen Jekyll-One-Pager, der direkt über GitHub Pages veröffentlicht werden kann.

## Struktur

- `index.html` – komplette One-Pager-Seite
- `_config.yml` – minimale Jekyll-Konfiguration
- `assets/css/style.css` – Layout und Design
- `assets/img/members/` – Porträts und Platzhalter

## Veröffentlichung über GitHub Pages

1. Neues Repository anlegen.
2. Alle Dateien dieses Ordners in das Repository hochladen.
3. In **Settings → Pages** als Quelle **Deploy from a branch** wählen.
4. Branch **main** und Ordner **/(root)** auswählen.
5. Nach dem nächsten Push veröffentlicht GitHub Pages die Seite automatisch.

## Hinweise

- Die Seite nutzt keine zusätzlichen Jekyll-Plugins.
- Externe Abhängigkeiten wurden vermieden; vorhandene Porträts liegen lokal im Projektordner.
- Für einige Profile, deren öffentliche Institutionsseiten kein direkt abrufbares Porträt ausgaben, wurden neutrale Platzhaltergrafiken erzeugt.
