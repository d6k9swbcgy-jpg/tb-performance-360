# TB PERFORMANCE 360 – Web-App-Prototyp

## Inhalt
- `index.html`: App-Oberfläche und Funktionen
- `manifest.webmanifest`: PWA-Metadaten
- `sw.js`: einfacher Offline-Cache

## Lokal testen
`index.html` im Browser öffnen. Für die Installation als PWA muss die App über HTTPS oder localhost ausgeliefert werden.

## Auf dem iPhone installieren
1. Die Dateien auf einen HTTPS-Webhost laden (z. B. eigenen Webspace oder einen Static-Hosting-Dienst).
2. Die veröffentlichte URL in Safari öffnen.
3. Teilen → „Zum Home-Bildschirm“ bzw. „Zum Home-Bildschirm hinzufügen“.
4. Die Web-App über das neue Symbol starten.

## Wichtige Grenzen dieses Prototyps
- Trainings-, Schicht- und Profildaten werden nur lokal im Browser gespeichert.
- Garmin ist noch NICHT verbunden; angezeigte Gesundheitswerte sind Platzhalter.
- Für Garmin Connect ist ein genehmigter API-Zugang sowie ein sicherer Backend-Server mit OAuth-Flow erforderlich. Garmin-Zugangsdaten oder Tokens dürfen nicht in den HTML-/JavaScript-Code eingebaut werden.
- Es gibt noch keine Benutzerkonten, Cloud-Synchronisierung, Push-Mitteilungen oder medizinisch validierte Trainingsentscheidungen.
- Keine medizinische Diagnose: Trainingsempfehlungen müssen konservativ sein und Warnsignale berücksichtigen.
