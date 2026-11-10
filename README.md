# Teapacks Royale – spielbarer Prototyp

## Start
1. Entpacke `teapacks_royale.zip`.
2. Öffne `index.html` auf einem PC mit Internetverbindung in einem aktuellen Browser (Chrome, Edge oder Firefox).
3. Klicke auf **Battle Royale starten**. Für 3D wird Three.js beim Start von jsDelivr geladen.

Falls der Browser ES-Module bei `file://` blockiert, starte im Projektordner einen lokalen Server:
- Python: `python -m http.server 8000`
- Öffne dann `http://localhost:8000`.

## Steuerung
- WASD: bewegen
- Maus: umsehen
- Linksklick: Energieblaster
- E: Loot aufnehmen / Heil-Kit verwenden
- Q: Wand platzieren
- Shift: sprinten
- Esc: Pause
- Kreativmodus: Linksklick platziert, Rechtsklick entfernt

## Bereits enthalten
- 3D-Insel mit zufällig verteilten Bäumen, Gebäuden und Loot
- Lobby mit Spielmodus- und Schwierigkeitsauswahl
- Bot-Gegner, Treffer, Eliminierungen, Sturm-Timer und HUD
- Loot, Heil-Kits und Baumaterial
- Kreativmodus mit Platzieren und Entfernen von Bauteilen
- Teapacks-Belohnungen, Shop, Spind und 100 Battle-Pass-Stufen
- Lokales Speichern von Währung, XP, Freischaltungen und Einstellungen

## Technischer Stand / nächste Entwicklungsphase
Dies ist ein erster spielbarer Browser-Prototyp und noch kein fertiges kommerzielles Spiel. Die Spielwelt, Bots und Gegenstände sind lokal simuliert. Online-Multiplayer, echte Team-Mitspieler, vollständiges Bau-/Zerstörungssystem, richtige Waffen-/Charakteranimationen, Tagesrotation mit Serverzeit, Cloud-Speicherung, Controller-Mapping und produktionsreife Optimierung sind noch nicht implementiert. Die Kampfmechanik nutzt bewusst einen stilisierten Energieblaster statt realistischer Waffen.


## iPhone-Version
Die Oberfläche enthält Touch-Steuerung: links bewegen, rechts wischen zum Umschauen, dazu Feuer-, Sprung-, Bauen-, Loot-, Heilen- und Pause-Tasten. Öffne die Spieladresse in Safari. Über Teilen → „Zum Home-Bildschirm“ kannst du sie wie eine App ablegen. Für den iPhone-Betrieb muss die Seite über HTTPS oder einen lokalen Entwicklungsserver bereitgestellt werden; das ZIP allein ist keine native App aus dem App Store.
