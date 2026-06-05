# number-station-sounds
Number station sounds
# 📻 Web-Based Number Station Transmitter (Plug & Play)

An interactive, retro-styled web control panel designed to simulate historical shortwave cryptographic numbers stations. This repository is **fully operational and live**—all required audio assets (`.mp3`) for G03, E06, and E03 are already pre-loaded and ready to broadcast.

## 🚀 Launch Transmitter
You can use the simulator directly in your browser without installing anything:
👉 **[Open Live Radio Transmitter](https://slimecrafty.github.io/number-station-sounds/)**

---

## 🛠️ Features

- **100% Ready-to-Use:** No configuration needed. Open the link, and the transmitter works instantly.
- **Dynamic UI Translation:** Toggle the entire interface between **English** and **German** with a single click.
- **Smart Input Mapping:** Automatically translates human-readable text inputs into specific repository file requests in the background.
- **Audio Queue System:** Sequentially chains audio files with tight timing gaps (**600 ms**) for an authentic transmission feel.
- **Responsive Retro Design:** High-contrast terminal look matching the mysterious vibe of cold-war radio transmissions.

---

## 📡 Supported Station Profiles & Formats

The transmitter automatically handles the correct audio assets from this repository based on your text input:

| Station Profile | UI Language | Allowed Parameters / Text Inputs | Played `.mp3` File (Pre-loaded) |
| :--- | :--- | :--- | :--- |
| **G03** <br>*(German Language)* | **DE** <br> **EN** | `GONG` <br> `ACHTUNG` / `ATTENTION` <br> `TRENNUNG` / `SEPARATION` <br> `0-9` | `DE_GONG.mp3` <br> `DE_ACHTUNG.mp3` <br> `DE_TRENNUNG.mp3` <br> `DE_0.mp3` to `DE_9.mp3` |
| **E06** <br>*(English Man)* | **DE / EN** | `0-9` *(Strictly numbers only. Text parameters are automatically stripped out).* | `E_0.mp3` to `E_9.mp3` |
| **E03** <br>*(Lincolnshire Poacher)*| **DE** <br> **EN** | `MELODIE` <br> `MELODY` <br> `PAUSE` <br> `0-9` | `EN_GONG.mp3` <br> `EN_GONG.mp3` <br> `EN_TRENNUNG.mp3` <br> `EN_0.mp3` to `EN_9.mp3` |

---

## 💻 How to Use

1. **Select Language & Station:** Choose your preferred interface language and the target station profile from the dropdown menus. The transmitter will automatically load the correct default sequence.
2. **Modify Message:** Type your custom sequence into the command console using the allowed parameters listed above. 
3. **Broadcast:** Press **START TRANSMISSION** to begin the automated playback queue. Click **STOP** at any time to immediately abort the broadcast.

---
*Disclaimer: This project is created for educational, historical simulation, and art purposes only. All audio files have been normalized to a standardized volume level (**89.0 dB**) for consistent audio quality.*
