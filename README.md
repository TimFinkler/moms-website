# moms-website

Website für **Expat Family Life** – eine statische Ein-Seiten-Website (`index.html`), self-contained ohne externe Dienste.

## 🌐 Website ansehen

**Live:** https://stephanie-finkler.de (auch erreichbar über https://www.stephanie-finkler.de)

> Das Deployment läuft automatisch über GitHub Actions (`.github/workflows/deploy-pages.yml`):
> Bei jedem Push auf `main` wird die Seite neu veröffentlicht.
>
> Hosting: GitHub Pages (Settings → Pages → Source „GitHub Actions", Custom Domain `stephanie-finkler.de`).
> Die Domain liegt bei domainfactory und zeigt per DNS auf GitHub Pages
> (A-Record der Hauptdomain auf `185.199.108.153`, CNAME `www` auf `timfinkler.github.io`).
> E-Mail läuft unabhängig davon weiter über Microsoft 365 (MX-Einträge bei domainfactory).

## Struktur

| Datei/Ordner | Inhalt |
|---|---|
| `index.html` | die komplette Website (eine Seite) |
| `images/` | Fotos (Buch, Autorin, Banner) |
| `fonts/` | lokale Schriftarten (kein Google Fonts) |
| `README.txt` | ursprüngliche Anleitung für SFTP-Upload zu domainfactory (überholt – das Hosting läuft jetzt über GitHub Pages, siehe oben) |

## Änderungen

Texte stehen direkt in `index.html`, Fotos in `images/` einfach durch gleichnamige Dateien ersetzen. Kein Build-Schritt nötig.
