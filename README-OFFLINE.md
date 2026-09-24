# Kaderplaner Version 72 Offline

## Fehlerkorrekturen
- „＋ Spieler“ funktioniert wieder zuverlässig.
- Eine aktive Spielersuche wird beim Hinzufügen automatisch geleert.
- Der neue Spieler wird sichtbar gemacht und das Namensfeld sofort fokussiert.
- Robuste Spieler-ID-Erzeugung für Browser ohne `crypto.randomUUID()`.
- Fehlende oder beschädigte Zählerstrukturen werden automatisch repariert.
- Die fehlende `manifest.webmanifest` wurde ergänzt. Dadurch kann die Offline-PWA vollständig installiert und gecacht werden.
- Offline-Cache auf Version 72 angehoben.

## Aktualisierung
Alle Dateien bei GitHub ersetzen. Danach die App einmal mit Internet öffnen und neu laden, damit Version 72 und der neue Offline-Cache übernommen werden.
