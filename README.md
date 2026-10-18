# METAL DESIGN 3D – Version 1.4

3D-Konfigurator für Balkongeländer und gerade Stahlstiegen, für Kundenpräsentationen im Browser.

## GitHub Pages

1. `index.html` und `README.md` in das Stammverzeichnis deines GitHub-Repositories hochladen (bestehende Dateien ersetzen).
2. Unter **Settings → Pages → Build and deployment** `Deploy from a branch` auswählen, Branch `main`, Ordner `/(root)`.
3. Nach dem Deployment die GitHub-Pages-URL öffnen. Falls die alte Version erscheint, Seite neu laden bzw. Cache leeren.

Die Seite nutzt **Three.js 0.160.1** und `OrbitControls` über ein Import-Map-CDN. Eine Internetverbindung ist erforderlich. Moderne Browser mit WebGL werden benötigt. Keine Installation oder Build-Schritte.

## Funktionen

### Balkongeländer (aus v1.3 übernommen)
- Gerade, L- und U-Form mit getrennten Seitenlängen
- Vertikale / horizontale Stäbe oder Glasfüllung
- Länge, Höhe, Pfostenabstand, aufgesetzte oder seitliche Befestigung
- Rechteck-/Rundhandlauf (schematisch)

### Gerade Stiege (neu)
- Geschosshöhe und Breite
- Automatische Anzahl Steigungen (gerundet aus Höhe / Ziel-Steigung)
- Auftritt und tatsächliche Steigung
- Holz- oder Stahlstufen
- Zwei Stahlwangen oder Mittelholm
- Geländer links, rechts, beidseitig oder ohne
- 3D-Drehung, Zoom, Front- und Gesamtansicht

### Gemeinsame Funktionen
- Material Stahl, Edelstahl, Aluminium; RAL 7016 / 9005 / 9016 / 7035 und Edelstahloptik
- Projektbezeichnung, PNG-Ansicht und JSON-Konfiguration exportieren

## Wichtige Grenzen

**Nicht zur Fertigung oder als Nachweis geeignet.** Modelle und Profile sind schematisch; es gibt keine geprüften statischen Berechnungen, Schweiß- oder Befestigungsnachweise, Geländer- und Treppennormprüfung oder verbindliche Materialmengen. Die Treppe stellt die obere Geschossfläche als letzte Austrittsfläche dar; die Anzahl gezeichneter Trittstufen ist daher um eins kleiner als die Anzahl Steigungen. Die Eingabe 'Tragmaterial' ändert die Oberflächenwirkung, nicht die konstruktive Eignung. Bei echten Projekten müssen Maße, zulässige Steigungen, Geländer, Lastannahmen und Anschlüsse fachlich geprüft werden.

## Technischer Stand

Einzelne HTML-Datei ohne Build-Prozess. Syntaxprüfung ist möglich, echte Grafikfunktion benötigt einen Browser mit WebGL und Internetzugang.
