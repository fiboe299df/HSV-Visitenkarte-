# TODO

## Profilseite und Seitenaktionen
- [x] Die bestehende HSV-Profilseite aus der separaten HTML-Kopie als Website übernehmen; die Originaldatei `/home/ubuntu/upload/index(17).html` unverändert lassen.
- [x] Profil-, Kontakt-, Karriere- und bestehende Navigationsinhalte beibehalten.
- [x] Auf Mobilgeräten einen Schnellzugriff auf zentrale Seitenaktionen bereitstellen.
- [x] Eine druckfreundliche Ansicht der Profilseite bereitstellen.
- [x] Die vorhandene `noindex, nofollow`-Einstellung beibehalten.

## HSV-Spiele und Tickets
- [x] Die Spielekarte zeigt die letzten zwei bestätigten Spiele und die nächsten zwei Spiele der HSV-Erstmannschaft.
- [x] Den bestehenden öffentlichen OpenFootball-Feed verwenden und bei Nichterreichbarkeit die vorhandenen Fallback-Daten anzeigen.
- [x] Für Heim- und Auswärtsspiele offizielle HSV-Ticketeinstiege anbieten.
- [x] Spiele und Ticketportal in blauen aufklappbaren Bereichen darstellen.

## Lebenslauf und Vorschaubilder
- [x] Die bereitgestellte PDF als CV-Download anbieten; der Downloadname lautet `Lebenslauf.pdf`.
- [x] Alle drei PDF-Seiten als separate WebP-Vorschaubilder einbinden.
- [x] Das bereitgestellte PDF bytegleich übernehmen (SHA-256 `1fbc6260f9e14c8047ea1525d135b2a0348bf3d5b6ad7a1ee7c9b9c32cd1381f`).

## Profilbild und Stadionmotiv
- [x] Die links stehende Person aus dem Profilfoto entfernen, Lasses Identität erhalten und das HSV-Wappen großflächig in den Hintergrund setzen.
- [x] Ein Bild des Volksparkstadions als abgedunkeltes Hintergrundmotiv im Kopfbereich einbinden, sodass Text und Profilbild gut lesbar bleiben.

## Statische Bereitstellung
- [x] Die Website als statische Manus-Site bereitstellen; der aktuelle Zugriff ist auf den Eigentümer begrenzt (`owner`).
- [x] Öffentliche Sichtbarkeit entziehen und automatische Veröffentlichung deaktivieren.
- [x] Keine API-Schlüssel in öffentlichen HTML-Dateien hinterlegen.

## Bildfeinschliff
- [x] Das Profilbild bis zum oberen Brustbereich neu rahmen, sodass Hände und Unterarme vollständig aus dem Bild sind; Lasses Erscheinung und HSV-Wappen erhalten.
- [x] Ein großes HSV-Wappen über den gesamten Website-Hintergrund legen und harmonisch mit den Blautönen verschmelzen.

## Kontakt & Standort
- [x] Telefon-, E-Mail- und Standorticons in kräftigem HSV-Blau mit gutem Kontrast darstellen.

## Domain und externe Subdomains
- [x] Kostenlose externe Hosting-Subdomains ohne Personennamen prüfen: Cloudflare Pages (`*.pages.dev`), Netlify (`*.netlify.app`) und Vercel (`*.vercel.app`). Der konkrete Netlify-Kandidat `hsv-profilkarte.netlify.app` wurde bei der Site-Erstellung als verfügbar bestätigt; andere Kandidaten bleiben ungeprüft.
- [x] Netlify Free wurde gewählt; ein neues Projekt mit dem namensfreien Slug `hsv-profilkarte` wurde im kostenlosen persönlichen Team angelegt.
- [x] Die früheren Manus-Storage-Dateien wurden in `public/assets/` übertragen und alle HTML-Verweise darauf umgestellt. Der Download heißt `Lebenslauf.pdf`; PDF-SHA-256 stimmt bytegleich mit der bereitgestellten Datei überein; die drei WebP-Vorschaubilder sind vorhanden.
- [ ] Den öffentlichen Netlify-Deploy abschließen und HTTPS-Seite, Bilder sowie PDF verifizieren. Der erste Deploy wurde von Netlify mit „Skipped due to account credit usage exceeded“ abgewiesen; aktuell ist noch keine Website-Version live.

## Sprachen und Flaggen
- [x] Die vier Sprachen in der Profilkarte zusätzlich mit passenden Länderflaggen kennzeichnen: Deutsch, Englisch, Spanisch und Französisch.
- [x] Im bestehenden Dropdown zur Sprachauswahl passende Flaggen für alle sechs auswählbaren Sprachen anzeigen: Deutsch, Englisch, Französisch, Spanisch, Italienisch und Portugiesisch.

## HSV-Logos
- [x] Die vier HSV-Logos in Kopfmarke, Kopfzeilenmitte, Hero und Fußzeile jeweils als Kreis darstellen.
- [x] Jedem runden HSV-Logo eine einheitliche, HSV-blaue innere Kreiskontur geben; das Wappen selbst unverzerrt erhalten.
