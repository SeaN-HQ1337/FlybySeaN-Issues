<details open>
  Link: https://ficsit.app/mod/FlybySeaN
<summary><strong>Deutsch</strong></summary>

# FlybySeaN

FlybySeaN fügt Satisfactory einen freien Flugmodus hinzu. Damit können alle Spieler frei fliegen, ohne den Kreativmodus zu aktivieren.

Die Mod ist für Mehrspieler-Spiele ausgelegt und unterstützt dedizierte Windows- und Linux-Server.

## Funktionen

- Freier Flug ohne Kreativmodus
- Für alle Spieler verfügbar
- Mehrspieler-Unterstützung
- Unterstützung für dedizierte Windows- und Linux-Server
- Acht vordefinierte Geschwindigkeitsstufen
- Horizontale und vertikale Geschwindigkeit nutzen den gewählten Multiplikator
- Flugmodus lässt sich mit `G` umschalten
- Auf- und Absteigen während des Fliegens
- Flugmodus und Geschwindigkeit werden pro Spieler gespeichert
- Flugzustand und Geschwindigkeit werden nach erneutem Verbinden oder Serverneustart wiederhergestellt
- Flugmodus bleibt beim Ein- und Aussteigen aus Fahrzeugen aktiv
- Beim Landen bleibt der Flugmodus kurzzeitig aktiv und die Geschwindigkeit wird auf **x2** gesetzt, damit kurzes Streifen des Bodens beim niedrigen Fliegen nicht aus dem Flugmodus wirft
- Nach dem Landen kann man ganz normal laufen; der Flugmodus wird erst wieder aktiv, wenn man bewusst erneut aufsteigt
- Das Bau-Overlay blockiert das Umschalten des Flugmodus und Geschwindigkeitsänderungen
- Kollisionen deaktivieren den Flugmodus nicht absichtlich

## Tastenbelegung

| Taste / Eingabe | Funktion |
| --- | --- |
| `G` | Flugmodus umschalten |
| `Leertaste` halten | Aufsteigen während des Fliegens |
| `C` halten | Absteigen während des Fliegens |
| Mausrad nach oben | Fluggeschwindigkeit erhöhen |
| Mausrad nach unten | Fluggeschwindigkeit verringern |

Das Umschalten des Flugmodus und Geschwindigkeitsänderungen sind blockiert, solange das Bau-Overlay aktiv ist.

## Fluggeschwindigkeitsstufen

FlybySeaN verwendet diese festen Geschwindigkeitsmultiplikatoren:

`x0.5 -> x1 -> x2 -> x6 -> x10 -> x14 -> x17 -> x20`

- Standardgeschwindigkeit: **x1**
- Minimale Geschwindigkeit: **x0.5**
- Maximale Geschwindigkeit: **x20**
- Mausrad nach oben wählt die nächsthöhere Geschwindigkeitsstufe
- Mausrad nach unten wählt die nächstniedrigere Geschwindigkeitsstufe

Die gewählte Geschwindigkeit wird pro Spieler gespeichert und nach erneutem Verbinden oder Serverneustart wiederhergestellt.

## Fahrzeug- und Bodenverhalten

Der Flugmodus bleibt beim Ein- und Aussteigen aus einem Fahrzeug aktiv. Beim Landen mit aktivem Flugmodus bleibt der Flugzustand kurzzeitig erhalten und die Geschwindigkeit wird auf **x2** gesetzt. Das fängt den Charakter ab, falls er beim niedrigen Fliegen über unebenem Gelände nur kurz den Boden berührt hat. Bleibt man am Boden und läuft weiter, zieht einen der Flugmodus nicht erneut in die Luft; drücke einfach wieder `Leertaste`, wenn du abheben möchtest.

## Mehrspieler

FlybySeaN ist für die Nutzung im Mehrspieler-Modus gedacht. Flugzustand und Geschwindigkeit werden zwischen Client und Server synchronisiert und pro Spieler gespeichert.

