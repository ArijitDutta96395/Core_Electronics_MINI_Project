# 🔊 Audio Amplifier Using Basic Components

![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Electronics-orange?style=for-the-badge)
![Contributors](https://img.shields.io/badge/Contributors-6-purple?style=for-the-badge)

---

## 📌 Project Overview
The **Audio Amplifier Using Basic Components** is designed to deliver **high-fidelity** sound output capable of driving speakers up to **150W**.  
This project was developed as part of the **EC-594 (Design-I Lab)** coursework at **Haldia Institute of Technology**.  
It is built using **discrete electronic components** such as **transistors, capacitors, resistors, and potentiometers**, ensuring high efficiency and minimal distortion.

---

## 🎯 Objectives
- ✅ Amplify low-level audio signals to high power levels.  
- ✅ Drive high-power speakers (up to 150W).  
- ✅ Maintain **low distortion** and **high sound clarity**.  
- ✅ Include **safety features** for reliability and durability.  

---

## 🛠 Components Used
| Component | Quantity | Purpose |
|-----------|----------|---------|
| **2SC5200 NPN Power Transistor** | 2 | Output stage high-power amplification |
| **BD139 NPN Transistor** | 2 | Driver stage |
| **BD140 PNP Transistor** | 1 | Push-pull configuration |
| **Resistors** | Multiple | Biasing, current limiting, feedback |
| **Capacitors** | Multiple | Filtering, coupling, smoothing |
| **Diodes (1N4007, IN5408)** | Multiple | Reverse polarity & surge protection |
| **Potentiometers (100k)** | 3 | Volume, bass, treble control |
| **Speaker (150W+)** | 1 | Output device |
| **Power Supply (24V DC)** | 1 | Main power source |
| **12-0-12 Transformer** | 1 | Dual polarity power supply |

---

## ⚙️ Working Principle
The amplifier works on a **Class AB Push-Pull Configuration**:
1. **Input Stage** – Coupling capacitors block DC, potentiometer controls volume.  
2. **Driver Stage** – BD139 & BD140 transistors handle positive/negative waveform halves.  
3. **Power Stage** – 2SC5200 power transistors boost current to drive the speaker.  
4. **Feedback Network** – Resistors stabilize and reduce distortion.  
5. **Safety Features** – Diodes protect against polarity reversal and voltage spikes.  

---

## 🛡 Safety Features
- **Overcurrent & Overvoltage Protection**
- **Thermal Protection**
- **Short-Circuit Protection**
- **Surge Protection**
- **Fuse Protection**
- **Reverse Polarity Protection**
- **Soft-Start Circuit**
- **Grounding & Isolation**

---

## 📐 Circuit Diagram
<p align="center">
  <img src="https://github.com/ArijitDutta96395/Core_Electronics_MINI_Project/blob/main/pic2.png" width="500"><br>
  <em>Fig 1: Audio Amplifier Testing Setup</em>
</p>

---

## 📊 Specifications
| Parameter | Value |
|-----------|-------|
| **Output Power** | Up to 150W |
| **Speaker Impedance** | 4Ω / 8Ω |
| **Supply Voltage** | 24V DC |
| **Transistor Type** | Bipolar Junction Transistors (BJT) |
| **Amplifier Class** | AB |
| **Frequency Response** | Full audio range |
| **Distortion** | Low |

---

## 🧪 Testing & Results
- ✅ Successfully drove a **150W speaker** with clear sound output.  
- ✅ Maintained stability under varying loads.  
- ✅ Demonstrated minimal distortion across full frequency range.  

---

## 👨‍💻 Contributors
| Name | Roll No. |
|------|----------|
| Arijit Dutta | 22/ECE/54 |
| Avijit Biswas | 22/ECE/60 |
| Abhijit Maity | L23/ECE/001 |
| Bikram Paul | 22/ECE/068 |
| Archisman Kundu | 22/ECE/51 |
| Dipon Das | 22/ECE/74 |

---

## 📚 References
- 📖 *The Art of Electronics* – Paul Horowitz & Winfield Hill  
- 📖 *Audio Power Amplifier Design Handbook* – Douglas Self  
- 🌐 [Electronics Tutorials](https://www.electronics-tutorials.ws/)  
- 🌐 [All About Circuits](https://www.allaboutcircuits.com/)  
- 📄 Datasheets:  
  - [2SC5200](https://www.onsemi.com/pdf/datasheet/2sc5200-d.pdf)  
  - [BD139](https://www.onsemi.com/pdf/datasheet/bd139-d.pdf)  
  - [BD140](https://www.onsemi.com/pdf/datasheet/bd140-d.pdf)  

---

## 📜 License
This project is licensed under the **MIT License** – you are free to use, modify, and distribute with attribution.

---

## 📷 Project Images
<p align="center">
  <img src="https://github.com/ArijitDutta96395/Core_Electronics_MINI_Project/blob/main/pic.jpeg" width="500"><br>
  <em>Fig 2: Audio Amplifier Assembled Circuit</em>
</p>

---

## 🚀 How to Use
1. Connect the **audio source** via AUX cable.  
2. Power the circuit using a **24V DC power supply**.  
3. Adjust **volume, bass, and treble** using potentiometers.  
4. Connect a **4Ω / 8Ω speaker**.  
5. Enjoy **high-quality amplified sound**.

---

### 💡 Future Improvements
- Add **Bluetooth audio input**.
- Integrate **digital volume control**.
- Add **LED VU meter** for real-time audio level display.

---

🔗 *Developed as part of EC-594 Design-I Lab, Dept. of ECE, Haldia Institute of Technology (2024–2025).*
