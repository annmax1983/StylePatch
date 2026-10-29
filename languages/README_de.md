# StylePatch

Offizielles Benutzerhandbuch · Mehrsprachig: [English](../README.md) | [中文](README_zh.md) | [Español](README_es.md) | Deutsch | [日本語](README_ja.md) | [Français](README_fr.md)

> Dieses Dokument ist das offizielle Benutzerhandbuch von StylePatch, erreichbar über den Button „Benutzerhandbuch" im Erweiterungspanel.

Eine schlanke Browser-Erweiterung, mit der du Hintergrundfarbe, Textfarbe, Linkfarbe, Schriftart, Filtereffekte und Schriftgröße jeder Webseite sofort anpassen kannst — für ein komfortableres Leseerlebnis.

✅ Offiziell im Chrome & Edge Web Store veröffentlicht · ✅ Kein Tracking, Daten lokal gespeichert (Cloud-Sync optional und Premium) · ✅ Unabhängige Einstellungen pro Seite

---

## Funktionsübersicht

### 🆓 Kostenlose Funktionen

| Funktion | Beschreibung |
|----------|--------------|
| 🎨 **Hintergrund-, Text- & Linkfarbe** | Wähle eine beliebige Farbe über den nativen Farbwähler oder gib den Hex-Code direkt ein; Linkfarbe passt sich automatisch für bessere Lesbarkeit an |
| 🔠 **Schriftgröße skalieren** | Von 80% bis 150% über CSS zoom einstellen |
| 🔤 **Schriftart** | Seiten-Schriftart wechseln — Systemschriften oder Google Fonts aus dem Web (Roboto, Open Sans, Noto Sans SC…) |
| 🌗 **Farbfilter** | Graustufenmodus und warmer Sepia-Ton für angenehmeres Lesen |
| 👁️ **Vorgefertigte Themes** | Hell, Warmton, Grün, Dunkel, Sepia, Blaue Nacht, Hoher Kontrast — ein Klick zum Anwenden |
| 🧭 **Kontrast-Hinweis** | Warnt, wenn Text- oder Linkfarbe die WCAG-Kontrastwerte unterschreitet |
| 🔄 **Globaler Schalter** | Erweiterung global aktivieren/deaktivieren ohne Einstellungen zu verlieren |
| 🚫 **Seiten-Blacklist** | Bestimmte Websites vom Styling ausschließen |
| 💾 **Einstellungen pro Seite** | Verschiedene Styles für verschiedene Websites speichern, werden beim nächsten Besuch automatisch wiederhergestellt (bis zu 5 Seiten kostenlos) |
| 📤 **Lokales Backup** | Alle Konfigurationen als JSON exportieren und später wiederherstellen (kostenloser Import auf 5 Seiten begrenzt) |
| ⚡ **Echtzeit-Vorschau** | Alle Änderungen werden sofort beim Ziehen angewendet, kein Neuladen nötig |
| 🌍 **Mehrsprachige UI** | Unterstützt Englisch, Chinesisch, Spanisch, Deutsch, Japanisch, Französisch |
| 🔒 **Minimale Berechtigungen** | Nur `storage`, `scripting` + `host_permissions` — kein unnötiger Zugriff |
| 🏗️ **Manifest V3** | Aufgebaut auf Manifest V3 Service Worker Architektur |
| 🔄 **Ein-Klick-Reset** | Entfernt die eigene Konfiguration der Seite; mit Standard-Theme fällt sie darauf zurück |

### ⭐ Premium-Funktionen (Lizenz erforderlich)

| Funktion | Beschreibung |
|----------|--------------|
| ♾️ **Unbegrenzte Konfigurationen** | Styles für unbegrenzt viele Websites speichern (kostenlos: max. 5 Seiten) |
| ☁️ **Cloud-Sync** | Website-Konfigurationen, Blacklist, EIN/AUS-Status und Standard-Theme zwischen Chrome/Edge/Firefox-Profilen mit demselben Browserkonto synchron halten (kein Backend, nutzt `storage.sync`) |
| 🎨 **Standard-Theme** | Ein globales Theme auf alle Seiten ohne eigene Konfiguration anwenden; der Reset fällt darauf zurück |
| 📥 **Vollständige Wiederherstellung** | Backups mit mehr als 5 Seiten inklusive Standard-Theme importieren |

