# METAL DESIGN 3D v1.7

## Neu
- Wählbare Pfostenprofile: RHS 40×40×2, 50×50×3, 60×40×3 mm
- Wählbare Handlaufprofile: RHS 60×40×3, 40×40×2, 50×30×2 mm
- Dargestellte Schraubenköpfe an Fußplatten (rein optisch)
- Überschlägige Materialübersicht für Pfosten und Handlauf mit theoretischen kg/m
- CSV-Export (Semikolon getrennt, Excel-kompatibel)

## Weiterhin enthalten
Gerade/L/U-Balkongeländer; gerade/L/U-Stiegen; Materialien und Farben; Holz- und Stahlstufen; Maße, PNG/JSON-Export und 3D-Kamerasteuerung.

## GitHub Pages
`index.html` und `README.md` im Repository ersetzen, committen, Settings → Pages → Deploy from a branch → main / (root). Three.js wird online über jsDelivr geladen.

## Grenzen
**Nur Visualisierung, nicht zur Fertigung.** Materialliste umfasst aktuell nur Pfosten, Handlauf und Stückzahl der Platten; Füllungen, Verschnitt, Schweißnähte, Befestigungsmittelgewicht und Zuschnittoptimierung fehlen. Profile werden als massive Körper gerendert, theoretisches Gewicht wird separat über Hohlprofilquerschnitte berechnet. Rundhandlauf wird visuell nur angenähert. Keine Statik, Normprüfung, Geländersicherheit oder geprüften Anschlüsse. Stiegen-Materialberechnung noch nicht implementiert.
