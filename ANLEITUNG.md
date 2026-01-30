# Aikido DAB Lern-App - Anleitung

## Installation

### Browser-Version
1. `aikido-schwachpunkte.html` in einem Ordner speichern
2. Mit Browser öffnen (Chrome, Firefox, Safari, Edge)
3. Funktioniert sofort - alle Daten lokal gespeichert

### Als App auf dem Handy (PWA)
**Android (Chrome):**
1. Im Browser öffnen
2. Menü → "Zum Startbildschirm hinzufügen"
3. Icon erscheint - öffnet wie native App

**iOS (Safari):**
1. Im Browser öffnen
2. Teilen-Button → "Zum Home-Bildschirm"

## Funktionen

### Techniken üben
- **Vorderseite:** Technik, Variation, Angriff (japanisch)
- **Rückseite:** Video-Links
- **Bewertung:** Kann ich / Geht so / Schwer
- **Filter:** Nach Gürtelfarbe
- **Schwachpunkte:** Zeigt nur Karten die wiederholt werden müssen
- **Prüfung:** Random-Test mit Auswertung

### Angriffsnamen lernen
- **Vorderseite:** Angriff (japanisch)
- **Rückseite:** Angriff (deutsch)
- **Bewertung:** Kann ich / Kann ich nicht
- **Filter:** Nach Gürtelfarbe
- **Schwachpunkte:** Zeigt nur Karten die wiederholt werden müssen

### Prüfungsmodus
1. Gürtelfarbe wählen
2. "Prüfung" klicken
3. Alle Techniken durchgehen (random)
4. Bewertung: Gewusst / Nicht gewusst
5. Endergebnis: Prozent + Aufschlüsselung

### Admin-Bereich
**Login:** Admin-Tab → Passwort: `aikido2025`

**Funktionen:**
- CSV-Upload (Tab-getrennt)
- Statistik

**CSV-Format:**
```
Technik	Variation	Angriff, japanischer Name	Angriff, deutsche Beschreibung	Farbprüfung	Video1	Video2	...
```

### Einstellungen (Menü)
- Hell/Dunkel-Modus
- Links zu Aikido-Webseiten
- Disclaimer

## Spaced Repetition System

**Bewertungen setzen Wiederholungs-Intervalle:**
- **Kann ich:** 7 Tage bis zur nächsten Wiederholung
- **Geht so:** 3 Tage bis zur nächsten Wiederholung
- **Schwer / Kann ich nicht:** 1 Tag bis zur nächsten Wiederholung

**Button "Schwachpunkte":**
- Zeigt nur Karten, deren Wiederholungs-Zeitpunkt erreicht ist
- Fokussiertes Lernen auf das Wichtigste

## Daten

### Lokaler Speicher
- Browser: localStorage (bleibt erhalten)
- App: lokale Datenbank

### Daten löschen
Browser-Einstellungen → Website-Daten löschen

### Backup
Admin → CSV hochladen (überschreibt Daten)

## Tipps

1. **Regelmäßig üben:** Täglich 10-15 Min effektiver als 2h am Wochenende
2. **Schwachpunkte nutzen:** Fokus auf das, was du nicht kannst
3. **Prüfung simulieren:** Vor echter Prüfung mehrmals durchgehen
4. **Videos ansehen:** Bei "Geht so" / "Schwer" immer Video anschauen
5. **Ehrlich bewerten:** Nur so funktioniert das System

## Technische Details

- **Keine Internet-Verbindung nötig** (außer für Videos)
- **Keine Registrierung**
- **Keine Cloud-Synchronisation**
- **Alle Daten bleiben auf dem Gerät**
- **Funktioniert offline**

## Admin-Passwort ändern

Im Code suchen nach:
```javascript
const ADMIN_PASSWORD = 'aikido2025';
```
Und ändern zu deinem Passwort.

## Support

Bei Fragen oder Problemen: Jorge kontaktieren
