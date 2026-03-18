# ccs-netzwerk

Dokumentation des DFG-Netzwerk "Potenziale und Herausforderungen der Computational Communication Science am Beispiel von Online-Protest".

## Jekyll + GitHub Pages Setup

Diese Repository-Vorlage ist fuer GitHub Pages mit Jekyll vorbereitet.
Der Seiteninhalt liegt unter `docs/`.

### Struktur

- `docs/index.md`: Startseite
- `docs/_config.yml`: Jekyll-Konfiguration
- `Gemfile`: Abhaengigkeiten fuer lokale Entwicklung
- `.github/workflows/pages.yml`: Build + Deploy ueber GitHub Actions

### Lokal starten

Voraussetzungen:

- Ruby 3.x
- Bundler (`gem install bundler`)

Dann im Repository-Root:

```bash
bundle install
bundle exec jekyll serve --source docs --destination docs/_site --livereload
```

Die Seite ist dann standardmaessig unter `http://127.0.0.1:4000` erreichbar.

### Deployment auf GitHub Pages

1. Repository nach GitHub pushen.
2. In GitHub unter `Settings -> Pages` als Quelle `GitHub Actions` waehlen.
3. Der Workflow in `.github/workflows/pages.yml` deployed bei Push auf `main` automatisch.

### Inhalte bearbeiten

- Seiten in `docs/` als Markdown-Dateien anlegen.
- Navigation/Theme-Einstellungen in `docs/_config.yml` anpassen.
