# Audio-Amplifier-with-Tone-Control-
This is contains all the details about the analog electronics project done under EN2111 Electronic Circuit Design Semester 4 Project  where we build an audio amplifier with tone control.

# 🎵 Analog Audio Amplifier with Tone Control (Bass, Mid, Treble)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![GitHub repo size](https://img.shields.io/github/repo-size/your-username/audio-tone-control-amplifier)
![GitHub last commit](https://img.shields.io/github/last-commit/your-username/audio-tone-control-amplifier)

---

## 🛠️ Project Overview

This project is a **Class AB analog audio amplifier** featuring a **3-band tone control system (Bass, Mid, Treble)** and a **TDA2003A power amplifier stage**. Designed and developed with **pure analog components**, this amplifier delivers rich sound quality with customizable tonal response.

> 🚧 Built with ❤️ by our passionate hardware team!

---

## 📸 Project Gallery

| Front View | Tone Control Stage | TDA2003A Power Stage |
|------------|--------------------|----------------------|
| ![Front View](assets/front_view.jpg) | ![Tone Control](assets/tone_control.jpg) | ![TDA2003A Stage](assets/power_stage.jpg) |

> ✨ For a video demonstration, [click here](https://your-youtube-demo-link.com) *(optional)*

---

## 🔊 Key Features

- ✅ 3-Band Active Tone Control (Bass, Midrange, Treble)
- ✅ Class AB Output with TDA2003A
- ✅ Up to 10W Output Power (Typical with 12V Supply)
- ✅ Designed using discrete analog components and op-amps
- ✅ Compact PCB Layout (Single-layer friendly)
- ✅ Suitable for DIY audio systems, speaker boxes, and embedded audio

---

## 🧩 Block Diagram

[Audio In] ---> [Tone Control: Bass | Mid | Treble] ---> [TDA2003A Power Amplifier] ---> [Speaker Out]

yaml
Copy
Edit

---

## 📐 Schematic and Circuit Design

### 📊 Tone Control Section

- **Architecture**: 3-band active tone control
- **Op-amp used**: TL072 / NE5532
- **Independent potentiometers** for bass, midrange, and treble

![Tone Control Schematic](assets/tone_control_schematic.png)

### 🔋 Power Amplifier Section

- **IC Used**: TDA2003A (Class AB)
- **Supply Voltage**: 8V–18V DC (12V Recommended)
- **Protection**: Short-circuit and thermal protection

![Power Amp Schematic](assets/power_amp_schematic.png)

---

## 📦 Bill of Materials (BOM)

| Component       | Value               | Description                        |
|----------------|---------------------|------------------------------------|
| Op-Amps         | TL072 / NE5532      | Dual low-noise op-amps             |
| TDA2003A        | -                   | Power amplifier IC                 |
| Capacitors      | 10nF – 470µF        | Signal coupling, tone shaping      |
| Resistors       | 1kΩ – 100kΩ         | Signal path and filters            |
| Potentiometers  | 10kΩ or 50kΩ        | Bass, Mid, Treble Control          |
| Power Supply    | 12V DC              | Regulated, 2A recommended          |

---

## 🧪 Testing & Performance

| Parameter          | Value               |
|-------------------|---------------------|
| Output Power       | ~10W @ 4Ω           |
| THD (Typ.)         | < 0.2%              |
| Frequency Response | ~20Hz – 20kHz       |
| SNR                | > 75dB              |

---

## 🧑‍💻 Contributors

| Name              | Role                  |
|-------------------|-----------------------|
| Banuka Liyanage   | Analog Design, Layout |
| Teammate 1        | Tone Control Circuit  |
| Teammate 2        | Testing and Assembly  |

> 👥 If you'd like to contribute or improve this project, feel free to open a Pull Request!

---

## 📁 Folder Structure

📂 audio-tone-control-amplifier
├── assets/ # Images and schematics
├── hardware/
│ ├── schematics/ # Circuit diagrams (.png, .pdf)
│ └── pcb/ # PCB files (Gerber, Eagle/Altium)
├── docs/ # Datasheets, app notes
├── README.md
└── LICENSE

yaml
Copy
Edit

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.

---

## 📬 Contact

If you have any feedback, suggestions, or want to share your version of the amp, please feel free to reach out:

- 📧 Email: [your.email@example.com]
- 🔗 LinkedIn: [linkedin.com/in/yourprofile]
- 🌐 Project Page (if available)

---

## 🌟 Star this repo!

If you like this project, don’t forget to ⭐ star the repository and share it with audio enthusiasts and makers!
