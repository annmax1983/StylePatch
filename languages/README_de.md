# StylePatch

Offizielles Benutzerhandbuch · Mehrsprachig: [English](../README.md) | [中文](README_zh.md) | [Español](README_es.md) | Deutsch | [日本語](README_ja.md) | [Français](README_fr.md)

> Dieses Dokument ist das offizielle Benutzerhandbuch von StylePatch, erreichbar über den Button „Benutzerhandbuch" im Erweiterungspanel.

Eine schlanke Browser-Erweiterung, mit der du Hintergrundfarbe, Textfarbe, Linkfarbe, Schriftart, Filtereffekte und Schriftgröße jeder Webseite sofort anpassen kannst — für ein komfortableres Leseerlebnis.

✅ Offiziell im Chrome & Edge Web Store veröffentlicht · ✅ Kein Tracking, alle Daten lokal gespeichert · ✅ Unabhängige Einstellungen pro Seite

---

## Funktionsübersicht

### 🆓 Kostenlose Funktionen

| Funktion | Beschreibung |
|----------|--------------|
| 🎨 **Hintergrund-, Text- & Linkfarbe** | Wähle eine beliebige Farbe über den nativen Farbwähler oder gib den Hex-Code direkt ein; Linkfarbe passt sich automatisch für bessere Lesbarkeit an |
| 🔠 **Schriftgröße skalieren** | Von 80% bis 150% über CSS zoom einstellen |
| 🔤 **Schriftart** | Seiten-Schriftart wechseln — Systemschriften oder Google Fonts aus dem Web (Roboto, Open Sans, Noto Sans SC…) |
| 🌗 **Farbfilter** | Graustufenmodus und warmer Sepia-Ton für angenehmeres Lesen |
| 👁️ **Vorgefertigte Themes** | Hell, Warmton, Grün, Dunkel — ein Klick zum Anwenden |
| 🔄 **Globaler Schalter** | Erweiterung global aktivieren/deaktivieren ohne Einstellungen zu verlieren |
| 🚫 **Seiten-Blacklist** | Bestimmte Websites vom Styling ausschließen |
| 💾 **Einstellungen pro Seite** | Verschiedene Styles für verschiedene Websites speichern, werden beim nächsten Besuch automatisch wiederhergestellt (bis zu 5 Seiten kostenlos) |
| ⚡ **Echtzeit-Vorschau** | Alle Änderungen werden sofort beim Ziehen angewendet, kein Neuladen nötig |
| 🌍 **Mehrsprachige UI** | Unterstützt Englisch, Chinesisch, Spanisch, Deutsch, Japanisch, Französisch |
| 🔒 **Minimale Berechtigungen** | Nur `storage` + `host_permissions` — kein unnötiger Zugriff |
| 🏗️ **Manifest V3** | Aufgebaut auf Manifest V3 Service Worker Architektur |
| 🔄 **Ein-Klick-Reset** | Ursprüngliches Aussehen jeder Seite sofort wiederherstellen |

### ⭐ Premium-Funktionen (Lizenz erforderlich)

| Funktion | Beschreibung |
|----------|--------------|
| ♾️ **Unbegrenzte Konfigurationen** | Styles für unbegrenzt viele Websites speichern (kostenlos: max. 5 Seiten) |
| 📤 **Alle Konfigurationen exportieren** | Ein-Klick-Download aller Seiten-Styles als strukturierte JSON-Backup-Datei |
| 📥 **Konfigurationen importieren** | Alle Styles aus einer Backup-Datei sofort wiederherstellen — ideal für Gerätemigration |
| 💾 **Backup & Restore Workflow** | Vor Systemneuinstallation exportieren, auf neuem Gerät importieren — alle Einstellungen bleiben erhalten |
| 🔄 **Gerätemigration** | StylePatch auf einem neuen Computer in Sekunden einrichten, jeder individuelle Look wird wiederhergestellt |

