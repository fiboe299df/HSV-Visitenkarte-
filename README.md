# Digitale Visitenkarte – Lasse Böttcher | HSV

## Lokal öffnen
Alle Dateien in **einem Ordner** lassen, dann `Lasse-Boettcher-HSV-Visitenkarte.html` im Browser öffnen.

Besser (Wallet, Clipboard, Manifest):

```bash
npx --yes serve .
```

Dann die angezeigte URL öffnen (z. B. http://localhost:3000).

## GitHub Pages
1. Neues Repository erstellen (öffentlich).
2. Inhalt dieses Ordners pushen (HTML, PDF, `manifest.webmanifest`, `assets/`).
3. Settings → Pages → Source: Deploy from branch `main` / Folder `/ (root)`.
4. Nach 1–2 Minuten: `https://<user>.github.io/<repo>/Lasse-Boettcher-HSV-Visitenkarte.html`

Optional: Datei in `index.html` umbenennen, dann reicht die Repo-URL.

## Netlify
1. [app.netlify.com](https://app.netlify.com) → Add new site → Deploy manually  
   **oder** Git-Repo verbinden.
2. Publish directory = Ordner mit der HTML-Datei.
3. Fertig – HTTPS-URL nutzen für Wallet & PWA.

## Spiele-Daten aktualisieren
In der HTML-Datei den Block `const HSV_MATCHES = { ... }` suchen und anpassen:

- `last` – letztes Ergebnis  
- `next` – nächstes Spiel (erscheint auch auf dem blauen Button)  
- `upcoming` – weitere Termine  
- `table` – Platz / Punkte / Spiele  

Speichern, fertig. Kein Build nötig.

## Assets ersetzen (echte Fotos)
| Datei | Verwendung |
|--------|------------|
| `assets/hsv-logo.webp` (+ `.png`) | Logo |
| `assets/lasse-profil.webp` | Profilbild |
| `assets/lasse-hero.webp` | Hero-Foto (optional) |
| `assets/volksparkstadion.webp` | Hintergrund / Hero |
| `assets/cv-preview-1.webp` / `2` | CV-Modal-Vorschau |
| `CV-Lasse-Boettcher-August.pdf` | CV-Download |

Empfehlung: echte Fotos als WebP exportieren (ca. 80–120 KB), gleiche Dateinamen behalten.

## Ticketportal
Offiziell: https://www.hsv.de/tickets
