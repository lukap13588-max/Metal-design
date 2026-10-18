# METAL DESIGN 3D v1.5

Interaktiver 3D-Konfigurator für Balkongeländer und Stiegen. GitHub Pages geeignet.

## Neu in v1.5
- L-Stiege mit 90°-Podest, wählbarer Drehrichtung
- Steigungen bis zum Podest und Podesttiefe
- Automatische Berechnung der Steigungshöhe
- Zwei Stiegenläufe und Podest in der 3D-Ansicht
- JSON-Export inklusive neuer Parameter

## Bestehende Funktionen
- Gerade Stiege, Stahlwangen/Mittelholm, Holz- und Stahlstufen, Geländer links/rechts/beidseitig
- Gerade, L- und U-förmige Balkongeländer
- Farben, Materialien, Abmessungen, PNG und JSON Export, Kameraansichten

## GitHub Pages
1. ZIP entpacken und `index.html` und `README.md` im Repository ersetzen.
2. Commit durchführen.
3. Settings → Pages → Deploy from a branch → main / (root).
4. Seite nach Deployment neu laden.

## Technische Hinweise
- Lädt Three.js über jsDelivr. Internetverbindung nötig.
- Nur **schematische Kundenvisualisierung**. Keine geprüfte Geometrie für Produktion.
- Die Podestverbindung und Geländerübergänge sind schematisch und müssen vor der Fertigung konstruktiv geprüft werden.
- Keine statische oder baurechtliche Prüfung, keine verbindlichen Materialmengen.
