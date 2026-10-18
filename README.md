# METAL DESIGN 3D – v3.8 Qualitätsupdate

## Ziel
METAL DESIGN 3D bleibt ein **reiner 3D-Konfigurator**. Kein Angebots- oder Kalkulationsmodul.

## Korrekturen
- Rahmenvorlagen setzen jetzt auch individuelle Feldrahmen-Einstellungen zurück; gespeicherte Projekte bleiben unberührt.
- Zuschnittliste berücksichtigt das individuell eingestellte Pfostenprofil statt immer das Standardprofil.
- Lichtes Achsmaß wird mit dem tatsächlichen Standard-Pfostenprofil statt einer festen 90-mm-Pauschale geschätzt.
- Rahmenrücksprung wird bei kurzen Feldern begrenzt, um invertierte Geometrie zu vermeiden.
- Plausibilitätsprüfung für Ober-/Untergurt-Höhen und zu kleine Füllungsbereiche.
- Fehlermeldung bei zu breiten seitlichen Rahmenprofilen.
- Materialressourcen werden erst nach Entfernen der alten Geometrie freigegeben.

## Installation
`index.html` und `README.md` im Root des GitHub-Repositories ersetzen und committen. Three.js wird online geladen; Internetverbindung und WebGL sind erforderlich.

## Prüfung
JavaScript-Syntax und HTML-ID-Referenzen geprüft. Kein vollständiger interaktiver Browser-/WebGL-Funktionstest; nicht als vollständig fehlerfrei zertifiziert.

## Grenzen
Nur Vorplanung und Visualisierung. Gehrungen, Schweißnähte, Befestigungen, Glasbemessung und Tragfähigkeit müssen vor Fertigung gesondert geprüft werden. Die Zuschnittliste ist nicht fertigungstauglich.
