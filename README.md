# Star Wars Battlefront 2 (2017) Save Editor (PS4)

A modern, high-performance save editor for *Star Wars Battlefront 2 (2017)* on PS4, built with Python and PyQt6. This tool provides a graphical interface for modifying hidden engine parameters, display settings, and advanced graphical quality toggles that are typically inaccessible on console.

## 🚀 Key Features

### 🔭 Display & Field of View (FOV)

Break past console limitations with precise control over your visual perspective:

* **Custom FOV:** Adjust Global FOV from the default 55 up to 110.
* **Resolution Scaling:** Toggle between Default (1080p) and Max (4K) resolution scales.
* **Gameplay Toggles:** Enable or disable Atmospheric Effects, Vertical Sync (V-Sync), and Loadout Presets.

### 🎨 Advanced Graphics Suite

Fine-tune the Frostbite engine settings to prioritize performance or visual fidelity:

* **Quick Presets:** One-click buttons to apply "Low", "Medium", "High", or "Ultra" settings across all categories.
* **Granular Control:** Individually adjust over 13 specific graphical parameters, including:
* Lighting, Shadow, and Texture Quality.
* Terrain and Undergrowth detail.
* Ambient Occlusion and Post-Process Quality.
* Mesh and Effects quality.


* **Anti-Aliasing:** Specific controls for Post-Process Anti-Aliasing.

## 🖥 User Interface

The editor features a professional, dark-themed "IDE-style" interface:

* **Modern Aesthetics:** Deep charcoal backgrounds with neon cyan accents ("#00d4ff").
* **Responsive Design:** Fully scrollable settings menus and organized tabs for "Display / FOV" and "Graphics Quality".
* **Real-time Validation:** Categorizes save data automatically upon loading for safe editing.

## 🛠 Tech Stack

* **Language:** Python 3.x
* **Framework:** PyQt6 (GUI)
* **Binary Engine:** Direct `bytearray` manipulation of save data offsets.

## 📝 How to Use

1. **Load:** Open your decrypted PS4 save file (`data` files).
2. **Modify:** Use the tabs to adjust your desired FOV or Graphical settings.
3. **Note:** To apply individual advanced graphics changes, ensure the **"Overall Graphics Quality"** is set to **"Custom"**.
4. **Save:** Commit changes back to the save file for use on your console.

---

*Created by ArsaModz*
