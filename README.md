# StylePatch

Official User Manual · Multi-language: [English](README.md) | [中文](languages/README_zh.md) | [Español](languages/README_es.md) | [Deutsch](languages/README_de.md) | [日本語](languages/README_ja.md) | [Français](languages/README_fr.md)

> This document is the official user manual for StylePatch, accessible via the "User Manual" button inside the extension panel.

A lightweight browser extension that lets you customize any webpage's background color, text color, link color, font, filter effect, and font size instantly for a more comfortable reading experience.

✅ Officially released on Chrome & Edge Web Store · ✅ Zero tracking, data stored locally (cloud sync is optional and Pro) · ✅ Per-site independent settings

---

## Feature List

### 🆓 Free Features

| Feature | Description |
|---------|-------------|
| 🎨 **Background, Text & Link Color** | Pick any color via native color picker or type hex code directly; link color auto-adjusts for readability |
| 🔠 **Font Size Scaling** | Adjust from 80% to 150% using CSS zoom |
| 🔤 **Font Family** | Switch the page font — system fonts, or Google Fonts loaded from the web (Roboto, Open Sans, Noto Sans SC…) |
| 🌗 **Color Filters** | Grayscale mode and a warm sepia tint for easier reading |
| 👁️ **Preset Themes** | Light, Warm Tone, Green, Dark, Sepia, Night Blue, High Contrast — one click to apply |
| 🧭 **Contrast Hint** | Warns when text or link color falls below WCAG contrast thresholds |
| 🔄 **Global Toggle** | Enable/disable the extension globally without losing settings |
| 🚫 **Site Blacklist** | Exclude specific websites from styling |
| 💾 **Per-Site Settings** | Save different styles for different websites, auto-restore on revisit (up to 5 sites free) |
| 📤 **Local Backup** | Export all configurations to JSON and restore them later (free import is capped at 5 sites) |
| ⚡ **Real-Time Preview** | All changes apply instantly as you drag, no page reload needed |
| 🌍 **Multi-Language UI** | Supports English, Chinese, Spanish, German, Japanese, French |
| 🔒 **Minimal Permissions** | Only `storage`, `scripting` + `host_permissions` — no unnecessary access |
| 🏗️ **Manifest V3** | Built on Manifest V3 service worker architecture |
| 🔄 **One-Click Reset** | Drop the site's own config; falls back to your default theme when one exists |

### ⭐ Premium Features (License Required)

| Feature | Description |
|---------|-------------|
| ♾️ **Unlimited Configs** | Save styles for unlimited websites (free tier: 5 sites max) |
| ☁️ **Cloud Sync** | Keep site configs, the blacklist, the on/off toggle and your default theme in sync across Chrome/Edge profiles signed in to the same browser account (no backend, uses `chrome.storage.sync`) |
| 🎨 **Default Theme** | Apply one global theme to every site without its own config; reset falls back to it |
| 📥 **Full Restore** | Import backups larger than 5 sites, including your default theme |

