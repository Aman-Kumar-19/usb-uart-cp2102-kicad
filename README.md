# 🔌 USB to UART Converter (CP2102)

A professionally designed **USB to UART (TTL) converter PCB** developed using KiCad, based on the CP2102 USB bridge IC. This project demonstrates industry-standard hardware design practices for reliable USB communication and embedded system interfacing.

---

## 🚀 Features

* USB to TTL UART conversion (3.3V logic)
* CP2102 USB-UART bridge (no external crystal required)
* TX/RX activity indication using LEDs
* Compact 2-layer PCB design
* Optimized for embedded debugging and programming

---

## 🧠 Design Methodology

The design is implemented following professional embedded hardware guidelines:

* **USB Signal Integrity**

  * Differential pair routing for D+ and D−
  * Short and matched trace lengths

* **Power Integrity**

  * Proper decoupling capacitors near IC power pins
  * Stable VBUS-based power design

* **Component Optimization**

  * Reduced BOM using CP2102 internal oscillator
  * Minimal and efficient external circuitry

* **Layout Considerations**

  * Functional block-based component placement
  * Ground plane for noise reduction

---

## 📸 Schematic
<img width="1335" height="921" alt="image" src="https://github.com/user-attachments/assets/9914595f-c0eb-455e-b532-356df6ea3ebd" />


---

## 🧾 PCB Layout

<img width="1496" height="874" alt="image" src="https://github.com/user-attachments/assets/8bcee33e-1254-4deb-aedf-4bc73c71897c" />


---

## 🧊 3D View

<img width="1557" height="791" alt="image" src="https://github.com/user-attachments/assets/1df55cb9-3606-40d5-888c-4e3e0692c365" />
<img width="1169" height="566" alt="image" src="https://github.com/user-attachments/assets/2c190ff2-c21d-4575-850c-221042fd7e6b" />


---

## 📦 Bill of Materials (BOM)

Available in `/BOM/bom.csv`

---

## 🛠️ Tools Used

* KiCad (Schematic + PCB Design)
* CP2102 Datasheet

---

## 🎯 Applications

* Embedded system debugging
* Microcontroller programming
* UART-based communication interfaces

---

## 📌 Key Learning Outcomes

* USB interface design fundamentals
* Differential signal routing
* Power integrity in PCB design
* Practical hardware implementation using KiCad

---

## 👨‍💻 Author

Aman Kumar


---
