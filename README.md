# Zeitberechnungstool
Ein Excel-Tool zur Berechnung der Arbeitszeit basierend auf voreingestellten Werten und der Einloggzeit

## Funktion
- Automatische Arbeitszeitberechnung: Berechnet die Arbeitszeit basierend auf der Einloggzeit und voreingestellten Standardwerten.
- Anpassbare Einstellungen: Definiere Standardarbeitszeiten, Pausen, extra Pausen z.B. rauchen und mehr direkt in der Tabelle.
- Einfache Bedienung: Intuitiv gestaltet und für jeden leicht verständlich.


## Voraussetzungen
- Microsoft Excel (Version 2019 oder neuer)

## Installation
1. Lade die Datei "Zeitberechnung_V1_2_0_0_DE.xlsm" aus dem Repository herunter.
2. Speichere die Datei auf deinem PC

## Verwendung
1. Öffnen der Datei:
	- Öffne die Datei in Excel.
2. Anpassung der Werte:
	- Passe die voreingestellten Werte (Standardarbeitszeit und Pausenlänge) im Konfigurationsbereich der Tabelle an.
3. Eintrag der Einloggzeit:
	- Gib deine Einloggzeit in die entsprechende Zelle ein (z.B. 07:00)
4. Eintrag der extra Pausen:
	- Gib deine extra Pausenzeiten in die entsprechende Zelle ein (z.B. 00:15). Wenn keine extra Pausen gemacht wurden dann kann hier einfach "00:00" eingetragen werden.
5. Ausgabe der Arbeitszeit:
	- Die Tabelle berechnet automatisch die Arbeitszeit, Pausen und die voraussichtliche Ausloggzeit.
	
## Beispiel
Eingabe:
	- Einloggzeit: 08:00
	- Pausenlänge: 30 Minuten (voreingestellt)
	- Arbeitszeit pro Tag: 8 Stunden (voreingestellt)
	- extra Pausen: 0 Minuten (voreingestellt)
Ausgabe:
	- geplante Ausloggzeit: 16:30
	- gearbeitete Zeit: 8 Stunden
	
## Anpassung
Standardwerte ändern:
	- Navigiere zum oberen linken Bereich in der Excel-Tabelle und passe die Werte nach Bedarf an.
	
## Fehlerbehebung
- Formeln werden nicht berechnet:
	- Stelle sicher, dass die automatische Berechnung in Excel aktiviert ist:
		- Menü: Formeln > Berechnungsoptionen > automatisch
- Kompatibilitätsprobleme:
	- Verwende Microsoft Excel für optimale Ergebnisse. In Google Sheets oder LibreOffice Calc können kleinere Anpassungen notwendig sein.
	
## Beitrag
1. Forke dieses Repository.
2. Lade die angepasste Excel-Datei hoch.
3. Erstelle ein Pull-Request mit der Beschreibung deiner Änderungen.

## Lizenz
Dieses Projekt steht unter der [MIT-Lizenz]https://de.wikipedia.org/wiki/MIT-Lizenz