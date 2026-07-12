# moms-website

Website für **Expat Family Life** – eine statische Ein-Seiten-Website (`index.html`), self-contained ohne externe Dienste.

## 🌐 Website ansehen

**Live-Vorschau (GitHub Pages):** https://timfinkler.github.io/moms-website/

> Das Deployment läuft automatisch über GitHub Actions (`.github/workflows/deploy-pages.yml`):
> Bei jedem Push auf `main` wird die Seite neu veröffentlicht.
> Voraussetzung (einmalig): **Settings → Pages → Source: „GitHub Actions"**.

## Struktur

| Datei/Ordner | Inhalt |
|---|---|
| `index.html` | die komplette Website (eine Seite) |
| `images/` | Fotos (Buch, Autorin, Banner) |
| `fonts/` | lokale Schriftarten (kein Google Fonts) |
| `README.txt` | Anleitung zum Hochladen auf die eigene Domain (domainfactory/SFTP) |

## Änderungen

Texte stehen direkt in `index.html`, Fotos in `images/` einfach durch gleichnamige Dateien ersetzen. Kein Build-Schritt nötig.
