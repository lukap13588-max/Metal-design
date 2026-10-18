# METAL DESIGN 3D v2.1

## Neu: Direktauswahl in 3D
- Ein Geländerfeld direkt im 3D-Modell anklicken: Es wird im Feld-Dropdown ausgewählt und kann individuell befüllt werden.
- Pfosten im 3D-Modell anklicken: den ausgewählten inneren Pfosten um bis zu ±300 mm versetzen oder zurücksetzen.
- End- und Eckpfosten bleiben fix.
- Die individuellen Pfostenversätze werden in der JSON-Konfiguration exportiert.
- Drehbewegungen werden anhand der Pointer-Bewegung von Klicks unterschieden.

## Bedienung
1. Geländermodus auswählen und Maße einstellen.
2. Feld anklicken, Füllung auswählen, **Füllung für Feld übernehmen**.
3. Inneren Pfosten anklicken, **Ausgewählten Pfosten verschieben** einstellen, **Pfostenversatz übernehmen**.
4. Bei Bedarf Kamera drehen, zoomen, Bemaßungen und Vollbild verwenden.

## Vorhandene Funktionen
Gerade/L/U-Geländer; gerade/L/U-Stiegen; Material-, Farb- und Profilwahl; Klarglas, Milchglas, Lochblech, Streckmetall; Pfostenbefestigungen; Rundhandlauf; drei Umgebungen; Kameraansichten; PNG-, JSON- und überschlägiger CSV-Export.

## GitHub Pages
`index.html` und `README.md` in das Repository-Root hochladen bzw. ersetzen, Commit ausführen und GitHub Pages für Branch `main`, Ordner `/(root)` aktivieren. Internet für Three.js-CDN und WebGL-fähigen Browser erforderlich.

## Einschränkungen
Nur schematische Kundenvisualisierung, **keine Fertigungszeichnung oder statische Prüfung**. Auswahlkörper sind unsichtbare Trefferflächen; bei Überlappungen kann ein anderes Feld/Pfosten ausgewählt werden. Pfostenverschiebung wird entlang der jeweiligen Geländerseite berechnet; sehr enge Felder und Anschlussdetails sind nicht konstruktiv geprüft. Der JSON-Export ist noch keine Import-/Wiederherstellungsfunktion. Browsertest ausstehend.
