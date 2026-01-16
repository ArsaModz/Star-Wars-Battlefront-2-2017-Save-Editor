# 🌌 Star Wars Battlefront 2 (PS4) Save Editor

A modern, high-performance save data editor for **Star Wars Battlefront 2 (2017)** on PS4. This tool allows players to bypass console limitations by modifying hidden graphics, display, and gameplay settings directly within the save file.

Created by **ArsaModz**, this editor features a sleek "Dark Mode" interface built with PyQt6, providing a user-friendly way to optimize your game's performance and visuals.

---

## ✨ Key Features

### 🖥️ Display & FOV Enhancements

* **Custom Field of View (FOV):** Unlock FOV ranges from 55 (Default) up to 110 (Max). Recommended setting of 90 is easily accessible.
* **Resolution Scaling:** Toggle between standard 1080p and a simulated 4K (2.0x) scale.
* **Gameplay Toggles:** Easily enable or disable Atmospheric Effects, Vertical Sync, and Loadout Presets.

### 🎮 Advanced Graphics Control

Gain access to PC-like graphics settings on your console:

* **Quick Presets:** Apply "All Low" to "All Ultra" settings with a single click.
* **Granular Adjustments:** Individually modify Terrain Quality, Texture Filtering, Shadow Quality, Ambient Occlusion, Mesh Quality, and more.
* **Anti-Aliasing:** Control Post-Process Anti-Aliasing levels.
* **Custom Profiles:** Set "Overall Graphics Quality" to Custom to unlock individual setting overrides.

---

## 🚀 How to Use

1. **Extract your Save:** Use your preferred method to transfer your BF2 save data from your PS4 to your PC.
2. **Open the Editor:** Run `main.py` or the compiled executable.
3. **Load Data:** Click **"Open Save"** and select your `data` file.
4. **Modify:** Adjust your FOV, graphics, and gameplay settings across the two tabs.
* *Note: To use advanced graphics, ensure "Overall Graphics Quality" is set to "Custom".*


5. **Save:** Click **"Save Changes"** to write the hex values back to the file.
6. **Transfer Back:** Move the modified save back to your PS4 and enjoy!

---

## 🛠️ Technical Details

* **GUI Framework:** PyQt6 (Python)
* **Styling:** Custom QSS (Modern Dark Theme)
* **File Handling:** Direct bytearray manipulation of binary save data via specific hex offsets (e.g., FOV at `0x25B`, VSync at `0x4A5`).

## ⚠️ Disclaimer

This tool is intended for educational and personal use only. Always create a backup of your original save file before making modifications. Modifying save data may result in unexpected behavior or file corruption if not handled carefully.
