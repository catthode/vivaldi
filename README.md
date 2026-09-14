# Catthode for Vivaldi

<p align="center">
  <img src="https://cattho.de/assets/icon.png" alt="Catthode Icon" width="128" />
</p>

> **From CRT to OLED.** Bringing warmth back to a world of cold themes. [cattho.de](https://cattho.de/)

Catthode is a high-contrast, retro-futuristic theme designed for prolonged browsing sessions. It blends the crushed blacks of modern OLED displays with the comforting, warm glow of analog tungsten filaments.

## 🎨 Color Palette

### Surface
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Base** | `#000000` | Browser window, tab bar background |
| **Text** | `#ffffff` | Primary text |
| **Highlight** | `#ffb86c` | Active elements, selection (Gold) |

## 📦 Installation

### Recommended

1.  **Install directly** from the [Vivaldi Themes Store](https://themes.vivaldi.net/themes/wOkJy5aAJmd/).

### Manual

1.  **Download** the latest `catthode.zip` from the [Releases page](https://github.com/catthode/vivaldi/releases).

2.  **Open Vivaldi** and go to **Settings** > **Themes**.

3.  Click the **Open Theme** button (usually located near the theme library or import section).

4.  Select the `catthode.zip` file.

The theme should now be imported and active.

## Local profile snapshot

`extensions.json` records the Chrome Web Store extensions enabled in the active Vivaldi profile, including IDs and versions. `profile-settings.json` records the UI-only Vivaldi preferences captured from that profile: Catthode theme data, tab/address-bar visibility, toolbars, panels, saved layouts, and related display settings.

The nix-darwin setup uses the extension IDs to seed Vivaldi's Chromium `External Extensions` directory and applies the UI snapshot only when Vivaldi is closed. Browsing data, bookmarks, cookies, passwords, sync credentials, and extension storage are intentionally excluded.
