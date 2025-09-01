# ⚡ XL4015 5V/5A USB Power Supply Module  

![Project Logo](https://img.shields.io/badge/DIY-XL4015%20USB%20Power%20Supply-blue?style=for-the-badge&logo=usb&logoColor=white)  
![Made with EasyEDA](https://img.shields.io/badge/PCB-EasyEDA-green?style=for-the-badge&logo=autodesk&logoColor=white)  
![License](https://img.shields.io/badge/License-OpenSource-yellow?style=for-the-badge)  

A compact and powerful **USB power supply** based on the **XL4015 buck converter IC**.  
Designed to deliver **stable 5V up to 5A** — perfect for powering **Raspberry Pi, ESP32, Arduino, and USB gadgets**.  

---

## ✨ Features
- 🔌 **Input Voltage**: 8V – 36V DC  
- ⚡ **Output Voltage**: Fixed 5V  
- 🔋 **Maximum Current**: 5A continuous  
- 🔒 **Reverse Polarity Protection** (SS1045 Schottky)  
- 📊 **Stable Output** with 330 µF electrolytic + ceramic capacitors  
- 🟢 **Power LED Indicator**  
- 🖥️ **USB-A Output Port** (5V)  
- 🐧 Tested with **Raspberry Pi 4** – no undervoltage warnings  

---

## 🧰 Bill of Materials (BOM)

| No. | Quantity | Component | Value / Part No. | Package | Notes |
|-----|----------|-----------|------------------|---------|-------|
| 1   | 1  | IC  | XL4015E1  | TO-263-5 | Buck regulator |
| 2   | 1  | Inductor | 47 µH / 6A | SMMS1360 | Power inductor |
| 3   | 1  | Diode | SS1045 | SMC | Schottky rectifier |
| 4   | 1  | Capacitor | 220 µF / 50V | Electrolytic | Input filter |
| 5   | 1  | Capacitor | 330 µF / 25V | Electrolytic | Output filter |
| 6   | 3  | Capacitors | 1 µF | 1206 SMD | Ceramic |
| 7   | 1  | Capacitor | 33 nF | 1206 SMD | Loop compensation |
| 8   | 2  | Resistors | 3.3k, 10k | 1206 SMD | Voltage feedback |
| 9   | 1  | Resistor | 330 Ω | 1206 SMD | LED current limit |
| 10  | 1  | LED | Green SMD | 1205 | Power indicator |
| 11  | 1  | USB Connector | USB-A Female | Through-hole | Output port |
| 12  | 1  | DC Jack | 5.5mm barrel | Through-hole | Input connector |

---

## 🔎 Circuit Diagram
📷 *Schematic (EasyEDA)*  

![Schematic](images/schematic.png)  

---

## 🖼️ PCB Preview
3D render of the finished board:  

![3D View](images/xl4015_usb_3d.png)  

PCB layout (top copper):  

![PCB Layout](images/xl4015_USB_layout.png)  

---

## 🧪 Use Cases
- 🐧 Power **Raspberry Pi 3/4** (stable 5V/5A supply)  
- ⚡ Supply **ESP32, Arduino, STM32 projects**  
- 💡 Power **5V LED strips**  
- 📱 Charge USB-powered gadgets (phones, tablets)  
- 📡 Use with routers, SBCs, or dev kits  

---

## 🚀 Future Improvements
- 🔋 Add **USB D+/D– resistor divider** for **fast charging (up to 2A)**  
- 🔒 Replace Schottky diode with **P-MOSFET reverse polarity protection** for higher efficiency  
- 🔥 Add a **polyfuse** on USB output for overcurrent protection  
- 📏 Optional: make a **multi-output version (5V/9V/12V)** with multiple XL4015s  

---

## 📝 License
This project is **open-source hardware** 🛠️.  
You’re free to use, modify, and improve it — just give credit when sharing ❤️.  

---

## 👨‍💻 Author
Designed by **ElectroI.T.in**  
🔗 [Website](https://electroI.t.in) | 🐙 [GitHub](https://github.com/) | 📝 [Instructables](https://www.instructables.com/)  

---

✨ *If you like this project, don’t forget to ⭐ star the repo and share it with fellow makers!* ✨
