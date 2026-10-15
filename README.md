# 🌍 NovaCraft: Swift Edition (v1.4 Alpha)

Ein performantes, Minecraft-inspiriertes Voxel-Spiel, entwickelt komplett nativ für iPadOS mit **SwiftUI** und **SceneKit / Metal**.

---

## ✨ Features

* **Authentisches Java-UI/UX:**
  * Vollständig nachgebildetes Survival- und Kreativ-Inventar mit Kategorien-Tabs, Live-Suche und 1-Item/Stack-Split-Modus.
  * Java-Style Menüs inklusive Pausenmenü, Welterstellung (*Game*, *World*, *More*) und Video-Settings.
* **Dynamischer Pixel- & UI-Editor:**
  * Eigener 16x16-Editor für Blöcke, Werkzeuge, Schwerter und UI-Elemente (Herzen, Hunger, Rüstung, Fadenkreuz).
  * Import und Export von eigenen Texturpaketen als komprimierte `.cpack`-Dateien.
* **Unendliche Welten & Persistenz:**
  * Dynamischer `WorldManager` ohne Slot-Begrenzung.
  * Speicherung von Block-Modifikationen, Inventarständen und Spielerpositionen.
* **Multiplayer-Ready (In Vorbereitung):**
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

1. Lade dir die neueste Version aus den **Releases** als `.zip` herunter.
2. Öffne die Dateien-App auf deinem iPad und tippe auf die Datei, um sie zu entpacken.
3. Tippe auf das `.swiftpm`-Paket – das Spiel öffnet sich direkt in **Swift Playgrounds**.
4. Drücke oben auf den Play-Button `▶` und starte deine Welt!

---

*Entwickelt als eigenständiges Voxel-Engine-Projekt. All rights reserved.*
