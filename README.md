# 🌵 RDR2 Physics & Immersion Overhaul (Ultimate Realism)

> **Experience Red Dead Redemption 2 like never before.** A powerful, highly-optimized gameplay and physics enhancement built to deliver hyper-realistic survival mechanics, dynamic immersion, and smooth control over your Wild West journey.

---

## 🔥 Key Features

* 🏹 **Hyper-Realistic Physics & Mechanics:** Elevates the game's core physical interactions, ragdoll behaviors, and movement systems to a whole new level of realism.
* ⛺ **Dynamic Survival Actions:** Seamlessly execute survival commands and camp management with intuitive hotkey combinations.
* ⚙️ **Auto-Generated Configuration:** Generates `UltimateRealism.ini` automatically upon first launch to allow custom tweaks tailored to your playstyle.
* 🚀 **Lightweight & High Performance:** Written in optimized C# utilizing `.NET` framework to ensure 0% FPS drop and zero impact on overall stability.

---

## 🎮 Controls & Hotkeys

| Action | Combination / Key |
| :--- | :--- |
| **Hide Status Bar** | `FrontendSelect` |
| **Drink Action** | `Reload` + `Jump` |
| **Eat Action** | `Reload` + `Duck` |
| **Camp Interaction** | `H` |
| **Unpack Camp / Actions** | `G` |

---

## 🛠️ Installation Guide

### Prerequisites
Make sure you have the following loaded into your main game directory:
1. **ScriptHookRDR2**
2. **ScriptHookRDRDotNet**

### Setup Steps
1. Download the latest release `.dll` file from the repository.
2. Move `UltimateRealism.dll` into your `<RDR2>\scripts\` directory.
3. Launch the game! The configuration file `UltimateRealism.ini` and execution log `UltimateRealism.log` will be created automatically.

---

## 🛠️ Building from Source

If you want to modify or compile the project yourself:

```bat
dotnet build -c Release
copy bin\UltimateRealism.dll "<RDR2>\scripts\"
