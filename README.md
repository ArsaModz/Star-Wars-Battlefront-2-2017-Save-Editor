It looks like there’s a **mismatch** between the description you posted and the code you uploaded:

* **Your text:** *Tales of Arise Save Editor (PS4)*
* **Your code (`main.py`):** *Star Wars Battlefront II (2017) Save Editor (PS4)*
  (FOV, resolution scale, graphics quality, AA, presets, etc.)

To help you move forward cleanly, here’s a **corrected README** that accurately reflects what your uploaded code actually does. You can drop this straight into a `README.md`.

---

# Star Wars Battlefront II (2017) Save Editor – PS4

A modern, GUI-based save editor for **Star Wars Battlefront II (2017)** on PlayStation 4, developed by **ArsaModz**.
Built with **Python + PyQt6**, this tool allows you to edit display settings, field of view, and advanced graphics quality options directly from a decrypted PS4 save file.

---

## 🚀 Features

### 🎥 Display & FOV Controls

* **Global FOV Editor**

  * Presets from **55 (Default)** up to **110 (Max)**
  * Recommended **90 FOV** included
* **Resolution Scale**

  * Default (1080p)
  * Max (4K scaling)

### 🎮 Gameplay & Display Toggles

* Atmospheric Effects (On / Off)
* Vertical Sync (VSync) (On / Off)
* Loadout Presets (On / Off)

---

## 🎨 Graphics Quality Editor

### 🔘 Quick Presets

* Set All **Low**
* Set All **Medium**
* Set All **High**
* Set All **Ultra**

### ⚙️ Advanced Graphics Settings

Individually editable quality options:

* Undergrowth Quality
* Sky Celestial Quality
* Debris Quality
* Terrain Quality
* Texture Filtering
* Shadow Quality
* Effects Quality
* Lighting Quality
* Ambient Occlusion
* Texture Quality
* Mesh Quality
* Terrain Groundcover
* Post Processing Quality

Additional options:

* **Anti-Aliasing Post**
* **Overall Graphics Quality**

  * Auto, Low, Medium, High, Ultra, Custom
    *(Custom required for manual overrides)*

---

## 🛠️ Requirements

* **Decrypted PS4 Save File**

  * Typically extracted using Save Wizard or equivalent tools
* **Python 3.10+**
* **PyQt6**

---

## 📖 How to Use

1. **Open Save**

   * Click **Open Save** and select your decrypted `*data` file
2. **Edit Settings**

   * Adjust FOV, resolution, toggles, and graphics options
3. **Save Changes**

   * Click **Save Changes**
4. **Re-sign Save**

   * Encrypt and re-sign the save for PS4 use

---

## ⚠️ Disclaimer

* Always **back up your save file** before editing.
* This tool is for **educational and personal use only**.
* Improper edits may corrupt your save.

---

**Developed by:** ArsaModz
