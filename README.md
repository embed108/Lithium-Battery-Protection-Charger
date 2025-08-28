# Lithium Battery Protection & Charger PCB

This repository contains the design files for a **Lithium-ion battery charger and protection circuit PCB**, designed in **KiCad**.  
It includes schematic, PCB layout, 3D renders, and Gerber files for fabrication.

---

## 📐 Project Overview
- **Battery Type:** Single-cell 18650 Li-ion battery
- **Charging Port:** USB-C
- **Charging IC:** TP4056 (linear Li-ion charger with protection)
- **Battery Protection:** DW01A + FS8205A MOSFET
- **Indicators:** Charging, Full, and Status LEDs
- **Mounting:** 4 × mounting holes for secure fitting

---

## 📂 Repository Contents
- `Gerber_LithiumBatteryProtectioncharger.zip` → Fabrication files
- `Schematic.png` → Complete circuit schematic
- `PCB.png` → PCB layout (2D view)
- `3D_1.png` → 3D render (top view)
- `3D_2.png` → 3D render (bottom view)

---

## ⚡ Circuit Features
1. **Charging Circuit**  
   - Based on TP4056 IC with programmable current.  
   - Micro-USB/USB-C input for charging.  

2. **Battery Protection Circuit**  
   - DW01A + FS8205A for overcharge, over-discharge, and short-circuit protection.  

3. **LED Indicators**  
   - Red LED → Charging  
   - Green LED → Fully charged  
   - Additional status LED  

---

## 🚀 How to Manufacture
1. Download `Gerber_LithiumBatteryProtectioncharger.zip`.
2. Upload it to a PCB manufacturer (e.g., JLCPCB, PCBWay).
3. Select:
   - 2 Layer PCB
   - Thickness: 1.6 mm
   - Copper: 1 oz
   - Surface Finish: HASL or ENIG
4. Place order.

---

## 🛠 Tools Used
- **EDA Tool:** KiCad
- **Design Author:** EmbedGyaan – Learn Code & Circuits

---

## 📜 License
This project is open-source. You may use, modify, and distribute under the **MIT License** (or replace with CERN OHL for hardware-specific licensing).

---
