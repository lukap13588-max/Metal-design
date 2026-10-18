# METAL DESIGN 3D – v1.2

Interaktiver 3D-Balkongeländer-Konfigurator für Kundenpräsentationen.

## Start
`index.html` im Browser über einen lokalen Webserver öffnen oder auf GitHub Pages bereitstellen. Three.js wird über CDN geladen, daher ist eine Internetverbindung erforderlich.

## GitHub Pages
1. `index.html` und `README.md` in das Stammverzeichnis deines Repositories hochladen.
2. Unter **Settings → Pages** `Deploy from a branch`, `main`, `/(root)` auswählen.
3. Auf die veröffentlichte URL warten und bei Bedarf den Browsercache aktualisieren.

## Funktionen
- 3D-Modell mit Maus/Touch drehen und zoomen
- Senkrechte Stäbe, waagrechte Stäbe, Glasfüllung
- Maße: Länge, Höhe, maximaler Pfostenabstand
- Stahl, Edelstahl, Aluminium; RAL-Oberflächen
- Rechteck- oder Rundhandlauf
- Fußplatten aufgesetzt oder seitliche Befestigung
- Projektbezeichnung, Frontansicht, automatische Gesamtansicht
- PNG-Screenshot und JSON-Konfiguration exportieren

## Hinweise
Das Modell ist eine **unverbindliche Visualisierung**. Weder Statik, Geländerhöhe, Füllstab-Abstände, Glasdimensionierung noch Befestigung sind baurechtlich oder statisch geprüft. Profile sind schematisch. Nicht zur Fertigung freigeben.

## Technik
Eine HTML-Datei, Vanilla JavaScript, Three.js 0.160.1 mit OrbitControls über Import Map. Kein Buildprozess nötig.
