# Veto Director 3

**Die kostenlose, lokale CS2 Casting & Broadcast Suite.**
Map-Veto, Broadcast-HUD und Match-Verwaltung in einem Tool – für Caster, Streamer, Turnierveranstalter und Community-Ligen.

Kein Konto. Keine Cloud. Keine Kosten. Download, starten, casten.

---

## Was kann Veto Director 3?

### Broadcast-HUD
Ein vollständiges HUD für CS2-Übertragungen, gespeist mit Live-Daten aus dem Spiel:

- Top-Bar mit Teamnamen, Logos, Score, Runde und Timer
- Spielerkarten mit Foto, HP, Armor, Geld, Waffen und Utility
- Fokus-Spieler, Minimap mit Spieler-, Bomben- und Granatenpositionen
- Kill-Feed und Ereignisse
- Rundensieger-Banner, das sich über die Top-Bar legt (T von rechts in Orange, CT von links in Blau)
- MVP-Einblendung, Scoreboard und Timeout-Menü mit Rundenverlauf

Als transparentes Fenster über dem Spiel **oder** als Browser-Quelle in OBS.

### Map-Veto
- Picks und Bans direkt im Tool, mit Veto-Typen wie Best of 1 / 3 / 5 oder eigenen Abläufen
- Eigener Mappool
- **OBS-Overlay** mit großen Map-Karten: Pick in Grün, Ban in Rot (Map schwarz-weiß), Decider in Gold
- Eine feste Browser-Quelle für alle Matches – du wählst nur das aktive Match

### Spieler, Teams und Matches
- Zentrale Datenbank für Spieler und Teams mit Fotos, Logos, Flaggen und Faceit-MMR
- **Faceit-Import:** Team-Link oder Matchroom-Link einfügen – Teams, Logos und Spieler werden automatisch angelegt
- Kartenergebnisse direkt unter jeder gespielten Map, auf Wunsch automatisch von Faceit
- Live-Daten (HP, Geld, K/D/A, Waffe) direkt in den Spielerlisten

### Eigene Designs
Das HUD lässt sich per CSS frei anpassen. Aus der eingebauten Vorlage entsteht mit einem Klick dein eigenes Design, fertige HUDs importierst du als Ordner oder ZIP.

---

## Schnellstart

1. **`Veto Director 3 by ClassicSchnitzel.exe`** unter [Releases](../../releases/latest) herunterladen und starten
   (Windows meldet evtl. „Unbekannter Herausgeber“ → *Weitere Informationen → Trotzdem ausführen*).
2. In den **Einstellungen** bei „CS2-Verbindung“ auf **Automatisch installieren** klicken und CS2 neu starten.
3. **Team importieren** (Faceit-Link) oder manuell anlegen, **Match erstellen**.
4. Auf der Matchseite **HUD starten** – oder in OBS eine Browser-Quelle mit `http://localhost:3535/huds/default/` einfügen.

## Für OBS

| Quelle | URL |
|---|---|
| Broadcast-HUD | `http://localhost:3535/huds/default/` |
| Map-Veto-Overlay | `http://localhost:3535/veto` |

Beides als Browser-Quelle in 1920×1080.

---

## Anleitungen

- [Kurzanleitung](ANLEITUNG_KURZ.txt) – der schnellste Weg zum Casten
- [Ausführliche Anleitung](ANLEITUNG_AUSFUEHRLICH.txt) – alles zu Einrichtung, Spielern, Teams, Matches, Veto, HUD und OBS
- [CS2-Verbindung (cfg)](gamestate_integration_vetodirector.cfg) – falls du sie lieber selbst in den CS2-Ordner kopierst (`…/game/csgo/cfg`)

## Systemvoraussetzungen

- Windows
- CS2 (Steam)
- OBS Studio (optional, für Streams)
- Internetverbindung für den Faceit-Import

## Status

Das Tool ist in aktiver Entwicklung. Geplant sind unter anderem eine MVP-Szene am Rundenende sowie Map- und Match-MVP, eine Caster-Ansicht mit großer Minimap und Heat-Markierungen, weitere Overlays (Match-Intro, Lineup, Player Card) und ein grafischer Overlay-Editor.

Feedback, Ideen und Fehlermeldungen sind willkommen – bitte als [Issue](../../issues) melden.

---

*Veto Director 3 by ClassicSchnitzel*
