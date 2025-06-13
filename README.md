<p align="center">
  <img src="assets/banner.png" alt="Audio Amplifier Banner" width="100%">
</p>

<h1 align="center">🎧 Analog Audio Amplifier with 3-Band Tone Control</h1>

<p align="center">
  Built with ❤️ using analog electronics and TDA2003A<br>
  <strong>Bass • Mid • Treble | Pure Class AB Sound</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Technology-Analog-blueviolet?style=for-the-badge" alt="Tech Badge">
  <img src="https://img.shields.io/badge/Amplifier-TDA2003A-red?style=for-the-badge" alt="Amp Badge">
  <img src="https://img.shields.io/badge/Project%20Type-Hardware-yellowgreen?style=for-the-badge" alt="Hardware Badge">
  <img src="https://img.shields.io/badge/Tone%20Control-3--Band-orange?style=for-the-badge" alt="Tone Badge">
</p>

---

## 🔊 Overview

A **fully analog, 3-band tone-controlled amplifier** designed around the **TDA2003A** IC. This project combines classic analog design techniques with user-friendly tone control to deliver **customizable, high-quality audio output**.

> ✅ Ideal for DIY audio systems, speaker builds, and analog audio enthusiasts.

---

## 🖼️ Gallery

<p align="center">
  <img src="assets/front_view.jpg" width="30%" alt="Front View"/>
  <img src="assets/tone_control.jpg" width="30%" alt="Tone Control"/>
  <img src="assets/power_stage.jpg" width="30%" alt="Power Stage"/>
</p>

---

## 🧩 Block Diagram

<p align="center">
  <img src="assets/block_diagram.png" width="70%" alt="Block Diagram"/>
</p>

---

## 🎛️ Features

- 🎚️ **3-Band Active Tone Control** (Bass, Mid, Treble)
- 🔉 **Class AB Power Amplification** using TDA2003A
- ⚙️ **Discrete Analog Design** – No digital processing
- 🔊 **Up to 10W Output @ 12V**
- 💡 Ideal for learning analog electronics and audio circuits

---

## 📐 Circuit Schematics

### 🎨 Tone Control Section
> Built using TL072/NE5532 op-amps with RC filters for frequency shaping.

<p align="center">
  <img src="assets/tone_control_schematic.png" width="80%" alt="Tone Schematic">
</p>

### 🔌 Power Amplifier Section
> Based on the TDA2003A for Class AB drive with thermal and short-circuit protection.

<p align="center">
  <img src="assets/power_amp_schematic.png" width="80%" alt="Power Amp Schematic">
</p>

---

## 📦 Bill of Materials

| Component        | Value / Part No       | Function                       |
|------------------|------------------------|--------------------------------|
| Op-Amp IC         | TL072 / NE5532         | Tone Control Amplification     |
| Power Amp IC      | TDA2003A               | Power Amplifier                |
| Potentiometers    | 10kΩ/50kΩ (x3)         | Bass, Mid, Treble Adjustments  |
| Capacitors        | 10nF – 470µF           | Coupling, Filtering            |
| Resistors         | 1kΩ – 100kΩ            | Biasing, Filter Control        |
| Power Supply      | 12V @ 2A               | Input Power                    |

---

## 📊 Performance

| Metric              | Value                  |
|---------------------|------------------------|
| Output Power        | ~10W @ 4Ω              |
| Frequency Range     | 20Hz – 20kHz           |
| Total Harmonic Distortion (THD) | < 0.2%    |
| Signal-to-Noise Ratio | > 75dB               |

---

## 🧪 Testing Setup

<p align="center">
  <img src="assets/testing_setup.jpg" width="70%" alt="Testing Setup">
</p>

---

## 🧑‍🤝‍🧑 Meet the Team

| Name             | Role                          |
|------------------|-------------------------------|
| **Banuka Liyanage** | Analog Design, Schematic, PCB |
| Teammate 1       | Tone Control Research & Testing |
| Teammate 2       | Assembly, Troubleshooting     |

---

## 📁 Repository Structure

```plaintext
📦 Audio-Tone-Control-Amplifier
 ┣ 📂 assets/
 ┃ ┣ 📄 banner.png
 ┃ ┣ 📄 tone_control.jpg
 ┃ ┣ 📄 power_stage.jpg
 ┃ ┣ 📄 block_diagram.png
 ┃ ┗ 📄 testing_setup.jpg
 ┣ 📂 hardware/
 ┃ ┣ 📄 schematic.pdf
 ┃ ┗ 📄 pcb_layout.pdf
 ┣ 📄 README.md
 ┣ 📄 LICENSE
📜 License
This project is licensed under the MIT License. You are free to use, modify, and distribute this project with attribution.

🌟 Show Your Support
If you like this project:

⭐ Star the repo

🛠️ Fork and improve

📣 Share with fellow audio enthusiasts

<p align="center"> <img src="assets/wave_banner.png" width="100%" alt="Thank you banner"> </p> ```
