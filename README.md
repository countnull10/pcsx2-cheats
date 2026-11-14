# PCSX2 Cheats & Patches

A collection of custom `.pnach` cheat files, memory patches, and mods for PlayStation 2 games, created and tested by me.

---

## 🎮 Available Patches

| Game | Game ID | CRC | Description |
| :--- | :--- | :--- | :--- |
| **Devil May Cry** | `SLES-50358` | `7D8F539A` | All Abilities, Devil Skin, Flight, Sparda DT, All Weapons, etc. |
| **Devil May Cry 2** | `SLES-82011` | `6D9F918C` | Shin Majin Form, Infinite DT, Infinite Jumps, All Weapons, etc. |

---

## 🛠️ How to Install (PCSX2)

### Method 1: Automatic / Built-in Cheat Engine (PCSX2 v1.7+)
1. Open **PCSX2** and launch the game at least once.
2. Right-click on the game in your game list and select **Properties**.
3. Go to the **Cheats** tab.
4. Click **Open Cheats Folder** at the bottom.
5. Copy the `.pnach` file (e.g., `GAMEID_CRC.pnach`) directly into that folder.
6. Make sure **Enable Cheats** is checked under `System > Enable Cheats` or in the game properties menu.

### Method 2: Manual Setup
1. Locate your PCSX2 installation directory (or `%DOCUMENTS%\PCSX2\cheats` on Windows).
2. Download the `.pnach` file for your game version from this repository.
3. Place the file inside the `cheats` folder.
4. Boot your game and enable cheats from the PCSX2 main menu (`System > Enable Cheats`).

---

## ⚠️ Notes & Compatibility
- **CRC Matching:** Ensure your game's CRC matches the filename (e.g., `GAMEID_CRC.pnach`). Different game regions (PAL, NTSC-U, NTSC-J) have different CRCs and memory addresses.
- **Game-Specific Behaviors:** Check the `description=` field inside each `.pnach` file before enabling cheats, as some patches alter game mechanics or have intentional side effects (e.g., disabling pause menus or prioritizing specific forms).

---

## 🔗 Links & Socials
- 📺 **YouTube Channel:** [@countnull10](https://www.youtube.com/@countnull10)
- 💬 **Support & Issues:** If you find bugs or want to report an issue, feel free to open an issue in this repository.

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).