> Siehe [VKT Preise](https://annmax1983.com/pricing.html) für Lizenzoptionen.

---

## Vorschau

<p align="center">
  <img src="../screenshots/en.png" alt="StylePatch Vorschau" width="640">
</p>

---

## Unterstützte Browser

| Browser | Status | Mindestversion |
|---------|--------|----------------|
| Google Chrome | ✅ Vollständig unterstützt | Chrome 95+ |
| Microsoft Edge | ✅ Vollständig unterstützt | Edge 95+ |
| Mozilla Firefox | ✅ Vollständig unterstützt | Firefox 140+ (Desktop) |
| Andere Chromium-basierte Browser | ✅ Grundlegend kompatibel | Nur über offiziellen Erweiterungsstore installieren |

> **Firefox-Hinweis:** Firefox kennt keinen Service Worker für Erweiterungen und nutzt stattdessen eine Event-Page. Die geräteübergreifende Synchronisierung läuft über Firefox Sync (Mozilla-Konto). Die übrigen Funktionen verhalten sich wie unter Chrome / Edge.

---

## Installation

| Store | Link |
|---|---|
| Chrome Web Store | [In Chrome installieren](https://chromewebstore.google.com/detail/hlmnodnjlhdecfcaiahnngpldkialkca) |
| Microsoft Edge Add-ons | [In Edge installieren](https://microsoftedge.microsoft.com/addons/detail/lkhpdpimlelcldbnkhggfdoejcimcfgo) |
| Firefox-Add-ons (AMO) | 🔜 In Prüfung – Link folgt nach der Freigabe |

> Installieren Sie nur über die offiziellen Stores oben – meiden Sie Download-Seiten Dritter.

---

## Verwendung

1. Klicke auf das **StylePatch-Symbol** in deiner Browser-Toolbar
2. **Farben wählen** — Verwende den nativen Farbwähler oder gib einen Hex-Code ein
3. **Vorlage wählen** — Hell, Warmton, Grün, Dunkel, Sepia, Blaue Nacht oder Hoher Kontrast
4. **Schriftgröße anpassen** — Schieberegler von 80% bis 150% ziehen
5. **Schriftart wählen** — Systemschrift wählen oder eine Google Font aus dem Web laden
6. **Filter anwenden** — Optional Graustufen oder warmen Augenschutz-Ton
7. **Speichern** — Klicke auf **Anwenden & Speichern**, um die Einstellungen für diese Seite zu übernehmen
8. **Zurücksetzen** — Klicke ↺, um die eigene Konfiguration der Seite zu entfernen; mit Standard-Theme fällt die Seite darauf zurück
9. **Als Standard festlegen** — Premium-Nutzer können die aktuellen Farben als Standard-Theme für alle Seiten speichern (Seiten mit eigener Konfiguration behalten sie)
10. **Ausschließen** — Klicke auf „Diese Seite ausschließen", um eine Domain zu blacklisten
11. **Umschalten** — Verwende den EIN/AUS-Schalter zum Deaktivieren ohne Einstellungen zu verlieren

### Konfigurationsmanager

Klicke unten im Popup auf **⚙ Konfigurationsmanager**, um die Konfigurationsseite zu öffnen:

- Konfigurierte Seiten mit Farb- und Schrifteinstellungen **anzeigen**, durchsuchen und **löschen**
- Alle Konfigurationen als JSON-Backup-Datei **exportieren** (kostenlos)
- Eine Backup-Datei **importieren**, um Einstellungen auf einem anderen Gerät oder nach Neuinstallation wiederherzustellen (kostenloser Import auf 5 Seiten begrenzt)
- **Cloud-Sync** (Premium) — Konfigurationen zwischen Chrome/Edge/Firefox-Profilen mit demselben Browserkonto spiegeln
- **Standard-Theme** (Premium) — das Theme für Seiten ohne eigene Konfiguration prüfen oder entfernen

---

## FAQ

1. **Styles greifen nach Anpassung nicht?**
   Schließe andere ähnliche Erweiterungen (Dunkelmodus / Augenschutz), die konflikten könnten, und aktualisiere die Seite.

2. **Gespeicherte Einstellungen verschwinden nach Browserneustart?**
   Stelle sicher, dass du auf „Anwenden & Speichern" geklickt hast. Im Inkognito-Modus: Aktiviere die StylePatch-Berechtigung für private Fenster.

3. **Wie übertrage ich meine Einstellungen auf ein neues Gerät?**
   Öffne den Konfigurationsmanager (⚙), klicke auf Exportieren, um eine Backup-Datei herunterzuladen, und importiere sie auf dem neuen Gerät. Der kostenlose Import stellt bis zu 5 Seiten wieder her; Premium stellt alles wieder her. Im selben Chrome/Edge/Firefox-Konto können Premium-Nutzer außerdem Cloud-Sync aktivieren und ganz auf die Datei verzichten.

4. **Warum teilen sich `www.example.com` und `example.com` dieselben Einstellungen?**
   Das ist beabsichtigt — Domains werden unabhängig vom führenden `www.` gematcht, damit dein Style auf beiden Adressen konsistent greift.

5. **StylePatch nicht im Erweiterungsstore gefunden?**
   Überprüfe deine Netzwerkregion. Den offiziellen Store-Link findest du unter [www.annmax1983.com](https://www.annmax1983.com).

---

## Datenschutz

StylePatch folgt den Prinzipien von Privacy-by-Design und erhebt keinerlei Nutzerdaten:

1. **Angeforderte Berechtigungen** — nur drei:
   - `storage`: Speichert deine benutzerdefinierten Farben, Schriftgröße, Seiten-Blacklist und Theme-Einstellungen lokal; der optionale Premium-Cloud-Sync nutzt `storage.sync`. Es werden keine Webseiteninhalte gespeichert.
   - `scripting`: Wird nur verwendet, um das erzeugte CSS in den aktuellen Tab zu injizieren (isolierte Welt der Erweiterung). Liest keine Seiteninhalte und führt keinen fremden Code aus.
   - `host_permissions`: Wird nur verwendet, um benutzerdefinierte CSS-Styles zur Anpassung des Seitenaussehens zu injizieren. Liest keinen DOM-Text, Bilder, Cookies, Anmeldedaten oder Formulardaten.

2. **Kein Tracking** — Kein Zugriff auf den Browserverlauf, keine eingebetteten Drittanbieter-Tracker, keine Analytik.

3. **Daten bleiben lokal, sofern du nicht zustimmst** — Konfigurationsdaten liegen standardmäßig auf deinem Gerät. Sie verlassen deinen Browser nur, wenn du:
   - manuell eine Backup-Datei exportierst;
   - Cloud-Sync (Premium) aktivierst: Dabei werden nur Website-Konfigurationen, Blacklist, EIN/AUS-Status und Standard-Theme über `storage.sync` in deinem Browserkonto gespeichert — niemals Lizenzschlüssel oder Browserdaten;
   - eine Google Font wählst (die Schriftdatei wird von fonts.googleapis.com heruntergeladen);
   - eine Lizenz aktivierst oder validierst (Lizenzschlüssel, eine zufällige Installations-ID und grundlegende Browser-Metadaten werden an api.annmax1983.com gesendet).

- [Vollständige Datenschutzerklärung](https://annmax1983.github.io/StylePatch/privacy-policy.html)
- [Ergänzende Datenschutzdetails](https://www.annmax1983.com)

---

## Urheberrechtshinweis

1. Diese Erweiterung passt nur lokal die visuelle Darstellung von Webseiten für komfortables Lesen an. Alle Text-, Bild- und Inhaltsrechte jeder Website gehören deren jeweiligem Herausgeber.
2. Das Ändern von Seitenanzeige-Styles gewährt Nutzern keine Urheberrechtslizenz an Website-Inhalten. Es ist strengstens verboten, diese Erweiterung zu nutzen, um Bezahlschranken, Mitgliedschaftsbeschränkungen oder Anti-Kopier-Schutzmechanismen zu umgehen.
3. Nutzer haben bei der Verwendung dieser Erweiterung lokale Gesetze und Plattform-Nutzungsbedingungen einzuhalten. Jede rechtswidrige Nutzung geht zu Lasten des Nutzers.

---

## Quellcode-Hinweis

> ⚠️ **Dieses Repository veröffentlicht keinen Quellcode.** Es enthält nur Nutzerdokumentation, Versionshinweise und Support-Ressourcen. Die Erweiterung wird ausschließlich über den Chrome Web Store, Microsoft Edge Add-ons und Firefox-Add-ons (AMO) vertrieben. Es werden keine Offline-Installationspakete oder Endbenutzer-Quellcodes bereitgestellt.

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
