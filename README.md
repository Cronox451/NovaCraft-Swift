# 🌍 NovaCraft: Swift Edition (v1.4 Alpha)

Ein performantes, Minecraft-inspiriertes Voxel-Spiel, entwickelt nativ für iPadOS mit **SwiftUI** und **SceneKit / Metal**.

> ⚠️ **Work in Progress (Aktive Entwicklung):**  
> NovaCraft befindet sich in der aktiven Alpha-Phase. Neue Features, Leistungsoptimierungen und Bugfixes werden kontinuierlich nachgereicht.

---

## 📢 Neu in Version v1.4 Alpha

* **Added:**
  * Eigener Editor- und Rendering-Support für **UI-Elemente** (Herzen, Hungerkeulen, Rüstung, Fadenkreuz).
* **Fixed:**
  * Absturzursachen bei der **World Generation** behoben (dynamische Weltenverwaltung, sicheres Spawnsystem).
* **Offizielles Texture Pack (v0.2):**
  * Erste Basistexturen integriert: *Log (Holz)*, *Stone*, *Dirt*, *Grass*, *Glass*.
  * *Hinweis:* Das Texture Pack ist noch nicht vollständig und wird mit kommenden Updates schrittweise ausgebaut.

---

## ✨ Kern-Features

* **Authentisches Java-UI/UX:**
  * Vollständig nachgebildetes Survival- und Kreativ-Inventar mit Kategorien-Tabs, Live-Suche und 1-Item/Stack-Split-Modus.
  * Java-Style Menüs inklusive Pausenmenü, Welterstellung (*Game*, *World*, *More*) und Video-Settings.
* **In-Game Textur- & UI-Editor:**
  * Integrierter 16x16-Pixel-Editor für Blöcke, Items und HUD-Elemente.
  * Import und Export von Texturpaketen als komprimierte `.cpack`-Dateien.
* **Unbegrenzte Weltenverwaltung:**
  * Dynamischer `WorldManager` ohne feste Slot-Limits.
  * Speicherung von Block-Modifikationen, Inventarständen und Spielerpositionen.
* **Multiplayer-Vorbereitung:**
  * Geplante P2P-Unterstützung via Apple `MultipeerConnectivity` (WLAN & Bluetooth).
  * Berechtigungssystem (Operator/OP) und Custom-Resourcepack-Syncing.

---

## 🛠️ Technische Basis & Entwicklung

* **Sprache:** Swift 5+
* **Plattform:** iPadOS (optimiert für Swift Playgrounds)
* **Grafik:** SceneKit / Metal (`NovaCore`)
* **UI:** 100% SwiftUI
* **Entwicklungsprozess:** Die Konzeption, Architektur und Implementierung der Engine, Shader und UI-Systeme entstand in kollaborativer Entwicklungsarbeit mit Unterstützung von KI (Gemini).

---

## 📦 Installation & Spielen

1. Gehe rechts auf **Releases** und lade dir die Datei `NovaCraft.V.1.4Apha.zip` herunter.
2. Öffne die Dateien-App auf deinem iPad und tippe auf die Datei, um sie zu entpacken.
3. Tippe auf das entpackte `.swiftpm`-Paket – das Projekt öffnet sich direkt in **Swift Playgrounds**.
4. Drücke oben auf den Play-Button `▶`, um das Spiel zu starten.

---

## 🎨 Offizielles Texture Pack einbinden (Optional)

1. Lade dir aus dem Release die Datei `NovaCraft-Official-TexturePack.V0.2.cpack` herunter.
2. Starte **NovaCraft**.
3. Gehe im Menü auf **Options...** ➔ **Resource Packs & Texture Editor...** (oder im laufenden Spiel über das Pausenmenü).
4. Tippe oben auf die Schaltfläche **Datei Importieren** und wähle die heruntergeladene `.cpack`-Datei in der Dateien-App aus.
5. Die neuen Texturen werden sofort im Spiel übernommen.

---

*NovaCraft ist ein unabhängiges Hobby- und Engine-Projekt. All rights reserved.*