Die Mod muss sowohl auf dem Client als auch auf dem dedizierten Server installiert sein. Es sind weder Kreativmodus noch Admin-Rechte oder besondere Spielerrechte erforderlich.

## Installation

1. Satisfactory Mod Loader installieren.
2. FlybySeaN über den Satisfactory Mod Manager installieren.
3. Dieselbe Mod-Version auf Client und Server installieren.
4. Satisfactory starten und dem Server beitreten.
5. `G` drücken, um den Flugmodus zu aktivieren.

## Voraussetzungen

- Satisfactory 1.2
- Satisfactory Mod Loader
- Satisfactory Mod Manager
- Übereinstimmende Mod-Versionen auf Client und Server

## Mod-Informationen

| | |
| --- | --- |
| Kreativmodus erforderlich | Nein |
| Mehrspieler | Unterstützt |
| Dedizierter Windows-Server | Unterstützt |
| Dedizierter Linux-Server | Unterstützt |

</details>

<details>
<summary><strong>English</strong></summary>

# FlybySeaN

FlybySeaN adds a free-flight mode to Satisfactory. It allows all players to fly freely without enabling Creative Mode.

The mod is designed for multiplayer and supports dedicated Windows and Linux servers.

## Features

- Free flight without Creative Mode
- Available to all players
- Multiplayer support
- Dedicated Windows and Linux server support
- Eight predefined speed levels
- Horizontal and vertical speed use the selected multiplier
- Flight mode can be toggled with `G`
- Ascending and descending while flying
- Flight mode and speed are saved per player
- Flight state and speed are restored after reconnecting or restarting the server
- Flight mode remains active when entering and leaving vehicles
- Landing briefly keeps flight mode active and sets the speed to **x2**, so clipping the ground while flying low does not kick you out of flight
- After landing you can walk around normally; flight mode only reactivates when you intentionally ascend again
- Build overlay blocks flight toggling and speed changes
- Collisions do not intentionally disable flight mode

## Keybinds

| Key / Input | Function |
| --- | --- |
| `G` | Toggle flight mode |
| Hold `Space` | Ascend while flying |
| Hold `C` | Descend while flying |
| Mouse Wheel Up | Increase flight speed |
| Mouse Wheel Down | Decrease flight speed |

Flight toggling and speed changes are blocked while the Build Gun overlay is active.

## Flight Speed Levels

FlybySeaN uses these fixed speed multiplier levels:

`x0.5 -> x1 -> x2 -> x6 -> x10 -> x14 -> x17 -> x20`

- Default speed: **x1**
- Minimum speed: **x0.5**
- Maximum speed: **x20**
- Mouse Wheel Up selects the next speed level
- Mouse Wheel Down selects the previous speed level

The selected speed is saved per player and restored after reconnecting or restarting the server.

## Vehicle and Ground Behavior

Flight mode remains active when entering or leaving a vehicle. Landing while flight mode is enabled briefly preserves the flight state and changes the speed to **x2**, which catches the character if it only clipped the ground for a moment while flying low over uneven terrain. If you stay grounded and keep walking, flight mode does not pull you back into the air; press `Space` again whenever you want to take off.

## Multiplayer

FlybySeaN is intended for multiplayer use. Flight state and speed are synchronized between client and server and saved per player.

The mod must be installed on both the client and the dedicated server. No Creative Mode, admin permissions, or special player permissions are required.

## Installation

1. Install Satisfactory Mod Loader.
2. Install FlybySeaN using the Satisfactory Mod Manager.
3. Install the same mod version on the client and server.
4. Start Satisfactory and join the server.
5. Press `G` to activate flight.

## Requirements

- Satisfactory 1.2
- Satisfactory Mod Loader
- Satisfactory Mod Manager
- Matching mod versions on client and server

## Mod Information

| | |
| --- | --- |
| Creative Mode required | No |
| Multiplayer | Supported |
| Dedicated Windows server | Supported |
| Dedicated Linux server | Supported |

</details>