> Siehe [VKT Preise](https://annmax1983.com/pricing.html) für Lizenzoptionen. Einzellizenz ab $2.99/Monat oder $9.99 lebenslang.

---

## Vorschau

<p align="center">
  <img src="screenshot/en.png" alt="StylePatch Vorschau" width="640">
</p>

---

## Unterstützte Browser

| Browser | Status | Mindestversion |
|---------|--------|----------------|
| Google Chrome | ✅ Vollständig unterstützt | Chrome 95+ |
| Microsoft Edge | ✅ Vollständig unterstützt | Edge 95+ |
| Andere Chromium-basierte Browser | ✅ Grundlegend kompatibel | Nur über offiziellen Erweiterungsstore installieren |

---

## Installation

Zu deiner Sicherheit: Installiere StylePatch ausschließlich über offizielle Browser-Erweiterungsstores:

1. Öffne den **Chrome Web Store** oder **Microsoft Edge Add-ons**
2. Suche: `StylePatch`
3. Klicke auf **„Zu Chrome hinzufügen"** / **„Zu Edge hinzufügen"**
4. Klicke auf das StylePatch-Symbol in deiner Toolbar zum Starten

> ⚠️ Nicht von Drittanbieter-Websites installieren. Nicht autorisierte Versionen können deine Datensicherheit gefährden.

---

## Verwendung

1. Klicke auf das **StylePatch-Symbol** in deiner Browser-Toolbar
2. **Farben wählen** — Verwende den nativen Farbwähler oder gib einen Hex-Code ein
3. **Vorlage wählen** — Hell, Warmton, Grün oder Dunkel
4. **Schriftgröße anpassen** — Schieberegler von 80% bis 150% ziehen
5. **Schriftart wählen** — Systemschrift wählen oder eine Google Font aus dem Web laden
6. **Filter anwenden** — Optional Graustufen oder warmen Augenschutz-Ton
7. **Speichern** — Klicke auf **Anwenden & Speichern**, um die Einstellungen für diese Seite zu übernehmen
8. **Zurücksetzen** — Klicke ↺, um das Standardaussehen der Seite wiederherzustellen
9. **Ausschließen** — Klicke auf „Diese Seite ausschließen", um eine Domain zu blacklisten
10. **Umschalten** — Verwende den EIN/AUS-Schalter zum Deaktivieren ohne Einstellungen zu verlieren

### Konfigurationsmanager

Klicke unten im Popup auf **⚙ Konfigurationsmanager**, um die Konfigurationsseite zu öffnen:

- **Anzeigen** aller konfigurierter Seiten mit Farb- und Schrifteinstellungen
- **Exportieren** aller Konfigurationen als JSON-Backup-Datei
- **Importieren** einer Backup-Datei zur Wiederherstellung auf einem anderen Gerät oder nach Neuinstallation
- **Löschen** einzelner Seitenkonfigurationen

---

## FAQ

1. **Styles greifen nach Anpassung nicht?**
   Schließe andere ähnliche Erweiterungen (Dunkelmodus / Augenschutz), die konflikten könnten, und aktualisiere die Seite.

2. **Gespeicherte Einstellungen verschwinden nach Browserneustart?**
   Stelle sicher, dass du auf „Anwenden & Speichern" geklickt hast. Im Inkognito-Modus: Aktiviere die StylePatch-Berechtigung für private Fenster.

3. **Wie übertrage ich meine Einstellungen auf ein neues Gerät?**
   Öffne den Konfigurationsmanager (⚙), klicke auf Exportieren, um eine Backup-Datei herunterzuladen, und importiere sie auf dem neuen Gerät.

4. **Warum teilen sich `www.example.com` und `example.com` dieselben Einstellungen?**
   Das ist beabsichtigt — Domains werden unabhängig vom führenden `www.` gematcht, damit dein Style auf beiden Adressen konsistent greift.

5. **StylePatch nicht im Erweiterungsstore gefunden?**
   Überprüfe deine Netzwerkregion. Den offiziellen Store-Link findest du unter [www.annmax1983.com](https://www.annmax1983.com).

---

## Datenschutz

StylePatch folgt den Prinzipien von Privacy-by-Design und erhebt keinerlei Nutzerdaten:

1. **Angeforderte Berechtigungen** — nur zwei:
   - `storage`: Speichert deine benutzerdefinierten Farben, Schriftgröße, Seiten-Blacklist und Theme-Einstellungen lokal. Es werden keine Webseiteninhalte gespeichert.
   - `host_permissions`: Wird nur verwendet, um benutzerdefinierte CSS-Styles zur Anpassung des Seitenaussehens zu injizieren. Liest keinen DOM-Text, Bilder, Cookies, Anmeldedaten oder Formulardaten.

2. **Kein Tracking** — Kein Zugriff auf den Browserverlauf, keine eingebetteten Drittanbieter-Tracker, keine automatische externe Datenübertragung.

3. **Daten bleiben lokal** — Alle Konfigurationsdaten existieren nur auf deinem Gerät. Daten verlassen deinen Browser nur, wenn du manuell eine Backup-Datei exportierst, oder wenn du eine Google Font wählst (dann wird die Schriftdatei von fonts.googleapis.com heruntergeladen).

- [Vollständige Datenschutzerklärung](https://annmax1983.github.io/StylePatch/privacy-policy.html)
- [Ergänzende Datenschutzdetails](https://www.annmax1983.com)

---

## Urheberrechtshinweis

1. Diese Erweiterung passt nur lokal die visuelle Darstellung von Webseiten für komfortables Lesen an. Alle Text-, Bild- und Inhaltsrechte jeder Website gehören deren jeweiligem Herausgeber.
2. Das Ändern von Seitenanzeige-Styles gewährt Nutzern keine Urheberrechtslizenz an Website-Inhalten. Es ist strengstens verboten, diese Erweiterung zu nutzen, um Bezahlschranken, Mitgliedschaftsbeschränkungen oder Anti-Kopier-Schutzmechanismen zu umgehen.
3. Nutzer haben bei der Verwendung dieser Erweiterung lokale Gesetze und Plattform-Nutzungsbedingungen einzuhalten. Jede rechtswidrige Nutzung geht zu Lasten des Nutzers.

---

## Quellcode-Hinweis

> ⚠️ **Dieses Repository veröffentlicht keinen Quellcode.** Es enthält nur Nutzerdokumentation, Versionshinweise und Support-Ressourcen. Die Erweiterung wird ausschließlich über den Chrome Web Store vertrieben. Es werden keine Offline-Installationspakete oder Endbenutzer-Quellcodes bereitgestellt.

---

## Lizenz

Copyright © 2026 StylePatch. Alle Rechte vorbehalten.

Diese Software ist Closed-Source-Proprietärsoftware. Ohne offizielle schriftliche Genehmigung ist Folgendes strengstens untersagt:
- Dekompilieren, Knacken oder Modifizieren des Programmcodes
- Umpacken, Weiterverbreitung, Weitergabe oder kommerzieller Wiederverkauf
- Einbetten des Programms in andere Software zur gebündelten Distribution

Verstoßende tragen die entsprechenden rechtlichen Konsequenzen.

---

## ❤️ Support

Wenn dir StylePatch hilft, kannst du dem Entwickler gerne einen Kaffee ausgeben!

**[👉 Hier unterstützen](https://ko-fi.com/annmax?buyACoffee=true&ref=stylepatch)**
