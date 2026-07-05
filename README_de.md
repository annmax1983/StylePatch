# StylePatch
Leichte Browser-Erweiterung, mit der du Hintergrundfarbe, Textfarbe und Schriftgröße jeder Webseite sofort anpassen kannst.
> Chromium-basiert · Manifest V3 · Kein Tracking · Einstellungen pro Webseite speicherbar

## Funktionen
| Funktion | Beschreibung |
|----------|--------------|
| 🎨 Hintergrund- und Textfarbe | Farben über den integrierten Farbwähler wählen oder Hex-Code eingeben |
| 🔠 Schriftgrößen-Skalierung | Skalierung von 60% bis 150%, funktioniert bei festen Pixel-Schriften |
| 👁️ Augenschutzmodus | Ein Klick für warmfarbenes Design, angenehmer beim Lesen |
| 💾 Webseiten-spezifische Einstellungen | Speichere individuelle Designs für jede Seite, automatisch wiederhergestellt |
| ⚡ Echtzeit-Vorschau | Alle Änderungen wirken sofort, keine Seitenaktualisierung nötig |
| 🔄 Dynamischer Seiteninhalt | Passt automatisch SPA und nachgeladene Inhalte an |
| 🌍 Mehrsprachig | Unterstützt Deutsch, Englisch, Spanisch, Japanisch, Französisch, Chinesisch |
| 🔒 Minimale Berechtigungen | Benötigt nur `activeTab` und `storage` – keine unnötigen Zugriffe |

## Vorschau
<p align="center">
  <img src="screenshot/de.png" alt="StylePatch Vorschau" width="640">
</p>

## Unterstützte Browser
| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Vollständig unterstützt |
| Microsoft Edge | ✅ Vollständig unterstützt |
| Andere Chromium-Browser | ✅ Funktionsfähig |

## Installation
1. Öffne die Erweiterungsseite deines Browsers:
   - Chrome: `chrome://extensions/`
   - Edge: `edge://extensions/`
2. Schalte oben rechts den **Entwicklermodus** ein
3. Klicke auf **Entpackte Erweiterung laden** und wähle den Projektordner aus
4. Klicke auf das StylePatch-Symbol in der Werkzeugleiste zum Starten

## Nutzung
1. Klicke auf das StylePatch-Symbol in der Browser-Werkzeugleiste
2. Farben auswählen: Nutze den Farbwähler oder gib einen Hex-Code ein
3. Schriftgröße anpassen: Ziehe den Regler zwischen 60% und 150%
4. Augenschutzmodus: Klicke auf 👁 für warmes Lesedesign
5. Speichern: Klicke auf **Übernehmen & Speichern**, um Einstellungen für die Seite zu sichern
6. Zurücksetzen: Klicke auf ↺, um das Originaldesign der Webseite wiederherzustellen

Einstellungen werden automatisch gespeichert, wenn das Popup geschlossen wird und beim nächsten Besuch der Seite wieder geladen.

## Datenschutz
- Nur die Berechtigungen `activeTab` und `storage` werden angefordert
- Kein Zugriff auf Browserverlauf, keine Nutzerverfolgung, keine Datenübertragung nach außen
- Alle Einstellungen bleiben lokal im Browser gespeichert

## Lizenz
Copyright © 2026 StylePatch. Alle Rechte vorbehalten.

> Hinweis: Dieses Repository dient nur zur Projektvorstellung. Es enthält keinen vollständigen Quellcode, Manifest, Icons oder Build-Skripte. Der vollständige Quellcode wird hier nicht veröffentlicht.