> See [VKT Pricing](https://annmax1983.com/pricing.html) for license options. Single tool license from $2.99/mo or $9.99 lifetime.

---

## Preview

<p align="center">
  <img src="screenshot/en.png" alt="StylePatch Preview" width="640">
</p>

---

## Supported Browsers

| Browser | Status | Minimum Version |
|---------|--------|-----------------|
| Google Chrome | ✅ Fully supported | Chrome 95+ |
| Microsoft Edge | ✅ Fully supported | Edge 95+ |
| Other Chromium-based browsers | ✅ Basic compatible | Install via official extension store only |

---

## Installation

For your safety, only install StylePatch through official browser extension stores:

1. Open **Chrome Web Store** or **Microsoft Edge Add-ons**
2. Search: `StylePatch`
3. Click **"Add to Chrome"** / **"Add to Edge"**
4. Click the StylePatch icon in your toolbar to start

> ⚠️ Do not install from third-party websites. Unauthorized versions may compromise your data security.

---

## Usage

1. Click the **StylePatch icon** in your browser toolbar
2. **Pick colors** — Use the native color picker or type a hex code
3. **Choose a preset** — Light, Warm Tone, Green, Dark, Sepia, Night Blue, or High Contrast
4. **Adjust font size** — Drag the slider from 80% to 150%
5. **Choose a font** — Pick a system font, or load a Google Font from the web
6. **Apply a filter** — Optional grayscale or warm eye-care tint
7. **Save** — Click **Apply & Save** to persist settings for this site
8. **Reset** — Click ↺ to remove the site's own config; with a default theme saved, the site falls back to it
9. **Set as default** — Pro users can save the current colors as the default theme for every site (sites with their own config keep it)
10. **Exclude** — Click "Exclude this site" to blacklist a domain
11. **Toggle** — Use the ON/OFF switch to disable without losing settings

### Config Manager

Click **⚙ Config Manager** at the bottom of the popup to open the configuration page:

- **View**, search and **delete** configured sites with their color and font settings
- **Export** all configurations as a JSON backup file (free)
- **Import** a backup file to restore settings on another device or after reinstalling (free imports are capped at 5 sites)
- **Cloud Sync** (Pro) — mirror configs across Chrome/Edge profiles signed in to the same browser account
- **Default Theme** (Pro) — review or remove the theme applied to sites without their own config

---

## FAQ

1. **Styles don't take effect after adjustment?**
   Close other similar extensions (dark mode / eye-care) that may conflict, then refresh the page.

2. **Saved settings disappear after reopening the browser?**
   Make sure you clicked "Apply & Save". If using incognito mode, enable StylePatch permission for private windows.

3. **How do I transfer my settings to a new device?**
   Open Config Manager (⚙), click Export to download a backup file, then Import it on the new device. Free imports restore up to 5 sites; Pro restores everything. Within the same Chrome/Edge account, Pro users can also enable Cloud Sync and skip the file entirely.

4. **Why do `www.example.com` and `example.com` share the same settings?**
   That's intentional — domains are matched regardless of the leading `www.`, so your style applies consistently on both addresses.

5. **Can't find StylePatch on the extension store?**
   Check your network region. You can find the official store link at [www.annmax1983.com](https://www.annmax1983.com).

---

## Privacy

StylePatch follows privacy-by-design principles and collects zero user data:

1. **Permissions requested** — only three:
   - `storage`: Saves your custom colors, font size, site blacklist and theme preferences. Local data uses `chrome.storage.local`; the optional Pro Cloud Sync uses `chrome.storage.sync`.
   - `scripting`: Used only to inject the generated CSS into the current tab (in the extension's isolated world). It does not read page content or execute remote code.
   - `host_permissions`: Only used to inject custom CSS styles to adjust page appearance. Does not read DOM text, images, cookies, login credentials or form data.

2. **No tracking** — No browsing history access, no embedded third-party trackers, no analytics.

3. **Data stays local unless you opt in** — Configuration data exists on your device by default. Data leaves your browser only when you:
   - manually export a backup file;
   - enable Cloud Sync (Pro), which stores only site configs, the blacklist, the on/off toggle and the default theme in your browser account via `chrome.storage.sync` — never license keys or browsing data;
   - pick a Google Font (the font file is downloaded from fonts.googleapis.com);
   - activate or validate a license (the license key, a random install ID and basic browser metadata are sent to `api.annmax1983.com`).

- [Full Privacy Policy](https://annmax1983.github.io/StylePatch/privacy-policy.html)
- [Supplementary Privacy Details](https://www.annmax1983.com)

---

## Copyright Disclaimer

1. This extension only locally adjusts the visual rendering style of web pages for comfortable reading. All text, images and content copyright of each website belong to its respective publisher.
2. Modifying page display styles does not grant users any copyright authorization of website content. Users are strictly prohibited from using this extension to bypass website paywalls, membership restrictions, or anti-copy protection mechanisms.
3. Users shall comply with local laws and platform terms of service when using this extension. Any illegal use shall be borne by the user.

---

## Source Code Notice

> ⚠️ **This repository does not publish source code.** It contains only usage documentation, release notes, and support resources. The extension is distributed exclusively through the Chrome Web Store. No offline installation packages or end-user source code are provided.

---

## License

Copyright © 2026 StylePatch. All rights reserved.

This software is closed-source proprietary software. Without official written authorization, the following are strictly prohibited:
- Decompiling, cracking, or modifying the program code
- Repackaging, redistribution, sharing, or commercial resale
- Embedding the program into other software for bundled distribution

Violators will bear corresponding legal liabilities.

---

## ❤️ Support

If you find StylePatch helpful, consider buying the developer a coffee!

**[👉 Click here to support](https://ko-fi.com/annmax?buyACoffee=true&ref=stylepatch)**
