# Edge Profil Manager (C# Edition)

> **No backup, no sympathy.**

Ein leichtgewichtiges, portables Windows-Tool zur Verwaltung von Microsoft Edge Profilen. Ursprünglich als PowerShell-Skript entwickelt, wurde dieses Tool nun vollständig nach C# (Windows Forms) portiert, um als eigenständige `.exe` ohne Abhängigkeiten zu laufen.

![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Language](https://img.shields.io/badge/language-C%23-purple)

## 🚀 Funktionen

* **Profil Erstellen:** Erstellt neue Edge-Profile basierend auf dem Standard-Profil ('Default').
* **Backup:** Sichert komplette Profile inkl. JSON-Manifest in kompakte `.zip`-Dateien.
* **Restore:** Stellt Profile aus Backups wieder her (mit automatischer Namenserkennung).
* **Löschen:** Entfernt Profile sicher (Schutz für das 'Default'-Profil).
* **Portable:** Läuft als einzelne `.exe`-Datei (Bilder und Icons sind integriert).
* **Mehrsprachig:** Umschaltbar zwischen **Deutsch** 🇩🇪 und **Englisch** 🇬🇧.
* **Sicherheit:** Erkennt laufende Edge-Prozesse und fordert zum Schließen auf, um Datenverlust zu vermeiden.

## 🛠️ Voraussetzungen

* Windows Betriebssystem (Windows 10/11 empfohlen).
* .NET Framework 4.5 oder höher (auf fast allen Windows-PCs vorinstalliert).
* **Administrator-Rechte** (empfohlen, da Edge seine Daten in geschützten Systemverzeichnissen speichert).

## 📥 Installation & Nutzung

Da es sich um eine portable Anwendung handelt, ist keine Installation notwendig:

1.  Lade die `EdgeProfilManager.exe` herunter (siehe [Releases](#)).
2.  Führe die Datei aus (Rechtsklick -> *Als Administrator ausführen* wird empfohlen).
3.  Wähle deine Sprache oben rechts.
