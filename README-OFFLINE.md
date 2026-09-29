# Kaderplaner V75 - sicherer Offline- und Datenpatch

## Offline-Start
- Robustes Einzeldatei-Caching statt `cache.addAll()`.
- `index.html` ist der zwingende Offline-Kern.
- Sicherer Navigationsfallback statt schwarzem oder weißem Bildschirm.
- Cache-Treffer funktionieren auch bei Versionsparametern.
- Nur alte Kaderplaner-Caches werden entfernt.
- Fehlerhafte HTTP-Antworten werden nicht als App-Seite gespeichert.
- `structuredClone()` besitzt einen Rückfall für ältere Safari-/iOS-Versionen.

## Daten und Logik
- Beschädigte lokale Daten werden soweit möglich separat gesichert und verständlich gemeldet.
- Fehler beim lokalen Speichern werden nicht mehr lautlos verschluckt.
- Spieler- und Dienst-IDs werden auf Leerwerte und Duplikate geprüft.
- Verwaiste Dienstzuordnungen werden entfernt.
- Dienstzähler werden auf endliche, nicht negative Ganzzahlen begrenzt.
- Textfelder, Farben und Auswahllisten werden beim Start normalisiert.
- Importdaten werden vor dem endgültigen Speichern erneut normalisiert.
- Bestehender Speicherschlüssel `vfr-kaderplaner-v4` bleibt erhalten.

## Installation auf dem iPhone
1. Alle Dateien aus der ZIP gemeinsam hochladen und vorhandene Dateien ersetzen.
2. Veröffentlichung von GitHub Pages abwarten.
3. Alte Homescreen-App löschen.
4. Website einmal vollständig online in Safari öffnen.
5. Neu zum Home-Bildschirm hinzufügen und einmal online starten.
6. Anschließend im Flugmodus schließen und erneut öffnen.
