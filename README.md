# Strichzeichnung-vektorisieren

Deutschsprachige Anleitung zur Digitalisierung und Vektorisierung von Strichzeichnungen.

- Zeichnung auf einem weißen Blatt Papier mit Bleispift anfertigen
- Linien mit einem schwarzen Stift (z.B. Fineliner) nachziehen
- Zeichnung bildfüllend fotografieren
    - Zeichnung sollte einigermaßen gleichmäßig ausgeleuchtet sein (Schatten vermeiden)
    - Bild sollte scharf sein, ggf. Fotoapperat durch Bücherstapen stabilisieren
- Bild mit Gimp öffnen
- Bild drehen und beschneiden
- Rechtsklick -> Bild -> Modus -> Graustufen
- Reinzomen um zu ermitteln wie breit eine Strich ungefähr in Pixel ist (z. B. 18px)
- Rechtsklick -> Filter -> Kanten finden -> Differenz der Normalverteilung
    - Radius 1 auf das doppelte der Strichbreite (z. B. 36px)
    - Radius 2 auf die Strichbreite (z. B. 18px)
    - Normalisieren und invertieren anhacken
- Rechtsklick -> Farben -> Schwellwert
    - Automatisch, ggf. Linienstärke durch anpassen der unteren Grenze einstellen
- Rechtsklick -> Bild -> Modus -> Indiziert
    - Schwarz/Weiß-Palette
- ggf. mit Radiergummi kleine Unschönheiten manuell korrigieren
    - Tipp: Vorder und Hintergrundfarde können über den kleinen Pfeil getauscht werden
- Datei -> Exportieren als -> als PNG Datei speichern -> Exportieren
    - die PNG Export-Einstellungen sind egal

![Bild Öffnen und ggf. konvertieren](images/01.png)
![Auswahlwerkzeug](images/02.png)
![Bereich auswählen](images/03.png)
![Zuschneiden](images/04.png)
![Drehen](images/05.png)
![In Graustufen umwandeln](images/06.png)
![Linienbreite ermitteln](images/07.png)
![Differenz der Normalverteilung](images/08.png)
![Linienbreite einstellen](images/09.png)
![Schwellwert](images/10.png)
![Automatisch](images/11.png)
![Untergrenze nachjustieren](images/12.png)
![Bestätigen](images/13.png)
![Indizieren](images/14.png)
![In Schwwarz-/Weiß-Bild umwandeln](images/15.png)
![Radiergummi](images/16.png)
![Harter Pinsel](images/17.png)
![Pinselgröße](images/18.png)
![Unschönheiten manuell beseitigen](images/19.png)
![Schwarz und Weiß tauschen](images/20.png)
![Exportieren](images/21.png)
![Als PNG-Datei exportieren](images/22.png)
![Exportieren bestätigen](images/23.png)
![Bild in GIMP schließen](images/24.png)
