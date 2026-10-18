# METAL DESIGN 3D – v1.9

Interaktiver WebGL-Konfigurator für Geländer und Stiegen.

## Neu in 1.9
- Rundhandlauf wird als Zylinder statt als rechteckiger Balken dargestellt
- Klarglas und Milchglas: Wahl zwischen schematischen Glasklemmen und Rahmenprofilen
- Eckhandläufe mit visuellen Verbindungskappen (keine fertigungstauglichen Gehrungen)
- Drei wählbare 3D-Umgebungen: dunkles Studio, helles Studio, Außenbereich
- Neue Konfigurationswerte im JSON-Export

## Weiterhin enthalten
Gerade/L/U-Balkongeländer; senkrechte und waagrechte Stäbe, Glas, Lochblech, Streckmetall; Profile, Farben, Maße und Befestigungen. Gerade/L/U-Stiegen mit Holz-/Stahlstufen, Podesten und Geländern. Kameraansichten, Bemaßungen, Vollbild, PNG-/JSON-Export sowie bisherige überschlägige CSV-Materialübersicht.

## Veröffentlichung mit GitHub Pages
`index.html` und `README.md` in das Stammverzeichnis des Repositories hochladen und bestehende Dateien ersetzen. In **Settings → Pages** Branch `main` und `/(root)` einstellen. Die Seite braucht WebGL und eine Internetverbindung (Three.js-CDN).

## Einschränkungen
**Kundenvisualisierung, keine Fertigungsplanung.** Glasklemmen und Eckkappen sind nur optische Platzhalter; Glasstärken, Glaslagerung, Standsicherheit, Statik, Normen und Auflager müssen fachlich geprüft werden. Bei L-/U-Stiegen sind Podestanschlüsse schematisch. Ein Live-Browsertest der Version 1.9 wurde nicht durchgeführt.
