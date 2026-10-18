# METAL DESIGN 3D – Geländerkonfigurator

Interaktiver 3D-Web-Prototyp zur Präsentation von Balkongeländern.

## Funktionen
- Echtzeit-3D mit Maus- und Touchsteuerung (Three.js)
- Geländertypen: senkrechte Stäbe, waagrechte Stäbe, Glas
- Länge, Höhe, maximaler Pfostenabstand
- Stahl, Edelstahl, Aluminium sowie RAL-Farben und Edelstahloptik
- Eckiger oder runder Handlauf
- Automatische Aufteilung in Felder und Pfosten
- Export der Ansicht als PNG und Konfiguration als JSON
- Responsive Oberfläche für PC und Smartphone

## GitHub Pages veröffentlichen
1. Neues öffentliches GitHub-Repository erstellen, z. B. `metal-design-3d`.
2. `index.html` und `README.md` im Stammverzeichnis hochladen.
3. **Settings → Pages → Build and deployment → Deploy from a branch** auswählen.
4. Branch **main** und Ordner **/(root)** auswählen und speichern.
5. Nach der Veröffentlichung unter `https://DEIN-NAME.github.io/metal-design-3d/` öffnen.

## Lokal testen
Die Datei `index.html` mit einem lokalen Webserver öffnen, z. B. in VS Code mit Live Server oder per `python -m http.server 8000` und `http://localhost:8000`.

**Internetverbindung erforderlich:** Three.js und OrbitControls werden von jsDelivr geladen.

## Hinweis
Dies ist ein **Visualisierungsprototyp**. Er prüft keine Statik, Absturzsicherheit, Geländerabstände, Anschlüsse oder baurechtliche Normen. Profilabmessungen und Materialdarstellung sind beispielhaft. Nicht als Fertigungs- oder Montageplanung verwenden.
