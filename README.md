# 🎯 Escape From Tarkov Cheat Menu

[![222186879-a88a267e-16ba-4532-85ec-8cb385737947.png](https://i.postimg.cc/HLYt5mw1/222186879-a88a267e-16ba-4532-85ec-8cb385737947.png)](https://postimg.cc/87YWQqXZ)
> ⚠️ This software is for **educational and research purposes only**.  
> Use at your own risk.

A fully-featured internal cheat for Escape From Tarkov designed to give players powerful ESP visuals, precise aimbot mechanics, and a smooth in-game experience. Built for developers, researchers, and curious minds who want to explore how game internals work.

---

## ✨ Key Features (Explained)

### 🔍 ESP (Wallhack)
See through walls like never before. Highlights:

- ✅ Player ESP (names, distance, health bars, skeletons)
- 💰 Loot ESP (filtered by rarity or type)
- 🧭 Extraction zone markers
- 🛠️ Adjustable colors, distance, and visibility checks

**How to use:**  
Press `Insert` to open the in-game menu. Toggle “ESP” section on. Use sliders to control distance and what types of objects you want to see.

---

### 🎯 Aimbot
Snap to enemy heads like magic (but customizable so it looks legit).

- 🎚️ Smooth aiming (to avoid looking suspicious)
- 🎯 Adjustable FOV circle
- 🧠 Bone targeting (head, chest, etc.)
- 👁️ Visibility check (won’t aim through walls if disabled)

**How to use:**  
Enable Aimbot in the menu. Hold `Right Mouse Button` (configurable) to activate aimlock. Adjust FOV and smoothness to your liking.

---

### 🔫 Weapon Mods

- ❌ No Recoil
- ❌ No Sway
- 🎯 Perfect Accuracy
- 🔫 Instant ADS

**How to use:**  
Toggle each feature under the “Weapon” tab in the menu. Combine with aimbot for laser-like precision.

---

### 🦶 Movement Tweaks

- 🏃 Speed Hack
- 🚀 Super Jump
- 🧱 No Fall Damage

**How to use:**  
Enable in the “Movement” section. Speed multiplier can be adjusted on a slider.

---

### 🧪 Experimental Features

> May not be stable in every version

- 🔎 Loot Through Walls (auto-loot key items)
- 🧊 Thermal Vision
- 📡 Radar Overlay (2D top-down map)

---

## 🛠 Installation Guide

> For Windows 10/11 x64 systems only.

### Requirements

- ✅ Visual Studio 2022
- ✅ .NET 6 SDK
- ✅ C++ Redistributables
- ✅ A Mono DLL injector (like [SharpMonoInjector](https://github.com/warxander/SharpMonoInjector))

### Steps

1. Clone the repo:

    ```bash
    git clone https://github.com/yourusername/eft-cheat.git
    cd eft-cheat
    ```

2. Build the solution in Visual Studio (`Release x64`).
3. Launch Escape From Tarkov and wait until you're in the main menu.
4. Run your injector as admin and inject the compiled DLL.
5. Press `Insert` to open the in-game menu.

> 🧠 Tip: Some injectors may require manual mapping or kernel-level access if BE/EAC is active.

---

А, понял тебя! Давай тогда обновим раздел **Controls** в самом `README.md`, чтобы он выглядел более информативно и красиво — как часть основного документа. Вот как может выглядеть улучшенная версия:

---

## 🎛 Controls

Below is a full list of default hotkeys for navigating and using the cheat in-game. All keys can be customized via the `config.json` file.

| 🔑 Key              | 🕹️ Action Description                             |
|---------------------|--------------------------------------------------|
| `Insert`            | Open / close the in-game menu                   |
| `Right Mouse Button`| Hold to activate aimbot                         |
| `F1`                | Toggle Player ESP on/off                        |
| `F2`                | Toggle Loot ESP on/off                          |
| `F3`                | Toggle No Recoil                                |
| `F4`                | Toggle Aimbot                                   |
| `F5`                | Toggle Speed Hack                               |
| `F6`                | Toggle Thermal Vision (experimental)            |
| `F7`                | Toggle Radar Overlay                            |
| `F8`                | Panic Button – disables all cheat functions     |
| `Delete`            | Fully unload the cheat from memory              |
| `Home`              | Save current settings to config file            |
| `End`               | Load saved settings from config file            |
| `Page Up / Page Down`| Navigate through item filters in the menu     |
| `Arrow Keys`        | Navigate menu (if mouse is disabled or buggy)  |
| `Escape`            | Exit menu without saving changes                |

> 💡 **Note:** These hotkeys are designed for quick toggling during a raid or in the lobby. You can edit or remap them in your `config.json` for maximum comfort.

---

Хочешь, я добавлю ещё блок с "Recommended Settings" или "Legit vs Rage" пресетами?
## 🔐 Safe Usage & Tips

- Always test in **offline mode** first.
- Use a **spoofed account** or alt.
- Avoid rage settings in online raids.
- Update offsets after each EFT patch.

---

## ❗ Disclaimer

This project is for **educational purposes only**.  
We do **not** encourage or condone cheating in multiplayer games.  
Using this code online **can get you banned**. You’ve been warned.

---

## 📄 License

Licensed under the MIT License.  
Feel free to fork, learn, or improve — just don’t sell it without credit 😉

---

<p align="center">
  Made with ❤️ for reverse engineering
</p>
